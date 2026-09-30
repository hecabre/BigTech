# Best Time to Buy and Sell Stock

[← Anterior: Maximum Average Subarray I](../Semana%2017/01-Lunes-maximum-average-subarray-i.md) · [Siguiente: Minimum Size Subarray Sum →](../Semana%2017/03-Miercoles-minimum-size-subarray-sum.md)

> [!quote] Para darle con todo
> «La mentalidad Mamba no se trata de buscar un resultado; se trata del proceso de llegar a ese resultado.»
> — *Kobe Bryant, The Mamba Mentality*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
- **Dificultad:** Easy
- **Tipo:** Repaso
- **Patrón:** Sliding window
- **Semana:** 17 — Sliding window (tema sin cubrir en el calendario) (problema 2 de 5)
- **Día:** [Semana 17 — Martes](../../Semanas/Semana%2017/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Maximum Average Subarray I](../Semana%2017/01-Lunes-maximum-average-subarray-i.md):** Hoy léelo como una ventana: el mínimo a la izquierda y el día actual a la derecha.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Por cada día, ¿cuál fue el precio más barato antes de él?

> [!question]- Pista 2 — ¿qué estructura usar?
> Lleva `minHastaAhora`.

> [!question]- Pista 3 — el algoritmo
> `mejor = max(mejor, precio - minHastaAhora)`.

> [!warning]- Trampa común
> Buscar el mínimo y el máximo globales sin respetar el orden de los días.

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
