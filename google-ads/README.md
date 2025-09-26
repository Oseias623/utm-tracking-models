# Google Ads UTM Models

## Código Padrão Principal

```
{lpurl}?utm_campaign={_campanha}&utm_source={_origem}&utm_medium={_midia}&utm_content={_conteudo}&utm_term={keyword}
```

## Código Alternativo

```
{lpurl}?utm_source={network}&utm_medium={adgroupid}&utm_campaign={campaignid}&utm_content={adid}&utm_term={keyword}
```

## Lista de Parâmetros ValueTrack

### utm_campaign={_campanha}
- **Definição**: Nome da campanha, produto ou lançamento
- **Exemplos**: `GPS`, `ITC`, `L1`

### utm_source={_origem}
- **Definição**: Origem do tráfego
- **Exemplos**: `Google_Ads`, `Youtube_Ads`, `Display_Ads`

### utm_medium={_midia}
- **Definição**: Nome do grupo de anúncios
- **Exemplos**: `Grupo_01_Dor_Nas_Costas`, `Grupo_02_Dores_Na_Coluna`

### utm_content={_conteudo}
- **Definição**: Nome do anúncio
- **Exemplos**: `ADV_01`, `AD_01_Responsivo`

### utm_term={keyword}
- **Definição**: Palavra-chave do anúncio (dinâmica)
- **Exemplos**: `como comprar casa`, `como vender lote`, `como vender pela internet`

## Exemplo Prático

```
https://exemplo.com/landing?utm_campaign=GPS&utm_source=Google_Ads&utm_medium=Grupo_01_Dor_Nas_Costas&utm_content=ADV_01&utm_term=tratamento+dor+nas+costas
```