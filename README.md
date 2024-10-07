# CS2 Line-ups Viewer

CS2 Line-ups Viewer es una aplicación web interactiva diseñada para ayudar a los jugadores de Counter-Strike 2 a aprender y visualizar diferentes line-ups (posiciones de lanzamiento de utilidades) en varios mapas del juego.

## 🌟 Características

- 🗺️ Filtrado por mapas de CS2
- 🧨 Filtrado por tipos de utilidades (Humos, Molotov, Flash)
- 🔍 Barra de búsqueda para encontrar line-ups específicos
- 📺 Galería de videos de YouTube integrada
- 📱 Diseño responsive para una experiencia óptima en dispositivos móviles y de escritorio

## 🛠️ Tecnologías utilizadas

- [Astro](https://astro.build) - Framework web moderno
- HTML5
- CSS3 (con Tailwind CSS para estilos)
- TypeScript
- YouTube API (para la integración de videos)

## 🚀 Inicio rápido

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/cs2-lineups-viewer.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd cs2-lineups-viewer
   ```

3. Instala las dependencias:
   ```bash
   npm install
   ```

4. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

5. Abre tu navegador y visita `http://localhost:4321`

## 📁 Estructura del proyecto

```
/
├── public/
│   └── data/
│       └── [mapname].json
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

## 📋 Comandos disponibles

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                         |
| `npm run dev`             | Inicia el servidor de desarrollo en `localhost:4321` |
| `npm run build`           | Construye el sitio para producción en `./dist/`  |
| `npm run preview`         | Previsualiza la construcción antes de desplegar  |

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si tienes alguna idea para mejorar la aplicación o añadir nuevas características, no dudes en abrir un issue o realizar un pull request.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## 📞 Contacto

Si tienes alguna pregunta o sugerencia, no dudes en contactarme:

- GitHub: [@tu-usuario](https://github.com/tu-usuario)
- Email: tu-email@ejemplo.com

---

Hecho con ❤️ para la comunidad de CS2
