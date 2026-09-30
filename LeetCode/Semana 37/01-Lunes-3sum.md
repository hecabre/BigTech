# 3Sum

[← Anterior: Copy List with Random Pointer](../Semana%2036/05-Viernes-copy-list-with-random-pointer.md) · [Siguiente: Search in Rotated Sorted Array →](../Semana%2037/02-Martes-search-in-rotated-sorted-array.md)

> [!quote] Para darle con todo
> «Lo que no puedo crear, no lo entiendo.»
> — *Richard Feynman, Nobel de Física; estaba escrito en su pizarrón*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/3sum/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Two pointers
- **Semana:** 37 — Eliminar errores repetidos — trampas típicas (problema 1 de 5)
- **Día:** [Semana 37 — Lunes](../../Semanas/Semana%2037/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Two Sum II](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/):** Es fijar un número y hacer Two Sum II con el resto.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Ordena el arreglo.

> [!question]- Pista 2 — ¿qué estructura usar?
> Fija `i`; usa dos punteros sobre `i+1..n-1` buscando `-nums[i]`.

> [!question]- Pista 3 — el algoritmo
> Salta los duplicados tanto en `i` como en los punteros después de encontrar una tripleta.

> [!warning]- Trampa común
> No saltar los duplicados y devolver tripletas repetidas.

> [!success]- Complejidad meta
> Tiempo O(n²), espacio O(1) extra

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
