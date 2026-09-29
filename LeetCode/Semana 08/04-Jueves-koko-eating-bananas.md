# Koko Eating Bananas

[← Anterior: Sqrt(x)](../Semana%2008/03-Miercoles-sqrtx.md) · [Siguiente: Find First and Last Position of Element in Sorted Array →](../Semana%2008/05-Viernes-find-first-and-last-position-of-element-in-sorted-array.md)

> [!quote] Para darle con todo
> «Cuando algo sale mal, solo di: «Good». Ahora tienes algo de qué aprender.»
> — *Jocko Willink, ex Navy SEAL*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/koko-eating-bananas/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Binary search on answer
- **Semana:** 08 — Búsqueda binaria (problema 4 de 5)
- **Día:** [Semana 08 — Jueves](../../Semanas/Semana%2008/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Sqrt(x)](../Semana%2008/03-Miercoles-sqrtx.md):** Es la misma búsqueda sobre las respuestas, con una función de verificación más interesante.
- **Repaso del patrón:** [Búsqueda binaria](../../Estudio/Articulos/07-Busqueda-binaria.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> La velocidad está entre 1 y `max(piles)`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Escribe `horas(k) = Σ Math.ceil(p / k)`. ¿Es monótona?

> [!question]- Pista 3 — el algoritmo
> Busca la menor `k` con `horas(k) <= h` (el mismo patrón que First Bad Version).

> [!warning]- Trampa común
> Buscar sobre los índices del arreglo en lugar de sobre las velocidades.

> [!success]- Complejidad meta
> Tiempo O(n log max), espacio O(1)

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
