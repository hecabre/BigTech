# Grafos, DFS y BFS

Un grafo se modela con lista de adyacencia o matriz. DFS es útil para componentes, detección de ciclos y exploración exhaustiva. BFS encuentra caminos mínimos cuando cada arista tiene el mismo costo.

Marca un nodo como visitado al añadirlo a la pila o cola, no al retirarlo, para evitar duplicados. En matrices, cada celda puede verse como nodo conectado a vecinos válidos.

Con lista de adyacencia, recorrer todo el grafo cuesta `O(V + E)`: se visitan vértices y aristas. El espacio también puede llegar a `O(V)`.

## Recuperación

1. ¿Cuándo garantiza BFS un camino mínimo?
2. ¿Por qué marcar al insertar evita trabajo duplicado?
3. ¿Qué representan `V` y `E`?
