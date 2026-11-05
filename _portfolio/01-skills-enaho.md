---
title: "Cuatro skills que limpian la ENAHO 2024"
orden: 1
destacado: true
imagen: /images/proyectos/skills-enaho.jpg
imagen_alt: "Mapa de la pobreza monetaria por departamento, Perú 2024"
etiquetas: [Claude Code, Python, ENAHO]
contexto: "Data Science con Python · QLab PUCP · octubre 2026"
pregunta: "¿Puede un agente limpiar la ENAHO y replicar la pobreza oficial, siempre de la misma forma?"
cifra: "27.6 %"
resultado: "de pobreza monetaria, igual que el INEI, con los mismos 108,664 residentes habituales."
excerpt: "Skills de Claude Code que descargan, limpian, grafican y mapean la ENAHO 2024 y replican la pobreza oficial."
enlaces:
  - {texto: "Código", url: "https://github.com/LuisGuevaraVega/skills_enaho"}
  - {texto: "Evaluación con y sin skills", url: "https://github.com/LuisGuevaraVega/skills_enaho/blob/main/evaluacion.md"}
---

Cuatro skills de Claude Code (descargar, limpiar, graficar y mapear) que trabajan siempre igual. Se encadenan solas: si pido «haz un mapa de la pobreza por departamento» y falta la base limpia, Claude primero la limpia, y si faltan los datos, primero los descarga del INEI.

## Validación contra el INEI

| Indicador | Obtenido | INEI |
|---|---|---|
| Pobreza monetaria | 27.58 % | 27.6 % |
| Pobreza extrema | 5.50 % | 5.5 % |
| Residentes habituales | 108,664 | 108,664 |
| Departamentos en el mapa | 25 | 25 |

## Lo que muestran los datos

- La pobreza es de 24.8 % en el área urbana y de 39.3 % en la rural.
- Los departamentos más pobres son Cajamarca (45.0 %), Loreto (43.0 %) y Puno (39.9 %).
- Los menos pobres son Ica (6.0 %), Moquegua (11.0 %) y Madre de Dios (11.1 %).
