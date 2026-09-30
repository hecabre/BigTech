# Fruit Into Baskets

[← Anterior: Kth Largest Element in an Array](../Semana%2021/05-Viernes-kth-largest-element-in-an-array.md) · [Siguiente: Max Consecutive Ones III →](../Semana%2022/02-Martes-max-consecutive-ones-iii.md)

> [!quote] Para darle con todo
> «Aquí no hay talento. Esto es trabajo duro. Esto es una obsesión.»
> — *Conor McGregor, campeón de UFC en dos divisiones*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/fruit-into-baskets/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Sliding window
- **Semana:** 22 — Sliding window y prefix sums avanzados (problema 1 de 5)
- **Día:** [Semana 22 — Lunes](../../Semanas/Semana%2022/01-Lunes.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Longest Substring Without Repeating Characters](../Semana%2017/04-Jueves-longest-substring-without-repeating-characters.md):** Es la ventana variable: «a lo mucho 2 tipos distintos».
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Traducción: el subarreglo más largo con a lo mucho 2 valores distintos.

> [!question]- Pista 2 — ¿qué estructura usar?
> Usa un `Map` de fruta → conteo dentro de la ventana.

> [!question]- Pista 3 — el algoritmo
> Si `map.size > 2`, contrae desde la izquierda y borra la fruta cuando su conteo llegue a 0.

> [!warning]- Trampa común
> No borrar la llave cuando el conteo llega a 0: `size` queda mal.

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
