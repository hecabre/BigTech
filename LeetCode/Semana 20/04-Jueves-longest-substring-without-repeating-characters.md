# Longest Substring Without Repeating Characters

[← Anterior: Set Matrix Zeroes](../Semana%2020/03-Miercoles-set-matrix-zeroes.md) · [Siguiente: Top K Frequent Elements →](../Semana%2020/05-Viernes-top-k-frequent-elements.md)

> [!quote] Para darle con todo
> «Siempre es el Día 1.»
> — *Jeff Bezos, fundador de Amazon, carta a accionistas*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Sliding window
- **Semana:** 20 — Matrices + repaso bajo presión (semana SAA) (problema 4 de 5)
- **Día:** [Semana 20 — Jueves](../../Semanas/Semana%2020/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Minimum Size Subarray Sum](../Semana%2017/03-Miercoles-minimum-size-subarray-sum.md):** Es la misma ventana variable; la condición es «no hay repetidos».
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> La ventana es válida mientras no tenga caracteres repetidos.

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa un `Set` con los caracteres de la ventana.

> [!question]- Pista 3 — el algoritmo
> Si `s[r]` ya está, saca `s[l]` y avanza `l` hasta que deje de estar; luego agrega `s[r]`.

> [!warning]- Trampa común
> Reiniciar la ventana completa al encontrar un repetido.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(min(n, alfabeto))

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
