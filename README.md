# Carrusel de Imágenes
[![Version](https://img.shields.io/badge/version-1.0.0-blue)]
[![License](https://img.shields.io/badge/license-MIT-green)]
## 🔧 Tecnologías Utilizadas

Tecnologías usadas en el proyecto:

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 Badge"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3 Badge"/>
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery Badge"/>
</p>

---

###  Descripción de Tecnologías

| 🔧 Tecnología | 📄 Descripción                         |
|---------------|----------------------------------------|
| **HTML5**     | Lenguaje de marcado para estructurar contenido |
| **CSS3**      | Hojas de estilo para diseño visual           |
| **jQuery**    | Librería JS para manipulación del DOM         |

---


# 1.- Objetivo
Crear una galería de imágenes donde se cumplan los siguientes requisitos utilizando jQuery:
Visualizar las imágenes en miniatura: Las imágenes deben estar en un formato de cuadrícula, y al hacer clic en cualquiera de ellas, se debe mostrar la imagen en tamaño grande en una ventana emergente o modal.
Navegación entre imágenes: Deben existir botones de "Siguiente" y "Anterior" dentro del modal para navegar entre las imágenes sin cerrar el modal.
Cerrar el modal: Al hacer clic fuera de la imagen en el modal o en el botón de cerrar, el modal debe desaparecer.


# 2.- Requerimientos Técnicos
Estructura HTML:
Utiliza una estructura básica de HTML con una galería de imágenes pequeñas.
Cada imagen debe tener un ID único para facilitar la selección con jQuery.

### CSS:
Aplica estilos para que las imágenes miniatura se muestren en una cuadrícula.
El modal debe estar centrado y oculto por defecto.

### jQuery:
Mostrar imagen en tamaño grande: Al hacer clic en una miniatura, la imagen debe aparecer en tamaño grande en el modal.
Navegación entre imágenes: Al hacer clic en los botones de "Siguiente" y "Anterior", la imagen debe cambiar a la siguiente o anterior de la galería.
Cerrar modal: Al hacer clic en cualquier lugar fuera de la imagen grande o en el botón de cerrar, el modal debe desaparecer.
Efectos de jQuery: Usa efectos de jQuery como fadeIn, fadeOut, slideUp, etc., para mejorar la interacción.

### Validación:
Asegúrate de que todos los elementos del modal se comporten correctamente sin recargar la página.


# 3.- Instrucciones
Crea un archivo HTML con la estructura de la galería, utilizando miniaturas de imágenes. Por ejemplo, puedes usar imágenes de ejemplo con el atributo src como "image1.jpg", "image2.jpg", etc.
Agrega el código jQuery para que al hacer clic en cualquier imagen miniatura, la imagen se vea en tamaño grande en un modal.
Incorpora los botones de navegación (Siguiente y Anterior) dentro del modal para permitir la navegación entre las imágenes.
Agrega una opción para cerrar el modal haciendo clic fuera de la imagen o en un botón de cerrar.
Agrega los efectos de jQuery para hacer la galería más interactiva, como hacer que el modal aparezca y desaparezca suavemente.
Asegúrate de que el modal esté centrado en la pantalla y se ajuste bien en diferentes tamaños de ventana.


# 4.-Estructura de Archivos
index.html: El archivo principal que contiene la galería y el modal.
styles.css: Archivo de estilos para la galería y el modal.
script.js: Archivo que contiene el código jQuery para manejar la interactividad.

# Imágenes del proyecto

![ScreenShot del Carrusel de Imágenes](https://drive.google.com/uc?id=1qaMxZhCq5WBrrx3WfmKNYT2NpSrh3-Af)
