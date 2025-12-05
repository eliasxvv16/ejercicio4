# Práctica: Creación de un sitio Jekyll – *Fútbol Total*

## Introducción

En esta práctica se ha creado un nuevo sitio web estático utilizando **Jekyll** y **GitHub Pages**, con una temática relacionada con el **fútbol**.  
El objetivo es aprender a generar, personalizar y desplegar un blog estático usando las herramientas y comandos de Jekyll.

---

## 1. Creación del proyecto

**Comandos utilizados:**
```bash
mkdir myblog2
cd myblog2
jekyll new . --force
```
**Descripción:**
Se crea la estructura base del proyecto Jekyll dentro del directorio myblog2.
Esto incluye los archivos principales como _config.yml, index.markdown, la carpeta _posts, etc.

📸 Captura:
[c1](img/img-ej1//1.png)

## 2. Personalización del archivo _config.yml

Se personaliza la configuración del sitio con información básica: título, descripción, URL, usuario de GitHub, etc.

Contenido Modificado:

[](img/img-ej1/2.png)

## 3. Modificación de la página de inicio (index.markdown)

Se edita el archivo index.markdown para incluir un título y un texto de bienvenida en formato Markdown.

Contenido añadido:
[](img/img-ej1/3.png)

## 4. Edición de about.markdown

Objetivo: Personalizar la página “Acerca de” para incluir información personal y gustos relacionados con el fútbol.

Contenido añadido:

[](img/img-ej1/4.png)

## 5. Creación de la página `cv.md`
Creamos el fichero `cv.md` y añadimos contenido.

Contenido:
[](img/img-ej1/5.png)

## 6. Creación de 3 publicaciónes (Post)
Todos los posts que se van ir creando se crearan en la carpeta _posts y es muy recomendado establecer un patrón de nombrado para tenerlos organizados.

Primer Post:

[](img/img-ej1/6.png)

Segundo Post:

[](img/img-ej1/7.png)

Tercer Post:

[](img/img-ej1/8.png)

## 7. Probar el funcionamiento.
Para visualizar lo que hemos estado haciendo ejecutamos los siguientes comandos:
```bash
bundle exec jekyll build
bundle exec jekyll serve
```

[](img/img-ej1/9.png)

[](img/img-ej1/10.png)

