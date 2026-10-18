# Hoja de vida web · Johan Cepeda

Sitio personal responsive que reúne mi hoja de vida, una página de contacto y la presentación del proyecto académico Help Me Tenerife. Su objetivo es mostrar mi perfil, experiencia, formación y trabajo web en una navegación sencilla.

**Sitio publicado:** pendiente. Al revisar el repositorio, GitHub Pages no aparece habilitado; por eso todavía no hay una dirección pública que pueda confirmar. Este enlace debe completarse antes de la entrega final.

**Repositorio público:** [JohanCepeda92/Hoja_de_vida_Web_CepedaJohan](https://github.com/JohanCepeda92/Hoja_de_vida_Web_CepedaJohan) · Repositorio comprobado como público el 18 de octubre de 2026.

## Páginas

- [Hoja de vida — `index.html`](index.html)
- [Contacto — `contacto.html`](contacto.html)
- [Proyecto Help Me Tenerife — `help-me.html`](help-me.html)

## Mockups

Los siguientes PNG son diseños esquemáticos previos de las páginas. Representan su estructura con bloques grises, líneas y marcadores; no son capturas del sitio terminado.

### Hoja de vida

**Escritorio**

![Mockup esquemático de la hoja de vida en escritorio](mockups/inicio-computador.png)

**Celular**

![Mockup esquemático de la hoja de vida en celular](mockups/inicio-celular.png)

### Contacto

**Escritorio**

![Mockup esquemático de la página de contacto en escritorio](mockups/contacto-computador.png)

**Celular**

![Mockup esquemático de la página de contacto en celular](mockups/contacto-celular.png)

### Help Me Tenerife

**Escritorio**

![Mockup esquemático de Help Me Tenerife en escritorio](mockups/help-me-computador.png)

**Celular**

![Mockup esquemático de Help Me Tenerife en celular](mockups/help-me-celular.png)

## Capturas del sitio publicado

**Pendiente de completar.** No existe una carpeta `capturas/` ni hay capturas reales del sitio publicado en el proyecto. Antes de la entrega se deben añadir, como mínimo:

- Una captura del sitio publicado en computador.
- Una captura del sitio publicado en celular; al menos una de las capturas requeridas debe obtenerse desde un dispositivo físico.

Cuando estén disponibles, se deben incluir aquí con enlaces Markdown a sus archivos locales. Los mockups de la sección anterior no sustituyen estas capturas.

## Breakpoints

El CSS usa un enfoque mobile first: los estilos base se aplican desde pantallas estrechas y las media queries amplían la distribución en anchos mayores.

- **Ancho base (menos de 600 px):** la hoja de vida usa una columna y apila cabecera, navegación, perfil, contenido, barra lateral y pie. Contacto apila la presentación y las tarjetas. Los servicios de Help Me aparecen en una columna.
- **Desde 600 px:** la navegación de la hoja de vida se alinea a la izquierda y su pie pasa a una disposición horizontal. El contenido y la barra lateral pueden formar más columnas según el espacio disponible. Contacto coloca presentación y fotografía en dos columnas, y sus tarjetas lado a lado. Help Me distribuye los servicios en dos columnas.
- **Desde 801 px:** la cabecera de Help Me coloca el logotipo y la navegación en una fila.
- **Desde 1024 px:** la hoja de vida distribuye el contenido principal y la barra lateral en dos columnas. Help Me presenta sus tarjetas de servicios en tres columnas y fija su cabecera en la parte superior.

## Cómo lo publiqué

1. **Repositorio:** existe un repositorio público de GitHub en la rama `main`. Su URL y visibilidad se comprobaron; la copia local también tiene este repositorio configurado como remoto.
2. **Archivos:** la versión revisada contiene cambios locales aún sin subir. En el repositorio remoto consultado todavía no constan las páginas `contacto.html` y `help-me.html` ni este README.
3. **GitHub Pages:** la publicación no está configurada. La API de GitHub indica que Pages está desactivado (`has_pages: false`), así que no se puede confirmar una URL publicada ni pruebas sobre ella.
4. **Pendiente:** subir la versión final del proyecto al repositorio. Después, configurar Pages desde **Settings → Pages**, seleccionando **Deploy from a branch**, la rama `main` y la carpeta raíz (`/(root)`, si esa será la ubicación de los archivos), y guardar.
5. **Verificación final:** cuando GitHub Pages complete la publicación, abrir la URL que muestre la sección **Settings → Pages**, comprobar las páginas en computador y celular, y actualizar el enlace de “Sitio publicado” y las capturas de esta documentación.

La selección de rama y carpeta descrita arriba es el paso recomendado para publicar desde una rama; no se presenta como una configuración que ya se haya realizado.

## Fuentes consultadas

### Archivos del proyecto

- `index.html`, `contacto.html` y `help-me.html`: estructura y contenido de las páginas.
- `styles.css`: estilos y breakpoints implementados.
- Carpeta `mockups/`: nombres y rutas de los seis diseños esquemáticos.
- Repositorio público enlazado arriba: comprobación de visibilidad, rama principal y estado de GitHub Pages.

### Documentación externa

- [GitHub Docs: configurar una fuente de publicación para GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) — consultada para describir los pasos de publicación que siguen pendientes.

### Herramientas y tecnologías

- HTML5 y CSS3 para las páginas.
- Git y GitHub para el repositorio.
- GitHub Pages está previsto como plataforma de publicación, pero todavía no está configurado.