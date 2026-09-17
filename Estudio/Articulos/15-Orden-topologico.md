# Orden topológico

Un orden topológico existe solo en grafos dirigidos acíclicos. Modela dependencias: una arista `a → b` indica que `a` debe ocurrir antes que `b`.

El algoritmo de Kahn mantiene el grado de entrada. Añade a la cola los nodos con grado cero, elimínalos conceptualmente y reduce el grado de sus vecinos. Si procesas menos de `V` nodos, existe un ciclo.

DFS también funciona usando tres estados: no visitado, visitando y terminado. Encontrar una arista hacia un nodo “visitando” revela un ciclo.

## Recuperación

1. ¿Qué significa grado de entrada cero?
2. ¿Cómo detecta ciclos el algoritmo de Kahn?
3. ¿Qué representa el estado “visitando” en DFS?
