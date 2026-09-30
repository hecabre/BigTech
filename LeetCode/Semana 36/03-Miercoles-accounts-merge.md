# Accounts Merge

[← Anterior: Random Pick with Weight](../Semana%2036/02-Martes-random-pick-with-weight.md) · [Siguiente: Basic Calculator II →](../Semana%2036/04-Jueves-basic-calculator-ii.md)

> [!quote] Para darle con todo
> «He fallado más de 9,000 tiros en mi carrera. He perdido casi 300 partidos. 26 veces me confiaron el tiro ganador y lo fallé. He fallado una y otra y otra vez en mi vida. Y por eso tengo éxito.»
> — *Michael Jordan, seis veces campeón de la NBA*

- **Problema:** [Abrir en LeetCode](https://leetcode.com/problems/accounts-merge/)
- **Dificultad:** Medium
- **Tipo:** Nuevo
- **Patrón:** Union-Find
- **Semana:** 36 — Otras empresas — Medium variados (problema 3 de 5)
- **Día:** [Semana 36 — Miércoles](../../Semanas/Semana%2036/03-Miercoles.md)
- **Registro general:** [añadir intento](../Registro.md)
- **Estado:** Nuevo

## Por qué este problema

- **Se conecta con [Redundant Connection](../Semana%2025/05-Viernes-redundant-connection.md):** Es Union-Find sobre los correos.
- **Repaso del patrón:** [Orden topológico](../../Estudio/Articulos/15-Orden-topologico.md)

## Guía — abre una pista solo cuando te atores

> [!question]- Pista 1 — ¿qué observar?
> Dos cuentas son la misma persona si comparten algún correo.

> [!question]- Pista 2 — ¿qué estructura usar?
> Une todos los correos de cada cuenta con el primero de esa cuenta.

> [!question]- Pista 3 — el algoritmo
> Agrupa por `find(correo)`, ordena cada grupo y agrega el nombre al inicio.

> [!warning]- Trampa común
> Unir cuentas por nombre: dos personas pueden llamarse igual.

> [!success]- Complejidad meta
> Tiempo O(N log N), espacio O(N)

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
