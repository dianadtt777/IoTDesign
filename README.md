# ⋆.˚🛜 Reto IoT · UX ↔ Sistema ໑ ݁༝ ۫ ׅ 

Presentación web interactiva sobre el diseño UX y la arquitectura de sistemas para un proyecto de Internet de las Cosas (IoT) enfocado en el monitoreo ambiental (temperatura, humedad y amoniaco) y control en granjas de grillos.



##  Estructura del proyecto (`IoT`)

* `index.html` — Presentación web interactiva con estilos CSS, animaciones, tarjetas giratorias (*flip*), carrusel, sobre interactivo (*envelope*) y videos por sección.
* **Tipografía:**
  * `AlteHaasGroteskBold.ttf` y `AlteHaasGroteskRegular...` — Fuente principal de títulos.
  * `Alte Haas Grotesk licenc...` — Licencia de la tipografía.
* **Imágenes y recursos gráficos:**
  * `portada.jpg` — Fondo de la diapositiva de portada.
  * `Gabriel.avif`, `MapaEmpatia.png`, `persona.png` — Recursos del carrusel de usuario/contexto y evidencia del sistema.
  * `dash.jpg` — Captura/evidencia del dashboard de control.
  * `papel.png`, `wireframe.png` — Prototipado ágil y evolución de interfaz.
  * `diagrama.png` — Diagrama técnico del sistema (revisar que coincida con el nombre referenciado en `index.html`, por ejemplo `diagrama-memoria.png` o `diagrama.png`).
  * `Tux.webp` — Recurso visual para la sección de sistema operativo / abstracción Linux.
  * `capa.jpg` — Recurso gráfico adicional del proyecto.
* **Videos:**
  * `arqui.mp4` — Animación/video para el flujo de Entrada/Salida (`#es`).
  * `riegos.mp4` — Video para la sección `#riesgos`.
  * `apre.mp4` — Video para la sección de cierre (`#cierre`).

## Publicación en GitHub Pages

1. Asegúrate de que `index.html` y todos los archivos multimedia/fuentes referenciados estén en la raíz del repositorio `IoTDesign` (rama `main`).
2. Verifica que los nombres de archivo en `index.html` coincidan **exactamente** (incluyendo mayúsculas y minúsculas) con los archivos subidos, ya que GitHub Pages distingue entre mayúsculas y minúsculas.
3. En **Settings → Pages**, confirma que el despliegue esté configurado desde `Deploy from a branch` (`main` / `/ (root)`).
4. Accede a la URL del sitio:
   `https://dianadtt777.github.io/IoTDesign/`

## Notas de mantenimiento
* Si alguna imagen o video no carga tras publicar, revisa el nombre exacto en el código (`diagrama.png` vs. `diagrama-memoria.png`, o `riegos.mp4` vs. `riesgos.mp4`) y confirma que el repositorio sea público o cuente con soporte de GitHub Pages habilitado.