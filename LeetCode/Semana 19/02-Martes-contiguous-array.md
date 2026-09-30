# Contiguous Array

[← Anterior: Find Pivot Index](../Semana%2019/01-Lunes-find-pivot-index.md) · [Siguiente: Continuous Subarray Sum →](../Semana%2019/03-Miercoles-continuous-subarray-sum.md)

> [!quote] Para darle con todo
> «Corres el peligro de vivir una vida tan cómoda y blanda que te mueras sin descubrir tu verdadero potencial.»
> — *David Goggins, Can't Hurt Me*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/contiguous-array/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Prefix sum + Hash map
- **Semana:** 19 — Prefix sums + sliding window (problema 2 de 5)
- **Día:** [Semana 19 — Martes](../../Semanas/Semana%2019/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

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
