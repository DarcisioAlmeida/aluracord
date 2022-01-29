### Imersão Alura React com NextJS 
| Detalhes desta aula
  Nesta primeira aula de React começaremos a fazer a nossa área de login no Aluracord! E você vai colocá-la no ar!

  Nesta aula vamos criar tudo do ZERO: desde o package.json até os arquivos bases do Next.js para iniciar nosso projeto e ter o CSS in JS com styled-jsx para cuidar da camada de estilo da nossa aplicação, duas ferramentas essenciais do mundo React. Também entenderemos como React se tornou tão popular no mercado de tecnologia e como iniciar o nosso aprendizado com a tecnologia.

| Conteúdo detalhado desta aula
  Iniciaremos um projeto Next.js;
  Criaremos components com React usando CSS in JS;
  Vamos ver a estrutura inicial de um projeto Next.js;
  Passaremos propriedades para components;
  Faremos deploy do seu Aluracord na Vercel.

Desafios desta aula!
 - Customizar o Aluracord com o SEU tema, seu background do assunto favorito (Filmes, Séries, Esportes, o desenho do coração)!, lembre-se de usar o Coolors que indicamos nesta aula, para gerar a paleta de cores.

 - Nosso arquivo de config com a parte das cores para você fazer o seu tema está aqui, use-o como base 😍
 
| Iniciar o projeto

  npx create-next-app --example with-styled-components
  # ou
  yarn create next-app --example with-styled-components

| Instalar e importar a lib de componentes brasileira totalmente integrada com o Next.js @skynexui/components

npm install @skynexui/components
# ou
yarn add @skynexui/components

E depois, no seu código importe:

  import { Box, Button, Text, TextField, Image } from '@skynexui/components';

| Repositório do Aluracord

  Aqui você consegue ver com detalhes as alterações de arquivos que fizemos: https://github.com/alura-challenges/aluracord-matrix/pull/1/files

| Links citados nesta aula
  React
  Mario Souto - Strategy Pattern
  Mario Souto - Pegando dados de uma API com React
  Mario Souto - O sistema de rotas do NextJS, principais dúvidas
  Mario Souto - Linter
  Mario Souto - Centralizar conteúdo na tela
  CSS Grid Garden
  Flexbox Froggy
  Mario Souto - Storybook na prática
  Mario Souto - Configurando ambiente JavaScript/NodeJS/Yarn
  Documentação interativa com Storybook do SkynexUI