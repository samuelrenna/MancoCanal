# MancoCanal - Proyecto Web

Este repositorio contiene el código fuente del sitio web oficial para la comunidad de streaming "MancoSam". El proyecto ha sido desarrollado utilizando HTML5,
 SASS y Bootstrap, enfocado en brindar una experiencia responsiva y dinámica para los seguidores del canal.

## Descripción del Proyecto
El sitio web sirve como punto de encuentro para la comunidad, permitiendo a los usuarios:
- Conocer el perfil del streamer.
- Explorar una colección de videojuegos recomendados.
- Leer reseñas y opiniones sobre diversos títulos.
- Contactar o enviar recomendaciones a través de un formulario.
- Acceder directamente a las redes sociales (Twitch, TikTok).

## 🚀 Tecnologías Utilizadas

### Core
* HTML5: Estructura semántica.
* CSS3: Estilos en cascada.
* SASS (SCSS): Preprocesador CSS para modularización y funciones avanzadas.

### Librerías y Frameworks
* Bootstrap 5.3.1: Framework para el sistema de rejilla (grid), componentes (navbar, cards, forms) y responsividad.
* AOS (Animate On Scroll): Librería para animaciones al hacer scroll.
* Bootstrap Icons: Iconografía vectorial para redes sociales y elementos de UI.
* Google Fonts: Tipografía 'Roboto'.

## Estructura del Repositorio

El proyecto sigue una arquitectura organizada separando vistas, estilos y recursos:

```text
/
├── index.html            # Página de inicio (Home)
├── package.json          # Configuración del proyecto y dependencias
├── /css
│   ├── style.css         # Hoja de estilos final compilada
│   └── style.css.map     # Mapa de estilos para depuración
├── /img                  # Imágenes optimizadas en formato .webp
├── /page                 # Páginas internas del sitio
│   ├── coleccion.html    # Catálogo de juegos
│   ├── contacto.html     # Formulario de contacto
│   ├── perfil.html       # Biografía del autor
│   └── resena.html       # Sección de reseñas con videos
└── /scss                 # Código fuente SASS modularizado
    ├── style.scss        # Archivo principal (importador)
    ├── _variables.scss   # Variables globales (colores, fuentes, mixins)
    ├── _global.scss      # Estilos bases y resets
    ├── _home.scss        # Estilos específicos del home
    ├── _cards.scss       # Estilos para las tarjetas de juegos
    └── _contacto.scss    # Estilos del formulario.
```
## Características de SASS Implementadas
Se utilizó SASS para mantener un código limpio y escalable:
* Variables: Paleta de colores (#A3BAC3, #253237, #B20D30, etc.) y breakpoints.
* Mixins: Para flexbox (`@mixin centro`, `@mixin flex-columna`).
* Operaciones: Cálculo dinámico de márgenes y fuentes.
* Nesting: Anidación de selectores CSS.

## :earth_americas: Deploy del sitio web
[Visitar sitio Web MancoCanal](https://manco-canal.vercel.app/)

## 🔧 Instrucciones de Instalación

1. Clonar el repositorio:
   git clone <https://github.com/samuelrenna/MancoCanal.git>

2. Instalar dependencias (si aplica para futuras herramientas):
   npm install

3. Compilar SASS (requiere tener SASS instalado):
   sass --watch scss/style.scss css/style.css

## Autor
* Samuel Renna - Desarrollador Web.

---
© 2023 MancoCanal, Este proyecto fue realizado con fines educativos como parte del curso de Desarrollo Web de CoderHouse.
