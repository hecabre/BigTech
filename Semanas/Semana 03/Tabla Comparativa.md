
| Servicio          | Que es?                                             | Que administras?                                                        | AWS Administra                                 | Ideal para                                                | Palabras claves                      |
| ----------------- | --------------------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------- | --------------------------------------------------------- | ------------------------------------ |
| EC2               | Son maquinas virtuales en AWS                       | Sistema operativo, parches, software, configuracion, parte del escalado | Hardware fisico                                | Ideal para aplicaciones que necesitan control de servidor | Maquina virtual / Maximo control     |
| Lambda            | Ejecuta codigo sin tener que administrar servidores | Codigo y configuracion de la funcion                                    | Servidores, escalado e infraestructura         | Eventos, APIs, automatizaciones, tareas cortas            | Serverless / Eventos                 |
| ECS               | Orquestador de contenedores                         | Contenedores, tareas y servicios                                        | Orquestador de contenedores                    | Microservicios, apps y Docker                             | Contenedores / orquestacion          |
| Fargate           | Motor serverless para ejecutar contenedores         | Contenedor, CPU / RAM requeridos                                        | Servidores donde corren los contenedores       | ECS / EKS sin administrar EC2                             | Serverless para contenedores         |
| Lightsail         | Plataforma simplificada con VPS y servicios basicos | Tu aplicacion y configuracion basica                                    | Simplifica gran parte de AWS                   | Blogs, webs pequenas, WordPress, proyectos simples        | AWS simplificado / precio predecible |
| Elastic Beanstalk | Paas para desplegar aplicaciones                    | El codigo                                                               | Provisionamiento, LB, Auto Scaling y monitoreo | Web apps y APIs tradicionales                             | Sube tu codigo y AWS despliega       |
## ECS vs Fargate
No son competidores directos.
ECS = El administrador de los contenedores
Fargate = Donde se ejecutan esos contenedores sin que tengas que administrar contenedores.
```
Docker container
       ↓
      ECS
       ↓
 ┌───────────────┐
 │               │
EC2           Fargate
│               │
Tú manejas      AWS maneja
servidores      servidores
```
ECS puede ejecutar sus tareas usando EC2 o Fargate. AWS define como un moto de computo serverless para contenedores coimpatibles con ECS y EKS.
Si quieres administrar contenedores de Docker sin administrar servidores = ECS + Fargate

## EC2 vs Lambda
Quieres controlar el servidor => EC2
Solo quieres ejecutar el codigo => Lambda
## Lightsail vs EC2
Lightsail puede darte una maquina virtual, pero esta disenado para ser mucho mas sencillo
Muchisima configuracion => EC2
Muchisima flexibilidad => EC2
Muchisimo control => EC2

Configuracion => Lightsail
Planes predecibles => Lightsail
Menos opciones => Lightsail

AWS Lo orienta especialmente a sitios webs, aplicaciones pequenas, blogs y proyectos que quieren empezar rapidamene, ofreciendo VPS, bases de datos, CDN, balanceadores de carga y DNS dentro de una experiencia simplificada
"Una pequeña empresa quiere alojar un sitio WordPress rápidamente con costos mensuales predecibles."
Lightsail
Cosas importantes

| Si el examen menciona                                  | Pensamos en       |
| ------------------------------------------------------ | ----------------- |
| Virtual machine / Control absoluto                     | EC2               |
| Correr codigo sin servidor                             | Lambda            |
| Orquestar contenedores con Docker                      | ECS               |
| Contenedores sin manejar servidores                    | Fargate           |
| Un vps simple / sitios pequenos / precios predecibles  | Lightsail         |
| Subir una aplicacion a AWS sin manejar infraestructura | Elastic Beanstalk |
