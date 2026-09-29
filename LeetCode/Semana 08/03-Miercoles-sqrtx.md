# Sqrt(x)

[← Anterior: First Bad Version](../Semana%2008/02-Martes-first-bad-version.md) · [Siguiente: Koko Eating Bananas →](../Semana%2008/04-Jueves-koko-eating-bananas.md)

> [!quote] Para darle con todo
> «Puedo aceptar el fracaso; todos fallan en algo. Lo que no puedo aceptar es no intentarlo.»
> — *Michael Jordan, seis veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/sqrtx/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Binary search
- **Semana:** 08 — Búsqueda binaria (problema 3 de 5)
- **Día:** [Semana 08 — Miércoles](../../Semanas/Semana%2008/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [First Bad Version](../Semana%2008/02-Martes-first-bad-version.md):** Es búsqueda binaria sobre el rango de respuestas posibles, no sobre un arreglo.
- **Repaso del patrón:** [Búsqueda binaria](../../Estudio/Articulos/07-Busqueda-binaria.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> La respuesta está entre 0 y x.

> [!question]- Pista 2 — ¿qué estructura usar?
> Busca el mayor `m` que cumpla `m * m <= x`.

> [!question]- Pista 3 — el algoritmo
> Si `m * m <= x`, guarda `m` y sigue a la derecha; si no, ve a la izquierda.

> [!warning]- Trampa común
> Olvidar los casos `x = 0` y `x = 1`.

> [!success]- Complejidad meta
> Tiempo O(log x), espacio O(1)

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
