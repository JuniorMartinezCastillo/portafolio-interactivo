# Portafolio Interactivo - SportZone

Práctica Calificada N° 3 - Hojas de Estilo en Cascada Avanzado

Landing page de una tienda de productos deportivos hecha con Bootstrap 5, transformaciones y animaciones CSS.

## Bootstrap 5
- Navbar con logo y menú (Inicio, Proyectos, Contacto) que se vuelve hamburguesa en celular.
- Grid con `container`, `row`, `col-sm-12` y `col-md-6` / `col-md-4`.
- Formulario de contacto con `form-label`, `form-control` y `mb-3`.
- Botones Enviar (`btn btn-primary`) y Limpiar (`btn btn-secondary`) dentro de `d-grid gap-2`.

## Transformaciones 2D
Las tres cajas de productos cambian al pasar el mouse y usan `transition` para que sea suave:
- Caja 1 (balón de fútbol): `rotate(10deg)`
- Caja 2 (balón de básquet): `scale(1.2)`
- Caja 3 (raqueta): `translateY(-15px) skew(10deg)`

## Transformación 3D
La tarjeta de zapatillas está dentro de un contenedor con `perspective: 800px`. La tarjeta usa `transform-style: preserve-3d` y `rotateX()` / `rotateY()`, y gira al pasar el mouse.

## Animaciones
- `@keyframes aparecer`: el título aparece deslizándose desde la izquierda.
- `@keyframes girar`: loader circular que gira infinitamente dentro del botón amarillo.
- `@keyframes cambiarColor`: el título "Nuestros Productos" cambia de color y tamaño constantemente, de ida y vuelta.
- Se usaron `animation-duration`, `animation-iteration-count`, `animation-timing-function` y `animation-direction` (`normal` y `alternate`).
