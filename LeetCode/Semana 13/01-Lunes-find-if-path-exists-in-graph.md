# Find if Path Exists in Graph

[← Anterior: Task Scheduler](../Semana%2012/05-Viernes-task-scheduler.md) · [Siguiente: Find the Town Judge →](../Semana%2013/02-Martes-find-the-town-judge.md)

> [!quote] Para darle con todo
> «Lo que no puedo crear, no lo entiendo.»
> — *Richard Feynman, Nobel de Física; estaba escrito en su pizarrón*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/find-if-path-exists-in-graph/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Graph DFS/BFS
- **Semana:** 13 — Grafos — introducción (problema 1 de 5)
- **Día:** [Semana 13 — Lunes](../../Semanas/Semana%2013/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Flood Fill](https://leetcode.com/problems/flood-fill/):** Es el DFS de Flood Fill, pero en una lista de adyacencia.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Construye la lista de adyacencia: `adj[u].push(v)` y `adj[v].push(u)`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Haz DFS o BFS desde `source` con un `Set` de visitados.

> [!question]- Pista 3 — el algoritmo
> Si visitas `destination`, devuelve true.

> [!warning]- Trampa común
> Olvidar que el grafo es no dirigido y agregar solo una dirección.

> [!success]- Complejidad meta
> Tiempo O(V + E), espacio O(V + E)

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
