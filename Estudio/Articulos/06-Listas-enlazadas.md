# Listas enlazadas

Cada nodo contiene un valor y una referencia al siguiente. Insertar después de un nodo conocido es `O(1)`, pero encontrar una posición es `O(n)`. La dificultad real está en cambiar referencias sin perder el resto de la lista.

Usa un nodo centinela cuando la cabeza pueda cambiar. Para invertir una lista conserva tres referencias: `previous`, `current` y `next`. Para detectar ciclos, los punteros lento y rápido se encontrarán si existe un ciclo.

Dibuja los enlaces antes de modificarlos y guarda `next` antes de cambiar `current.next`.

## Recuperación

1. ¿Qué problema elimina un nodo centinela?
2. ¿Por qué debes guardar `next` al invertir?
3. ¿Cómo detectan un ciclo los punteros lento y rápido?
