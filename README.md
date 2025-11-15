
# PSDI - Static Site (GitHub Pages)

Esta pasta contém um site estático (HTML/CSS) para o *Programa de Saúde Digital Integrado (PSDI)*.
Arquivos gerados:
- index.html
- funcionalidades.html
- arquitetura.html
- contato.html
- assets/logo.svg (placeholder)

## Como publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Faça commit dos arquivos desta pasta para o branch `main` (ou `gh-pages`).
3. No GitHub, vá em *Settings > Pages* e selecione o branch (`main`) e a pasta (`/`).
4. Salve — o site ficará disponível em `https://<seu-usuario>.github.io/<seu-repo>/`.

## Substituir sua logo
Substitua `assets/logo.svg` pelo seu arquivo de logo real (por exemplo `logo.png`):
- Se usar `logo.png`, mantenha o mesmo nome `assets/logo.svg` ou atualize a tag `<img>` nos arquivos HTML para apontar para `assets/logo.png`.

## Formulário de contato
- O formulário é estático e não envia mensagens por si só.
- Use Formspree, Netlify Forms, or GitHub Actions para integrar envios.
