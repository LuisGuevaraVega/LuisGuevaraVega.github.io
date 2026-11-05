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
---

Comparamos la lluvia de cada departamento entre enero y mayo de 2022 (Open-Meteo) con las declaratorias de emergencia por lluvias de la PCM, que recogimos con scraping de gob.pe. Las dos fuentes se unieron por ubigeo.

Los tres departamentos que sí tuvieron declaratoria quedan en los puestos 13 (Ayacucho), 15 (Amazonas) y 20 (Piura) de 25. **Con solo un decreto y tres casos, la comparación es frágil.** Describe esta temporada, pero no prueba que el Estado nunca declare emergencia donde más llueve.
