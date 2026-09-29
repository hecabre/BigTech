# Longest Palindromic Substring

[← Anterior: Course Schedule II](../Semana%2029/05-Viernes-course-schedule-ii.md) · [Siguiente: Integer to Roman →](../Semana%2030/02-Martes-integer-to-roman.md)

> [!quote] Para darle con todo
> «Aquí no hay talento. Esto es trabajo duro. Esto es una obsesión.»
> — *Conor McGregor, campeón de UFC en dos divisiones*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/longest-palindromic-substring/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Expandir desde el centro
- **Semana:** 30 — Strings y arrays clásicos de Amazon (problema 1 de 5)
- **Día:** [Semana 30 — Lunes](../../Semanas/Semana%2030/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/):** Es Valid Palindrome, pero expandiendo desde el centro.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Todo palíndromo tiene un centro: una letra o un espacio entre dos letras.

> [!question]- Pista 2 — ¿qué estructura usar?
> Hay 2n - 1 centros; desde cada uno expande mientras `s[l] === s[r]`.

> [!question]- Pista 3 — el algoritmo
> Guarda el mejor inicio y la mejor longitud.

> [!warning]- Trampa común
> Olvidar los centros pares (`"abba"`).

> [!success]- Complejidad meta
> Tiempo O(n²), espacio O(1)

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
