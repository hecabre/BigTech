# Redundant Connection

[← Anterior: Find All Possible Recipes from Given Supplies](../Semana%2025/04-Jueves-find-all-possible-recipes-from-given-supplies.md) · [Siguiente: Design HashMap →](../Semana%2026/01-Lunes-design-hashmap.md)

> [!quote] Para darle con todo
> «Sin terquedad, abandonas los experimentos demasiado pronto. Sin flexibilidad, te das de topes contra la pared y no ves otra solución.»
> — *Jeff Bezos, fundador de Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/redundant-connection/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Union-Find
- **Semana:** 25 — Orden topológico y Union-Find (problema 5 de 5)
- **Día:** [Semana 25 — Viernes](../../Semanas/Semana%2025/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Number of Provinces](../Semana%2013/05-Viernes-number-of-provinces.md):** Es Union-Find, la otra forma de resolver Number of Provinces.
- **Repaso del patrón:** [Orden topológico](../../Estudio/Articulos/15-Orden-topologico.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> La arista redundante es la que une dos nodos que ya estaban conectados.

> [!question]- Pista 2 — ¿qué estructura usar?
> Union-Find con `find` (con compresión de camino) y `union`.

> [!question]- Pista 3 — el algoritmo
> Si `find(a) === find(b)`, devuelve esa arista.

> [!warning]- Trampa común
> No aplicar compresión de camino y que `find` se vuelva lento.

> [!success]- Complejidad meta
> Tiempo O(n·α(n)), espacio O(n)

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
