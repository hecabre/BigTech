# Minimum Depth of Binary Tree

[← Anterior: Subtree of Another Tree](../Semana%2009/05-Viernes-subtree-of-another-tree.md) · [Siguiente: Average of Levels in Binary Tree →](../Semana%2010/02-Martes-average-of-levels-in-binary-tree.md)

> [!quote] Para darle con todo
> «The Marathon Continues. El maratón continúa.»
> — *Nipsey Hussle, rapero y empresario*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/minimum-depth-of-binary-tree/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Tree BFS
- **Semana:** 10 — Árboles — BFS por niveles (problema 1 de 5)
- **Día:** [Semana 10 — Lunes](../../Semanas/Semana%2010/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/):** Es BFS por niveles: la primera hoja que aparezca es la respuesta.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> ¿Por qué `1 + min(L, R)` falla cuando un hijo es null?

> [!question]- Pista 2 — ¿qué estructura usar?
> Con BFS, la primera hoja que encuentras está a la profundidad mínima.

> [!question]- Pista 3 — el algoritmo
> Guarda `[nodo, profundidad]` en la cola y devuelve al ver una hoja.

> [!warning]- Trampa común
> Contar un hijo null como profundidad 0: un nodo con un solo hijo no es hoja.

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
