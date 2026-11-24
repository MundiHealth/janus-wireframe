# Janus Optimize — Wireframe exportável

Versão estática e independente do wireframe em português, preparada para aprovação visual e publicação em GitHub Pages.

## Páginas disponíveis

- `#home` — Home
- `#category` — Categoria / catálogo
- `#product` — Produto
- `#cart` — Carrinho
- `#checkout` — Checkout
- `#about` — Sobre
- `#faq` — Perguntas frequentes

## Visualização local

Na raiz do repositório:

```bash
python3 -m http.server 4173 --directory wireframe-export
```

Depois acesse `http://localhost:4173`.

Esta pasta é independente da implementação Bagisto. Após a aprovação visual, ela pode ser descartada ou mantida como referência, enquanto a implementação definitiva segue no pacote `JanusOptimize`.
