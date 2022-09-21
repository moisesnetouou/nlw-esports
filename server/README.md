# Back-end

## Entidades

### Game

id
title
bannerUrl

CDN (Amazon S3) (Content Delivery Network) -> Serve os arquivos (url da imagem), mas vamos usar a da Twitch

### Ad

id
gameId
name
yearsPlaying
discord
weekDays
hourStart
hourEnd
useVoiceChannel
createdAt

<!-- 1:30 -> 90min
R$ 179,89 -> 17989

Datas (fuso horário / formatos diferentes i18n)
Pontos flutuantes -->

## Casos de uso - Como o usuário vai utilizar nossa aplicação

- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por game
- Buscar discord pelo ID do anúncio
