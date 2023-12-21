# Quiz Faction 

App oficial da Expofred 2022 para a realização de pesquisas de satisfação com os frequentadores e expositores da feira.


## Sobre o app

  O Quiz Faction foi um app desenvolvido para atender a uma demanda de um grupo de pesquisadores da UFSM-FW (Universidade Federal de Santa Maria campus Frederico Westphalen - RS). Este grupo tinha por objetivo coletar dados de frequentadores e expositores da feira multissetorial da cidade de Frederico Westphalen, que fica na região norte do RS.

  Para facilitar a coleta de dados e opiniões dos entrevistados, o Quiz Faction possibilita preencher formulários personalizados para cada tipo de entrevistado, podendo funcionar sem a dependência de conexão com a internet no momento da entrevista. O entrevistador abre o formulário desejado e então preenche-o com os dados coletados e após a finalização do questionário, o mesmo é salvo localmente no dispositivo, em um banco de dados Sqlite. Posteriormente, é possível fazer o envio dos formulários para um servidor em nuvem (Firebase) onde todos os formulários preenchidos ficam salvos.
  
  O grande diferencial deste app, é a possibilidade de criar formulários personalizados e trabalhar de forma offline na maior parte do tempo, realizando a sincronização dos dados, uma vez ao dia!
  
  
## Telas do aplicativo
:iphone: *Como o app não está mais disponível em produção, pois o banco de dados ja foi desativado, deixo abaixo algumas imagens ilustrativas sobre o app*



:large_blue_circle: Telas de Login e Cadastro de Usuário

![login](https://user-images.githubusercontent.com/108557225/176982543-057b4cf6-9769-4de3-908d-1016402ec00d.png)  ![cadastro](https://user-images.githubusercontent.com/108557225/176982751-94c1543c-6d0a-4bd8-bd1f-f1f0379fc8d9.png)

:large_blue_circle: Listagem de questionários

![formularios](https://user-images.githubusercontent.com/108557225/176982620-cd4620f7-38c0-4729-9269-17997088c6b1.png)  ![formulario_2](https://user-images.githubusercontent.com/108557225/176983567-fe546438-a385-48bd-8b5c-9207aaa2a003.png)

:large_blue_circle: Questionário

![detalhe](https://user-images.githubusercontent.com/108557225/176983637-de6b3438-57ec-468f-99db-5c4f644fe936.png)  ![questionario](https://user-images.githubusercontent.com/108557225/176982684-d0b0c863-af60-4470-9b67-c4259db9ad7f.png)



## Recursos do app

 -  Autenticação com o Firebase Authentication;
 -  Segurança de formulários com definição de senha;
 -  Uso de forma offline utilizando banco de dados Sqlite;
 -  Persistencia de dados em nuvem com Firestore Database;


## Detalhes
  O Quiz Faction foi uma ideia que utilizei para desenvolver meu TGSI (trabalho de graduação de Sistemas de Informação - o famoso TCC) que tinha como estudo de caso, a Expofred 2022, uma feira de exposições que ocorre na minha cidade, Frederico Westphalen - RS. O projeto teve uma grande aprovação dos professores e outros interessados, onde então decidimos aplicá-lo durante a feira de exposições, como um projeto-piloto.
  Como esse app foi desenvolvido sob demanda, e o mesmo deveria ser de uso privado, decidi subir o apk para a nuvem, e disponibilizar o link de download apenas para uma lista de entrevistadores aprovados. A ideia deu certo, e ao final da feira, gerei um arquivo em excel, exportando todos os dados coletados para que as análises pudessem ser feitas.
  O app seguiu uma definição de projeto feita pelo grupo de pesquisadores, que passou a ideia principal, e através de algumas conversas, definimos a estrutura de funcionamento, gerenciamento e detalhes de layout.
  
  
  *Este foi meu primeiro projeto colocado em produção, onde pude aprender muito. Atualmente este aplicativo encontra-se desativado, por ter seu uso aplicado apenas durante a feira.*


# App Pet+ 

Um conjunto de aplicações voltadas para o ramo pet.


## Sobre o app

  Este é um grande projeto onde sou o responsável por todo o desenvolvimento das aplicações, desde o backend até o frontend. Este projeto consta com uma aplicação voltada para os tutores de pets e outra aplicação a ser utilizada por empresas do ramo pet, como clínicas veterinárias, petshops, dentre outros.
  O app dos tutores (Pet+) é uma aplicação que roda em Flutter, e estará disponível nas plataformas Android e iOS. Já a aplicação web, foi desenvolvida com o framework Flutter Web. O backend foi desenvolvido em Dart, e consta com requisições autenticadas por token jwt, envio de notificações, dentre outros.
  A plataforma permite com que tutores de pets realizem agendamentos de serviços das empresas parceiras, cadastramento de pets, controle de vacinação, busca por pets perdidos, dentre outros. Estou em fase final de desenvolvimento também, e próximo do lançamento das aplicações em produção. Já houveram avanços nas etapas de testes com uma clínica de conhecidos, que aprovaram o app.  
  
  
## Telas do aplicativo Pet+
:large_blue_circle: Login e página inicial

![login](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/ca58638b-4e79-459e-a7a3-fa0c018b8d5a) ![home](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/34594160-8aa6-4612-9fcc-1968baf76d58) ![drawer](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/690c262d-4ff4-4ed2-adce-1064e1a5ae1d)

:large_blue_circle: Agendamentos

![clinica](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/97cc9867-560c-4624-ade5-01b0f9d761b7) ![agendamento](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/2fb194ae-99ac-4493-b817-c132b859fec6) ![agendamentos](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/6f7551b1-054e-45fb-8631-f2396c809e9b)

:large_blue_circle: Pets e carteira de vacinação

![pets](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/59c5e84c-9f78-4c83-a911-c12129f70453) ![vacinas](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/bae116ac-a355-4a03-9da0-116aaf3c90e6)

## Telas da plataforma Web
:large_blue_circle: Login e página inicial

![login_web](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/68465ca6-cf00-45a0-b538-6e689fbbe651) ![home_web](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/aa47652b-7f7b-4219-b29b-cc24bb5edf60)

:large_blue_circle: Configurações, relatórios e controle de vacinas

![configuracoes_web](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/8cebbee6-0df6-46e3-a920-5c8787ad14f5) ![relatorios](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/b7fea9f3-ff4f-41bc-9a52-8ae805d0695d) ![vacinacoes](https://github.com/RodrigoMagalskiDev/Portfolio/assets/108557225/86b8ae3d-b866-4acd-a793-a8efb72cbeaa)


## Recursos do app

 -  Agendamento de serviços;
 -  Controle de vacinação de pets;
 -  Busca por pets perdidos;
 -  Notificações no app;
 -  Controle de permissões de funcionários na plataforma web;
 -  Relatórios gerenciais;
 -  Controle de agenda por serviço prestado



# P2Fit - Aplicativo para academias

  App destinado para uso de alunos de academias para controle e gerenciamento de treinos.


## Sobre o app

  O P2Fit é um projeto pessoal, o qual desenvolvo junto com outros tres colegas, onde sou o responsável pelo frontend mobile e web. A app está em fase final de desenvolvimento, muito próximo do seu lançamento e tem como propósito aproximar o aluno da academia permitindo com que o mesmo tenha um controle dos seus treinos, acessos de evoluções diárias, dentre outras informações. O aplicativo estará disponível nas plataformas Android e iOS. A plataforma web mencionada, utilizada pelo gestor da academia, foi desenvolvida em Typescript, a qual também fiz parte do desenvolvimento, mas não constará neste portfólio.
  
  
## Telas do aplicativo
:large_blue_circle: Login e página inicial

![login](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/652f2561-a6dd-402c-9e56-deac4dea0f9b) ![home](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/e3ff852f-f19d-461f-acd4-26e9ef0c79db)

:large_blue_circle: Contratos e Menu lateral

![contratos](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/d4a4284c-ee90-4a40-aa3c-a2139df247f2) ![drawer](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/0ab72caf-71ef-43cf-bb0b-5cf3358645a3)

:large_blue_circle: Treinos

![treinos](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/692ecf72-fc0c-42aa-beaf-57216c506843) ![exercicio](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/6167e3e4-7e2e-435d-b481-b30851276559)

:large_blue_circle: Perfil

![perfil](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/d8088160-1003-4355-83c5-96f01250f56e)
  

## Recursos do app

 -  Backend próprio com segurança nas requisições utilizando token jwt;
 -  Integração com Firebase Analytics, Crashlytics, Firebase Storage;
 -  Controle de versão mínima utilizando Firebase Remote Config;

  # 2K Fest 

App para venda de ingressos de evento promovido por uma ONG da cidade.


## Sobre o app

  O 2KFest foi um aplicativo criado juntamente com outro colega, onde utilizamos o Flutter Web aliado ao Firebase. O objetivo do aplicativo era realizar a venda de ingressos para um evento beneficiente promovido pelo Rotaract, clube da minha cidade que realiza ações sociais. 
  Inicialmente cadastramos todos os usuário dos responsáveis pela venda de ingressos no aplicativo, e então todos eles teriam acesso para vender os lotes disponíveis. Ao vender um ingresso, o mesmo informava alguns dados do comprador e após isso, o ingresso era enviado para o whatsapp informado. No dia do evento, ocorreu a validação dos ingressos, onde era necessário apresentar o ticket com o QrCode e então nosso aplicativo fazia a validação se era um QrCode válido e se o mesmo já tinha sido apresentado ou não. Validando, a pessoa estava liberada para acessar o evento.
  
  
## Telas do aplicativo
:large_blue_circle: Tela de Login do vendedor

![login](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/245628a7-6fbc-40a7-b24e-8dd29fdcca45)

:large_blue_circle: Lotes de Ingressos (informações pessoais ocultas aqui por questões de segurança)

![venda_ingressos](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/fcbaa97a-0dff-4438-bedc-6a591fcbd4fc) ![ingressos_1](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/c07a4352-e8d3-453a-bd46-86fc7c5de30b) ![venda](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/84d737e7-bd0c-4ba3-ae66-a6ef001feca9)

:large_blue_circle: Ticket

![ingressos_vendidos](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/81924c45-6fee-4519-aaf2-2b22e51d6e4e)

:large_blue_circle: Validação do Ingresso

![validacao](https://github.com/RodrigoMagalskiDev/Portf-lio/assets/108557225/ab6834f5-43aa-47e0-a5c7-9fdb0beb7ce0)
  

## Recursos do app

 -  Autenticação com o Firebase Authentication;
 -  Venda de ingressos com controle de quantidade por lote;
 -  Envio do ticket por whatsapp do comprador;
 -  Validação automática do ingresso com leitura de QrCode


## Detalhes
  O app foi desenvolvido em menos de uma semana para atender a urgente necessidade do clube para o evento. O uso do aplicativo foi um sucesso, onde o mesmo possivelmente será novamente utilizado em um futuro evento promovido pelo grupo.
