# Portafolio · Nicolás Rozas

Sitio web personal para mostrar mis proyectos, habilidades y certificados como **Desarrollador Full Stack Junior**. Diseño oscuro, responsive y construido con Astro y Tailwind CSS.

🔗 **Demo:** [tu-portafolio.netlify.app](https://tu-portafolio.netlify.app)

---

## ✨ Características

- Diseño **responsive** (mobile-first) con Tailwind CSS.
- **Carrusel de fotos** en el hero con animación CSS (sin JavaScript).
- Sección de **Skills deslizable en móvil** con scroll snap e indicadores de posición.
- Header fijo con navegación por secciones y acceso directo a WhatsApp.
- Sección de **certificados** generada dinámicamente desde un archivo de constantes.
- Botón de **descarga de CV** y enlaces a GitHub, LinkedIn y correo.

## 🛠️ Tecnologías

| Área | Herramientas |
|---|---|
| Framework | [Astro](https://astro.build) |
| Estilos | [Tailwind CSS](https://tailwindcss.com) |
| Lenguaje | TypeScript / JavaScript |
| Despliegue | Netlify |

## 📁 Estructura del proyecto

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   │   ├── cv/            # CV en PDF
│   │   ├── img/me/        # Fotos del hero
│   │   └── svg/           # Iconos
│   ├── components/        # Header, Hero, About, Skills, Projects, Certificates, Contact
│   ├── constants/
│   │   ├── Info.ts        # Datos personales del sitio
│   │   └── Certificates.ts
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🚀 Instalación y uso

Requisitos: [Node.js](https://nodejs.org) 18 o superior.

```bash
# 1. Clonar el repositorio
git clone https://github.com/nicorp12/nombre-del-repositorio.git

# 2. Entrar a la carpeta
cd nombre-del-repositorio

# 3. Instalar dependencias
npm install

# 4. Iniciar el servidor de desarrollo
npm run dev
```

El sitio quedará disponible en `http://localhost:4321`.

### Comandos disponibles

| Comando | Acción |
|---|---|
| `npm run dev` | Inicia el servidor de desarrollo |
| `npm run build` | Genera el sitio final en `./dist/` |
| `npm run preview` | Previsualiza el build localmente |

## ⚙️ Personalización

- **Datos personales** (nombre, rol, WhatsApp, año): edita `src/constants/Info.ts`.
- **Certificados**: edita `src/constants/Certificates.ts`.
- **Fotos del hero**: reemplaza las imágenes en `src/assets/img/me/`.
- **CV**: reemplaza el PDF en `src/assets/cv/`.

## 📦 Despliegue

El proyecto se despliega en **Netlify**:

1. Sube el repositorio a GitHub.
2. En Netlify, elige *Add new site → Import from Git*.
3. Configura:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`

## 🗂️ Proyectos destacados

| Proyecto | Tecnologías | Enlace |
|---|---|---|
| **AsisDuocUC** | Ionic · Angular | App móvil de control de asistencia con lector QR |
| **AsisDuocUC - Landing Page** | Astro · Tailwind CSS | [asisduocuc.netlify.app](https://asisduocuc.netlify.app/) |

## 📬 Contacto

- 📧 [nicorozas6694@gmail.com](mailto:nicorozas6694@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/nicorozasp/)
- 🐙 [GitHub](https://github.com/nicorp12)

Abierto a nuevas oportunidades como Junior o Trainee.

## 📄 Licencia

Este proyecto es de uso personal. Si te sirve de inspiración, ¡puedes basarte en él! Te agradecería que no copies el contenido (textos, fotos y CV).