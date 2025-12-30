# Documento Detallado de Diseño (DDD) - Trabajo Práctico: Fundamentos de la Ingeniería Informática

## Descripción del Trabajo

Este proyecto consiste en el desarrollo de un sitio web estático para el trabajo práctico de la asignatura "Fundamentos de la Ingeniería Informática". El sitio web tiene como objetivo proporcionar una plataforma informativa y organizada que reúna diversas secciones.

### Propósito y Alcance
- **Propósito**: Crear un sitio web accesible que sirva como índice y repositorio de información para el trabajo práctico, facilitando la navegación y presentación de contenidos académicos.
- **Alcance**: El sitio incluye páginas principales como Inicio, Acerca de mí, Grado, Tema (Blockchain), Red de compañeros, Contacto y una página dedicada a FII (Fundamentos de la Ingeniería Informática).

### Tecnologías Utilizadas
- **HTML5**: Para la estructura semántica de las páginas.
- **CSS3**: Para el diseño, layout responsivo y estilos visuales, incluyendo flexbox y grid para la disposición de elementos.
- **Estructura del Proyecto**:
  - `index.html`: Página principal con navegación y viñetas informativas.
  - `css/styles.css`: Hoja de estilos centralizada.
  - `public/`: Carpeta con páginas secundarias (about.html, degree.html, etc.).
  - `images/`: Carpeta para imágenes (fotos personales, etc.).

### Diseño y Arquitectura
- **Diseño Visual**: Utiliza una paleta de colores azul marino y blanco para un aspecto profesional. Incluye franjas de navegación, viñetas rectangulares con esquinas redondeadas para agrupar contenido, y un layout centrado.
- **Navegación**: Barra de navegación horizontal en la parte superior de cada página, con enlaces a secciones clave.
- **Componentes Clave**:
  - Viñetas grandes (big-card) para agrupar secciones enteras.
  - Viñetas pequeñas (small-card) para contenidos específicos.
  - Formularios en la página de contacto (sin backend, solo interfaz).
- **Responsividad**: Adaptable a dispositivos móviles mediante media queries.

## Problemas Durante el Desarrollo

Durante el desarrollo del proyecto, se enfrentaron varios desafíos técnicos y de diseño que requirieron iteraciones y ajustes:

- **Organización del Contenido**: Inicialmente, el contenido estaba disperso en secciones sin una jerarquía clara. Se resolvió reorganizando en viñetas grandes y pequeñas, lo que mejoró la legibilidad y navegación.
- **Diseño Responsivo**: Asegurar que las viñetas y la navegación se adaptaran a pantallas pequeñas fue complicado, especialmente con el grid de viñetas pequeñas. Se utilizaron flexbox y media queries para lograr consistencia.
- **Integración de CSS**: Al centralizar estilos en un solo archivo, surgieron conflictos de especificidad. Se resolvió mediante una revisión de selectores y el uso de clases específicas.
- **Gestión de Imágenes**: Las rutas de imágenes locales causaron problemas de carga. Se corrigieron ajustando las rutas relativas y verificando la estructura de carpetas.
- **Consistencia en Navegación**: Mantener la barra de navegación idéntica en todas las páginas requirió copiar y pegar código, lo que podría mejorarse con un sistema de plantillas en un entorno más avanzado.
- **Validación y Compatibilidad**: Asegurar compatibilidad con navegadores modernos y validar HTML/CSS fue un proceso iterativo, resolviéndose mediante pruebas en diferentes entornos.

## Conclusiones

Este proyecto ha demostrado la importancia de una planificación cuidadosa en el diseño web, desde la estructura de contenido hasta la implementación técnica. Se logró crear un sitio web funcional, accesible y visualmente coherente que cumple con los requisitos del trabajo práctico ademas se comprendió la complejidad que el desarrollo de webs conlleva.

### Aprendizajes Clave
- **HTML y CSS**: Dominio de semántica HTML y técnicas de CSS avanzadas como flexbox y grid.
- **Diseño UX/UI**: La importancia de la jerarquía visual y la navegación para mejorar la experiencia del usuario.
- **Resolución de Problemas**: La iteración y el testing continuo son esenciales para superar desafíos en desarrollo web.

### Mejoras Futuras
- Implementar un sistema de gestión de contenido (CMS) o un framework como React para mayor dinamismo.
- Agregar JavaScript para funcionalidades interactivas, como validación de formularios o animaciones.


Este DDD resume el proceso de diseño y desarrollo, destacando tanto los logros como las lecciones aprendidas.
