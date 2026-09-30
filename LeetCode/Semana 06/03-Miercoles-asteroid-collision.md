# Asteroid Collision

[← Anterior: Crawler Log Folder](../Semana%2006/02-Martes-crawler-log-folder.md) · [Siguiente: Simplify Path →](../Semana%2006/04-Jueves-simplify-path.md)

> [!quote] Para darle con todo
> «Sabía que si fallaba no me iba a arrepentir. Lo único de lo que me podría arrepentir era de no haberlo intentado.»
> — *Jeff Bezos, sobre dejar su trabajo para fundar Amazon*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/asteroid-collision/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Stack
- **Semana:** 06 — Pila monotónica (problema 3 de 5)
- **Día:** [Semana 06 — Miércoles](../../Semanas/Semana%2006/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/):** La pila guarda a los sobrevivientes, como los paréntesis abiertos.
- **Repaso del patrón:** [Pilas y colas](../../Estudio/Articulos/05-Pilas-y-colas.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Solo chocan un asteroide que va a la derecha (tope > 0) y uno que va a la izquierda (actual < 0).

> [!question]- Pista 2 — ¿qué estructura usar?
> Mientras haya choque, compara tamaños: el menor explota; si son iguales, explotan los dos.

> [!question]- Pista 3 — el algoritmo
> Usa una bandera `vivo` para saber si el actual termina en la pila.

> [!warning]- Trampa común
> Hacer chocar `[-1, 1]`: van en direcciones opuestas y nunca se tocan.

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
