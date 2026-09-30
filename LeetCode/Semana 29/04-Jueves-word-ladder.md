# Word Ladder

[← Anterior: Path With Minimum Effort](../Semana%2029/03-Miercoles-path-with-minimum-effort.md) · [Siguiente: Course Schedule II →](../Semana%2029/05-Viernes-course-schedule-ii.md)

> [!quote] Para darle con todo
> «Odié cada minuto del entrenamiento, pero me dije: «No renuncies. Sufre ahora y vive el resto de tu vida como un campeón».»
> — *Muhammad Ali, tricampeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/word-ladder/)
- **Dificultad:** Hard
- **Tipo:** Nuevo
- **Patrón:** BFS
- **Semana:** 29 — Caminos más cortos (problema 4 de 5)
- **Día:** [Semana 29 — Jueves](../../Semanas/Semana%2029/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!warning] Hard
> Límite de 45 minutos. Si no sale, estudia la solución y reintenta en 7 días. No cuenta como fracaso.

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
