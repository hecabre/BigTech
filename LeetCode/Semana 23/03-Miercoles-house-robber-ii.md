# House Robber II

[← Anterior: N-th Tribonacci Number](../Semana%2023/02-Martes-n-th-tribonacci-number.md) · [Siguiente: Decode Ways →](../Semana%2023/04-Jueves-decode-ways.md)

> [!quote] Para darle con todo
> «El talento sin trabajo duro no es nada.»
> — *Cristiano Ronaldo, cinco veces Balón de Oro*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/house-robber-ii/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** DP 1D
- **Semana:** 23 — DP de una dimensión (problema 3 de 5)
- **Día:** [Semana 23 — Miércoles](../../Semanas/Semana%2023/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [House Robber](https://leetcode.com/problems/house-robber/):** Es House Robber aplicado dos veces.
- **Repaso del patrón:** [Programación dinámica](../../Estudio/Articulos/14-Programacion-dinamica.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Las casas forman un círculo: la primera y la última no pueden ir juntas.

> [!question]- Pista 2 — ¿qué estructura usar?
> Caso A: roba de 0 a n - 2. Caso B: roba de 1 a n - 1.

> [!question]- Pista 3 — el algoritmo
> La respuesta es `max(A, B)`, más el caso especial n = 1.

> [!warning]- Trampa común
> Olvidar el caso de una sola casa.

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
