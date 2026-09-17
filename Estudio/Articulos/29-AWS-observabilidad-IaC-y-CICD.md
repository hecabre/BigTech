# AWS: observabilidad, IaC y CI/CD

Define indicadores antes de dashboards: latencia, tráfico, errores y saturación. Los logs necesitan contexto y correlación; las alarmas deben ser accionables.

Infraestructura como código vuelve revisables y reproducibles los cambios. Separa configuración, secretos y estado. Un pipeline debe probar, construir, publicar, desplegar gradualmente y permitir rollback.

La automatización no elimina el riesgo; lo hace repetible. Usa permisos mínimos, artefactos inmutables y evidencia de qué versión está desplegada.

## Recuperación

1. ¿Qué alarma indica impacto real?
2. ¿Dónde vive el estado de IaC?
3. ¿Cómo regresarías a una versión estable?
