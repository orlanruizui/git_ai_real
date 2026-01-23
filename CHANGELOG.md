

--- Nuevo Cambio ---
Update to version 5.2.1, featuring enhancements to the lightbox functionality, improved media previews, and various optimizations for responsiveness and accessibility.

--- Nuevo Cambio ---
### CHANGELOG.md

#### [5.2.1] - 2023-10-01

- Se ha añadido una nueva funcionalidad de visualización tipo "lightbox" que permite a los usuarios interactuar con imágenes, vídeos y enlaces directamente desde una presentación, mejorando la experiencia visual. La inclusión de atributos `data-preview-image`, `data-preview-video` y `data-preview-link` facilita la integración de estos elementos, permitiendo que se muestren en una ventana emergente cuando son seleccionados. Adicionalmente, se han actualizado las referencias a recursos externos para mejorar la fiabilidad y el rendimiento, como el cambio en las URLs de los vídeos de fondo y otros elementos gráficos. Asimismo, se realizó una optimización en el control de solapamientos (overlays) que ahora gestionan la apertura y cierre de manera más efectiva con el uso de nuevas funciones específicas en el código, tales como `previewIframe`, `previewImage`, y `previewVideo`. Estas mejoras no solo enriquecen las funcionalidades actuales de `reveal.js`, sino que también refuerzan la estabilidad y el rendimiento del marco en general, facilitando a los presentadores la creación de experiencias más atractivas.

--- Nuevo Cambio ---
### [5.2.1] - 2023-10-25

#### Changed
- Updated the preview functionality by introducing a new lightbox feature, enhancing user experience with the capability to preview images and videos more interactively. This feature allows elements to use the `data-preview-image` and `data-preview-video` attributes to trigger a lightbox overlay. Users can now click on linked images or videos within their presentations to view them in a larger format without leaving the slide, thereby creating a seamless experience that maintains focus on the content. 
- The `README.md` file has been updated to reflect changes regarding the new `lightbox` feature, ensuring clarity and easier navigation for developers looking to implement or explore this functionality.
- Several links pointing to assets have been corrected, replacing outdated links with current URLs, thus ensuring all resources are accessible. 
- Minor adjustments to CSS styles related to viewport mechanics for smoother rendering on devices with smaller screens, ensuring better adaptability across devices.

This update enhances both functionality and user experience, making it easier for presenters to effectively utilize multimedia within their presentations, while also maintaining a clear and well-structured documentation resource.

--- Nuevo Cambio ---
```markdown
### [Actualización de 5.2.0 a 5.2.1] - 2026-01-23

**Descripción**  
En esta actualización se han realizado cambios significativos para mejorar la experiencia del usuario y la funcionalidad del sistema. Se ha corregido la URL de varios recursos en el archivo `README.md`, garantizando que los enlaces a imágenes y videos se dirijan a la ubicación correcta. Además, se han agregado nuevas características de "lightbox" en el sistema de presentación, permitiendo a los usuarios convertir elementos en una vista ampliada utilizando atributos como `data-preview-image` y `data-preview-video`. Estos cambios se realizaron para optimizar la visualización de contenido multimedia, mejorando la interactividad y la estética de las presentaciones para usuarios de dispositivos de pantalla más pequeña. También se realizaron ajustes en el CSS y JavaScript, como el cambio de z-index y adición de nuevas propiedades en el controlador de teclado, enfocándose en el manejo efectivo de la interfaz de usuario. El impacto para el usuario es notable, pues ahora podrán disfrutar de una visualización de contenido más rica y accesible.

**Archivos modificados**  
- `README.md`: Corregida la URL de la imagen para apuntar al nuevo origen.  
- `css/reveal.scss`: Ajustes de estilo responsivo para el encabezado del overlay en pantallas pequeñas.  
- `demo.html`: Se añadió nueva sección de "Lightbox" con ejemplos claros de uso y estructura de código.  
- `examples/lightbox.html`: Modificación del título para reflejar el nuevo enfoque en “Lightbox”. Se añadieron ejemplos de uso de enlaces de previsualización.  
- `js/controllers/keyboard.js`: Se añadieron nuevas funcionalidades para cerrar overlays mediante el teclado, mejorando la navegabilidad.  
- `js/controllers/overlay.js`: Se redefinieron métodos para manejar las nuevas funcionalidades de lightbox, adaptando la interfaz y mejorando la gestión del estado de los previews.

**Posibles mejoras futuras**  
- Implementar soporte para más tipos de medios en lightbox, como audio o contenido embebido.  
- Mejorar la experiencia de usuario añadiendo animaciones de transición al abrir y cerrar overlays.  
- Integrar nuevos temas visuales que se adapten a las preferencias del usuario para la visualización de presentaciones.  
- Optimizar aún más la interactividad respondiendo a gestos y acciones táctiles en dispositivos móviles.

**Posibles problemas o riesgos de la release**  
- Respuesta inesperada del overlay en navegadores antiguos que pueden no soportar algunas propiedades CSS nuevas.  
- Riesgos asociados a enlaces externos que pueden cambiar, lo que afectaría la funcionalidad de previsualización de enlaces.  
- Dependencias desactualizadas que podrían ocasionar errores de compatibilidad con las nuevas funcionalidades de lightbox.  
- Cualquier error en la implementación del sistema de lightbox podría causar problemas de visualización, afectando la usabilidad del sistema de presentación.

```