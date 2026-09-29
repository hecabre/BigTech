# Find First and Last Position of Element in Sorted Array

[← Anterior: Koko Eating Bananas](../Semana%2008/04-Jueves-koko-eating-bananas.md) · [Siguiente: Symmetric Tree →](../Semana%2009/01-Lunes-symmetric-tree.md)

> [!quote] Para darle con todo
> «Tu tiempo es limitado, así que no lo desperdicies viviendo la vida de alguien más.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Binary search
- **Semana:** 08 — Búsqueda binaria (problema 5 de 5)
- **Día:** [Semana 08 — Viernes](../../Semanas/Semana%2008/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [First Bad Version](../Semana%2008/02-Martes-first-bad-version.md):** Son dos búsquedas de «primer verdadero».
- **Repaso del patrón:** [Búsqueda binaria](../../Estudio/Articulos/07-Busqueda-binaria.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Haz una búsqueda para el primer índice con `nums[i] >= target`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Haz otra para el primer índice con `nums[i] > target`; el último es ese menos 1.

> [!question]- Pista 3 — el algoritmo
> Verifica que el primero realmente sea `target`.

> [!warning]- Trampa común
> Encontrar el target y expandirte hacia los lados: es O(n) en el peor caso.

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
