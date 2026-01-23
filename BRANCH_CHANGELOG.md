

--- Nuevo Merge ---
## Resumen
- Se ha cambiado el título de la presentación en `index.html` de "reveal.js" a "Axet Reveal Deck", mejorando la identificación del proyecto.
- Se han añadido nuevos elementos a las diapositivas, como encabezados y párrafos, para enriquecer el contenido y utilidad de la presentación.
- La inclusión de un "aside" con notas para el revisor permite facilitar el proceso de revisión y contextualización de cambios.
- Se ha añadido una tercera diapositiva, generando un cambio significativo en la estructura de la presentación.
- Los cambios implican una mejora en la claridad visual y funcionalidad del contenido de las diapositivas.

## Cambios detallados
- **UI**
  - `index.html`: 
    - Cambiado el título de la página.
    - Mejorada la estructura de las secciones de las diapositivas con encabezados (`<h2>`, `<h3>`) y párrafos (`<p>`).
    - Añadida una sección de notas para el revisor, con información de contexto sobre los cambios realizados.

## Riesgos / puntos de atención
- Asegurarse de que los cambios en la estructura HTML no afecten la presentación visual en diferentes dispositivos o navegadores.
- Verificar que las nuevas diapositivas y los encabezados no generen conflictos o errores en la funcionalidad de la presentación.
- Monitorizar el impacto en el rendimiento si se realizan cambios significativos en el contenido de las diapositivas mientras se prueba el flujo de revisión.

## Checklist para el revisor
- [ ] Revisar la nueva estructura y contenido en `index.html`.
- [ ] Verificar que el título de la presentación esté correctamente implementado.
- [ ] Confirmar que no haya errores de sintaxis HTML.
- [ ] Probar la presentación en diferentes navegadores para asegurar compatibilidad.
- [ ] Validar que las notas para el revisor sean claras y útiles.

## Tips para revisar más rápido
- Comienza revisando los cambios en la sección del título para entender el contexto del merge.
- Presta especial atención a la estructura de las nuevas diapositivas y a los elementos añadidos.
- Utiliza el comando `git diff` para visualizar los cambios en el contexto del archivo completo.
- Revisa la presentación previa a cambios y compárala haciendo uso de `git checkout <commit-anterior>`.
- Utiliza la funcionalidad de vista previa en el navegador para evaluar el diseño en tiempo real.
- Considera hacer pruebas en múltiples resoluciones de pantalla para asegurarte de que todo se visualice correctamente.
- Utiliza herramientas de desarrollo de navegadores para inspeccionar elementos y verificar que no haya problemas de estilo.
- Asegúrate de que el `aside` esté formatado correctamente y que cumpla su función informativa.

Estos pasos ayudarán a asegurar que los cambios realizados no solo sean funcionales sino también estéticamente agradables y útiles para los usuarios finales.