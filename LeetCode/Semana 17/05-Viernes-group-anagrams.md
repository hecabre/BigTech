# Group Anagrams

[← Anterior: Longest Substring Without Repeating Characters](../Semana%2017/04-Jueves-longest-substring-without-repeating-characters.md) · [Siguiente: Summary Ranges →](../Semana%2018/01-Lunes-summary-ranges.md)

> [!quote] Para darle con todo
> «Sin terquedad, abandonas los experimentos demasiado pronto. Sin flexibilidad, te das de topes contra la pared y no ves otra solución.»
> — *Jeff Bezos, fundador de Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/group-anagrams/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Hash map
- **Semana:** 17 — Sliding window (tema sin cubrir en el calendario) (problema 5 de 5)
- **Día:** [Semana 17 — Viernes](../../Semanas/Semana%2017/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Valid Anagram](../Semana%2001/02-Martes-valid-anagram.md):** La firma de Valid Anagram se convierte en la llave de un `Map`.
- **Repaso del patrón:** [Arrays, hash maps y sets](../../Estudio/Articulos/03-Arrays-hash-maps-y-sets.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Dos anagramas comparten una misma «firma».

> [!question]- Pista 2 — ¿qué estructura usar?
> Firma: la palabra ordenada, o un conteo de 26 letras unido con `#`.

> [!question]- Pista 3 — el algoritmo
> `Map<firma, lista>` y devuelve `[...map.values()]`.

> [!warning]- Trampa común
> Usar un arreglo como llave del `Map`: se compara por referencia, no por contenido.

> [!success]- Complejidad meta
> Tiempo O(n·k log k), espacio O(n·k)

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
