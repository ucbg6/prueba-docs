
## Prueba Docs

Esta es la página principal de documentación.

### Configuración de MkDocs (mkdocs.yml)
<pre>
  site_name: 'prueba-docs'
  repo_url: https://github.com/ucbg6/prueba-docs/
  
  # Indica que la documentación se encuentra 
  # en el mismo directorio que este fichero
  docs_dir: '.'

  nav:
   - Pagina principal: README.md
   - Backstage: docs/index.md
   - Otra pagina: docs/page2.md

  plugins:
   - techdocs-core
   - same-dir
  # Es necesario agregar este plugin para que MkDocs
  # permita esta configuración, de lo contrario dará error

  # pip3 install mkdocs-same-dir
  
</pre>

