# Decode String

[← Anterior: Word Ladder](../Semana%2035/05-Viernes-word-ladder.md) · [Siguiente: Random Pick with Weight →](../Semana%2036/02-Martes-random-pick-with-weight.md)

> [!quote] Para darle con todo
> «Hablar es barato. Enséñame el código.»
> — *Linus Torvalds, creador de Linux*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/decode-string/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Stack
- **Semana:** 36 — Otras empresas — Medium variados (problema 1 de 5)
- **Día:** [Semana 36 — Lunes](../../Semanas/Semana%2036/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Evaluate Reverse Polish Notation](../Semana%2005/05-Viernes-evaluate-reverse-polish-notation.md):** Es una pila que guarda el contexto.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Al abrir `[` necesitas recordar el string que llevabas y el número.

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa dos pilas: una de números y una de strings.

> [!question]- Pista 3 — el algoritmo
> `[` hace push y reinicia; `]` hace pop y `prev + actual.repeat(n)`.

> [!warning]- Trampa común
> Leer solo un dígito cuando el número puede ser `12[a]`.

> [!success]- Complejidad meta
> Tiempo O(tamaño de la salida), espacio O(n)

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
