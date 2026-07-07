# AGENTS.md

## Purpose

Portafolio personal de Sebastián Vergara (Senior Software Engineer). Sitio estático hospedado en GitHub Pages para postulaciones laborales.

## Repository

- **GitHub:** https://github.com/svergara-dev/svergara-dev.github.io
- **Live URL:** https://svergara-dev.github.io/

## Tech Stack

- HTML5 semántico
- CSS3 vanilla (variables CSS, grid, flexbox)
- JavaScript vanilla (Intersection Observer, theme toggle)
- Google Fonts (Inter)
- Sin frameworks ni dependencias externas

## Structure

```
├── index.html        ← Página principal (single-page, 6 secciones)
├── css/style.css     ← Estilos (modo oscuro/claro, responsive)
├── js/script.js      ← Interacciones (scroll reveal, nav activo, theme toggle)
├── assets/           ← Imágenes (pendiente)
├── AGENTS.md         ← Este archivo
└── MEMORY.md         ← Correcciones y datos del perfil
```

## Sections

1. **Hero** — Nombre, título, frase, links (LinkedIn, GitHub, Email)
2. **Sobre mí** — Resumen profesional, datos clave
3. **Habilidades** — Grid por categorías (Frontend, Backend, DB, DevOps, Testing)
4. **Proyectos** — 5 proyectos destacados con links a repos
5. **Experiencia** — Línea de tiempo: Fracttal → Buk → Propal
6. **Contacto** — Formulario + links directos

## Deployment

1. Hacer cambios en los archivos
2. `git add . && git commit -m "mensaje"`
3. `git push`
4. GitHub Pages actualiza automáticamente en 1-2 minutos

## Conventions

- Cambios en español
- Sin comentarios en el código
- Mantener diseño responsive
- Probar modo oscuro/claro después de cambios CSS
