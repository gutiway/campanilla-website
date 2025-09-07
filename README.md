# Mi Página Personal

Una página web moderna y atractiva para mostrar tu perfil personal, redes sociales, fotos, videos y lista de deseos.

## 🚀 Características

- **Diseño Responsive**: Se adapta perfectamente a todos los dispositivos
- **Animaciones Suaves**: Efectos visuales modernos sin ser abrumadores
- **Secciones Incluidas**:
  - Hero con foto de perfil animada
  - Enlaces a redes sociales
  - Galería de fotos con modal
  - Carrusel de videos
  - Lista de deseos de Amazon
- **Efectos Interactivos**: Hover effects, parallax, y animaciones de scroll

## 📝 Personalización

### 1. Información Personal
Edita el archivo `index.html` y cambia:
- **Nombre**: Línea 25 - `<h1 class="name">Tu Nombre</h1>`
- **Biografía**: Línea 26 - `<p class="bio">Desarrollador | Diseñador | Creador de contenido</p>`
- **Foto de perfil**: Línea 20 - Cambia la URL de la imagen placeholder

### 2. Redes Sociales
En las líneas 35-60, actualiza los enlaces:
```html
<a href="TU_CANAL_YOUTUBE" class="social-card youtube" target="_blank">
<a href="TU_INSTAGRAM" class="social-card instagram" target="_blank">
<a href="TU_TWITTER" class="social-card twitter" target="_blank">
<!-- etc... -->
```

### 3. Fotos de la Galería
Reemplaza las URLs placeholder en las líneas 70-95:
```html
<img src="URL_DE_TU_FOTO_1" alt="Descripción de la foto">
```

### 4. Videos del Carrusel
En las líneas 105-125, actualiza los títulos y agrega tus videos:
```html
<div class="video-placeholder">
    <i class="fas fa-play"></i>
    <p>Tu Video 1 - Título del video</p>
</div>
```

### 5. Lista de Deseos
En la línea 140, actualiza el enlace a tu lista de Amazon:
```html
<a href="TU_LISTA_AMAZON" class="wishlist-btn" target="_blank">
```

### 6. Colores y Estilos
Edita el archivo `styles.css` para personalizar:
- **Colores principales**: Líneas 15-16 (gradiente del hero)
- **Colores de redes sociales**: Líneas 180-186
- **Fuentes**: Línea 8 (cambia la fuente de Google Fonts)

## 🎨 Sugerencias de Mejoras

### Contenido Adicional
- **Sección de Habilidades**: Agrega una sección con tus habilidades técnicas
- **Proyectos**: Muestra tus proyectos más importantes
- **Testimonios**: Agrega comentarios de clientes o colegas
- **Blog**: Enlace a tu blog personal
- **Contacto**: Formulario de contacto

### Efectos Visuales
- **Partículas animadas**: Agrega partículas flotantes en el fondo
- **Cursor personalizado**: Cambia el cursor por uno personalizado
- **Modo oscuro**: Toggle para cambiar entre tema claro y oscuro
- **Sonidos**: Efectos de sonido sutiles en las interacciones

### Funcionalidades
- **Lazy loading**: Carga las imágenes solo cuando son visibles
- **PWA**: Convierte la página en una Progressive Web App
- **Analytics**: Agrega Google Analytics para estadísticas
- **SEO**: Optimiza para motores de búsqueda

## 📱 Responsive Design

La página está optimizada para:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Animaciones, gradientes, grid, flexbox
- **JavaScript**: Interactividad y efectos
- **Font Awesome**: Iconos
- **Google Fonts**: Tipografía

## 🚀 Cómo Usar

1. Descarga todos los archivos
2. Personaliza el contenido según tus necesidades
3. Reemplaza las imágenes placeholder con tus fotos
4. Actualiza los enlaces a tus redes sociales
5. Sube a tu servidor web o usa GitHub Pages

## 📄 Estructura de Archivos

```
WebInma/
├── index.html          # Página principal
├── styles.css          # Estilos y animaciones
├── script.js           # Funcionalidades JavaScript
└── README.md           # Este archivo
```

## 🎯 Próximos Pasos

1. **Personaliza el contenido** con tu información
2. **Agrega tus fotos** reales
3. **Configura los enlaces** a tus redes sociales
4. **Prueba en diferentes dispositivos**
5. **Optimiza las imágenes** para mejor rendimiento
6. **Agrega tu dominio** personalizado

¡Tu página personal está lista para impresionar! 🌟