# Método de system design para New Grad

Empieza aclarando usuarios, casos de uso, escala y requisitos no funcionales. Después define API, modelo de datos y flujo principal antes de dibujar servicios.

Haz estimaciones sencillas: solicitudes por segundo, almacenamiento y ancho de banda. Identifica el cuello de botella y añade componentes solo para resolver una necesidad concreta. Para cada decisión explica alternativa y trade-off.

Termina recorriendo una petición, fallos, observabilidad, seguridad y costos. Un diseño pequeño bien justificado vale más que un diagrama lleno de servicios.

## Recuperación

1. ¿Qué requisito justifica cada componente?
2. ¿Dónde está el estado?
3. ¿Qué ocurre si falla una dependencia?
