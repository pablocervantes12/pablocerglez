# Juan Pablo Cervantes González — Sitio Personal

Sitio web personal estático con la información profesional, experiencia laboral y stack tecnológico.

## Archivos

- `index.html` — estructura del sitio
- `styles.css` — estilos (sin gradientes, sin badges)
- `profile.jpg` — foto de perfil

## Ver localmente

Abrir `index.html` en el navegador, o servir con cualquier servidor estático:

```bash
python -m http.server 8000
# luego abrir http://localhost:8000
```

## Publicar en GitHub Pages

1. Crear un repositorio nuevo en GitHub (ejemplo: `pablocerglez.github.io` para sitio de usuario, o cualquier nombre para sitio de proyecto).
2. Inicializar git y subir archivos:

   ```bash
   git init
   git add .
   git commit -m "feat: sitio personal inicial"
   git branch -M main
   git remote add origin git@github.com:pablocerglez/NOMBRE_REPO.git
   git push -u origin main
   ```

3. En GitHub: **Settings → Pages → Source: Deploy from a branch → Branch: `main` / root → Save**.
4. URL del sitio:
   - Repo `pablocerglez.github.io` → `https://pablocerglez.github.io`
   - Otro repo → `https://pablocerglez.github.io/NOMBRE_REPO`

## Personalizar

- Cambiar foto: reemplazar `profile.jpg`.
- Editar contenido: directo en `index.html`.
- Editar colores: variables `:root` en `styles.css`.
