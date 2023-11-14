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
          * [Node.js](#Node_js)
          * [NPM](#NPM)
          * [Express](#Express)
          * [Pug](#Pug)
          * [Bootstrap](#Bootstrap)
          * [Javascript](#Javascript)
          * [CSS](#CSS)
          * [Jest](#Jest)
          * [Heroku](#Heroku)
          * [JawsDB MySQL](#JawsDB_MySQL)
      * [Estrutura do Projeto](#Estrutura_do_Projeto)
   * [Desenvolvimento](#Desenvolvimento)
      * [VS Code](#VS_Code)
      * [GitHub Copilot](#GitHub_Copilot)
      * [Git/GitHub](#Git_GitHub)
      * [MySQL Workspace](#MySQL_Workspace)
      * [Trello](#Trello)
      * [Slack](#Slack)
      * [Draw.io](#Draw_io)
      * [BR Modelo](#BR_Modelo)
      * [Figma](#Figma)
      * [Notion](#Notion)
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


## Node_js

> #### Node.js é um ambiente de execução de código aberto, multi-plataforma de JavaScript. Roda a partir do motor de execução V8, o mesmo utilizado em navegadores como Google Chrome, possibilitando uma grande performance do código sem comprometer o uso de recursos.

> #### O amplo suporte de sistemas de hospedagens e sistemas operacionais com suporte ao node, o uso da linguagem javascript, diminuindo a curva de aprendizado no uso da tecnologia, e o caráter assíncrono e orientado à eventos da linguagem a torna perfeita para aplicações web como a desenvolvida nesse projeto.


## NPM

> #### NPM ou Node Package Manager é o gerenciador de pacotes padrão do Node.js, utilizado para criar e gerenciar projetos, além de adicionar, gerenciar e remover dependências do projeto.

> #### A sua facilidade de uso e o fato de já vir instalado junto com o Node.js tornam o NPM um ótimo gerenciador de pacotes em meio a outras opções como o yarn.


## Express

> #### Express é um framework do Node.js utilizado para a construção de aplicações web, como sites ou APIs online.

> #### A sua flexibilidade de uso e a facilidade de aprendizado são os principais motivos para a escolha do express.


## Pug

> #### Pug, também conhecido como Jade, é uma linguagem e um motor de modelagem para transmitir dados recebidos do backend para o frontend e, consequentemente, para o usuário final.

> #### Por ser a linguagem padrão utilizada pelo express e pelo código mais limpo e legível criado com a linguagem o pug será utilizado o sucesso.


## Bootstrap

> #### Bootstrap é um framework web para criação de sites responsivos com maior facilidade e eficiência, sem precisar entrar em detalhes sobre o desenvolvimento de sites responsivos.

> #### A facilitação na criação de aplicações web mobile-friendly, além do aumento na velocidade de criação de páginas, minimizando a quantidade de estilos personalizados que serão criados, são os principais motivos da escolha dessa tecnologia para o projeto.


## Javascript

> #### Javascript, junto com html e css, é uma das principais tecnologias da World Wide Web, permitindo adicionar interatividade no website, essencial para qualquer projeto que será executado na web.


## CSS

> #### CSS ou Cascading Style Sheets é outra das principais tecnologias da World Wide Web, utilizada para dar personalidade às páginas, modificando as cores e os layouts dos elementos, essencial em qualquer projeto que será executado na web.


## Jest

> #### Jest é um framework de testes unitários para javascript. Seu foco na simplicidade e facilidade de aprender o torna um ótimo framework para o objetivo do projeto.


## Heroku

> #### Heroku é uma plataforma de hospedagem em nuvem com suporte a diversas linguagens, incluindo Node.js. Sua grande popularidade e documentação extensa permite que qualquer pessoa consiga hospedar um serviço web sem grandes problemas. Isso aliado ao plano de Estudante em parceria com o GitHub Students, que disponibiliza 13 dólares por mês para o uso na plataforma, tornam-o o serviço perfeito para a hospedagem do projeto.


## JawsDB_MySQL

> #### JawsDB é um serviço de banco de dados MySQL disponível no heroku como add-on na plataforma do heroku. O fato da existência de um plano gratuito para testes o torna uma grande ferramenta para a execução do projeto


## Estrutura_do_Projeto

| Diretório/Arquivo |    Função   |
| ----------------- | ----------- |
| /src                 | Diretório onde estão os arquivos principais do projeto, como arquivos de configuração, controladores, rotas, etc.|
| /configs                | Diretório de configuração do projeto, onde ficam armazenadas variáveis de configuração do projeto, como .env, db.config.js, general.config.js, etc. Todos os arquivos desse diretório tem a extensão .config.js.  |
| /controllers                 | Diretório dos controladores do projeto, que recebem e processam as requisições http vindas das rotas. Todos os arquivos dese diretório tem a extensão .controller.js.|
| /middlewares                 | Diretório das middlewares do projeto, cuidam dos processos de autenticação da aplicação, como login, verificação de pagamento, etc. Todos os arquivos desse diretório tem a extensão .middleware.js.|
| /public                 | Diretório onde os arquivos públicos do projeto são alocados, esses arquivos são os únicos que o usuário tem acesso direto.|
| /assets                 | Diretório onde todos os assets do projeto estão, como imagens, fontes, ícones, etc.|
| /css                 | Diretório onde as folhas de estilo da aplicação são criadas.|
| /js       |    Diretório onde os scripts da aplicação são criadas    |
| /views                 | Diretório onde as views do projeto estão, as views não são mostradas diretamente para o usuário, mas são renderizadas e convertidas para html no backend e enviadas para o usuário como resposta para a requisição http.|
| /routes                 | Diretório das rotas do projeto. Cada arquivo de rota agrupa um conjunto de rotas com finalidades relacionadas, como login e cadastro, etc. Todos os arquivos desse diretório tem a extensão .route.js.|
| /models                 | Diretório dos modelos dos dados da aplicação, contém o modelo dos dados do banco de dados que serão manipulados durante a execução da aplicação. Todos os arquivos desse diretório tem a extensão .model.js|
| /services                 | Diretório dos arquivos que controlam a lógica do sistema, como cadastrar um usuário ou gerar um cartão. Todos os arquivos desse diretório tem a extensão .service.js.|
| /utils                | Diretório dos arquivos que tem funções que são utilizadas por outros arquivos, como formatar um número de telefone. Todos os arquivos desse diretório tem a extensão .util.js.|
| /test                 | Diretório onde são armazenados os testes do projeto, são separados em testes unitários, testes de integração e testes de sistema. Todos o arquivos desse diretório tem a extensão .test.js.|
| /unit                 | Diretório dos arquivos de teste que testam um módulo ou uma parte de uma funcionalidade, são subdivididos da mesma maneira que o /src. Todos os arquivos desse diretório tem a extensão .unit.test.js.|
| /integration                 | Diretório dos arquivos de teste que testam funcionalidades inteira, com todos os seus módulos de uma vez. Todos os arquivos desse diretório tem a extensão .integration.test.js.|
| /system                 | Diretório dos arquivos de teste que fazem uma simulação do uso de uma funcionalidade como se fosse feita por um usuário real. Todos os arquivos desse diretório tem a extensão .system.test.js.|
| index.js                 | Arquivo raiz do projeto, onde todos os módulos do projeto são unidos para a criação efetiva da aplicação.|
| package.json                 | Arquivo que contém informações sobre o projeto, como o nome e a versão.|
| .gitignore                 | Diretório onde estão os arquivos principais do projeto, como arquivos de configuração, controladores, rotas, etc.|


## Desenvolvimento

### Esta seção descreve as ferramentas utilizadas diretamente no desenvolvimento da aplicação, mas não são necessárias para a utilização do projeto. São apenas recomendações para o ambiente de desenvolvimento.

### As tecnologias utilizadas e recomendadas para o desenvolvimento do projeto são:

- Visual Studio Code (VS Code) - Ambiente de Desenvolvimento Integrado (IDE);
- GitHub Copilot - Copiloto de desenvolvimento controlado por Inteligência Artificial (IA);
- MySQL Workspace - Gerenciamento do banco de dados;
- Git/GitHub - Armazenamento e Versionamento do Projeto;
- Trello - Gerenciamento do time;
- Slack - Plataforma de comunicação primária entre as partes do time;
- [Draw.io](http://Draw.io) - Modelagem de diagramas;
- BR Modelo - Modelagem do banco de dados;
- Figma - Prototipação do projeto;
- Notion - Confecção e manutenção da documentação.


## VS_Code

> #### VS Code ou Visual Studio Code é uma IDE open source desenvolvida e mantida pela microsoft, com sua grande variedade de extensões desenvolvidas pela própria comunidade e a variedade de customizações que podem ser feitas, o VS Code é uma das IDEs mais famosas que existem, e pode ser utilizada nas mais diversas linguagens, porém tem um foco especial no desenvolvimento com JavaScript e Node.js, tornado-a a perfeita para esse projeto.


## GitHub_Copilot

> #### O GitHub Copilot é o resultado da parceria entre a maior empresa de pesquisas relacionadas com inteligências artificiais, a OpenAI, e uma das maiores empresas de tecnologia existentes, a Microsoft.  O Copilot é uma ferramenta de auxílio ao desenvolvimento de software com as mais diversas funções, como sugestão e código, refatoração, criação de código a partir de uma frase ou perguntas sobre o funcionamento de certa tecnologia, tornando essa ferramenta um facilitador no processo de desenvolvimento, reduzindo o tempo gasto no desenvolvimento da aplicação.


## Git_GitHub

> #### Git é um sistema de versionamento de arquivos, usado para controlar diferentes versões do mesmo código que está sendo desenvolvido em diferentes máquinas. E GitHub é uma plataforma de hospedagem de código fonte utilizando o git.

> #### A partir da necessidade de compartilhamento do código fonte por entre os membros do time de desenvolvimento, torna-se indispensável o uso de um sistema de versionamento de código, e pela popularidade e facilidade de acesso a materiais que ensinam e demonstram o uso de Git e GitHub, eles foram escolhidos para a confecção deste projeto.


## MySQL_Workspace

> #### MySQL Workspace é uma ferramenta visual que integra desenvolvimento SQL, administração e design de banco de dados. Será usado para gerenciar tanto o banco de dados remoto quanto o local.


## Trello

> #### Trelo é um aplicativo de gestão de projetos baseado na web, sua utilização visa facilitar o processo de análise das etapas do projeto e organização das tarefas entre os membros da equipe.


## Slack

> #### Slack é uma plataforma de comunicação criada inicialmente para facilitar a comunicação do time, será utilizada como principal meio de comunicação entre os membros do time.


## Draw_io

> #### [Draw.io](http://Draw.io), também conhecido como [Diagrams.net](http://Diagrams.net) é uma plataforma para criação dos mais diversos tipos de diagramas, como diagramas de UML, diagramas de casos de uso, wireframes, etc.


## BR_Modelo

> #### BR Modelo é uma ferramenta de criação de modelos conceituais e lógicos de bancos de dados.


## Figma

> #### Figma é um editor gráfico de vetores e prototipagem de projetos de design. Será utilizado para a criação de protótipos de alto nível na fase de prototipagem do projeto.


## Notion

> #### Notion é uma aplicação web para gerenciamento de notas e informações online que pode ser compartilhada entre diversos dispositivos. Será utilizada para confecção e manutenção da documentação do projeto.


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




