# AWS: mensajería y resiliencia

SQS desacopla con colas; SNS distribuye mensajes a suscriptores; EventBridge enruta eventos según reglas; Step Functions coordina estados y pasos.

Configura visibility timeout según el procesamiento. Una DLQ aísla fallos repetidos, pero necesita monitoreo y un proceso de redrive. Diseña consumidores idempotentes porque pueden recibir duplicados.

RTO define cuánto tiempo puede permanecer caído un sistema; RPO define cuántos datos puede perder. Backup/restore, pilot light, warm standby y multi-site intercambian costo por recuperación.

## Recuperación

1. ¿Cola, pub/sub o bus de eventos?
2. ¿Qué ocurre si vence el visibility timeout?
3. ¿Qué diferencia hay entre RTO y RPO?
