# LIFE OS 0.5.0

PWA local-first para organización personal y seguimiento de progreso.

## Novedades 0.5.0
- Gráfica visual del volumen de entrenamiento con filtros de 7 días, 30 días y todo el historial.
- Resumen de sesiones, ejercicios y volumen estimado en el apartado Progreso.
- Registro de varios ejercicios dentro de una misma sesión de gimnasio.
- Cada ejercicio admite series, repeticiones, carga y notas opcionales.
- Historial de sesiones desplegable y cálculo orientativo del volumen (series × repeticiones × kg).
- Sistema de experiencia (XP), niveles y logros desbloqueables.
- Animaciones sutiles, transiciones, respuesta visual al guardar y soporte para reducir movimiento.
- Modo Focus oculto: toca cinco veces el logotipo LIFE OS para abrir un temporizador de concentración de 25 minutos.
- Los registros antiguos del gimnasio siguen mostrándose; se interpretan como sesiones de un solo ejercicio.

## Publicación en GitHub Pages
1. Descomprime el ZIP.
2. Abre el repositorio `life-os` en GitHub.
3. Entra en **Add file → Upload files**.
4. Sube y sustituye `index.html`, `manifest.webmanifest`, `sw.js` y `README.md`.
5. Pulsa **Commit changes** y espera a que GitHub Pages publique los cambios.
6. En iPhone, cierra y vuelve a abrir LIFE OS. Si ves la versión anterior, recarga la web instalada o ábrela una vez en Safari para que se actualice el service worker.

## Compatibilidad y datos
- Mantiene la clave local `life-os-v02`: conserva los datos de las versiones anteriores en el mismo navegador/dispositivo.
- No cambia el formato de los registros antiguos ni borra el almacenamiento.
- Exporta una copia JSON desde Perfil antes de actualizar, como precaución.
- Los datos siguen guardándose localmente; no hay sincronización en la nube.
- El volumen de entrenamiento es una estimación (series × repeticiones × kg) y no compara directamente ejercicios distintos.

## Limitaciones conocidas
- Los recordatorios se comprueban mientras LIFE OS está abierta; no hay servidor push.
- Los widgets nativos de pantalla de inicio de iOS no están disponibles en esta PWA.
- El temporizador Focus funciona mientras la página permanece abierta.
- La información de bienestar es un registro personal, no una valoración médica.
