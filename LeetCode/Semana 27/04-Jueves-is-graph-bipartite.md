# Is Graph Bipartite?

[← Anterior: Evaluate Division](../Semana%2027/03-Miercoles-evaluate-division.md) · [Siguiente: Copy List with Random Pointer →](../Semana%2027/05-Viernes-copy-list-with-random-pointer.md)

> [!quote] Para darle con todo
> «La simplicidad es requisito para la confiabilidad.»
> — *Edsger Dijkstra, Premio Turing*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/is-graph-bipartite/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Graph coloring
- **Semana:** 27 — Mixto árboles y grafos (problema 4 de 5)
- **Día:** [Semana 27 — Jueves](../../Semanas/Semana%2027/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Number of Provinces](../Semana%2013/05-Viernes-number-of-provinces.md):** Es un recorrido por componentes, pero coloreando.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Colorea cada nodo con 0 o 1; los vecinos deben tener colores distintos.

> [!question]- Pista 2 — ¿qué estructura usar?
> BFS o DFS desde cada nodo sin color (el grafo puede estar desconectado).

> [!question]- Pista 3 — el algoritmo
> Si un vecino tiene el mismo color, la respuesta es false.

> [!warning]- Trampa común
> Revisar solo el componente del nodo 0.

> [!success]- Complejidad meta
> Tiempo O(V + E), espacio O(V)

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
