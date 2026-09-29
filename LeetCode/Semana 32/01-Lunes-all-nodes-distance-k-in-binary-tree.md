# All Nodes Distance K in Binary Tree

[← Anterior: Merge Intervals](../Semana%2031/05-Viernes-merge-intervals.md) · [Siguiente: Maximum Width of Binary Tree →](../Semana%2032/02-Martes-maximum-width-of-binary-tree.md)

> [!quote] Para darle con todo
> «La mejor forma de predecir el futuro es inventarlo.»
> — *Alan Kay, pionero de la programación orientada a objetos*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Tree → grafo + BFS
- **Semana:** 32 — Árboles nivel entrevista (problema 1 de 5)
- **Día:** [Semana 32 — Lunes](../../Semanas/Semana%2032/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Rotting Oranges](https://leetcode.com/problems/rotting-oranges/):** Conviertes el árbol en un grafo y luego haces BFS por capas, como Rotting Oranges.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> En un árbol solo puedes bajar, pero aquí también necesitas subir.

> [!question]- Pista 2 — ¿qué estructura usar?
> Con un DFS, guarda `padre[nodo]`.

> [!question]- Pista 3 — el algoritmo
> Haz BFS desde el target durante k niveles, con visitados, sobre izquierda, derecha y padre.

> [!warning]- Trampa común
> Olvidar el conjunto de visitados y regresar al nodo de donde viniste.

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
