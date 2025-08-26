# 🚀 AppDelivery - Aplicación de Entrega de Comida

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)
[![Gulp](https://img.shields.io/badge/Gulp-4.0.2-red.svg)](https://gulpjs.com/)
[![Sass](https://img.shields.io/badge/Sass-1.37.5-pink.svg)](https://sass-lang.com/)

## 📱 Descripción de la Aplicación

**DeliveryApp** es una aplicación web moderna y responsive diseñada para conectar usuarios con restaurantes locales, permitiendo la búsqueda, selección y pedido de comida a domicilio. La aplicación ofrece una experiencia de usuario intuitiva y atractiva con un diseño profesional que se adapta a todos los dispositivos.

## 🌐 Demo en Vivo

**Visita el sitio web:** [cafeteria.app](https://cafeteria2025jebdev.netlify.app/)


## 📸 Capturas de Pantalla

![Vista Principal](build/img/cafeteria.png)
![Página del Menú](build/img/cafeteria2.png)
![Galería de Imágenes](build/img/cafeteria3.png)
![Página Nosotros](build/img/cafeteria4.png)
![Proceso del Café](build/img/cafeteria5.png)
![Formulario de Contacto](build/img/cafeteria6.png)
![Vista Móvil](build/img/cafeteria7.png)

### ✨ Características Principales

- 🔍 **Búsqueda Inteligente**: Sistema de búsqueda por restaurante y tipo de platillo
- 🏪 **Catálogo de Restaurantes**: Amplia selección de establecimientos gastronómicos
- ⭐ **Sistema de Calificaciones**: Evaluaciones y testimonios de usuarios
- 💳 **Múltiples Métodos de Pago**: Soporte para tarjeta y efectivo
- 📱 **Diseño Responsive**: Optimizado para móviles, tablets y desktop
- 🚚 **Sección de Repartidores**: Información para conductores interesados en trabajar

## 🛠️ Funcionalidad y Rendimiento

### Funcionalidades Implementadas

1. **Header de Navegación**
   - Logo de la aplicación
   - Enlaces de autenticación (Iniciar Sesión, Crear Cuenta)
   - Registro de restaurantes

2. **Formulario de Búsqueda**
   - Campo de búsqueda por restaurante
   - Filtro por tipo de platillo
   - Interfaz intuitiva con imagen ilustrativa

3. **Sección de Pasos**
   - Explicación visual del proceso de pedido
   - Diseño atractivo con imágenes paso a paso

4. **Testimonios de Usuarios**
   - Opiniones reales de clientes satisfechos
   - Sistema de calificación con estrellas
   - Diseño en grid responsive

5. **Restaurantes Favoritos**
   - Catálogo visual de establecimientos
   - Información detallada de cada restaurante
   - Calificaciones y descripciones

6. **Sección de Repartidores**
   - Información para conductores
   - Oportunidades de trabajo
   - Enlaces de contacto

7. **Descarga de Aplicación**
   - Enlaces a tiendas de aplicaciones
   - Soporte para iOS y Android
   - Diseño atractivo con mockups

8. **Footer Completo**
   - Información de la empresa
   - Navegación adicional
   - Datos de contacto

### Rendimiento y Optimización

- **Build Process**: Automatizado con Gulp para máxima eficiencia
- **Optimización de Imágenes**: Compresión automática y formatos modernos (WebP, AVIF)
- **CSS Optimizado**: Minificación y autoprefixer para compatibilidad
- **Source Maps**: Para desarrollo y debugging eficiente
- **Responsive Design**: CSS Grid y Flexbox para layouts modernos

## 🚀 Tecnologías Utilizadas

### Frontend
- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos modernos con Grid y Flexbox
- **Sass/SCSS**: Preprocesador CSS con arquitectura modular
- **BEM Methodology**: Metodología de nomenclatura CSS escalable

### Build Tools & Development
- **Gulp 4**: Automatización de tareas de build
- **Sass**: Compilación de SCSS a CSS
- **PostCSS**: Post-procesamiento de CSS
- **Autoprefixer**: Compatibilidad automática entre navegadores
- **CSSNano**: Minificación y optimización de CSS
- **Source Maps**: Mapeo de código para debugging

### Optimización de Imágenes
- **Gulp Imagemin**: Compresión automática de imágenes
- **Gulp WebP**: Conversión a formato WebP para mejor rendimiento
- **Gulp AVIF**: Conversión a formato AVIF para máxima compresión

### Fuentes y Tipografía
- **Google Fonts**: Fuente Roboto para excelente legibilidad
- **Iconografía**: SVGs optimizados y escalables

## 📁 Estructura del Proyecto

```
DeliveryApp/
├── src/
│   ├── scss/
│   │   ├── app.scss
│   │   ├── base/
│   │   ├── descargar/
│   │   ├── favoritos/
│   │   ├── footer/
│   │   ├── formulario/
│   │   ├── header/
│   │   ├── pasos/
│   │   ├── repartidores/
│   │   └── testimoniales/
│   └── img/
├── build/
├── gulpfile.js
├── package.json
└── index.html
```

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js (versión 14 o superior)
- npm o yarn

### Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tu-usuario/DeliveryApp.git
   cd DeliveryApp
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Ejecutar en modo desarrollo**
   ```bash
   npm run dev
   ```

### Scripts Disponibles

- `npm run dev`: Inicia el servidor de desarrollo con Gulp
- `gulp css`: Compila solo los archivos SCSS
- `gulp imagenes`: Optimiza las imágenes
- `gulp versionWebp`: Convierte imágenes a formato WebP
- `gulp versionAvif`: Convierte imágenes a formato AVIF

## 🎨 Características de Diseño

- **Metodología BEM**: Nomenclatura CSS escalable y mantenible
- **Arquitectura SCSS Modular**: Organización por componentes y secciones
- **Diseño Responsive**: Mobile-first approach con breakpoints optimizados
- **Sistema de Grid**: CSS Grid para layouts complejos y flexibles
- **Paleta de Colores**: Esquema de colores profesional y accesible
- **Tipografía**: Jerarquía visual clara y legible

## 📱 Compatibilidad de Navegadores

- Chrome (última versión)
- Firefox (última versión)
- Safari (última versión)
- Edge (última versión)
- Navegadores móviles (iOS Safari, Chrome Mobile)

## 🔧 Configuración del Entorno

El proyecto incluye configuración automática para:
- Autoprefixer con soporte para navegadores modernos
- Source maps para desarrollo eficiente
- Optimización automática de imágenes
- Compilación en tiempo real de SCSS

## 📈 Métricas de Rendimiento

- **Tiempo de Carga**: Optimizado para carga rápida
- **SEO**: Estructura HTML semántica y accesible
- **Accesibilidad**: Cumple estándares WCAG
- **Performance**: Imágenes optimizadas y CSS minificado

## 🤝 Contribuir

Las contribuciones son bienvenidas. Para contribuir:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia ISC. Ver el archivo `LICENSE` para más detalles.

## 👨‍💻 Autor del Proyecto

**JEB$DEV de Javier Berchtold**

- **Desarrollador Full Stack**
- **Especialista en Frontend y UX/UI**
- **Experto en metodologías CSS modernas**
- **Apasionado por la optimización y rendimiento web**

### Contacto
- **GitHub**: [@tu-usuario](https://github.com/tu-usuario)
- **Portfolio**: [javierberchtold.dev](https://javierberchtold.dev)
- **Email**: contacto@javierberchtold.dev

## 🙏 Agradecimientos

- Comunidad de desarrolladores web
- Contribuidores de las librerías utilizadas
- Usuarios que han probado y dado feedback
- Equipo de diseño y UX

---

⭐ **Si te gusta este proyecto, ¡no olvides darle una estrella en GitHub!**

---

*Desarrollado con ❤️ por JEB$DEV*
