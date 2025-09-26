# Email Marketing UTM Models

## Estrutura Básica

```
utm_source=[plataforma]
utm_medium=email
utm_campaign=[nome_campanha_vendas]
utm_term=[identificador_email]
```

## Plataformas Suportadas

- `activecampaign`
- `mautic`
- `mailchimp`
- `rd` (RD Station)
- `sendgrid`
- `convertkit`

## Exemplos por Plataforma

### ActiveCampaign
```
utm_source=activecampaign
utm_medium=email
utm_campaign=L30
utm_term=email_convite01_antigos
```

**URL Exemplo:**
```
https://exemplo.com/oferta?utm_source=activecampaign&utm_medium=email&utm_campaign=L30&utm_term=email_convite01_antigos&utm_content=email_vendas
```

### Mautic
```
utm_source=mautic
utm_medium=email
utm_campaign=BF24
utm_term=email_promocao_01
```

### RD Station
```
utm_source=rd
utm_medium=email
utm_campaign=DIAMAES
utm_term=email_rec_abandono1
```

## Identificadores de Email (utm_term)

### Por Sequência:
- `email_convite01_antigos`
- `email_convite02_antigos`
- `email_rec_abandono1`
- `email_rec_abandono2`

### Por Público:
- `antigos` - Lista de contatos antigos
- `novos` - Lista de contatos novos
- `vip` - Lista VIP
- `prospect` - Prospects

### Por Tipo:
- `convite` - Email de convite
- `promocao` - Email promocional
- `abandono` - Recuperação de carrinho
- `nurturing` - Email de relacionamento
- `lancamento` - Email de lançamento

## Exemplo Completo - Sequência de Lançamento

```
https://exemplo.com/L30?utm_source=activecampaign&utm_medium=email&utm_campaign=L30&utm_term=email_convite03_vip&utm_content=sequencia_lancamento
```