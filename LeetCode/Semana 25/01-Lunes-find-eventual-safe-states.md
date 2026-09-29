# Find Eventual Safe States

[← Anterior: Maximal Square](../Semana%2024/05-Viernes-maximal-square.md) · [Siguiente: Minimum Height Trees →](../Semana%2025/02-Martes-minimum-height-trees.md)

> [!quote] Para darle con todo
> «No hay que llegar primero, pero hay que saber llegar.»
> — *José Alfredo Jiménez, «El Rey»*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/find-eventual-safe-states/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Topological sort
- **Semana:** 25 — Orden topológico y Union-Find (problema 1 de 5)
- **Día:** [Semana 25 — Lunes](../../Semanas/Semana%2025/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Course Schedule](https://leetcode.com/problems/course-schedule/):** Es detección de ciclos, como Course Schedule.
- **Repaso del patrón:** [Orden topológico](../../Estudio/Articulos/15-Orden-topologico.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Un nodo es seguro si ningún camino que sale de él entra en un ciclo.

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa DFS con 3 colores: 0 sin visitar, 1 en proceso, 2 seguro.

> [!question]- Pista 3 — el algoritmo
> Si llegas a un nodo en proceso, hay ciclo. Alternativa: Kahn sobre el grafo invertido.

> [!warning]- Trampa común
> Usar solo visitado/no visitado: no distingue un ciclo de un nodo ya resuelto.

> [!success]- Complejidad meta
> Tiempo O(V + E), espacio O(V)

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
