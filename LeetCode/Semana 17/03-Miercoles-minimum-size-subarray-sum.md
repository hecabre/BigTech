# Minimum Size Subarray Sum

[← Anterior: Best Time to Buy and Sell Stock](../Semana%2017/02-Martes-best-time-to-buy-and-sell-stock.md) · [Siguiente: Longest Substring Without Repeating Characters →](../Semana%2017/04-Jueves-longest-substring-without-repeating-characters.md)

> [!quote] Para darle con todo
> «La frase más peligrosa del idioma es: «Siempre lo hemos hecho así».»
> — *Grace Hopper, pionera de la computación y almirante de la Marina de EE. UU.*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/minimum-size-subarray-sum/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Sliding window variable
- **Semana:** 17 — Sliding window (tema sin cubrir en el calendario) (problema 3 de 5)
- **Día:** [Semana 17 — Miércoles](../../Semanas/Semana%2017/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Maximum Average Subarray I](../Semana%2017/01-Lunes-maximum-average-subarray-i.md):** Es una ventana, pero ahora de tamaño variable.
- **Repaso del patrón:** [Dos punteros y ventana deslizante](../../Estudio/Articulos/04-Dos-punteros-y-ventana-deslizante.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> El puntero derecho expande la ventana y suma.

> [!question]- Pista 2 — ¿qué estructura usar?
> Mientras `suma >= target`, guarda el tamaño y contrae desde la izquierda.

> [!question]- Pista 3 — el algoritmo
> Cada puntero se mueve a lo mucho n veces, así que es O(n).

> [!warning]- Trampa común
> Contraer con un `if` en lugar de un `while`.

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
