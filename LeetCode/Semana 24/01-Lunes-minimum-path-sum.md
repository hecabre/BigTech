# Minimum Path Sum

[← Anterior: Word Break](../Semana%2023/05-Viernes-word-break.md) · [Siguiente: Longest Increasing Subsequence →](../Semana%2024/02-Martes-longest-increasing-subsequence.md)

> [!quote] Para darle con todo
> «La mejor forma de predecir el futuro es inventarlo.»
> — *Alan Kay, pionero de la programación orientada a objetos*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/minimum-path-sum/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** DP 2D
- **Semana:** 24 — DP de dos dimensiones (problema 1 de 5)
- **Día:** [Semana 24 — Lunes](../../Semanas/Semana%2024/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Unique Paths](https://leetcode.com/problems/unique-paths/):** Es Unique Paths, pero con `min` en lugar de suma.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Solo puedes llegar desde arriba o desde la izquierda.

> [!question]- Pista 2 — ¿qué estructura usar?
> `dp[r][c] = grid[r][c] + min(arriba, izquierda)`.

> [!question]- Pista 3 — el algoritmo
> La primera fila y la primera columna solo tienen un camino.

> [!warning]- Trampa común
> No inicializar la primera fila y la primera columna.

> [!success]- Complejidad meta
> Tiempo O(m·n), espacio O(n)

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
