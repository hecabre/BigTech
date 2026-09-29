# Network Delay Time

[← Anterior: Top K Frequent Words](../Semana%2028/05-Viernes-top-k-frequent-words.md) · [Siguiente: Cheapest Flights Within K Stops →](../Semana%2029/02-Martes-cheapest-flights-within-k-stops.md)

> [!quote] Para darle con todo
> «Lo que no puedo crear, no lo entiendo.»
> — *Richard Feynman, Nobel de Física; estaba escrito en su pizarrón*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/network-delay-time/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Dijkstra
- **Semana:** 29 — Caminos más cortos (problema 1 de 5)
- **Día:** [Semana 29 — Lunes](../../Semanas/Semana%2029/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Shortest Path in Binary Matrix](../Semana%2014/04-Jueves-shortest-path-in-binary-matrix.md):** Es el BFS de camino más corto, pero con pesos: eso es Dijkstra.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Con pesos, BFS ya no garantiza el camino más corto.

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa un min-heap `[distancia, nodo]` empezando en `[0, k]`.

> [!question]- Pista 3 — el algoritmo
> Al sacar un nodo ya visitado, ignóralo. La respuesta es la distancia máxima, o -1 si faltan nodos.

> [!warning]- Trampa común
> Marcar un nodo como visitado al meterlo al heap y no al sacarlo.

> [!success]- Complejidad meta
> Tiempo O(E log V), espacio O(V + E)

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
