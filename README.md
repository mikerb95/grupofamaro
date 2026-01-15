# Grupo FAMARO - Landing Page

Landing page profesional para Grupo FAMARO, un conglomerado empresarial con presencia en múltiples sectores estratégicos.

## 🎯 Sectores

- **Arquitectura**: Proyectos residenciales y comerciales con enfoque sostenible
- **Café**: Café de especialidad premium con comercio directo
- **Diseño**: Branding, identidad visual y experiencia de usuario
- **Oil**: Exploración, producción y servicios especializados
- **Gas & Energy**: Soluciones energéticas integrales y renovables

## 🚀 Características

- Diseño moderno y responsive
- Navegación suave y animaciones elegantes
- Secciones optimizadas para conversión
- Formulario de contacto funcional
- Compatible con todos los navegadores modernos
- Optimizado para SEO

## 📁 Estructura del Proyecto

```
grupofamaro/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidad JavaScript
└── README.md          # Documentación
```

## 🎨 Paleta de Colores

- **Primary**: #0f3460 (Azul oscuro)
- **Secondary**: #e94560 (Rosa/Rojo)
- **Accent**: #16213e (Azul profundo)
- **Background**: #f8f9fa (Gris claro)

## 💻 Uso

1. Abre `index.html` en tu navegador
2. Navega por las diferentes secciones
3. Personaliza el contenido según tus necesidades

## 🔧 Personalización

### Cambiar colores

Edita las variables CSS en `styles.css`:

```css
:root {
    --primary-color: #0f3460;
    --secondary-color: #e94560;
    --accent-color: #16213e;
}
```

### Modificar secciones

Edita el HTML en `index.html` para agregar o modificar secciones.

### Integrar backend

El formulario de contacto está preparado para integrarse con un backend. Descomenta y configura el código en `script.js`:

```javascript
fetch('/api/contact', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(data)
})
```

## 📱 Responsive

La landing page es completamente responsive y se adapta a:
- 📱 Mobile (< 640px)
- 📱 Tablet (640px - 968px)
- 💻 Desktop (> 968px)

## 🌟 Próximas Mejoras

- [ ] Integración con backend para formulario
- [ ] Galería de proyectos por sector
- [ ] Blog corporativo
- [ ] Sección de testimonios
- [ ] Integración con Google Analytics
- [ ] Optimización de imágenes reales

## 📄 Licencia

© 2025 Grupo FAMARO. Todos los derechos reservados.
