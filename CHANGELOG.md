

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