# Partition Equal Subset Sum

[← Anterior: Longest Common Subsequence](../Semana%2024/03-Miercoles-longest-common-subsequence.md) · [Siguiente: Maximal Square →](../Semana%2024/05-Viernes-maximal-square.md)

> [!quote] Para darle con todo
> «Cuando algo sale mal, solo di: «Good». Ahora tienes algo de qué aprender.»
> — *Jocko Willink, ex Navy SEAL*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/partition-equal-subset-sum/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** DP knapsack
- **Semana:** 24 — DP de dos dimensiones (problema 4 de 5)
- **Día:** [Semana 24 — Jueves](../../Semanas/Semana%2024/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Coin Change](https://leetcode.com/problems/coin-change/):** Es una mochila 0/1: la familia de Coin Change.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si la suma total es impar, es imposible.

> [!question]- Pista 2 — ¿qué estructura usar?
> ¿Existe un subconjunto que sume `total / 2`?

> [!question]- Pista 3 — el algoritmo
> `dp[s]` booleano; recorre `s` de mayor a menor por cada número.

> [!warning]- Trampa común
> Recorrer `s` de menor a mayor: usa el mismo número dos veces.

> [!success]- Complejidad meta
> Tiempo O(n·sum), espacio O(sum)

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
