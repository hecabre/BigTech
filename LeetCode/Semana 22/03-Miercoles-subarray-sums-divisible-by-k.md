# Subarray Sums Divisible by K

[← Anterior: Max Consecutive Ones III](../Semana%2022/02-Martes-max-consecutive-ones-iii.md) · [Siguiente: Number of Sub-arrays With Odd Sum →](../Semana%2022/04-Jueves-number-of-sub-arrays-with-odd-sum.md)

> [!quote] Para darle con todo
> «Sabía que si fallaba no me iba a arrepentir. Lo único de lo que me podría arrepentir era de no haberlo intentado.»
> — *Jeff Bezos, sobre dejar su trabajo para fundar Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/subarray-sums-divisible-by-k/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Prefix sum + módulo
- **Semana:** 22 — Sliding window y prefix sums avanzados (problema 3 de 5)
- **Día:** [Semana 22 — Miércoles](../../Semanas/Semana%2022/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Continuous Subarray Sum](../Semana%2019/03-Miercoles-continuous-subarray-sum.md):** Es el `Map` de residuos, contando pares en lugar de buscar uno.
- **Repaso del patrón:** [Prefix sums](../../Estudio/Articulos/13-Prefix-sums.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Dos prefijos con el mismo residuo forman un subarreglo divisible entre k.

> [!question]- Pista 2 — ¿qué estructura usar?
> Lleva `count[residuo]` e inicia con `count[0] = 1`.

> [!question]- Pista 3 — el algoritmo
> Normaliza los negativos: `((p % k) + k) % k`.

> [!warning]- Trampa común
> No normalizar el residuo negativo en JavaScript.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(k)

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
