# Estudio Creativo Chinchulín

Portfolio personal desarrollado como parte del curso de Desarrollo Web en Coderhouse. El sitio presenta los servicios de freelance de Camila (landing pages, mantenimiento y branding) y una galería con proyectos reales entregados a clientes.

## Tecnologías utilizadas

- HTML5 semántico
- SCSS (variables, partials, nesting, mixins y `@use`), compilado a un único `style.css`
- Flexbox y CSS Grid con `grid-template-areas`
- Bootstrap 5.3.3 (navbar responsive, carousel)
- Google Fonts (Fraunces + Work Sans)

## Estructura del proyecto

```
├── index.html
├── pages/
│   ├── sobre-mi.html
│   ├── proyectos.html
│   ├── servicios.html
│   └── contacto.html
├── styles/
│   ├── style.css          (compilado, no editar a mano)
│   └── scss/
│       ├── main.scss      (punto de entrada)
│       ├── utilities/
│       │   ├── _variables.scss
│       │   └── _mixins.scss
│       ├── base/
│       │   ├── _base.scss
│       │   └── _tipografia.scss
│       ├── layout/
│       │   ├── _header.scss
│       │   ├── _nav.scss
│       │   ├── _hero.scss
│       │   └── _footer.scss
│       └── components/
│           ├── _buttons.scss
│           ├── _links.scss
│           ├── _cards.scss
│           ├── _carousel.scss
│           └── _forms.scss
└── assets/
    └── img/
```

## Cómo compilar el SCSS

Los estilos se editan en los archivos `.scss` dentro de `styles/scss/`, nunca directamente en `style.css`. Para compilar:

```
npm install -g sass
sass styles/scss/main.scss styles/style.css --style=expanded
```

## Funcionalidades

- Navbar responsive con menú hamburguesa en mobile (Bootstrap)
- Galería de proyectos con carousel (Bootstrap) en Inicio y Proyectos
- Estados `:hover`, `:focus` y `:active` con transiciones en todos los elementos interactivos
- Diseño mobile-first con CSS Grid y Flexbox
- Paleta de colores personalizada (soft pink, butter yellow, celeste)

## Autora

Camila Zoulalian
