# Time Based Key-Value Store

[← Anterior: Insert Delete GetRandom O(1)](../Semana%2026/04-Jueves-insert-delete-getrandom-o1.md) · [Siguiente: Construct Binary Tree from Preorder and Inorder Traversal →](../Semana%2027/01-Lunes-construct-binary-tree-from-preorder-and-inorder-traversal.md)

> [!quote] Para darle con todo
> «Los campeones siguen jugando hasta que les sale bien.»
> — *Billie Jean King, 39 títulos de Grand Slam*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/time-based-key-value-store/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Hash map + binary search
- **Semana:** 26 — Diseño de estructuras (POO) (problema 5 de 5)
- **Día:** [Semana 26 — Viernes](../../Semanas/Semana%2026/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Search Insert Position](../Semana%2008/01-Lunes-search-insert-position.md):** Es un `Map` más la búsqueda binaria de Search Insert Position.
- **Repaso del patrón:** [POO y diseño](../../Estudio/Articulos/16-POO-y-SOLID.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Los timestamps llegan en orden creciente.

> [!question]- Pista 2 — ¿qué estructura usar?
> `Map<key, [[t, v], …]>`.

> [!question]- Pista 3 — el algoritmo
> En `get`, busca con búsqueda binaria el mayor `t <= timestamp`.

> [!warning]- Trampa común
> Recorrer la lista linealmente.

> [!success]- Complejidad meta
> Tiempo O(log n) en `get`, espacio O(n)

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
