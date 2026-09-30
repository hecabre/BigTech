# Word Break

[← Anterior: Decode Ways](../Semana%2023/04-Jueves-decode-ways.md) · [Siguiente: Minimum Path Sum →](../Semana%2024/01-Lunes-minimum-path-sum.md)

> [!quote] Para darle con todo
> «Disciplina es hacer lo que odias como si lo amaras.»
> — *Mike Tyson, campeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/word-break/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** DP 1D
- **Semana:** 23 — DP de una dimensión (problema 5 de 5)
- **Día:** [Semana 23 — Viernes](../../Semanas/Semana%2023/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Decode Ways](../Semana%2023/04-Jueves-decode-ways.md):** Es la misma DP de prefijos, con palabras de tamaño variable.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `dp[i]` = ¿los primeros i caracteres se pueden segmentar?

> [!question]- Pista 2 — ¿qué estructura usar?
> `dp[0] = true`.

> [!question]- Pista 3 — el algoritmo
> `dp[i]` es true si existe j con `dp[j]` y `s.slice(j, i)` en el diccionario (usa un `Set`).

> [!warning]- Trampa común
> Hacer backtracking sin memo: es exponencial.

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
