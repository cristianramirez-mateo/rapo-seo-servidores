# RAPO Creative — Entregable SEO y Servidores

Proyecto final del módulo, desarrollado para aplicar SEO local, técnico, on-page y off-page sobre el sitio de RAPO Creative. Incluye cinco páginas HTML semánticas, estilos propios, Bootstrap 5.3.8 y recursos gráficos con nombres descriptivos.

## Sitio y repositorio

- Sitio de la marca: [rapocreative.com.ar](https://rapocreative.com.ar/)
- Repositorio público de esta entrega: [cristianramirez-mateo/rapo-seo-servidores](https://github.com/cristianramirez-mateo/rapo-seo-servidores)

## Páginas

- `index.html`: agencia de marketing digital en Rosario.
- `pages/nosotros.html`: identidad, equipo, valores y forma de trabajo.
- `pages/servicios.html`: community management, diseño web y estrategia para creadoras.
- `pages/proyectos.html`: áreas de proyectos y proceso de trabajo.
- `pages/contacto.html`: contacto, ubicación y atención online.

## Palabras clave por página

| Página | Palabras clave principales |
| --- | --- |
| Inicio | agencia de marketing digital en Rosario, community management, diseño web |
| Nosotros | agencia de marketing en Rosario, equipo de marketing digital, estrategia de marca |
| Servicios | community management en Rosario, diseño web en Rosario, gestión de redes sociales |
| Proyectos | proyectos de marketing digital, portfolio de diseño web, marca personal |
| Contacto | contacto agencia de marketing Rosario, presupuesto de community manager, presupuesto diseño web |

Las palabras clave están integradas de forma natural en títulos, descripciones y contenido, sin repetirlas de manera excesiva.

## SEO aplicado

### SEO on-page

- Un solo `<h1>` por página y jerarquía ordenada de `<h2>` y `<h3>`.
- Títulos `<title>` únicos y descriptivos.
- Una `meta description` y una `meta keywords` específica en cada HTML.
- Contenido semántico organizado con `header`, `nav`, `main`, `section`, `article`, `figure`, `figcaption`, `address` y `footer`.
- Enlaces internos descriptivos entre las cinco páginas.
- Todas las imágenes poseen `alt` relacionado con su contenido.
- Nombres descriptivos para archivos HTML e imágenes.

### SEO técnico y local

- Atributo `lang="es-AR"`, diseño responsive y navegación accesible.
- URL canónica, directivas `robots`, metadatos Open Graph y tarjeta de X/Twitter en cada página.
- `robots.txt` y `sitemap.xml` con las cinco URLs públicas.
- Datos estructurados JSON-LD de tipo `ProfessionalService` con ubicación en Rosario, Santa Fe, Argentina.
- Ubicación visible dentro de la página de contacto.
- Recursos servidos por HTTPS y relaciones `noopener noreferrer` en enlaces externos.

### SEO off-page

- Enlace al perfil oficial de [RAPO Creative en Instagram](https://www.instagram.com/rapocreative/).
- Perfil social asociado mediante `sameAs` en los datos estructurados y `rel="me"` en los enlaces correspondientes.
- Metadatos Open Graph para que cada URL tenga un título y una descripción adecuados al compartirse.

## Accesibilidad

- Enlace “Saltar al contenido principal” en las cinco páginas.
- Textos alternativos descriptivos en todas las imágenes.
- Controles de Bootstrap con etiquetas ARIA.
- Estados visibles de foco para enlaces y botones.
- Se eliminaron focos innecesarios de elementos no interactivos.
- Paleta revisada según WCAG AA: el contraste mínimo de texto normal utilizado es superior a `4.5:1`.
- Respeto por `prefers-reduced-motion` para personas que reducen animaciones.

## Tecnologías

- HTML5 semántico.
- CSS3 Mobile First, Grid, Flexbox y media queries.
- Bootstrap 5.3.8 mediante CDN.
- JSON-LD, Open Graph, `robots.txt` y sitemap XML.
- Git y GitHub.

Para recorrer el proyecto en forma local, abrí `index.html` con conexión a internet para cargar Bootstrap y Google Fonts.
