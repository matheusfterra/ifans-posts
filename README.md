# ifans-posts · Repositório de Posts

Portal de carrosseis e conteúdo Instagram do **ifans.click** — plataforma para criadores que monetizam sem pedir licença.

**URL pública:** `https://posts.ifans.click`

## Como adicionar novo post

1. Salvar o arquivo HTML do carrossel em `carousels/`
2. Adicionar entrada em `posts.json`
3. Adicionar entrada no array `POSTS` em `index.html`
4. Commitar e fazer push para `main` → deploy automático via Cloudflare Pages

## Estrutura

```
ifans-posts/
├── index.html          Portal principal (galeria + download + legendas)
├── posts.json          Registro de todos os posts
└── carousels/          Arquivos HTML de cada carrossel
```

## Tags disponíveis

- `viralizacao` — Conteúdo sobre o que está viralizando
- `engajamento` — Dicas de engajamento e algoritmo
- `monetizacao` — Roadmaps e estratégias de monetização
- `copywriting` — Hooks, ganchos e copy
- `analytics` — Métricas e análise de dados
