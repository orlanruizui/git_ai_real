# reveal.js

## Descripción

reveal.js es un framework de presentaciones HTML que permite crear presentaciones interactivas y modernas utilizando tecnologías web estándar. Este proyecto es ampliamente utilizado para realizar presentaciones en línea y permite la inclusión de elementos multimedia y estilos personalizados.

## Arquitectura

La arquitectura de reveal.js consiste en una serie de archivos HTML, CSS y JavaScript que trabajan juntos para proporcionar una experiencia de presentación fluida. Los componentes principales incluyen:

- **HTML**: El archivo HTML básico que define la estructura de la presentación, incluyendo las secciones (slides) que forman las diferentes diapositivas.
- **CSS**: Archivos de estilo que definen la apariencia visual de las presentaciones. Esto incluye reset de CSS y temas predefinidos.
- **JavaScript**: El archivo principal `reveal.js` donde se manejan las funcionalidades del framework, incluyendo la navegación entre diapositivas y la integración de plugins.
- **Plugins**: reveal.js permite la integración de varios plugins, como Markdown para el formateo de texto y Highlight.js para la sintaxis destacada del código.

## Instalación

Para instalar reveal.js, sigue estos pasos:

1. **Clone el repositorio**: Usa Git para clonar el repositorio en tu máquina local.
   ```
   git clone git://github.com/hakimel/reveal.js.git
   ```

2. **Instalar dependencias**: Navega al directorio del proyecto y ejecuta el siguiente comando para instalar las dependencias necesarias. Asegúrate de tener Node.js instalado (versión 18.0.0 o superior).
   ```
   npm install
   ```

3. **Ejecutar el servidor de desarrollo**: Para iniciar un servidor de desarrollo y ver tu presentación en el navegador, utiliza el siguiente comando:
   ```
   npm start
   ```

4. **Construir el proyecto**: Si deseas crear una versión de producción, utiliza el siguiente comando para construir los archivos optimizados.
   ```
   npm run build
   ```

## Uso

Una vez que hayas instalado y configurado reveal.js, puedes comenzar a crear tu presentación siguiendo estos pasos:

1. **Crear una nueva presentación**: Abre el archivo HTML proporcionado en el proyecto y agrega tus diapositivas dentro del contenedor `<div class="slides">`. Cada `<section>` representa una nueva diapositiva.
   ```html
   <div class="slides">
       <section>Mi primera diapositiva</section>
       <section>Mi segunda diapositiva</section>
   </div>
   ```

2. **Configurar la presentación**: Puedes personalizar la configuración de reveal.js utilizando el método `Reveal.initialize()`, donde puedes definir opciones como la navegación por hash y los plugins a utilizar.
   ```javascript
   Reveal.initialize({
       hash: true,
       plugins: [ RevealMarkdown, RevealHighlight, RevealNotes ]
   });
   ```

3. **Visualizar tu presentación**: Abre el navegador y accede a `http://localhost:8000` (o donde hayas alojado tu servidor) para ver tu presentación en acción.

## Contribuciones

Si deseas contribuir a este proyecto, por favor, revisa la sección de contribuciones en el repositorio. Esta comunidad es abierta y siempre está buscando mejoras, errores y nuevas características.

## Licencia

reveal.js se distribuye bajo la licencia MIT, lo que significa que puedes usar, copiar y modificar el código. Consulta el archivo `LICENSE` para detalles adicionales.

## Autor

Este proyecto fue creado por Hakim El Hattab. Para más información o preguntas, puedes contactarlo en [hakim.elhattab@gmail.com](mailto:hakim.elhattab@gmail.com) o visitar su [sitio web](https://hakim.se).