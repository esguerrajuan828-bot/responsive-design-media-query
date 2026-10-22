# Práctica: Diseño de Tarjetas con Clip-Path, Font Awesome y BEM

## Descripción del Ejercicio
Este proyecto consiste en la maquetación de dos tarjetas de presentación inspiradas en los boxeadores **Ilia Topuria** y **Gervonta Davis**, replicando el diseño propuesto en clase mediante HTML5 semántico y CSS3 moderno.

## Estructura de la Carpeta
- `index.html`: Estructura principal de las tarjetas utilizando la metodología **BEM** (Block, Element, Modifier).
- `css/style.css`: Hoja de estilos con diseño responsivo, Flexbox y recortes geométricos con `clip-path`.
- `topuria.png` / `gervonta.png`: Imágenes de perfil de los deportistas.

## Tecnologías y Conceptos Aplicados
1. **Propiedad `clip-path`:** Uso de polígonos (`polygon()`) generados con Clippy para crear los cortes diagonales y en punta tanto en el encabezado (`card__header`) como en el pie de tarjeta (`card__footer`).
2. **Font Awesome (CDN):** Integración de iconos vectoriales para los botones de contacto (`+`, WhatsApp, Email) y redes sociales (Facebook, LinkedIn, Twitter, Instagram).
3. **Metodología BEM:** Organización limpia y modular de clases CSS (`.card`, `.card__header--first`, `.card__action-btn--circle`, etc.).
