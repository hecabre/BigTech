# Arrays, hash maps y sets

Un arreglo ofrece acceso por índice `O(1)` y recorrido `O(n)`, pero insertar al principio o en medio puede requerir desplazar elementos. Un `Set` representa pertenencia; un `Map` relaciona una clave con información como frecuencia, índice o estado.

La técnica común es intercambiar memoria por tiempo: guardar lo visto permite reemplazar una búsqueda interna `O(n)` por consultas promedio `O(1)`, convirtiendo muchos algoritmos de `O(n²)` a `O(n)`.

El diseño de la clave importa. En Group Anagrams, la palabra ordenada o un vector de frecuencias funciona como firma. La firma debe ser idéntica para elementos equivalentes y distinta cuando no lo son.

## Recuperación

1. ¿Cuándo usarías `Set` en lugar de `Map`?
2. ¿Por qué una firma permite agrupar?
3. ¿Qué costo añade ordenar cada palabra?
