# Comando `tcpdump` - Captura y Análisis de Tráfico de Red

El comando `tcpdump` permite la captura y análisis de tráfico de red. A continuación, se detallan su uso básico y algunas opciones representativas:

| Opción         | Descripción |
|----------------|-------------|
| `-i`           | Especifica la interfaz de red para capturar el tráfico. |
| `-n`           | Muestra direcciones IP y puertos en formato numérico. |
| `-c`           | Limita el número de paquetes a capturar. |
| `-s`           | Especifica la longitud de captura para cada paquete. |
| `-X`           | Muestra el contenido de los paquetes en formato hexadecimal y ASCII. |
| `-q`           | Muestra menos información para imprimir en un formato más compacto. |
| `port`         | Filtra paquetes basados en un puerto específico. |
| `host`         | Filtra paquetes basados en una dirección IP específica. |
| `expr`         | Permite expresiones más avanzadas para filtrar paquetes. |
| `tcp`          | Filtra paquetes TCP. |
| `udp`          | Filtra paquetes UDP. |
| `icmp`         | Filtra paquetes ICMP. |
| `protocolo`    | Filtra paquetes basados en un protocolo específico. |
| `archivo`      | Lee datos de un archivo en lugar de una interfaz de red. |
| `--help`       | Muestra la ayuda con una lista de todas las opciones disponibles. |

**Uso básico:**
- `tcpdump` muestra todos los paquetes en la interfaz especificada.
- `tcpdump -i eth0` captura paquetes solo en la interfaz eth0.
- `tcpdump -n -c 10 port 80` captura los primeros 10 paquetes HTTP.

El comando `tcpdump` es una herramienta poderosa para el análisis de tráfico de red, y estas opciones permiten una filtración flexible para enfocarse en paquetes específicos.
