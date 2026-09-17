# AWS: responsabilidad compartida, IAM y seguridad

AWS protege la infraestructura de la nube; el cliente protege su configuración, identidades, datos y lo que ejecuta en la nube. La división exacta cambia según el nivel administrado del servicio.

IAM responde quién puede hacer qué sobre qué recurso y bajo qué condiciones. Prefiere credenciales temporales mediante roles, mínimo privilegio y políticas explícitas. Una denegación explícita prevalece sobre permisos.

Separa autenticación de autorización. Cifra en tránsito y reposo, administra secretos fuera del código y registra acciones sensibles.

## Recuperación

1. ¿Qué responsabilidad cambia entre EC2 y un servicio administrado?
2. ¿Por qué un role es preferible a claves permanentes?
3. ¿Qué significa mínimo privilegio?
