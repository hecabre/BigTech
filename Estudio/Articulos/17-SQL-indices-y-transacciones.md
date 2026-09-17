# SQL, índices y transacciones

Un índice acelera lecturas al mantener una estructura adicional, pero consume espacio y encarece escrituras. El orden de columnas importa en índices compuestos. Usa el plan de ejecución para confirmar si el motor aprovecha el índice.

Una transacción busca propiedades ACID. El aislamiento define qué anomalías pueden observar transacciones concurrentes. Más aislamiento puede reducir concurrencia; la decisión depende de la consistencia necesaria.

Normalizar reduce duplicación y anomalías. Desnormalizar puede mejorar lecturas a cambio de complejidad de actualización.

## Recuperación

1. ¿Por qué un índice perjudica escrituras?
2. ¿Qué riesgo introduces al desnormalizar?
3. ¿Qué debes mirar en un plan de ejecución?
