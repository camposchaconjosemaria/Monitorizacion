# Opciones Detalladas del Comando `top`

El comando `top` proporciona una visión en tiempo real de los procesos que consumen más recursos. A continuación, se detallan algunas opciones más específicas:

| Opción         | Descripción |
|----------------|-------------|
| `c`            | Muestra la línea de comandos completas de los procesos. |
| `k`            | Permite enviar señales de terminación o señales personalizadas a los procesos. |
| `H`            | Agrupa los procesos por árbol de tareas, mostrando las jerarquías de los procesos. |
| `u`            | Filtra la salida para mostrar solo los procesos de un usuario específico. |
| `p`            | Filtra la salida para mostrar solo los procesos con ID de proceso (PID) especificados. |
| `i`            | Invierte la visualización, mostrando solo los procesos inactivos. |
| `o`            | Permite ordenar la tabla según el campo especificado. Ejemplo: `o %MEM` para ordenar por uso de memoria. |
| `F`            | Permite seleccionar los campos que se mostrarán y ordenarán. |
| `n`            | Establece el número de procesos mostrados. |
| `f`            | Abre el menú de campos para seleccionar los campos que se mostrarán. |
| `z`            | Alternar entre mostrar y ocultar los procesos que se han cerrado. |
| `E`            | Cambia entre la visualización de procesos y la visualización de hilos. |
| `W`            | Guarda la configuración actual en el archivo de configuración de `top`. |
| `q`            | Sale de `top`. |
