

--- Nuevo Cambio ---
Update to version 5.2.1, featuring enhancements to the lightbox functionality, improved media previews, and various optimizations for responsiveness and accessibility.

--- Nuevo Cambio ---
### CHANGELOG.md

#### [5.2.1] - 2023-10-01

- Se ha añadido una nueva funcionalidad de visualización tipo "lightbox" que permite a los usuarios interactuar con imágenes, vídeos y enlaces directamente desde una presentación, mejorando la experiencia visual. La inclusión de atributos `data-preview-image`, `data-preview-video` y `data-preview-link` facilita la integración de estos elementos, permitiendo que se muestren en una ventana emergente cuando son seleccionados. Adicionalmente, se han actualizado las referencias a recursos externos para mejorar la fiabilidad y el rendimiento, como el cambio en las URLs de los vídeos de fondo y otros elementos gráficos. Asimismo, se realizó una optimización en el control de solapamientos (overlays) que ahora gestionan la apertura y cierre de manera más efectiva con el uso de nuevas funciones específicas en el código, tales como `previewIframe`, `previewImage`, y `previewVideo`. Estas mejoras no solo enriquecen las funcionalidades actuales de `reveal.js`, sino que también refuerzan la estabilidad y el rendimiento del marco en general, facilitando a los presentadores la creación de experiencias más atractivas.