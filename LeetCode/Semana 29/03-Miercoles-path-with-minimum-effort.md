# Path With Minimum Effort

[← Anterior: Cheapest Flights Within K Stops](../Semana%2029/02-Martes-cheapest-flights-within-k-stops.md) · [Siguiente: Word Ladder →](../Semana%2029/04-Jueves-word-ladder.md)

> [!quote] Para darle con todo
> «Disciplina es libertad.»
> — *Jocko Willink, ex Navy SEAL*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/path-with-minimum-effort/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Dijkstra en grid
- **Semana:** 29 — Caminos más cortos (problema 3 de 5)
- **Día:** [Semana 29 — Miércoles](../../Semanas/Semana%2029/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Network Delay Time](../Semana%2029/01-Lunes-network-delay-time.md):** Es Dijkstra en un grid; el costo es el máximo del camino, no la suma.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> El esfuerzo de un camino es el mayor salto de altura que contiene.

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa Dijkstra con `nuevo = max(esfuerzoActual, |h1 - h2|)`.

> [!question]- Pista 3 — el algoritmo
> Alternativa: búsqueda binaria sobre el esfuerzo más un BFS.

> [!warning]- Trampa común
> Sumar las diferencias en lugar de tomar el máximo.

> [!success]- Complejidad meta
> Tiempo O(m·n log(m·n)), espacio O(m·n)

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
