# Opciones Detalladas del Comando `ps`

El comando `ps` muestra información de los procesos activos. A continuación, se detallan algunas opciones más específicas:

| Opción         | Descripción |
|----------------|-------------|
| `aux`          | Muestra todos los procesos de todos los usuarios en un formato detallado. |
| `ef`           | Muestra información completa, incluyendo la jerarquía de procesos. |
| `--sort`       | Permite ordenar la salida según un campo específico. Ejemplo: `--sort=-cpu` para ordenar por uso de CPU descendente. |
| `--forest`     | Muestra los procesos en formato de árbol, destacando las relaciones entre ellos. |
| `--pid`        | Especifica los IDs de proceso (PIDs) que se deben mostrar. |
| `--user`       | Filtra los procesos por nombre de usuario. |
| `--group`      | Filtra los procesos por nombre de grupo. |
| `--format`     | Permite personalizar la salida mostrando solo los campos deseados. Ejemplo: `--format pid,cmd,%cpu` |
| `--ppid`       | Muestra procesos hijos de un PID específico. |
| `--watch`      | Refresca continuamente la salida con un intervalo especificado. Ejemplo: `ps --watch 1` para actualizar cada segundo. |
| `--no-headers` | Omite la fila de encabezados al mostrar los resultados. |
