# Comando `df` - Monitorización de Espacio en Disco

El comando `df` muestra información sobre el espacio disponible y utilizado en los sistemas de archivos montados. A continuación, se detalla su uso básico y algunas opciones representativas:

| Opción         | Descripción |
|----------------|-------------|
| `-h`           | Muestra los resultados en un formato legible para humanos (KB, MB, GB). |
| `-B <unidad>`  | Define la unidad de medida para mostrar los resultados (B, K, M, G, T). |
| `--total`      | Muestra una línea adicional al final que resume el espacio total. |
| `--block-size` | Establece el tamaño del bloque para la visualización (1K, 1M, etc.). |
| `--output`     | Permite seleccionar los campos que se mostrarán en la salida. |
| `--type`       | Filtra los sistemas de archivos mostrados según el tipo (ext4, tmpfs, etc.). |
| `--help`       | Muestra la ayuda con una lista de todas las opciones disponibles. |

**Uso básico:**
- `df` muestra la información por defecto del espacio en disco para todos los sistemas de archivos montados.
- `df -h` muestra los resultados en un formato legible para humanos.
- `df -h /ruta` muestra la información específica para el sistema de archivos que contiene la ruta especificada.

El comando `df` es útil para evaluar la utilización del espacio en disco en el sistema y estas opciones proporcionan flexibilidad para personalizar la presentación de la información.
