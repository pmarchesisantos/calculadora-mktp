# Calculadora de Preço para Marketplaces

Calculadora de preço de venda para **Shopee**, **TikTok Shop** e **Mercado Livre**.
Você informa o custo do produto, embalagem, etiqueta e o lucro desejado, e ela calcula o preço de anúncio já com as taxas de cada plataforma, além de um comparativo entre as três.

## Funcionalidades
- Descobrir o preço de venda a partir do lucro desejado (em R$ ou % da venda)
- Simular um preço e ver lucro, margem e preço mínimo sem prejuízo
- Alertas de mudança de faixa de taxa
- Imposto, anúncios pagos e outros custos opcionais

## Taxas usadas (levantadas em 01/11/2026)
- **Shopee:** tabela por faixa de preço vigente desde 01/10/2026
- **TikTok Shop:** tabela vigente desde 15/07/2026 + Programa de Taxas de Envio
- **Mercado Livre:** tarifa por categoria (Clássico/Premium) + custos de envio por peso (reputação verde)

As plataformas mudam as taxas com frequência. Para atualizar, edite as tabelas no início do `<script>` em `index.html` (`SH_BANDS`, `tiktokFees`, `ML_SHIP`).

## Rodar localmente
É um site estático de um arquivo só: basta abrir `index.html` no navegador.

## Deploy
Projeto estático, sem build. Na Vercel: importe o repositório, deixe o Framework Preset como **Other** e publique.
