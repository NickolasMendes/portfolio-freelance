# Portfólio freelance

Site de portfólio do Nickolas Mendes: serviços, projetos e contato. HTML e CSS puros, sem build.

- `public/`: o site (página principal, `img/` com prints e `demos/` com projetos demonstrativos)
- Deploy: Cloudflare Workers (`wrangler.jsonc`), automático a cada push na `main`

Para ver localmente, sirva a pasta `public/` com qualquer servidor estático, por exemplo:

```bash
python -m http.server 5510 --directory public
```
