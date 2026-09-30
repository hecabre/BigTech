# Furthest Building You Can Reach

[← Anterior: Reorganize String](../Semana%2028/01-Lunes-reorganize-string.md) · [Siguiente: Single-Threaded CPU →](../Semana%2028/03-Miercoles-single-threaded-cpu.md)

> [!quote] Para darle con todo
> «Todo el mundo tiene un plan hasta que le dan un golpe en la boca.»
> — *Mike Tyson, campeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/furthest-building-you-can-reach/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Heap greedy
- **Semana:** 28 — Heaps avanzados + primer Hard (problema 2 de 5)
- **Día:** [Semana 28 — Martes](../../Semanas/Semana%2028/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Kth Largest Element in a Stream](../Semana%2012/01-Lunes-kth-largest-element-in-a-stream.md):** Es un min-heap de tamaño fijo: las escaleras van para los k saltos más altos.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Las escaleras deberían usarse en las subidas más grandes.

> [!question]- Pista 2 — ¿qué estructura usar?
> Mete cada subida en un min-heap.

> [!question]- Pista 3 — el algoritmo
> Si el heap tiene más elementos que escaleras, saca la subida menor y págala con ladrillos; si no alcanzan, detente.

> [!warning]- Trampa común
> Decidir entre escalera y ladrillos en el momento, sin poder corregir después.

> [!success]- Complejidad meta
> Tiempo O(n log L), espacio O(L)

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
