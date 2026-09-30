# LeetCode opcional

Esta ruta añade **un problema opcional por día laboral**. No sustituye las tareas principales del calendario.

## Flujo

1. Leer **Por qué este problema**: dice con qué problema anterior se conecta. Si no recuerdas ese problema, ábrelo primero.
2. Intentar el problema 10–15 minutos sin ayuda y escribir el enfoque antes del código.
3. Si te atoras, abre **una** pista (están plegadas) y vuelve a intentar. Pista 1 → observación, Pista 2 → estructura de datos, Pista 3 → algoritmo.
4. Antes de enviar, abre **Trampa común** y revisa que no caíste en ella.
5. Probar casos límite y comparar tu complejidad con la **Complejidad meta**.
6. Si con la Pista 3 tampoco sale, estudia la solución y reconstrúyela sin copiar. Anota qué pista usaste en la nota y en el [registro general](Registro.md).

Usar pistas no es hacer trampa: es exactamente para lo que están. Lo que importa es poder explicarlo después.

## Cómo están unidos los problemas

- Cada nota tiene **← Anterior / Siguiente →**: la ruta completa se puede recorrer de corrido de la semana 4 a la 38.
- Cada nota dice **Se conecta con**: el problema en el que se apoya (de la misma semana, de una anterior o del calendario).
- Cada nota semanal tiene un **Hilo de LeetCode de la semana** con los 5 problemas en orden.
- Cada nota diaria tiene una **frase del día**, una **cita de alguien que la rompió** (Jordan, Kobe, Tyson, Goggins, Bezos, Feynman…) y un **mínimo que cuenta** para los días pesados.
- Cada nota de problema abre con una cita **"Para darle con todo"**.

## Estados

- `Nuevo`: todavía no intentado.
- `Con ayuda`: fue necesario consultar una pista o solución.
- `Resuelto`: pasó los casos de prueba, pero aún cuesta explicarlo.
- `Explicable`: se puede reconstruir y justificar sin ayuda.

Los problemas se repiten deliberadamente en semanas posteriores cuando conviene practicar recuperación espaciada.

## Curva de dificultad

La ruta sigue el tema que el [calendario](../01-CALENDARIO_SEMANAL_BIG_TECH_AWS.md) enseña esa semana: nunca pide un patrón antes de que se haya visto en el calendario.

| Periodo | Mezcla objetivo | Por qué |
|---|---|---|
| Semanas 4–13 (sep–nov) | Mayoría Easy, 1–3 Medium | Sesiones de 30–45 min en semestre. Primero se automatiza el patrón. |
| Semanas 14–27 (dic–mar) | Mayoría Medium | Amazon OA y la entrevista técnica se evalúan sobre Medium. |
| Semanas 28–34 (mar–abr) | Medium + máximo un Hard por semana | Solo Hards clásicos de Amazon: Merge k Sorted Lists, Word Ladder, Trapping Rain Water, Serialize Tree, Minimum Window Substring. |
| Semanas 35–38 (mayo) | Repaso | Velocidad y explicación en voz alta; nada nuevo antes de entrevistas. |

### Reglas de ajuste

- **Medium atascado:** si a los 35 min no tienes enfoque, busca un Easy del mismo patrón, resuélvelo y vuelve al Medium al día siguiente.
- **Hard:** límite de 45 min. Si no sale, estudia la solución y reintenta en 7 días.
- **Repaso:** meta de 20 min sin notas. Si tardas más, vuelve a agendarlo en 7 días en el [registro](Registro.md).
- **Dos Medium seguidos resueltos en menos de 25 min:** puedes sustituir el siguiente Easy por un Medium del mismo tema.

## Ruta semanal

| Semana | Enfoque | Mezcla | Repasos |
|---:|---|---|---:|
| 04 | Calentamiento arrays/strings (semana de examen CCP) | 4E / 1M | 1 |
| 05 | Pilas | 4E / 1M | 0 |
| 06 | Pila monotónica | 2E / 3M | 1 |
| 07 | Listas enlazadas | 4E / 1M | 0 |
| 08 | Búsqueda binaria | 3E / 2M | 0 |
| 09 | Árboles — DFS | 5E | 0 |
| 10 | Árboles — BFS por niveles | 3E / 2M | 0 |
| 11 | BST | 3E / 2M | 0 |
| 12 | Heaps | 2E / 3M | 0 |
| 13 | Grafos — introducción | 3E / 2M | 0 |
| 14 | Grafos — BFS y grids | 5M | 1 |
| 15 | Backtracking | 1E / 4M | 0 |
| 16 | Semana ligera — repaso de fundamentos | 4E / 1M | 5 |
| 17 | Sliding window (tema sin cubrir en el calendario) | 2E / 3M | 2 |
| 18 | Intervalos y greedy | 1E / 4M | 0 |
| 19 | Prefix sums + sliding window | 1E / 4M | 0 |
| 20 | Matrices + repaso bajo presión (semana SAA) | 5M | 2 |
| 21 | Semana de examen SAA — solo repaso | 4E / 1M | 5 |
| 22 | Sliding window y prefix sums avanzados | 5M | 1 |
| 23 | DP de una dimensión | 2E / 3M | 0 |
| 24 | DP de dos dimensiones | 5M | 0 |
| 25 | Orden topológico y Union-Find | 5M | 0 |
| 26 | Diseño de estructuras (POO) | 1E / 4M | 0 |
| 27 | Mixto árboles y grafos | 5M | 0 |
| 28 | Heaps avanzados + primer Hard | 4M / 1H | 1 |
| 29 | Caminos más cortos | 4M / 1H | 1 |
| 30 | Strings y arrays clásicos de Amazon | 4M / 1H | 1 |
| 31 | Etiquetados frecuentes de Amazon | 1E / 4M | 1 |
| 32 | Árboles nivel entrevista | 4M / 1H | 2 |
| 33 | Semana de mocks — repaso de clásicos | 1E / 3M / 1H | 5 |
| 34 | Últimos patrones nuevos | 4M / 1H | 2 |
| 35 | Simulación Amazon — repaso OA | 3M / 2H | 5 |
| 36 | Otras empresas — Medium variados | 5M | 1 |
| 37 | Eliminar errores repetidos — trampas típicas | 5M | 5 |
| 38 | Modo entrevista — repaso ligero | 1E / 4M | 5 |

Las semanas 1–3 se conservan como estaban porque ya se trabajaron.

## Navegación

- [Registro general](Registro.md)
- [Plan semanal](../Semanas/00-%C3%8Dndice-semanal.md)
- [LeetCode 75 oficial](https://leetcode.com/studyplan/leetcode-75/)
