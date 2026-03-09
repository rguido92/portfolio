# Portfolio — Rodrigo Guido 

Portfolio personal construido con la plantilla oficial de Astro.

## 🚀 Inicio rápido

```bash
npm install
npm run dev
```

Abre [http://localhost:4321](http://localhost:4321) en tu navegador.

## 🧞 Comandos

| Comando           | Acción                                        |
|-------------------|-----------------------------------------------|
| `npm install`     | Instala dependencias                          |
| `npm run dev`     | Servidor de desarrollo en `localhost:4321`    |
| `npm run build`   | Build de producción en `./dist/`              |
| `npm run preview` | Preview del build antes de desplegar          |

## 📁 Estructura

```
portfolio/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro    # Navbar + Footer + SEO
│   ├── pages/
│   │   └── index.astro         # Página principal (todo el contenido)
│   └── styles/
│       └── global.css          # Sistema de diseño completo
├── astro.config.mjs
└── package.json
```

## 🌐 Despliegue en Vercel

1. Sube el proyecto a GitHub
2. Conecta el repo en [vercel.com](https://vercel.com)
3. Framework preset: **Astro**
4. Deploy automático en cada push

## ✏️ Personalización

Todo el contenido (proyectos, stack, formación) está centralizado
en los arrays al inicio de `src/pages/index.astro`.
Los estilos y variables de color están en `src/styles/global.css`.
