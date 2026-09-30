# All Ancestors of a Node in a Directed Acyclic Graph

[← Anterior: Minimum Height Trees](../Semana%2025/02-Martes-minimum-height-trees.md) · [Siguiente: Find All Possible Recipes from Given Supplies →](../Semana%2025/04-Jueves-find-all-possible-recipes-from-given-supplies.md)

> [!quote] Para darle con todo
> «La frase más peligrosa del idioma es: «Siempre lo hemos hecho así».»
> — *Grace Hopper, pionera de la computación y almirante de la Marina de EE. UU.*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/all-ancestors-of-a-node-in-a-directed-acyclic-graph/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Topological sort
- **Semana:** 25 — Orden topológico y Union-Find (problema 3 de 5)
- **Día:** [Semana 25 — Miércoles](../../Semanas/Semana%2025/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/):** Es el orden topológico de Course Schedule II propagando información.
- **Repaso del patrón:** [Orden topológico](../../Estudio/Articulos/15-Orden-topologico.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si recorres en orden topológico, los ancestros de un padre ya están completos.

> [!question]- Pista 2 — ¿qué estructura usar?
> Kahn: al procesar u → v, agrega u y los ancestros de u al `Set` de v.

> [!question]- Pista 3 — el algoritmo
> Al final, ordena cada set.

> [!warning]- Trampa común
> No deduplicar los ancestros.

> [!success]- Complejidad meta
> Tiempo O(V·(V + E)), espacio O(V²)

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
