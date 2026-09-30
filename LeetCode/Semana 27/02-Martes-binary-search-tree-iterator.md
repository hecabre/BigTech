# Binary Search Tree Iterator

[← Anterior: Construct Binary Tree from Preorder and Inorder Traversal](../Semana%2027/01-Lunes-construct-binary-tree-from-preorder-and-inorder-traversal.md) · [Siguiente: Evaluate Division →](../Semana%2027/03-Miercoles-evaluate-division.md)

> [!quote] Para darle con todo
> «Corres el peligro de vivir una vida tan cómoda y blanda que te mueras sin descubrir tu verdadero potencial.»
> — *David Goggins, Can't Hurt Me*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/binary-search-tree-iterator/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** BST + Stack
- **Semana:** 27 — Mixto árboles y grafos (problema 2 de 5)
- **Día:** [Semana 27 — Martes](../../Semanas/Semana%2027/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Kth Smallest Element in a BST](../Semana%2011/04-Jueves-kth-smallest-element-in-a-bst.md):** Es el inorder de Kth Smallest, pero pausado.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Usa una pila con el camino hacia el menor.

> [!question]- Pista 2 — ¿qué estructura usar?
> Constructor: empuja todos los izquierdos desde la raíz.

> [!question]- Pista 3 — el algoritmo
> `next`: haz `pop`, empuja los izquierdos de su hijo derecho y devuelve el valor.

> [!warning]- Trampa común
> Guardar todo el inorder en un arreglo: usa O(n) de espacio en lugar de O(h).

> [!success]- Complejidad meta
> Tiempo O(1) amortizado, espacio O(h)

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
