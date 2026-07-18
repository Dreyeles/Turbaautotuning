# 🚗 Turba Autotuning

Sitio web oficial de **Turba Autotuning** (Importadora y Taller Especialista de Consolas Multimedia, Audio, GPS y Cámaras de Retroceso), completamente remasterizado y optimizado utilizando **Astro**, **Bootstrap 5** y **CSS3 personalizado**.

🔗 **Sitio Web en Vivo:** [https://dreyeles.github.io/Turbaautotuning/](https://dreyeles.github.io/Turbaautotuning/)

---

## 🛠️ Tecnologías Utilizadas

* **Framework:** [Astro](https://astro.build/) (para generación de sitio estático rápido, carga óptima y SEO).
* **Estilos & Diseño:** CSS3 moderno (Glassmorphism, gradientes dinámicos y micro-interacciones) y [Bootstrap 5.3](https://getbootstrap.com/) (rejilla responsiva).
* **Iconografía:** [Bootstrap Icons](https://icons.getbootstrap.com/).
* **Formularios:** [Web3Forms API](https://web3forms.com/) (recepción de correos automática sin backend intermedio).
* **Integración Continua (CI/CD):** GitHub Actions para despliegue automático en GitHub Pages.

---

## ✨ Características Destacadas

* **Carrusel Premium de Trabajos:** Carrusel interactivo personalizado con control de indicadores (dots en forma de píldora neón), flechas con efecto de vidrio esmerilado, pausa inteligente al pasar el cursor y transiciones fluidas de desvanecimiento con efecto zoom en las imágenes.
* **Sección Ubícanos Optimizada (Grid 2 Columnas):** Panel izquierdo con información interactiva estructurada con iconos temáticos reactivos al pasar el cursor (hover neón) y panel derecho con la vista de fachada del taller, vinculando al mapa interactivo responsivo.
* **Diseño Responsivo Completo:** Adaptación impecable en dispositivos móviles, tablets y computadoras de escritorio.
* **Optimización WPO (Rendimiento):** Eliminación de cargas pesadas duplicadas (Mapas, Iframe de YouTube, Formularios) en la página principal para garantizar una carga ultrarrápida y un flujo de navegación lógico.

---

## 📂 Estructura del Proyecto

* `/src/components/`: Componentes reutilizables como la barra de navegación (`Navbar.astro`), el pie de página (`Footer.astro`) y las tarjetas de productos (`ProductCard.astro`).
* `/src/layouts/`: Estructura base del sitio (`BaseLayout.astro`) para mantener el mismo diseño y metadatos en todas las páginas.
* `/src/pages/`: Páginas y rutas del sitio web (`index.astro`, `nosotros.astro`, `ubicanos.astro`, `contactanos.astro` y las páginas de categorías de productos).
* `/src/styles/`: Hojas de estilo personalizadas (`styles.css`) con variables centralizadas y temas oscuros.
* `/public/`: Assets estáticos como imágenes y logotipos de productos.

---

## 🚀 Instrucciones de Desarrollo

Para ejecutar y probar el proyecto de forma local, asegúrate de tener instalado [Node.js](https://nodejs.org/).

### 1. Instalar dependencias
```bash
npm install
```

### 2. Iniciar servidor de desarrollo
```bash
npm run dev
```
La aplicación estará disponible en `http://localhost:4321`.

### 3. Compilar para producción
```bash
npm run build
```
Los archivos optimizados y estáticos se generarán en la carpeta `/dist/`, listos para ser desplegados en cualquier hosting estático (GitHub Pages, Netlify, Vercel, etc.).

---

## 👨‍💻 Autor / Desarrollador

Este sitio web fue diseñado, desarrollado y optimizado de forma integral por:

* **Nombre:** Drey E. Aymituma Julca
* **Rol Profesional:** Desarrollador Full Stack (Frontend, Backend & Bases de Datos)
* **LinkedIn:** [drey-aymituma-b2320a207](https://www.linkedin.com/in/drey-aymituma-b2320a207/)
* **GitHub Profile:** [@Dreyeles](https://github.com/Dreyeles)
* **Correo Electrónico:** [drewgamer681@gmail.com](mailto:drewgamer681@gmail.com)