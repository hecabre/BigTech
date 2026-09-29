# Kth Largest Element in a Stream

[← Anterior: Lowest Common Ancestor of a Binary Tree](../Semana%2011/05-Viernes-lowest-common-ancestor-of-a-binary-tree.md) · [Siguiente: Relative Ranks →](../Semana%2012/02-Martes-relative-ranks.md)

> [!quote] Para darle con todo
> «Hablar es barato. Enséñame el código.»
> — *Linus Torvalds, creador de Linux*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/kth-largest-element-in-a-stream/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Heap
- **Semana:** 12 — Heaps (problema 1 de 5)
- **Día:** [Semana 12 — Lunes](../../Semanas/Semana%2012/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/):** Es la misma idea que Kth Largest in an Array, pero los datos llegan uno a uno.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Solo te importan los k más grandes.

> [!question]- Pista 2 — ¿qué estructura usar?
> Mantén un min-heap de tamaño k: su tope es el k-ésimo mayor.

> [!question]- Pista 3 — el algoritmo
> En `add`: `push` y, si el tamaño pasa de k, `pop`.

> [!warning]- Trampa común
> Ordenar el arreglo completo en cada `add`.

> [!success]- Complejidad meta
> Tiempo O(log k) por `add`, espacio O(k)

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
