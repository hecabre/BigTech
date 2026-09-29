# Number of Provinces

[← Anterior: Max Area of Island](../Semana%2013/04-Jueves-max-area-of-island.md) · [Siguiente: Keys and Rooms →](../Semana%2014/01-Lunes-keys-and-rooms.md)

> [!quote] Para darle con todo
> «No puedes conectar los puntos mirando hacia adelante; solo puedes conectarlos mirando hacia atrás.»
> — *Steve Jobs, discurso en Stanford, 2005*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/number-of-provinces/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Graph DFS / Union-Find
- **Semana:** 13 — Grafos — introducción (problema 5 de 5)
- **Día:** [Semana 13 — Viernes](../../Semanas/Semana%2013/05-Viernes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Number of Islands](https://leetcode.com/problems/number-of-islands/):** Es Number of Islands, pero sobre una matriz de adyacencia.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cada provincia es un componente conectado.

> [!question]- Pista 2 — ¿qué estructura usar?
> Recorre las ciudades; si una no está visitada, inicia DFS y suma 1.

> [!question]- Pista 3 — el algoritmo
> Los vecinos de i son los j donde `isConnected[i][j] === 1`.

> [!warning]- Trampa común
> Tratar la matriz como un grid 2D de islas.

> [!success]- Complejidad meta
> Tiempo O(n²), espacio O(n)

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
