# Surrounded Regions

[← Anterior: 01 Matrix](../Semana%2014/02-Martes-01-matrix.md) · [Siguiente: Shortest Path in Binary Matrix →](../Semana%2014/04-Jueves-shortest-path-in-binary-matrix.md)

> [!quote] Para darle con todo
> «Sabía que si fallaba no me iba a arrepentir. Lo único de lo que me podría arrepentir era de no haberlo intentado.»
> — *Jeff Bezos, sobre dejar su trabajo para fundar Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/surrounded-regions/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Grid DFS
- **Semana:** 14 — Grafos — BFS y grids (problema 3 de 5)
- **Día:** [Semana 14 — Miércoles](../../Semanas/Semana%2014/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Max Area of Island](../Semana%2013/04-Jueves-max-area-of-island.md):** Es DFS en un grid, pero empezando desde los bordes.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> ¿Qué `O` NO se capturan? Las conectadas a un borde.

> [!question]- Pista 2 — ¿qué estructura usar?
> Haz DFS desde cada `O` del borde y márcalas como seguras (por ejemplo, `#`).

> [!question]- Pista 3 — el algoritmo
> Al final: `O` → `X` y `#` → `O`.

> [!warning]- Trampa común
> Intentar decidir cada región desde adentro hacia afuera.

> [!success]- Complejidad meta
> Tiempo O(filas·cols), espacio O(filas·cols)

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
