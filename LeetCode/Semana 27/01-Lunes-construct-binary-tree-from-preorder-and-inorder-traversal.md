# Construct Binary Tree from Preorder and Inorder Traversal

[← Anterior: Time Based Key-Value Store](../Semana%2026/05-Viernes-time-based-key-value-store.md) · [Siguiente: Binary Search Tree Iterator →](../Semana%2027/02-Martes-binary-search-tree-iterator.md)

> [!quote] Para darle con todo
> «Vacía tu mente. Sin forma, como el agua. Be water, my friend.»
> — *Bruce Lee, maestro de artes marciales*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Tree recursion
- **Semana:** 27 — Mixto árboles y grafos (problema 1 de 5)
- **Día:** [Semana 27 — Lunes](../../Semanas/Semana%2027/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Convert Sorted Array to Binary Search Tree](../Semana%2011/02-Martes-convert-sorted-array-to-binary-search-tree.md):** Construyes un árbol dividiendo rangos, como Convert Sorted Array.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `preorder[0]` es la raíz.

> [!question]- Pista 2 — ¿qué estructura usar?
> En el inorder, lo que queda a la izquierda de la raíz es el subárbol izquierdo.

> [!question]- Pista 3 — el algoritmo
> Usa un `Map` de valor → índice en inorder y un índice global sobre preorder.

> [!warning]- Trampa común
> Usar `indexOf` y `slice` en cada llamada: O(n²).

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
