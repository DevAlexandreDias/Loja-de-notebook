# Loja de Notebook

Loja virtual de notebooks seminovos com laudo técnico, carrinho e pedido enviado pelo WhatsApp. É um protótipo em um único arquivo HTML, sem servidor.

**Site:** https://devalexandredias.github.io/loja-de-notebook/

## O que tem

- Catálogo com busca (ignora acentos), filtros por categoria e condição, ordenação e filtros na URL
- Página de cada aparelho com laudo técnico e consulta de entrega pelo CEP (ViaCEP)
- Carrinho salvo no navegador, com desfazer ao remover
- Finalização em 4 etapas que monta a mensagem do pedido e abre o WhatsApp
- Agendamento de conserto, lojas e dúvidas frequentes
- Feito para celular primeiro e acessível (teclado, contraste, leitores de tela)

## Como personalizar

No começo do `<script>` em `index.html`:

- `WA_NUMBER`: WhatsApp da loja com 55 + DDD (ex.: `'5583999999999'`). Vazio abre o WhatsApp para a pessoa escolher o contato.
- `STORES`: nomes e endereços das lojas.
- `PRODUCTS`: aparelhos, especificações, preços e dados do laudo.

Produtos e preços atuais são exemplos.
