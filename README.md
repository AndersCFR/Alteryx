# Alteryx

## Alteryx designer

Alteryx designer es uno de los suites para ingeniería de datos más utilizados, permite crear
ETLs a partir de operadores de tipo grag and drop.

### Input

- Si deseamos importar varios archivos a la vez podemos usar *

Ejemplo path: E:\Alteryx\Input_Output\*.csv

En este se inportarán todos los archivos csv del directorio en cuestión


- Podemos usar patrones: E:\Alteryx\Input_Output\sales_stores2*.csv

Para filtrar ciertos patrones podemos usar partes de los nombres

- Si deseamos distinguir de que archivo proviene cada dato, podemos agregar el campo "Output File Name as Field" que creará una nueva columna indicando el archivo origen.

- En el caso de subpaths que tengan archivos con el mismo nombre podemos habilitar la opción
"Search SubDirs"


### Macros
Las macros se usan para reutilizar flujos

Macro estándar:
Macro por lote: Se ejecuta varias veces hasta tene
Macro iterativa:
Macro del optimizador de ubicación:


## Procesamiento de datos geográficos

Operación generalizar: Generar un polígono más cóncavo, usa el algoritmo, Ramer-Douglas-Peucker
Operación suavisar (smooth): Genera un polígono más genérico con menos puntas, más redondo, usa el algoritmo B-spline