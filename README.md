# IFID

> Status: Em Desenvolvimento

### O IFID é um projeto de teor independente com o objetivo de disponibilizar uma ferramenta online para criação e gerenciamento de crachás de identificação do IFPA Campus Belém partindo da matrícula do estudante.


Tabela de conteúdos
=================
<!--ts-->
   * [Documentação](#Documentação)
   * [Autores](#Autores)
   * [Projeto](#Projeto)
      * [Tecnologias](#Tecnologias)
          * [Node.js](#Node.js)
          * [NPM](#NPM)
          * [Express](#Express)
          * [Pug](#Pug)
          * [Bootstrap](#Bootstrap)
          * [Javascript](#Javascript)
          * [CSS](#CSS)
          * [Jest](#Jest)
          * [Heroku](#Heroku)
          * [JawsDB MySQL](#JawsDB_MySQL)
   * [Tests](#testes)
<!--te-->


## Documentação

> ### [Documentação do IFID] ([https://documentaçãoIFID](https://docs.google.com/document/d/1rpWPJLzkzfs-VpM3YVrIp-eR6A8Imf8qffkGM6C-FoQ/edit?usp=sharing))


## Autores

- [@liljmmiguel13](https://www.github.com/liljmmiguel13)
- [@Rodrifer2004](https://www.github.com/Rodrifer2004)
- [@nathil](https://www.github.com/nathil)
- [@murilo-henrique060](https://www.github.com/murilo-henrique060)


## Projeto

> ### Esta seção descreve as tecnologias utilizadas no projeto, além da estrutura do projeto, tanto de diretórios quando de arquivos.


## Tecnologias

### As técnicas utilizadas para alcançar os objetivos definidos nesta documentação são:

- Node.js - Tecnologia necessária para a utilização do javascript no backend;
- Node Package Manager (NPM) - Gerenciador de pacotes e configuração do projeto;
- Express - Framework javascript para criação de aplicações web;
- Pug (Jade) - Motor de modelagem para interação entre o backend e o frontend;
- Bootstrap - Camada de apresentação da aplicação;
- JavaScript - Adicionar as funcionalidades para os elementos da camada de apresentação;
- Cascading Styles Sheets (CSS) - Personalização da camada de apresentação;
- Jest - Framework de testes
- Heroku - Hospedagem do projeto;
- Jaws Mysql - Banco de dados.


## Node.js

> ### Node.js é um ambiente de execução de código aberto, multi-plataforma de JavaScript. Roda a partir do motor de execução V8, o mesmo utilizado em navegadores como Google Chrome, possibilitando uma grande performance do código sem comprometer o uso de recursos.

> ### O amplo suporte de sistemas de hospedagens e sistemas operacionais com suporte ao node, o uso da linguagem javascript, diminuindo a curva de aprendizado no uso da tecnologia, e o caráter assíncrono e orientado à eventos da linguagem a torna perfeita para aplicações web como a desenvolvida nesse projeto.


## NPM

> ### NPM ou Node Package Manager é o gerenciador de pacotes padrão do Node.js, utilizado para criar e gerenciar projetos, além de adicionar, gerenciar e remover dependências do projeto.

> ### A sua facilidade de uso e o fato de já vir instalado junto com o Node.js tornam o NPM um ótimo gerenciador de pacotes em meio a outras opções como o yarn.


## Express

> ### Express é um framework do Node.js utilizado para a construção de aplicações web, como sites ou APIs online.

> ### A sua flexibilidade de uso e a facilidade de aprendizado são os principais motivos para a escolha do express.


## Pug

> ### Pug, também conhecido como Jade, é uma linguagem e um motor de modelagem para transmitir dados recebidos do backend para o frontend e, consequentemente, para o usuário final.

> ### Por ser a linguagem padrão utilizada pelo express e pelo código mais limpo e legível criado com a linguagem o pug será utilizado o sucesso.


## Bootstrap

> ### Bootstrap é um framework web para criação de sites responsivos com maior facilidade e eficiência, sem precisar entrar em detalhes sobre o desenvolvimento de sites responsivos.

> ### A facilitação na criação de aplicações web mobile-friendly, além do aumento na velocidade de criação de páginas, minimizando a quantidade de estilos personalizados que serão criados, são os principais motivos da escolha dessa tecnologia para o projeto.


## Javascript

> ### Javascript, junto com html e css, é uma das principais tecnologias da World Wide Web, permitindo adicionar interatividade no website, essencial para qualquer projeto que será executado na web.


## CSS

> ### CSS ou Cascading Style Sheets é outra das principais tecnologias da World Wide Web, utilizada para dar personalidade às páginas, modificando as cores e os layouts dos elementos, essencial em qualquer projeto que será executado na web.


## Jest

> ### Jest é um framework de testes unitários para javascript. Seu foco na simplicidade e facilidade de aprender o torna um ótimo framework para o objetivo do projeto.


## Heroku

> ### Heroku é uma plataforma de hospedagem em nuvem com suporte a diversas linguagens, incluindo Node.js. Sua grande popularidade e documentação extensa permite que qualquer pessoa consiga hospedar um serviço web sem grandes problemas. Isso aliado ao plano de Estudante em parceria com o GitHub Students, que disponibiliza 13 dólares por mês para o uso na plataforma, tornam-o o serviço perfeito para a hospedagem do projeto.


## JawsDB_MySQL

> ### JawsDB é um serviço de banco de dados MySQL disponível no heroku como add-on na plataforma do heroku. O fato da existência de um plano gratuito para testes o torna uma grande ferramenta para a execução do projeto

## Funcionalidades

### As funcionalidades citadas a seguir derivam de nosso estudo com as Proto Personas indicadas em nossa documentação, não necessariamente representam as funcionalidades totais que serão implementadas, mas servem como guia e base para nossos esforços.

- Possibilidade de acessar o site pelo computador.
- Criar crachá sem fazer login.
- Exportar o crachá em PDF no tamanho correto para impressão.
- Possibilidade de fazer o download do crachá como PNG.
- Possibilidade de criar uma conta na aplicação para acessar os seus crachás de qualquer local.
- Acesso rápido ao crachá, abrindo-o assim que o usuário entra no aplicativo.
- Possibilidade de criar e armazenar uma série de crachás ao mesmo tempo.
- Possibilidade de exportar múltiplos crachás como PNG e como pdf para impressão.
- Possibilidade de compartilhar crachás como PNG pelo whatsapp.


## Tecnologias Utilizadas

