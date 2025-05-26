# AUDAGRAMA – Sitio Web Minimalista

Este repositorio contiene el código fuente del sitio web de **AUDAGRAMA**, una agencia de creatividad y estrategia.  
El diseño es minimalista, profesional y responsivo, siguiendo buenas prácticas de accesibilidad, SEO y usabilidad.

---

## 📁 Estructura de Carpetas

```
/
├── index.html
├── terms.html
├── privacy.html
├── favicon.ico
│
├── css/
│   └── styles.css
│
├── img/
│   ├── logo.svg
│   └── og-image.jpg
│
└── README.md
```

### Descripción de archivos y carpetas

- **index.html**  
  Página principal del sitio. Incluye animación minimalista, menú, frase multilingüe y footer profesional.

- **terms.html**  
  Página de Términos y Condiciones. Incluye header minimalista, menú de navegación y footer pequeño.

- **privacy.html**  
  Página de Política de Privacidad. Igual estructura que terms.html.

- **favicon.ico**  
  Ícono del sitio para navegadores.

- **css/styles.css**  
  Todos los estilos globales del sitio, incluyendo fuentes, colores, animaciones y responsive.

- **img/**  
  Carpeta para imágenes, logos y recursos visuales.  
  - `logo.svg`: Logo principal de AUDAGRAMA.  
  - `og-image.jpg`: Imagen para Open Graph (compartir en redes sociales).

- **README.md**  
  Este archivo.

---

## 🚀 Cómo trabajar con el proyecto

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/tuusuario/audagrama.git
   cd audagrama
   ```

2. **Estructura de archivos:**  
   Asegúrate de mantener la estructura de carpetas y rutas relativas para que los enlaces funcionen correctamente.

3. **Editar contenido:**  
   - Modifica los textos en los archivos `.html` según sea necesario.
   - Cambia imágenes en `/img/` si lo requieres.
   - Personaliza estilos en `/css/styles.css`.

4. **Pruebas locales:**  
   Abre `index.html`, `terms.html` y `privacy.html` en tu navegador para revisar el diseño y la navegación.

5. **Despliegue:**  
   Puedes subir el contenido a cualquier hosting estático (GitHub Pages, Netlify, Vercel, etc.).  
   El archivo `index.html` debe estar en la raíz del proyecto.

---

## 🟢 Buenas prácticas

- Usa **nombres en minúsculas y sin espacios** para archivos y carpetas.
- Mantén **rutas relativas** en los enlaces (`css/styles.css`, `img/logo.svg`, etc.).
- Los **enlaces del menú** en las páginas legales apuntan a secciones de `index.html` (por ejemplo, `index.html#servicios`).
- El **footer** incluye año automático y enlaces legales.
- Todos los **enlaces externos** usan `rel="noopener noreferrer"` y `target="_blank"` donde corresponde.
- El **logo** en el header nunca está subrayado y siempre lleva a la home.

---

## ✨ Personalización

- Cambia el logo en `/img/logo.svg` y la imagen de Open Graph en `/img/og-image.jpg`.
- Modifica los colores o fuentes en `/css/styles.css` si lo deseas.
- Agrega nuevas secciones o páginas siguiendo la misma estructura.

---

## 📄 Licencia

Este proyecto es propiedad de TODO KÜL S.A.S. de C.V.  
Uso y distribución sujetos a los términos descritos en `terms.html`.

---

¿Dudas o sugerencias?  
Contacta a [hola@audagrama.com](mailto:hola@audagrama.com)
