## LISTA COM O LINK DOS PORTFÓLIOS DOS APIs:
[API 1° SEMESTRE - **DANZO - Mapeador de Criminalidade ao Redor da FATEC**](https://github.com/ZVIEWIL/portifolio1) 

[API 2° SEMESTRE - **GANTT CHART**](https://github.com/ZVIEWIL/portifolio2)

[API 3° SEMESTRE - **CADASTRO POSITIVO**](https://github.com/ZVIEWIL/portifolio3)

# API do 3° SEMESTRE - ***FATEC & SPC BRASIL - CADASTRO POSITIVO***

### **RESUMO DO PROJETO**
No Terceiro API a Fatec trouxe o cliente SPC Brasil que nos desafiou em criar alguma aplicação que conseguisse agregar valor aos dados que eles possuem em sua base e fidelizar os usuários de maneira que eles utilizassem mais a plataforma do CADASTRO POSITIVO, que é como um histórico financeiro, mostrando como o usuário se comporta em relação a pagamentos de faturas, emprestimos, consórcios, financiamentos etc. 

Com base nos requisitos passados pelo cliente, desenvolvemos uma aplicação na qual:
- O Usuário se cadastra e realiza login(e-mail + senha);
- O Usuário consegue visualizar seu SCORE, histograma do SCORE, número de pendências financeiras e quantidade de vezes que o nome foi consultado;
- O Usuário consegue visualizar lista com seus histórico de pagamentos;
- O Usuário é fidelizado por gamificação, quanto mais ele permite acesso a seus dados na plataforma (pontos que podem ser acumulados e trocados); 
- O Usuário desbancarizado pode conseguir crédito (ao realizar seu cadastro e cadastrar suas transações em pequenos comércios);
- O Usuário configura as Permissões de Controle de Acesso aos seus dados (LGPD).

Tela de cadastro:

![Screenshot_1](https://user-images.githubusercontent.com/54503903/142959747-270e771e-941c-49de-8834-cd536bfc34ec.png)

Tela de login:

![Screenshot_2](https://user-images.githubusercontent.com/54503903/142959881-1d072b6b-88e2-4c92-834f-6d9b5672fd5f.png)

Tela de entrada, mostrando SCORE, Histograma do SCORE, Quantidade de consultas e pendências:

![Screenshot_3](https://user-images.githubusercontent.com/54503903/142959992-da8774b7-b924-47b4-b5be-7aa84fc06dca.png)

Permissão de acesso aos dados:

![Screenshot_4](https://user-images.githubusercontent.com/54503903/142960184-084fec98-2ade-4530-a647-5f525c8a7c20.png)

Pontos e Trocas:

![Screenshot_5](https://user-images.githubusercontent.com/54503903/142960233-605311dc-3832-4417-90e9-1aa752b31fd3.png)

Caderneta dos desbancarizados:

![Screenshot_6](https://user-images.githubusercontent.com/54503903/142960317-9ca5dd97-a4c3-4d7f-9b0a-b784952822d1.png)

Lista do Histórico de Pagamentos:

![Screenshot_7](https://user-images.githubusercontent.com/54503903/142960438-8fcf3271-2dc9-4216-83e5-f853d29e75b6.png)

### **TECNOLOGIAS UTILIZADAS**

#### **JAVA**
Continuamos utilizando para desenvolver o back end JAVA, como já tinhamos uma certa experiência, preferimos mante-la.

SpringBoot: O Spring Boot é um framework Java open source que tem como objetivo facilitar esse processo em aplicações Java. Consequentemente, ele traz mais agilidade para o processo de desenvolvimento, uma vez que devs conseguem reduzir o tempo gasto com as configurações iniciais. Usamos por Indicação de uma nova colega que entrou no grupo.

#### **TypeScript**
É uma linguagem de programação de código aberto desenvolvida pela Microsoft. É um superconjunto sintático estrito de JavaScript e adiciona tipagem estática opcional à linguagem. Utilizamos para desenvolver o front end.

#### **Angular**
É uma plataforma de aplicações web de código-fonte aberto e front-end baseado em TypeScript liderado pela Equipe Angular do Google e por uma comunidade de indivíduos e corporações. Angular é uma reescrita completa do AngularJS, feito pela mesma equipe que o construiu. Utilizamos para realizar as conexões entre os templates e configurar as requisições em JSON entre o front/back end.

#### **Node JS**
É um software de código aberto, multiplataforma, baseado no interpretador V8 do Google e que permite a execução de códigos JavaScript fora de um navegador web. Utilizamos ele para conseguir rodar a aplicação em Angular.

#### **Oracle Database** 
É um SGBD que surgiu no fim dos anos 70, quando Larry Ellison vislumbrou uma oportunidade que outras companhias não haviam percebido, quando encontrou uma descrição de um protótipo funcional de um banco de dados relacional e descobriu que nenhuma empresa tinha se empenhado em comercializar essa tecnologia.

#### **Insomnia**
Testamos nossas requisições através do Insominia, que é um API Client que facilita aos desenvolvedores criar, compartilhar, testar e documentar APIs. Utilizamos para testar as requisições criadas para nossa API.

#### **VSCode**
O Visual Studio Code é um editor de código-fonte desenvolvido pela Microsoft para Windows, Linux e macOS. Ele inclui suporte para depuração, controle de versionamento Git incorporado, realce de sintaxe, complementação inteligente de código, snippets e refatoração de código. Utilizei como IDE para trabalhar com o Angular.

#### **ECLIPSE**
IDE utilizada para desenvolver aplicações em Java. Utilizei como IDE para desenvolver o back end da aplicação.

### **CONTRIBUIÇÕES INDIVIDUAIS**
Esta API ajudei a desenvolver no Back e no Front End. Para realizar as tarefas precisei estudar Angular+SpringBoot+TypeScript.
Fiz um curso de 20 horas na Udemy que me ajudou a realizar as tarefas a que fui atribuido.

Algumas das Tarefas que realizei:
- Configurei o Authorization Server,  OAuth para utilizar tokens JWT e o Resource Server:

![Screenshot_1](https://user-images.githubusercontent.com/54503903/142968453-3bcb9ff7-abb3-4e23-ae39-6601845a2c22.png)
![Screenshot_2](https://user-images.githubusercontent.com/54503903/142968455-b69e3781-9728-4c1e-9082-f1f3b8578470.png)
![Screenshot_3](https://user-images.githubusercontent.com/54503903/142968462-a6ae5f8f-8d76-464a-b8f7-deaa35cf2792.png)

- Tratamento de Erros nas telas de Cadastro de clientes e login:

![Screenshot_10](https://user-images.githubusercontent.com/54503903/142965471-0f56030b-ed0b-463b-afde-c7614d3fa990.png)
![Screenshot_8](https://user-images.githubusercontent.com/54503903/142964045-bf11ce03-9c85-4d63-acc3-d574d7b95bf9.png)

- Autenticação dos dados a serem compartilhados - Usuário só visualiza os seus próprios dados

![Screenshot_11](https://user-images.githubusercontent.com/54503903/142965700-b814234d-d54a-4d62-9827-9cbb0445afc9.png)

- Requisição da Lista de Pagamentos realizados por determinado cliente Front ==> Back end:

![Screenshot_9](https://user-images.githubusercontent.com/54503903/142965152-40c3551f-5dc9-48db-ae69-6470ecc5b991.png)
![Screenshot_12](https://user-images.githubusercontent.com/54503903/142966341-1593ae7b-41d3-43bb-82ec-f03e5369c1d4.png)

- Conexão das Rotas das Telas do Front End:
![Screenshot_13](https://user-images.githubusercontent.com/54503903/142966588-935cafc8-c8fe-4658-932f-50ae31a74732.png)

### **APRENDIZADOS EFETIVOS**
#### **Angular + TypeScript** 
Aprendi a criar rotas entre as telas, receber e enviar requisições, como que funciona a criação dos módulos, aprendi um pouco de linguagem TypeScript, configurar o Navbar e Sidebar de forma que eles ficassem estáticos ao realizar a troca de páginas.

#### **JAVA + SpringBoot** 
Aprendi a criar uma aplicação SpringBoot(Maven), configurar e importar bibliotecas pelo POM, configurar a conexão com o banco de dados e oAuth no Application Properties, desenvolver as camadas do Spring (Entity, Repository, Controller, Service), Desenvolver utilizando o Lombok, Hibernate.

#### **Insomnia**
Aprendi a realizar testes de requisições (POST, GET, PUT, DELETE), configurar o JSON, realizar testes de requisição com Token configurando o Auth

#### **ECLIPSE**
Aprendi a configurar a IDE para rodar aplicações MAVEN (maven clean, maven install, maven updated);

#### **Node JS**
Aprendi a configurar o framework, e utiliza-lo. Hoje em dia utilizo Node para rodar além de aplicações Angular, aplicações em React.

#### **Oracle Database** 
Aprimorei a forma de realizar queries DML.

O API do 3° semestre foi o qual eu mais consegui me destacar e mostrar meus conhecimentos.


