# Cheapest Flights Within K Stops

[← Anterior: Network Delay Time](../Semana%2029/01-Lunes-network-delay-time.md) · [Siguiente: Path With Minimum Effort →](../Semana%2029/03-Miercoles-path-with-minimum-effort.md)

> [!quote] Para darle con todo
> «Todo lo negativo —la presión, los retos— es una oportunidad para elevarme.»
> — *Kobe Bryant, cinco veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/cheapest-flights-within-k-stops/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** BFS / Bellman-Ford
- **Semana:** 29 — Caminos más cortos (problema 2 de 5)
- **Día:** [Semana 29 — Martes](../../Semanas/Semana%2029/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Network Delay Time](../Semana%2029/01-Lunes-network-delay-time.md):** Es un camino más corto con un límite de pasos.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> El límite de paradas rompe la versión normal de Dijkstra.

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa Bellman-Ford limitado: repite k + 1 rondas de relajación.

> [!question]- Pista 3 — el algoritmo
> En cada ronda, trabaja sobre una COPIA de las distancias.

> [!warning]- Trampa común
> Relajar sobre el mismo arreglo y usar más vuelos de los permitidos en una sola ronda.

> [!success]- Complejidad meta
> Tiempo O(k·E), espacio O(V)

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
