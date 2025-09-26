# Tráfego Orgânico UTM Models

## Padrões GA4 Recomendados

### Parâmetros Obrigatórios

**UTM Source** - Origem do tráfego:
- `instagram`, `facebook`, `twitter`, `linkedin`
- `activecampaign`, `whatsapp`, `telegram`
- `mautic`, `rd`

**UTM Medium** - Tipo de tráfego:
- `social` - Redes sociais
- `social-network` - Redes sociais específicas  
- `sm` - Stories, bio, WhatsApp, Telegram
- `video` - Descrição de vídeo
- `organic` - Pesquisas orgânicas
- `referral` - Indicações/WhatsApp
- `email` - Email marketing

### Parâmetros Opcionais

**UTM Campaign** - Nome da campanha:
- `L30`, `JAN24`, `MAR24`, `L13`, `BF24`, `DIAMAES`
- Formatos: `base_antiga`, `grupos_antigos`, `grupos_atuais`

**UTM Content** - Público:
- `organico`

**UTM Term** - Diferenciação de links:
- `link_da_bio`, `instabio`
- `link_stories`, `instastories`
- `email_convite01_antigos`
- `msg_pesquisa01_atuais`

## Recomendações Gerais

- Use nomes descritivos e consistentes
- Evite caracteres especiais, espaços, acentos
- Utilize letras minúsculas
- Mantenha valores curtos e concisos

## Exemplo Instagram Bio

```
https://exemplo.com/oferta?utm_source=instagram&utm_medium=social&utm_campaign=BF24&utm_content=organico&utm_term=link_bio
```

## Exemplo WhatsApp

```
https://exemplo.com/oferta?utm_source=whatsapp&utm_medium=social&utm_campaign=L30&utm_content=organico&utm_term=msg_direta
```