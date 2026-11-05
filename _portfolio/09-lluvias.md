---
title: "¿El Estado declara emergencia donde más llueve?"
orden: 9
destacado: false
imagen: /images/proyectos/lluvias.jpg
imagen_alt: "Lluvia acumulada por departamento en 2022, con los tres departamentos que tuvieron declaratoria de emergencia"
etiquetas: [Streamlit, Scraping, Open-Meteo]
contexto: "Fundamentos de Python · QLab PUCP · 2026 · trabajo en grupo (G1)"
pregunta: "¿Coinciden las declaratorias de emergencia por lluvias de 2022 con los departamentos donde más llovió?"
cifra: "0 de 3"
resultado: "departamentos más lluviosos (Loreto, Ucayali y Áncash) tuvieron declaratoria de emergencia por lluvias."
excerpt: "Cruce de lluvia de Open-Meteo con decretos de la PCM, en un dashboard de Streamlit."
enlaces:
  - {texto: "Dashboard", url: "https://repositoriog1fundpython-fp6ocm6megy3k7eaoagk9r.streamlit.app/"}
  - {texto: "Código", url: "https://github.com/LuisGuevaraVega/Repositorio_G1_FundPython/tree/main/assignment_3"}
title_en: "Does the government declare emergencies where it rains most?"
contexto_en: "Python Fundamentals · QLab PUCP · 2026 · group project (G1)"
pregunta_en: "Did the 2022 rain emergency declarations match the regions where it rained the most?"
cifra_en: "0 of 3"
resultado_en: "rainiest regions (Loreto, Ucayali and Áncash) received a rain emergency declaration."
cuerpo_en: |
  We compared rainfall in each region between January and May 2022 (Open-Meteo) with the rain emergency declarations issued by the Prime Minister's Office, which we scraped from gob.pe. The two sources were joined by ubigeo code.

  The three regions that did get a declaration rank 13th (Ayacucho), 15th (Amazonas) and 20th (Piura) out of 25. **With a single decree and three cases, the comparison is fragile.** It describes this season, but it does not prove that the government never declares emergencies where it rains most.
---

Comparamos la lluvia de cada departamento entre enero y mayo de 2022 (Open-Meteo) con las declaratorias de emergencia por lluvias de la PCM, que recogimos con scraping de gob.pe. Las dos fuentes se unieron por ubigeo.

Los tres departamentos que sí tuvieron declaratoria quedan en los puestos 13 (Ayacucho), 15 (Amazonas) y 20 (Piura) de 25. **Con solo un decreto y tres casos, la comparación es frágil.** Describe esta temporada, pero no prueba que el Estado nunca declare emergencia donde más llueve.
