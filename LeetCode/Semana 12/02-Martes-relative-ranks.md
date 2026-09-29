# Relative Ranks

[← Anterior: Kth Largest Element in a Stream](../Semana%2012/01-Lunes-kth-largest-element-in-a-stream.md) · [Siguiente: K Closest Points to Origin →](../Semana%2012/03-Miercoles-k-closest-points-to-origin.md)

> [!quote] Para darle con todo
> «Todo el mundo tiene un plan hasta que le dan un golpe en la boca.»
> — *Mike Tyson, campeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/relative-ranks/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Heap / sorting
- **Semana:** 12 — Heaps (problema 2 de 5)
- **Día:** [Semana 12 — Martes](../../Semanas/Semana%2012/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/):** Ordenar por puntaje sin perder la posición original.
- **Repaso del patrón:** [Heaps](../../Estudio/Articulos/09-Heaps-y-priority-queues.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Necesitas el puesto de cada atleta, pero la respuesta va en el orden original.

> [!question]- Pista 2 — ¿qué estructura usar?
> Crea pares `[puntaje, índice]` y ordénalos de mayor a menor.

> [!question]- Pista 3 — el algoritmo
> Recorre los pares ordenados y asigna el lugar a `res[índice]`: Gold, Silver, Bronze y luego números.

> [!warning]- Trampa común
> Ordenar el arreglo original y perder los índices.

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
