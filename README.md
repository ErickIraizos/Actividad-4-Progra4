# Interfaz Web Accesible

Una aplicación React moderna diseñada específicamente para usuarios con discapacidad visual, cumpliendo con los estándares WCAG 2.1 nivel AA.

## 🎯 Características de Accesibilidad

### Navegación por Teclado
- **Navegación completa**: Usa Tab para moverte entre elementos
- **Atajos de teclado**: Enter para activar, Escape para cerrar
- **Indicadores de foco visibles**: Contorno azul claro para elementos enfocados
- **Sin trampas de foco**: Navegación fluida sin puntos de bloqueo

### Compatibilidad con Lectores de Pantalla
- **Etiquetas ARIA apropiadas**: Roles, estados y propiedades descriptivas
- **Estructura semántica**: Encabezados, landmarks y navegación lógica
- **Anuncios dinámicos**: Mensajes de estado y errores anunciados automáticamente
- **Compatibilidad**: Optimizado para NVDA, JAWS, VoiceOver y otros lectores

### Contraste y Visibilidad
- **Contraste 4.5:1 mínimo**: Cumple con WCAG 2.1 AA
- **Múltiples temas**: Modo claro, oscuro y alto contraste
- **Texto escalable**: Hasta 200% sin pérdida de funcionalidad
- **Indicadores visuales**: Iconos y colores complementarios al texto

### Formularios Accesibles
- **Validación en tiempo real**: Mensajes de error claros y descriptivos
- **Etiquetas asociadas**: Cada campo tiene su etiqueta correspondiente
- **Mensajes de ayuda**: Descripciones adicionales para campos complejos
- **Navegación lógica**: Orden de tabulación coherente

## 🚀 Instalación

### Prerrequisitos
- Node.js (versión 14 o superior)
- npm o yarn

### Pasos de instalación

1. **Clonar el repositorio**
   ```bash
   git clone <url-del-repositorio>
   cd interfaz-accesible
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Iniciar el servidor de desarrollo**
   ```bash
   npm start
   ```

4. **Abrir en el navegador**
   ```
   http://localhost:3000
   ```

## 🛠️ Tecnologías Utilizadas

- **React 18**: Framework principal
- **React Aria**: Librería de accesibilidad de Adobe
- **CSS3**: Estilos con enfoque en accesibilidad
- **HTML5**: Marcado semántico

## 📋 Estructura del Proyecto

```
src/
├── components/
│   ├── Navigation.js      # Navegación principal accesible
│   ├── Hero.js           # Sección de bienvenida
│   ├── Features.js       # Características de accesibilidad
│   ├── ContactForm.js    # Formulario de contacto
│   ├── Footer.js         # Pie de página
│   └── *.css            # Estilos específicos de componentes
├── App.js               # Componente principal
├── App.css             # Estilos globales
├── index.js            # Punto de entrada
└── index.css           # Estilos base
```

## 🎮 Cómo Usar

### Navegación por Teclado

1. **Navegación básica**:
   - `Tab`: Mover al siguiente elemento
   - `Shift + Tab`: Mover al elemento anterior
   - `Enter`: Activar botones y enlaces
   - `Escape`: Cerrar modales o cancelar acciones

2. **Atajos específicos**:
   - `Home`: Ir a la página de inicio
   - `End`: Ir a la página de contacto
   - `Ctrl + Enter`: Enviar formulario

### Funciones de Accesibilidad

1. **Cambiar contraste**:
   - Haz clic en el botón 🎨 en la navegación
   - O usa las preferencias del sistema

2. **Cambiar tamaño de texto**:
   - Haz clic en el botón 🔍 en la navegación
   - O usa Ctrl + "+" / Ctrl + "-" del navegador

3. **Navegación por landmarks**:
   - Usa las teclas de navegación de tu lector de pantalla
   - Los landmarks están marcados con roles ARIA apropiados

## 🧪 Pruebas de Accesibilidad

### Herramientas Recomendadas

1. **Lighthouse**: Auditoría de accesibilidad
   ```bash
   npm run build
   # Luego ejecutar Lighthouse en el build
   ```

2. **axe-core**: Pruebas automatizadas
   ```bash
   npm install --save-dev axe-core
   ```

3. **Lectores de pantalla**:
   - **NVDA** (Windows, gratuito)
   - **JAWS** (Windows, comercial)
   - **VoiceOver** (macOS, incluido)
   - **TalkBack** (Android, incluido)

### Checklist de Accesibilidad

- [ ] Contraste de color 4.5:1 mínimo
- [ ] Navegación completa por teclado
- [ ] Etiquetas ARIA apropiadas
- [ ] Estructura de encabezados lógica
- [ ] Texto alternativo para imágenes
- [ ] Mensajes de error descriptivos
- [ ] Sin trampas de foco
- [ ] Texto escalable hasta 200%
- [ ] Compatibilidad con lectores de pantalla

## 📊 Cumplimiento WCAG 2.1 AA

### Principio 1: Perceptible
- ✅ **1.1.1**: Contenido no textual
- ✅ **1.3.1**: Información y relaciones
- ✅ **1.4.3**: Contraste (mínimo)
- ✅ **1.4.4**: Redimensionamiento de texto

### Principio 2: Operable
- ✅ **2.1.1**: Teclado
- ✅ **2.1.2**: Sin trampas de teclado
- ✅ **2.4.1**: Bloques de navegación
- ✅ **2.4.2**: Título de página
- ✅ **2.4.3**: Orden de foco
- ✅ **2.4.4**: Propósito de enlaces

### Principio 3: Comprensible
- ✅ **3.1.1**: Idioma de la página
- ✅ **3.2.1**: Al enfocar
- ✅ **3.2.2**: Al introducir datos
- ✅ **3.3.1**: Identificación de errores
- ✅ **3.3.2**: Etiquetas o instrucciones

### Principio 4: Robusto
- ✅ **4.1.1**: Análisis
- ✅ **4.1.2**: Nombre, función, valor

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

### Guías de Contribución

- Mantén el enfoque en accesibilidad
- Prueba con lectores de pantalla
- Verifica la navegación por teclado
- Asegúrate de que el contraste sea adecuado
- Documenta cualquier nueva característica de accesibilidad

## 📝 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📞 Contacto

- **Email**: accesibilidad@ejemplo.com
- **Proyecto**: [GitHub Repository](https://github.com/tu-usuario/interfaz-accesible)

## 🙏 Agradecimientos

- [React Aria](https://react-spectrum.adobe.com/react-aria/) por las herramientas de accesibilidad
- [WCAG 2.1 Guidelines](https://www.w3.org/WAI/WCAG21/quickref/) por los estándares
- Comunidad de accesibilidad web por las mejores prácticas

---

**Nota**: Esta interfaz está diseñada como un ejemplo educativo de accesibilidad web. Para uso en producción, asegúrate de realizar pruebas exhaustivas con usuarios reales y tecnologías asistivas. 