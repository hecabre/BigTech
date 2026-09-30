# Contiguous Array

[← Anterior: Number of Sub-arrays With Odd Sum](../Semana%2022/04-Jueves-number-of-sub-arrays-with-odd-sum.md) · [Siguiente: Min Cost Climbing Stairs →](../Semana%2023/01-Lunes-min-cost-climbing-stairs.md)

> [!quote] Para darle con todo
> «Lo que define a quien es campeón no son sus victorias, sino cómo se recupera cuando cae.»
> — *Serena Williams, 23 títulos de Grand Slam*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/contiguous-array/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Prefix sum + Hash map
- **Semana:** 22 — Sliding window y prefix sums avanzados (problema 5 de 5)
- **Día:** [Semana 22 — Viernes](../../Semanas/Semana%2022/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/):** Es Subarray Sum Equals K con k = 0, cambiando los 0 por -1.
- **Repaso del patrón:** [Prefix sums](../../Estudio/Articulos/13-Prefix-sums.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si los 0 valen -1, un subarreglo balanceado suma 0.

> [!question]- Pista 2 — ¿qué estructura usar?
> Si el mismo prefix sum aparece dos veces, lo que hay entre ambos suma 0.

> [!question]- Pista 3 — el algoritmo
> `Map<prefijo, primer índice>` con `{0: -1}` al inicio.

> [!warning]- Trampa común
> Actualizar el índice cada vez: solo sirve el PRIMERO.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(n)

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
