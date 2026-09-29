# Continuous Subarray Sum

[← Anterior: Contiguous Array](../Semana%2019/02-Martes-contiguous-array.md) · [Siguiente: Range Sum Query 2D - Immutable →](../Semana%2019/04-Jueves-range-sum-query-2d-immutable.md)

> [!quote] Para darle con todo
> «Stay hungry, stay foolish. Sigue con hambre, sigue con locura.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/continuous-subarray-sum/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Prefix sum + módulo
- **Semana:** 19 — Prefix sums + sliding window (problema 3 de 5)
- **Día:** [Semana 19 — Miércoles](../../Semanas/Semana%2019/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Contiguous Array](../Semana%2019/02-Martes-contiguous-array.md):** Es el mismo `Map` de prefijos, ahora con módulo k.
- **Repaso del patrón:** [Prefix sums](../../Estudio/Articulos/13-Prefix-sums.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si dos prefijos tienen el mismo residuo mod k, lo que hay entre ellos es múltiplo de k.

> [!question]- Pista 2 — ¿qué estructura usar?
> `Map<residuo, primer índice>` con `{0: -1}`.

> [!question]- Pista 3 — el algoritmo
> Si el residuo ya existe y `i - idx >= 2`, devuelve true.

> [!warning]- Trampa común
> Olvidar que el subarreglo debe tener al menos 2 elementos.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(min(n, k))

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
