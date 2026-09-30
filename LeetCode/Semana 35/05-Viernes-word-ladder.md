# Word Ladder

[← Anterior: Trapping Rain Water](../Semana%2035/04-Jueves-trapping-rain-water.md) · [Siguiente: Decode String →](../Semana%2036/01-Lunes-decode-string.md)

> [!quote] Para darle con todo
> «Trabaja duro, diviértete, haz historia.»
> — *Jeff Bezos, lema de Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/word-ladder/)
- **Dificultad:** Hard
- **Tipo:** Repaso
- **Patrón:** BFS
- **Semana:** 35 — Simulación Amazon — repaso OA (problema 5 de 5)
- **Día:** [Semana 35 — Viernes](../../Semanas/Semana%2035/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Shortest Path in Binary Matrix](../Semana%2014/04-Jueves-shortest-path-in-binary-matrix.md):** Es BFS de camino más corto; los nodos son palabras.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cada palabra es un nodo; dos palabras son vecinas si difieren en una letra.

> [!question]- Pista 2 — ¿qué estructura usar?
> BFS desde `beginWord` con un `Set` del diccionario.

> [!question]- Pista 3 — el algoritmo
> Para generar vecinos, cambia cada posición por las letras a–z y borra del set las palabras visitadas.

> [!warning]- Trampa común
> Comparar cada par de palabras para construir el grafo: O(n²·L).

> [!success]- Complejidad meta
> Tiempo O(n·L·26), espacio O(n)

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
