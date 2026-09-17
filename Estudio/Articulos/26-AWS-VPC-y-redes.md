# AWS: VPC y redes

Una VPC es una red lógica regional. Las subredes pertenecen a una Availability Zone. Una subred se considera pública cuando su tabla de rutas permite salida mediante Internet Gateway; una IP pública por sí sola no define la ruta.

Security Groups son stateful y se asocian a interfaces. NACL son stateless y operan a nivel de subred. Un NAT Gateway permite salida desde subredes privadas, pero no inicia conexiones entrantes desde internet.

Los VPC endpoints permiten acceder a servicios compatibles sin recorrer internet pública y pueden reducir exposición y ciertos costos de red.

## Recuperación

1. ¿Qué hace pública a una subred?
2. ¿Qué diferencia práctica hay entre SG y NACL?
3. ¿Por qué usarías un endpoint?
