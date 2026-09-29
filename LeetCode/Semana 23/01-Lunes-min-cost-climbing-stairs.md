# Min Cost Climbing Stairs

[← Anterior: Contiguous Array](../Semana%2022/05-Viernes-contiguous-array.md) · [Siguiente: N-th Tribonacci Number →](../Semana%2023/02-Martes-n-th-tribonacci-number.md)

> [!quote] Para darle con todo
> «Somos lo que hacemos repetidamente. La excelencia, entonces, no es un acto, sino un hábito.»
> — *Will Durant, historiador, resumiendo a Aristóteles*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/min-cost-climbing-stairs/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** DP 1D
- **Semana:** 23 — DP de una dimensión (problema 1 de 5)
- **Día:** [Semana 23 — Lunes](../../Semanas/Semana%2023/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/):** Es Climbing Stairs con costos.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `dp[i]` = el costo mínimo para llegar al escalón i.

> [!question]- Pista 2 — ¿qué estructura usar?
> `dp[i] = min(dp[i-1] + cost[i-1], dp[i-2] + cost[i-2])`.

> [!question]- Pista 3 — el algoritmo
> La cima es el índice n; solo necesitas dos variables.

> [!warning]- Trampa común
> Tomar el último escalón como la cima: la cima está una posición después.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(1)

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
