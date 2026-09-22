# RAPO Creative — Proyecto Final

Sitio web estático de 5 páginas desarrollado como proyecto final del curso, integrando HTML5 semántico, SCSS con arquitectura de partials, Bootstrap, diseño responsive, animaciones, SEO y preparación para despliegue en Vercel o Netlify.

## Páginas

- `index.html`
- `pages/nosotros.html`
- `pages/servicios.html`
- `pages/proyectos.html`
- `pages/contacto.html`

## Tecnologías

- HTML5 semántico
- SCSS
- CSS3
- Bootstrap 5.3.8
- Animate.css
- Git y GitHub

## Arquitectura SCSS

El código fuente de estilos está organizado dentro de `scss/` mediante partials.

Incluye:

- Variables
- Nesting
- Mixins con parámetros
- `@extend`
- Partials
- Media queries
- Animaciones con `@keyframes`

El archivo `scss/main.scss` contiene únicamente sentencias `@use`.

El CSS compilado utilizado por el sitio se encuentra en:

`styles/styles.css`

## Responsividad

El sitio fue trabajado con enfoque Mobile First y media queries para:

- Mobile
- Tablet
- Desktop

Se utiliza Grid, Flexbox y componentes responsivos de Bootstrap. También se evita el scroll horizontal mediante ajustes específicos de ancho y overflow.

## Bootstrap

Las cinco páginas incluyen una navbar Bootstrap responsive con menú hamburguesa funcional en dispositivos móviles y estilos personalizados para mantener la identidad visual de RAPO Creative.

## Animaciones

El proyecto utiliza dos tipos de animaciones:

1. Animación nativa mediante SCSS/CSS con `@keyframes rapo-enter`.
2. Librería externa Animate.css mediante CDN.

## SEO

Cada HTML contiene:

- `<title>` único
- `meta description` propia
- `meta keywords` propia
- atributos `alt` descriptivos en imágenes
- estructura HTML semántica
- URL canónica
- metadatos Open Graph
- datos estructurados JSON-LD

También se incluyen:

- `robots.txt`
- `sitemap.xml`

## Estructura

```text
.
├── index.html
├── pages/
│   ├── nosotros.html
│   ├── servicios.html
│   ├── proyectos.html
│   └── contacto.html
├── scss/
│   ├── utilities/
│   │   ├── _variables.scss
│   │   ├── _mixins.scss
│   │   └── _extends.scss
│   ├── base/
│   │   └── _base.scss
│   ├── components/
│   │   ├── _navbar.scss
│   │   ├── _cards.scss
│   │   ├── _carousel.scss
│   │   ├── _accordion.scss
│   │   └── _animations.scss
│   ├── layout/
│   │   ├── _layout.scss
│   │   ├── _footer.scss
│   │   └── _responsive.scss
│   ├── pages/
│   │   └── _home.scss
│   └── main.scss
├── styles/
│   └── styles.css
├── assets/
│   └── img/
├── robots.txt
├── sitemap.xml
└── README.md
```

## Compilación SCSS

Ejemplo con Sass:

```bash
sass scss/main.scss styles/styles.css
```

Para trabajar observando cambios:

```bash
sass --watch scss/main.scss styles/styles.css
```

## Deploy

El sitio debe desplegarse en Vercel o Netlify una vez creado el repositorio público definitivo de esta entrega.

**URL del deploy:** pendiente de completar al publicar el repositorio final.

## Entrega

La entrega final deberá realizarse mediante un repositorio público nuevo e independiente de las entregas anteriores.

Repositorio final previsto:

`rapo-proyecto-final`

Debe contener al menos dos commits descriptivos y el enlace público del deploy en este README.
