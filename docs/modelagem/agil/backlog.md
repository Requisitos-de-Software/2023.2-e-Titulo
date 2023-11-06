# Backlog do Produto

## Introdução

O backlog de um produto é uma ferramenta essencial em desenvolvimento ágil, é como um cardápio de opções, listando todas as ideias e melhorias planejadas. Essa lista é constantemente atualizada e priorizada com base no valor que cada item traz ao produto e nas necessidades dos usuários e do negócio e funciona como um guia estratégico, ajudando a equipe a priorizar e desenvolver funcionalidades alinhadas com metas e expectativas, mantendo o produto flexível diante de mudanças. O backlog é dividido em três áreas: temas, épicos e [histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/historiasdeusuario.md), onde os temas são as formas mais abstratas e as histórias de usuário as menos abstratas.

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

A elaboração do backlog do produto partiu da análise e verificação dos requisitos funcionais elicitados anteriormente no projeto, seguida pelo agrupamento destes requisitos em temas e épicos, baseados nas [histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/historiasdeusuario.md).

## Requisitos Elicitados

Na Tabela 1 estão registrados todos os requisitos elicitados durante o processo de [elicitação](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/tree/feature-Backlogs/docs/elicitacao/tecnicas), juntamente com a origem de cada requisito.

| Identificador | Requisito | Rastreabilidade |
| :-: | :-: | :-: |
| RF01 | No aplicativo deve ser possível realizar o cadastro do usuário. | [BS1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |
| RF02 | Deve ser possível o usuário realizar o login por senha ou biometria para acessar o aplicativo, com a condição de já ter se cadastrado. | [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |
| RF03 | Deve ser possível realizar a emissão do Título do usuário no aplicativo. | [BS3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |
| RF04 | No aplicativo deve ser possível o usuário acessar o QR Code para a leitura do seu título. | [BS4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |
| RF05 | No aplicativo deve ser possível o usuário vizualizar a localização do Local de Votação. | [BS5](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |
| RF06 | No aplicativo deve possível o usuário receber notificações. | [BS6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |
| RF07 | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo. | [ENTNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md) |
| RF08 | No aplicativo deve ser possível o usuário realizar a recuperação da senha. | [BS10](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)|
| RF09 | O aplicativo deve ter a opção de sair/logoff disponível para o usuário. | [INT7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |
| RF10 | Deve ser possível o usuário visualizar as dúvidas frequentes do aplicativo. | [BS12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)|
| RF11 | O usuário deve conseguir fazer alterações em seus dados cadastrais. | [INT8](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |
| RF12 | O aplicativo deve permitir apenas usuários acima de 16 anos, por serem aptos a votar. | [BSNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |
| RF13 | Para o aplicativo ser utilizado, o dispositivo que mantém ele instalado deve precisar ter acesso a internet. | [BSNF4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |
| RF14 | No aplicativo deve ser possível que o usuário realize a quitação eleitoral. | [ENT4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md) |
| RF15 | Na navegação do aplicativo deve possuir linkagem com o site do TSE ou outros aplicativos externos, assim o aplicativo possui algumas funcionalidades não sendo pertencentes a ele, mas de fora dele. | [ENTNF4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md) |
| RF16 | O aplicativo deve oferecer suporte ao usuário. | [ENT5](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md) |
| RF17 | O usuário deve conseguir informar a sua justificativa no aplicativo. | [INT19](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |
| RF18 | O aplicativo deve permitir que os usuários alterem a foto do documento do título eleitoral. | [INTNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |
| RF19 |O aplicativo deve mostrar ao usuário as autenticidades de seus documentos. | [INTNF9](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |
| RF20 | O aplicativo deve notificar o horário da votação para o usuário. | [ENT7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md) |
| RF21 | Deve ser possível o usuário acompanhar a apuração de votos.| [ENT8](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md) |
| RF22 | O usuário deve visualizar o candidato eleito referente ao ano da votação. | [ENT9](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md) |
| RF23 | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança. | [INTNF13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |
| RF24 | O aplicativo deve possuir um design intuitivo com elementos como botão e menu padronizados. | [ENTNF2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md) |

<div style="text-align: center">
<p> Tabela 1: Requisitos elicitados (Fonte: autor, 2023).</p>
</div>

## Backlog 

## Temas

Analisando as histórias de usuário, foi possível organizá-las inicialmente em três grandes temas.

- **Funcionalidade**: Organiza as funcionalidades necessárias para que o usuário possa executar suas tarefas com sucesso no sistema.
- **Documento**: Agrupa funcionalidades relacionadas a documentos, como emiti-los.
- **Segurança:** Agrupa funcionalidades relacionadas a segurança do usuário no sistema.

Após a elaboração dos temas, os requisitos foram detalhados em um nível mais abstrato por meio dos épicos. Essas são histórias de usuário que permitem uma maior especificação e foram redigidas seguindo o mesmo padrão utilizado para as histórias de usuário.

### Épicos 

Para diminuir o nível de abstração expresso nos temas, foram registrados os épicos, que são histórias de usuário que ainda podem ser mais especificadas. Para facilitar a leitura da tabela de backlog (Tabela 2), os épicos estão especificados a seguir.

#### E01 - Cadastro

Eu, como cidadão, gostaria de realizar o cadastro e login de usuáio.

#### E02 - Título 

Eu, como cidadão, gostaria de realizar a emissão do meu título de eleitor no apicativo.

#### E03 - Vizualização

Eu, como cidadão, gostaria de visualizar o candidato eleito referente ao ano da votação.

#### E04 - Termo de uso

Eu, como usuário, gostaria de acessar o termo de uso de forma fácil para leitura do mesmo.

#### E05 - Alterações

Eu, como usuário, gostaria de realizar a recuperação de senha.

#### E06 - Restrições

Eu, como usuário, gostaria que a aplicação fosse restrita para pessoas a partir de 16 anos.

#### E07 - Autenticação

Eu, como usuário, gostaria poder visualizar a autenticidade dos meus documentos.
 
#### E08 - Notificações

Eu, como usuário, gostaria poder visualizar por meio de notificações, os horários disponíveis para votação.

#### E09 - Etapas de segurança

Eu, como usuário, gostaria que meus dados fossem protegidos por etapas de segurança.

#### E10 - Design apropriado

Eu, como usuário, gostaria poder visualizar um design intuitivo, conteporâneo e padronizado.

## Histórias de usuário

Elas especificam os temas e épicos e serão detalhadas melhor no artefato de [histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/historiasdeusuario.md). Se apresentam como descrições concisas e de alto nível de uma funcionalidade desejada em termos do cliente. Usualmente seguem a forma "Eu, como ___, gostaria ___ para ___."

A tabela 6 abaixo vai relacionar a prioridade de cada história:

|  Épico  | Tema    | História de Usuário    | ID | Prioridade | Origem |
|---------|---------|------------------------|----|------------|--------|
|  E01    | Funcionalidade | Eu, como cidadão, gostaria de realizar o cadastro e login de usuáio. | US01 | Alta | RF01 |
|         | Segurança | Eu, como cidadão, desejo efetuar o login por meio de senha ou biometria no aplicativo, com a condição prévia de ter realizado o cadastro. | US01 | Alta | RF02 |
|  E02    | Documento | Eu, como cidadão, anseio pela facilidade de emitir meu Título no aplicativo. | US02 | Alta | RF03 |
|         | Documento | Eu, como cidadão, quero a facilidade de acessar um QR Code no aplicativo para a leitura do meu Título. |    | Média | RF04 |
|  E03    | Eu, como cidadão, gostaria de visualizar a localização do meu local de votação no aplicativo. |   |    | Média | RF05  |
|         | Eu, como cidadão, gostaria de ter a facilidade de visualizar as dúvidas frequentes no aplicativo para esclarecer questões comuns. |  Funcionalidade |      |  Baixa  |  RF10 |
|         | Eu, como cidadão, desejo a capacidade de acompanhar a apuração de votos no aplicativo. | Funcionalidade  |    | Média | RF21 |
|         | Eu, como cidadão, gostaria de visualizar de forma clara no aplicativo o candidato eleito referente ao ano da votação. | Funcionalidade   | US03 | Baixa | RF22 |
|  E04    | Eu, como cidadão, valorizo a facilidade de encontrar o termo de uso no aplicativo, com explicações claras sobre sua utilidade para evitar mal-entendidos. | Funcionalidade | US04 | Alta | RF07 |
|  E05    | Eu, como cidadão, espero a facilidade de recuperar minha senha no aplicativo quando necessário. | Segurança | US05 | Alta | RF08 |
|         | Eu, como cidadão, quero a capacidade de fazer alterações nos meus dados cadastrais no aplicativo para manter as informações atualizadas. | Segurança |    | Média | RF11 |
|         | Eu, como cidadão, espero a funcionalidade no aplicativo que me permita alterar a foto do documento do título eleitoral, garantindo a atualização de informações visuais. | Documento |    | Baixa | RF18 |
|  E06    | Eu, como cidadão, sugiro que o aplicativo permita o acesso apenas a usuários com 16 anos ou mais, considerando sua aptidão para votar. | Segurança | US06 | Alta | RF12 |
|         | Eu, como cidadão, reconheço que o aplicativo requer acesso à internet no dispositivo para seu pleno funcionamento. | Funcionalidade |    |  Média  | RF13 |
|  E07    | Eu, como cidadão, espero que o aplicativo me ofereça a possibilidade de realizar a quitação eleitoral de forma fácil e conveniente. | Documento |    | Média | RF14 |
|         | Eu, como cidadão, gostaria de poder informar minha justificativa diretamente no aplicativo, proporcionando uma forma conveniente de cumprir esse procedimento. | Documento |    | Média | RF17 |
|         | Eu, como cidadão, desejo que o aplicativo me forneça a visualização das autenticidades dos meus documentos, garantindo transparência e confiança.| Segurança| US07 | Alta | RF19 |
|  E08    | Eu, como cidadão, espero receber notificações no aplicativo para ficar atualizado. | Funcionalidade |    | Baixa | RF06 |
|         | Eu, como cidadão, aprecio a funcionalidade no aplicativo que me notifica sobre o horário da votação, garantindo que eu esteja bem informado e preparado. | Funcionalidade | US08 | Alta | RF20 |
|  E09    | Eu, como cidadão, aprecio a presença da opção de sair/logoff no aplicativo para garantir a segurança e controle sobre minha sessão. | Funcionalidade |    | Média | RF09 |
|         | Eu, como cidadão, valorizo a presença de suporte no aplicativo para me auxiliar em eventuais dúvidas ou problemas. | Segurança |    | Média | RF16 |
|         | Eu, como cidadão, considero crucial que o aplicativo ofereça segurança robusta, protegendo meus dados por meio de etapas de segurança eficazes. | Segurança | US09 | Alta | RF23 |
|  E10    | Eu, como cidadão, aprecio a integração do aplicativo com links para o site do TSE e outras funcionalidades externas, ampliando suas capacidades além do seu escopo próprio. | Funcionalidade |    | Baixa | RF15 |
|         | Eu, como cidadão, prefiro um aplicativo com design intuitivo, que utilize elementos padronizados como botões e menus, proporcionando uma experiência mais fácil e consistente. | Documento | US10 | Alta | RF24 |
                  
<div align="center">
<p> <b>Tabela 6</b>: Backlog do produto (Fonte: autores, 2023). </p>
</div>

## Bibliografia

> RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian. Disponível em: [Backlog](https://www.atlassian.com/br/agile/scrum/backlogs). Acesso em 22 out, 2023.

> O QUE É BACKLOG DO PRODUTO SCRUM E COMO FAZER UM. Lucidchart. Disponível em: [Backlog](https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto). Acesso em 22 out, 2023.

> SANTOS, Cris. Como Construir Um Product Backlog: Guia Em Pdf. Disponível em> [Backlog](https://awari.com.br/como-construir-um-product-backlog-guia-em-pdf-4/?utm_source=blog&utm_campaign=projeto+blog&utm_medium=Como%20Construir%20Um%20Product%20Backlog:%20Guia%20Em%20Pdf). Acesso em 06 nov, 2023.

> 2022.2-Lichess. Backlog. Disponível em: [Backlog](https://github.com/Requisitos-de-Software/2022.2-Lichess/blob/main/docs/modelagem/agil/backlog.md). Acesso em 06 nov, 2023.

> SERRANO, Milene e SERRANO, Maurício. Requisitos - Aula 15. Disponível em: [Backlog](https://aprender3.unb.br/pluginfile.php/2692826/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf).Acesso em 06 nov, 2023.

## Histórico de Versões
|   Data     | Versão | Descrição                   |    Autor(es)     |  Revisor(es) |
| :--------: | :----: | :-------------------------: | :--------------: | :---------: |
| 22/10/2023   |  `1.0`  | Criação do documento               | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza)   | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques)  |
| 06/11/2023   |  `1.1`  | Adição de introdução e metodologia | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques)  |
| 06/11/2023   |  `1.2`  | Adição do resto da documentação | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques)  |
