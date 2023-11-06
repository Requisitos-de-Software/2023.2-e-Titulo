# Histórias de Usuário

## Conceito

Histórias de usuário é uma técnica de modelagem de requisitos no desenvolvimento de software ágil, que descreve funcionalidades do sistema do ponto de vista do usuário. Elas seguem uma estrutura simples, destacando o tipo de usuário, a ação desejada e o objetivo a ser alcançado. São usadas para comunicar necessidades do cliente e funcionalidades desejadas à equipe de desenvolvimento, facilitando a compreensão e implementação incremental. As histórias podem incluir critérios de aceitação para verificar a conclusão da funcionalidade. Em suma, as histórias de usuário melhoram a comunicação e mantêm o foco nas necessidades dos usuários no processo de desenvolvimento ágil.

## Metodologia

A elaboração das histórias de usuário foi baseada na técnica de priorização [Three Level Scale](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/priorizacao/threeLevelScale/), pegando assim os requisitos de alta prioridade (exceto a US03) para elaborar de forma mais concisa e acertiva, as histórias de usuário. Além disso, elas vão seguir o seguinte modelo estrutural:

<center style="max-width: 500px; margin: auto; align-items: center;">

### Título/Nome

| ID     |      Código de identificação da história de usuário.                        |
| ------ | --------------------------------------------------------------------------- |
| Rastreabilidade | Requisito elicitado do qual a história veio.                       |
| Descrição | Descrição mais detalhada que deve responder (Quem?, "Por quê ?" e "Para quem ?").  |
| Situação Problema | O que motivou a criação dessa história?                                  |
| Critérios de Aceitação | condições que precisam ser atendidas para considerar a história como concluída e pronta para entrega. |
| Status | Se a história foi validada ou não pelo usuário.                       |

Tabela 1 - Representação do modelo das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>


Para validar as histórias de usuário, foi buscado um usuário do e-título, Gustavo Marocolo, um estudante de Economia na UnB, que prontamente se ofereceu para avaliar as histórias desse artefato. Antes da realização da entrevista, o entrevistado recebeu o documento com antecedência e esclareceu suas dúvidas, a fim de agilizar e dinamizar a gravação. As histórias de usuário foram apresentadas no Miro, deixando a entrevista mais dinâmica.

## Miro

<p style="text-indent: 0px; text-align: justify">
A seguir está o quadro miro onde foi feita a dinâmica de histórias de usuários.
</p>


<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVNUXzCCc=/?moveToViewport=-4665,11228,30370,83414&embedId=864732936992" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>
<div style="text-align: center">
<p>Miro 1: Histórias de usuário</p>
</div>

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

## Gravação

- Caso não consiga assistir dentro da gitPages, [Clique aqui](https://youtu.be/Q7mb23aTHkQ?si=DYe2QTmMCXfWrvCK)

<iframe width="560" height="315" src="https://www.youtube.com/embed/Q7mb23aTHkQ?si=a2fWPZUzIEMBuf2x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<font size="3"><p style="text-align: center">Fonte: Grupo 4.</p></font>

### A Entrevista

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Participante**                                        | **Função**     |
| :------------------------------------------------------ | :------------- |
| <span style = "color: orange"> Gustavo Marocolo </span>| Product Owner (P.O)  |
| [Mateus Orlando](https://github.com/MateusPy) | Desenvolvedor  |
| [João Costa](https://github.com/jvcostta)     | Entrevistador  |

Tabela 2 - Representação das Funções

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

## Histórias de Usuário

### US01

| ID     |      US01                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Rastreabilidade |  BS1 e BS2                                                        |
| Descrição |  Eu, como cidadão, gostaria de realizar o cadastro e login de usuáio.    |
| Situação Problema |   Possibilidade de acessar minha conta e prosseguir com as tarefas.                      |
| Critérios de Aceitação | 1. Deve ter um botão para cadastro e outro para login <br /> 2. Deve ser possível cadastrar na aplicação apenas se os campos “Nome do eleitor”, “Data de nascimento”, “Número de inscrição (título de eleitor)”, “Nome da mãe” e “Nome do pai” forem válidos. <br /> 3. Deve ser possível fazer o login apenas se os campos de usuário e senha forem válidos. <br /> 4. Só deve ser possível se a versão do dispositivo for compatível com a aplicação
| Status |  Validada                                                          |

Tabela 3 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">


### US02

| ID     |      US02                                                                   |
| ------ | --------------------------------------------------------------------------- |
| Rastreabilidade |                 BS3                                                |
| Descrição |    Eu, como cidadão, gostaria de realizar a emissão do meu título de eleitor no apicativo.   |
| Situação Problema |   Burocracia com impressão de papeis e esquecimento do documento no dia da eleição. |
| Critérios de Aceitação |   1. Deve ser possivel emitir o título apenas se o usuário estiver com todos os documentos adicionados no aplicativo já autênticados. <br /> 2. Deve ser possivel emitir o título apenas se o usuário estiver com a quitação eleitoral em dias. <br /> 3. Deve ter essa opção na aba de menu.   |
| Status |  Validada                                                          |

Tabela 4 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US03

| ID     |      US03                                                                   |
| ------ | --------------------------------------------------------------------------- |
| Rastreabilidade |                 ENT9                                               |
| Descrição |  Eu, como cidadão, gostaria de visualizar o candidato eleito referente ao ano da votação.       |
| Situação Problema |  Dificuldade do cidadão de acessar a informação.                      |
| Critérios de Aceitação |  1. Deve ser possivel visualizar o candidato eleito apenas após a finalização das votações e resultado das eleições (consultado através do site TSE). <br /> 2. Deve ter essa opção na aba de menu.|
| Status |  NÃO validada. <br />Explicação do P.O: - Ja vemos esse tipo de informação em emissoras, redes sociais e dia a dia.                                   |

Tabela 5 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US04

| ID     |      US04                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Rastreabilidade |                 ENTFNF1                                           |
| Descrição |  Eu, como usuário, gostaria de acessar o termo de uso de forma fácil para leitura do mesmo.|
| Situação Problema | Dificuldade do usuário de entender as condições de uso, principalmente relacionados a segurança das informações privadas. |
| Critérios de Aceitação | 1. O termo de uso estará disponível na aplicação na página de conclusão na realização do cadastro. <br />2. o termo deve está disponível dentro da aplicação em qualquer situação que o usuário se encontre. <br /> 3. Deve ter essa opção na aba de menu.  |
| Status |  Validada                                                          |

Tabela 6 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US05

| ID     |      US05                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Rastreabilidade |                 BS10                                              |
| Descrição | Eu, como usuário, gostaria de realizar a recuperação de senha.          |
| Situação Problema | Caso um usuário esqueça sua senha como ele poderia acessar o aplicativo novamente? |
| Critérios de Aceitação | 1. A recuperação de senha só deve ser possível caso o usuário já tenha um cadastro (consultar banco de dados). <br /> 2. Só deve ser possível se o usuário obtiver um endereço de email e/ou um número de telefone válidos. <br /> 3. Deve ter essa opção na página de login/cadastro.   |
| Status |   Validada                                                         |

Tabela 7 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US06

| ID     |      US06                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Rastreabilidade |                 BSNF1                                             |
| Descrição | Eu, como usuário, gostaria que a aplicação fosse restrita para pessoas a partir de 16 anos.   |
| Situação Problema | A votação no Brasil só é permitida para cidadãos que tenham 16 anos ou mais. |
| Critérios de Aceitação | 1. Só deve ser possível realizar o cadastro se o cidadão obtiver 16 anos ou mais. Validação será feita através da data de nascimento comparada a data atual. <br /> 2. Caso o usuário cadastrado tenha 17, 18 ou mais de 70 anos, uma mensagem na tela deve aparecer informando que a votação para esses usuários não é obrigatória. |
| Status |    Validada                                   |

Tabela 8 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US07

| ID     |      US07                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Rastreabilidade |                 INTNF9                                            |
| Descrição | Eu, como usuário, gostaria poder visualizar a autenticidade dos meus documentos.   |
| Situação Problema | Necessidade em saber se os documentos emitidos e adicionados são realmente autênticos. |
| Critérios de Aceitação | 1. Os documentos só podem ser emitidos caso o cadastro do usuário esteja completo, com dados verificados. <br /> 2. Os documentos emitidos devem obter um código de autênticidade emitido pelo TSE. <br /> 3. Deve ter essa opção na aba de menu.|
| Status |    Validada                                   |

Tabela 9 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US08

| ID     |      US08                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Rastreabilidade |                 ENT7                                              |
| Descrição | Eu, como usuário, gostaria poder visualizar por meio de notificações, os horários disponíveis para votação. |
| Situação Problema | Dificuldade do cidadão em saber os horários de votação das instituiçôes, que podem mudar devido imprevistos. |
| Critérios de Aceitação | 1. As notificações começam aparecer 1 semana antes do início das votações. <br /> 2. Os horários disponíveis devem aparecer em relação a localização do usuário, mostrando os horários das regiões de votação mais próximas (com endereço). <br /> 3. Deve notificar o usuário após o login.  |
| Status |  Validada                                    |

Tabela 10 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US09

| ID     |      US9                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Rastreabilidade |                 INTNF13                                           |
| Descrição | Eu, como usuário, gostaria que meus dados fossem protegidos por etapas de segurança. |
| Situação Problema | Em uma era tão tecnologica o que geralmente aflinge os usuários é a eficiência em relação a proteção e segurança de seus dados. |
| Critérios de Aceitação | 1. Ao clicar para iniciar um cadastro, antes de preencher o 1° campo de dados pessoais deve-se emitir um alerta informando o usuário que os dados não serão divulgados e serão de uso restrito da aplicação. <br /> 2. Deve-se obter um link na mensagem que direcione para uma página informativa sobre segurança de dados. |
| Status |   Validada                                   |

Tabela 11 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### US10

| ID     |      US10                                                                  |
| ------ | -------------------------------------------------------------------------- |
| Rastreabilidade |                 ENTNF2                                            |
| Descrição | Eu, como usuário, gostaria poder visualizar um design intuitivo, conteporâneo e padronizado.   |
| Situação Problema | Necessidade por se manter no mercado de forma conteporânea, se conectando sempre da melhor forma com o usuário. |
| Critérios de Aceitação | 1. A interface deve ser de fácil entendimento para usuários com pouca experiência. <br /> 2. Interface deve ser responsiva. <br /> 3. O design deve ser padronizado.  |
| Status |   Validada                                   |

Tabela 12 - Representação das Histórias de usuário

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/jvcostta">João Costa e </a><a href="https://github.com/MateusPy">Mateus Orlando</a></b></p></font>

</center>

## Histórico de Versões

| Versão | Data       | Descrição                                      | Autor(es)                                        | Revisor(es)   |
| ------ | ---------- | ---------------------------------------------- | ------------------------------------------------ | ------------------------ |
| 1.0    | 28/10/2023 | Criação da página | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| 1.1    | 02/11/2023 | Início das Histórias de Usuário | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| 1.2    | 03/11/2023 | Finalizando Histórias de Usuário | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
| 1.3    | 06/11/2023 | Adicionando videos e links | [Mateus Orlando](https://github.com/MateusPy) e [João Costa](https://github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza)|
