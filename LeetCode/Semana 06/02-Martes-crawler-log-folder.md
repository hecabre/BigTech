# Crawler Log Folder

[← Anterior: Final Prices With a Special Discount in a Shop](../Semana%2006/01-Lunes-final-prices-with-a-special-discount-in-a-shop.md) · [Siguiente: Asteroid Collision →](../Semana%2006/03-Miercoles-asteroid-collision.md)

> [!quote] Para darle con todo
> «No se trata de qué tan fuerte pegas. Se trata de qué tan fuerte te pueden pegar y seguir avanzando.»
> — *Rocky Balboa, personaje de Sylvester Stallone*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/crawler-log-folder/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Stack
- **Semana:** 06 — Pila monotónica (problema 2 de 5)
- **Día:** [Semana 06 — Martes](../../Semanas/Semana%2006/02-Martes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Conexión:** Es una pila donde solo importa su tamaño: es la base de Simplify Path.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> `../` sube un nivel, `./` no hace nada y `x/` baja un nivel.

> [!question]- Pista 2 — ¿qué estructura usar?
> No necesitas guardar los nombres, solo la profundidad.

> [!question]- Pista 3 — el algoritmo
> Usa un contador que nunca baje de 0.

> [!warning]- Trampa común
> Dejar que la profundidad sea negativa al hacer `../` en la raíz.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(1)

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
