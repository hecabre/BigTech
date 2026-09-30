# Max Area of Island

[← Anterior: Island Perimeter](../Semana%2013/03-Miercoles-island-perimeter.md) · [Siguiente: Number of Provinces →](../Semana%2013/05-Viernes-number-of-provinces.md)

> [!quote] Para darle con todo
> «Odié cada minuto del entrenamiento, pero me dije: «No renuncies. Sufre ahora y vive el resto de tu vida como un campeón».»
> — *Muhammad Ali, tricampeón mundial de peso completo*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/max-area-of-island/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Grid DFS
- **Semana:** 13 — Grafos — introducción (problema 4 de 5)
- **Día:** [Semana 13 — Jueves](../../Semanas/Semana%2013/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Number of Islands](https://leetcode.com/problems/number-of-islands/):** Es Number of Islands, pero el DFS devuelve el tamaño.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cada isla es un componente conectado.

> [!question]- Pista 2 — ¿qué estructura usar?
> El DFS devuelve `1 + dfs(arriba) + dfs(abajo) + dfs(izq) + dfs(der)`.

> [!question]- Pista 3 — el algoritmo
> Marca la celda como visitada (ponla en 0) antes de recursar.

> [!warning]- Trampa común
> No marcar la celda y contarla varias veces.

> [!success]- Complejidad meta
> Tiempo O(filas·cols), espacio O(filas·cols)

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
