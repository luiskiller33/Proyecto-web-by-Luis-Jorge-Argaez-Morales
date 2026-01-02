

# Timeless - Full Stack E-commerce Ecosystem

Este repositorio centraliza la documentación y el acceso al ecosistema **Timeless**, una plataforma de comercio electrónico de moda de alto rendimiento. El proyecto está diseñado bajo una arquitectura desacoplada que separa la experiencia del cliente, la gestión administrativa y el procesamiento de datos en el servidor.

## 🚀 Descripción del Proyecto

Timeless no es solo una tienda en línea; es una solución integral que combina una estética moderna con herramientas de gestión robustas. El sistema permite a los usuarios navegar por catálogos dinámicos con experiencias visuales inmersivas, mientras que los administradores cuentan con un panel de control avanzado para el manejo de inventario, análisis de ventas y generación de reportes.

---

## 🛠️ Tecnologías Utilizadas

El proyecto emplea un stack tecnológico moderno centrado en la velocidad, la escalabilidad y la experiencia de usuario:

### Frontend & UI/UX (Cliente y Admin)

* **React (v18.2.0):** Base de la interfaz de usuario basada en componentes.
* **Vite:** Herramienta de construcción para un entorno de desarrollo ultrarrápido.
* **Tailwind CSS:** Framework de utilidades para un diseño responsivo y consistente.
* **Framer Motion:** Biblioteca para animaciones fluidas y transiciones de página.
* **Three.js & Postprocessing:** (Lado Cliente) Implementación de elementos visuales y efectos en 3D.
* **Lucide React & React Icons:** Paquetes de iconografía vectorial.

### Gestión de Estado y Datos

* **React Context API:** Manejo de estado global para el carrito de compras (`CartContext`) y el filtrado del catálogo (`CatalogContext`).
* **Axios:** Cliente HTTP para la comunicación con la API del Backend.
* **React Router DOM (v6):** Gestión de rutas dinámicas y navegación protegida.

### Funcionalidades de Negocio (Panel Admin)

* **Recharts:** Visualización de estadísticas de ventas y rendimiento.
* **jsPDF & xlsx:** Generación de reportes descargables en formato PDF y Excel.
* **React Quill:** Editor de texto enriquecido para descripciones detalladas de productos.

---

## ⚙️ Lógica de Funcionamiento

### 1. Plataforma del Cliente (Frontend)

La aplicación cliente está optimizada para la conversión y la retención:

* **Catálogo Inteligente:** Implementa un sistema de filtros avanzado por categoría, talla, género y colección. Los usuarios pueden alternar entre diferentes modos de vista (Grid, List, Blocks) cuya preferencia se persiste en el `localStorage`.
* **Gestión de Carrito:** La lógica permite manejar variaciones complejas, diferenciando productos no solo por ID, sino por combinaciones únicas de **talla y color**.
* **Experiencia de Usuario:** Incluye un sistema de "ScrollToTop" automático en la navegación y un cargador de marca (Loader) para asegurar una presentación impecable del contenido.
* **Análisis:** Integración nativa con **Microsoft Clarity** para el monitoreo del comportamiento del usuario en tiempo real.

### 2. Panel Administrativo (Admin Page)

Diseñado para la eficiencia operativa:

* **Seguridad:** Sistema de rutas protegidas que valida sesiones activas. La aplicación detecta automáticamente cuando una sesión ha expirado (Error 403) y redirige al usuario al login, limpiando los datos sensibles.
* **Control de Inventario:** Interfaz para el CRUD completo de productos, permitiendo acciones masivas y edición rápida de stock y estado de publicación.
* **Comunicación Segura:** Configuración de Axios con `withCredentials: true` para el manejo seguro de sesiones y cookies con el backend.

---

## 🔗 Repositorios del Proyecto

Puedes acceder a los componentes individuales del ecosistema a través de los siguientes enlaces:

1. **[Frontend Page](https://github.com/luiskiller33/frontendpage):** El portal orientado al cliente final, construido con React, Tailwind y Three.js.
2. **[Admin Panel](https://www.google.com/search?q=https://github.com/luiskiller33/paneladminpage):** La herramienta de gestión empresarial con reportes, estadísticas y control de inventario.
3. **[Backend Server](https://www.google.com/search?q=https://github.com/luiskiller33/backendserver):** API centralizada que gestiona la base de datos, autenticación y lógica de negocio (alojada en Render).

Contacto del desarrollador.
Correo:a21203109@alumnos.uady.mx
Telefono(whatsapp):+52-9993345067
