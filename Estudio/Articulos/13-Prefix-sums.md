# Prefix sums

Un prefix sum transforma consultas repetidas sobre rangos. Si `prefix[i]` contiene la suma de los primeros `i` elementos, la suma de `[left, right]` es `prefix[right + 1] - prefix[left]`.

Para contar subarreglos con suma `k`, guarda cuántas veces apareció cada suma acumulada. Si la suma actual es `s`, necesitas una suma anterior `s - k`. Esto convierte muchos enfoques `O(n²)` en `O(n)` promedio.

## Recuperación

1. ¿Por qué se inicializa frecuencia de suma cero en uno?
2. ¿Qué diferencia hay entre encontrar y contar subarreglos?
3. ¿Qué cambia en dos dimensiones?
