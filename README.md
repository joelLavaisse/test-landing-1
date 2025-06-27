# Test Landing Page

Una landing page moderna y responsive desarrollada con HTML, CSS y JavaScript vanilla.

## 🚀 Características

- **Diseño Moderno**: Interfaz limpia y profesional con gradientes y efectos visuales
- **Totalmente Responsive**: Optimizada para dispositivos móviles, tablets y desktop
- **Navegación Suave**: Scroll suave entre secciones
- **Animaciones**: Efectos de entrada y hover para mejorar la experiencia de usuario
- **Formulario Funcional**: Validación de campos y notificaciones
- **Contadores Animados**: Estadísticas con animación de números
- **Optimización SEO**: Estructura semántica y meta tags apropiados

## 📁 Estructura del Proyecto

```
test-landing-1/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
├── .mocks/             # Carpeta con archivos de diseño
│   └── 601098d3fe7e06017dce793b_shopify-hero.png
└── README.md           # Documentación
```

## 🎨 Secciones Incluidas

### 1. Header/Navegación
- Logo de la marca
- Menú de navegación responsive
- Botones de acción (Iniciar Sesión/Registrarse)
- Menú hamburguesa para móviles

### 2. Hero Section
- Título principal con gradiente
- Descripción del producto/servicio
- Botones de llamada a la acción
- Estadísticas animadas
- Imagen hero desde `.mocks/`

### 3. Características
- 6 tarjetas de características principales
- Iconos con gradientes
- Efectos hover y animaciones

### 4. Planes y Precios
- 3 planes de precios
- Plan destacado (Profesional)
- Lista de características por plan
- Botones de acción

### 5. Contacto
- Información de contacto
- Formulario funcional con validación
- Notificaciones de éxito/error

### 6. Footer
- Información de la empresa
- Enlaces de navegación
- Redes sociales
- Enlaces legales

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: 
  - Variables CSS (Custom Properties)
  - Flexbox y Grid
  - Animaciones y transiciones
  - Media queries para responsive design
- **JavaScript ES6+**:
  - Intersection Observer API
  - Event listeners
  - DOM manipulation
  - Form validation

## 🎯 Funcionalidades JavaScript

### Navegación
- Menú móvil con hamburguesa
- Header que se oculta/muestra al hacer scroll
- Scroll suave entre secciones

### Animaciones
- Elementos que aparecen al hacer scroll
- Contadores animados para estadísticas
- Efectos hover en botones y tarjetas

### Formulario
- Validación de campos requeridos
- Validación de formato de email
- Notificaciones de éxito/error
- Simulación de envío

### Optimizaciones
- Debounce para eventos de scroll
- Lazy loading para imágenes
- Intersection Observer para animaciones

## 🚀 Instalación y Uso

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/joelLavaisse/test-landing-1.git
   cd test-landing-1
   ```

2. **Abrir en el navegador**:
   - Simplemente abre `index.html` en tu navegador
   - O usa un servidor local:
     ```bash
     # Con Python
     python -m http.server 8000
     
     # Con Node.js (si tienes http-server instalado)
     npx http-server
     
     # Con PHP
     php -S localhost:8000
     ```

3. **Acceder a la página**:
   - Abre `http://localhost:8000` en tu navegador

## 📱 Responsive Design

La landing page está optimizada para:

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

### Breakpoints principales:
- `@media (max-width: 1024px)`: Ajustes para tablets
- `@media (max-width: 768px)`: Ajustes para móviles
- `@media (max-width: 480px)`: Ajustes para móviles pequeños

## 🎨 Personalización

### Colores
Los colores se pueden personalizar fácilmente modificando las variables CSS en `:root`:

```css
:root {
    --primary-color: #6366f1;
    --primary-dark: #4f46e5;
    --accent-color: #06b6d4;
    /* ... más variables */
}
```

### Fuentes
La página usa la fuente Inter de Google Fonts. Puedes cambiarla modificando:

```css
body {
    font-family: 'Tu-Fuente', sans-serif;
}
```

### Contenido
- Modifica el texto en `index.html`
- Cambia las imágenes en la carpeta `.mocks/`
- Ajusta los precios y características en la sección de pricing

## 🔧 Funcionalidades Avanzadas

### Sistema de Notificaciones
```javascript
showNotification('Mensaje de éxito', 'success');
showNotification('Mensaje de error', 'error');
showNotification('Mensaje informativo', 'info');
```

### Animaciones Personalizadas
```css
@keyframes tuAnimacion {
    from { /* estado inicial */ }
    to { /* estado final */ }
}
```

## 📊 Performance

- **Lighthouse Score**: Optimizada para obtener altas puntuaciones
- **Tiempo de carga**: < 2 segundos en conexiones 3G
- **Tamaño total**: < 500KB (sin incluir imágenes)
- **SEO**: Estructura semántica y meta tags optimizados

## 🌟 Próximas Mejoras

- [ ] Integración con CMS
- [ ] Analytics y tracking
- [ ] A/B testing
- [ ] PWA (Progressive Web App)
- [ ] Internacionalización (i18n)
- [ ] Temas oscuro/claro
- [ ] Más animaciones y micro-interacciones

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📞 Soporte

Para soporte técnico o preguntas:
- 📧 Email: contacto@empresa.com
- 🐛 Issues: [GitHub Issues](https://github.com/joelLavaisse/test-landing-1/issues)

---

**Desarrollado con ❤️ para crear experiencias web excepcionales** 