# 🌐 Mi primera web

¡Bienvenidos a la **Actividad de la Clase 02**! 👋

En esta actividad crearemos una página web sencilla utilizando **HTML y CSS**, trabajaremos con **Git** desde la terminal y utilizaremos **GitHub** para guardar nuestro proyecto.

> 💡 **Importante:** Sigue las instrucciones de la profesora durante la clase. Este README contiene algunas pistas y comandos que te pueden ayudar si te pierdes.

---

## 🚀 Paso 1 · Fork del repositorio

Antes de comenzar debes crear una copia de este repositorio en tu propia cuenta de GitHub.

1. Inicia sesión en GitHub.
2. Haz clic en **Fork** en la parte superior del repositorio.
3. Confirma la creación del Fork.
4. Ahora tendrás una copia del proyecto en tu propia cuenta.

⚠️ **Comprueba que el repositorio aparece en tu perfil antes de continuar.**

---

## 💻 Paso 2 · Clonar el repositorio

Ahora necesitamos llevar el proyecto desde GitHub hasta nuestro computador.

Desde tu repositorio busca:

**Code → HTTPS → Copiar enlace**

Luego abre la terminal de **Antigravity** y utiliza:

```bash
git clone "enlace-del-repositorio"
```

Por ejemplo:

```bash
git clone https://github.com/usuario/mi-primera-web.git
```

📌 **Recuerda:** debes clonar **tu Fork**, no el repositorio original de la profesora.

---

## 📂 Pistas para moverte por la terminal

### Ver archivos y carpetas

```bash
ls
```

Este comando muestra los archivos y carpetas disponibles.

### Entrar a una carpeta

```bash
cd nombre-carpeta
```

Por ejemplo:

```bash
cd mi-primera-web
```

### Volver a la carpeta anterior

```bash
cd ..
```

💡 Puedes volver a utilizar `ls` todas las veces que necesites para orientarte.

---

## ✏️ Paso 3 · Construir nuestra web

A partir de este punto:

### 👀 Sigue las instrucciones de la profesora

Durante la clase iremos construyendo nuestra primera página web.

Trabajaremos principalmente con:

```text
📁 mi-primera-web
 ├── index.html
 ├── style.css
 └── README.md
```

No te preocupes si todavía no sabes para qué sirve cada archivo. **Lo iremos descubriendo durante la actividad.**

---

## ☁️ Paso 4 · Subir tus cambios a GitHub

Cuando hayas realizado cambios en tu proyecto, puedes comprobar qué archivos fueron modificados utilizando:

```bash
git status
```

### 1. Preparar los cambios

```bash
git add .
```

### 2. Crear un commit

```bash
git commit -m "mensaje"
```

Por ejemplo:

```bash
git commit -m "Agrega estructura inicial de la web"
```

💡 El mensaje debería explicar brevemente **qué cambio realizaste**.

### 👤 Configuración de identidad (¡Importante!)

Antes de registrar tus cambios, Git necesita saber quién eres. Si no lo has hecho antes, el sistema te pedirá configurar tu correo y nombre de usuario. 

Puedes consultar tu configuración actual o establecerla de forma global con los siguientes comandos:

```bash
# Consultar configuración actual
git config --global user.name
git config --global user.email

# Configurar tu identidad de forma global
git config --global user.name "Tu Nombre de Usuario"
git config --global user.email "tu-correo@ejemplo.com"
```

⚠️ **Si usas un computador compartido:**
Para evitar que tus credenciales se queden guardadas en el computador y afecten a otros proyectos, es recomendable eliminar la configuración global y configurar tu identidad **solo para este repositorio actual**:

```bash

# Configurar tu identidad únicamente en este repositorio (local)
git config user.name "Tu Nombre de Usuario"
git config user.email "tu-correo@ejemplo.com"
```

---

### 3. Subir los cambios

> 🔑 **Autenticación en GitHub:** Antes de enviar el `git push`, el sistema te pedirá iniciar sesión y autenticarte en tu cuenta de GitHub (por ejemplo, a través de una ventana emergente en el navegador o solicitando un token de acceso). Sigue los pasos indicados para autorizar el acceso.

```bash
git push origin main
```

Luego entra a tu repositorio en GitHub y comprueba que tus cambios aparezcan correctamente.

---

## 🌎 Paso 5 · Pasar nuestra web a producción con GitHub Pages

¡Nuestra web ya está lista! 🎉

Hasta ahora hemos trabajado con los archivos en nuestro computador y los hemos subido al repositorio.

Ahora vamos a hacer que nuestra página quede **publicada en Internet** utilizando **GitHub Pages**.

> 💡 GitHub Pages permite publicar sitios web directamente desde un repositorio de GitHub.

---

### 1. Comprueba que tus cambios estén en GitHub

Antes de publicar, asegúrate de haber realizado:

```bash id="r9xjcy"
git status
git add .
git commit -m "Web lista para publicar"
git push origin main
```

Luego entra a tu repositorio en GitHub y comprueba que tus archivos estén ahí.

📌 **Importante:** Tu página principal debe llamarse:

```text id="c9m4m7"
index.html
```

---

### 2. Entra a la configuración del repositorio

Dentro de tu repositorio en GitHub:

**Settings → Pages**

Busca la sección:

**Build and deployment**

---

### 3. Configura GitHub Pages

En **Source**, selecciona:

```text id="3kpd3j"
Deploy from a branch
```

Luego configura:

```text id="3gs3j7"
Branch: main
Folder: / (root)
```

Finalmente, haz clic en:

**Save**

---

### 4. Espera a que GitHub publique tu web ⏳

GitHub comenzará a preparar tu página.

Este proceso puede tardar algunos minutos.

Puedes volver a:

**Settings → Pages**

Cuando la publicación esté lista, GitHub mostrará un mensaje indicando que tu sitio está publicado.

Tu dirección tendrá una estructura similar a:

```text id="6o3xj1"
https://usuario.github.io/mi-primera-web/
```

🎉 **¡Tu primera página web está en Internet!**

---

### 🔄 ¿Qué pasa si modifico mi web?

Una vez configurado GitHub Pages, **no necesitas volver a realizar la configuración**.

Simplemente modifica tu proyecto y vuelve a subir los cambios:

```bash id="opng67"
git status
git add .
git commit -m "Actualiza la web"
git push origin main
```

GitHub Pages detectará los nuevos cambios y actualizará automáticamente el sitio publicado.

> 💡 La actualización puede tardar unos minutos en aparecer.

---

## 🧠 Chuleta Git

```bash id="37twfm"
# Ver archivos y carpetas
ls

# Entrar a una carpeta
cd nombre-carpeta

# Volver atrás
cd ..

# Clonar el repositorio
git clone "enlace-del-github"

# Revisar los cambios
git status

# Preparar los cambios
git add .

# Crear un commit
git commit -m "mensaje"

# Subir los cambios a GitHub
git push origin main
```

---

## 🎯 ¡Actividad completada!

Al finalizar esta actividad habrás realizado un flujo completo:

**GitHub → Fork → Clone → Código → Commit → Push → GitHub Pages → 🌎 Web publicada**

Y tendrás una URL que podrás abrir desde cualquier navegador y compartir con otras personas. 🚀
