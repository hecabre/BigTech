# Fundamentos de sistemas distribuidos

En un sistema distribuido, la red puede retrasar, duplicar o perder mensajes. Diseña suponiendo fallos parciales. Timeouts detectan espera excesiva; retries recuperan fallos transitorios; idempotencia evita repetir efectos.

Replicación mejora disponibilidad y lectura, pero introduce retraso y decisiones de consistencia. Partición distribuye datos y capacidad, pero vuelve más difíciles las consultas cruzadas y el rebalanceo. Caché reduce latencia a cambio de invalidación y posible obsolescencia.

Una cola desacopla productor y consumidor, absorbe picos y permite reintentos. “Exactly once” suele lograrse en la práctica combinando entrega al menos una vez con consumidores idempotentes.

## Recuperación

1. ¿Qué es un fallo parcial?
2. ¿Qué trade-off introduce replicar?
3. ¿Cómo manejas mensajes duplicados?
