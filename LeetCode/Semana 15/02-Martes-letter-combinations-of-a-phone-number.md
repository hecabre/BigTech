# Letter Combinations of a Phone Number

[← Anterior: Binary Tree Paths](../Semana%2015/01-Lunes-binary-tree-paths.md) · [Siguiente: Combinations →](../Semana%2015/03-Miercoles-combinations.md)

> [!quote] Para darle con todo
> «Cuando crees que ya no puedes más, apenas vas al 40%.»
> — *David Goggins, la regla del 40%*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Backtracking
- **Semana:** 15 — Backtracking (problema 2 de 5)
- **Día:** [Semana 15 — Martes](../../Semanas/Semana%2015/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Subsets](https://leetcode.com/problems/subsets/):** Es el árbol de decisiones de Subsets: una letra por nivel.
- **Repaso del patrón:** [Backtracking](../../Estudio/Articulos/11-Backtracking.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cada dígito es un nivel y cada letra es una rama.

> [!question]- Pista 2 — ¿qué estructura usar?
> `bt(i, camino)`: si `i === digits.length`, guarda el camino.

> [!question]- Pista 3 — el algoritmo
> Por cada letra de `mapa[digits[i]]`, recursa con `camino + letra`.

> [!warning]- Trampa común
> No devolver `[]` cuando `digits` está vacío.

> [!success]- Complejidad meta
> Tiempo O(4ⁿ·n), espacio O(n)

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
