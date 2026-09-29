# Longest Common Subsequence

[← Anterior: Longest Increasing Subsequence](../Semana%2024/02-Martes-longest-increasing-subsequence.md) · [Siguiente: Partition Equal Subset Sum →](../Semana%2024/04-Jueves-partition-equal-subset-sum.md)

> [!quote] Para darle con todo
> «Puedo aceptar el fracaso; todos fallan en algo. Lo que no puedo aceptar es no intentarlo.»
> — *Michael Jordan, seis veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/longest-common-subsequence/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** DP 2D
- **Semana:** 24 — DP de dos dimensiones (problema 3 de 5)
- **Día:** [Semana 24 — Miércoles](../../Semanas/Semana%2024/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Minimum Path Sum](../Semana%2024/01-Lunes-minimum-path-sum.md):** Es una tabla 2D como Minimum Path Sum.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `dp[i][j]` = la LCS de `a[0..i)` y `b[0..j)`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Si `a[i-1] === b[j-1]`: `dp[i-1][j-1] + 1`.

> [!question]- Pista 3 — el algoritmo
> Si no: `max(dp[i-1][j], dp[i][j-1])`.

> [!warning]- Trampa común
> Errores de índices por no usar una tabla de tamaño (n+1)×(m+1).

> [!success]- Complejidad meta
> Tiempo O(n·m), espacio O(n·m)

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
