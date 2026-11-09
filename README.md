# MJSTORE

Site da loja de moda masculina MJSTORE. É um site estático: um único arquivo `index.html`, sem etapa de build.

## Estrutura

- `index.html`: a loja inteira (visual, produtos, carrinho e página de compra)
- `assets/logo.png`: logo usada como ícone da aba do navegador

## Como editar

- **Produtos:** procure por `var PRODUCTS` dentro do `index.html` (nome, categoria, preço, selo e tamanhos).
- **Cupom:** procure por `var COUPON` e `var RATE` (código e porcentagem de desconto).
- **WhatsApp:** procure por `var WHATSAPP` (somente números, com 55 e DDD).
- **Link de pagamento:** procure por `var PAYMENT_LINK` e cole o link do Mercado Pago, InfinitePay ou similar. Enquanto estiver vazio, o botão de pagamento mostra um aviso.

## Publicar na Vercel

1. Em vercel.com, escolha **Add New → Project** e importe este repositório do GitHub.
2. Em **Framework Preset** deixe **Other**. Não precisa de build command nem de output directory.
3. Clique em **Deploy**. A cada alteração enviada ao GitHub, a Vercel publica de novo.
