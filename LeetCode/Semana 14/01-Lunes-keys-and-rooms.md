# Keys and Rooms

[← Anterior: Number of Provinces](../Semana%2013/05-Viernes-number-of-provinces.md) · [Siguiente: 01 Matrix →](../Semana%2014/02-Martes-01-matrix.md)

> [!quote] Para darle con todo
> «Aquí no hay talento. Esto es trabajo duro. Esto es una obsesión.»
> — *Conor McGregor, campeón de UFC en dos divisiones*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/keys-and-rooms/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Graph DFS
- **Semana:** 14 — Grafos — BFS y grids (problema 1 de 5)
- **Día:** [Semana 14 — Lunes](../../Semanas/Semana%2014/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Find if Path Exists in Graph](../Semana%2013/01-Lunes-find-if-path-exists-in-graph.md):** Es alcanzabilidad desde un nodo, como Find if Path Exists.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cada cuarto es un nodo y cada llave es una arista.

> [!question]- Pista 2 — ¿qué estructura usar?
> DFS desde el cuarto 0 con un `Set` de visitados.

> [!question]- Pista 3 — el algoritmo
> Al final, ¿`visitados.size === rooms.length`?

> [!warning]- Trampa común
> Olvidar marcar los cuartos como visitados y entrar en un ciclo.

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
