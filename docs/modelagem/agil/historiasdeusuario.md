# Histórias de Usuário

## Introdução

Histórias de usuário é uma técnica de modelagem de requisitos no desenvolvimento de software ágil, que descreve funcionalidades do sistema do ponto de vista do usuário. Elas seguem uma estrutura simples, destacando o tipo de usuário, a ação desejada e o objetivo a ser alcançado.

## Objetivo
São usadas para comunicar necessidades do cliente e funcionalidades desejadas à equipe de desenvolvimento, facilitando a compreensão e implementação incremental. As histórias podem incluir critérios de aceitação para verificar a conclusão da funcionalidade. Em suma, as histórias de usuário melhoram a comunicação e mantêm o foco nas necessidades dos usuários no processo de desenvolvimento ágil.

## Metodologia

A elaboração das histórias de usuário foi baseada na técnica de priorização [Three Level Scale](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/priorizacao/threeLevelScale/), pegando assim os requisitos de alta prioridade (exceto a US03) para elaborar de forma mais concisa e acertiva, as histórias de usuário. Além disso, elas vão seguir o seguinte modelo estrutural:

<center style="max-width: 500px; margin: auto; align-items: center;">

### Título/Nome

Tabela 1 - Representação do modelo das Histórias de usuário

| ID     |      Código de identificação da história de usuário.                        |
| ------ | --------------------------------------------------------------------------- |
| Título | descrição resumida |
| Rastreabilidade | Requisito elicitado do qual a história veio.                       |
| Descrição | Descrição mais detalhada que deve responder (Quem?, "Por quê ?" e "Para quem ?").  |
| Situação Problema | O que motivou a criação dessa história?                                  |
| Critérios de Aceitação | condições que precisam ser atendidas para considerar a história como concluída e pronta para entrega. |
| Status | Se a história foi validada ou não pelo usuário.                       |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>


Para validar as histórias de usuário, foi buscado um usuário do e-título, Gustavo Marocolo, um estudante de Economia na UnB, que prontamente se ofereceu para avaliar as histórias desse artefato. Antes da realização da entrevista, o entrevistado recebeu o documento com antecedência e esclareceu suas dúvidas, a fim de agilizar e dinamizar a gravação. As histórias de usuário foram apresentadas no Miro, deixando a entrevista mais dinâmica.

## Miro

<p style="text-indent: 0px; text-align: justify">
A seguir está o quadro 1 do miro onde foi feita a dinâmica de histórias de usuários.
</p>

<p>Miro 1: Histórias de usuário</p>

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVNUXzCCc=/?moveToViewport=-4665,11228,30370,83414&embedId=864732936992" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>
<div style="text-align: center">
</div>

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

## Entrevista

<center style="max-width: 500px; margin: auto; align-items: center;">

Tabela 2 - Representação das Funções

| **Participante**                                        | **Função**     |
| :------------------------------------------------------ | :------------- |
| <span style = "color: orange"> Gustavo Marocolo </span>| Product Owner (P.O)  |
| [Mateus Orlando](https://github.com/MateusPy) | Desenvolvedor  |
| [João Costa](https://github.com/jvcostta)     | Entrevistador  |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

<iframe width="560" height="315" src="https://www.youtube.com/embed/Q7mb23aTHkQ?si=a2fWPZUzIEMBuf2x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<font size="3"><p style="text-align: center">Fonte: Grupo 4.</p></font>


- Caso não consiga assistir dentro da gitPages [Clique aqui](https://youtu.be/Q7mb23aTHkQ?si=DYe2QTmMCXfWrvCK)



## Histórias de Usuário

### US01

Tabela 3 - Representação das Histórias de usuário

| ID     |      US01                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | cadastro e login de usuário |
| Rastreabilidade |  BS1 e BS2                                                        |
| Descrição |  Eu, como cidadão, gostaria de realizar o cadastro e login de usuáio para usar no app.    |
| Situação Problema |   Possibilidade de acessar minha conta e prosseguir com as tarefas.                      |
| Critérios de Aceitação | 1. Deve ter um botão para cadastro e outro para login <br /> 2. Deve ser possível cadastrar na aplicação apenas se os campos “Nome do eleitor”, “Data de nascimento”, “Número de inscrição (título de eleitor)”, “Nome da mãe” e “Nome do pai” forem válidos. <br /> 3. Deve ser possível fazer o login apenas se os campos de usuário e senha forem válidos. <br /> 4. Só deve ser possível se a versão do dispositivo for compatível com a aplicação
| Status |  Validada                                                          |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


### US02

Tabela 4 - Representação das Histórias de usuário

| ID     |      US02                                                                   |
| ------ | --------------------------------------------------------------------------- |
| Título | emitir título. |
| Rastreabilidade |                 BS3                                                |
| Descrição |    Eu, como cidadão, gostaria de realizar a emissão do meu título de eleitor no apicativo para apresentar-me apto a votar.   |
| Situação Problema |   Burocracia com impressão de papeis e esquecimento do documento no dia da eleição. |
| Critérios de Aceitação |   1. Deve ser possivel emitir o título apenas se o usuário estiver com todos os documentos adicionados no aplicativo já autênticados. <br /> 2. Deve ser possivel emitir o título apenas se o usuário estiver com a quitação eleitoral em dias. <br /> 3. Deve ter essa opção na aba de menu.   |
| Status |  Validada                                                          |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US03

Tabela 5 - Representação das Histórias de usuário

| ID     |      US03                                                                   |
| ------ | --------------------------------------------------------------------------- |
| Título | visualizar candidato eleito |
| Rastreabilidade |                 ENT9                                               |
| Descrição |  Eu, como cidadão, gostaria de visualizar o candidato eleito referente ao ano da votação para manter-me informado.       |
| Situação Problema |  Dificuldade do cidadão de acessar a informação.                      |
| Critérios de Aceitação |  1. Deve ser possivel visualizar o candidato eleito apenas após a finalização das votações e resultado das eleições (consultado através do site TSE). <br /> 2. Deve ter essa opção na aba de menu.|
| Status |  NÃO validada. <br />Explicação do P.O: - Ja vemos esse tipo de informação em emissoras, redes sociais e dia a dia.                                   |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US04

Tabela 6 - Representação das Histórias de usuário

| ID     |      US04                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | acessar termo de uso |
| Rastreabilidade |                 ENTFNF1                                           |
| Descrição |  Eu, como usuário, gostaria de acessar o termo de uso de forma fácil para leitura do mesmo.|
| Situação Problema | Dificuldade do usuário de entender as condições de uso, principalmente relacionados a segurança das informações privadas. |
| Critérios de Aceitação | 1. O termo de uso estará disponível na aplicação na página de conclusão na realização do cadastro. <br />2. o termo deve está disponível dentro da aplicação em qualquer situação que o usuário se encontre. <br /> 3. Deve ter essa opção na aba de menu.  |
| Status |  Validada                                                          |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US05

Tabela 7 - Representação das Histórias de usuário

| ID     |      US05                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | recuperar senha. |
| Rastreabilidade |                 BS10                                              |
| Descrição | Eu, como usuário, gostaria de realizar a recuperação de senha para caso eu não consiga fazer o login.          |
| Situação Problema | Caso um usuário esqueça sua senha como ele poderia acessar o aplicativo novamente? |
| Critérios de Aceitação | 1. A recuperação de senha só deve ser possível caso o usuário já tenha um cadastro (consultar banco de dados). <br /> 2. Só deve ser possível se o usuário obtiver um endereço de email e/ou um número de telefone válidos. <br /> 3. Deve ter essa opção na página de login/cadastro.   |
| Status |   Validada                                                         |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US06

Tabela 8 - Representação das Histórias de usuário

| ID     |      US06                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | restrição abaixo dos 16 anos |
| Rastreabilidade |                 BSNF1                                             |
| Descrição | Eu, como usuário, gostaria que a aplicação fosse restrita para pessoas a partir de 16 anos para impedir que haja usuários não aptos a votar.   |
| Situação Problema | A votação no Brasil só é permitida para cidadãos que tenham 16 anos ou mais. |
| Critérios de Aceitação | 1. Só deve ser possível realizar o cadastro se o cidadão obtiver 16 anos ou mais. Validação será feita através da data de nascimento comparada a data atual. <br /> 2. Caso o usuário cadastrado tenha 17, 18 ou mais de 70 anos, uma mensagem na tela deve aparecer informando que a votação para esses usuários não é obrigatória. |
| Status |    Validada                                   |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US07

Tabela 9 - Representação das Histórias de usuário

| ID     |      US07                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | autenticidade de documentos |
| Rastreabilidade |                 INTNF9                                            |
| Descrição | Eu, como usuário, gostaria poder visualizar a autenticidade dos meus documentos para conferir se são autenticos.   |
| Situação Problema | Necessidade em saber se os documentos emitidos e adicionados são realmente autênticos. |
| Critérios de Aceitação | 1. Os documentos só podem ser emitidos caso o cadastro do usuário esteja completo, com dados verificados. <br /> 2. Os documentos emitidos devem obter um código de autênticidade emitido pelo TSE. <br /> 3. Deve ter essa opção na aba de menu.|
| Status |    Validada                                   |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US08

Tabela 10 - Representação das Histórias de usuário

| ID     |      US08                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | notificações |
| Rastreabilidade |                 ENT7                                              |
| Descrição | Eu, como usuário, gostaria poder visualizar por meio de notificações, os horários disponíveis para votação para progamar-me no dia da votação. |
| Situação Problema | Dificuldade do cidadão em saber os horários de votação das instituiçôes, que podem mudar devido imprevistos. |
| Critérios de Aceitação | 1. As notificações começam aparecer 1 semana antes do início das votações. <br /> 2. Os horários disponíveis devem aparecer em relação a localização do usuário, mostrando os horários das regiões de votação mais próximas (com endereço). <br /> 3. Deve notificar o usuário após o login.  |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

<center style="max-width: 500px; margin: auto; align-items: center;">

### US09

Tabela 11 - Representação das Histórias de usuário

| ID     |      US09                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | QR code |
| Rastreabilidade |                 BS4                                              |
| Descrição | Eu, como usuário, gostaria poder visualizar por meio do app, o QR code para a leitura do meu título. |
| Situação Problema | Leitura feita por um humano sugeita a erros. |
| Critérios de Aceitação | 1. O QR code deve ser gerado automaticamente após o usuário concluir o cadastro com sucesso. <br /> 2. O QR code deve aparecer na tela inicial após login.  |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US10

Tabela 12 - Representação das Histórias de usuário

| ID     |      US10                                                                |
| ------ | -------------------------------------------------------------------------- |
| Título | Local de votação|
| Rastreabilidade |                 BS6                                              |
| Descrição | Eu, como usuário, gostaria poder visualizar por meio do app, o local de votação para planejar meu dia de votação melhor. |
| Situação Problema | Ter que pesquisar os locais de votação disponiveis. |
| Critérios de Aceitação | 1. O app deve fornecer um mapa da região onde o usuário se encontra. <br /> 2. ao clicar em uma instituição de votação o app fornece um trajeto como sugestão para o usuário.  |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US11

Tabela 13 - Representação das Histórias de usuário

| ID     |      US11                                                                |
| ------ | -------------------------------------------------------------------------- |
| Título | Logoff |
| Rastreabilidade |                 INT7                                              |
| Descrição | Eu, como usuário, gostaria poder fazer logoff(sair) do app para poder logar em outra conta. |
| Situação Problema | Fazer login e não conseguir sair afim de por exemplo, emprestar o celular com o app para outra pessoa. |
| Critérios de Aceitação | 1. O app deve possuir um botão para sair. <br /> 2. Ao clicar no botão deve haver um banner perguntando o usuário se ele tem certeza.  |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US12

Tabela 14 - Representação das Histórias de usuário

| ID     |      US12                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Alterar dados |
| Rastreabilidade |                 INT8                                              |
| Descrição | Eu, como usuário, gostaria poder alterar meus dados cadastrais para mudar algum dado que cadastrei errado. |
| Situação Problema | digitar algum dado errado. |
| Critérios de Aceitação | 1. Deve haver um botão que permite alterar os dados cadastrais. <br /> 2. ao finalizar as alterações o app deve emitir um banner pedindo para que o usuário confira os dados novamente para ter certeza. |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

<center style="max-width: 500px; margin: auto; align-items: center;">

### US13

Tabela 15 - Representação das Histórias de usuário

| ID     |      US13                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Realizar quitação eleitoral |
| Rastreabilidade |                 ENT4                                             |
| Descrição | Eu, como usuário, gostaria poder realizar a quitação eleitoral para ficar apto a votar. |
| Situação Problema | Ter que se deslocar para realizar quitação eleitoral |
| Critérios de Aceitação | 1. Deve haver um botão que permite realizar quitação eleitoral. <br /> 2. Só deve ser possível se os cados cadastrais estiverem todos corretos. |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

<center style="max-width: 500px; margin: auto; align-items: center;">

### US14

Tabela 16 - Representação das Histórias de usuário

| ID     |      US14                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Suporte ao usuário |
| Rastreabilidade |                 ENT5                                              |
| Descrição | Eu, como usuário, gostaria poder receber suporte do app para situação em que me encontre com dúvidas. |
| Situação Problema | duvidas sobre o app. |
| Critérios de Aceitação | 1. Deve haver um botão que permite entrar em contato com o suporte. <br /> 2. Deve abrir um banner sugerindo acessar a área de perguntas frequentes. |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

<center style="max-width: 500px; margin: auto; align-items: center;">

### US15

Tabela 17 - Representação das Histórias de usuário

| ID     |      US12                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Apuração de votos |
| Rastreabilidade |                 ENT8                                              |
| Descrição | Eu, como usuário, gostaria poder acompanhar a apuração de votos para que eu fique informado de qualquer lugar em que eu consiga acessar o aplicativo. |
| Situação Problema | Acompanhamento pelas emissoras de TV. |
| Critérios de Aceitação | 1. Deve haver um botão que permite acessar e acompanhar a apuração. <br /> 2. Deve informar qual candidato está ganhando e ocm quantos %. |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


## Bibliografia
> Armin Eberlein  Department of Elec.&Comp. Engineering University of Calgary Calgary, AB T2N 1N4 Canada. Agile Requirements Definition: A View from Requirements Engineering. Acesso em: 03 nov. 2023.
> Simone D.J. Barbosa. Interação Humano-Computado  [https://leanpub.com/ihc-ux](https://leanpub.com/ihc-ux). Acesso em: 03 nov. 2023.
> Alves, Douglas e Maciel, Geovanna. Perfil do Usuário. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: [https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital/blob/main/docs/modelagem/agil/historia-de-usuario.md](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital/blob/main/docs/modelagem/agil/historia-de-usuario.md). Acesso em: 03 nov. 2023.
> Alvissus, Giovanni. Historias de Usuário. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: [https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/modelagem/userStories.md](https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/modelagem/agil/historias_de_usuarios.md). Acesso em: 03 nov. 2023.
> Correia, João Victor e Perillo, Matheus. Historias de Usuário. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: [https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/modelagem/userStories.md](https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/modelagem/userStories.md). Acesso em: 03 nov. 2023.

## Histórico de Versões

| Versão | Data       | Descrição                                      | Autor(es)                                        | Revisor(es)   |
| ------ | ---------- | ---------------------------------------------- | ------------------------------------------------ | ------------------------ |
| `1.0 `   | 28/10/2023 | Criação da página | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| `1.1`    | 02/11/2023 | Início das Histórias de Usuário | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| `1.2`    | 03/11/2023 | Finalizando Histórias de Usuário | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| `1.3`    | 06/11/2023 | Adicionando videos e links | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| `1.3`    | 06/11/2023 | Adicionando videos e links | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| `1.4`    | 30/11/2023 | corrigindo erros da inspeção | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|


