# Árboles binarios y BST

DFS explora profundidad mediante recursión o pila. Preorden visita antes de los hijos; inorden visita entre ambos; postorden visita después. BFS procesa por niveles mediante una cola.

En un BST, todos los valores del subárbol izquierdo son menores y los del derecho mayores según la convención elegida. Validarlo exige propagar límites; comparar únicamente cada nodo con sus hijos no detecta violaciones lejanas.

La mayoría de recorridos visitan cada nodo una vez: tiempo `O(n)`. El espacio depende de la altura `h`: `O(h)` para DFS y hasta `O(w)` para BFS, donde `w` es el ancho máximo.

## Recuperación

1. ¿Qué recorrido usarías para procesar por niveles?
2. ¿Por qué comparar solo padre e hijos no valida un BST?
3. ¿Cuál es el peor espacio de recursión en un árbol degenerado?
