# 01 Matrix

[← Anterior: Keys and Rooms](../Semana%2014/01-Lunes-keys-and-rooms.md) · [Siguiente: Surrounded Regions →](../Semana%2014/03-Miercoles-surrounded-regions.md)

> [!quote] Para darle con todo
> «No se trata de qué tan fuerte pegas. Se trata de qué tan fuerte te pueden pegar y seguir avanzando.»
> — *Rocky Balboa, personaje de Sylvester Stallone*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/01-matrix/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Multi-source BFS
- **Semana:** 14 — Grafos — BFS y grids (problema 2 de 5)
- **Día:** [Semana 14 — Martes](../../Semanas/Semana%2014/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Rotting Oranges](https://leetcode.com/problems/rotting-oranges/):** Es BFS multi-origen, igual que Rotting Oranges.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Hacer un BFS desde cada 1 es demasiado lento.

> [!question]- Pista 2 — ¿qué estructura usar?
> Mete TODOS los 0 en la cola al inicio, con distancia 0.

> [!question]- Pista 3 — el algoritmo
> Expande: un vecino sin distancia recibe `dist + 1` y entra a la cola.

> [!warning]- Trampa común
> Hacer BFS celda por celda: es O((filas·cols)²).

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
