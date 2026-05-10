# Setup Shopify

## 1. Criar a loja

Crie uma development store pelo Shopify Partner/Dev Dashboard. Use o nome sugerido `lumae-skincare` ou outro nome disponivel. A conta e a loja precisam ser criadas no navegador, porque dependem do seu login Shopify.

## 2. Rodar o tema local

Dentro da pasta do projeto:

```bash
npx @shopify/cli@latest theme dev --store sua-loja.myshopify.com
```

Quando a CLI pedir login, entre com sua conta Shopify. A preview URL sera gerada pela propria CLI.

## 3. Importar produtos ficticios

No admin da Shopify:

1. Acesse Products.
2. Clique em Import.
3. Envie `docs/lumae-products.csv`.
4. Revise os produtos importados.
5. Adicione imagens reais ou mockups aos produtos para deixar o portfolio mais forte.

## 4. Criar colecoes

Crie estas colecoes:

- `All`, ou use a colecao automatica padrao.
- `Rotina essencial`, com todos os produtos da Lumae.
- `Tratamentos`, com Serum e Night Oil.
- `Kits`, com Complete Ritual Kit.

## 5. Criar paginas

Crie duas paginas no admin:

- `Sobre a Lumae`, usando o template `page.about`.
- `Case Study`, usando o template `page.case-study`.

## 6. Configurar navegacao

No menu principal, use:

- Home
- Catalogo
- Sobre
- Case Study

No footer, use links para:

- Catalogo
- Sobre a Lumae
- Case Study
- Politica de trocas
- Contato

## 7. Checklist antes de colocar no portfolio

- Home funciona em desktop e mobile.
- Produtos aparecem na colecao.
- Produto tem imagem, preco, descricao e variantes.
- Carrinho drawer abre, altera quantidade e remove produtos.
- Links do menu estao corretos.
- Paginas Sobre e Case Study usam os templates corretos.
- Loja tem senha anotada para enviar junto do link, caso continue como development store.
