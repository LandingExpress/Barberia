# Barber Shop Visagismo - Landing Page

Landing page profesional para servicios de barbería y visagismo, diseñada con HTML, CSS y JavaScript vanilla.

## 🎨 Características

- **Diseño Responsive**: Optimizado para todos los dispositivos (móvil, tablet, desktop)
- **Animaciones Suaves**: Transiciones y efectos de scroll profesionales
- **Paleta de Colores**: Negro/gris oscuro, blanco, azul petróleo y verde lima de acento
- **Tipografías Google Fonts**: Montserrat (títulos) y Roboto (textos)
- **Totalmente Estático**: Sin dependencias de backend, listo para GitHub Pages

## 📂 Estructura del Proyecto

```
/
├── index.html          # Archivo principal (en raíz)
├── css/
│   └── styles.css      # Estilos completos
├── js/
│   └── main.js         # Funcionalidad JavaScript
├── images/             # Imágenes del sitio
│   ├── hero-bg.jpg
│   ├── barber-work.jpg
│   └── gallery-*.jpg
└── README.md
```

## 🚀 Cómo Publicar en GitHub Pages

### Paso 1: Crear un Repositorio en GitHub

1. Ve a [GitHub](https://github.com) y crea una cuenta si no la tienes
2. Crea un nuevo repositorio:
   - Click en el botón **"New"** o **"+"** en la esquina superior derecha
   - Nombre del repositorio: `barber-shop-visagismo` (o el que prefieras)
   - Deja el repositorio como **Público**
   - **NO** marques "Initialize this repository with a README"
   - Click en **"Create repository"**

### Paso 2: Subir los Archivos

**Opción A: Usando la interfaz web de GitHub** (Más fácil)

1. En tu nuevo repositorio vacío, click en **"uploading an existing file"**
2. Arrastra y suelta TODOS los archivos y carpetas de este proyecto
3. Asegúrate de que `index.html` esté en la raíz del repositorio
4. Escribe un mensaje de commit (ej: "Primer commit - Landing page completa")
5. Click en **"Commit changes"**

**Opción B: Usando Git en terminal** (Avanzado)

```bash
git init
git add .
git commit -m "Primer commit - Landing page completa"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/barber-shop-visagismo.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. En tu repositorio de GitHub, ve a **Settings** (Configuración)
2. En el menú lateral, click en **Pages**
3. En **Source** (Fuente), selecciona:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click en **Save** (Guardar)
5. ¡Listo! En unos minutos tu sitio estará disponible en:
   ```
   https://TU-USUARIO.github.io/barber-shop-visagismo/
   ```

### Paso 4: Personalizar Antes de Publicar

Asegúrate de actualizar estos datos en `index.html`:

#### Número de WhatsApp
Busca y reemplaza:
```html
href="https://wa.me/5491112345678?text=..."
```
Con tu número real (formato internacional):
```html
href="https://wa.me/54911XXXXXXXX?text=Hola!%20Quiero%20reservar%20un%20turno"
```

#### Ubicación
Busca `[Ciudad o barrio]` y reemplázalo con tu ubicación real:
```html
<p>[Tu Ciudad o Barrio]</p>  <!-- Cambiar esto -->
```

#### Número de Teléfono
Busca `+54 9 [Tu número]` y actualízalo:
```html
<p>+54 9 [Tu número]</p>  <!-- Cambiar esto -->
```

#### Redes Sociales (Opcional)
Actualiza los links de Instagram y Facebook en el footer:
```html
<a href="https://instagram.com/TU_USUARIO" aria-label="Instagram" class="social-link">
<a href="https://facebook.com/TU_PAGINA" aria-label="Facebook" class="social-link">
```

## 🎯 Secciones Incluidas

1. **Hero/Banner**: Mensaje principal con llamado a la acción
2. **Sobre Mí**: Presentación del visagista y enfoque profesional
3. **Servicios**: 4 servicios principales con iconos y descripciones
4. **Testimonios**: 3 opiniones de clientes (Marcos, Luciano, Diego)
5. **Galería**: 6 imágenes de transformaciones antes/después
6. **Contacto**: Información de ubicación, horarios y WhatsApp
7. **CTA Final**: Llamado a la acción potente
8. **Footer**: Links rápidos y redes sociales

## 📱 Responsive Design

El sitio está optimizado para:
- 📱 Móviles (< 480px)
- 📱 Tablets (480px - 968px)
- 💻 Desktop (> 968px)

## 🛠️ Personalización Adicional

### Cambiar Colores
Edita las variables CSS en `css/styles.css`:
```css
:root {
    --color-dark: #1a1a1a;        /* Negro/gris oscuro */
    --color-accent: #7ed321;       /* Verde lima */
    --color-blue: #1e4a5f;         /* Azul petróleo */
}
```

### Agregar Más Imágenes a la Galería
1. Agrega tus imágenes en la carpeta `images/`
2. En `index.html`, duplica este bloque dentro de `.gallery-grid`:
```html
<div class="gallery-item">
    <img src="images/TU-IMAGEN.jpg" alt="Descripción" class="gallery-image">
    <div class="gallery-overlay">
        <span class="gallery-label">Antes / Después</span>
    </div>
</div>
```

### Modificar Servicios
Edita la sección `<section class="servicios">` en `index.html` para agregar, quitar o modificar servicios.

## 🌐 Dominio Personalizado (Opcional)

Si tienes un dominio propio (ej: `www.barbershopvisagismo.com`):

1. En la configuración de tu proveedor de dominio, crea un registro CNAME apuntando a:
   ```
   TU-USUARIO.github.io
   ```
2. En GitHub Pages settings, agrega tu dominio personalizado
3. Activa **"Enforce HTTPS"**

## 📝 Licencia

Este proyecto es de uso libre para tu emprendimiento.

## 🆘 Soporte

Si tienes problemas publicando en GitHub Pages:
- [Documentación oficial de GitHub Pages](https://docs.github.com/es/pages)
- [Video tutorial en español](https://www.youtube.com/results?search_query=github+pages+tutorial+español)

---

**¡Tu landing page está lista para impresionar a tus clientes! 🎉**