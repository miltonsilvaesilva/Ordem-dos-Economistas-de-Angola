# O.E.A. — Ordem dos Economistas de Angola

Página temporária "em construção" do portal da Ordem dos Economistas de Angola.

Site estático (HTML + CSS + JS, sem build). Para ver localmente basta abrir `index.html` no navegador.

## Estrutura

```
index.html                     página única
assets/img/oea-icone.webp      emblema (ícone) usado no destaque
assets/img/oea-logo-*.webp     logótipos principal e horizontal (reserva)
assets/img/favicon-32.png      favicon
assets/img/apple-touch-icon.png
assets/img/icone-512.png       imagem de partilha (redes sociais)
.nojekyll                      publica os ficheiros tal como estão
```

## Identidade aplicada

| Cor | Hex |
|---|---|
| Ouro Institucional | `#D4AF37` |
| Carvão Profundo | `#1F1A14` |
| Marfim | `#F9F7EE` |
| Vermelho Angola (acento) | `#B51E26` |
| Verde Resiliência (apoio) | `#0F5A3C` |

Tipografia: Cinzel (títulos), Cormorant Garamond (subtítulos), Source Sans 3 (texto).

## Publicação (GitHub Pages)

1. No GitHub: **Settings → Pages**.
2. Em **Source** escolher **Deploy from a branch**.
3. Escolher o ramo e a pasta `/ (root)` e guardar.
4. O site fica disponível em `https://<utilizador>.github.io/<repositório>/`.

Cada `git push` para esse ramo atualiza o site automaticamente.

## Atualizar o progresso

No `index.html`, alterar `const PROGRESSO = 3;` e as classes da lista de módulos
(`feito` = concluído, `curso` = em curso).
