# ROSITA Oruro - Ferretería Consolidada

## 📁 Estructura del Proyecto

```
ferreteria1/
├── index.html          # Archivo HTML principal (único)
├── css/
│   └── styles.css      # Estilos consolidados
├── img/                # Carpeta para imágenes locales
└── stitch/             # Carpetas originales (pueden ser eliminadas)
    ├── contacto_adaptable_rosita/
    ├── contactos_ferreter_a_rosita/
    ├── inicio_adaptable_rosita/
    └── nosotros_ferreter_a_rosita/
```

## ✨ Características

✅ **Un solo `index.html`** - Todas las páginas consolidadas en un único archivo
✅ **4 Páginas en 1**: Inicio, Nosotros, Catálogo y Contacto
✅ **SPA (Single Page Application)** - Navegación sin recargas de página
✅ **Diseño Responsivo** - Funciona en móvil, tablet y desktop
✅ **Navegación Completa**:
   - Barra de navegación de escritorio (oculta en móvil)
   - Barra de navegación inferior en móvil/tablet
   - Enlaces internos en el contenido

## 🌐 Páginas

### 1. **INICIO** (home)
- Hero section con imagen de fondo
- Categorías de productos
- Productos destacados
- Ubicación y horarios
- Vista de mapa

### 2. **NOSOTROS** (about)
- Historia de la empresa
- Misión y valores
- Ubicación estratégica
- Enlace "Cómo llegar" (directo a contacto)

### 3. **CATÁLOGO** (productos)
- Grid de productos
- Información de precios
- Botones de compra
- Descripción de artículos

### 4. **CONTACTO**
- Formulario de contacto
- Información de dirección
- Teléfono y horarios
- Mapa de ubicación

## 📱 Uso

### En Navegador
1. Abre `index.html` en tu navegador
2. Haz clic en cualquier link de navegación para cambiar de página
3. La barra inferior (móvil) o superior (desktop) maneja la navegación

### Estructura de Carpetas
- **css/styles.css** - Contiene estilos personalizados
- **img/** - Carpeta vacía para añadir imágenes locales en futuro
- Los archivos originales en `stitch/` pueden conservarse o eliminarse

## 🎨 Estilos

Los estilos utilizan:
- **Tailwind CSS** - Framework de utilidades CSS
- **Material Symbols** - Iconografía de Google
- **Fuentes de Google** - Work Sans (headlines), Inter (body)

Paleta de colores ROSITA:
- Primario: `#a63b00` (naranja oscuro)
- Primario Container: `#f26522` (naranja)
- Surface: `#f8f9ff` (gris claro)

## 🖼️ Imágenes

Actualmente todas las imágenes son **externas** (Google Images).

Para usar imágenes locales:
1. Coloca las imágenes en la carpeta `img/`
2. Cambia las rutas en el HTML de:
   ```html
   src="https://lh3.googleusercontent.com/..."
   ```
   A:
   ```html
   src="img/nombre-imagen.jpg"
   ```

## 📝 Personalización

### Cambiar texto o contenido
Edita directamente en `index.html` dentro de cada sección `<div id="...">`.

### Agregar nuevas páginas
1. Crea un nuevo `<div id="nueva-pagina" class="page-section">`
2. Añade un link en el navegación desktop
3. Añade un botón en el bottom nav mobile
4. Usa `showPage('nueva-pagina')` para enlazar

### Modificar estilos
Edita `css/styles.css` para cambios globales, o usa clases de Tailwind CSS directamente en el HTML.

## 🚀 Ventajas de esta Estructura

✅ Mantenimiento más fácil - Todo en un archivo
✅ Carga más rápida - No hay recargas de página
✅ Estilos organizados - Separados en CSS
✅ Preparado para imágenes locales - Carpeta `img/` lista
✅ Responsive y moderno - Compatible con todos los dispositivos

## 📞 Soporte

Si necesitas agregar más contenido o hacer cambios, puedes:
- Editar directamente en `index.html`
- Actualizar estilos en `css/styles.css`
- Agregar imágenes en `img/`

---

**Versión**: 1.0 | **Fecha**: 5 de Abril de 2026 | **Empresa**: ROSITA Oruro
