# Course Schedule

[← Anterior: Minimum Window Substring](../Semana%2034/03-Miercoles-minimum-window-substring.md) · [Siguiente: Coin Change →](../Semana%2034/05-Viernes-coin-change.md)

> [!quote] Para darle con todo
> «Pies, ¿para qué los quiero si tengo alas pa' volar?»
> — *Frida Kahlo, de su diario, 1953*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/course-schedule/)
- **Dificultad:** Medium
- **Tipo:** Repaso
- **Patrón:** Topological sort
- **Semana:** 34 — Últimos patrones nuevos (problema 4 de 5)
- **Día:** [Semana 34 — Jueves](../../Semanas/Semana%2034/04-Jueves.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

> [!tip] Repaso
> Ya lo viste antes. Meta: resolverlo en 20 minutos o menos, sin notas, y explicar el invariante en voz alta. Abre las pistas solo si te atoras.

## Por qué este problema

- **Conexión:** Es la plantilla base de orden topológico y detección de ciclos.
- **Repaso del patrón:** [Orden topológico](../../Estudio/Articulos/15-Orden-topologico.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Los cursos son nodos; los prerrequisitos son aristas.

> [!question]- Pista 2 — ¿qué estructura usar?
> Kahn: usa grados de entrada y una cola con los de grado 0.

> [!question]- Pista 3 — el algoritmo
> Si procesas los n cursos, no hay ciclo.

> [!warning]- Trampa común
> Invertir la dirección de las aristas.

> [!success]- Complejidad meta
> Tiempo O(V + E), espacio O(V + E)

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
