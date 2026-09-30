# Minimum Height Trees

[← Anterior: Find Eventual Safe States](../Semana%2025/01-Lunes-find-eventual-safe-states.md) · [Siguiente: All Ancestors of a Node in a Directed Acyclic Graph →](../Semana%2025/03-Miercoles-all-ancestors-of-a-node-in-a-directed-acyclic-graph.md)

> [!quote] Para darle con todo
> «La mentalidad Mamba no se trata de buscar un resultado; se trata del proceso de llegar a ese resultado.»
> — *Kobe Bryant, The Mamba Mentality*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/minimum-height-trees/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Topological sort (hojas)
- **Semana:** 25 — Orden topológico y Union-Find (problema 2 de 5)
- **Día:** [Semana 25 — Martes](../../Semanas/Semana%2025/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Course Schedule](https://leetcode.com/problems/course-schedule/):** Es el mismo Kahn: quitar nodos de grado 1 por capas.
- **Repaso del patrón:** [Orden topológico](../../Estudio/Articulos/15-Orden-topologico.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Los centros del árbol son las raíces de altura mínima.

> [!question]- Pista 2 — ¿qué estructura usar?
> Mete todas las hojas (grado 1) en una cola.

> [!question]- Pista 3 — el algoritmo
> Quita capas de hojas hasta que queden 1 o 2 nodos.

> [!warning]- Trampa común
> Hacer un BFS desde cada nodo: es O(n²).

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(n)

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
