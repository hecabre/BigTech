# First Bad Version

[← Anterior: Search Insert Position](../Semana%2008/01-Lunes-search-insert-position.md) · [Siguiente: Sqrt(x) →](../Semana%2008/03-Miercoles-sqrtx.md)

> [!quote] Para darle con todo
> «El mérito pertenece a quien está realmente en la arena, con la cara manchada de polvo, sudor y sangre.»
> — *Theodore Roosevelt, «El hombre en la arena», 1910*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/first-bad-version/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Binary search
- **Semana:** 08 — Búsqueda binaria (problema 2 de 5)
- **Día:** [Semana 08 — Martes](../../Semanas/Semana%2008/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Search Insert Position](../Semana%2008/01-Lunes-search-insert-position.md):** Buscas el primer `true` en una secuencia `false…false true…true`.
- **Repaso del patrón:** [Búsqueda binaria](../../Estudio/Articulos/07-Busqueda-binaria.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Si `mid` es mala, la primera mala está en `mid` o antes.

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa `lo < hi`; si es mala, `hi = mid`; si no, `lo = mid + 1`.

> [!question]- Pista 3 — el algoritmo
> Al terminar, `lo === hi` es la respuesta.

> [!warning]- Trampa común
> Usar `hi = mid - 1` y saltarte justo la primera versión mala.

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
