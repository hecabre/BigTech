# Merge k Sorted Lists

[← Anterior: Word Break](../Semana%2033/03-Miercoles-word-break.md) · [Siguiente: Rotting Oranges →](../Semana%2033/05-Viernes-rotting-oranges.md)

> [!quote] Para darle con todo
> «No puedes subir la escalera del éxito con las manos en los bolsillos.»
> — *Arnold Schwarzenegger, siete veces Mr. Olympia*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/merge-k-sorted-lists/)
- **Dificultad:** Hard
- **Tipo:** Repaso
- **Patrón:** Heap
- **Semana:** 33 — Semana de mocks — repaso de clásicos (problema 4 de 5)
- **Día:** [Semana 33 — Jueves](../../Semanas/Semana%2033/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

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
