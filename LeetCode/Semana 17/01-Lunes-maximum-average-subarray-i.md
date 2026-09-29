# Maximum Average Subarray I

[← Anterior: Subsets](../Semana%2016/05-Viernes-subsets.md) · [Siguiente: Best Time to Buy and Sell Stock →](../Semana%2017/02-Martes-best-time-to-buy-and-sell-stock.md)

> [!quote] Para darle con todo
> «No hay que llegar primero, pero hay que saber llegar.»
> — *José Alfredo Jiménez, «El Rey»*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/maximum-average-subarray-i/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Sliding window fija
- **Semana:** 17 — Sliding window (tema sin cubrir en el calendario) (problema 1 de 5)
- **Día:** [Semana 17 — Lunes](../../Semanas/Semana%2017/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Move Zeroes](https://leetcode.com/problems/move-zeroes/):** Es tu primera ventana deslizante: de tamaño fijo.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Recalcular la suma de cada ventana da O(n·k).

> [!question]- Pista 2 — ¿qué estructura usar?
> Calcula la suma de los primeros k elementos.

> [!question]- Pista 3 — el algoritmo
> Al avanzar, suma el que entra y resta el que sale: `sum += a[i] - a[i - k]`.

> [!warning]- Trampa común
> Dividir entre k en cada paso; basta con dividir la mejor suma al final.

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
