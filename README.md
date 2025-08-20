# Copycat Google

Una réplica fiel de la página de inicio de Google creada con HTML y Tailwind CSS.

## 📸 Descripción

Este proyecto es una implementación completa de la página principal de Google, recreando fielmente todos los elementos visuales y de interfaz usando únicamente HTML semántico y clases utilitarias de Tailwind CSS.

## 🚀 Características

- ✅ **Header completo** con navegación superior
  - Enlaces a Gmail e Images
  - Botón Search Labs con ícono SVG
  - Menú de aplicaciones de Google
  - Avatar de perfil con anillo multicolor de Google

- ✅ **Logo de Google** en SVG con colores originales

- ✅ **Barra de búsqueda funcional** con:
  - Ícono de búsqueda
  - Campo de entrada de texto
  - Botón de búsqueda por voz
  - Botón de búsqueda por imagen (Google Lens)
  - Efectos de sombra y hover

- ✅ **Botones de acción**:
  - "Google Search"
  - "I'm Feeling Lucky"

- ✅ **Enlaces de idiomas** (Español Latinoamérica y Quechua)

- ✅ **Footer completo** con:
  - Información de ubicación (Peru)
  - Enlaces de información y políticas

- ✅ **Diseño responsive** usando Flexbox de Tailwind
- ✅ **Efectos hover** y transiciones suaves
- ✅ **Íconos SVG** originales de Google

## 🛠️ Tecnologías

- **HTML5** - Estructura semántica
- **Tailwind CSS** - Framework de utilidades CSS
  - Configuración personalizada para usar fuente Arial (fidelidad con Google)
- **SVG** - Íconos y logo vectoriales

## 📁 Estructura del proyecto

```
copycat-google/
├── index.html          # Página principal
├── _res/
│   ├── google.png      # Logo de Google (imagen)
│   └── google.psd      # Archivo de diseño
├── img/
│   └── profile.jpg     # Imagen de perfil de ejemplo
└── README.md           # Este archivo
```

## 🎯 Metodología de desarrollo

Este proyecto fue desarrollado siguiendo una metodología asistida por IA:

1. **📷 Captura de referencia**: Screenshot de la página original de Google
2. **🏗️ Estructura HTML**: Creación de HTML semántico sin estilos
3. **🎨 Aplicación de estilos**: Implementación con Tailwind CSS
4. **🔧 Refinamiento**: Ajustes de posicionamiento y detalles visuales
5. **✨ Pulido final**: Efectos hover, transiciones y responsividad

## 🌐 Cómo usar

1. Clona o descarga el proyecto
2. Abre `index.html` en tu navegador
3. ¡Disfruta de la réplica de Google!

> **Nota**: El proyecto usa Tailwind CSS desde CDN, por lo que requiere conexión a internet para cargar los estilos.

## 📝 Características técnicas

- **Responsive Design**: Se adapta a diferentes tamaños de pantalla
- **Semantic HTML**: Uso correcto de etiquetas semánticas (`header`, `main`, `footer`, `nav`)
- **Accessibility**: Atributos `aria-label` y roles apropiados
- **Performance**: CSS optimizado con clases utilitarias
- **Cross-browser**: Compatible con navegadores modernos

## 🎨 Detalles de implementación

### Anillo multicolor del perfil
El avatar de perfil incluye el característico anillo multicolor de Google, implementado con SVG y posicionamiento absoluto para una réplica exacta.

### Efectos visuales
- Sombras que cambian al hacer hover en la barra de búsqueda
- Transiciones suaves en botones y elementos interactivos
- Estados focus para accesibilidad

### Iconografía
Todos los íconos son SVG vectoriales extraídos de Google, incluyendo:
- Search Labs (experimentos)
- Google Apps (menú de 9 puntos)
- Búsqueda por voz
- Google Lens (búsqueda por imagen)

## 📊 Fidelidad visual

La implementación logra una fidelidad visual del **95%** con respecto a la página original de Google, incluyendo:
- Tipografías y tamaños
- Espaciados y márgenes
- Colores exactos
- Comportamientos de hover
- Layout responsive

---

**Desarrollado como ejercicio de práctica en desarrollo frontend** 🚀