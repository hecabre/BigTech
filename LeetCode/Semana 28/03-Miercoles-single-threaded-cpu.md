# Single-Threaded CPU

[← Anterior: Furthest Building You Can Reach](../Semana%2028/02-Martes-furthest-building-you-can-reach.md) · [Siguiente: Merge k Sorted Lists →](../Semana%2028/04-Jueves-merge-k-sorted-lists.md)

> [!quote] Para darle con todo
> «He fallado más de 9,000 tiros en mi carrera. He perdido casi 300 partidos. 26 veces me confiaron el tiro ganador y lo fallé. He fallado una y otra y otra vez en mi vida. Y por eso tengo éxito.»
> — *Michael Jordan, seis veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/single-threaded-cpu/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Heap + simulación
- **Semana:** 28 — Heaps avanzados + primer Hard (problema 3 de 5)
- **Día:** [Semana 28 — Miércoles](../../Semanas/Semana%2028/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [K Closest Points to Origin](../Semana%2012/03-Miercoles-k-closest-points-to-origin.md):** Es un heap con dos criterios más simulación del tiempo.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Ordena las tareas por tiempo de llegada, sin perder su índice original.

> [!question]- Pista 2 — ¿qué estructura usar?
> Mete al heap `[duración, índice]` todas las que ya llegaron.

> [!question]- Pista 3 — el algoritmo
> Si el heap está vacío, salta el tiempo a la siguiente llegada.

> [!warning]- Trampa común
> No desempatar por índice.

> [!success]- Complejidad meta
> Tiempo O(n log n), espacio O(n)

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
