# LRU Cache

[← Anterior: Merge Intervals](../Semana%2038/02-Martes-merge-intervals.md) · [Siguiente: Number of Islands →](../Semana%2038/04-Jueves-number-of-islands.md)

> [!quote] Para darle con todo
> «Sabía que si fallaba no me iba a arrepentir. Lo único de lo que me podría arrepentir era de no haberlo intentado.»
> — *Jeff Bezos, sobre dejar su trabajo para fundar Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/lru-cache/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Hash map + lista doble
- **Semana:** 38 — Modo entrevista — repaso ligero (problema 3 de 5)
- **Día:** [Semana 38 — Miércoles](../../Semanas/Semana%2038/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Design HashMap](../Semana%2026/01-Lunes-design-hashmap.md):** Es un `Map` más una lista doblemente enlazada: tu problema de diseño más preguntado en Amazon.
- **Repaso del patrón:** [POO y diseño](../../Estudio/Articulos/16-POO-y-SOLID.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Necesitas `get` y `put` en O(1) y saber cuál es el menos usado.

> [!question]- Pista 2 — ¿qué estructura usar?
> `Map<key, nodo>` más una lista doble con `head` y `tail` dummy.

> [!question]- Pista 3 — el algoritmo
> Cada acceso mueve el nodo al frente; si se excede la capacidad, borra el anterior a `tail`.

> [!warning]- Trampa común
> Olvidar mover el nodo al frente en `get`.

> [!success]- Complejidad meta
> Tiempo O(1), espacio O(capacidad)

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
