# Lumae Skincare

Tema Shopify ficticio para portfolio, construido sobre o Dawn. A proposta e demonstrar uma loja premium de skincare com identidade visual propria, secoes customizadas em Liquid, templates Online Store 2.0 e documentacao de case.

## O que foi implementado

- Home customizada com hero editorial, colecao destaque, rotina em 3 passos, prova social e newsletter.
- Templates de colecao e produto ajustados para uma loja de skincare.
- Paginas customizadas para "Sobre" e "Case study".
- CSS de marca em `assets/lumae.css`.
- Secoes Liquid especificas:
  - `sections/lumae-hero.liquid`
  - `sections/lumae-routine.liquid`
  - `sections/lumae-editorial.liquid`
  - `sections/lumae-proof.liquid`
- Paleta premium: off-white, sage, ink e dourado discreto.
- Documentacao para configurar a loja e importar produtos ficticios.

## Como rodar com Shopify

1. Crie uma loja de desenvolvimento no Shopify Partner/Dev Dashboard.
2. Instale a Shopify CLI, se ainda nao tiver.
3. No terminal, dentro deste projeto, rode:

```bash
npx @shopify/cli@latest theme dev --store sua-loja.myshopify.com
```

4. No admin da Shopify, importe os produtos de `docs/lumae-products.csv`.
5. Crie as paginas `Sobre a Lumae` e `Case Study`, aplicando os templates `page.about` e `page.case-study`.
6. Configure o menu principal para apontar para Home, Catalogo, Sobre e Case Study.

Mais detalhes estao em `docs/SHOPIFY_SETUP.md`.

## Portfolio

Use `docs/CASE_STUDY.md` como base do texto do case. Depois de publicar ou visualizar a loja, complete o documento com prints reais da home, colecao, produto, carrinho e paginas institucionais.

## Base

Este projeto usa o Dawn, tema oficial de referencia da Shopify para Online Store 2.0. A licenca original esta preservada em `LICENSE.md`.
