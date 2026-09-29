# Search Insert Position

[← Anterior: Remove Nth Node From End of List](../Semana%2007/05-Viernes-remove-nth-node-from-end-of-list.md) · [Siguiente: First Bad Version →](../Semana%2008/02-Martes-first-bad-version.md)

> [!quote] Para darle con todo
> «La mejor forma de predecir el futuro es inventarlo.»
> — *Alan Kay, pionero de la programación orientada a objetos*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/search-insert-position/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Binary search
- **Semana:** 08 — Búsqueda binaria (problema 1 de 5)
- **Día:** [Semana 08 — Lunes](../../Semanas/Semana%2008/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Binary Search](https://leetcode.com/problems/binary-search/):** Es Binary Search, pero devuelves dónde debería ir el número.
- **Repaso del patrón:** [Búsqueda binaria](../../Estudio/Articulos/07-Busqueda-binaria.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si no existe, ¿dónde quedan `lo` y `hi` al terminar?

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa `while (lo <= hi)` con `mid = Math.floor((lo + hi) / 2)`.

> [!question]- Pista 3 — el algoritmo
> Al salir del ciclo, `lo` es la posición de inserción.

> [!warning]- Trampa común
> Devolver `mid` al salir del ciclo en lugar de `lo`.

> [!success]- Complejidad meta
> Tiempo O(log n), espacio O(1)

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
