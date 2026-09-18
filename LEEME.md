# Minish 100% — app de la guía

App independiente de la guía de logros de RetroAchievements para *The Legend of Zelda: The Minish Cap* (set #559, ROM europea con European Backport Edition, nombres oficiales en español).

- Guarda el progreso **solo en el dispositivo donde está instalada**. No usa cuentas ni sincroniza nada.
- Funciona **sin internet** una vez abierta la primera vez.
- Se instala con ícono propio y se abre a pantalla completa, como cualquier app.

## Instalarla en el celular

Para que el teléfono la reconozca como app instalable, los archivos tienen que estar en una dirección `https`. La forma gratuita más simple es GitHub Pages:

1. Crea una cuenta gratis en github.com (si no tienes).
2. Crea un repositorio nuevo **público** llamado, por ejemplo, `minish100`.
3. En el repositorio, pulsa **Add file → Upload files** y arrastra **todo el contenido** de esta carpeta (`index.html`, `manifest.webmanifest`, `sw.js` y las carpetas `fonts` e `icons`). Pulsa **Commit changes**.
4. Ve a **Settings → Pages**, en *Branch* elige `main` y carpeta `/ (root)`, y guarda.
5. Espera uno o dos minutos. Tu app quedará en `https://TU-USUARIO.github.io/minish100/`.
6. Abre esa dirección en el celular:
   - **Android (Chrome):** menú ⋮ → **Instalar app** (o «Agregar a pantalla de inicio»).
   - **iPhone (Safari):** botón Compartir → **Agregar a inicio**.

Alternativa: Netlify (app.netlify.com) con una cuenta gratis; arrastra la carpeta completa en «Deploy manually».

Después de instalarla ya no necesitas volver a abrir la dirección: usa el ícono. En iPhone, la app instalada tiene un guardado separado del de Safari.

### ¿Quieres un APK de Android?

Con la app ya publicada, entra a pwabuilder.com, pega tu dirección y usa **Package for stores → Android**. Genera un APK que puedes instalar directamente en el teléfono.

## Usarla en el PC

Abre `index.html` con doble clic. Funciona y guarda el progreso en ese navegador, aunque sin ícono de app ni modo sin conexión (eso requiere la dirección `https`).

## Respaldos

En la pestaña **Inicio → Tu progreso**:

- **Descargar respaldo** guarda un archivo `.json` con todo lo marcado.
- **Cargar respaldo** lo restaura (en el mismo dispositivo o en otro).

Descarga un respaldo de vez en cuando: si desinstalas la app o borras los datos del navegador, el progreso se pierde.

## Si actualizas algún archivo

Cambia el número de versión de `minish-ra559-v2` (por ejemplo, a `minish-ra559-v3`) en `sw.js` y vuelve a subir los archivos. La app instalada se actualizará la próxima vez que la abras con internet. Tu progreso no se borra.
