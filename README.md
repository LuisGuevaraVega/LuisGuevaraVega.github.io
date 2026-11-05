# luisguevaravega.github.io

Portafolio de **Luis Gabriel Guevara Vega**, economista PUCP: <https://luisguevaravega.github.io>

Hecho con el template [academicpages](https://github.com/academicpages/academicpages.github.io) y Claude Code. Se publica solo con GitHub Actions en cada push a `main`.

## Dónde está cada cosa

| Qué | Dónde |
|---|---|
| Portada | `_layouts/inicio.html` y `_pages/about.md` |
| Cifras de la cinta de la portada | `_data/cifras.yml` |
| Proyectos, uno por archivo | `_portfolio/` (campos: `pregunta`, `cifra`, `resultado`, `enlaces`, `orden`, `destacado`) |
| Videos, tesis y CV | `_pages/videos.md`, `_pages/tesis.md`, `_pages/cv.md` |
| Estilo propio | `assets/css/gabo.css` |
| Imágenes y PDF | `images/`, `images/proyectos/`, `files/` |

## Agregar un proyecto

Copia un archivo de `_portfolio/`, cambia los campos y pon su imagen en `images/proyectos/` (JPG de unos cientos de KB). Para que salga en la portada, usa `destacado: true`.

## Lo que no se sube

El CV original, el diploma y la foto original están en `.gitignore`. El CV público, sin teléfonos ni referencias, es `files/cv-luis-guevara-vega.pdf`.
