# Site com Decap CMS — Vicente Coimbra

Este pacote inclui:
- `index.html` (carrega conteúdo dinâmico via `content/settings.json` e `content/books.json`)
- `/admin/` com Decap CMS
- `/content/` com ficheiros JSON editáveis no CMS
- `/posts/` para artigos do blog (Markdown)
- `/images/uploads/` para imagens carregadas no CMS

## Como usar
1. Faça upload de tudo para o **GitHub** (repositório `vicente-coimbra-site`).
2. No **Netlify**: *Add new site → Import from GitHub* → selecione o repositório. Build command em branco, Publish directory `/`.
3. No site do Netlify: **Settings → Identity → Enable Identity**.
4. Em **Identity → Settings → Registration**, escolha **Invite only** (recomendado).
5. Em **Identity → Services**, ative **Git Gateway**.
6. Acesse `https://SEUSITE.netlify.app/admin` e clique **“Login”** (receberá um email de convite/validação).
7. Edite os conteúdos em **Definições do Site** e **Livros**, carregue capas em `/images/uploads/`, e publique.

## Nota
- Para a secção Livros, as capas devem ser referenciadas como `images/uploads/ficheiro.jpg`.
- O `index.html` lê o JSON e renderiza no browser, sem build.
- Os posts em `/posts` podem ser listados mais tarde na homepage com JavaScript adicional (posso adicionar).

Gerado em 2025-10-22.
