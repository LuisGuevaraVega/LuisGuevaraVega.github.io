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
title_en: "Four skills that clean Peru's 2024 household survey"
contexto_en: "Data Science with Python · QLab PUCP · October 2026"
pregunta_en: "Can an agent clean Peru's ENAHO household survey and replicate the official poverty rate, the same way every time?"
resultado_en: "monetary poverty, matching INEI, with the same 108,664 usual residents."
cuerpo_en: |
  Four Claude Code skills (download, clean, chart and map) that always work the same way. They chain on their own: if I ask for "a map of poverty by region" and the clean dataset is missing, Claude cleans it first, and if the raw data is missing, it downloads it from INEI first.

  ## Validation against INEI

  | Indicator | Obtained | INEI |
  |---|---|---|
  | Monetary poverty | 27.58 % | 27.6 % |
  | Extreme poverty | 5.50 % | 5.5 % |
  | Usual residents | 108,664 | 108,664 |
  | Regions on the map | 25 | 25 |

  ## What the data shows

  - Poverty is 24.8 % in urban areas and 39.3 % in rural areas.
  - The poorest regions are Cajamarca (45.0 %), Loreto (43.0 %) and Puno (39.9 %).
  - The least poor are Ica (6.0 %), Moquegua (11.0 %) and Madre de Dios (11.1 %).
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
