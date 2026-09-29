# Convert Sorted Array to Binary Search Tree

[← Anterior: Search in a Binary Search Tree](../Semana%2011/01-Lunes-search-in-a-binary-search-tree.md) · [Siguiente: Two Sum IV - Input is a BST →](../Semana%2011/03-Miercoles-two-sum-iv-input-is-a-bst.md)

> [!quote] Para darle con todo
> «Corres el peligro de vivir una vida tan cómoda y blanda que te mueras sin descubrir tu verdadero potencial.»
> — *David Goggins, Can't Hurt Me*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** BST
- **Semana:** 11 — BST (problema 2 de 5)
- **Día:** [Semana 11 — Martes](../../Semanas/Semana%2011/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Binary Search](https://leetcode.com/problems/binary-search/):** El `mid` de la búsqueda binaria se convierte en la raíz.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Para que quede balanceado, la raíz debe ser el elemento del medio.

> [!question]- Pista 2 — ¿qué estructura usar?
> Todo lo que está a la izquierda de `mid` forma el subárbol izquierdo.

> [!question]- Pista 3 — el algoritmo
> `build(lo, hi)`: si `lo > hi` devuelve null; si no, crea el nodo con `mid` y recursa.

> [!warning]- Trampa común
> Usar `slice` en cada llamada: funciona, pero copia el arreglo y cuesta O(n log n).

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(log n)

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
