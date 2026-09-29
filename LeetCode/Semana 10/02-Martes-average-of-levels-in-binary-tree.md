# Average of Levels in Binary Tree

[← Anterior: Minimum Depth of Binary Tree](../Semana%2010/01-Lunes-minimum-depth-of-binary-tree.md) · [Siguiente: Merge Two Binary Trees →](../Semana%2010/03-Miercoles-merge-two-binary-trees.md)

> [!quote] Para darle con todo
> «El primer principio es no autoengañarte, y la persona más fácil de engañar eres tú.»
> — *Richard Feynman, Nobel de Física*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/average-of-levels-in-binary-tree/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Tree BFS
- **Semana:** 10 — Árboles — BFS por niveles (problema 2 de 5)
- **Día:** [Semana 10 — Martes](../../Semanas/Semana%2010/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/):** Es Level Order Traversal: en lugar de guardar la lista de cada nivel, lo promedias.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Procesa la cola nivel por nivel.

> [!question]- Pista 2 — ¿qué estructura usar?
> Guarda `size = queue.length` antes de recorrer el nivel.

> [!question]- Pista 3 — el algoritmo
> Suma los `size` nodos y agrega `suma / size`.

> [!warning]- Trampa común
> Leer `queue.length` dentro del ciclo mientras la cola sigue creciendo.

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
