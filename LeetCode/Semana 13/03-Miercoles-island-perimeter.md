# Island Perimeter

[← Anterior: Find the Town Judge](../Semana%2013/02-Martes-find-the-town-judge.md) · [Siguiente: Max Area of Island →](../Semana%2013/04-Jueves-max-area-of-island.md)

> [!quote] Para darle con todo
> «Disciplina es libertad.»
> — *Jocko Willink, ex Navy SEAL*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/island-perimeter/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Grid
- **Semana:** 13 — Grafos — introducción (problema 3 de 5)
- **Día:** [Semana 13 — Miércoles](../../Semanas/Semana%2013/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Flood Fill](https://leetcode.com/problems/flood-fill/):** Recorres un grid como en Flood Fill, pero solo cuentas.
- **Repaso del patrón:** [Grafos: DFS y BFS](../../Estudio/Articulos/10-Grafos-DFS-y-BFS.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cada celda de tierra aporta 4 lados.

> [!question]- Pista 2 — ¿qué estructura usar?
> Cada vecino que también es tierra tapa un lado.

> [!question]- Pista 3 — el algoritmo
> `perímetro = 4 * tierras - 2 * pares adyacentes` (revisa solo arriba y a la izquierda).

> [!warning]- Trampa común
> Hacer DFS cuando basta con un recorrido simple.

> [!success]- Complejidad meta
> Tiempo O(filas·cols), espacio O(1)

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
