# Estadísticas de ediciones de la wiki castellana de Dead by Daylight

Página interactiva con las aportaciones de cada editor a la [wiki castellana de Dead by Daylight](https://deadbydaylight.wiki.gg/es/) a lo largo del tiempo: ediciones y caracteres añadidos, quitados y netos, por fecha, usuario y espacio de nombres.

Se puede ver en <https://ojgarciab.github.io/dead-by-daylight-wiki-stats/>.

| Fichero | Contenido |
|---|---|
| `index.html` | La página, sin dependencias externas |
| `datos.js` | Historial de ediciones obtenido de la API pública de la wiki |

Los dos ficheros se generan en otro repositorio y llegan aquí automáticamente; no se editan a mano. Cada vez que cambia alguno de ellos, el flujo `.github/workflows/pages.yml` publica la página en GitHub Pages.
