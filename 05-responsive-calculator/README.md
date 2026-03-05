# Calculadora Responsive (Solo Maquetación)

## Objetivo
Diseñar y estructurar la interfaz de una calculadora completamente responsive, enfocándose exclusivamente en la maquetación.

Este proyecto **no incluye funcionalidad en JavaScript**, ya que el objetivo principal fue practicar la construcción de un sistema de layout responsive utilizando únicamente HTML y CSS.

## Tecnologías
- HTML5
- CSS3
- CSS Custom Properties (`:root`)
- Flexbox
- Media Queries

## Detalles Técnicos

Se desarrolló un sistema de columnas propio utilizando variables CSS definidas en `:root` con clases reutilizables que permiten construir la estructura de manera modular.

El diseño se adapta a distintos tamaños de pantalla mediante media queries:

- **Mobile** (por defecto)
- **Tablet** (`@media (width > 768px)`)
- **Desktop** (`@media (width > 1024px)`)

Se implementaron clases específicas por breakpoint:
- `.col-md-*`
- `.col-lg-*`

Este enfoque simula el funcionamiento de un pequeño framework de grid, pero desarrollado desde cero.

## Enfoque de Aprendizaje
Este ejercicio consolida:

- Creación de un sistema de grid personalizado sin frameworks.
- Uso avanzado de `calc()` y variables CSS.
- Organización escalable y mantenible del CSS.
- Construcción de layouts responsive desde cero.

## Cómo ver el proyecto
Abrir `index.html` en el navegador y redimensionar la ventana para comprobar el comportamiento responsive.

## Capturas
![Preview](preview.png)