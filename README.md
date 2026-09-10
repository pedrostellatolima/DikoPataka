# Diko Pataka — Site

Site institucional da **Diko Pataka**, escola de berçário e educação infantil no Brooklin, São Paulo.

🔗 **dikopataka.com.br**

## Estrutura

| Arquivo | Descrição |
|---|---|
| `index.html` | O site inteiro (HTML, CSS e JS em arquivo único) |
| `fotos-site/` | Fotos da escola usadas nas seções |
| `diko-drone-hero.mp4` | Vídeo aéreo exibido no topo |
| `FachadaDiko-1.png` | Imagem de espera do vídeo e prévia em redes sociais |
| `logo-redondo.png` | Logo (cabeçalho, rodapé e ícone da aba) |
| `robots.txt` / `sitemap.xml` | Arquivos de indexação para buscadores |

## Como editar

Todo o site está em `index.html`. Alterações enviadas para a branch `main` são publicadas
automaticamente pelo Cloudflare Pages, sem nenhum passo extra.

## Tecnologia

HTML, CSS e JavaScript puros. As únicas dependências são carregadas por CDN:
Google Fonts (DM Sans, Archivo, Caveat) e GSAP com ScrollTrigger para as animações.
