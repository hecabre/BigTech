# Balanced Binary Tree

[← Anterior: Diameter of Binary Tree](../Semana%2009/03-Miercoles-diameter-of-binary-tree.md) · [Siguiente: Subtree of Another Tree →](../Semana%2009/05-Viernes-subtree-of-another-tree.md)

> [!quote] Para darle con todo
> «No puedes subir la escalera del éxito con las manos en los bolsillos.»
> — *Arnold Schwarzenegger, siete veces Mr. Olympia*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/balanced-binary-tree/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Tree DFS
- **Semana:** 09 — Árboles — DFS (problema 4 de 5)
- **Día:** [Semana 09 — Jueves](../../Semanas/Semana%2009/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Diameter of Binary Tree](../Semana%2009/03-Miercoles-diameter-of-binary-tree.md):** Es el mismo cálculo de altura; cambia la condición.
- **Repaso del patrón:** [Árboles y BST](../../Estudio/Articulos/08-Arboles-y-BST.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Calcular la altura en cada nodo por separado da O(n²).

> [!question]- Pista 2 — ¿qué estructura usar?
> Haz que la función devuelva la altura, o -1 si el subárbol no está balanceado.

> [!question]- Pista 3 — el algoritmo
> Si algún hijo devuelve -1, o `|L - R| > 1`, devuelve -1.

> [!warning]- Trampa común
> Revisar solo la raíz y no cada nodo.

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
