# Facebook Ads UTM Models

## Parâmetros Dinâmicos do Facebook

- **Nome da Campanha**: `{{campaign.name}}`
- **Nome do Conjunto de Anúncios**: `{{adset.name}}`
- **Nome do Anúncio**: `{{ad.name}}`
- **Posicionamento**: `{{placement}}`

## Estrutura UTM Recomendada

```
UTM Campaign = {{campaign.name}}
UTM Medium = {{adset.name}}
UTM Source = {{placement}}
UTM Content = {{ad.name}}
```

## Exemplo de URL Final

```
https://exemplo.com/landing?utm_source={{placement}}&utm_medium={{adset.name}}&utm_campaign={{campaign.name}}&utm_content={{ad.name}}
```

## Exemplo Prático

```
https://exemplo.com/landing?utm_source=facebook&utm_medium=Conjunto_Interesse_Saude&utm_campaign=Lancamento_Produto_Julho&utm_content=Video_Testemunho_01
```

## Posicionamentos Comuns

- `facebook` - Feed do Facebook
- `instagram` - Feed do Instagram
- `instagram_stories` - Stories do Instagram
- `messenger` - Messenger
- `audience_network` - Audience Network