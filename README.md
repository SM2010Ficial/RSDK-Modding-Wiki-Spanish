<h1>
    <a href="#rsdk">
        <img width="120" align="left" src="docs/assets/icon.png">
    </a>
    RSDK Modding Wiki (Traduccion al español)
</h1>

Este es un sitio web con documentacion, recursos y guias para el modding del Retro Engine, este proyecto funciona gracias a [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) y inspirado en [HedgeDocs](https://hedgedocs.com/).

> [!WARNING]
> Este sitio (y la traduccion correspondiente) sigue en proceso. Puedes esperar informacion faltante o paginas vacias/placeholders. Todo esta sujeto a cambios.

## Contribuir

Esta wiki (y su traduccion) estan escritas en Markdown, como las de GitHub!. Una de las mejores maneras para escribir textos en formato Markdown es usar [Visual Studio Code](https://code.visualstudio.com/), con esta aplicacion podras ver una vista previa de la pagina que estas escribiendo precionando CTRL+Shift+V. Para que se vea mas exacto, deberias configurar el sitio localmente siguiendo las instrucciones en la seccion [Probando](#probando).

Apreciamos cada contribucion hecha para la wiki, cada aporte ayuda a que la comunidad de modding aumente y que se puedan hacer mejores mods.


### Añadiendo nuevas paginas

Añadir una pagina a la wiki es facil! luego de crear una difurcacion [de el repositorio original](https://github.com/RSDKModding/RSDK-Modding-Wiki), editalo siguiendo estos pasos:
1. Añade tu pagina en el lugar correcto editando el archivo `mkdocs.yml`. Incluso puedes crear nuevas secciones en tal caso no veas una seccion que se adecue a tus necesidades!
2. Crea un archivo con formato Markdown en la ubicacion que especificaste en el paso anterior, yahi tienes!

Luego de hacer tus contribuciones, abre un pull request, y si es aprobado, tu pagina se mostrara en la wiki para que todo el mundo lo vea.

### Material for MkDocs features

Since this wiki uses Material for MkDocs, you might want to check its [references](https://squidfunk.github.io/mkdocs-material/reference/) to better understand its features. You can use plain Markdown, but you can also use admonitions, buttons, and even icons from Font Awesome.

### Probando

Puedes probar los cambios que hisiste antes de subirlos en el pull request solo haciendo estos pasos:

- Descarga y luego instala [Python](https://www.python.org/downloads/)
- Descarga y luego instala Material For MkDocs y sus plug-ins necesarios: `pip install mkdocs-material mkdocs-glightbox --upgrade`
- Sube tu pagina Localmente: `mkdocs serve`
    - Tambien puedes crear una pagina estatica usando el comando `mkdocs build`

La version subida localmente se actualizara automaticamente al hacer algun cambio en los archivos.
