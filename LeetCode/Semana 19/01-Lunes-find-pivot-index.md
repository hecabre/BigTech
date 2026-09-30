# Find Pivot Index

[← Anterior: Jump Game II](../Semana%2018/05-Viernes-jump-game-ii.md) · [Siguiente: Contiguous Array →](../Semana%2019/02-Martes-contiguous-array.md)

> [!quote] Para darle con todo
> «Vacía tu mente. Sin forma, como el agua. Be water, my friend.»
> — *Bruce Lee, maestro de artes marciales*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/find-pivot-index/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Prefix sum
- **Semana:** 19 — Prefix sums + sliding window (problema 1 de 5)
- **Día:** [Semana 19 — Lunes](../../Semanas/Semana%2019/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Range Sum Query – Immutable](https://leetcode.com/problems/range-sum-query-immutable/):** Es el prefix sum del calendario aplicado a un problema real.
- **Repaso del patrón:** [Prefix sums](../../Estudio/Articulos/13-Prefix-sums.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Calcula la suma total.

> [!question]- Pista 2 — ¿qué estructura usar?
> Lleva la suma de la izquierda mientras recorres.

> [!question]- Pista 3 — el algoritmo
> La suma derecha es `total - izq - nums[i]`; si es igual a `izq`, ese es el pivote.

> [!warning]- Trampa común
> Sumar `nums[i]` a `izq` antes de comparar.

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
