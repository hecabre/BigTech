# Lowest Common Ancestor of a Binary Tree

[← Anterior: Kth Smallest Element in a BST](../Semana%2011/04-Jueves-kth-smallest-element-in-a-bst.md) · [Siguiente: Kth Largest Element in a Stream →](../Semana%2012/01-Lunes-kth-largest-element-in-a-stream.md)

> [!quote] Para darle con todo
> «Trabaja duro, diviértete, haz historia.»
> — *Jeff Bezos, lema de Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Tree DFS
- **Semana:** 11 — BST (problema 5 de 5)
- **Día:** [Semana 11 — Viernes](../../Semanas/Semana%2011/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Lowest Common Ancestor of a BST](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/):** Es LCA sin la ayuda del orden del BST.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si el nodo es null, p o q, devuélvelo.

> [!question]- Pista 2 — ¿qué estructura usar?
> Busca en los dos lados: `L = lca(left)` y `R = lca(right)`.

> [!question]- Pista 3 — el algoritmo
> Si L y R existen, el nodo actual es el LCA; si no, devuelve el que exista.

> [!warning]- Trampa común
> Pensar que primero necesitas los caminos completos a p y a q.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(h)

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
