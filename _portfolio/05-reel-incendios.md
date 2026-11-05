---
title: "Del informe al reel, con mi voz clonada"
orden: 5
destacado: false
imagen: /images/proyectos/reel-incendios.jpg
imagen_alt: "Portada del reel sobre los incendios de Chichas y Río Tambo"
etiquetas: [Qwen3-TTS, Whisper, Video]
contexto: "Python Intermedio · QLab PUCP · octubre 2026"
pregunta: "¿Se puede convertir un informe en un reel de un minuto con modelos abiertos, sin inventar cifras?"
cifra: "59.6 s"
resultado: "de reel en 8 escenas. DeepSeek inventó menos que Qwen, y cada frase se revisó contra el informe."
excerpt: "Reel vertical narrado con mi voz clonada (Qwen3-TTS) y subtítulos palabra por palabra (Whisper)."
enlaces:
  - {texto: "Código", url: "https://github.com/LuisGuevaraVega/reel-incendios"}
  - {texto: "Qwen vs DeepSeek", url: "https://github.com/LuisGuevaraVega/reel-incendios/blob/main/comparacion.md"}
title_en: "From report to reel, with my cloned voice"
contexto_en: "Intermediate Python · QLab PUCP · October 2026"
pregunta_en: "Can a report become a one-minute reel with open models, without making up numbers?"
resultado_en: "reel in 8 scenes. DeepSeek invented less than Qwen, and every sentence was checked against the report."
cuerpo_en: |
  A one-minute vertical reel based on [my wildfire report](/portfolio/02-incendios/). Qwen and DeepSeek wrote the script from the same prompt. A script flags every number that is not in the report, and then I review each sentence. The voice is mine, cloned with Qwen3-TTS from 15 seconds of audio. Whisper listens to each scene again and regenerates it if more than 25 % of the words are wrong.

  **The video says throughout that the voice is AI-generated.** The original recording is not in the repository: with it, anyone could clone me.
---

Un reel vertical de un minuto hecho a partir de [mi informe de incendios](/portfolio/02-incendios/). El guion lo escribieron Qwen y DeepSeek con el mismo prompt. Un script marca toda cifra que no aparece en el informe, y después yo reviso cada frase. La voz es la mía, clonada con Qwen3-TTS a partir de 15 segundos de audio. Whisper vuelve a escuchar cada escena y la repite si falla más del 25 % de las palabras.

**El video dice todo el tiempo que la voz fue generada con IA.** La grabación original no está en el repositorio: con ella cualquiera podría clonarme.
