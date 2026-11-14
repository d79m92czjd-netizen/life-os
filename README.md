# LIFE OS 0.5.2 — Task Progress

PWA local-first para organización personal, hábitos, estudios, deporte y progreso.

## Novedades 0.5.2
- Gráfica circular animada en Inicio con el porcentaje real de tareas completadas.
- Desglose de tareas completadas, pendientes y totales.
- Mensajes dinámicos según el progreso registrado.
- El gráfico se actualiza al añadir, completar o eliminar tareas.
- Se conserva la clave local `life-os-v02` y la estructura de datos anterior.

## Publicación en GitHub Pages
1. Antes de actualizar, abre LIFE OS y usa Perfil → Exportar datos para guardar una copia JSON.
2. Descomprime este ZIP.
3. Sube `index.html`, `manifest.webmanifest`, `sw.js` y `README.md` a la raíz del mismo repositorio, sustituyendo los anteriores.
4. No cambies la configuración de GitHub Pages.
5. Abre la URL y recarga. La caché del service worker se renueva con esta versión.

## Privacidad y compatibilidad
- Los datos permanecen en `localStorage` del dispositivo.
- No se añaden servidores, cuentas, APIs ni dependencias externas.
- La clave de almacenamiento sigue siendo `life-os-v02`; no borres los datos del navegador.
- Haz una copia de seguridad antes de actualizar.
