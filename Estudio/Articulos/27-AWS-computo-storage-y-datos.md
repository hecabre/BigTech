# AWS: cómputo, almacenamiento y datos

Selecciona cómputo por control operativo, duración y patrón de carga. EC2 ofrece mayor control; contenedores estandarizan despliegue; Fargate elimina administración de hosts; Lambda funciona bien para eventos y ejecuciones acotadas.

S3 almacena objetos; EBS ofrece bloques para una instancia o casos compatibles; EFS ofrece sistema de archivos compartido. RDS administra bases relacionales; DynamoDB ofrece clave-valor/documento con escalado administrado.

No elijas por popularidad. Compara latencia, consistencia, patrón de acceso, disponibilidad, operación y costo.

## Recuperación

1. ¿Qué control necesitas realmente?
2. ¿Objeto, bloque o archivo?
3. ¿Qué patrón de consulta define la base de datos?
