# front_PFO1_Landing

# PFO1: Landing de Portafolio Personal

**Autor:** Miguel Martinez Colombos
**Materia:** Desarrollo de Sistemas Web / Front End (IFTS 29)
**Instancia:** PFO1

## Descripción del Proyecto
Este proyecto es una landing page personal diseñada para presentar mi perfil como Diseñador de Proyectos. El portafolio está estructurado para exhibir trabajos en tres áreas principales: Proyectos con Arduino & ESP32 (incluyendo programación y simulaciones en Tinkercad), Robótica y Automatización, y Servicios de Impresión 3D. Está completamente desarrollada con HTML semántico y CSS puro; no se utilizaron frameworks o JavaScript.

## Enlaces
* **Despliegue en vivo (Vercel):** https://front-pfo-1-landing.vercel.app
* **Perfil de GitHub:** https://github.com/mpmarcol/front_PFO1_Landing

## Decisiones de Diseño y Arquitectura Técnica

Para cumplir con los requisitos de la consigna y lograr una estética profesional, tomé las siguientes decisiones:

1. **Diseño Visual (Estilo Editorial):**
   * Opté por un diseño limpio y minimalista, inspirado en maquetaciones editoriales, priorizando el espacio en blanco para que las fotografías de los componentes físicos destaquen.
   * Utilicé una paleta de colores contenida: un fondo *off-white* (`#FAFAFA`) para reducir la fatiga visual frente al blanco puro, texto en gris oscuro (`#333333`) y acentos en tono dorado (`#D4AF37`) exclusivamente en el `<header>` y `<footer>` para enmarcar el contenido.
   * Seleccioné dos familias tipográficas a través de Google Fonts: una fuente Serif (Playfair Display) para aportar jerarquía y elegancia a los títulos, y una Sans-Serif (Montserrat) para garantizar la legibilidad en los párrafos descriptivos.

2. **Estructura HTML Semántica:**
   * El documento prescinde del uso excesivo de `<div>`. Se implementaron etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) para dar significado lógico a cada bloque, mejorando la accesibilidad y el SEO.

3. **Maquetación con Flexbox y CSS Grid:**
   * **Flexbox:** Se aplicó en el `<header>` y el `<footer>` para controlar la alineación horizontal de la navegación y la distribución del espacio entre el logo y los enlaces.
   * **CSS Grid:** Fue la tecnología elegida para construir las galerías de imágenes dentro de las secciones de proyectos. Permitió crear un sistema de cuadrícula responsivo (`grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`) que adapta automáticamente la cantidad de columnas según el tamaño de la pantalla, manteniendo la uniformidad visual sin requerir complejas *media queries*.

4. **Interactividad:**
   * Se incorporaron transiciones CSS (`transition`) en los enlaces de navegación y en las tarjetas de la galería (efecto *scale* en *hover*) para brindar retroalimentación visual al usuario.

## Declaración de Uso de Inteligencia Artificial

Para la realización de este proyecto, he utilizado herramientas de Inteligencia Artificial Generativa como asistencia técnica y creativa, cumpliendo con los requisitos de transparencia de la materia.

* **Herramienta(s) utilizada(s):** Gemini
* **Plan:** PRO Estudiantil
* **Experiencia previa:** Tengo experiencia previa formulando prompts detallados para generación de contenido multimedia y lógica de programación. Sólo se ha utilizado para detalles específicos de maquetación y adornos visuales.
* **Uso y adaptación con criterio propio:**
  * **Estructura:** En determinados elementos consulte a la IA para verificar que mi idea del esqueleto coincida con las buenas practicas. Hace años que aprendí HTML, pero por falta de tiempo preferí consultar esos detalles dinámicamente y no recurrir a MDN.
  * **CSS:** En determinados momentos de inconvenientes, consulté aspectos y usos para decidir entre el uso de Flexbox y CSS Grid.
  * **Criterio propio:** No realicé copias automáticas de código. Me cercioré que el uso en las áreas de especialidad (Arduino, Robótica, Impresión 3D) coincidan con el formato que utilicé. Ajusté manualmente los parámetros de la grilla, los márgenes (`padding`) de las secciones editoriales y la paleta de colores para lograr la estética que buscaba proyectar.
  * **ReadME:** En base a una estructura inicial del documento, solicité ayuda para generar este documento de la forma en que sea más útil a los usos actuales.