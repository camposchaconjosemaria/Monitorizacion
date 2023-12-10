# Comando `tcptrack` - Seguimiento en Tiempo Real de Conexiones TCP

El comando `tcptrack` realiza el seguimiento en tiempo real de las conexiones TCP activas. A continuación, se detallan su uso básico y algunas opciones representativas:

| Opción         | Descripción |
|----------------|-------------|
| `-i`           | Especifica la interfaz de red para monitorear las conexiones. |
| `-r`           | Lee datos desde un archivo en lugar de una interfaz de red. |
| `-u`           | Muestra el tiempo de actividad y la cantidad de datos transferidos para cada conexión UDP. |
| `-d`           | Muestra el tiempo de inactividad de las conexiones. |
| `-p`           | Filtra conexiones basadas en un puerto específico. |
| `-l`           | Limita la cantidad de conexiones mostradas en la pantalla. |
| `-n`           | Muestra direcciones IP y puertos en formato numérico. |
| `-B`           | Muestra el ancho de banda total utilizado por todas las conexiones. |
| `-W`           | Ajusta el ancho de la columna para la dirección IP y el puerto. |
| `--help`       | Muestra la ayuda con una lista de todas las opciones disponibles. |

**Uso básico:**
- `tcptrack` muestra una lista en tiempo real de las conexiones TCP activas en la interfaz especificada.
- `tcptrack -i eth0` monitorea las conexiones solo en la interfaz eth0.
- `tcptrack -r archivo.pcap` analiza un archivo de captura previamente guardado.

El comando `tcptrack` es útil para obtener una visión rápida de las conexiones TCP en tiempo real y estas opciones proporcionan flexibilidad para personalizar la presentación de la información.
