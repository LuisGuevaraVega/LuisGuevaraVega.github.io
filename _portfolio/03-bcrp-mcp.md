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
