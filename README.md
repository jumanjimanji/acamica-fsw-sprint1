# Podcast Channel / Acámica - Full Stack Web - Sprint 1

En este proyecto debía construir un sitio web estático responsivo utilizando únicamente código HTML y CSS, en mi caso utilicé SASS como precompilador de CSS.

Desde el sitio vas a poder escuchar podcasts reales que estarán embebidos junto con imágenes y texto relacionados a su contenido. Trabajé con una visión mobile first, por lo que comencé por la vista mobile, y luego adopté la responsividad a pantallas más grandes.

El objetivo del proyecto es replicar un esquema laboral de un/a Front-End Developer.

## Responsive Design

Los breakpoints establecidos son:
- Mobile: 320px
- Tablet: 768px
- Desktop: 1024px



## Mantenimiento

Para modificar el contenido de los distintos archivos de estilos el comando del observador de SASS será:

```powershell
sass --watch src/style/scss/main.scss:src/style/css/style.css
```