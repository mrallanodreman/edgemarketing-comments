# edgemarketing-comments

Backend de comentarios del blog de Edge Marketing usando [giscus](https://giscus.app) (comentarios guardados como GitHub Discussions de este repo).

Estado: **pendiente de inicializar** — el repo esta vacio.

## Como activarlo

1. En este repo: Settings > General > Features > activar **Discussions**.
2. Instalar la app [giscus](https://github.com/apps/giscus) sobre este repo.
3. En la pagina del blog, embeber el script de giscus apuntando a `mrallanodreman/edgemarketing-comments`:
   - `data-repo="mrallanodreman/edgemarketing-comments"`
   - `data-mapping="pathname"` (un hilo por post)
   - `data-category="Announcements"` (o la categoria que se cree)
4. Verificar comentando en un post y viendo el hilo en Discussions.

Repo principal del sitio: `mrallanodreman/edgemarketing-web`.
