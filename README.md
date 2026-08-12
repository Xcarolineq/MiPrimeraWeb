# MiPrimeraWeb
# 🌐 Mi primera web

¡Bienvenidos a la **Actividad Clase 02**! 👋

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

### 3. Subir los cambios

```bash
git push origin main
```

Luego entra a tu repositorio en GitHub y comprueba que tus cambios aparezcan correctamente.

---

# 🧠 Chuleta Git

Si te pierdes durante la actividad, estos son los comandos que probablemente necesitas:

```bash
# Ver archivos y carpetas
ls

# Entrar a una carpeta
cd nombre-carpeta

# Volver atrás
cd ..

# Clonar un repositorio
git clone "enlace-del-github"

# Revisar cambios
git status

# Preparar todos los cambios
git add .

# Crear un commit
git commit -m "mensaje"

# Subir cambios a GitHub
git push origin main
```

---

## 🎯 Objetivo de la actividad

Al finalizar esta actividad deberías haber logrado:

* Crear un **Fork** de un repositorio.
* Clonar un proyecto desde GitHub.
* Navegar entre carpetas utilizando la terminal.
* Modificar archivos de una página web.
* Utilizar comandos básicos de Git.
* Crear un commit.
* Subir tus cambios a GitHub.

---

> 💡 **No necesitas memorizar todos los comandos.**
>
> La idea de esta actividad es comenzar a familiarizarte con Git, GitHub y la terminal. Si algo sale mal, revisa las pistas, pregunta y vuelve a intentarlo. 🚀
