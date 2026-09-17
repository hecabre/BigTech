# Heaps y colas de prioridad

Un heap permite consultar el mínimo o máximo en `O(1)` e insertar o extraer en `O(log n)`. No mantiene todos los elementos ordenados; solo garantiza la relación entre cada padre y sus hijos.

Para conservar los `k` elementos más grandes, usa un min-heap de tamaño `k`: la cima es el candidato que debe salir. El costo es `O(n log k)`, útil cuando `k` es mucho menor que `n`.

Un heap es adecuado cuando necesitas repetidamente “el siguiente mejor”. Si solo quieres ordenar una vez, ordenar el arreglo puede ser más simple.

## Recuperación

1. ¿Por qué un min-heap sirve para los `k` mayores?
2. ¿Qué operación cuesta `O(log n)`?
3. ¿Cuándo preferirías ordenar?
