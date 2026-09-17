# Cómo medir complejidad temporal y espacial

La complejidad describe cómo crece el costo de un algoritmo cuando aumenta el tamaño de la entrada `n`. No intenta predecir milisegundos exactos: compara tasas de crecimiento.

## Procedimiento

1. Define qué representa `n`: caracteres, nodos, filas o elementos.
2. Identifica la operación dominante.
3. Cuenta cuántas veces puede ejecutarse en el peor caso.
4. Conserva el término de mayor crecimiento y elimina constantes.
5. Calcula aparte la memoria adicional.

Un recorrido de `n` elementos es `O(n)`. Dos recorridos consecutivos son `O(n + n) = O(n)`. Dos recorridos anidados sobre toda la entrada suelen ser `O(n²)`. Dividir el espacio de búsqueda a la mitad en cada paso produce `O(log n)`. Recorrer `n` elementos y hacer una búsqueda logarítmica por elemento produce `O(n log n)`.

## Espacio

Cuenta memoria que crece con la entrada. Unas cuantas variables son `O(1)`. Un `Set` que puede guardar todos los elementos es `O(n)`. Una pila recursiva también cuenta: la profundidad de un árbol balanceado es `O(log n)` y la de un árbol degenerado puede ser `O(n)`.

## Cuidado

- Un `Map` suele ofrecer acceso promedio `O(1)`, no una garantía universal.
- `sort()` normalmente domina con `O(n log n)`.
- Dos índices no significan dos ciclos anidados: si cada índice avanza como máximo `n` veces, puede seguir siendo `O(n)`.
- Big-O es una cota superior; `Θ` expresa una cota ajustada.

## Recuperación

1. ¿Por qué dos ciclos consecutivos no son `O(n²)`?
2. ¿Qué memoria usa una función recursiva aunque no cree arreglos?
3. ¿Cuál es el costo de ordenar y luego recorrer?

Fuente ampliada: [MIT 6.006 — notas de complejidad asintótica](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/resources/mit6_006f11_rec01/).
