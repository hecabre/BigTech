# Design Circular Queue

[← Anterior: Design HashMap](../Semana%2026/01-Lunes-design-hashmap.md) · [Siguiente: LRU Cache →](../Semana%2026/03-Miercoles-lru-cache.md)

> [!quote] Para darle con todo
> «El primer principio es no autoengañarte, y la persona más fácil de engañar eres tú.»
> — *Richard Feynman, Nobel de Física*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/design-circular-queue/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Diseño
- **Semana:** 26 — Diseño de estructuras (POO) (problema 2 de 5)
- **Día:** [Semana 26 — Martes](../../Semanas/Semana%2026/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/):** Es otra cola, ahora con arreglo circular.
- **Repaso del patrón:** [POO y diseño](../../Estudio/Articulos/16-POO-y-SOLID.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Usa un arreglo de tamaño k, más `head` y `count`.

> [!question]- Pista 2 — ¿qué estructura usar?
> `tail = (head + count - 1) % k`.

> [!question]- Pista 3 — el algoritmo
> `enQueue` escribe en `(head + count) % k`; `deQueue` mueve `head = (head + 1) % k`.

> [!warning]- Trampa común
> Confundir lleno con vacío cuando solo usas `head` y `tail`.

> [!success]- Complejidad meta
> Tiempo O(1), espacio O(k)

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
