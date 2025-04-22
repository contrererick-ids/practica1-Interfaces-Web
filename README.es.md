# Interfaces Web con Bootstrap — Práctica 1

Este repositorio contiene la implementación de las **interfaces de usuario frontend** para una aplicación web tipo e-commerce. La práctica se centra en el uso de **HTML, CSS y Bootstrap 5** para construir páginas responsivas, accesibles y visualmente atractivas que permitan la interacción del usuario con la tienda.

## 🎯 Objetivo

Diseñar e implementar las interfaces de una aplicación web utilizando **Bootstrap 5** y buenas prácticas de maquetado y estructura.

## 🚀 Funcionalidades Implementadas

### 🏠 Página de Inicio (`index.html`)
- **Navbar** responsiva con enlaces de navegación y menú desplegable para cuenta de usuario.
- **Carrusel de imágenes** de productos destacados usando componentes de Bootstrap.
- Ícono de **carrito de compras** con soporte para indicadores (badges) de cantidad.
- **Cuadrícula de productos** usando tarjetas (`cards`) de Bootstrap:
  - 4 productos en pantallas grandes.
  - 3 productos en pantallas medianas.
  - 2 productos en pantallas pequeñas.
- Componente de **paginación** al final para navegar entre páginas de productos.

### 🔐 Modal de Inicio de Sesión
- Se activa desde "Mi Cuenta > Ingresar" en la barra de navegación.
- Implementado con la estructura modal de Bootstrap.
- Incluye validación de campos requeridos.
- Uso de **íconos FontAwesome** y clases `input-group` para diseño mejorado.
- El envío del formulario cierra el modal al validar correctamente.

### 📝 Modal de Registro de Usuario
- Accesible desde "Mi Cuenta > Registro".
- El modal incluye:
  - Entradas para nombre, apellido, correo y contraseña.
  - Diseño en **Flexbox** para organizar nombre y apellido en la misma fila.
- Validaciones:
  - Campos obligatorios.
  - Expresiones regulares para validar formato de nombre y contraseña.
- Validación de patrones (`pattern`) y longitud mínima (`minlength`) vía HTML.

### 🛒 Página del Carrito (`shopping_cart.html`)
- Página separada que muestra los productos agregados por el usuario.
- Usa la estructura `media object` de **Bootstrap 4** para presentar cada producto.
- Visualiza nombre, imagen, botones de control y navegación.
- Reutiliza la barra de navegación para mantener consistencia.

### 📦 Página de Pedidos (`orders.html`)
- Desglose de productos pedidos en tarjetas, tablas o acordeones.
- Inspirado en la vista de historial de pedidos de sitios como Amazon.
- Contiene botones de retorno y estructura responsiva.

### 📱 Diseño Responsivo
- Adaptación para distintos tamaños de pantalla mediante **sistema de grillas** de Bootstrap.
- Uso de clases `col-sm`, `col-md`, `col-lg` para lograr layouts fluidos.

## 🧠 Lo que Aprendí

- Mejoré mi comprensión del diseño responsivo con **Bootstrap**.
- Apliqué **formularios modales y validación** utilizando HTML5 y clases Bootstrap.
- Practiqué la estructura modular y reutilización de componentes.
- Trabajé en la fluidez de diseño con **Flexbox** y sistemas de columnas.
- Afiné el comportamiento responsivo y la lógica de validación.

## ⏱️ Tiempo Invertido

Aproximadamente: 10 horas  
Incluyendo diseño, validaciones, pruebas y ajuste visual.

## 📦 Entregables

- Código HTML, CSS (con estilo propio donde fue necesario) y recursos enlazados.
- Todos los recursos están referenciados mediante **rutas relativas** y fuentes públicas (e.g., Unsplash).
- Este repositorio es **público y puede clonarse**.

## 📝 Licencia

Este proyecto fue desarrollado con fines educativos como parte del curso de *Ingeniería en Computación*. Todos los derechos reservados por los autores originales.

---

📘 Also available in English: [README.md](README.md)