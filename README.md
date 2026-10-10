# Base de conocimiento del Tutor CDIO

Sitio estático pensado para publicarse con GitHub Pages y usarse como fuente de conocimiento pública en Microsoft 365 Copilot Agent Builder.

## Contenido
- `index.html`: página principal y resumen de las 7 prácticas.
- `practica1.html` ... `practica7.html`: páginas específicas.
- `styles.css`: estilos simples.
- `.nojekyll`: evita procesamiento innecesario por Jekyll.
- `robots.txt`: permite el rastreo público.

## Publicación rápida
1. Crea un repositorio público nuevo en GitHub.
2. Sube **el contenido de esta carpeta** a la raíz del repositorio.
3. En GitHub ve a `Settings > Pages`.
4. En `Build and deployment`, selecciona `Deploy from a branch`.
5. Selecciona la rama `main` y la carpeta `/(root)`.
6. Guarda y espera a que GitHub muestre la URL pública.
7. Abre la URL en una ventana privada para comprobar que no pide iniciar sesión.
8. Pega la URL raíz en `Conocimiento > Escribir un vínculo` de Agent Builder.

No subas los PDFs originales si no quieres hacerlos públicos: esta web ya contiene un resumen técnico derivado de ellos.


## PDF originales
Los 7 PDF originales se encuentran en la raíz del repositorio. Las páginas HTML enlazan a cada PDF.
La web queda pensada para que el agente pueda recuperar tanto texto HTML estructurado como los documentos originales.

**Importante:** al publicar el repositorio con GitHub Pages, estos PDFs serán accesibles públicamente mediante URL.
