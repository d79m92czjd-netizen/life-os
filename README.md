# LIFE OS 0.5.1 — Progress & Experience

PWA local-first para organización personal, hábitos, estudios, deporte y progreso.

## Novedades 0.5.1
- Panel de progreso con XP y niveles calculados a partir de tareas, hábitos, objetivos y sesiones de gimnasio.
- Registro de varios ejercicios por sesión de gimnasio (series, repeticiones y carga).
- Historial compatible con las sesiones de gimnasio del formato anterior.
- Gráficas SVG sin librerías externas: sesiones de los últimos 7 días y volumen estimado de entrenamiento.
- Animaciones ligeras y avisos visuales, respetando la preferencia de movimiento reducido del dispositivo.
- Se conserva la clave local `life-os-v02` y el formato de datos previo.

## Publicación en GitHub Pages
1. Antes de actualizar, abre LIFE OS y usa Perfil → Exportar datos para guardar una copia JSON.
2. Descomprime este ZIP.
3. Sube `index.html`, `manifest.webmanifest`, `sw.js` y `README.md` a la raíz del mismo repositorio.
4. No cambies la configuración de GitHub Pages.
5. Abre la URL y recarga. Si aparece la versión anterior, cierra la PWA y vuelve a abrirla tras unos minutos para que el nuevo service worker actualice la caché.

## Privacidad y compatibilidad
- Los datos permanecen en `localStorage` del dispositivo.
- No se añaden servidores, cuentas, APIs ni dependencias externas.
- La clave de almacenamiento sigue siendo `life-os-v02`; no borres los datos del navegador.
- Haz una copia de seguridad antes de actualizar.
