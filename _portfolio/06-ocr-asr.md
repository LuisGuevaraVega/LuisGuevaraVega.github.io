---
title: "Voces y documentos peruanos: del escaneo al texto buscable"
orden: 6
destacado: false
imagen: /images/proyectos/ocr-asr.jpg
imagen_alt: "Manuscrito de Miguel Grau, de dominio público, uno de los documentos del corpus"
etiquetas: [OCR, ASR, LLM]
contexto: "Python Intermedio · QLab PUCP · octubre 2026"
pregunta: "¿Podemos convertir documentos escaneados y entrevistas en audio en un archivo de texto buscable?"
cifra: "CER 0.091"
resultado: "con PaddleOCR en documentos y WER 0.218 con faster-whisper en entrevistas."
excerpt: "Pipeline de OCR, transcripción, seudonimización y extracción con LLM sobre documentos y audios peruanos."
enlaces:
  - {texto: "Dashboard", url: "https://tarea-2-texto-audio.streamlit.app/"}
  - {texto: "Código", url: "https://github.com/LuisGuevaraVega/python_interm_dip_qlab/tree/main/tarea_2"}
---

Un pipeline de IA para 25 documentos y 23 clips de audio de Wikimedia Commons, todos con licencia libre. Extrae el texto con OCR, transcribe las entrevistas, seudonimiza a las personas privadas, saca campos estructurados con un LLM y publica todo en un dashboard.

## Hallazgos

- **El tipo de documento importa más que el modelo.** PaddleOCR lee impresos y fotos casi sin errores (CER de 0.04 y 0.03), pero en manuscritos el error sube a 0.24.
- **En audio, el modelo más pequeño es la mejor opción.** faster-whisper *small* y Qwen3-ASR tienen casi el mismo error (0.22 frente a 0.23), pero Whisper transcribe 2.3 veces más rápido.
- **Los manuscritos y las multitudes todavía necesitan revisión humana.**
