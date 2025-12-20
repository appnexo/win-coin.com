# Win Coin - Sitio Web Oficial

Sitio web oficial de **Win Coin 💰 - Gana Dinero Real Viendo Anuncios**

## 🚀 Despliegue en GitHub Pages

### Paso 1: Crear repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Haz clic en **New repository**
3. Nombra el repositorio: `wincoin-website`
4. Marca como **Public**
5. Haz clic en **Create repository**

### Paso 2: Subir archivos

Ejecuta estos comandos en PowerShell desde esta carpeta:

```powershell
git init
git add .
git commit -m "Initial commit - Win Coin website"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/wincoin-website.git
git push -u origin main
```

**Nota:** Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub.

### Paso 3: Activar GitHub Pages

1. Ve a tu repositorio en GitHub
2. Haz clic en **Settings** (Configuración)
3. En el menú lateral, haz clic en **Pages**
4. En **Source**, selecciona **main** branch
5. Carpeta: **/ (root)**
6. Haz clic en **Save**
7. Espera 2-3 minutos

Tu sitio estará disponible en: `https://TU_USUARIO.github.io/wincoin-website/`

## 📝 Actualizar el Sitio Web

Después del despliegue inicial, actualiza las URLs en los archivos:

1. En `index.html`, línea 9:
   ```html
   <meta property="og:image" content="https://TU_USUARIO.github.io/wincoin-website/assets/og-image.png">
   ```

2. En `index.html`, línea 10:
   ```html
   <meta property="og:url" content="https://TU_USUARIO.github.io/wincoin-website/">
   ```

3. Actualiza el enlace de Google Play Store con el real cuando esté disponible.

## 📱 Cumplimiento con Meta/Facebook Ads

Este sitio web cumple con los requisitos de Meta para publicidad:

✅ **Política de Privacidad** - `privacy-policy.html`
✅ **Términos y Condiciones** - `terms-of-service.html`
✅ **Información de Contacto** - Email visible en footer y páginas legales
✅ **Descripción Clara del Servicio** - Landing page con información completa
✅ **Diseño Profesional** - Responsive y moderno
✅ **Call-to-Action Claro** - Botón de descarga prominente

## 🎨 Personalización

### Agregar Logo de la App

1. Coloca tu logo en `assets/`
2. Actualiza las referencias de imágenes en `index.html`

### Cambiar Colores

Los colores principales están definidos en CSS:
- Primario: `#667eea` y `#764ba2` (gradiente morado)
- Secundario: `#ff6b6b` (rojo/naranja)

Busca estos valores en `index.html` y cámbialos según tu marca.

### Actualizar Estadísticas

En la sección "Stats", actualiza los números según tus datos reales:
- Retiro mínimo
- Tiempo de pago
- Coins por anuncio
- Etc.

## 📊 Meta Pixel (Opcional)

Para rastrear conversiones de Facebook Ads, agrega Meta Pixel:

1. Crea un Pixel en Facebook Business Manager
2. Copia el código del Pixel
3. Pégalo en `index.html` antes de `</head>`

## 🔗 Enlaces Importantes

Actualiza estos enlaces con los reales:

- **Google Play Store:** Actualmente placeholder, actualizar cuando app esté publicada
- **Redes Sociales:** Agrega tus perfiles de Facebook, Instagram, Twitter en el footer
- **Email de Contacto:** `dpsservicio@gmail.com` (ya configurado)

## 📸 Imágenes Recomendadas

Para mejorar el sitio, agrega:

1. **assets/og-image.png** - Imagen para compartir en redes (1200x630px)
2. **assets/logo.png** - Logo de la app
3. **assets/screenshot1.png** - Capturas de pantalla de la app
4. **assets/app-icon.png** - Ícono de la app

## 🧪 Testing

Antes de hacer publicidad, verifica:

- [ ] Todos los enlaces funcionan
- [ ] Sitio se ve bien en móvil
- [ ] Política de privacidad y términos son accesibles
- [ ] Email de contacto funciona
- [ ] Enlace de Google Play Store actualizado

## 🎯 Configurar Facebook Ads

1. Usa la URL de GitHub Pages como landing page
2. Asegúrate de incluir enlaces a:
   - Política de privacidad
   - Términos y condiciones
3. Target: Personas 18+ interesadas en:
   - Ganar dinero online
   - Recompensas
   - PayPal
   - Apps de entretenimiento

## 📧 Soporte

Para preguntas sobre el sitio web: **dpsservicio@gmail.com**

---

**© 2024 Win Coin. Todos los derechos reservados.**
