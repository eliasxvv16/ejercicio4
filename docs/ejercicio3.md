# Ejercicio 3 – Tema Jekyll “Professional-resume” usando Fork  
## Despliegue en GitHub Pages

En este documento explico los pasos que he seguido para **importar, configurar y desplegar** el tema **Lagrange**, utilizando el método recomendado: **Fork del repositorio original**.

---

# 1. Realizar el Fork del tema Particle

1. Busqué el repositorio oficial del tema en GitHub:  
   `https://github.com/byanko55/jekyll-professional-resume`.
2. Accedí al repositorio y pulsé el botón **Fork**.
3. Se creó una copia del repositorio en mi cuenta de GitHub:  
   `https://github.com/eliasxvv16/professional-resume`

[](/img/img-ej3/1.png)

---

# 2. Clonar el repositorio

En mi máquina local Debian ejecuté:

```bash
git clone https://github.com/eliasxvv16/portfolio.git
cd professional-resume
```

[](/img/img-ej3/2.png/)

---

# 3. Instalar dependencias

Instalé Jekyll y Bundler si no estaban instalados:

```bash
gem install jekyll bundler
```

Luego instalé las dependencias del tema:

```bash
bundle install
```

[](/img/img-ej3/3.png)

---

# 4. Ejecutar Jekyll en local

Probé el sitio con:

```bash
bundle exec jekyll serve
```

Navegué a:

```
http://localhost:4000
```

[](/img-ej2/4.png)
[](/img-ej2/5.png)

---

# 5. Configuración del archivo `_config.yml`

Personalicé los valores principales:

```yaml
title: "Mi Blog con Lagrange"
author: "Mi Nombre y Apellidos"
email: "miemail@example.com"
description: "Blog creado con el tema Lagrange"
url: "https://mi_usuario.github.io"
baseurl: "/lagrange"
```

(Imagen: Contenido del _config.yml)

---

# 6. Personalización del sitio

La página es una página portfolio osea que voy a cambiar toda la información
He ido cambiando toda la información

[](/img/img-ej3/6.png)

# 7. Desplegar el sitio en netlify

Primero hago un push para actualizar todo lo hecho localmente y tambien voy a hacer un despliege en local para ver como queda la página.

[](/img/img-ej3/7.png)

Ahora Despues de crear un cuenta en netlify le damos a deploy y seleccionamos el repositorio de la página

[](/img/img-ej3/8.png)

Netlify nos va ejecutar automaticamente el jekyll build si no tenemos la carpeta _Site

[](/img/img-ej3/9.png)

Captura del sitio desplegado

[](/img/img-ej3/10.png)