# Course Schedule II

[← Anterior: Word Ladder](../Semana%2029/04-Jueves-word-ladder.md) · [Siguiente: Longest Palindromic Substring →](../Semana%2030/01-Lunes-longest-palindromic-substring.md)

> [!quote] Para darle con todo
> «No puedes conectar los puntos mirando hacia adelante; solo puedes conectarlos mirando hacia atrás.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/course-schedule-ii/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Topological sort
- **Semana:** 29 — Caminos más cortos (problema 5 de 5)
- **Día:** [Semana 29 — Viernes](../../Semanas/Semana%2029/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Course Schedule](https://leetcode.com/problems/course-schedule/):** Es Course Schedule devolviendo el orden.
- **Repaso del patrón:** [Orden topológico](../../Estudio/Articulos/15-Orden-topologico.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Construye la lista de adyacencia y los grados de entrada.

> [!question]- Pista 2 — ¿qué estructura usar?
> Algoritmo de Kahn: la cola empieza con los cursos de grado 0.

> [!question]- Pista 3 — el algoritmo
> Si el orden resultante tiene menos de n cursos, hay un ciclo y devuelves `[]`.

> [!warning]- Trampa común
> Invertir la dirección de las aristas `[a, b]` (b va antes que a).

> [!success]- Complejidad meta
> Tiempo O(V + E), espacio O(V + E)

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
