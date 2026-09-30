# Subtree of Another Tree

[← Anterior: Balanced Binary Tree](../Semana%2009/04-Jueves-balanced-binary-tree.md) · [Siguiente: Minimum Depth of Binary Tree →](../Semana%2010/01-Lunes-minimum-depth-of-binary-tree.md)

> [!quote] Para darle con todo
> «Sin terquedad, abandonas los experimentos demasiado pronto. Sin flexibilidad, te das de topes contra la pared y no ves otra solución.»
> — *Jeff Bezos, fundador de Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/subtree-of-another-tree/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Tree DFS
- **Semana:** 09 — Árboles — DFS (problema 5 de 5)
- **Día:** [Semana 09 — Viernes](../../Semanas/Semana%2009/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Same Tree](https://leetcode.com/problems/same-tree/):** Es Same Tree aplicado en cada nodo.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Reutiliza `sameTree(a, b)`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Para cada nodo de `root`, pregunta si `sameTree(nodo, subRoot)`.

> [!question]- Pista 3 — el algoritmo
> `isSub(root) = same(root, sub) || isSub(root.left) || isSub(root.right)`.

> [!warning]- Trampa común
> Comparar solo valores y no la estructura completa.

> [!success]- Complejidad meta
> Tiempo O(n·m), espacio O(h)

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
