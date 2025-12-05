# Ejercicio 2 – Tema Jekyll “Lagrange” usando Fork  
## Despliegue en GitHub Pages

En este documento explico los pasos que he seguido para **importar, configurar y desplegar** el tema **Lagrange**, utilizando el método recomendado: **Fork del repositorio original**.

---

# 1. Realizar el Fork del tema Lagrange

1. Busqué el repositorio oficial del tema en GitHub:  
   `Lagrange Jekyll theme`.
2. Accedí al repositorio y pulsé el botón **Fork**.
3. Se creó una copia del repositorio en mi cuenta de GitHub:  
   `https://github.com/eliasxvv16/lagrange`

[](/img/img-ej2/1.png)

---

# 2. Clonar el repositorio

En mi máquina local Debian ejecuté:

```bash
git clone https://github.com/mi_usuario/lagrange
cd lagrange
```

[](/img/img-ej2/2.png)

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

[](/img/img-ej2/3.png)

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

[](/img/img-ej2/4.png)
[](/img/img-ej2/5.png)

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

# 6. Personalización del sitio y Creación de publicaciones (posts)

Para personalizar el sitio y crear posts en la carpeta `_posts` añadimos **publicaciones** ahí:

He modificado y he creado nuevos posts..
ejemplos:

```markdown
---
layout: post
title: "Mi primer post con Lagrange"
author: "Mi Nombre"
---
Contenido del post...
```

[](/img/img-ej2/6.png)

---

# 8. Subir el sitio a GitHub

```bash
git add .
git commit -m "Configuración inicial del tema Lagrange"
git push 
```

[](/img/img-ej2/7.png)

---

# 9. Activar GitHub Pages

Entré en:

**Settings → Pages**

Configuré:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/** (root)

URL final del sitio:

```
https://eliasxvv.github.io/lagrange/
```

[](/img/img-ej2/8.png)

---

# 10. Comprobación del sitio publicado

Probé la URL y verifiqué:

- Página principal personalizada  
- Nueva página  
- 3 publicaciones  
- Mi nombre como autor  
- Imágenes funcionando  

[](/img/img-ej2/9.png)

---

# ✔ Resultado final

El tema **Lagrange** ha sido correctamente configurado, personalizado y desplegado en GitHub Pages.
