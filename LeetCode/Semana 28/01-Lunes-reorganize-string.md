# Reorganize String

[← Anterior: Copy List with Random Pointer](../Semana%2027/05-Viernes-copy-list-with-random-pointer.md) · [Siguiente: Furthest Building You Can Reach →](../Semana%2028/02-Martes-furthest-building-you-can-reach.md)

> [!quote] Para darle con todo
> «Hablar es barato. Enséñame el código.»
> — *Linus Torvalds, creador de Linux*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/reorganize-string/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Heap greedy
- **Semana:** 28 — Heaps avanzados + primer Hard (problema 1 de 5)
- **Día:** [Semana 28 — Lunes](../../Semanas/Semana%2028/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Task Scheduler](../Semana%2012/05-Viernes-task-scheduler.md):** Es Task Scheduler construyendo el string.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si una letra aparece más de `ceil(n / 2)` veces, es imposible.

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa un max-heap por frecuencia.

> [!question]- Pista 3 — el algoritmo
> Saca las dos más frecuentes, agrégalas y regrésalas con su conteo - 1.

> [!warning]- Trampa común
> Sacar una sola letra y repetirla dos veces seguidas.

> [!success]- Complejidad meta
> Tiempo O(n log 26), espacio O(26)

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
