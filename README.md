# Pulso Club Fitness · muestra para GitHub Pages

Landing estática en español argentino, versión 3. HTML, CSS y JavaScript nativos; todo el diseño y el guion del chat están en `index.html`. No requiere npm, compilación, servidor de aplicaciones, claves ni servicios pagos.

## Cambios de esta versión

- Logo PNG con transparencia real, sin el fondo negro. Incorporado a la cabecera, al pie y al icono del sitio.

- Eliminadas las leyendas sobre las fotos, “Sin filtro. Con toda la energía.” y otros rótulos de presentación.
- Cinta de actividades en movimiento continuo con guiones simples y sin estrellas.
- Entradas suaves de secciones, pulso animado y transiciones de portada. El movimiento respeta la preferencia de movimiento reducido y se pausa fuera de pantalla.
- Foto de comunidad original a 4096 × 2731; fachada, musculación y salsa retocadas con ImageGen a 941 × 1672. Las imágenes anteriores de estos tres casos eran miniaturas de 360 × 640. Los detalles de la edición están en `IMAGENES.md`.

## Abrir la muestra

Abrí `index.html` en un navegador. Las imágenes y tipografías están incluidas en `assets/`, por lo que el diseño y la animación funcionan sin Internet. Los enlaces a Instagram, WhatsApp y Maps sí requieren conexión.

## Publicar en GitHub Pages

1. Descomprimí el ZIP.
2. Subí **el contenido** a la raíz de tu repositorio: `index.html`, la carpeta `assets`, `.nojekyll` y los archivos de documentación. No subas el ZIP como único archivo ni agregues una carpeta contenedora encima de `index.html`.
3. En GitHub, abrí **Settings → Pages**.
4. En **Build and deployment**, elegí **Deploy from a branch**.
5. Seleccioná la rama donde subiste los archivos (normalmente `main`) y **/(root)**. Guardá.
6. Cuando termine la publicación, GitHub mostrará el enlace. Para un repositorio de proyecto tendrá el formato `https://TU-USUARIO.github.io/TU-REPOSITORIO/`.

Las rutas son relativas y funcionan tanto en un sitio de usuario como dentro de un repositorio de proyecto. No se configuró un dominio propio ni se publicó automáticamente.

Referencia: [configurar la fuente de publicación en GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Chat de muestra

- Conversaciones preescritas en español, con mensajes progresivos, doble tilde, horarios y estado “Escribiendo…”.
- Dos conversaciones de aproximadamente 29 segundos cada una, en bucle.
- Solo reproducción: no contiene input, formulario, botón de enviar ni respuestas interactivas.
- No usa IA real ni llama a APIs. No recopila ni almacena datos.
- Se pausa al salir de pantalla o cambiar de pestaña y continúa al volver.
- Respeta “reducir movimiento”: muestra una conversación estática si el sistema tiene esa preferencia.
- El guion está en `conversations`, al final de `index.html`.

## Contenido y marca

Logo basado en el adjunto del usuario, con el fondo negro retirado mediante ImageGen. Paleta negra, blanca y amarillo dorado (`#ffbd46`). Imágenes basadas en las publicaciones públicas del gimnasio, guardadas localmente para evitar enlaces de Instagram que vencen. La procedencia y los retoques se detallan en `FUENTES.md` e `IMAGENES.md`.

Se verificaron en la biografía pública: Av. Patria 235; WhatsApp +54 9 3512 11-1154; diez actividades. No se inventaron precios, reseñas, descuentos ni horarios. Los botones de contacto abren los canales reales; no envían mensajes automáticamente.

La muestra lleva `noindex, nofollow`. Al convertirla en sitio oficial, revisá los datos con el gimnasio y quitá esa metaetiqueta si corresponde. El chat sigue identificado como simulación.

## Edición rápida

- Colores: variables al comienzo de `<style>`.
- Textos y secciones: HTML de `index.html`.
- Contacto: buscá `5493512111154`, `Av. Patria 235` y el enlace a Maps.
- Fotos: reemplazá los archivos conservando sus nombres, o actualizá los `src`.
- Fuentes Barlow y Barlow Condensed: licencias OFL incluidas en `assets/fonts`.

La carpeta es autónoma y no modifica los otros proyectos del espacio de trabajo.
