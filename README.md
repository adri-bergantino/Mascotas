# TP Galería Visual — Mis Mascotas

* **Nombre y apellido:** Adriel Bergantino
* **Materia:** Diseño y Desarrollo Web
* **Tema:** Mis Mascotas (Kafka, Flash y Alma)

## De qué trata el proyecto
El sitio es una galería visual que armé para presentar a mis tres mascotas: Kafka (mi gato adoptado), Flash (un border collie de 3 años) y Alma (una caniche de 14 años). La idea fue contar brevemente cómo es cada uno, sus costumbres en casa y mostrar fotos que les saqué.

## Objetivo
Crear una web sencilla con HTML y CSS que permita recorrer la información de las mascotas de forma cómoda, con una portada general y una página propia para cada una con sus fotos y datos.

## Contenidos del sitio
* `index.html`: Página principal con la presentación y las tres tarjetas de acceso.
* `kafka.html`: Página sobre Kafka con su información, el origen de su nombre y sus fotos.
* `flash.html`: Página sobre Flash con su historia del moquillo y sus fotos.
* `alma.html`: Página sobre Alma contando su rutina de caniche viejita y fotos.
* `css/style.css`: Estilos visuales de todo el sitio.
* `img/`: Fotos de las mascotas usadas en las páginas.

## Decisiones de diseño
* **Colores:** Usé verde oscuro (`#2e5b32`) para el encabezado y los botones, y un naranja (`#c45a1b`) para marcar la página activa y cuando pasas el mouse por arriba. De fondo elegí un gris claro (`#f4f4f4`) para que no quede el blanco puro de fondo y las tarjetas blancas resalten mejor.
* **Tipografía:** Usé Arial (`Arial, Helvetica, sans-serif`) para que sea fácil de leer en cualquier pantalla y no tarde en cargar.
* **Maquetación y Responsive:**
  * Usé Flexbox para ordenar el menú de navegación, poner las tres tarjetas una al lado de la otra en el inicio y ordenar las fotos en las páginas individuales.
  * Para que se adapte a celulares sumé un `@media (max-width: 768px)` que apila las tarjetas y los botones en una sola columna.
  * Usé porcentajes (`%`) para que las imágenes y tarjetas se adapten al ancho de la pantalla, `rem` para los tamaños de los títulos y `em` para los botones.