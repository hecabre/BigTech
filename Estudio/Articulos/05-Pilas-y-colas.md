# Pilas y colas

Una pila sigue LIFO: el último elemento en entrar es el primero en salir. Sirve para anidamiento, deshacer, evaluación de expresiones y recorridos DFS iterativos. En paréntesis válidos se guardan aperturas; cada cierre debe coincidir con la cima.

Una cola sigue FIFO y es natural para BFS, procesamiento por llegada y buffers. En JavaScript/TypeScript, hacer `shift()` repetidamente en un arreglo puede desplazar elementos; para una cola eficiente usa un índice de lectura.

Una pila monotónica mantiene valores crecientes o decrecientes. Cada elemento entra y sale a lo sumo una vez, por eso el costo total suele ser `O(n)`.

## Recuperación

1. ¿Por qué basta comparar con la cima en Valid Parentheses?
2. ¿Qué diferencia conceptual hay entre DFS y BFS?
3. ¿Por qué una pila monotónica no necesariamente es `O(n²)`?
