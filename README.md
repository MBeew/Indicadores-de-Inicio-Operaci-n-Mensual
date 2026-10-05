# Control de Inicio Diario

Dashboard estático e interactivo para analizar la hoja **DATOS DE INICIO DIARIO** de los archivos diarios de operación.

## Publicarlo

1. Descomprime este archivo ZIP.
2. En Netlify, Vercel, GitHub Pages o cualquier hosting estático, publica el contenido de la carpeta `dist`.
3. Abre el sitio y selecciona el archivo Excel desde **Cargar archivo Excel**.

No necesita instalar programas, servidor, base de datos ni claves. El archivo Excel se procesa en el navegador y no se carga a ningún servidor.

## Archivo esperado

La herramienta usa únicamente la hoja `DATOS DE INICIO DIARIO`. Debe conservar estas columnas:

- FECHA
- FLOTA VINCULADA
- VEH EN OTRAS ACTIVIDADES
- REPARACIONES MAYORES
- VEH AL INICIO EN MTTO
- FLOTA DISPONIBLE POR MANTENIMIENTO
- FLOTA OPERATIVA
- VEH DISPONIBLE CON NOVEDAD
- % CUMPLIMIENTO MTTO
- % CUMPLIMIENTO OPERATIVO

El nombre de la columna `MES` puede estar presente, pero los filtros se calculan desde la fecha para evitar inconsistencias.
