# Backlog do Produto

## Introdução


<p>&emsp;&emsp; 
O backlog de um produto em engenharia de requisitos é como um cardápio de opções, listando todas as ideias e melhorias planejadas. É um depósito dinâmico de necessidades do usuário e requisitos do. Funciona como um guia estratégico, ajudando a equipe a priorizar e desenvolver funcionalidades alinhadas com metas e expectativas, mantendo o produto flexível diante de mudanças. Em resumo, é uma ferramenta vital que permite o desenvolvimento contínuo e adaptativo do produto.</p>


## Vantagens de usar o backlog 
<div style="text-align:justify">
    <ul>
        <li> Lista organizada e fácil de usar.
        <li> Simplicidade na priorização de tarefas.
        <li> Flexibilidade para ajustes conforme mudanças nas prioridades.
        <li> Exibição imediata e organizada das dependências.
        <li> Consideração de aspectos a longo prazo, não limitando-se apenas às necessidades imediatas.
        <li> Agrega valor ao cliente.
        <li> Possibilidade de estimativas.
    </ul>
</div>

## Metodologia

A elaboração do product backlog partiu da análise e verificação dos requisitos funcionais elicitados anteriormente no projeto, seguida pelo agrupamento destes requisitos em temas e épicos, o agrupamento de histórias de usuário está presente no documento do mesmo ([histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/historiasdeusuario.md)).

## Requisitos Elicitados

Na Tabela 1 estão registrados todos os requisitos elicitados durante o processo de [elicitação](../../elicitacao/tecnicas_planejadas.md), juntamente com a origem de cada requisito.

| Identificador | Requisito | Rastreabilidade |
| :-: | :-: | :-: |
| RF01 | No aplicativo deve ser possível realizar o cadastro do usuário. | BS1 |
| RF02 | Deve ser possível o usuário realizar o login por senha ou biometria para acessar o aplicativo, com a condição de já ter se cadastrado. | BS2 |
| RF03 | Deve ser possível realizar a emissão do Título do usuário no aplicativo. | BS3 |
| RF04 | No aplicativo deve ser possível o usuário acessar o QR Code para a leitura do seu título. | BS4 |
| RF05 | No aplicativo deve ser possível o usuário vizualizar a localização do Local de Votação. | BS5 |
| RF06 | No aplicativo deve possível o usuário receber notificações. | BS6 |
| RF07 | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo. | ENTNF1 |
| RF08 | No aplicativo deve ser possível o usuário realizar a recuperação da senha. | BS10|
| RF09 | O aplicativo deve ter a opção de sair/logoff disponível para o usuário. | INT7 |
| RF10 | Deve ser possível o usuário visualizar as dúvidas frequentes do aplicativo. | BS12|
| RF11 | O usuário deve conseguir fazer alterações em seus dados cadastrais. | INT8|
| RF12 | O aplicativo deve permitir apenas usuários acima de 16 anos, por serem aptos a votar. | BSNF1 |
| RF13 | Para o aplicativo ser utilizado, o dispositivo que mantém ele instalado deve precisar ter acesso a internet. | BSNF4 |
| RF14 | No aplicativo deve ser possível que o usuário realize a quitação eleitoral. | ENT4 |
| RF15 | Na navegação do aplicativo deve possuir linkagem com o site do TSE ou outros aplicativos externos, assim o aplicativo possui algumas funcionalidades não sendo pertencentes a ele, mas de fora dele. | ENTNF4 |
| RF16 | O aplicativo deve oferecer suporte ao usuário. | ENT5 |
| RF17 | O usuário deve conseguir informar a sua justificativa no aplicativo. | INT19 |
| RF18 | O aplicativo deve permitir que os usuários alterem a foto do documento do título eleitoral. | INTNF1 |
| RF19 |O aplicativo deve mostrar ao usuário as autenticidades de seus documentos. | INTNF9 |
| RF20 | O aplicativo deve notificar o horário da votação para o usuário. | ENT7 |
| RF21 | Deve ser possível o usuário acompanhar a apuração de votos.| ENT8 |
| RF22 | O usuário deve visualizar o candidato eleito referente ao ano da votação. | ENT9 |
| RF23 | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança. | INTNF13 |
| RF24 | O aplicativo deve possuir um design intuitivo com elementos como botão e menu padronizados.| ENTNF2 |


<div style="text-align: center">
<p> Tabela 1: Requisitos elicitados (Fonte: autor, 2023).</p>
</div>

## Backlog 

## Temas

Analisando as histórias de usuário, foi possível organizá-las inicialmente em dois grandes temas.

- **Funcionalidades**: Organiza as funcionalidades necessárias para que o usuário possa executar suas tarefas com sucesso no sistema.
- **Documentos**: Agrupa funcionalidades relacionadas a documentos, e como emiti-los.
- **Segurança:** Agrupa funcionalidades relacionadas a segurança do usuário no sistema.

  
Após a elaboração dos temas, os requisitos foram detalhados em um nível mais abstrato por meio dos épicos. Essas são histórias de usuário que permitem uma maior especificação e foram redigidas seguindo o mesmo padrão utilizado para as histórias de usuário.

### Épicos 

Para diminuir o nível de abstração expresso nos temas, foram registrados os épicos, que são histórias de usuário que ainda podem ser mais especificadas. Para facilitar a leitura da tabela de backlog (Tabela 2), os épicos estão especificados a seguir.

#### E01 - Cadastro de usuário

Eu, como cidadão, gostaria de realizar o cadastro e login de usuáio.

#### E02 - Emissão do título

Eu, como cidadão, gostaria de realizar a emissão do meu título de eleitor no apicativo.

#### E03 - Vizualizar candidato

Eu, como cidadão, gostaria de visualizar o candidato eleito referente ao ano da votação.

#### E04 - Acesso ao termo de uso

Eu, como usuário, gostaria de acessar o termo de uso de forma fácil para leitura do mesmo.

#### E05 - Recuperar senha

Eu, como usuário, gostaria de realizar a recuperação de senha.

#### E06 - Restringir para menores de 16 anos

Eu, como usuário, gostaria que a aplicação fosse restrita para pessoas a partir de 16 anos.

#### E07 - Vizualizar autencidade

Eu, como usuário, gostaria poder visualizar a autenticidade dos meus documentos.
 
#### E08 - Vizualizar horários disponíveis

Eu, como usuário, gostaria poder visualizar por meio de notificações, os horários disponíveis para votação.

#### E09 - Etapas de segurança

Eu, como usuário, gostaria que meus dados fossem protegidos por etapas de segurança.

#### E10 - Design apropriado

Eu, como usuário, gostaria poder visualizar um design intuitivo, conteporâneo e padronizado.

A tabela 6 abaixo vai relacionar a prioridade de cada história:

| História de Usuário | Épico                  | Prioridade |
|--------------------|------------------------|----------------------------------------|
| US01               | Épico |        |
| US02               | Épico |        |
| US03               | Épico    |        |
| US04               | Épico    |        |
| US05               | Épico  |   |
| US06               | Épico    |       |
| US07               | Épico   |       |
| US08               | Épico     |       |
| US09               | Épico  |  |
| US10               | Épico    |       |
| US11               | Épico    |       |
| US12               | Épico    |       |
| US13               | Épico     |       |
| US14               | Épico     |       |
| US15               | Épico    |       |
| US16               | Épico    |       |
| US17               | Épico     |       |
| US18               | Épico     |       |
| US19               | Épico    |       |
| US20               | Épico    |       |

<div align="center">
<p> <b>Tabela 6</b>: Backlog do produto (Fonte: autores, 2023). </p>
</div>


## Conclusão

<div style="text-align: justify">

&emsp;&emsp; ---------------------------------------------------------



## Bibliografia

- RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian. Disponível em: [Backlog](https://www.atlassian.com/br/agile/scrum/backlogs)

- O QUE É BACKLOG DO PRODUTO SCRUM E COMO FAZER UM. Lucidchart. Disponível em: [Backlog](https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto) 

## Histórico de Versões
|   Data     | Versão | Descrição                   |    Autor(es)     |  Data de revisão | Revisor(es) |
| :--------: | :----: | :-------------------------: | :--------------: | :--------------: | :---------: |
| 20/05/2023   |  `1.0`  | Criação do documento               | Esther Sena  | 22/05/2023 |  |
