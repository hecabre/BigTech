# HTTP, DNS, TCP y TLS

DNS traduce un nombre a una dirección. TCP establece una conexión confiable y ordenada. TLS autentica al servidor y cifra el canal. HTTP define la semántica de petición y respuesta sobre ese transporte.

Los métodos HTTP tienen propiedades útiles: `GET` debe ser seguro; `PUT` suele ser idempotente; `POST` no lo es automáticamente. Un timeout limita espera; un retry puede duplicar efectos si la operación no es idempotente. El backoff y jitter evitan reintentos sincronizados.

## Recuperación

1. ¿Qué parte autentica TLS?
2. ¿Por qué un retry puede ser peligroso?
3. ¿Qué significa idempotencia?
