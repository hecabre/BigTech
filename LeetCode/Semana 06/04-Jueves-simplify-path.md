# Simplify Path

[← Anterior: Asteroid Collision](../Semana%2006/03-Miercoles-asteroid-collision.md) · [Siguiente: Min Stack →](../Semana%2006/05-Viernes-min-stack.md)

> [!quote] Para darle con todo
> «Las últimas tres o cuatro repeticiones son las que hacen crecer el músculo.»
> — *Arnold Schwarzenegger, Pumping Iron*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/simplify-path/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Stack
- **Semana:** 06 — Pila monotónica (problema 4 de 5)
- **Día:** [Semana 06 — Jueves](../../Semanas/Semana%2006/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Crawler Log Folder](../Semana%2006/02-Martes-crawler-log-folder.md):** Es Crawler Log Folder, pero ahora sí guardas los nombres.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Separa la ruta con `split('/')`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Ignora `''` y `'.'`; `'..'` hace `pop` si hay algo; cualquier otro nombre hace `push`.

> [!question]- Pista 3 — el algoritmo
> La respuesta es `'/' + pila.join('/')`.

> [!warning]- Trampa común
> Tratar `'...'` como especial: es un nombre de carpeta válido.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(n)

## Antes de programar

- **Entrada y salida con mis palabras:**
- **Restricciones importantes:**
- **Casos límite:**
- **Fuerza bruta y su costo:**
- **Patrón que intentaré:**

## Mi solución

```ts

```

## Complejidad

- **Tiempo:**
- **Por qué:**
- **Espacio adicional:**
- **Por qué:**

## Error o aprendizaje

- **Dónde me atasqué:**
- **Pista consultada:** ninguna / 1 / 2 / 3
- **Invariante o idea clave:**
- **Qué haré distinto:**

## Repetición espaciada

- [ ] Reintento en 24 horas
- [ ] Reintento en 7 días
- [ ] Reintento en 30 días
