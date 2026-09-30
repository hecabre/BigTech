# Serialize and Deserialize Binary Tree

[← Anterior: Maximum Width of Binary Tree](../Semana%2032/02-Martes-maximum-width-of-binary-tree.md) · [Siguiente: Lowest Common Ancestor of a Binary Tree →](../Semana%2032/04-Jueves-lowest-common-ancestor-of-a-binary-tree.md)

> [!quote] Para darle con todo
> «Puedo aceptar el fracaso; todos fallan en algo. Lo que no puedo aceptar es no intentarlo.»
> — *Michael Jordan, seis veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)
- **Dificultad:** Hard
- **Tipo:** Nuevo
- **Patrón:** Tree DFS/BFS
- **Semana:** 32 — Árboles nivel entrevista (problema 3 de 5)
- **Día:** [Semana 32 — Miércoles](../../Semanas/Semana%2032/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!warning] Hard
> Límite de 45 minutos. Si no sale, estudia la solución y reintenta en 7 días. No cuenta como fracaso.

## Por qué este problema

- **Se conecta con [Construct Binary Tree from Preorder and Inorder Traversal](../Semana%2027/01-Lunes-construct-binary-tree-from-preorder-and-inorder-traversal.md):** Es reconstruir un árbol, ahora marcando los nulls.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> El preorder con marcadores de null (`#`) define el árbol de forma única.

> [!question]- Pista 2 — ¿qué estructura usar?
> `serialize`: DFS preorder que une los valores con `,`.

> [!question]- Pista 3 — el algoritmo
> `deserialize`: usa un índice global; `#` devuelve null y cualquier otro valor crea un nodo y recursa izquierda y luego derecha.

> [!warning]- Trampa común
> No marcar los nulls y perder la estructura.

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
