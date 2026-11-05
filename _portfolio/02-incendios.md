---
title: "Incendios de Chichas y Río Tambo vistos desde el espacio"
orden: 2
destacado: true
imagen: /images/proyectos/incendios.jpg
imagen_alt: "Mapa del área quemada en Río Tambo, Satipo, con imágenes Sentinel-2"
etiquetas: [Sentinel-2, Geoespacial, Python]
contexto: "Python Intermedio · QLab PUCP · octubre 2026"
pregunta: "¿Cuánto se quemó en dos de los incendios más grandes de octubre de 2026 y qué edificaciones quedan expuestas?"
cifra: "2,695 ha"
resultado: "quemadas en Río Tambo (98 % bosque) y 648 edificaciones a 1 km o menos del fuego."
excerpt: "Área quemada con Sentinel-2, cobertura con WorldCover y edificaciones expuestas con Google Open Buildings."
enlaces:
  - {texto: "Informe interactivo 3D", url: "https://luisguevaravega.github.io/incendios-peru/"}
  - {texto: "Código", url: "https://github.com/LuisGuevaraVega/incendios-peru"}
  - {texto: "Diapositivas", url: "https://claude.ai/artifact/PVJG8uQaNE7VpfKT9hgWjy"}
---

Medí dos incendios de octubre de 2026 con imágenes Sentinel-2 (dNBR), los crucé con la cobertura del suelo de ESA WorldCover y el relieve, y ubiqué las edificaciones de Google Open Buildings que quedan cerca del fuego. Todos los datos son abiertos y no piden clave ni pago.

## Tres hallazgos

1. **Chichas (Arequipa): 1,475 ha en tres días**, 72 % pastizal y 28 % matorral, entre 3,337 y 4,112 m. Con el umbral clásico de dNBR habrían salido solo 91 ha: el 94 % del área ardió con severidad baja, típica del pasto de puna.
2. **Río Tambo (Junín): 2,695 ha, 98 % bosque, y seguía activo.** Hubo 778 focos VIIRS desde el 28 de septiembre. El clima no lo explica: ardió con una humedad mínima de 45 % a 70 %. La explicación son las quemas.
3. **648 edificaciones a 1 km o menos del fuego**, de las cuales 322 tienen exposición alta y 6 ya estaban dentro del área quemada.

El índice de exposición no predice qué casa se quemará. Solo ordena dónde conviene mirar primero.
