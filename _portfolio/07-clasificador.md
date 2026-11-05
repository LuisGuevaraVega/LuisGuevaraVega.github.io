---
title: "Noticias peruanas: del titular al clasificador"
orden: 7
destacado: false
imagen: /images/proyectos/clasificador.jpg
imagen_alt: "F1 macro de tres enfoques para clasificar titulares"
etiquetas: [NLP, DistilBERT, Scraping]
contexto: "Python Intermedio · QLab PUCP · octubre 2026"
pregunta: "¿Se pueden convertir titulares peruanos en un clasificador de noticias?"
cifra: "F1 0.913"
resultado: "con un DistilBERT afinado sobre 458 titulares de La República, frente a 0.672 de un modelo sin entrenar."
excerpt: "Scraping de La República, etiquetado con un LLM y DistilBERT afinado para clasificar titulares."
enlaces:
  - {texto: "Dashboard", url: "https://tarea1-luisguevara-larepublica-dashboard-en-vivo.streamlit.app/"}
  - {texto: "Código", url: "https://github.com/LuisGuevaraVega/python_interm_dip_qlab/tree/main/tarea_1"}
---

Descargué 458 noticias de La República y las etiqueté con un LLM (supervisión débil) en cuatro categorías: política, economía, deportes y ciencia y tecnología. Con esas etiquetas afiné un DistilBERT multilingüe.

El LLM clasifica un poco mejor (F1 de 0.942), pero tarda de 1 a 3 segundos por lote y cuesta por llamada. El DistilBERT llega a 0.913 y clasifica cada titular en 17 ms en una CPU, sin pagar nada. En una auditoría humana de 20 predicciones del LLM coincidí con las 20.
