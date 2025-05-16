# 🚀 Despliegue de un sitio web estático en Amazon S3 desde cero

Este repositorio contiene el código fuente utilizado para un artículo en Medium  
que explica cómo desplegar un sitio web estático utilizando únicamente **Amazon S3** desde cero.

---

## 📋 Descripción

El proyecto incluye:

- 🏠 **Página principal** (`index.html`): Muestra un mensaje de éxito al desplegar el sitio.
- ⚠️ **Página de error personalizada** (`error.html`): Maneja errores 404.
- 🔐 **Política de bucket S3** (`policies/bucket.json`): Permite el acceso público a los archivos del sitio.

---

## 🗂️ Estructura del proyecto

```plaintext
website/
├── index.html       # 🏠 Página principal
├── error.html       # ⚠️ Página de error 404
policies/
├── bucket.json      # 🔐 Política de acceso para el bucket S3
README.md            # 📄 Documentación del proyecto
```
## 📖 Enlace al artículo

Puedes leer el artículo completo en Medium para obtener más detalles sobre el proceso de despliegue.

[Ver artículo en Medium]()