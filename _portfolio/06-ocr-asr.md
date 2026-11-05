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
title_en: "Peruvian voices and documents: from scans to searchable text"
contexto_en: "Intermediate Python · QLab PUCP · October 2026"
pregunta_en: "Can we turn scanned documents and recorded interviews into a structured, searchable text archive?"
resultado_en: "with PaddleOCR on documents and WER 0.218 with faster-whisper on interviews."
cuerpo_en: |
  An AI pipeline for 25 documents and 23 audio clips from Wikimedia Commons, all openly licensed. It extracts text with OCR, transcribes the interviews, pseudonymizes private individuals, pulls structured fields with an LLM and publishes everything in a dashboard.

  ## Findings

  - **The type of document matters more than the model.** PaddleOCR reads printed text and photos almost flawlessly (CER of 0.04 and 0.03), but on handwriting the error rises to 0.24.
  - **For audio, the smallest model is the best choice.** faster-whisper *small* and Qwen3-ASR have almost the same error (0.22 vs 0.23), but Whisper transcribes 2.3 times faster.
  - **Handwriting and crowds still need human review.**
---

Un pipeline de IA para 25 documentos y 23 clips de audio de Wikimedia Commons, todos con licencia libre. Extrae el texto con OCR, transcribe las entrevistas, seudonimiza a las personas privadas, saca campos estructurados con un LLM y publica todo en un dashboard.

## Hallazgos

- **El tipo de documento importa más que el modelo.** PaddleOCR lee impresos y fotos casi sin errores (CER de 0.04 y 0.03), pero en manuscritos el error sube a 0.24.
- **En audio, el modelo más pequeño es la mejor opción.** faster-whisper *small* y Qwen3-ASR tienen casi el mismo error (0.22 frente a 0.23), pero Whisper transcribe 2.3 veces más rápido.
- **Los manuscritos y las multitudes todavía necesitan revisión humana.**
