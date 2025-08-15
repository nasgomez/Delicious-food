# 🍽️ Delias Food Restaurant - Sitio Web

Una réplica completa y moderna del sitio web de Delias Food Restaurant con diseño responsivo y funcionalidades interactivas.

## ✨ Características

- **Diseño Moderno**: Interfaz elegante y profesional con gradientes y sombras
- **Totalmente Responsivo**: Se adapta perfectamente a todos los dispositivos
- **Navegación Suave**: Scroll suave entre secciones
- **Menú Móvil**: Navegación hamburguesa para dispositivos móviles
- **Animaciones**: Efectos de aparición y hover atractivos
- **Contadores Animados**: Estadísticas que se animan al hacer scroll
- **Efectos Interactivos**: Botones con efecto ripple y hover effects
- **Optimizado**: Lazy loading de imágenes y rendimiento optimizado
- **Sistema de Autenticación**: Modales interactivos para login, registro y recuperación de contraseña
- **Dashboard del Restaurante**: Sistema completo de gestión con roles específicos

## 🚀 Instalación y Uso

### Opción 1: Abrir directamente
1. Simplemente abre el archivo `index.html` en tu navegador web
2. ¡Listo! El sitio web funcionará completamente

### Opción 2: Servidor local (recomendado)
1. Instala un servidor local como Live Server en VS Code
2. O usa Python: `python -m http.server 8000`
3. Abre `http://localhost:8000` en tu navegador

### Opción 3: Deploy en Netlify
1. Sube los archivos a GitHub
2. Conecta tu repositorio a Netlify
3. ¡Deploy automático!

## 📁 Estructura del Proyecto

```
delicious_food/
├── index.html          # Página principal HTML
├── nosotros.html       # Página Nosotros
├── servicios.html      # Página Servicios
├── menu.html           # Página Menú
├── contacto.html       # Página Contacto
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidad JavaScript
├── netlify.toml        # Configuración Netlify
├── README.md           # Este archivo
└── auth/               # Sistema de Autenticación
    ├── login.html      # Página de Login
    ├── olvido_contrasena.html  # Recuperar Contraseña
    └── registrate.html # Crear Cuenta
└── dashboard/          # Sistema de Dashboard
    ├── index.html      # Dashboard Principal
    ├── admin/          # Dashboard Administrador
    ├── chef/           # Dashboard Chef
    ├── waiter/         # Dashboard Mesero
    └── delivery/       # Dashboard Delivery
```

## 🎨 Tecnologías Utilizadas

- **HTML5**: Estructura semántica y accesible
- **CSS3**: Estilos modernos con Flexbox y Grid
- **JavaScript ES6+**: Funcionalidad interactiva
- **Font Awesome**: Iconos profesionales
- **Google Fonts**: Tipografía Poppins
- **Unsplash**: Imágenes de alta calidad

## 📱 Páginas del Sitio

### 🏠 **Página Principal (index.html)**
1. **Header**: Navegación fija con menú hamburguesa
2. **Hero**: Sección principal con llamadas a la acción
3. **Platos Destacados**: Grid de platos con imágenes y descripciones
4. **Historia**: Información del restaurante con estadísticas
5. **Servicios**: Tarjetas de servicios ofrecidos
6. **CTA**: Llamada a la acción para reservas
7. **Footer**: Información de contacto y enlaces

### 👥 **Página Nosotros (nosotros.html)**
1. **Historia Detallada**: Información completa del restaurante
2. **Valores**: Principios que guían la empresa
3. **Equipo**: Perfiles de chefs y personal
4. **Estadísticas**: Números y logros
5. **Premios**: Reconocimientos y logros

### 🛠️ **Página Servicios (servicios.html)**
1. **Reservaciones**: Sistema de reservas online
2. **Delivery**: Servicio a domicilio
3. **Eventos**: Organización de eventos privados
4. **Catering**: Servicio profesional de catering
5. **Servicios Adicionales**: Sommelier, postres, etc.
6. **Horarios**: Información de disponibilidad

### 🍽️ **Página Menú (menu.html)**
1. **Filtros**: Categorías de platos (Entradas, Principales, Mariscos, etc.)
2. **Menú Completo**: Todos los platos con precios y descripciones
3. **Menú del Día**: Platos especiales diarios
4. **Tags**: Información dietética y características

### 📞 **Página Contacto (contacto.html)**
1. **Información de Contacto**: Ubicación, teléfono, email, horarios
2. **Formulario**: Formulario de contacto completo
3. **Mapa**: Ubicación en Google Maps
4. **FAQ**: Preguntas frecuentes expandibles
5. **Redes Sociales**: Enlaces a redes sociales

### 🔐 **Sistema de Autenticación (auth/)**
1. **Modal de Login**: Formulario de inicio de sesión integrado en la página principal
2. **Página de Login**: Formulario completo con opciones sociales y enlaces de navegación
3. **Recuperar Contraseña**: Formulario para restablecer contraseña olvidada
4. **Crear Cuenta**: Formulario de registro con validaciones y términos
5. **Características**: Modales centrados, efectos visuales, responsive design

### 🎛️ **Sistema de Dashboard (dashboard/)**
1. **Dashboard Principal**: Selección de roles y estadísticas generales del restaurante
2. **Dashboard Administrador**: Gestión completa, reportes, inventario y configuración
3. **Dashboard Chef**: Control de pedidos, menús del día y gestión de cocina
4. **Dashboard Mesero**: Gestión de mesas, pedidos en vivo y atención al cliente
5. **Dashboard Delivery**: Control de entregas, optimización de rutas y seguimiento
6. **Características**: Interfaz moderna, datos en tiempo real, responsive design

## 🔧 Personalización

### Cambiar Colores
Edita las variables CSS en `styles.css`:
```css
:root {
    --primary-color: #e74c3c;
    --secondary-color: #c0392b;
    --dark-color: #2c3e50;
}
```

### Cambiar Imágenes
Reemplaza las URLs de Unsplash en `index.html` con tus propias imágenes.

### Modificar Contenido
Edita el texto en `index.html` según tus necesidades.

## 🌟 Funcionalidades JavaScript

- **Menú Móvil**: Toggle del menú hamburguesa
- **Scroll Suave**: Navegación entre secciones
- **Animaciones**: Efectos de aparición al hacer scroll
- **Contadores**: Animación de estadísticas
- **Efectos Hover**: Transformaciones en tarjetas
- **Botón Ripple**: Efecto de onda en botones
- **Scroll to Top**: Botón para volver arriba
- **Header Dinámico**: Cambios de estilo al hacer scroll

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: < 480px

## 🚀 Optimizaciones

- **Lazy Loading**: Imágenes se cargan cuando son visibles
- **CSS Optimizado**: Estilos eficientes y reutilizables
- **JavaScript Modular**: Código organizado y mantenible
- **Performance**: Animaciones optimizadas con CSS transforms

## 📞 Soporte

Si tienes alguna pregunta o necesitas ayuda para personalizar el sitio:

1. Revisa el código comentado
2. Modifica los estilos en `styles.css`
3. Ajusta la funcionalidad en `script.js`

## 📄 Licencia

Este proyecto es de uso libre. Puedes modificarlo y usarlo para tus propios proyectos.

## 🎯 Próximas Mejoras

- [ ] Formulario de reservas funcional
- [ ] Galería de imágenes con lightbox
- [ ] Sistema de menú dinámico
- [ ] Integración con APIs de pago
- [ ] Chat en vivo
- [ ] Sistema de reseñas

---

**¡Disfruta tu nuevo sitio web de restaurante! 🎉**
