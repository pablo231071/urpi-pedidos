# Pedidos URPI — PWA

Aplicación web instalable para gestionar los pedidos semanales de las 5 casas URPI.

## Casas
- Milema
- Maria Cristina
- La Hosteria
- Mencey
- La Molina

## Despliegue en Vercel

1. Sube este repositorio a GitHub
2. Ve a [vercel.com](https://vercel.com) → "Add New Project"
3. Importa el repositorio
4. En configuración: **no hace falta cambiar nada**, Vercel detecta el `vercel.json` automáticamente
5. Haz clic en **Deploy**

## Instalar como app en el móvil

**Android (Chrome):**
- Abre la URL del proyecto
- Aparece un banner automático "Instalar app" → pulsa **Instalar**

**iPhone (Safari):**
- Abre la URL en Safari
- Pulsa el botón de compartir (⎋)
- Selecciona "Añadir a pantalla de inicio"

## Estructura
```
public/
  index.html     → App principal
  sw.js          → Service Worker (offline)
  manifest.json  → Config PWA
  icons/         → Iconos de la app
vercel.json      → Config Vercel
```
