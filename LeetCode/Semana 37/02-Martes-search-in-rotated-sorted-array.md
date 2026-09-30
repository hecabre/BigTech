# Search in Rotated Sorted Array

[← Anterior: 3Sum](../Semana%2037/01-Lunes-3sum.md) · [Siguiente: Validate Binary Search Tree →](../Semana%2037/03-Miercoles-validate-binary-search-tree.md)

> [!quote] Para darle con todo
> «Todo lo negativo —la presión, los retos— es una oportunidad para elevarme.»
> — *Kobe Bryant, cinco veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Binary search
- **Semana:** 37 — Eliminar errores repetidos — trampas típicas (problema 2 de 5)
- **Día:** [Semana 37 — Martes](../../Semanas/Semana%2037/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Binary Search](../Semana%2021/03-Miercoles-binary-search.md):** Es búsqueda binaria donde siempre una mitad está ordenada.
- **Repaso del patrón:** [Búsqueda binaria](../../Estudio/Articulos/07-Busqueda-binaria.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> En cada `mid`, una de las dos mitades está ordenada.

> [!question]- Pista 2 — ¿qué estructura usar?
> Si `nums[lo] <= nums[mid]`, la izquierda está ordenada.

> [!question]- Pista 3 — el algoritmo
> Revisa si el target cae en el rango de la mitad ordenada; si sí, ve ahí; si no, ve a la otra.

> [!warning]- Trampa común
> Usar `<` en lugar de `<=` cuando `lo === mid`.

> [!success]- Complejidad meta
> Tiempo O(log n), espacio O(1)

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
