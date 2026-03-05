# Responsive Dog Cards Grid - Página Responsive

## Objetivo
Diseñar y maquetar una página de **cards** de perros completamente responsive, enfocándose en la correcta disposición visual y la experiencia en distintos tamaños de pantalla.  
Este proyecto **no incluye funcionalidades dinámicas**, el objetivo principal fue practicar la construcción de layouts flexibles y responsivos usando solo HTML y CSS.

## Tecnologías
- HTML5
- CSS3
- CSS Custom Properties (`:root`)
- Flexbox
- Media Queries

## Detalles Técnico

- Se utilizó un **sistema de filas y columnas** basado en Flexbox para organizar las cards.
- Cada card se diseñó como un bloque independiente, con alineación y espaciado consistentes.
- Variables CSS definidas en `:root` 
- Las columnas permiten construir la disposición de las cards de manera modular y escalable.

El diseño se adapta a distintos tamaños de pantalla mediante media queries:

- **Mobile** (por defecto)
- **Tablet** (`@media (width > 768px)`)
- **Desktop** (`@media (width > 1024px)`)

Se implementaron clases específicas por breakpoint:
- `.col-md-*`
- `.col-lg-*`

## Enfoque de Aprendizaje
Este ejercicio refuerza:

- Construcción de layouts flexibles sin frameworks.
- Uso de CSS variables para mantener consistencia y facilitar el mantenimiento.
- Maquetación responsive basada en Flexbox y media queries.
- Organización modular del código HTML y CSS.

## Cómo ver el proyecto
Abrir `index.html` en un navegador y redimensionar la ventana para comprobar el comportamiento responsive.

## Capturas
![Preview](preview.png)