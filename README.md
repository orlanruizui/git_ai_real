# README.md

## Proyecto Reveal.js

Reveal.js es un marco de presentaciones HTML que utiliza una arquitectura modular para permitir la creación de presentaciones interactivas y visualmente atractivas. 

### Arquitectura

Reveal.js está construido en JavaScript y CSS, utilizando tecnologías modernas para garantizar un rendimiento y experiencia de usuario optimales. La estructura del proyecto se organiza en diversos directorios que contienen:

- `dist`: donde se encuentran los archivos compilados de JavaScript y CSS.
- `css`: contiene las hojas de estilo Sass y CSS para personalizar el diseño de la presentación.
- `plugin`: contiene los complementos adicionales que extienden las funcionalidades de Reveal.js, como la sintaxis de Markdown, notas de orador y zoom.
- `js`: contiene el código fuente principal de la biblioteca.
- `examples`: ejemplos de uso y características de la biblioteca para probar y entender mejor su funcionamiento.

### Instalación

Para instalar Reveal.js, se necesita tener instalado Node.js y npm. Luego, puedes seguir estos pasos:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/hakimel/reveal.js.git
   cd reveal.js
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Compila el proyecto:
   ```bash
   npm run build
   ```

4. Inicia un servidor de desarrollo para ver la presentación en acción:
   ```bash
   npm run serve
   ```

Ahora deberías poder acceder a la presentación en `http://localhost:8000`.

### Uso

Una vez instalado, puedes crear tu presentación utilizando archivos HTML. A continuación, se muestra un ejemplo básico para iniciar tu presentación:

```html
<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">

    <title>Mi Presentación</title>

    <link rel="stylesheet" href="dist/reset.css">
    <link rel="stylesheet" href="dist/reveal.css">
    <link rel="stylesheet" href="dist/theme/black.css">

</head>
<body>
    <div class="reveal">
        <div class="slides">
            <section>Bienvenido a mi presentación</section>
            <section>
                <h2>Titulo</h2>
                <p>Esto es un ejemplo de un slide con contenido.</p>
            </section>
        </div>
    </div>

    <script src="dist/reveal.js"></script>
    <script>
        Reveal.initialize({
            hash: true,
            controls: true,
            progress: true,
            dependencies: [
                { src: 'plugin/markdown/markdown.js' },
                { src: 'plugin/highlight/highlight.js', async: true },
                { src: 'plugin/notes/notes.js', async: true }
            ]
        });
    </script>
</body>
</html>
```

### Personalización

Para personalizar los estilos de tu presentación, puedes crear temas utilizando Sass. Simplemente duplica uno de los archivos SCSS en la carpeta `css/theme/source`, modifícalo según tus necesidades y luego compílalo utilizando:

```bash
npm run build -- css-themes
```

### Contribuciones

Las contribuciones son bienvenidas. Si deseas agregar características, corregir errores o mejorar la documentación, siéntete libre de realizar un fork del proyecto y enviar tus pull requests.

Para más información sobre las características, documentación completa y guías de uso, visita el sitio oficial: [revealjs.com](https://revealjs.com).