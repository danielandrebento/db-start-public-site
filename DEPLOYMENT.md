# Publicação do site público DB Start

A pasta `public-site/` é inteiramente estática e não requer build, base de dados, JavaScript ou backend.

## URLs que devem existir depois do alojamento

- `/` — página pública do DB Start.
- `/privacy.html` — Política de Privacidade PT-PT + EN completa.
- `/support.html` — página de suporte PT-PT + EN.

As URLs finais devem usar HTTPS e permanecer estáveis após a publicação nas lojas.

## Plataformas compatíveis

Pode ser publicada diretamente em serviços de alojamento estático como Netlify, Cloudflare Pages, GitHub Pages ou equivalente. A pasta a publicar é exatamente `public-site/`.

O ficheiro `_headers` adiciona cabeçalhos de segurança em plataformas que suportem esta convenção. Plataformas que não o suportem podem ignorá-lo sem afetar o conteúdo do site.

## Antes de preencher as lojas

1. Publicar a pasta.
2. Abrir as três páginas num browser normal e confirmar HTTPS.
3. Confirmar que os logótipos e estilos carregam sem erros.
4. Guardar os URLs finais em `docs/PUBLIC_RELEASE_CHECKLIST.md` e `docs/STORE_SUBMISSION_PACK.md`.
5. Só depois submeter os formulários de privacidade das lojas.
