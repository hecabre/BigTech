# Non-overlapping Intervals

[← Anterior: Summary Ranges](../Semana%2018/01-Lunes-summary-ranges.md) · [Siguiente: Minimum Number of Arrows to Burst Balloons →](../Semana%2018/03-Miercoles-minimum-number-of-arrows-to-burst-balloons.md)

> [!quote] Para darle con todo
> «El primer principio es no autoengañarte, y la persona más fácil de engañar eres tú.»
> — *Richard Feynman, Nobel de Física*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/non-overlapping-intervals/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Intervalos greedy
- **Semana:** 18 — Intervalos y greedy (problema 2 de 5)
- **Día:** [Semana 18 — Martes](../../Semanas/Semana%2018/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Merge Intervals](https://leetcode.com/problems/merge-intervals/):** Es Merge Intervals, pero ordenando por el final.
- **Repaso del patrón:** [Greedy e intervalos](../../Estudio/Articulos/12-Greedy-e-intervalos.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Quieres conservar la mayor cantidad posible de intervalos sin choques.

> [!question]- Pista 2 — ¿qué estructura usar?
> Ordena por el final: el que termina antes deja más espacio.

> [!question]- Pista 3 — el algoritmo
> Recorre; si `start < finAnterior`, elimínalo (+1); si no, actualiza `finAnterior`.

> [!warning]- Trampa común
> Ordenar por el inicio y elegir mal cuál eliminar.

> [!success]- Complejidad meta
> Tiempo O(n log n), espacio O(1)

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
