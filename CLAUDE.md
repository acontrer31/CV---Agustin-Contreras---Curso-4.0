# CLAUDE.md

Este archivo guía a Claude Code al trabajar en este repositorio.

## Descripción del proyecto

Sitio web estático de CV (Curriculum Vitae) de Agustín Contreras Vidal, desarrollado
como práctica del Curso Front End Developer - Programar Argentina 4.0.

## Stack

- HTML5 + CSS3 puro, sin frameworks ni build tools.
- `index.html` — contenido del CV.
- `style.css` — estilos.
- `package.json` incluye dependencias de Node (Express, nodemon, etc.) heredadas
  del bootstrap del curso; el sitio en sí no requiere un servidor para funcionar,
  basta con abrir `index.html` en el navegador.

## Cómo trabajar en este repo

- No hay proceso de build ni linter configurado: los cambios en `index.html` y
  `style.css` se ven reflejados directamente.
- Verificar cambios abriendo `index.html` en el navegador (o `npx serve .` si se
  prefiere un servidor local).
- Mantener el HTML semántico y el CSS organizado por secciones, siguiendo el
  estilo ya presente en el archivo.
- Los textos del sitio están en español; mantener ese idioma en el contenido.

## Convenciones de Git

- Mensajes de commit claros y descriptivos, en español o inglés según el commit
  history existente.
- Commits atómicos, enfocados en un solo cambio.

## Antes de dar por terminada una tarea

- [ ] El HTML es válido y semántico.
- [ ] Los estilos no rompen el layout existente.
- [ ] Las rutas a assets (imágenes, CSS, favicon) son correctas.
- [ ] El contenido del CV es preciso y está en español.
