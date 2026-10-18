# Museo del Conocimiento

**Cuando el conocimiento aprendió a viajar**: museo web interactivo sobre tres hitos de la educación digital.

## Abrir en tu computadora

Abre `index.html` con Chrome, Edge o Firefox. No necesitas instalar nada. Los cuadros del museo son archivos SVG locales en `assets/`; la fuente tipográfica usa Google Fonts y, si no hay internet, aparece una alternativa local.

## Publicar en GitHub y Render

1. Crea un repositorio nuevo en GitHub (por ejemplo `museo-del-conocimiento`).
2. Sube **el contenido de esta carpeta** (`index.html`, `styles.css`, `script.js`, `assets/`, `render.yaml`, `README.md`). Puedes hacerlo en **Add file → Upload files**. Asegúrate de que `index.html` quede en la raíz del repositorio.
3. En [Render](https://render.com/) entra a **New → Static Site** y conecta ese repositorio.
4. Configura **Build Command**: `echo 'Sitio listo'` y **Publish Directory**: `.`. Si Render reconoce `render.yaml`, también puedes usar **New → Blueprint**.
5. Pulsa **Deploy**. Render entregará una URL pública `https://...onrender.com` que puedes publicar en el foro o convertir en código QR.

**No selecciones Web Service:** esta es una web estática, no necesita un servidor Node o Python.

## Personalizar

- Textos de las salas y sus fechas: `index.html`.
- Preguntas, respuestas y referencias emergentes: `script.js`.
- Colores, tamaños, iluminación, cuadros y diseño móvil: `styles.css`.
- Pinturas: `assets/*.svg` (ilustraciones originales en SVG).

## Contenido académico

La exposición interpreta tres momentos (correspondencia, LMS y aprendizaje móvil) y establece vinculaciones **analíticas** con marcos teóricos. La correspondencia es anterior al conductismo formal, por lo que no se afirma que este enfoque haya causado ese hito. La lectura asignada de López Benito y Santacana Mestre (coords., 2014, pp. 48-61) se empleó sobre todo para la reflexión crítica sobre revolución digital y m-learning. Los antecedentes históricos se complementan con las fuentes enlazadas en el botón **Fuentes**.

## Créditos

Museo interactivo diseñado para una actividad académica. Ilustraciones SVG originales incluidas. Código HTML, CSS y JS sin dependencias de ejecución externas.
