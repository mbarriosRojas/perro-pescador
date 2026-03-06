# Médico Online - Landing Page

Landing page de alta conversión para "Médico Online", una plataforma integral de telemedicina y bienestar humano.

## 🚀 Tecnologías

- **Astro** - Framework web moderno para sitios estáticos
- **HTML5 semántico** - Estructura accesible y SEO-friendly
- **CSS moderno** - Variables CSS, Grid, Flexbox, diseño responsive
- **JavaScript vanilla** - Interactividad sin frameworks adicionales

## 📋 Características

- ✅ Diseño responsive (móvil, tablet, desktop)
- ✅ Optimizado para conversión
- ✅ SEO optimizado
- ✅ Accesibilidad (semántica HTML5)
- ✅ Animaciones suaves
- ✅ Formulario de contacto funcional
- ✅ Secciones completas: Hero, Servicios, Especialidades, Cómo Funciona, Testimonios, Contacto

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando              | Acción                                              |
| :------------------- | :-------------------------------------------------- |
| `npm install`        | Instala las dependencias                            |
| `npm run dev`        | Inicia servidor de desarrollo en `localhost:4321`   |
| `npm run build`      | Construye el sitio para producción en `./docs/`     |
| `npm run preview`    | Previsualiza la build localmente antes de desplegar |

## 🚀 Cómo ejecutar

1. Instalar dependencias:
```bash
npm install
```

2. Iniciar servidor de desarrollo:
```bash
npm run dev
```

3. Abrir navegador en `http://localhost:4321`

## 📦 Build para producción

```bash
npm run build
```

El sitio estático se generará en la carpeta `docs/` listo para ser desplegado en GitHub Pages.

## 🌐 Despliegue en GitHub Pages

Este proyecto está configurado para desplegarse en GitHub Pages desde la carpeta `/docs`:

1. Ve a Settings > Pages en tu repositorio
2. Selecciona "Deploy from a branch"
3. Elige la rama `main` y la carpeta `/docs`
4. Guarda los cambios

El sitio estará disponible en: `https://mbarriosRojas.github.io/perro-pescador/`

## 📁 Estructura del Proyecto

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── Specialties.astro
│   │   ├── HowItWorks.astro
│   │   ├── Testimonials.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
└── package.json
```

## 🎨 Personalización

- **Colores**: Edita las variables CSS en `src/layouts/Layout.astro`
- **Contenido**: Modifica los componentes en `src/components/`
- **Estilos**: Cada componente tiene sus propios estilos encapsulados

## 📄 Licencia

MIT
