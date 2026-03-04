# 🔧 AutoPro Taller - Sitio Web Profesional

Sitio web profesional para un taller automotriz, desarrollado con HTML5 semántico y CSS3 puro. Diseño responsive, moderno y optimizado para conversiones a través de WhatsApp.

## 📁 Estructura de Archivos

```
TALLERWEB/
├── index.html      # Página principal con toda la estructura
├── styles.css      # Estilos, responsive y animaciones
└── README.md       # Este archivo de documentación
```

## 🎨 Personalización

### Cambiar el Número de WhatsApp

Busca `507XXXXXXXX` en `index.html` y reemplázalo por tu número real con código de país (sin signos "+" ni espacios).

Ejemplo: Si tu número es +507 6123-4567, usa `50761234567`.

> **Nota:** El número aparece en 5 lugares: header, hero, CTA section, footer y botón flotante.

### Cambiar Colores

Edita las variables CSS al inicio de `styles.css`:

```css
:root {
    --color-primary: #1E3A8A;    /* Azul principal */
    --color-accent: #3B82F6;     /* Azul de acento */
    --color-whatsapp: #25D366;   /* Verde WhatsApp */
}
```

### Cambiar Textos

Los textos se encuentran directamente en `index.html`. Busca los comentarios `⚠️ CAMBIAR` para ubicar los campos personalizables:

- Nombre del taller
- Dirección
- Teléfono y email
- Nombres y datos de mecánicos
- Horarios de atención
- Descripción del taller

### Cambiar Imágenes

Reemplaza las URLs de `placehold.co` con rutas a tus imágenes reales:

```html
<!-- Antes -->
<img src="https://placehold.co/600x450/1E3A8A/FFFFFF?text=Nuestro+Taller" alt="...">

<!-- Después -->
<img src="img/taller.jpg" alt="Interior de nuestro taller automotriz">
```

## 🚀 Publicar en GitHub Pages

### 1. Crear repositorio en GitHub

1. Ve a [github.com/new](https://github.com/new)
2. Nombre del repositorio: `taller-web` (o el que prefieras)
3. Marca "Public"
4. Click en **Create repository**

### 2. Subir los archivos

Abre una terminal en la carpeta del proyecto y ejecuta:

```bash
git init
git add .
git commit -m "🚀 Sitio web del taller automotriz"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/taller-web.git
git push -u origin main
```

### 3. Activar GitHub Pages

1. En tu repositorio, ve a **Settings** → **Pages**
2. En **Source**, selecciona **Deploy from a branch**
3. En **Branch**, selecciona `main` y carpeta `/ (root)`
4. Click en **Save**
5. Espera 1-2 minutos y tu sitio estará en: `https://TU-USUARIO.github.io/taller-web/`

## 📱 Secciones del Sitio

| Sección | Descripción |
|---------|-------------|
| Header | Navegación fija con logo y botón WhatsApp |
| Hero | Banner principal con CTA y estadísticas |
| Quiénes Somos | Historia, misión y valores del taller |
| Servicios | 7 servicios en tarjetas con hover |
| Mecánicos | 4 perfiles del equipo técnico |
| Horarios | Tabla de horarios + info de contacto |
| Agenda tu Cita | CTA destacado con WhatsApp |
| Footer | Links, contacto y redes sociales |

## 🛠️ Tecnologías

- **HTML5** semántico con accesibilidad (ARIA)
- **CSS3** con Custom Properties y Grid/Flexbox
- **JavaScript** mínimo (menú, animaciones, año dinámico)
- **Google Fonts** (Inter)
- **Responsive**: 3 breakpoints (1024px, 768px, 480px)

## 📄 Licencia

Proyecto de uso libre. Personaliza y utiliza según tus necesidades.
