# Binary Search

[← Anterior: Merge Two Sorted Lists](../Semana%2021/02-Martes-merge-two-sorted-lists.md) · [Siguiente: Invert Binary Tree →](../Semana%2021/04-Jueves-invert-binary-tree.md)

> [!quote] Para darle con todo
> «Disciplina es libertad.»
> — *Jocko Willink, ex Navy SEAL*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/binary-search/)
- **Dificultad:** Easy
- **Tipo:** Repaso
- **Patrón:** Binary search
- **Semana:** 21 — Semana de examen SAA — solo repaso (problema 3 de 5)
- **Día:** [Semana 21 — Miércoles](../../Semanas/Semana%2021/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Conexión:** Es la plantilla base de búsqueda binaria.
- **Repaso del patrón:** [Búsqueda binaria](../../Estudio/Articulos/07-Busqueda-binaria.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `lo = 0` y `hi = n - 1`.

> [!question]- Pista 2 — ¿qué estructura usar?
> `while (lo <= hi)` con `mid = lo + ((hi - lo) >> 1)`.

> [!question]- Pista 3 — el algoritmo
> Si es igual, devuelve; si es menor, `lo = mid + 1`; si no, `hi = mid - 1`.

> [!warning]- Trampa común
> Hacer `lo = mid` con `lo <= hi`: provoca un ciclo infinito.

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
