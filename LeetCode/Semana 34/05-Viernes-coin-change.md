# Coin Change

[← Anterior: Course Schedule](../Semana%2034/04-Jueves-course-schedule.md) · [Siguiente: Reorganize String →](../Semana%2035/01-Lunes-reorganize-string.md)

> [!quote] Para darle con todo
> «Los campeones siguen jugando hasta que les sale bien.»
> — *Billie Jean King, 39 títulos de Grand Slam*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/coin-change/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** DP 1D
- **Semana:** 34 — Últimos patrones nuevos (problema 5 de 5)
- **Día:** [Semana 34 — Viernes](../../Semanas/Semana%2034/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/):** Es Climbing Stairs, donde cada moneda es un tamaño de paso.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `dp[a]` = el mínimo de monedas para formar a.

> [!question]- Pista 2 — ¿qué estructura usar?
> `dp[0] = 0` y el resto empieza en `Infinity`.

> [!question]- Pista 3 — el algoritmo
> `dp[a] = min(dp[a], dp[a - c] + 1)` para cada moneda c `<= a`.

> [!warning]- Trampa común
> Usar greedy (la moneda más grande primero): falla con `[1, 3, 4]` y 6.

> [!success]- Complejidad meta
> Tiempo O(amount·coins), espacio O(amount)

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
