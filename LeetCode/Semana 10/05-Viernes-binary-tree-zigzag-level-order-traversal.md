# Binary Tree Zigzag Level Order Traversal

[← Anterior: Binary Tree Right Side View](../Semana%2010/04-Jueves-binary-tree-right-side-view.md) · [Siguiente: Search in a Binary Search Tree →](../Semana%2011/01-Lunes-search-in-a-binary-search-tree.md)

> [!quote] Para darle con todo
> «Los campeones siguen jugando hasta que les sale bien.»
> — *Billie Jean King, 39 títulos de Grand Slam*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Tree BFS
- **Semana:** 10 — Árboles — BFS por niveles (problema 5 de 5)
- **Día:** [Semana 10 — Viernes](../../Semanas/Semana%2010/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/):** Es Level Order más una bandera de dirección.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Haz BFS normal por niveles.

> [!question]- Pista 2 — ¿qué estructura usar?
> Alterna una bandera `izqADer` en cada nivel.

> [!question]- Pista 3 — el algoritmo
> Si la bandera es false, invierte el arreglo del nivel antes de guardarlo.

> [!warning]- Trampa común
> Cambiar el orden en que agregas a los hijos a la cola: eso rompe los niveles siguientes.

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
