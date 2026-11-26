# LIFE OS 1.0 — Performance Edition

Rediseño iPhone-first centrado en adherencia, rendimiento deportivo y estudios.

## Cambios principales
- Inicio convertido en un panel de rendimiento con accesos directos a planificación, balonmano y estudios.
- Check-in diario con racha de revisiones.
- Navegación simplificada: Inicio, Plan, Deporte, Estudios y Progreso.
- Recordatorio diario exportable a Calendario de iPhone mediante un archivo `.ics`.
- Se mantienen los módulos existentes y el almacenamiento local.
- Se conserva la clave `life-os-v02` para mantener los datos de versiones anteriores.

## Actualización
1. Exporta una copia JSON desde Perfil.
2. Sustituye los archivos publicados por los de este paquete.
3. Mantén la clave `life-os-v02`.
4. Publica los archivos y vuelve a abrir LIFE OS. La caché se ha actualizado a `life-os-v100`.

## Recordatorios en iPhone
Esta PWA local no puede garantizar avisos cuando está cerrada. Desde Perfil puedes generar un evento recurrente `.ics`; ábrelo en el iPhone y añádelo a Calendario para recibir un aviso diario a la hora elegida.

## Privacidad
Los datos permanecen en el almacenamiento local del navegador. No hay cuentas ni sincronización en la nube. Exporta copias periódicamente y no guardes contraseñas ni datos sensibles.
