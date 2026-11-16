# Backend LIFE OS AI (referencia)

Requiere Node.js 20+. No incluyas `.env` en GitHub.

## Configuración por una persona adulta responsable
1. Configura una cuenta de API y presupuesto/límites con supervisión adulta.
2. Copia `.env.example` a `.env`.
3. Define `OPENAI_API_KEY` solo en variables secretas del servidor. Nunca la pongas en `index.html`, GitHub Pages ni en el iPhone.
4. Genera un `LIFE_OS_ACCESS_TOKEN` aleatorio largo y privado. Este es el token que se introduce en la pantalla LIFE AI; no es la clave de OpenAI.
5. Configura `ALLOWED_ORIGIN` con el origen exacto de la PWA y usa HTTPS.
6. Despliega el servidor en una plataforma backend con secretos de entorno. No publiques el `.env`.

## Ejecución local
`npm start`

## Seguridad / limitaciones
- La API key solo se lee desde el entorno del servidor.
- Token Bearer para limitar el acceso; límite simple de 12 solicitudes/minuto por IP. Añade autenticación/limitación robusta del proveedor de hosting antes de producción.
- CORS no es autenticación. El token es obligatorio.
- La app envía únicamente el contexto permitido por los toggles; aun así, los datos autorizados salen del dispositivo.
- Las acciones se validan y ejecutan en el cliente solo tras pulsar Aprobar. El backend no recibe permiso para escribir en la base local.
- Este backend es una plantilla inicial, no una auditoría de seguridad ni una configuración lista para producción.
