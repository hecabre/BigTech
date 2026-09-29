# Trapping Rain Water

[← Anterior: Search Suggestions System](../Semana%2035/03-Miercoles-search-suggestions-system.md) · [Siguiente: Word Ladder →](../Semana%2035/05-Viernes-word-ladder.md)

> [!quote] Para darle con todo
> «Tal vez no pueda ganar. Pero para vencerme, va a tener que matarme. Y para matarme, va a tener que tener el valor de pararse frente a mí. Y para hacer eso, tiene que estar dispuesto a morir él también.»
> — *Rocky Balboa, Rocky IV, antes de pelear contra Drago*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/trapping-rain-water/)
- **Dificultad:** Hard
- **Tipo:** Repaso
- **Patrón:** Two pointers
- **Semana:** 35 — Simulación Amazon — repaso OA (problema 4 de 5)
- **Día:** [Semana 35 — Jueves](../../Semanas/Semana%2035/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Container With Most Water](../Semana%2002/01-Lunes-container-with-most-water.md):** Usa los dos punteros de Container With Most Water.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> El agua sobre i es `min(maxIzq, maxDer) - h[i]`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Versión 1: precalcula arreglos `maxIzq` y `maxDer`.

> [!question]- Pista 3 — el algoritmo
> Versión 2: dos punteros; mueve el lado con el máximo menor y acumula agua ahí.

> [!warning]- Trampa común
> Mover el puntero equivocado: siempre se mueve el lado cuyo máximo es menor.

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
