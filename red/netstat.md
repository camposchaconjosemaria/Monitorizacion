# Comando `netstat` - Visualización de Estadísticas de Red y Conexiones

El comando `netstat` muestra información sobre conexiones de red, tablas de enrutamiento, estadísticas de interfaz y más. A continuación, se detallan su uso básico y algunas opciones representativas:

| Opción         | Descripción |
|----------------|-------------|
| `-a`           | Muestra todas las conexiones y escucha en todos los puertos. |
| `-n`           | Muestra direcciones y puertos en formato numérico. |
| `-p`           | Muestra el identificador del proceso (PID) y el nombre del programa asociado. |
| `-t`           | Filtra las conexiones TCP. |
| `-u`           | Filtra las conexiones UDP. |
| `-l`           | Muestra solo las conexiones que están en estado de escucha. |
| `-r`           | Muestra la tabla de enrutamiento. |
| `-i`           | Muestra estadísticas de interfaz, incluyendo paquetes y bytes. |
| `-s`           | Muestra estadísticas detalladas de protocolo. |
| `-c`           | Muestra información continua. |
| `--numeric`    | Muestra direcciones y puertos en formato numérico. |
| `--verbose`    | Muestra información adicional, como nombres de host y programas. |
| `--help`       | Muestra la ayuda con una lista de todas las opciones disponibles. |

**Uso básico:**
- `netstat` muestra una lista de conexiones y estadísticas básicas.
- `netstat -tulpn` muestra todas las conexiones TCP con información detallada sobre los programas y sus identificadores de proceso (PID).
- `netstat -r` muestra la tabla de enrutamiento del sistema.

El comando `netstat` es una herramienta versátil para la visualización de estadísticas de red y conexiones, proporcionando opciones para adaptarse a diferentes escenarios de monitorización.
