# 📘 Apuntes-Victor_Merino_Saceda_ASIX1

## Índice

- [📘 Apuntes-Victor\_Merino\_Saceda\_ASIX1](#-apuntes-victor_merino_saceda_asix1)
	- [Índice](#índice)
	- [🐙 GITHUB](#-github)
		- [Crear un repositorio](#crear-un-repositorio)
		- [🔧 Comandos GIT](#-comandos-git)
		- [🛠 Otros comandos útiles](#-otros-comandos-útiles)
	- [📝 MARKDOWN](#-markdown)
		- [Encabezados](#encabezados)
		- [Enlaces](#enlaces)
		- [Imágenes](#imágenes)
		- [HTML en Markdown](#html-en-markdown)
	- [🌐 HTML](#-html)
		- [📄 Fichero HTML](#-fichero-html)
		- [🧩 Etiquetas Generales](#-etiquetas-generales)
		- [🔤 Etiquetas para body](#-etiquetas-para-body)
		- [🧱 Bloques de contenido](#-bloques-de-contenido)
	- [🎨 CSS](#-css)

---

## 🐙 GITHUB

**GITHUB** es una herramienta para realizar **copias de seguridad (backups)** de tu web o programa. Puedes conectarte mediante el inicio de sesión y la creación de repositorios.

### Crear un repositorio

1. Ve a **Tu perfil > Tus repositorios**.
2. Haz clic en el botón verde **New** para crear un repositorio.

![Interfaz de GitHub](./img/interfaz_github.png)
![Botón New](./img/boton_new.png)

Aparecerá un formulario donde debes rellenar los siguientes campos:

![Formulario creación de repositorio](./img/creacion_rep.png)

| Propiedad              | Descripción                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Owner**              | Propietario del repositorio                                                 |
| **Repository name**    | Nombre que asignas al repositorio                                           |
| **Description**        | Descripción del repositorio                                                 |
| **Public or Private**  | Define si el repositorio será público o privado                             |
| **Add a README file**  | Opción recomendada para estructurar e informar sobre el repositorio         |

[🔝 Volver al índice](#índice)

---

### 🔧 Comandos GIT

Una vez creado el repositorio, debemos conectarnos a él desde la carpeta que queremos subir.

1. Inicializar Git:
   ```bash
   git init
   ```
   ![git init](./img/git_init.png)

2. Ver la rama actual:
   ```bash
   git branch
   ```
   ![git branch](./img/git_branch.png)

3. Clonar un repositorio:
   ```bash
   git clone <URL-del-repositorio>
   ```
   ![git clone](./img/git_clone.png)

4. Añadir archivos:
   ```bash
   git add .
   ```
   ![git add](./img/git_add.png)

5. Hacer commit:
   ```bash
   git commit -m "Primer backup"
   ```
   ![git commit](./img/git_commit.png)

6. Subir a GitHub:
   ```bash
   git push origin main
   ```
   ![git push](./img/git_push.png)

[🔝 Volver al índice](#índice)

---

### 🛠 Otros comandos útiles

| Comando                                        | Descripción                                               |
|-----------------------------------------------|-----------------------------------------------------------|
| `git --version`                               | Ver la versión de Git                                     |
| `git config --global username "tu_usuario"`   | Configurar tu nombre de usuario global en Git             |
| `git config --global useremail "tu_email"`    | Configurar tu correo electrónico global en Git            |

[🔝 Volver al índice](#índice)

---

## 📝 MARKDOWN

Un archivo **Markdown** tiene la extensión `.md` y permite crear contenido visual estructurado mediante combinaciones de símbolos.

![Ejemplo de README](./img/readme.png)

### Encabezados

```markdown
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3
#### Encabezado nivel 4
##### Encabezado nivel 5
###### Encabezado nivel 6
```

![Encabezados](./img/encabezados.png)

### Enlaces

```markdown
[Texto visible](ruta "Texto emergente")
```

### Imágenes

```markdown
![Texto alternativo](ruta "Texto emergente")
```

### HTML en Markdown

Puedes insertar etiquetas HTML directamente:

```html
<p>Hola</p>
```

[🔝 Volver al índice](#índice)

---

## 🌐 HTML

### 📄 Fichero HTML

Un archivo HTML debe tener extensión `.html`, como `index.html`.

![Archivo HTML](./img/ficherohtml.png)

**Visual Studio Code** es la mejor herramienta para editar HTML por sus funciones y soporte.

![Comparación](./img/comparacion.png)

Código base de un archivo HTML:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

Puedes generarlo escribiendo `html:5` y pulsando **Enter**.

[🔝 Volver al índice](#índice)

---

### 🧩 Etiquetas Generales

```html
<!DOCTYPE html>       <!-- Tipo de documento -->
<html lang="es">      <!-- Idioma principal -->
<head>                <!-- Información no visible para el usuario -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Prueba</title> <!-- Título que aparece en el navegador -->
</head>
<body>                <!-- Contenido visible -->
</body>
</html>
```

[🔝 Volver al índice](#índice)

---

### 🔤 Etiquetas para body

| Etiqueta                     | Descripción                                                           |
|-----------------------------|------------------------------------------------------------------------|
| `<p>`                       | Añade un párrafo                                                       |
| `<img src="">`              | Muestra una imagen                                                     |
| `<h1>` a `<h6>`             | Encabezados, del nivel 1 al 6                                          |
| `<ul>` / `<ol>`             | Listas desordenadas / ordenadas                                       |
| `<li>`                      | Elemento de lista                                                      |
| `<a href="">`               | Inserta un enlace                                                      |
| `<br>`                      | Salto de línea                                                         |
| `<hr>`                      | Línea horizontal                                                       |
| `<!-- Comentario -->`       | Comentario invisible en la web                                        |
| `<b>`                       | Texto en negrita                                                       |

[🔝 Volver al índice](#índice)

---

### 🧱 Bloques de contenido

En HTML puedes estructurar tu contenido con bloques semánticos:

```html
<section>
  <article>
    <p>Texto de ejemplo</p>
  </article>
  <article>
    <img src="../img/ejemplo.png" alt="Imagen de ejemplo">
  </article>
</section>
```

- `<section>` agrupa contenido por secciones.
- `<article>` representa contenido independiente y auto-contenido.

[🔝 Volver al índice](#índice)

---

## 🎨 CSS

<!-- por hacer  -->

[🔝 Volver al índice](#índice)
