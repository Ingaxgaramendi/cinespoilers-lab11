# Reporte del Proyecto Grupal

## Integrantes del grupo

| N° | Nombre del integrante | Parte desarrollada |
|---|---|---|
| 1 | Yojhan Huanca | Consumo de API TMDB e interfaz de peliculas populares |
| 2 | Nombre del integrante 2 | Describir su parte |
| 3 | Nombre del integrante 3 | Describir su parte |

---

# Reporte Individual - CineSpoilerS

## Integrante

**Nombre:** Yojhan Huanca  
**Proyecto:** CineSpoilerS  
**Parte desarrollada:** Consumo de API TMDB e interfaz de peliculas populares

## Descripcion de mi trabajo

En esta parte del proyecto desarrolle la conexion con la API de TMDB para obtener peliculas populares y mostrarlas en una interfaz web creada con React, TypeScript, Vite, Tailwind CSS y componentes estilo shadcn/ui.

La aplicacion permite visualizar peliculas con su poster, titulo, fecha de estreno, calificacion, idioma, votos y resumen. Tambien se implementaron estados de carga y error para mejorar la experiencia del usuario.

## Tecnologias usadas

- React
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- Axios
- Lucide React
- TMDB API

## Actividades realizadas

## 1. Creacion del proyecto

Se creo el proyecto base usando React, TypeScript y Vite.

![Creacion del proyecto](https://github.com/yojhanHuanca/CinnSin/raw/main/docs/01-nombre-del-pro.png)

## 2. Limpieza inicial

Se eliminaron archivos innecesarios del template inicial para trabajar con una estructura mas limpia.

![Limpieza inicial](https://github.com/yojhanHuanca/CinnSin/raw/main/docs/02-limpiesa.png)

## 3. Configuracion de Tailwind CSS

Se configuro Tailwind CSS para manejar los estilos de la aplicacion.

![Configuracion de Tailwind](https://github.com/yojhanHuanca/CinnSin/raw/main/docs/03-confi-talwin.png)

## 4. Configuracion del alias @

Se configuro el alias @ para importar archivos desde la carpeta src de forma mas ordenada.

![Configuracion del alias](https://github.com/yojhanHuanca/CinnSin/raw/main/docs/04-confi%40.png)

## 5. Configuracion de shadcn/ui

Se agrego y probo el componente Button como parte de la configuracion de componentes reutilizables.

![Boton shadcn](https://github.com/yojhanHuanca/CinnSin/raw/main/docs/05-boton..png)

## 6. Conexion con TMDB

Se instalo Axios y se configuraron las variables de entorno para consumir la API de TMDB.

Variables usadas:

    VITE_TMDB_BASE_URL=https://api.themoviedb.org/3
    VITE_TMDB_API_TOKEN=token_de_tmdb

Se valido en consola que la API devolviera correctamente el arreglo de peliculas populares.

![Peliculas en consola](https://github.com/yojhanHuanca/CinnSin/raw/main/docs/06-tmdb-movies-console.png)

## 7. Interfaz final

Se creo una interfaz visual para mostrar las peliculas populares en tarjetas responsive.

Cada tarjeta muestra:

- Poster de la pelicula
- Titulo
- Fecha de estreno
- Calificacion
- Idioma
- Cantidad de votos
- Resumen corto

![Interfaz final](https://github.com/yojhanHuanca/CinnSin/raw/main/docs/07-tmdb-movies-ui.png)

## Archivos principales trabajados

    src/
      App.tsx
      services/
        tmdb.ts
      lib/
        axios.ts
        utils.ts
      components/
        ui/
          button.tsx
          card.tsx
          badge.tsx

## Funcionalidades implementadas

- Consumo de peliculas populares desde TMDB.
- Configuracion de Axios.
- Uso de variables de entorno.
- Renderizado de peliculas en tarjetas.
- Diseño responsive.
- Estado de carga.
- Estado de error.
- Boton para actualizar la informacion.
- Interfaz oscura con estilo cinematografico.

## Comandos usados

    npm install
    npm run dev
    npx tsc -b

## Repositorio de mi parte

https://github.com/yojhanHuanca/CinnSin
