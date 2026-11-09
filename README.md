# LIFE OS 0.3.1

PWA local-first para organización personal.

## Publicación
Sube el contenido de esta carpeta a la raíz del repositorio de GitHub Pages.

## Funciones de esta versión
- Dashboard con widgets adicionales configurables y reordenables.
- Widgets de objetivos, balonmano, gimnasio y estudios.
- Ajustes de recordatorios y prueba de notificación.
- Avisos locales de tareas/estudios con fecha de hoy y recordatorio diario de hábitos mientras la aplicación está abierta.
- Exportación/importación JSON y conservación de la clave local `life-os-v02` para compatibilidad con datos previos.

## Limitaciones importantes
- Los avisos se comprueban mientras LIFE OS está abierta. No hay servidor push ni suscripciones Web Push, por lo que no se garantizan avisos cuando la app está cerrada.
- En iPhone, instala la PWA desde Safari mediante Compartir → Añadir a pantalla de inicio y concede permiso desde la app instalada.
- Los widgets de pantalla de inicio de iOS (WidgetKit) no están disponibles en esta arquitectura PWA.
- Los datos siguen guardándose localmente en el navegador/dispositivo.


## Módulos funcionales 0.3.1
- Nutrición y recuperación: registro de sueño, hidratación, energía, recuperación y observaciones de comidas.
- Finanzas: registro manual de ingresos, gastos y ahorro.
- Desarrollo personal: diario de lectura, aprendizaje, concentración, movilidad y proyectos.
- Futuro e independencia: hoja de ruta con áreas, horizontes y tareas completadas.

Los datos se guardan localmente en el dispositivo. Conserva una copia exportada antes de cambiar de versión.
