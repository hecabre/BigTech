# Binary Tree Zigzag Level Order Traversal

[← Anterior: Lowest Common Ancestor of a Binary Tree](../Semana%2032/04-Jueves-lowest-common-ancestor-of-a-binary-tree.md) · [Siguiente: Two Sum →](../Semana%2033/01-Lunes-two-sum.md)

> [!quote] Para darle con todo
> «Tu tiempo es limitado, así que no lo desperdicies viviendo la vida de alguien más.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Tree BFS
- **Semana:** 32 — Árboles nivel entrevista (problema 5 de 5)
- **Día:** [Semana 32 — Viernes](../../Semanas/Semana%2032/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

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
