# Web oficial de Aplasta Hormigas Pro

Sitio estático listo para GitHub Pages.

## Antes de publicar

1. Reemplaza `TU_CORREO_DE_SOPORTE` en `privacy.html` y `support.html`.
2. Cuando tengas el enlace de prueba abierta, cambia el botón **Unirme a la prueba** en `index.html` por la URL de Google Play.
3. Verifica que la política de privacidad coincida con los SDK realmente incluidos en la aplicación.
4. No publiques contraseñas, archivos `.keystore`, IDs privados ni credenciales en GitHub.

## Subir a GitHub

```bash
git init
git add .
git commit -m "Publicar web de Aplasta Hormigas Pro"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/aplasta-hormigas-pro.git
git push -u origin main
```

Después, en GitHub:

- **Settings**
- **Pages**
- **Build and deployment**
- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**
- **Save**

La web quedará normalmente en:

`https://TU_USUARIO.github.io/aplasta-hormigas-pro/`

## Archivos

- `index.html`: portada.
- `privacy.html`: política de privacidad.
- `support.html`: soporte.
- `styles.css`: diseño responsive.
- `script.js`: navegación móvil y año automático.
- `assets/`: imágenes optimizadas.
