# Max Consecutive Ones III

[← Anterior: Fruit Into Baskets](../Semana%2022/01-Lunes-fruit-into-baskets.md) · [Siguiente: Subarray Sums Divisible by K →](../Semana%2022/03-Miercoles-subarray-sums-divisible-by-k.md)

> [!quote] Para darle con todo
> «No se trata de qué tan fuerte pegas. Se trata de qué tan fuerte te pueden pegar y seguir avanzando.»
> — *Rocky Balboa, personaje de Sylvester Stallone*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/max-consecutive-ones-iii/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Sliding window
- **Semana:** 22 — Sliding window y prefix sums avanzados (problema 2 de 5)
- **Día:** [Semana 22 — Martes](../../Semanas/Semana%2022/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Longest Repeating Character Replacement](../Semana%2019/05-Viernes-longest-repeating-character-replacement.md):** Es Character Replacement con dos valores.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Una ventana es válida si tiene a lo mucho k ceros.

> [!question]- Pista 2 — ¿qué estructura usar?
> Cuenta los ceros de la ventana.

> [!question]- Pista 3 — el algoritmo
> Si pasan de k, avanza `l` y, si `nums[l]` era 0, resta uno.

> [!warning]- Trampa común
> Intentar decidir cuáles ceros voltear.

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
