# CAPIBARES 17 🦫🦫🦫 (los mas gossu)

## Integrantes del grupo

| N°  | Nombre del integrante | Parte desarrollada                                    |
| --- | --------------------- | ----------------------------------------------------- |
| 1   | Yojhan Huanca         | Consumo de API TMDB e interfaz de peliculas populares |
| 2   | Anderson rivera       | lo mismo que el de arriba y que el de abajo           |
| 3   | NCarlos carbajal      | consumo de apis y renderizado                         |

---

# Reporte Individual - CineSpoilerS

## Integrante

**Nombre:** Yojhan Huanca  
**Proyecto:** CineSpoilerS  
**Parte desarrollada:** Consumo de API TMDB e interfaz de peliculas populares

## Descripcion de mi trabajo

En esta parte del proyecto desarrolle la conexion con la API de TMDB para obtener peliculas populares y mostrarlas en una interfaz web creada con React, TypeScript, Vite, Tailwind CSS y componentes estilo shadcn/ui.

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

## Repositorio de mi parte

https://github.com/yojhanHuanca/CinnSin

## Integrante

**Nombre:** Anderson Rivera
**Proyecto:** CineSpoilerS  
**Parte desarrollada:** Consumo de API TMDB e interfaz de peliculas populares

# Descripcion

CineSpoilerS es una app web de películas que consume la API de The Movie Database (TMDB) para mostrar información actualizada de estrenos, detalles y tendencias.

## Tecnologías usadas

- React
- Tailwind CSS
- shadcn/ui
- Axios
- TMDB API

## Instalación

```bash
cd cinespoilers3
npm install
npm run dev
```

## Estructura del proyecto

- `src/`
  - `components/` - componentes UI reutilizables
  - `pages/` - pantallas principales
  - `services/` - llamadas a API y lógica de datos
  - `types/` - tipos TypeScript
  - `lib/` - utilidades compartidas
- `public/` - activos estáticos
- `.env` - variables de entorno, clave TMDB
- `vite.config.ts` - configuración de Vite

## Capturas

A continuación se presentan las capturas en orden, con títulos claros y profesionales:

1. **Servidor corriendo**
   ![Servidor corriendo](capturas/corriendo.png)

2. **Limpieza del proyecto**
   ![Limpieza del proyecto](capturas/limpieza.png)

3. **Instalar Tailwind**
   ![Instalar Tailwind](capturas/instalartailwind.png)

4. **Instalar y probar shadcn/ui**
   ![Instalar shadcn/ui](capturas/instalarshadcn.png)
   ![Instalar shadcn/ui](capturas/instalarshadcn3.png)
5. **Configurar alias**
   ![Configurar alias](capturas/configuraralias.png)

   ![Configuración alias 2](capturas/configuracionalias2.png)

6. **Instalar y configurar axios**
   ![Configurar Axios](capturas/configuraraxios.png)
   ![Configurar Axios](capturas/instalaraxios.png)
7. **Mostrar datos en consola**
   ![Mostrar en consola](capturas/mostrarenconsola.png)
8. **Captura general**
   ![Captura general](capturas/image.png)

## Configuración de API

1. Crea un archivo `.env` en la raíz del proyecto.
2. Añade la clave de TMDB:

```env
VITE_TMDB_API_KEY=tu_clave_tmdb_aqui
```

3. Reinicia el servidor de desarrollo si está en ejecución.

## Integrante

**Nombre:** Carlos Carbajal
**Proyecto:** CineSpoilerS  
**Parte desarrollada:** Consumo de API TMDB e interfaz de peliculas populares

# Descripcion

> E-commerce de tickets de cine construido con React 19 + TypeScript + Vite. Base escalable para un proyecto real de venta de entradas.
> Proyecto educativo — Lab 11 · 2026

## 🛠️ Tech Stack

| Tecnología            | Uso                               |
| --------------------- | --------------------------------- |
| React 19 + TypeScript | UI y tipado                       |
| Vite                  | Bundler y dev server              |
| Tailwind CSS v4       | Estilos utilitarios               |
| shadcn/ui             | Componentes UI                    |
| Axios                 | HTTP client                       |
| React Router v6       | Navegación                        |
| Zustand               | Estado global (carrito)           |
| TMDB API              | Datos de películas en tiempo real |

---

## 🚀 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/cinespoilers/cinespoilers.git
cd cinespoilers

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev
```

## 📸 Evidencias

### 1. Proyecto creado

![proyecto_creado](capturas/proyecto_creado.png)

### 2. Inicio limpio

![inicio_limpio](capturas/inicio_limpio.png)

### 3. Instalar Tailwind CSS

![tailwindcss](capturas/tailwindcss.png)

### 4. Configurar alias

![configurar_alias](capturas/configurar_alias.png)

### 5. Instalar shadcn

![shadcss](capturas/shadcss.png)

### 6. Botón shadcn

![button](capturas/button.png)

### 7. Configurar shadcn

![configurar_shadcn](capturas/Configurar%20shadcn.png)

### 8. Instalar y configurar Axios

![axios](capturas/Instalar%20y%20configurar%20Axios%20.png)

### 9. Fetching de datos

![fetching](capturas/Fetching%20de%20datos.png)

### 10. Mostrar por consola

![consola](capturas/Mostrar%20por%20consola.png)

### 11. Renderizado

![renderizado](capturas/renderizadocarbajal.png)
