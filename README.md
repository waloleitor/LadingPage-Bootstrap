# 🌿 EcoTrends - Landing Page Responsive

Pequeño proyecto para dominar Tailwind CSS creando una landing page moderna y completamente responsive.

## 🛠️ Tecnologías utilizadas
- **Tailwind CSS** v3.3+ (con plugins oficiales)
- HTML5 semántico
- Mobile-First Workflow

## ✨ Características implementadas
- **Diseño responsive** (4 breakpoints: mobile, tablet, desktop, wide)
- **Componentes Tailwind**:
  - Navbar con menú hamburguesa (mobile)
  - Cards con hover effects
  - Formulario de contacto funcional
  - Testimonios en carrusel
- **Optimizaciones**:
  - Imágenes con lazy loading
  - Transiciones suaves
  - Modo oscuro opcional

## 🎨 Paleta de colores (Tailwind)
| Uso           | Clase Tailwind      |
|---------------|---------------------|
| Color primario| `bg-emerald-600`    |
| Secundario    | `bg-amber-400`      |
| Fondo         | `bg-stone-50`       |
| Texto         | `text-stone-800`    |
| Modo oscuro   | `dark:bg-stone-900` |


## 🛠️ Configuración técnica

### Tailwind CSS
Este proyecto utiliza **Tailwind CSS v3.4.1** (última versión estable) mediante CDN.  
Para implementarlo en tu HTML, añade este código en el `<head>`:

```html
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <style type="text/tailwindcss">
      @theme {
        --color-clifford: #da373d;
      }
    </style>

#📦 Alternativa local: Instala via npm con npm install tailwindcss

## 🚀 Cómo visualizarlo
1. Clona el repositorio
2. Abre `index.html` en tu navegador
3. Alternativamente:
   ```bash
   python3 -m http.server 8000
