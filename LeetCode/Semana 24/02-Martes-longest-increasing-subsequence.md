# Longest Increasing Subsequence

[← Anterior: Minimum Path Sum](../Semana%2024/01-Lunes-minimum-path-sum.md) · [Siguiente: Longest Common Subsequence →](../Semana%2024/03-Miercoles-longest-common-subsequence.md)

> [!quote] Para darle con todo
> «El mérito pertenece a quien está realmente en la arena, con la cara manchada de polvo, sudor y sangre.»
> — *Theodore Roosevelt, «El hombre en la arena», 1910*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/longest-increasing-subsequence/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** DP 1D
- **Semana:** 24 — DP de dos dimensiones (problema 2 de 5)
- **Día:** [Semana 24 — Martes](../../Semanas/Semana%2024/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [House Robber](https://leetcode.com/problems/house-robber/):** Es DP donde cada estado mira hacia todos los anteriores.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `dp[i]` = la LIS que TERMINA en i.

> [!question]- Pista 2 — ¿qué estructura usar?
> `dp[i] = 1 + max(dp[j])` para cada `j < i` con `nums[j] < nums[i]`.

> [!question]- Pista 3 — el algoritmo
> La respuesta es `max(dp)`. Reto: O(n log n) con búsqueda binaria.

> [!warning]- Trampa común
> Devolver `dp[n - 1]` en lugar del máximo.

> [!success]- Complejidad meta
> Tiempo O(n²), espacio O(n)

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
