# Web Studio · Editor Master

Un editor visual de **un solo archivo HTML** para montar tu propia web y tu página de enlaces (tipo "link in bio") sin tocar código. Lo abres en el navegador, lo editas, y descargas el HTML ya hecho.

No necesita instalar nada, ni servidor, ni cuenta. Funciona en local.

## Qué puedes hacer

- Editar textos, imágenes, enlaces, secciones y colores.
- Trabajar dos páginas desde el mismo editor: la **web principal** y la página de **enlaces**.
- Ver el resultado en la **vista previa** mientras editas.
- **Deshacer / rehacer** cambios (Ctrl/Cmd + Z).
- Elegir el idioma de la página y el de los textos que editas.
- **Importar** un proyecto `.json` (o un HTML que ya generaste) y **exportarlo** para guardarlo o compartirlo.
- **Restaurar** una página (o todo) al ejemplo original.
- Descargar los HTML generados, o guardarlos directamente en una carpeta (en navegadores basados en Chromium).
- Opciones para añadir analítica (Google Analytics, Plausible, Umami, Cloudflare) y un formulario de contacto con [Formspree](https://formspree.io).

## Cómo usarlo

1. Descarga **`editor-master.html`** (botón *Download raw file* en GitHub, o clona el repo).
2. Ábrelo con doble clic en un navegador moderno (Chrome, Edge, Firefox o Safari).
3. Empieza desde el proyecto de ejemplo o importa uno tuyo (`.json`).
4. Cambia los textos, imágenes y enlaces por los tuyos y revisa la vista previa.
5. Descarga los HTML generados.

El editor guarda tu trabajo en el propio navegador, pero **ese guardado es local y puede borrarse**. Exporta el proyecto `.json` de vez en cuando como copia de seguridad.

## Cómo publicar tu web

Los archivos que descargas son HTML estáticos, así que sirven en cualquier hosting estático. Con GitHub Pages:

1. Crea un repositorio nuevo y sube el HTML generado. La página principal debe llamarse `index.html`.
2. Ve a **Settings → Pages**.
3. En *Source* elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En un par de minutos tendrás tu web en `https://TU-USUARIO.github.io/TU-REPO/`.

Si más adelante quieres un dominio propio, se configura también desde **Settings → Pages**.

## Notas

- Todo ocurre en tu navegador: el editor no envía tus datos a ningún servidor.
- Si pones analítica o un formulario, esos servicios sí recibirán datos de tus visitantes, así que usa tus propios identificadores.
- Es un proyecto personal que comparto tal cual. Si te sirve, deja una ⭐.

Hecho por [PrintsNCode](https://github.com/PrintsNCode).
