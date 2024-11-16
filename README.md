# Apuntes-asix1
# MarkDown
## Segundo nivel de encabezado
### Tercero nivel de encabezado
#### Quarto nivel de encabezado
##### Quinto nivel de encabezado

Mis apuntes de *0373* del ciclo de _asix_ o **daw** __**2425**__

Las eqtiquetas de HTML y **_Markdown_** puede anidarse

1. Primer punto de la lista
    1. Primer punto de la sublista
    2. Segundo punto de la sublista

2. Segundo punto de la lista
    * 
3. Tercer punto de la lista

* Primer punto de lista desordenada
- Segundo punto de lista desordenada
+ Tercer punto de lista desordenada


**Como mostrar codigo en un repositorio**
```
<html>
	<head>
		<title>Mi página de ejemplo</title>
	</head>
	<body>
	Aquí va el contenido
	</body>
</html>
```

### Como poner un link
[texto clicable](URL "Titulo opcional")
[Pagina Web Joan23](https://www.fje.edu/ca/jesuites-bellvitge "Titulo opcional")


### Como poner una imagen

![Texto alternativo](Ubicacion de la imagen "Titulo opcional")

![Ronaldiño](https://github.com/MerinoVic115/apuntes-asix1/blob/main/ronaldi%C3%B1o.jpg "Titulo opcional")


|Titulo 1 | Titulo 2 | Titulo 3 |
|----------|:--------------:|------------------:|
|SMX2 |Curso 2423 |25 |
|**ASIX1** |Curso 2425 |33 |
|DAW2 |Curso 2425 |32 |

# Comandos Github

| **Comando**                     | **Descripción**                                                                                     |
|             ------------------- |-----------------------------------------------------------------------------------------------------|
| `git init`                      | Inicializa un nuevo repositorio Git en el directorio actual.                                        |
| `git clone <URL>`               | Clona un repositorio existente desde una URL.                                                       |
| `git add .`                     | Agrega todos los cambios al área de preparación.                                                    |
| `git commit -m "mensaje"`       | Guarda los cambios en el historial del repositorio con un mensaje.                                  |
| `git push`                      | Sube los cambios al repositorio remoto.                                                             |
| `git pull`                      | Descarga y fusiona los cambios del repositorio remoto al local.                                     |


# HTML

## Introducción a html

HTML (HyperText Markup Language), es un **lenguaje de marcas**, es lo mas importante de internet ya que sin html no se vería nada.
HTML define la estructura y el contenido, tiene una estructura lógica y es fácil de interpretar y entender.
No se dedica a ver como se interactúa con el contenido (javascript y etc).
Los elementos de html son bloques de construcción de las paginas web.
HyperText: texto que enlaza otros contenidos
Markup: Todas las webs están construidas en base de etiquetas
Language: HTML es un lenguaje, pero no es un lenguaje de programación, no tiene estructuras de lenguaje de programación, bucles, condiciones, funciones y etc.


## Elementos: 
El contenido esta entre dos etiquetas.

## Atributos: 
Es algo que modifica la etiqueta. El atributo va en la etiqueta de inicio.

## Estructura de html:
Esto es una estructura básica de HTML.
```
<html>
	<head>
		<title>Título de ejemplo</title>
	</head>
	<body>
		<p>¡Esta es mi web!</p>
	</body>
</html>
```

## Elementos de bloque y línea

### Elementos de bloque
Son grandes estructuras independientes que separan contenido.  
Ejemplos: `<h1>` - `<h6>` (encabezados), `<p>` (párrafo), `<br>` (salto de línea), `<hr>` (separador), `<div>`, `<blockquote>`, `<pre>`.

### Elementos de línea
Son pequeñas estructuras que representan trozos de texto dentro de los bloques.  
Ejemplos: `<em>` (cursiva), `<strong>` (negrita), `<a>` (hipervínculos), `<span>`, `<code>`.

---

## Legibilidad y organización del código

La legibilidad del código facilita su comprensión. Es fundamental que el código HTML sea claro y organizado.

### Puntos clave:
- **Usa comentarios.**
- **Aplica indentación del código.**
- **Organiza los archivos en directorios según sea necesario.**

---

## Etiquetas básicas de HTML (Listas)

### Listas desordenadas
Usan `<ul>` (unordered list) con símbolos como círculos, discos o cuadrados.  
**Ejemplo:** `<ul type="disc">`.

### Listas ordenadas
Usan `<ol>` (ordered list) donde el orden importa (como recetas).  
Pueden ser numéricas o alfabéticas.  
**Ejemplo:** `<ol type="1">` para números o `<ol type="A">` para letras.  
**Parámetro:** `start=n` para definir el inicio.

---

## Etiquetas básicas de HTML

**Listas de definición:** Enumeran términos con sus definiciones.
**Formadas por dos elementos:** el término y su definición.
**Etiquetas usadas:**
*<dl>*: Define el inicio y fin de la lista (definition list).
*<dt>*: Representa el término (definition term).
*<dd>*: Contiene la definición del término (definition description).

## Rutas de HTML

- **Ruta absoluta:** Incluye la ruta completa.  
  **Ejemplo:** `C:\html\img1.jpg`
  
- **Ruta relativa:** Define la ruta desde la ubicación actual.  
  **Ejemplo:** `..\imagenes\img2.jpg`

---

## Validación HTML

Para validar un HTML, utiliza el siguiente enlace:  
[validator.w3.org](https://validator.w3.org/ "Validador de HTML")


## Elementos semánticos en html 5:

<span> permite agrupar contenido en línea.
<div> permite guardar otras etiquetas. 
HTML semántico: Describe el contenido con un significado claro y estructurado.

Elementos como <span> (contenido en línea) y <div> (contenido en bloque) no aportan valor semántico, solo estructuran sin indicar el tipo de contenido.

Ventaja del HTML semántico: Proporciona información clara sobre el contenido, facilitando la comprensión y accesibilidad.

Ejemplos de elementos semánticos:

<header>, <footer>, <article>, <section>, <nav>, <figure>.


## Formulario
El formulario es para recopilar datos del usuario y contiene varios elementos (nombre, password y etc).
Cada formulario debe de tener atributo name, con lo cual se identifica el dato.
Apertura y cierre: <form>
Atributo común: 
		action: Define la url donde se enviará los datos
		method: especifica el método de envio de datos
		enctype: Define como se codifican los datos

etiqueta *imput*: 
	Se usa para crear diversos campos interactivos.

