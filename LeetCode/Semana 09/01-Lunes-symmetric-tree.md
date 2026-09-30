# Symmetric Tree

[← Anterior: Find First and Last Position of Element in Sorted Array](../Semana%2008/05-Viernes-find-first-and-last-position-of-element-in-sorted-array.md) · [Siguiente: Path Sum →](../Semana%2009/02-Martes-path-sum.md)

> [!quote] Para darle con todo
> «No hay que llegar primero, pero hay que saber llegar.»
> — *José Alfredo Jiménez, «El Rey»*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/symmetric-tree/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Tree DFS
- **Semana:** 09 — Árboles — DFS (problema 1 de 5)
- **Día:** [Semana 09 — Lunes](../../Semanas/Semana%2009/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Same Tree](https://leetcode.com/problems/same-tree/):** Es Same Tree, pero comparando en espejo.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Un árbol es simétrico si su subárbol izquierdo es el espejo del derecho.

> [!question]- Pista 2 — ¿qué estructura usar?
> Escribe `espejo(a, b)`: ambos null → true; uno null → false.

> [!question]- Pista 3 — el algoritmo
> `a.val === b.val && espejo(a.left, b.right) && espejo(a.right, b.left)`.

> [!warning]- Trampa común
> Comparar `left` con `left` como en Same Tree.

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
