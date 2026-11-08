# LIFE OS 0.2.0

## Funciones incluidas
- Dashboard y navegación Inicio / Agenda / Progreso / Perfil.
- Crear, completar y eliminar tareas; fecha opcional.
- Seguimiento de hábitos.
- Objetivos con horizonte y estado.
- Registro de entrenamientos/partidos de balonmano y evaluaciones personales.
- Registro de sesiones de gimnasio, series, repeticiones y carga.
- Registro de tareas y exámenes de estudio.
- Notas con título y contenido.
- Historial de actividad.
- Exportación e importación JSON.
- Tema claro/oscuro automático y estructura PWA.

## Probar
Abre `index.html` en un navegador. Para service worker e instalación PWA usa un alojamiento HTTPS o localhost.

## Instalar en iPhone
Publica los archivos en HTTPS, abre la URL en Safari, pulsa Compartir y selecciona Añadir a pantalla de inicio.

## Privacidad y limitaciones
Los datos se guardan en localStorage del navegador y no se envían a ningún servidor. Exporta copias periódicamente. No guardes contraseñas ni información sensible. No hay todavía cuenta, sincronización cloud, cifrado extremo a extremo, notificaciones push ni integraciones externas. Los módulos de nutrición/recuperación, finanzas, desarrollo personal y futuro están en la navegación pero pendientes de implementación profunda. El calendario avanzado y el Dashboard drag-and-drop también quedan para siguientes versiones.

## Actualizaciones
Al publicar una nueva versión, incrementa el nombre de caché en `sw.js` para que el service worker sustituya los archivos anteriores. Conserva la misma clave de almacenamiento `life-os-data-v2` para mantener los datos locales compatibles.
