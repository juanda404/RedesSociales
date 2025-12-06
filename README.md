# Portfolio Personal - Juan David Santamaría

Landing page personal con enlaces a redes sociales, construida con JavaScript Vanilla y Webpack.

## 🚀 Tecnologías

- **JavaScript Vanilla** - Sin frameworks, solo JS puro
- **Webpack** - Empaquetador de módulos
- **Tailwind CSS** - Framework de CSS vía CDN
- **HTML5** - Estructura semántica

## 📁 Estructura del Proyecto

```
WEBPACK/
├── .github/
├── dist/                # Archivos compilados
│   └── index.html
├── node_modules/
├── public/             # Archivos estáticos
│   └── index.html
├── src/                # Código fuente
│   ├── index.js       # Punto de entrada
│   ├── package-lock.json
│   └── package.json
├── README.md
└── webpack.config.js   # Configuración de Webpack
```

## 🔧 Instalación

1. Clona el repositorio:
```bash
git clone [tu-repositorio]
cd WEBPACK
```

2. Instala las dependencias:
```bash
npm install
```

## 💻 Scripts Disponibles

```bash
# Modo desarrollo (con hot reload)
npm run dev

# Build para producción
npm run build

# Servidor de desarrollo
npm start
```

## 📝 Configuración

### webpack.config.js

El proyecto utiliza Webpack para:
- Empaquetar módulos JavaScript
- Servir archivos en desarrollo
- Optimizar código para producción
- Copiar archivos estáticos

### Estructura Visual

El diseño utiliza un esquema de colores en degradado:
- **Header**: Fondo blanco con sombra
- **Tarjeta de perfil**: Información personal con avatar circular
- **Enlaces**: Gradiente de azul marino a cyan claro
  - Platzi: `bg-blue-900` (más oscuro)
  - Entrenamiento: `bg-blue-700`
  - Blog: `bg-cyan-500`
  - Motivation: `bg-cyan-400`
  - Projects: `bg-cyan-300` (más claro)
- **Footer**: Email de contacto con icono de briefcase 💼

### Personalización

Para personalizar tu información, edita el archivo `src/index.js`:


## 🎨 Características

- ✅ Diseño responsive con Tailwind CSS
- ✅ SEO optimizado con meta tags
- ✅ Open Graph para redes sociales
- ✅ Twitter Cards
- ✅ Favicon personalizado
- ✅ Componentes modulares en JavaScript
- ✅ Tarjeta de perfil con foto y bio
- ✅ Iconos de redes sociales (YouTube, GitHub, Instagram, Twitter, LinkedIn)
- ✅ Enlaces categorizados con emojis (Platzi 💻, Entrenamiento 💪, Blog 💬, Motivation 🥕, Projects 🎬)
- ✅ Email de contacto visible
- ✅ Banderas de Colombia 🇨🇴

## 🌐 Deploy

El sitio está desplegado en Netlify:
[https://jdsantamaria.netlify.app/](https://jdsantamaria.netlify.app/)


## 📄 Meta Tags Incluidos

- **SEO básico**: title, description, robots
- **Open Graph**: para Facebook, LinkedIn
- **Twitter Cards**: para Twitter/X
- **Viewport**: para responsive design

## 🔗 Redes Sociales

El proyecto incluye enlaces a:
- 🎥 YouTube
- 💻 GitHub
- 📷 Instagram
- 🐦 Twitter/X
- 💼 LinkedIn

## 📂 Secciones de Enlaces

El sitio organiza los enlaces en categorías con diseño degradado de azul oscuro a cyan claro:

1. **Platzi** 💻 - Contenido educativo
2. **Entrenamiento** 💪 - Contenido de fitness
3. **Blog** 💬 - Artículos y posts
4. **Motivation** 🥕 - Contenido motivacional
5. **Projects** 🎬 - Proyectos personales

## 📦 Dependencias de Desarrollo

Principales dependencias (revisa `package.json` para lista completa):
- webpack
- webpack-cli
- webpack-dev-server
- html-webpack-plugin
- (otras dependencias según tu configuración)

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:
1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📧 Contacto

Juan David Santamaría Gómez - [@juanda4042](https://twitter.com/juanda4042)

Project Link: [https://jdsantamaria.netlify.app/](https://jdsantamaria.netlify.app/)

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

---

⭐️ Si te gusta este proyecto, no olvides darle una estrella en GitHub!