# Comando `iostat` - Monitorización de Estadísticas de E/S

El comando `iostat` muestra estadísticas de entrada/salida (E/S) para dispositivos de bloque y CPU. A continuación, se detallan su uso básico y algunas opciones representativas:

| Opción         | Descripción |
|----------------|-------------|
| `-c`           | Muestra estadísticas de CPU. |
| `-d`           | Muestra estadísticas de dispositivos de bloque. |
| `-h`           | Muestra los resultados en un formato legible para humanos. |
| `-k`           | Muestra las estadísticas en kilobytes por segundo (KB/s). |
| `-m`           | Muestra las estadísticas en megabytes por segundo (MB/s). |
| `-N`           | Muestra estadísticas por dispositivo (nombre) en lugar de por número. |
| `-t`           | Muestra la hora junto con las estadísticas. |
| `-x`           | Muestra estadísticas extendidas, incluyendo estadísticas de dispositivos que no están realizando E/S. |
| `intervalo`    | Especifica el intervalo de tiempo entre actualizaciones. |
| `repeticiones` | Especifica el número de actualizaciones antes de detenerse. |
| `dispositivo`  | Muestra estadísticas solo para el dispositivo especificado. |
| `cpu`          | Muestra estadísticas solo para la CPU. |
| `--help`       | Muestra la ayuda con una lista de todas las opciones disponibles. |

**Uso básico:**
- `iostat` muestra estadísticas de resumen de CPU y E/S para todos los dispositivos.
- `iostat -c` muestra solo estadísticas de CPU.
- `iostat -d` muestra solo estadísticas de dispositivos de bloque.
- `iostat -h -k 1` muestra estadísticas legibles para humanos en KB/s con actualizaciones cada segundo.

El comando `iostat` es útil para monitorear el rendimiento de la CPU y los dispositivos de bloque, y estas opciones proporcionan flexibilidad para personalizar la presentación de la información.
