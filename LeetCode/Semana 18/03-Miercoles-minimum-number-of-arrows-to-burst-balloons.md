# Minimum Number of Arrows to Burst Balloons

[← Anterior: Non-overlapping Intervals](../Semana%2018/02-Martes-non-overlapping-intervals.md) · [Siguiente: Gas Station →](../Semana%2018/04-Jueves-gas-station.md)

> [!quote] Para darle con todo
> «Cuando algo es lo suficientemente importante, lo haces aunque las probabilidades no estén a tu favor.»
> — *Elon Musk, fundador de SpaceX*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Intervalos greedy
- **Semana:** 18 — Intervalos y greedy (problema 3 de 5)
- **Día:** [Semana 18 — Miércoles](../../Semanas/Semana%2018/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Non-overlapping Intervals](../Semana%2018/02-Martes-non-overlapping-intervals.md):** Es la misma estrategia: ordenar por el final.
- **Repaso del patrón:** [Greedy e intervalos](../../Estudio/Articulos/12-Greedy-e-intervalos.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Una flecha en el final del primer globo revienta todos los que empiezan antes.

> [!question]- Pista 2 — ¿qué estructura usar?
> Ordena por el final.

> [!question]- Pista 3 — el algoritmo
> Si `start > flechaActual`, necesitas otra flecha en `end`.

> [!warning]- Trampa común
> Usar `>=`: los globos que se tocan en el borde se revientan con la misma flecha.

> [!success]- Complejidad meta
> Tiempo O(n log n), espacio O(1)

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
