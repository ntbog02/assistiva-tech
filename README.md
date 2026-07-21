# Assistiva Tech — Landing Page

Sitio de una sola página (Single Page Website) para Assistiva Tech: HTML + Tailwind CSS (vía CDN) + JavaScript vanilla. No requiere build ni instalación de dependencias.

## Estructura del proyecto

```
assistiva-tech-web/
├── index.html              # Página completa (contenido, estilos y lógica)
├── assets/
│   └── images/
│       ├── assistiva-logo.png   # Logo de la marca
│       └── whatsapp-qr.png      # QR mostrado en el modal de WhatsApp
└── README.md
```

## Cómo subirlo a GitHub

1. Creá un repositorio nuevo en GitHub (podés dejarlo vacío, sin README ni .gitignore).
2. Desde esta carpeta, en la terminal:
   ```bash
   git init
   git add .
   git commit -m "Sitio Assistiva Tech"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
   git push -u origin main
   ```

## Cómo publicarlo gratis con GitHub Pages

1. En el repositorio, andá a **Settings → Pages**.
2. En "Build and deployment" elegí **Deploy from a branch**.
3. Seleccioná la rama `main` y la carpeta `/ (root)`.
4. Guardá. En un par de minutos el sitio queda publicado en:
   `https://TU-USUARIO.github.io/TU-REPO/`

## Configuración pendiente antes de publicar

- **Formulario de contacto**: ya está conectado a Formspree (`https://formspree.io/f/mojgwodn`), apuntando al correo configurado en esa cuenta. Confirmá el primer envío desde el mail de verificación de Formspree si todavía no lo hiciste.
- **Dominio propio**: si comprás `assistivatech.com`, podés conectarlo desde la misma sección de Settings → Pages ("Custom domain").
- **QR de WhatsApp**: el modal usa la imagen `assets/images/whatsapp-qr.png`. Si el número de WhatsApp cambia, hay que generar un QR nuevo y reemplazar ese archivo (mismo nombre, para no tocar el HTML).
