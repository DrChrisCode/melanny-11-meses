# Para Melanny · Nuestras canciones ♡

Sitio de aniversario diseñado para GitHub Pages. Incluye las letras **completas y originales** de `Not Style` y `I Tried to Hold Everything` con traducción **línea por línea**, modo EN/ES/bilingüe, diseño adaptable a móviles, botón para imprimir letras, enlaces Mureka y reproductor de audio HTML5.

## 1. Antes de publicarlo: colocar los MP3

El paquete aún **no incluye los archivos de audio MP3**. Los enlaces de Mureka son páginas para escuchar y no se pueden usar como URL de audio directo y fiable en un `<audio>` HTML5. Obtén/exporta de tu cuenta de Mureka tus dos canciones y guárdalas EXACTAMENTE con estos nombres:

- `audio/not-style.mp3`
- `audio/i-tried-to-hold-everything.mp3`

El sitio reconocerá las canciones y habilitará reproducción, pausa, avance, volumen y siguiente/anterior. Si faltan los MP3, mostrará la alternativa «Escuchar en Mureka».

## 2. Publicar en GitHub Pages

1. Inicia sesión en https://github.com y crea un repositorio (por ejemplo, `melanny-11-meses`).
2. **Descomprime** este ZIP en tu computadora. Sube a la raíz del repositorio el `index.html`, `lyrics.json`, `.nojekyll` y las carpetas `assets/` y `audio/`, manteniendo la estructura. No subas únicamente el `.zip` sin extraer.
3. En el repositorio, ve a **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
4. Selecciona la rama **main** y la carpeta **/(root)**; después pulsa **Save**.
5. GitHub publicará la página. En **Settings → Pages**, aparecerá su dirección cuando el despliegue termine.
6. Abre ese enlace desde tu celular y compártelo con Melanny.

## Archivos y funcionamiento

- `index.html`: web completa, sin dependencias externas (la letra está incluida en el HTML).
- `lyrics.json`: copia estructurada y editable del catálogo bilingüe.
- `assets/`: láminas de las canciones originales.
- `audio/`: donde deben colocarse los MP3 exportados.
- `.nojekyll`: permite publicar como sitio estático sin procesamiento Jekyll.

Para abrir la web en la computadora, haz doble clic en `index.html`. La reproducción directa solo funcionará cuando estén los MP3 con los nombres anteriores.

## Privacidad

**Importante:** GitHub Pages publica una web accesible a quien tenga la dirección, y en repositorios públicos el contenido del código y las letras también es público. Evita subir fotos o datos privados que no quieras compartir. El simple enlace no funciona como contraseña ni control de acceso.

## Nota sobre letras

El original en inglés se conserva sin cambios respecto a las letras aportadas por el autor. Las traducciones al español son versiones interpretativas línea por línea, no versiones cantables independientes.
