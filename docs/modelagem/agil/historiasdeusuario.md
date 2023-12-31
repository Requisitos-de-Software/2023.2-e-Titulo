# Histórias de Usuário

## Introdução

Histórias de usuário é uma técnica de modelagem de requisitos no desenvolvimento de software ágil, que descreve funcionalidades do sistema do ponto de vista do usuário. Elas seguem uma estrutura simples, destacando o tipo de usuário, a ação desejada e o objetivo a ser alcançado.

## Objetivo
São usadas para comunicar necessidades do cliente e funcionalidades desejadas à equipe de desenvolvimento, facilitando a compreensão e implementação incremental. As histórias podem incluir critérios de aceitação para verificar a conclusão da funcionalidade. Em suma, as histórias de usuário melhoram a comunicação e mantêm o foco nas necessidades dos usuários no processo de desenvolvimento ágil.

## Metodologia

A elaboração das histórias de usuário foi baseada na técnica de priorização [Three Level Scale](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/priorizacao/threeLevelScale/), pegando assim os requisitos de alta prioridade para elaborar de forma mais concisa e acertiva, as histórias de usuário. Além disso, elas vão seguir o seguinte modelo estrutural:

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


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

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

<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

## Entrevista

<center style="max-width: 500px; margin: auto; align-items: center;">

Tabela 2 - Representação das Funções

| **Participante**                                        | **Função**     |
| :------------------------------------------------------ | :------------- |
| <span style = "color: orange"> Gustavo Marocolo </span>| Product Owner (P.O)  |
| [Mateus Orlando](https://github.com/MateusPy) | Desenvolvedor  |
| [João Costa](https://github.com/jvcostta)     | Entrevistador  |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

<iframe width="560" height="315" src="https://www.youtube.com/embed/aQaGBCykqTM?si=oqZp7iprVDeCnkBg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- Caso não consiga assistir dentro da gitPages [Clique aqui](https://www.youtube.com/embed/aQaGBCykqTM?si=oqZp7iprVDeCnkBg)



## Histórias de Usuário

### US01 - cadastro e login de usuário

Tabela 3 - Representação das Histórias de usuário

| ID     |      US01                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | cadastro e login de usuário |
| Rastreabilidade |  BS1, BS2 e INT2                                                         |
| Descrição |  Eu, como usuário, gostaria de realizar o cadastro de usuáio e biometria para realizar login por senha ou biometria no app.    |
| Situação Problema |   Possibilidade de acessar minha conta e prosseguir com as tarefas.                      |
| Critérios de Aceitação | 1. Deve ter um botão para cadastro e outro para login <br /> 2. Deve ser possível cadastrar na aplicação apenas se os campos “Nome do eleitor”, “Data de nascimento”, “Número de inscrição (título de eleitor)”, “Nome da mãe” e “Nome do pai” forem válidos. <br /> 3. Deve ser possível fazer o login apenas se os campos de usuário e senha forem válidos. <br /> 4. Só deve ser possível se a versão do dispositivo for compatível com a aplicação
| Status |  Validada                                                          |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


### US02 - Título de eleitor

Tabela 4 - Representação das Histórias de usuário

| ID     |      US02                                                                   |
| ------ | --------------------------------------------------------------------------- |
| Título | Título de eleitor. |
| Rastreabilidade |       INT5, INT9, INT11 e INT24                                                 |
| Descrição |    Eu, como usuário, gostaria de ter acesso ao meu título de eleitor no apicativo para visualizar o título, os dados, fazer download e alterar foto.   |
| Situação Problema |   Burocracia com impressão de papeis e esquecimento do documento no dia da eleição. |
| Critérios de Aceitação |   1. Deve ser possivel emitir o título apenas se o usuário estiver com todos os documentos adicionados no aplicativo já autênticados. <br /> 2. Deve ser possivel emitir o título apenas se o usuário estiver com a quitação eleitoral em dias. <br /> 3. Deve ter essa opção na aba de menu.   |
| Status |  Validada                                                          |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US03 - Visualizar candidato eleito

Tabela 5 - Representação das Histórias de usuário

| ID     |      US03                                                                   |
| ------ | --------------------------------------------------------------------------- |
| Título | visualizar candidato eleito |
| Rastreabilidade |                 ENT5, ENT9 e INTNF2                                              |
| Descrição |  Eu, como usuário, gostaria de visualizar o candidato eleito com transparencias em suas informações, incluindo criminal eleitora, referente ao ano da votação para manter-me informado.       |
| Situação Problema |  Dificuldade do cidadão de acessar a informação.                      |
| Critérios de Aceitação |  1. Deve ser possivel visualizar o candidato eleito apenas após a finalização das votações e resultado das eleições (consultado através do site TSE). <br /> 2. Deve ter essa opção na aba de menu.|
| Status |  Validada.                                 |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US04 - Acessar termo de uso

Tabela 6 - Representação das Histórias de usuário

| ID     |      US04                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | acessar termo de uso |
| Rastreabilidade |                 BS7 e BS8                                           |
| Descrição |  Eu, como usuário, gostaria de acessar e concordar com o termo de uso de forma fácil para leitura do mesmo.|
| Situação Problema | Dificuldade do usuário de entender as condições de uso, principalmente relacionados a segurança das informações privadas. |
| Critérios de Aceitação | 1. O termo de uso estará disponível na aplicação na página de conclusão na realização do cadastro. <br />2. o termo deve está disponível dentro da aplicação em qualquer situação que o usuário se encontre. <br /> 3. Deve ter essa opção na aba de menu.  |
| Status |  Validada                                                          |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US05 - Recuperar senha

Tabela 7 - Representação das Histórias de usuário

| ID     |      US05                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | recuperar senha. |
| Rastreabilidade |                 BS10                                              |
| Descrição | Eu, como usuário, gostaria de realizar a recuperação de senha para caso eu não consiga fazer o login.          |
| Situação Problema | Caso um usuário esqueça sua senha como ele poderia acessar o aplicativo novamente? |
| Critérios de Aceitação | 1. A recuperação de senha só deve ser possível caso o usuário já tenha um cadastro (consultar banco de dados). <br /> 2. Só deve ser possível se o usuário obtiver um endereço de email e/ou um número de telefone válidos. <br /> 3. Deve ter essa opção na página de login/cadastro.   |
| Status |   Validada                                                         |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US06 - Restrição abaixo dos 16 anos.

Tabela 8 - Representação das Histórias de usuário

| ID     |      US06                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | restrição abaixo dos 16 anos |
| Rastreabilidade |                 BSNF1                                             |
| Descrição | Eu, como usuário, gostaria que a aplicação fosse restrita para pessoas a partir de 16 anos para impedir que haja usuários não aptos a votar.   |
| Situação Problema | A votação no Brasil só é permitida para cidadãos que tenham 16 anos ou mais. |
| Critérios de Aceitação | 1. Só deve ser possível realizar o cadastro se o cidadão obtiver 16 anos ou mais. Validação será feita através da data de nascimento comparada a data atual. <br /> 2. Caso o usuário cadastrado tenha 17, 18 ou mais de 70 anos, uma mensagem na tela deve aparecer informando que a votação para esses usuários não é obrigatória. |
| Status |    Validada                                   |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US07 - Documentos

Tabela 9 - Representação das Histórias de usuário

| ID     |      US07                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | documentos |
| Rastreabilidade |                 INT15, INT16, INTNF3 e INT29                                           |
| Descrição | Eu, como usuário, gostaria poder visualizar os dados e autenticidade dos meus documentos para conferir se são autenticos.   |
| Situação Problema | Necessidade em saber se os documentos emitidos e adicionados são realmente autênticos. |
| Critérios de Aceitação | 1. Os documentos só podem ser emitidos caso o cadastro do usuário esteja completo, com dados verificados. <br /> 2. Os documentos emitidos devem obter um código de autênticidade emitido pelo TSE. <br /> 3. Deve ter essa opção na aba de menu.|
| Status |    Validada                                   |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US08 - Notificações

Tabela 10 - Representação das Histórias de usuário

| ID     |      US08                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Título | notificações |
| Rastreabilidade |                 INT6, INT26, INT27 e ENT7                                              |
| Descrição | Eu, como usuário, gostaria poder ser notificado sobre alertas de datas, atualizações eleitorais e horário de votação, pelo app para me manter informado e progamar-me no dia da votação. |
| Situação Problema | Dificuldade do cidadão em saber os horários de votação das instituiçôes, que podem mudar devido imprevistos. |
| Critérios de Aceitação | 1. As notificações começam aparecer 1 semana antes do início das votações. <br /> 2. Os horários disponíveis devem aparecer em relação a localização do usuário, mostrando os horários das regiões de votação mais próximas (com endereço). <br /> 3. Deve notificar o usuário após o login.  |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


### US09 - QR code

Tabela 11 - Representação das Histórias de usuário

| ID     |      US09                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | QR code |
| Rastreabilidade |                 INT30                                              |
| Descrição | Eu, como usuário, gostaria poder visualizar por meio do app, o QR code para a leitura do meu título. |
| Situação Problema | Leitura feita por um humano sugeita a erros. |
| Critérios de Aceitação | 1. O QR code deve ser gerado automaticamente após o usuário concluir o cadastro com sucesso. <br /> 2. O QR code deve aparecer na tela inicial após login.  |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US10 - Locação votação

Tabela 12 - Representação das Histórias de usuário

| ID     |      US10                                                                |
| ------ | -------------------------------------------------------------------------- |
| Título | Local de votação|
| Rastreabilidade |                 ST1, INT13, INT14 e QSTNF1                                             |
| Descrição | Eu, como usuário, gostaria poder visualizar por meio do app, o local de votação para planejar o local de partida e ver as rotas para o local de votação. |
| Situação Problema | Ter que pesquisar os locais de votação disponiveis. |
| Critérios de Aceitação | 1. O app deve fornecer um mapa da região onde o usuário se encontra. <br /> 2. ao clicar em uma instituição de votação o app fornece um trajeto como sugestão para o usuário.  |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US11 - Logoff

Tabela 13 - Representação das Histórias de usuário

| ID     |      US11                                                                |
| ------ | -------------------------------------------------------------------------- |
| Título | Logoff |
| Rastreabilidade |                 INT7                                              |
| Descrição | Eu, como usuário, gostaria poder fazer logoff(sair) do app para poder logar em outra conta. |
| Situação Problema | Fazer login e não conseguir sair afim de por exemplo, emprestar o celular com o app para outra pessoa. |
| Critérios de Aceitação | 1. O app deve possuir um botão para sair. <br /> 2. Ao clicar no botão deve haver um banner perguntando o usuário se ele tem certeza.  |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US12 - Alterar dados

Tabela 14 - Representação das Histórias de usuário

| ID     |      US12                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Alterar dados |
| Rastreabilidade |                 INT8 e INT21                                            |
| Descrição | Eu, como usuário, gostaria poder alterar e apagar meus dados pessoais e cadastrais para mudar algum dado que cadastrei errado. |
| Situação Problema | digitar algum dado errado. |
| Critérios de Aceitação | 1. Deve haver um botão que permite alterar os dados cadastrais. <br /> 2. ao finalizar as alterações o app deve emitir um banner pedindo para que o usuário confira os dados novamente para ter certeza. |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


### US13 -  Realizar quitação eleitoral

Tabela 15 - Representação das Histórias de usuário

| ID     |      US13                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Realizar quitação eleitoral |
| Rastreabilidade |                 ENT5                                             |
| Descrição | Eu, como usuário, gostaria poder realizar a quitação eleitoral para ficar apto a votar. |
| Situação Problema | Ter que se deslocar para realizar quitação eleitoral |
| Critérios de Aceitação | 1. Deve haver um botão que permite realizar quitação eleitoral. <br /> 2. Só deve ser possível se os cados cadastrais estiverem todos corretos. |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


### US14 - Suporte ao usuário

Tabela 16 - Representação das Histórias de usuário

| ID     |      US14                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Suporte ao usuário |
| Rastreabilidade |                 BS12, BS14, INT31 e INT32, INTNF1                                              |
| Descrição | Eu, como usuário, gostaria poder receber suporte do app, incluindo tutoriais, para situação em que eu me encontre com dúvidas. |
| Situação Problema | duvidas sobre o app. |
| Critérios de Aceitação | 1. Deve haver um botão que permite entrar em contato com o suporte. <br /> 2. Deve abrir um banner sugerindo acessar a área de perguntas frequentes. |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


### US15 - Arquivo

Tabela 17 - Representação das Histórias de usuário

| ID     |      US15                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Arquivo |
| Rastreabilidade |                 INT10 e INT20                                             |
| Descrição | Eu, como usuário, gostaria poder escolher o formato do arquivo quando fizer o download, para selecionar entre pdf ou doc. |
| Critérios de Aceitação | 1.Deve haver um botão de download. <br /> 2.Após clicar no botão de download deve ter as opções de pdf ou doc como escolha . |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


### US16 - Justificativa

Tabela 18 - Representação das Histórias de usuário

| ID     |      US16                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Justificativa  |
| Rastreabilidade |                 INT19                                            |
| Descrição | Eu, como usuário, gostaria poder informar minha justificativa diretamente no aplicativo, para proporcionar uma forma conveniente de cumprir esse procedimento. |
| Critérios de Aceitação | 1.Deve haver um botão de acesso a área de justificativa . <br /> 2.Deve haver um pequeno texto falando sobre o processo de justificativa. |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


### US17 - Débitos

Tabela 19 - Representação das Histórias de usuário

| ID     |      US12                                                                 |
| ------ | -------------------------------------------------------------------------- |
| Título | Débitos  |
| Rastreabilidade |                 INT28                                             |
| Descrição | Eu, como usuário, gostaria poder ter a capacidade de receber comprovação de meus débitos pelo aplicativo para quita-los. |
| Critérios de Aceitação | 1.Deve haver um botão de acesso a área de Débitos . <br /> 2.Deve haver um pequeno texto falando sobre o processo de débitos, incluindo como quita-los. |
| Status |  Validada                                    |


<font size="2"><p style="text-align: center"><b>Fonte: Costa, João e Orlando, Mateus 2023</b></p></font>

</center>



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
| `1.4`    | 06/11/2023 | Adicionando videos e links | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| `1.5`    | 30/11/2023 | corrigindo erros da inspeção | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| `1.6`    | 06/12/2023 | corrigindo erros da inspeção | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| `1.7`    | 07/12/2023 | mudando link da entrevista | [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|



