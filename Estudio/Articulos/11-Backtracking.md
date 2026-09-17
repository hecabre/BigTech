# Backtracking

Backtracking construye una solución parcial, explora una decisión y deshace el cambio. Sus cuatro piezas son: estado actual, opciones disponibles, caso base y operación de deshacer.

El árbol de búsqueda puede crecer exponencialmente. Las podas evitan explorar ramas imposibles, pero deben preservar todas las respuestas válidas. Para evitar aliasing, guarda una copia de la combinación cuando encuentres una solución.

## Recuperación

1. ¿Qué debe restaurarse después de una llamada recursiva?
2. ¿Por qué se guarda una copia del camino?
3. ¿Qué hace válida una poda?
