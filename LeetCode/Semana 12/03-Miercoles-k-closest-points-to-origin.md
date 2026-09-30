# K Closest Points to Origin

[← Anterior: Relative Ranks](../Semana%2012/02-Martes-relative-ranks.md) · [Siguiente: Top K Frequent Words →](../Semana%2012/04-Jueves-top-k-frequent-words.md)

> [!quote] Para darle con todo
> «He fallado más de 9,000 tiros en mi carrera. He perdido casi 300 partidos. 26 veces me confiaron el tiro ganador y lo fallé. He fallado una y otra y otra vez en mi vida. Y por eso tengo éxito.»
> — *Michael Jordan, seis veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/k-closest-points-to-origin/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Heap
- **Semana:** 12 — Heaps (problema 3 de 5)
- **Día:** [Semana 12 — Miércoles](../../Semanas/Semana%2012/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Kth Largest Element in a Stream](../Semana%2012/01-Lunes-kth-largest-element-in-a-stream.md):** Es un heap de tamaño k, esta vez con un max-heap por distancia.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> No necesitas la raíz cuadrada: compara `x² + y²`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Solución simple: ordenar por distancia y tomar k.

> [!question]- Pista 3 — el algoritmo
> Solución con heap: un max-heap de tamaño k; si llega uno más cercano que el tope, reemplázalo.

> [!warning]- Trampa común
> Usar un min-heap de n elementos cuando k es pequeño.

> [!success]- Complejidad meta
> Tiempo O(n log k), espacio O(k)

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
