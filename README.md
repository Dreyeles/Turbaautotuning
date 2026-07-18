# Turba Autotuning

Este es el sitio web oficial de **Turba Autotuning** (Importadora de Consolas Multimedia, Audio, GPS y Cámaras de Retroceso), completamente remasterizado y optimizado utilizando **Astro** y **Bootstrap 5**.

---

## 🛠️ Tecnologías Utilizadas

* **Framework:** [Astro](https://astro.build/) (para una velocidad de carga óptima y SEO impecable).
* **Estilos:** CSS3 personalizado y [Bootstrap 5.3](https://getbootstrap.com/) (para una estructura responsiva y moderna).
* **Iconos:** [Bootstrap Icons](https://icons.getbootstrap.com/).
* **Formularios:** Integrado con [Web3Forms](https://web3forms.com/) para envío de correos sin necesidad de servidor de backend.

---

## 📂 Estructura del Proyecto

* `/src/components/`: Componentes reutilizables como la barra de navegación (`Navbar.astro`), el pie de página (`Footer.astro`) y las tarjetas de productos (`ProductCard.astro`).
* `/src/layouts/`: Estructura base del sitio (`BaseLayout.astro`) para mantener el mismo diseño y metadatos en todas las páginas.
* `/src/pages/`: Páginas y rutas del sitio web (`index.astro`, `nosotros.astro`, `ubicanos.astro`, `contactanos.astro` y las páginas de categorías de productos).
* `/src/styles/`: Hojas de estilo personalizadas (`styles.css`) con variables centralizadas y temas modernos.
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
Los archivos optimizados y estáticos se generarán en la carpeta `/dist/`, listos para ser desplegados en cualquier hosting estático (Netlify, Vercel, GitHub Pages, etc.).