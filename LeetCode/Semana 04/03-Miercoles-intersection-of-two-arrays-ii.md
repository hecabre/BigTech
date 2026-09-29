# Intersection of Two Arrays II

[← Anterior: Longest Common Prefix](../Semana%2004/02-Martes-longest-common-prefix.md) · [Siguiente: Is Subsequence →](../Semana%2004/04-Jueves-is-subsequence.md)

> [!quote] Para darle con todo
> «He fallado más de 9,000 tiros en mi carrera. He perdido casi 300 partidos. 26 veces me confiaron el tiro ganador y lo fallé. He fallado una y otra y otra vez en mi vida. Y por eso tengo éxito.»
> — *Michael Jordan, seis veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/intersection-of-two-arrays-ii/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Hash map
- **Semana:** 04 — Calentamiento arrays/strings (semana de examen CCP) (problema 3 de 5)
- **Día:** [Semana 04 — Miércoles](../../Semanas/Semana%2004/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Valid Anagram](../Semana%2001/02-Martes-valid-anagram.md):** Es el mismo conteo de frecuencias que en Valid Anagram.
- **Repaso del patrón:** [Arrays, hash maps y sets](../../Estudio/Articulos/03-Arrays-hash-maps-y-sets.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Necesitas saber cuántas veces aparece cada número, no solo si aparece.

> [!question]- Pista 2 — ¿qué estructura usar?
> Cuenta las frecuencias del primer arreglo en un `Map`.

> [!question]- Pista 3 — el algoritmo
> Recorre el segundo arreglo: si el conteo es > 0, agrega el número a la respuesta y resta 1.

> [!warning]- Trampa común
> Usar un `Set` pierde los duplicados, y `[1,2,2,1]` con `[2,2]` debe dar `[2,2]`.

> [!success]- Complejidad meta
> Tiempo O(n + m), espacio O(min(n, m))

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
