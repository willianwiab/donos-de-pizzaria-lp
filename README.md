# Landing page

`index.html` é a primeira versão, single-file, em preto e amarelo, para apresentar ao Leandro. Abre direto no navegador.

## Seções

1. Hero: foto do Leandro com a Borda Vulcão, frase do projeto, provas (3 unidades, 4 anos, 4,7, Santos), botão da aula gratuita.
2. Os cinco degraus, do gratuito ao privado, com preços.
3. Quem ensina: Leandro e a Marikota, com a imagem da fachada.
4. Curso online: os 6 módulos.
5. A história: teaser do mini-documentário (placeholder) e 4 episódios de exemplo do podcast, com convidados.
6. Mentoria privada, aula presencial e assessoria por vídeo, com botão de WhatsApp.
7. Formulário da aula gratuita (nome, WhatsApp, cidade, fase).
8. Perguntas frequentes.
9. Rodapé e botão flutuante do WhatsApp.

## Sem valores

Por decisão do Will (2026-10-05), a LP não mostra preço de nenhum produto. Os degraus trazem só o formato ("Uma noite", "6 módulos", "Mensal", "10 vagas"), e a FAQ diz que valores são apresentados na conversa. Os preços vivem em `03-numeros/simulacao.md` e no deck.

## Documentário no hero

Quando o mini-documentário existir, o teaser de 2 minutos substitui a foto estática do hero (vídeo com play, sem autoplay com som). Até lá, a foto fica.

## O que é modelo e precisa trocar antes de publicar

- O formulário só mostra a confirmação; o envio real vai para o CRM do projeto (`08-crm/spec.md`).
- O número de WhatsApp `5511999999999` é fictício. Trocar pelo número do projeto.
- O teaser do documentário é um placeholder; o embed do YouTube entra quando existir. Os 4 episódios do podcast são exemplos.
- A data da aula gratuita está como "a definir".
- As imagens são geradas por IA a partir de foto real; `hero.png` tem texto gravado com erros ("Leandro Marikota", "Programa de Autoridade"). Trocar pela sessão real.
- Sem Google Tag, pixel ou domínio. Publicar na Vercel no domínio do Leandro quando ele registrar.

## Prévia no ar (GitHub Pages)

Esta pasta é um repositório próprio, público, só com a LP: https://github.com/willianwiab/donos-de-pizzaria-lp
Página: https://willianwiab.github.io/donos-de-pizzaria-lp/

Para atualizar: editar `index.html`, depois `git add -A && git commit -m "..." && git push`. O Pages republica em 1 a 2 minutos. Nunca colocar neste repositório nada das outras pastas do projeto (números, contrato, cartas de negociação): ele é público.

## Publicar

Quando aprovada: Vercel, projeto novo na conta do projeto (não na da WEN), domínio em nome do Leandro, UTM nas campanhas, formulário apontando para o CRM.
