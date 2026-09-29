# Decode Ways

[← Anterior: House Robber II](../Semana%2023/03-Miercoles-house-robber-ii.md) · [Siguiente: Word Break →](../Semana%2023/05-Viernes-word-break.md)

> [!quote] Para darle con todo
> «Me tomó 17 años y 114 días convertirme en un éxito de la noche a la mañana.»
> — *Lionel Messi, ocho veces Balón de Oro*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/decode-ways/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** DP 1D
- **Semana:** 23 — DP de una dimensión (problema 4 de 5)
- **Día:** [Semana 23 — Jueves](../../Semanas/Semana%2023/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/):** Es Climbing Stairs con condiciones: se da un paso de 1 o de 2 dígitos.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `dp[i]` = formas de decodificar los primeros i caracteres.

> [!question]- Pista 2 — ¿qué estructura usar?
> Si `s[i-1] !== '0'`, suma `dp[i-1]`.

> [!question]- Pista 3 — el algoritmo
> Si `s[i-2..i-1]` está entre 10 y 26, suma `dp[i-2]`.

> [!warning]- Trampa común
> Aceptar `"06"` como un paso de dos dígitos.

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
