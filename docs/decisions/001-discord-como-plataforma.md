# ADR 0001 — Discord como plataforma da Ember

## Status
Aceito

## Contexto
A Ember é uma companheira digital pessoal. Ela precisa de um lugar para
"morar" onde eu já passo tempo naturalmente, com boa integração e sem
expor o bot a ataques externos enquanto ainda está em desenvolvimento.

## Decisão
A Ember vai rodar como um bot de Discord, hospedada inicialmente no meu
servidor pessoal (privado).

## Alternativas consideradas
- **App web própria**: exigiria construir interface do zero e não é
  onde eu de fato passaria tempo com ela no dia a dia.
- **WhatsApp/Telegram**: APIs mais restritas para esse tipo de uso e
  menos familiaridade minha com o ecossistema.

## Consequências
- Dependo da API e das regras do Discord (discord.js).
- Ficando em servidor privado, a superfície de ataque é menor.
- Se um dia ela ficar pública, terei que revisitar segurança e limites
  de uso (rate limiting, permissões).
