# Comando `iptraf` - Monitorización Interactiva de Red

El comando `iptraf` proporciona una interfaz interactiva para la monitorización de red. A continuación, se detallan su uso básico y algunas opciones representativas:

| Opción         | Descripción |
|----------------|-------------|
| `--color`      | Habilita el uso de colores para una presentación visual más clara. |
| `--noint`      | Inicia iptraf sin cambiar a la interfaz de texto completo. |
| `--filter`     | Permite filtrar la visualización de estadísticas por dirección IP o puerto. |
| `--port`       | Permite especificar un puerto para el filtrado. |
| `--lan`        | Muestra solo estadísticas de tráfico local de área de red (LAN). |
| `--detailed`   | Proporciona detalles adicionales, como la tasa de bits por segundo. |
| `--version`    | Muestra la versión de iptraf. |
| `--help`       | Muestra la ayuda con una lista de todas las opciones disponibles. |

**Uso básico:**
- `iptraf` inicia la interfaz interactiva que permite seleccionar diversas opciones de monitorización.
- `iptraf --color` habilita la presentación en color para mejorar la legibilidad.
- `iptraf --filter <direccion_IP>` filtra las estadísticas para mostrar solo el tráfico relacionado con la dirección IP especificada.

El comando `iptraf` es una herramienta interactiva y versátil para la monitorización de red en tiempo real, proporcionando diversas opciones para adaptarse a las necesidades específicas.
