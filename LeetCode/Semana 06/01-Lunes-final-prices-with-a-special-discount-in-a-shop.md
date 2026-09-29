# Final Prices With a Special Discount in a Shop

[← Anterior: Evaluate Reverse Polish Notation](../Semana%2005/05-Viernes-evaluate-reverse-polish-notation.md) · [Siguiente: Crawler Log Folder →](../Semana%2006/02-Martes-crawler-log-folder.md)

> [!quote] Para darle con todo
> «Aquí no hay talento. Esto es trabajo duro. Esto es una obsesión.»
> — *Conor McGregor, campeón de UFC en dos divisiones*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/final-prices-with-a-special-discount-in-a-shop/)
- **Dificultad:** Easy
- **Tipo:** Nuevo
- **Patrón:** Monotonic stack
- **Semana:** 06 — Pila monotónica (problema 1 de 5)
- **Día:** [Semana 06 — Lunes](../../Semanas/Semana%2006/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/):** Es la versión Easy de Daily Temperatures, del calendario de esta semana.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Para cada precio buscas el siguiente precio menor o igual a su derecha.

> [!question]- Pista 2 — ¿qué estructura usar?
> La fuerza bruta O(n²) es aceptable aquí. Escríbela primero.

> [!question]- Pista 3 — el algoritmo
> Luego hazlo con una pila de índices: mientras `prices[i] <= prices[tope]`, aplica el descuento al tope y haz `pop`.

> [!warning]- Trampa común
> Usar `<` en lugar de `<=`: el descuento aplica también con precio igual.

> [!success]- Complejidad meta
> Tiempo O(n), espacio O(n)

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
