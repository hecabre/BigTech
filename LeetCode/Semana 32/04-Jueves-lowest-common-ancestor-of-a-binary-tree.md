# Lowest Common Ancestor of a Binary Tree

[← Anterior: Serialize and Deserialize Binary Tree](../Semana%2032/03-Miercoles-serialize-and-deserialize-binary-tree.md) · [Siguiente: Binary Tree Zigzag Level Order Traversal →](../Semana%2032/05-Viernes-binary-tree-zigzag-level-order-traversal.md)

> [!quote] Para darle con todo
> «Cuando algo sale mal, solo di: «Good». Ahora tienes algo de qué aprender.»
> — *Jocko Willink, ex Navy SEAL*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Tree DFS
- **Semana:** 32 — Árboles nivel entrevista (problema 4 de 5)
- **Día:** [Semana 32 — Jueves](../../Semanas/Semana%2032/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

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
