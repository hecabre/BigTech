# Método para resolver un problema de algoritmos

## Antes de programar

Reformula entrada, salida y restricciones. Construye un ejemplo pequeño y pregunta por duplicados, negativos, entrada vacía y tamaño máximo. Después describe una solución de fuerza bruta: ofrece una referencia correcta contra la cual mejorar.

Busca la restricción que vuelve insuficiente la fuerza bruta. Si `n` es grande, un `O(n²)` probablemente no alcance. Identifica señales: pertenencia sugiere `Set`; asociación sugiere `Map`; entrada ordenada sugiere dos punteros o búsqueda binaria; “siguiente mayor” sugiere pila monotónica; “mínimo número de pasos” suele sugerir BFS.

## Durante el código

Explica el invariante: qué sigue siendo cierto después de cada iteración. Usa nombres que representen la idea y prueba primero el caso normal; después vacío, mínimo, máximo y duplicados.

## Al terminar

Calcula tiempo y espacio, explica el trade-off y realiza una ejecución manual. Si consultaste una solución, cierra la fuente y reconstruye el algoritmo.

## Recuperación

1. ¿Qué restricción determina si `O(n²)` es aceptable?
2. ¿Qué es un invariante?
3. ¿Qué cuatro clases de casos límite revisarías?
