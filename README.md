# Prytecto de Portafolio Personal
[![Image](https://github.com/user-attachments/assets/fd602577-8eb5-4ddc-823d-ebbf8fb7f53f)](https://miportfoliocv.netlify.app/)

Desarrollé un portafolio web dinámico e innovador, con el objetivo de presentar mi perfil profesional de manera creativa y funcional.
Desarrolle el proyecto desde la concepción de la arquitectura y UX/UI hasta la implementación front-end completa.

Utilizando HTML para una base sólida, CSS para un diseño visual moderno y adaptable, y JavaScript. Además con asistencia de IA logré soluciones rápidas e innovadoras.
Construí una plataforma que integra funcionalidades esenciales de forma intuitiva.  Implementé la descarga de CV, enlaces directos a mis principales redes, y un showcase interactivo de proyectos,
explorando con IA nuevas formas de mejorar la estructura y la experiencia de navegación web.

***

## Estructura HTML
### Encabezado del Documento
```html
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfolio</title>
  <link rel="icon" href="/assets/portfolio.png" />
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="mediaqueries.css" />
</head>
```

### Navegación
```html
<nav id="desktop-nav">
  <div class="logo">Jorge Antony Zarate Davila</div>
  <div>
    <ul class="nav-links">
      <li><a href="#about">Hacerca de</a></li>
      <li><a href="#experience">Habilidades</a></li>
      <li><a href="#projects">Proyectos</a></li>
      <li><a href="#contact">Contacto</a></li>
      <li><a href="">Ingles</a></li>
    </ul>
  </div>
</nav>
```

## Diseño CSS 
###  Diseños Generales
```css
* {
  margin: 0;
  padding: 0;
}
body {
  font-family: "Poppins", sans-serif;
}
html {
  scroll-behavior: smooth;
}
p {
  margin-bottom: 10px;
  color: rgb(85, 85, 85);
}
```

### Navegación
```css
nav,
.nav-links {
  display: flex;
}
nav {
  justify-content: space-around;
  align-items: center;
  height: 17vh;
}
.nav-links {
  gap: 2rem;
  list-style: none;
  font-size: 1.5rem;
}
a {
  color: black;
  text-decoration: none;
  text-decoration-color: white;
}
a:hover {
  color: grey;
  text-decoration: underline;
  text-underline-offset: 1rem;
  text-decoration-color: rgb(181, 181, 181);
}
.logo {
  font-size: 2rem;
}
.logo:hover {
  cursor: default;
}
```
