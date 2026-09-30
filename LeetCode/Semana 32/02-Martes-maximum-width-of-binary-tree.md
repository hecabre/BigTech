# Maximum Width of Binary Tree

[← Anterior: All Nodes Distance K in Binary Tree](../Semana%2032/01-Lunes-all-nodes-distance-k-in-binary-tree.md) · [Siguiente: Serialize and Deserialize Binary Tree →](../Semana%2032/03-Miercoles-serialize-and-deserialize-binary-tree.md)

> [!quote] Para darle con todo
> «El mérito pertenece a quien está realmente en la arena, con la cara manchada de polvo, sudor y sangre.»
> — *Theodore Roosevelt, «El hombre en la arena», 1910*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/maximum-width-of-binary-tree/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Tree BFS
- **Semana:** 32 — Árboles nivel entrevista (problema 2 de 5)
- **Día:** [Semana 32 — Martes](../../Semanas/Semana%2032/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Binary Tree Zigzag Level Order Traversal](../Semana%2010/05-Viernes-binary-tree-zigzag-level-order-traversal.md):** Es BFS por niveles numerando los nodos.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Numera los nodos como en un heap: los hijos de i son `2i` y `2i + 1`.

> [!question]- Pista 2 — ¿qué estructura usar?
> El ancho de un nivel es `último - primero + 1`.

> [!question]- Pista 3 — el algoritmo
> Resta el índice del primero de cada nivel para evitar overflow (o usa BigInt).

> [!warning]- Trampa común
> Usar índices que crecen sin normalizarse y se desbordan.

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
