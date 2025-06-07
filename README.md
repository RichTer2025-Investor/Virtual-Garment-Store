# 🛍️ Tienda de Ropa Casual - Plataforma E-commerce

Una moderna plataforma de comercio electrónico para ropa casual, desarrollada con React, TypeScript, Tailwind CSS y optimizada para GitHub Pages.

## 🌟 Características

- **Interfaz Moderna**: Diseño responsivo y atractivo con Tailwind CSS
- **Catálogo de Productos**: Navegación intuitiva por categorías
- **Carrito de Compras**: Funcionalidad completa de e-commerce
- **Panel de Administración**: Gestión de productos, pedidos y usuarios
- **Hosting Gratuito**: Desplegado en GitHub Pages
- **SEO Optimizado**: Metadatos y estructura optimizada para motores de búsqueda

## 🚀 Demo en Vivo

**URL de la Tienda**: `https://RichTer2025-Investor.github.io/tienda-ropa-casual`

*Reemplaza `[TU-USUARIO]` con tu nombre de usuario de GitHub*

## 📋 Requisitos Previos

- Node.js (versión 18 o superior)
- npm o pnpm
- Cuenta de GitHub
- Git instalado en tu sistema

## 🛠️ Instalación Local

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/RichTer2025-Investor/tienda-ropa-casual.git
   cd tienda-ropa-casual
   ```

2. **Instala las dependencias**
   ```bash
   # Con npm
   npm install
   
   # Con pnpm (recomendado)
   pnpm install
   ```

3. **Ejecuta en modo desarrollo**
   ```bash
   # Con npm
   npm run dev
   
   # Con pnpm
   pnpm dev
   ```

4. **Abre tu navegador**
   Visita `http://localhost:5173` para ver la aplicación

## 🌐 Despliegue en GitHub Pages

### Opción 1: Despliegue Automático (Recomendado)

El proyecto incluye GitHub Actions que automáticamente despliega en GitHub Pages cuando haces push a la rama `main`.

1. **Crea un repositorio en GitHub**
   - Ve a [GitHub](https://github.com) y crea un nuevo repositorio
   - Nómbralo: `tienda-ropa-casual`
   - **NO** inicialices con README, .gitignore o licencia

2. **Actualiza el package.json**
   ```json
   {
     "homepage": "https://RichTer2025-Investor.github.io/tienda-ropa-casual"
   }
   ```

3. **Sube el código a GitHub**
   ```bash
   git init
   git add .
   git commit -m "🎉 Inicial: Tienda de ropa casual completa"
   git branch -M main
   git remote add origin https://github.com/RichTer2025-Investor/tienda-ropa-casual.git
   git push -u origin main
   ```

4. **Configura GitHub Pages**
   - Ve a tu repositorio en GitHub
   - Navega a **Settings** > **Pages**
   - En **Source**, selecciona **GitHub Actions**
   - El despliegue se iniciará automáticamente

5. **¡Tu tienda estará en línea!**
   En unos minutos, tu tienda estará disponible en:
   `https://RichTer2025-Investor.github.io/tienda-ropa-casual`

### Opción 2: Despliegue Manual

```bash
# Construye el proyecto para GitHub Pages
npm run build:gh-pages

# Despliega manualmente (requiere gh-pages instalado)
npm run deploy
```

## 📁 Estructura del Proyecto

```
tienda-ropa-casual/
├── public/                    # Archivos estáticos
│   ├── productos.json        # Base de datos de productos
│   ├── usuarios.json         # Base de datos de usuarios
│   ├── pedidos.json          # Base de datos de pedidos
│   └── images/               # Imágenes de productos
├── src/
│   ├── components/           # Componentes React
│   │   ├── ui/              # Componentes de UI reutilizables
│   │   ├── CarritoCompras.tsx
│   │   ├── CatalogoProductos.tsx
│   │   ├── PanelAdmin.tsx
│   │   └── ...
│   ├── contexts/            # Contextos de React
│   ├── hooks/               # Hooks personalizados
│   └── lib/                 # Utilidades
├── .github/workflows/       # GitHub Actions
├── dist/                    # Build de producción
└── docs/                    # Documentación
```

## 🎨 Tecnologías Utilizadas

- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS, Radix UI
- **Build Tool**: Vite
- **Routing**: React Router DOM
- **State Management**: React Context
- **Forms**: React Hook Form + Zod
- **Icons**: Lucide React
- **Deployment**: GitHub Pages
- **CI/CD**: GitHub Actions

## 🔧 Scripts Disponibles

```bash
# Desarrollo
npm run dev              # Servidor de desarrollo
npm run build            # Build para producción
npm run build:gh-pages   # Build optimizado para GitHub Pages
npm run preview          # Preview del build
npm run lint             # Linting del código

# Despliegue
npm run predeploy        # Pre-build para despliegue
npm run deploy           # Despliegue a GitHub Pages
```

## 📊 Funcionalidades Principales

### Para Clientes
- **Catálogo de Productos**: Navegación por categorías (camisetas, pantalones, zapatos, accesorios)
- **Búsqueda y Filtros**: Filtrado por precio, talla, color
- **Carrito de Compras**: Agregar, eliminar, modificar cantidades
- **Proceso de Compra**: Checkout completo con validación de formularios
- **Responsive Design**: Optimizado para móviles, tablets y escritorio

### Para Administradores
- **Panel de Control**: Dashboard con estadísticas de ventas
- **Gestión de Productos**: CRUD completo de productos
- **Gestión de Pedidos**: Visualización y actualización de estados
- **Gestión de Usuarios**: Administración de clientes registrados

## 🎯 Cómo Personalizar

### Agregar Nuevos Productos
1. Edita `public/productos.json`
2. Agrega las imágenes en `public/images/productos/`
3. El cambio se reflejará automáticamente

### Cambiar Colores y Estilos
1. Modifica `tailwind.config.js` para colores personalizados
2. Edita los componentes en `src/components/`

### Agregar Nuevas Funcionalidades
1. Crea nuevos componentes en `src/components/`
2. Actualiza el contexto en `src/contexts/TiendaContext.tsx`
3. Agrega rutas en `src/App.tsx`

## 🚀 Actualizaciones Futuras

Para actualizar tu tienda desplegada:

1. **Realiza cambios en tu código local**
2. **Haz commit y push**
   ```bash
   git add .
   git commit -m "✨ Nueva funcionalidad agregada"
   git push origin main
   ```
3. **GitHub Actions automáticamente desplegará los cambios**

## 📞 Soporte y Contribuciones

- **Issues**: Reporta problemas en GitHub Issues
- **Pull Requests**: Las contribuciones son bienvenidas
- **Documentación**: Mantén actualizada la documentación

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🏆 Características Técnicas

### Optimizaciones para Producción
- **Code Splitting**: Chunks optimizados para carga rápida
- **Tree Shaking**: Eliminación de código no utilizado
- **Minificación**: Código comprimido para mejor rendimiento
- **Lazy Loading**: Carga bajo demanda de componentes

### SEO y Accesibilidad
- **Meta Tags**: Optimizado para motores de búsqueda
- **Semantic HTML**: Estructura semántica correcta
- **ARIA Labels**: Accesibilidad para lectores de pantalla
- **Performance**: Optimizado para Core Web Vitals

---

## 🌟 ¡Tu Tienda en Línea Está Lista!

Sigue las instrucciones de despliegue y tendrás tu propia tienda de comercio electrónico funcionando en GitHub Pages de forma **gratuita y permanente**.

**¿Necesitas ayuda?** Revisa la documentación o crea un issue en el repositorio.

---

**Desarrollado con ❤️ para emprendedores digitales**
