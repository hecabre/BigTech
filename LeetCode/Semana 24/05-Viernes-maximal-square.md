# Maximal Square

[← Anterior: Partition Equal Subset Sum](../Semana%2024/04-Jueves-partition-equal-subset-sum.md) · [Siguiente: Find Eventual Safe States →](../Semana%2025/01-Lunes-find-eventual-safe-states.md)

> [!quote] Para darle con todo
> «Tu tiempo es limitado, así que no lo desperdicies viviendo la vida de alguien más.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/maximal-square/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** DP 2D
- **Semana:** 24 — DP de dos dimensiones (problema 5 de 5)
- **Día:** [Semana 24 — Viernes](../../Semanas/Semana%2024/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Minimum Path Sum](../Semana%2024/01-Lunes-minimum-path-sum.md):** Es una DP 2D que mira arriba, a la izquierda y en diagonal.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `dp[r][c]` = el lado del mayor cuadrado cuya esquina inferior derecha es (r, c).

> [!question]- Pista 2 — ¿qué estructura usar?
> Si la celda es `'1'`: `1 + min(arriba, izquierda, diagonal)`.

> [!question]- Pista 3 — el algoritmo
> La respuesta es `lado²`.

> [!warning]- Trampa común
> Devolver el lado en lugar del área.

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
