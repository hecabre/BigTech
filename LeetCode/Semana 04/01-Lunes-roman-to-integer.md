# Roman to Integer

[Siguiente: Longest Common Prefix →](../Semana%2004/02-Martes-longest-common-prefix.md)

> [!quote] Para darle con todo
> «Hablar es barato. Enséñame el código.»
> — *Linus Torvalds, creador de Linux*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/roman-to-integer/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Hash map
- **Semana:** 04 — Calentamiento arrays/strings (semana de examen CCP) (problema 1 de 5)
- **Día:** [Semana 04 — Lunes](../../Semanas/Semana%2004/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Two Sum](../Semana%2001/01-Lunes-two-sum.md):** Como en Two Sum, un `Map` te da la respuesta de cada símbolo en O(1).
- **Repaso del patrón:** [Arrays, hash maps y sets](../../Estudio/Articulos/03-Arrays-hash-maps-y-sets.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Guarda el valor de cada símbolo en un `Map` o un objeto.

> [!question]- Pista 2 — ¿qué estructura usar?
> Compara cada símbolo con el que sigue. ¿Qué pasa en `IV` o en `XC`?

> [!question]- Pista 3 — el algoritmo
> Si el valor actual es menor que el siguiente, réstalo; si no, súmalo.

> [!warning]- Trampa común
> Querer escribir un caso especial para cada par (`IV`, `IX`, `XL`…). La regla de «menor antes de mayor» los cubre todos.

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
