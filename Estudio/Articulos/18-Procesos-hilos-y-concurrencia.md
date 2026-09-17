# Procesos, hilos y concurrencia

Un proceso posee espacio de memoria aislado; los hilos de un proceso comparten memoria. Compartir facilita comunicación, pero introduce carreras cuando el resultado depende del orden de ejecución.

Un lock protege una sección crítica. Demasiada granularidad reduce paralelismo; locks múltiples pueden causar deadlock. Inmutabilidad, colas y partición del estado reducen la necesidad de sincronización.

Concurrencia significa gestionar tareas superpuestas; paralelismo significa ejecutarlas simultáneamente. Trabajo I/O-bound y CPU-bound requieren estrategias distintas.

## Recuperación

1. ¿Qué comparten los hilos?
2. ¿Cuáles son las condiciones de una race condition?
3. ¿Cómo puede una cola reducir acoplamiento temporal?
