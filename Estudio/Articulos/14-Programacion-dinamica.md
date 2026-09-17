# Programación dinámica

DP aplica cuando existen subproblemas repetidos y estructura óptima. Empieza definiendo el estado con una frase completa: “`dp[i]` representa…”. Después escribe transición, casos base, orden de cálculo y respuesta final.

Memoization resuelve top-down y guarda resultados. Tabulation construye bottom-up. Ambas pueden tener la misma complejidad; la elección depende de qué estados se visitan y del riesgo de profundidad recursiva.

No optimices espacio antes de validar la recurrencia. Primero crea una tabla correcta; luego observa cuántos estados anteriores necesita cada paso.

## Recuperación

1. ¿Qué debe explicar la definición del estado?
2. ¿Cuándo memoization evita estados innecesarios?
3. ¿Cómo decides si puedes reducir memoria?
