# Tienda de Comercio Electrónico - Programación Web II (Semana 3)

Este proyecto consiste en una aplicación web dinámica del lado del cliente que simula una tienda en línea. Implementa la manipulación del DOM y el manejo de eventos en JavaScript nativo, permitiendo una experiencia de usuario fluida sin recargar el navegador.

## Estructura del Proyecto

Para cumplir con las buenas prácticas de desarrollo y el principio de separación de responsabilidades, el código se ha dividido de la siguiente manera:

* `index.html`: Estructura base de la página, contenedor del buscador, catálogo y estados del carrito.
* `styles.css`: Reglas de estilo para el diseño responsivo, empaquetado de imágenes y tipografías personalizadas.
* `Producto.js`: Modelado de datos. Contiene la clase `Producto` con sus métodos de cálculo de descuento y auto-renderizado HTML, además del inventario inicial.
* `app.js`: Lógica de la aplicación. Maneja el filtrado de búsqueda, el botón de limpiar, el contador del carrito y el sistema de notificaciones en tiempo real.
* `assets/`: Carpeta local que almacena las imágenes de los productos (`laptop.png`, `teclado.png`, etc.).

## Características Implementadas

1.  **Manipulación Dinámica del DOM:** Los productos no están fijos en el HTML; se generan y añaden dinámicamente al árbol del DOM desde JavaScript.
2.  **Sistema de Búsqueda y Filtrado:** Permite buscar productos por nombre o categoría en tiempo real.
3.  **Botón Limpiar:** Restaura el buscador vaciando el cuadro de texto y recargando el catálogo completo instantáneamente para mejorar la usabilidad (UX).
4.  **Simulación de Carrito de Compras:** Al presionar "Agregar al Carrito", se actualiza de forma reactiva un contador en el encabezado.
5.  **Eventos Avanzados:** Uso de `addEventListener` para controlar clics, pulsaciones de teclas (`Enter`) y la carga del documento (`DOMContentLoaded`).
6.  **Notificaciones Instantáneas:** Alertas dinámicas temporales para avisar sobre promociones de marketing o confirmar interacciones del usuario.

## Tecnologías utilizadas:

- Javascript
- HTML5
- CSS3

## Desarrollado por:

- Tamara Muñoz
