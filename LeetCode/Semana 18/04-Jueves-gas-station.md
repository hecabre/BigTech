# Gas Station

[← Anterior: Minimum Number of Arrows to Burst Balloons](../Semana%2018/03-Miercoles-minimum-number-of-arrows-to-burst-balloons.md) · [Siguiente: Jump Game II →](../Semana%2018/05-Viernes-jump-game-ii.md)

> [!quote] Para darle con todo
> «Pies, ¿para qué los quiero si tengo alas pa' volar?»
> — *Frida Kahlo, de su diario, 1953*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/gas-station/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Greedy
- **Semana:** 18 — Intervalos y greedy (problema 4 de 5)
- **Día:** [Semana 18 — Jueves](../../Semanas/Semana%2018/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Best Time to Buy and Sell Stock](../Semana%2017/02-Martes-best-time-to-buy-and-sell-stock.md):** Es un recorrido de una sola pasada con un acumulado, como Best Time.
- **Repaso del patrón:** [Greedy e intervalos](../../Estudio/Articulos/12-Greedy-e-intervalos.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si `Σgas < Σcost`, es imposible.

> [!question]- Pista 2 — ¿qué estructura usar?
> Lleva el tanque actual; si baja de 0, ninguna estación hasta aquí puede ser el inicio.

> [!question]- Pista 3 — el algoritmo
> Reinicia: `inicio = i + 1` y `tanque = 0`.

> [!warning]- Trampa común
> Simular desde cada estación: es O(n²).

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
