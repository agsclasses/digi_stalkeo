# Stalkea a Lucía

Actividad de **Digitalización (4º ESO)** sobre privacidad, identidad y huella digital (bloque 3 del currículo de la Comunitat Valenciana).

El alumnado analiza el perfil de una red social ficticia de Lucía, una chica de 15 años inventada, y busca las 12 pistas que revelan dónde vive, sus rutinas, cuándo estará su casa vacía o cuál es su contraseña. Anota lo que descubre en un cuaderno de detective integrado en la página y lo copia al cuestionario de Aules/Moodle, que no está en este repositorio.

## Contenido

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La actividad completa (HTML, CSS y JavaScript en un solo archivo). Lleva una etiqueta `noindex` para que no aparezca en Google. |
| `.nojekyll` | Indica a GitHub Pages que sirva los archivos tal cual. |
| `.gitignore` | Evita subir por error el cuestionario o el solucionario. |

## Publicar en GitHub Pages

1. Crea un repositorio público nuevo, por ejemplo `stalkea-a-lucia`.
2. **Add file › Upload files**: sube `index.html` (y, si quieres, el resto de archivos) y pulsa **Commit changes**.
3. **Settings › Pages › Build and deployment**: en Source elige **Deploy from a branch**, en Branch elige `main` y `/ (root)`, y pulsa **Save**.
4. En uno o dos minutos la actividad estará en `https://TU-USUARIO.github.io/stalkea-a-lucia/`.

## Notas

- Lucía, sus amigos, Riubaix, el IES Riubaix, el CB Riubaix, la Cafetería Fornet y Fotogram son inventados. Las imágenes son dibujos, no fotos de personas reales.
- El cuaderno de detective se guarda solo en el navegador de cada alumno. La página no envía ningún dato a ningún sitio.
- Solo necesita conexión para cargar las tipografías de Google Fonts; sin conexión usa las del sistema.
