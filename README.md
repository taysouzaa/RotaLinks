# RotaLinks

Landing page simples para usar no link do Instagram (estilo “link na bio”), com logo, botões para marketplaces e botão para o site oficial.

## O que tem aqui

- `index.html`: página única (HTML + CSS + JS) pronta para hospedar.
- Tema **claro/escuro** com botão de alternância (salva preferência no `localStorage`).
- Layout responsivo (mobile e desktop).
- Botões com links para:
  - Site oficial
  - Mercado Livre
  - Amazon
  - Magalu
  - Shein
  - Shopee
  - TikTok Shop
  - Kwai Shop

## Estrutura

```
.
├─ index.html
├─ logo.rota.png
└─ assets/
   └─ marketplaces/
      ├─ amazon.webp
      ├─ kwai.ico
      ├─ magalu.webp
      ├─ mercado-livre.webp
      ├─ shein.webp
      ├─ shopee.webp
      └─ tiktok.ico
```

## Como usar (local)

1. Abra o arquivo `index.html` no navegador.
2. (Opcional) Para testar em celular, use o modo responsivo do DevTools.

## Como editar (links e logos)

- **Trocar os links**: edite os `href="..."` dos botões dentro de `index.html`.
- **Trocar a logo principal**: substitua o arquivo `logo.rota.png` (mantendo o mesmo nome) ou atualize o `src="logo.rota.png"` no `index.html`.
- **Trocar ícones/logos dos marketplaces**: substitua os arquivos em `assets/marketplaces/` e mantenha os nomes, ou atualize os `src="assets/marketplaces/..."` no `index.html`.

## Deploy (GitHub Pages)

1. Suba este repositório no GitHub.
2. Vá em **Settings → Pages**.
3. Em **Build and deployment**, selecione:
   - **Source**: *Deploy from a branch*
   - **Branch**: `main` e pasta `/ (root)`
4. Aguarde a publicação e use a URL gerada como link na bio.

## Observações

- A página usa a fonte **Sora** via Google Fonts.
- Marcas e logotipos citados pertencem aos seus respectivos proprietários.

## Desenvolvedora

- Taynara Correia de Souza
