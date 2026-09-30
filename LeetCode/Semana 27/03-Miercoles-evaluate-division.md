# Evaluate Division

[← Anterior: Binary Search Tree Iterator](../Semana%2027/02-Martes-binary-search-tree-iterator.md) · [Siguiente: Is Graph Bipartite? →](../Semana%2027/04-Jueves-is-graph-bipartite.md)

> [!quote] Para darle con todo
> «Stay hungry, stay foolish. Sigue con hambre, sigue con locura.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/evaluate-division/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Weighted graph DFS
- **Semana:** 27 — Mixto árboles y grafos (problema 3 de 5)
- **Día:** [Semana 27 — Miércoles](../../Semanas/Semana%2027/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Find if Path Exists in Graph](../Semana%2013/01-Lunes-find-if-path-exists-in-graph.md):** Es un camino en un grafo, multiplicando los pesos.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `a / b = 2` equivale a las aristas a → b con peso 2 y b → a con peso 1/2.

> [!question]- Pista 2 — ¿qué estructura usar?
> Cada consulta es un DFS de x a y multiplicando los pesos.

> [!question]- Pista 3 — el algoritmo
> Si alguna variable no existe o no hay camino, la respuesta es -1.

> [!warning]- Trampa común
> Olvidar la arista inversa.

> [!success]- Complejidad meta
> Tiempo O(Q·(V + E)), espacio O(V + E)

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
