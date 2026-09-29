# Number of Islands

[← Anterior: Shortest Path in Binary Matrix](../Semana%2014/04-Jueves-shortest-path-in-binary-matrix.md) · [Siguiente: Binary Tree Paths →](../Semana%2015/01-Lunes-binary-tree-paths.md)

> [!quote] Para darle con todo
> «Lo que define a quien es campeón no son sus victorias, sino cómo se recupera cuando cae.»
> — *Serena Williams, 23 títulos de Grand Slam*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/number-of-islands/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Grid DFS
- **Semana:** 14 — Grafos — BFS y grids (problema 5 de 5)
- **Día:** [Semana 14 — Viernes](../../Semanas/Semana%2014/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Flood Fill](https://leetcode.com/problems/flood-fill/):** Es Flood Fill repetido por cada isla nueva.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Recorre todas las celdas.

> [!question]- Pista 2 — ¿qué estructura usar?
> Al encontrar un `'1'` no visitado, suma 1 y hunde toda la isla con DFS.

> [!question]- Pista 3 — el algoritmo
> Hundir = cambiar a `'0'` antes de recursar en las 4 direcciones.

> [!warning]- Trampa común
> Comparar con el número `1` cuando el grid tiene strings `'1'`.

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
