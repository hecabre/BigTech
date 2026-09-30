# Merge Two Binary Trees

[← Anterior: Average of Levels in Binary Tree](../Semana%2010/02-Martes-average-of-levels-in-binary-tree.md) · [Siguiente: Binary Tree Right Side View →](../Semana%2010/04-Jueves-binary-tree-right-side-view.md)

> [!quote] Para darle con todo
> «Cuando algo es lo suficientemente importante, lo haces aunque las probabilidades no estén a tu favor.»
> — *Elon Musk, fundador de SpaceX*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/merge-two-binary-trees/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Tree DFS
- **Semana:** 10 — Árboles — BFS por niveles (problema 3 de 5)
- **Día:** [Semana 10 — Miércoles](../../Semanas/Semana%2010/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/):** Es la recursión de Invert Binary Tree construyendo un árbol nuevo.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si uno de los dos es null, devuelve el otro.

> [!question]- Pista 2 — ¿qué estructura usar?
> Si no, suma los valores.

> [!question]- Pista 3 — el algoritmo
> Asigna `left = merge(a.left, b.left)` y `right = merge(a.right, b.right)`.

> [!warning]- Trampa común
> Crear nodos nuevos cuando uno de los dos es null (no hace falta).

> [!success]- Complejidad meta
> Tiempo O(min(n, m)), espacio O(h)

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
