# Comando `du` - Monitorización de Uso de Espacio en Disco

El comando `du` muestra el uso de espacio en disco para archivos y directorios. A continuación, se detalla su uso básico y algunas opciones representativas:

| Opción         | Descripción |
|----------------|-------------|
| `-h`           | Muestra los resultados en un formato legible para humanos (KB, MB, GB). |
| `-s`           | Muestra el total utilizado por el directorio, sin detalles internos. |
| `-c`           | Muestra el total acumulado al final de la salida. |
| `--max-depth`  | Limita la profundidad máxima de visualización de directorios. |
| `--exclude`    | Excluye archivos o directorios específicos de los resultados. |
| `--time`       | Muestra la última modificación de archivos junto con el uso de espacio. |
| `--block-size` | Establece el tamaño del bloque para la visualización (1K, 1M, etc.). |
| `--help`       | Muestra la ayuda con una lista de todas las opciones disponibles. |

**Uso básico:**
- `du` muestra el uso de espacio en disco para archivos y directorios en el directorio actual.
- `du -h` muestra los resultados en un formato legible para humanos.
- `du -h -s /ruta/directorio` muestra el total utilizado por el directorio especificado.

El comando `du` es útil para identificar rápidamente qué archivos o directorios consumen más espacio en disco, y estas opciones proporcionan flexibilidad para personalizar la presentación de la información.
