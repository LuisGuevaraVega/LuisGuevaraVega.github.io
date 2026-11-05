---
title: "Un MCP con las 17,167 series del BCRP"
orden: 3
destacado: true
imagen: /images/proyectos/bcrp-mcp.jpg
imagen_alt: "Nota de coyuntura generada con el MCP: inflación, expectativas y tasa de referencia"
etiquetas: [MCP, Claude Code, Python]
contexto: "Data Science con Python · QLab PUCP · octubre 2026"
pregunta: "¿Cuántas cifras oficiales del BCRP acierta Claude de memoria y cuántas con un servidor propio?"
cifra: "12 de 12"
resultado: "cifras correctas con el MCP. De memoria acertó 0 y buscando en la web, 8."
excerpt: "Servidor MCP con FastMCP que le da a Claude las series oficiales del BCRP y los indicadores del Banco Mundial."
enlaces:
  - {texto: "Código", url: "https://github.com/LuisGuevaraVega/bcrp-mcp"}
  - {texto: "Informe de la evaluación", url: "https://github.com/LuisGuevaraVega/bcrp-mcp/blob/main/informe.md"}
title_en: "An MCP server with the Central Bank of Peru's 17,167 series"
contexto_en: "Data Science with Python · QLab PUCP · October 2026"
pregunta_en: "How many official Central Bank of Peru figures does Claude get right from memory, and how many with a custom server?"
cifra_en: "12 of 12"
resultado_en: "correct figures with the MCP. From memory it got 0, and searching the web, 8."
cuerpo_en: |
  An [MCP](https://modelcontextprotocol.io) server built with FastMCP that gives Claude access to the 17,167 statistical series of the Central Reserve Bank of Peru (BCRP) and, for regional comparisons, to World Bank indicators. Python does the math, not the model. Every figure comes from a repeatable call and carries the URL of its source.

  ## What it can do

  - **Search series and fetch their data**, with warnings when a series is discontinued or does not reach the requested period.
  - **Transform the data:** year-on-year or cumulative change, base-100 indices and real values deflated with the Lima CPI. The results match the figures published by the BCRP, and the tests check it.
  - **Make publication-style charts and export to Excel**, with a metadata sheet.
  - **Compare Peru with other countries** through the World Bank API. This tool is my own addition.
  - **Write a macroeconomic brief** that cites the code and period of every figure.

  ## The evaluation

  I asked Claude 12 questions about 2025 and 2026 figures. From memory it answered "I don't know" to all of them, without making anything up. With the MCP it got all 12 right and cited the series and URL for each one. In a second run, web search got 8 and the MCP, 11.
---

Un servidor [MCP](https://modelcontextprotocol.io) hecho con FastMCP que le da a Claude acceso a las 17,167 series estadísticas del Banco Central de Reserva del Perú y, para comparar con la región, a los indicadores del Banco Mundial. Las cuentas las hace Python y no el modelo. Cada cifra sale de una llamada que se puede repetir y viene con la URL de su fuente.

## Qué puede hacer

- **Buscar series y traer sus datos**, con avisos cuando una serie está descontinuada o no llega al periodo pedido.
- **Transformar los datos:** variación interanual o acumulada, índice base 100 y valores reales deflactados con el IPC de Lima. Los resultados coinciden con las cifras que publica el BCRP, y las pruebas lo verifican.
- **Hacer gráficos con estilo de publicación y exportar a Excel**, con una hoja de metadatos.
- **Comparar al Perú con otros países** con la API del Banco Mundial. Esta herramienta es propia.
- **Escribir una nota de coyuntura** que cita el código y el periodo de cada cifra.

## La evaluación

Hice a Claude 12 preguntas con cifras de 2025 y 2026. De memoria respondió «no sé» en todas, sin inventar nada. Con el MCP acertó las 12 y citó la serie y la URL de cada dato. En una segunda corrida, buscando en la web acertó 8 y el MCP, 11.
