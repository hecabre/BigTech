# Validate Binary Search Tree

[← Anterior: Search in Rotated Sorted Array](../Semana%2037/02-Martes-search-in-rotated-sorted-array.md) · [Siguiente: Decode Ways →](../Semana%2037/04-Jueves-decode-ways.md)

> [!quote] Para darle con todo
> «Disciplina es libertad.»
> — *Jocko Willink, ex Navy SEAL*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/validate-binary-search-tree/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** BST
- **Semana:** 37 — Eliminar errores repetidos — trampas típicas (problema 3 de 5)
- **Día:** [Semana 37 — Miércoles](../../Semanas/Semana%2037/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Se conecta con [Search in a Binary Search Tree](../Semana%2011/01-Lunes-search-in-a-binary-search-tree.md):** La propiedad del BST aplica a todo el subárbol, no solo a los hijos directos.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Comparar un nodo solo con sus hijos no es suficiente.

> [!question]- Pista 2 — ¿qué estructura usar?
> Pasa un rango `(min, max)` que cada nodo debe respetar.

> [!question]- Pista 3 — el algoritmo
> Izquierda: `(min, nodo.val)`; derecha: `(nodo.val, max)`. Alternativa: que el inorder sea estrictamente creciente.

> [!warning]- Trampa común
> Permitir valores iguales (el BST debe ser estricto).

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(h)

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
