# Number of Sub-arrays With Odd Sum

[← Anterior: Subarray Sums Divisible by K](../Semana%2022/03-Miercoles-subarray-sums-divisible-by-k.md) · [Siguiente: Contiguous Array →](../Semana%2022/05-Viernes-contiguous-array.md)

> [!quote] Para darle con todo
> «Las últimas tres o cuatro repeticiones son las que hacen crecer el músculo.»
> — *Arnold Schwarzenegger, Pumping Iron*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/number-of-sub-arrays-with-odd-sum/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Prefix sum
- **Semana:** 22 — Sliding window y prefix sums avanzados (problema 4 de 5)
- **Día:** [Semana 22 — Jueves](../../Semanas/Semana%2022/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Subarray Sums Divisible by K](../Semana%2022/03-Miercoles-subarray-sums-divisible-by-k.md):** Es lo mismo con k = 2: la paridad del prefijo.
- **Repaso del patrón:** [Prefix sums](../../Estudio/Articulos/13-Prefix-sums.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> La suma de un subarreglo es impar si los prefijos tienen distinta paridad.

> [!question]- Pista 2 — ¿qué estructura usar?
> Cuenta cuántos prefijos pares e impares has visto (inicia con `par = 1`).

> [!question]- Pista 3 — el algoritmo
> Si el prefijo actual es impar, suma los pares vistos; si es par, suma los impares. Aplica mod 1e9+7.

> [!warning]- Trampa común
> Olvidar el módulo.

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
