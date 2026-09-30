# Merge k Sorted Lists

[← Anterior: Single-Threaded CPU](../Semana%2028/03-Miercoles-single-threaded-cpu.md) · [Siguiente: Top K Frequent Words →](../Semana%2028/05-Viernes-top-k-frequent-words.md)

> [!quote] Para darle con todo
> «Siempre es el Día 1.»
> — *Jeff Bezos, fundador de Amazon, carta a accionistas*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/merge-k-sorted-lists/)
- **Dificultad:** Hard
- **Tipo:** Nuevo
- **Patrón:** Heap
- **Semana:** 28 — Heaps avanzados + primer Hard (problema 4 de 5)
- **Día:** [Semana 28 — Jueves](../../Semanas/Semana%2028/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!warning] Hard
> Límite de 45 minutos. Si no sale, estudia la solución y reintenta en 7 días. No cuenta como fracaso.

## Por qué este problema

- **Se conecta con [Merge Two Sorted Lists](../Semana%2021/02-Martes-merge-two-sorted-lists.md):** Es Merge Two Sorted Lists con k cabezas en un heap.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Versión simple: combina las listas de dos en dos (divide y vencerás).

> [!question]- Pista 2 — ¿qué estructura usar?
> Versión con heap: mete la cabeza de cada lista.

> [!question]- Pista 3 — el algoritmo
> Saca el menor, engánchalo con `dummy` y mete su `next`.

> [!warning]- Trampa común
> Combinar una por una contra el resultado acumulado: O(k·N).

> [!success]- Complejidad meta
> Tiempo O(N log k), espacio O(k)

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
