# Minimum Window Substring

[← Anterior: Snapshot Array](../Semana%2034/02-Martes-snapshot-array.md) · [Siguiente: Course Schedule →](../Semana%2034/04-Jueves-course-schedule.md)

> [!quote] Para darle con todo
> «Cuando algo es lo suficientemente importante, lo haces aunque las probabilidades no estén a tu favor.»
> — *Elon Musk, fundador de SpaceX*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/minimum-window-substring/)
- **Dificultad:** Hard
- **Tipo:** Nuevo
- **Patrón:** Sliding window
- **Semana:** 34 — Últimos patrones nuevos (problema 3 de 5)
- **Día:** [Semana 34 — Miércoles](../../Semanas/Semana%2034/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!warning] Hard
> Límite de 45 minutos. Si no sale, estudia la solución y reintenta en 7 días. No cuenta como fracaso.

## Por qué este problema

- **Se conecta con [Longest Substring Without Repeating Characters](../Semana%2017/04-Jueves-longest-substring-without-repeating-characters.md):** Es tu ventana variable más difícil: une todo lo que viste de sliding window.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Cuenta lo que necesitas de t en un `Map`.

> [!question]- Pista 2 — ¿qué estructura usar?
> Expande `r`; lleva `formados`: cuántos caracteres ya cumplen su conteo.

> [!question]- Pista 3 — el algoritmo
> Mientras la ventana sea válida, guarda si es la mejor y contrae `l`.

> [!warning]- Trampa común
> Comparar los dos `Map` completos en cada paso.

> [!success]- Complejidad meta
> Tiempo O(|s| + |t|), espacio O(alfabeto)

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
