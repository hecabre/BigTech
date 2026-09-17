# Búsqueda binaria

La búsqueda binaria requiere una propiedad monotónica: al evaluar una posición puedes descartar de forma segura una mitad. No se limita a buscar valores; también encuentra el mínimo parámetro que hace verdadero un predicado.

Decide antes si el intervalo es cerrado `[left, right]` o semiabierto `[left, right)`. Mantén esa convención en condición, actualización y retorno. Calcula el medio como `left + Math.floor((right - left) / 2)`.

En arreglos rotados, al menos una mitad está ordenada. Identifica esa mitad y comprueba si el objetivo pertenece a su rango.

## Recuperación

1. ¿Qué significa que un predicado sea monotónico?
2. ¿Cuál es el invariante de tu intervalo?
3. ¿Cómo evitas un ciclo infinito al actualizar límites?
