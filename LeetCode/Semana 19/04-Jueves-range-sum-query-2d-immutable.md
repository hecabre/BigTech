# Range Sum Query 2D - Immutable

[← Anterior: Continuous Subarray Sum](../Semana%2019/03-Miercoles-continuous-subarray-sum.md) · [Siguiente: Longest Repeating Character Replacement →](../Semana%2019/05-Viernes-longest-repeating-character-replacement.md)

> [!quote] Para darle con todo
> «Tal vez no pueda ganar. Pero para vencerme, va a tener que matarme. Y para matarme, va a tener que tener el valor de pararse frente a mí. Y para hacer eso, tiene que estar dispuesto a morir él también.»
> — *Rocky Balboa, Rocky IV, antes de pelear contra Drago*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/range-sum-query-2d-immutable/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Prefix sum 2D
- **Semana:** 19 — Prefix sums + sliding window (problema 4 de 5)
- **Día:** [Semana 19 — Jueves](../../Semanas/Semana%2019/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Range Sum Query – Immutable](https://leetcode.com/problems/range-sum-query-immutable/):** Es Range Sum Query en 2D.
- **Repaso del patrón:** [Prefix sums](../../Estudio/Articulos/13-Prefix-sums.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Precalcula `P[r + 1][c + 1]` = suma del rectángulo desde (0, 0).

> [!question]- Pista 2 — ¿qué estructura usar?
> `P[r+1][c+1] = m[r][c] + P[r][c+1] + P[r+1][c] - P[r][c]`.

> [!question]- Pista 3 — el algoritmo
> Consulta: `P[r2+1][c2+1] - P[r1][c2+1] - P[r2+1][c1] + P[r1][c1]`.

> [!warning]- Trampa común
> Olvidar sumar de vuelta la esquina que restaste dos veces.

> [!success]- Complejidad meta
> Tiempo O(1) por consulta y O(m·n) de preparación

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
