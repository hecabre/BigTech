# Dos punteros y ventana deslizante

Dos punteros funcionan especialmente bien en arreglos ordenados, comparaciones desde extremos y transformaciones in-place. La clave es demostrar que mover un puntero descarta opciones que ya no pueden mejorar la respuesta.

Una ventana deslizante representa un intervalo contiguo. El puntero derecho expande; el izquierdo reduce cuando se viola una condición. Si cada puntero recorre la entrada una sola vez, el costo total es `O(n)`, aunque exista un `while` dentro de un `for`.

Ventana fija: el tamaño es conocido. Ventana variable: crece y se contrae de acuerdo con una condición. Para que funcione, debes poder actualizar el estado de la ventana eficientemente.

## Recuperación

1. ¿Por qué dos punteros pueden ser `O(n)`?
2. ¿Qué invariante mantiene una ventana válida?
3. ¿Cuándo un arreglo ordenado elimina la necesidad de un `Map`?
