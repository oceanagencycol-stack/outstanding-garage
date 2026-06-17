---
title: Outstanding Garage 🚪
colorFrom: gray
colorTo: blue
sdk: static
emoji: 🚪
pinned: false
---

# Outstanding Garage 🚪

Landing page premium para Outstanding Garage — especialistas en instalación y mantenimiento de puertas de garaje modernas (Miami, FL).

## Características

- **Bilingüe ES / EN** — switch en la barra de navegación. Detecta el idioma del navegador y recuerda la preferencia del visitante (localStorage).
- **Video de ensamblaje controlado por scroll** — en la sección "Proceso", el video de la puerta se ensambla cuadro a cuadro a medida que el usuario hace scroll (efecto tipo Apple). Incluye respaldo automático a reproducción normal en navegadores que no soportan scrubbing y respeto a `prefers-reduced-motion`.
- Diseño oscuro premium, animaciones reveal al scroll, cursor personalizado en escritorio, parallax en el hero, galería tipo mosaico, navbar con auto-ocultado y botón flotante de WhatsApp.
- 100% responsive, sin dependencias de build: un solo `index.html`.

## Stack

- HTML + Tailwind (CDN) + JavaScript vanilla
- Iconos: Lucide
- Tipografía: Inter (Google Fonts)
- Media (imágenes y video): Cloudinary

## Estructura

```
index.html    → toda la página (estilos + markup + scripts)
README.md     → este archivo
style.css     → estilos heredados de la plantilla (no se usa; los estilos viven en index.html)
```

## Publicar

Es un sitio estático. Funciona en cualquier hosting estático:

- **Hugging Face Spaces** (sdk: static) — sube los archivos al Space.
- **Vercel** — importa el repo de GitHub; framework preset "Other".
- Cualquier servidor que sirva `index.html`.

---

Construido por Ocean Industries · we turn brands into waves
