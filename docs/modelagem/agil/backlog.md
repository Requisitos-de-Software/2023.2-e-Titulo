# Backlog do Produto

## Introdução

O backlog de um produto é uma ferramenta essencial em desenvolvimento ágil, é como um cardápio de opções, listando todas as ideias e melhorias planejadas. Essa lista é constantemente atualizada e priorizada com base no valor que cada item traz ao produto e nas necessidades dos usuários e do negócio e funciona como um guia estratégico, ajudando a equipe a priorizar e desenvolver funcionalidades alinhadas com metas e expectativas, mantendo o produto flexível diante de mudanças. O backlog é dividido em três áreas: temas, épicos e [histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/modelagem/agil/historiasdeusuario.md) , onde os temas são as formas mais abstratas e as histórias de usuário as menos abstratas, com base no conhecimento adquirido na referência  <a id=anchor_4 href="#REF4">[1]</a>.

## Motivação e Objetivo 

O uso do backlog oferece diversas vantagens que podem impulsionar a eficácia e eficiência de um projeto. Ao adotar essa prática, a equipe beneficia-se das seguintes razões:

- **Lista Organizada e Fácil de Usar:** Proporciona uma visão estruturada e acessível das tarefas pendentes.

- **Simplicidade na Priorização de Tarefas:** Facilita o processo de decidir quais tarefas devem ser abordadas primeiro.

- **Flexibilidade para Ajustes:** Permite adaptações rápidas conforme as mudanças nas prioridades ou requisitos.

- **Exibição Imediata e Organizada das Dependências:** Facilita a compreensão das relações entre as diferentes tarefas.

- **Consideração de Aspectos a Longo Prazo:** Vai além das necessidades imediatas, considerando o panorama completo do projeto.

- **Agrega Valor ao Cliente:** Foca nas necessidades e expectativas do cliente, garantindo entregas que realmente importam.

- **Possibilidade de Estimativas:** Permite uma visão mais clara do tempo e recursos necessários para concluir as tarefas.

Essas vantagens não apenas otimizam o fluxo de trabalho, mas também contribuem para o sucesso e satisfação global do cliente. O backlog é mais do que uma ferramenta; é uma estratégia para impulsionar o progresso e a entrega de valor.


## Metodologia

A elaboração do backlog do produto partiu da análise e verificação dos requisitos funcionais elicitados anteriormente no projeto, seguida pelo agrupamento destes requisitos em temas e épicos, baseados nas [histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/historiasdeusuario.md).

## Requisitos Elicitados

Na Tabela 1 estão registrados todos os requisitos elicitados durante o processo de [elicitação](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/tree/feature-Backlogs/docs/elicitacao/tecnicas), juntamente com a origem de cada requisito.

**Tabela 1 - requisitos elicitados**

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
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.</p>
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

Eu, como cidadão, gostaria de realizar o cadastro e login de usuário.

#### E02 - Título 

Eu, como cidadão, gostaria de realizar a emissão do meu título de eleitor no aplicativo.

#### E03 - Visualização

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

Eu, como usuário, gostaria poder visualizar um design intuitivo, contemporâneo e padronizado.

## Histórias de usuário

Elas especificam os temas e épicos e serão detalhadas melhor no artefato de [histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/modelagem/agil/historiasdeusuario.md) . Se apresentam como descrições concisas e de alto nível de uma funcionalidade desejada em termos do cliente. Usualmente seguem a forma "Eu, como ___, gostaria ___ para ___."


**Tabela 2 - relaciona a prioridade de cada história:**


|  Épico  | Tema    | História de Usuário    | ID | Prioridade | Origem |
|---------|---------|------------------------|----|------------|--------|
|  E01    | Funcionalidade | Eu, como cidadão, gostaria de realizar o cadastro e login de usuáio. | US01 | Alta | RF01 |
|         | Segurança | Eu, como cidadão, desejo efetuar o login por meio de senha ou biometria no aplicativo, com a condição prévia de ter realizado o cadastro. | US01 | Alta | RF02 |
|  E02    | Documento | Eu, como cidadão, anseio pela facilidade de emitir meu Título no aplicativo. | US02 | Alta | RF03 |
|         | Documento | Eu, como cidadão, quero a facilidade de acessar um QR Code no aplicativo para a leitura do meu Título. | -- | Média | RF04 |
|  E03    | Funcionalidade | Eu, como cidadão, gostaria de visualizar a localização do meu local de votação no aplicativo. | -- | Média | RF05  |
|         |  Funcionalidade | Eu, como cidadão, gostaria de ter a facilidade de visualizar as dúvidas frequentes no aplicativo para esclarecer questões comuns. | -- |  Baixa  |  RF10 |
|         | Funcionalidade | Eu, como cidadão, desejo a capacidade de acompanhar a apuração de votos no aplicativo. | -- | Média | RF21 |
|         | Funcionalidade   |Eu, como cidadão, gostaria de visualizar de forma clara no aplicativo o candidato eleito referente ao ano da votação. |  US03 | Baixa | RF22 |
|  E04    | Funcionalidade | Eu, como cidadão, valorizo a facilidade de encontrar o termo de uso no aplicativo, com explicações claras sobre sua utilidade para evitar mal-entendidos. |  US04 | Alta | RF07 |
|  E05    | Segurança | Eu, como cidadão, espero a facilidade de recuperar minha senha no aplicativo quando necessário. |  US05 | Alta | RF08 |
|         | Segurança | Eu, como cidadão, quero a capacidade de fazer alterações nos meus dados cadastrais no aplicativo para manter as informações atualizadas. | -- | Média | RF11 |
|         |  Documento | Eu, como cidadão, espero a funcionalidade no aplicativo que me permita alterar a foto do documento do título eleitoral, garantindo a atualização de informações visuais. | -- | Baixa | RF18 |
|  E06    | Segurança |  Eu, como cidadão, sugiro que o aplicativo permita o acesso apenas a usuários com 16 anos ou mais, considerando sua aptidão para votar. | US06 | Alta | RF12 |
|         | Funcionalidade | Eu, como cidadão, reconheço que o aplicativo requer acesso à internet no dispositivo para seu pleno funcionamento. | -- |  Média  | RF13 |
|  E07    |  Documento | Eu, como cidadão, espero que o aplicativo me ofereça a possibilidade de realizar a quitação eleitoral de forma fácil e conveniente. | -- | Média | RF14 |
|         | Documento |  Eu, como cidadão, gostaria de poder informar minha justificativa diretamente no aplicativo, proporcionando uma forma conveniente de cumprir esse procedimento. | -- | Média | RF17 |
|         |  Segurança|  Eu, como cidadão, desejo que o aplicativo me forneça a visualização das autenticidades dos meus documentos, garantindo transparência e confiança.|US07 | Alta | RF19 |
|  E08    | Funcionalidade |Eu, como cidadão, espero receber notificações no aplicativo para ficar atualizado. | -- | Baixa | RF06 |
|         |  Funcionalidade | Eu, como cidadão, aprecio a funcionalidade no aplicativo que me notifica sobre o horário da votação, garantindo que eu esteja bem informado e preparado. | US08 | Alta | RF20 |
|  E09    | Funcionalidade |  Eu, como cidadão, aprecio a presença da opção de sair/logoff no aplicativo para garantir a segurança e controle sobre minha sessão. | -- | Média | RF09 |
|         |Segurança |  Eu, como cidadão, valorizo a presença de suporte no aplicativo para me auxiliar em eventuais dúvidas ou problemas. | -- | Média | RF16 |
|         |Segurança |  Eu, como cidadão, considero crucial que o aplicativo ofereça segurança robusta, protegendo meus dados por meio de etapas de segurança eficazes. | US09 | Alta | RF23 |
|  E10    | Funcionalidade |  Eu, como cidadão, aprecio a integração do aplicativo com links para o site do TSE e outras funcionalidades externas, ampliando suas capacidades além do seu escopo próprio. | -- | Baixa | RF15 |
|         | Documento |  Eu, como cidadão, prefiro um aplicativo com design intuitivo, que utilize elementos padronizados como botões e menus, proporcionando uma experiência mais fácil e consistente. | US10 | Alta | RF24 |
                  
<div align="center">
<p> <b>Tabela 6</b>: Backlog do produto (Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.). </p>
</div>


<table>
    <tr>
        <th style="text-align: center" colspan=6> Backlog do produto </th>
    </tr>
    <tr>
        <td style="text-align: center"> <b> Épico  </b></td>
        <td style="text-align: center"> <b> Tema  </b></td>
        <td style="text-align: center"> <b> História de Usuário (US)  </b></td>
        <td style="text-align: center"> <b> ID </b></td>
        <td style="text-align: center"> <b> Prioridade  </b></td>
        <td style="text-align: center"> <b> Origem  </b></td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a >E01</a></td>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, gostaria de realizar o cadastro e login de usuáio.</td>
        <td><a >US01</a></td>
        <td>Alta</td>
        <td><a >RF01</td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Segurança </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, desejo efetuar o login por meio de senha ou biometria no aplicativo, com a condição prévia de ter realizado o cadastro.</td>
        <td><a >US01</a></td>
        <td>Alta</td>
        <td><a >RF02</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a >E02</a></td>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Documento </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, anseio pela facilidade de emitir meu Título no aplicativo.</td>
        <td><a >US02</a></td>
        <td>Alta</td>
        <td><a >RF03</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, quero a facilidade de acessar um QR Code no aplicativo para a leitura do meu Título. </td>
        <td><a >--</a></td>
        <td>Média</td>
        <td><a >RF04</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=4 style="vertical-align: middle; text-align: center"> <a ">E03</a></td>
        <!-- Tema  -->
        <td rowspan=4 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, gostaria de visualizar a localização do meu local de votação no aplicativo.</td>
        <td><a >--</a></td>
        <td>Média</td>
        <td><a >RF05</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, gostaria de ter a facilidade de visualizar as dúvidas frequentes no aplicativo para esclarecer questões comuns. </td>
        <td><a >--</a></td>
        <td>Baixa</td>
        <td><a >RF10</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, desejo a capacidade de acompanhar a apuração de votos no aplicativo. </td>
        <td><a >--</a></td>
        <td>Média</td>
        <td><a >RF21</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, gostaria de visualizar de forma clara no aplicativo o candidato eleito referente ao ano da votação. </td>
        <td><a >US03</a></td>
        <td>Baixa</td>
        <td><a >RF22</td>
    </tr>
     <tr>
        <!-- Épico -->
        <td rowspan=1 style="vertical-align: middle; text-align: center"> <a ">E04</a></td>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, valorizo a facilidade de encontrar o termo de uso no aplicativo, com explicações claras sobre sua utilidade para evitar mal-entendidos. </td>
        <td><a >US04</a></td>
        <td>Alta</td>
        <td><a >RF07</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a ">E05</a></td>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Segurança</td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, espero a facilidade de recuperar minha senha no aplicativo quando necessário. </td>
        <td><a >US05</a></td>
        <td>Alta</td>
        <td><a >RF08</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, quero a capacidade de fazer alterações nos meus dados cadastrais no aplicativo para manter as informações atualizadas. </td>
        <td><a >--</a></td>
        <td>Média</td>
        <td><a >RF11</td>
    </tr>
     <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Documento </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, espero a funcionalidade no aplicativo que me permita alterar a foto do documento do título eleitoral, garantindo a atualização de informações visuais.</td>
        <td><a >--</a></td>
        <td>Baixa</td>
        <td><a >RF18</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a ">E06</a></td>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Segurança</td>
        <!-- Histórias de Usuário (2) -->
        <td>	Eu, como cidadão, sugiro que o aplicativo permita o acesso apenas a usuários com 16 anos ou mais, considerando sua aptidão para votar. </td>
        <td><a >US06</a></td>
        <td>Alta</td>
        <td><a >RF12</td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, reconheço que o aplicativo requer acesso à internet no dispositivo para seu pleno funcionamento. </td>
        <td><a >--</a></td>
        <td>Média</td>
        <td><a >RF13</td>
    </tr>
     <tr>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a ">E07</a></td>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Documento</td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, espero que o aplicativo me ofereça a possibilidade de realizar a quitação eleitoral de forma fácil e conveniente. </td>
        <td><a >--</a></td>
        <td>Média</td>
        <td><a >RF14</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, gostaria de poder informar minha justificativa diretamente no aplicativo, proporcionando uma forma conveniente de cumprir esse procedimento. </td>
        <td><a >--</a></td>
        <td>Média</td>
        <td><a >RF17</td>
    </tr>
     <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Segurança </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, desejo que o aplicativo me forneça a visualização das autenticidades dos meus documentos, garantindo transparência e confiança. </td>
        <td><a >US07</a></td>
        <td>Alta</td>
        <td><a >RF19</td>
    </tr>
     <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a ">E08</a></td>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Funcionalidade</td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, espero receber notificações no aplicativo para ficar atualizado. </td>
        <td><a >--</a></td>
        <td>Baixa</td>
        <td><a >RF06</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, aprecio a funcionalidade no aplicativo que me notifica sobre o horário da votação, garantindo que eu esteja bem informado e preparado. </td>
        <td><a >US08</a></td>
        <td>Alta</td>
        <td><a >RF20</td>
    </tr>
     <tr>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a ">E09</a></td>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, aprecio a presença da opção de sair/logoff no aplicativo para garantir a segurança e controle sobre minha sessão. </td>
        <td><a >--</a></td>
        <td>Média</td>
        <td><a >RF09</td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Segurança </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, valorizo a presença de suporte no aplicativo para me auxiliar em eventuais dúvidas ou problemas. </td>
        <td><a >--</a></td>
        <td>Média</td>
        <td><a >RF16</td>
    </tr>
    <tr>
        <td>Eu, como cidadão, considero crucial que o aplicativo ofereça segurança robusta, protegendo meus dados por meio de etapas de segurança eficazes. </td>
        <td><a >US09</a></td>
        <td>Alta</td>
        <td><a >RF23</td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a >E10</a></td>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (1) -->
        <td>Eu, como cidadão, aprecio a integração do aplicativo com links para o site do TSE e outras funcionalidades externas, ampliando suas capacidades além do seu escopo próprio. </td>
        <td><a >--</a></td>
        <td>Baixa</td>
        <td><a >RF15</td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Documento </td>
        <!-- Histórias de Usuário (1) -->
        <td> Eu, como cidadão, prefiro um aplicativo com design intuitivo, que utilize elementos padronizados como botões e menus, proporcionando uma experiência mais fácil e consistente. </td>
        <td><a >US10</a></td>
        <td>Alta</td>
        <td><a >RF24</td>
    </tr>

</table>

<div align="center">
<p> <b>Tabela 6</b>: Backlog do produto (Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.). </p>
</div>

## Bibliografia

> RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian. Disponível em: [Backlog](https://www.atlassian.com/br/agile/scrum/backlogs). Acesso em 22 out, 2023.

> O QUE É BACKLOG DO PRODUTO SCRUM E COMO FAZER UM. Lucidchart. Disponível em: [Backlog](https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto). Acesso em 22 out, 2023.

> SANTOS, Cris. Como Construir Um Product Backlog: Guia Em Pdf. Disponível em> [Backlog](https://awari.com.br/como-construir-um-product-backlog-guia-em-pdf-4/?utm_source=blog&utm_campaign=projeto+blog&utm_medium=Como%20Construir%20Um%20Product%20Backlog:%20Guia%20Em%20Pdf). Acesso em 06 nov, 2023.

> 2022.2-Lichess. Backlog. Disponível em: [Backlog](https://github.com/Requisitos-de-Software/2022.2-Lichess/blob/main/docs/modelagem/agil/backlog.md). Acesso em 06 nov, 2023.

> <a id=anchor_4 href="#REF4">[1]</a> SERRANO, Milene e SERRANO, Maurício. Requisitos - Aula 15. Disponível em: [Backlog](https://aprender3.unb.br/pluginfile.php/2692826/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf).Acesso em 06 nov, 2023.

## Histórico de Versões
|  Versão    | Data | Descrição                   |    Autor(es)     |  Revisor(es) |
| :--------: | :----: | :-------------------------: | :--------------: | :---------: |
|  `1.0`  |  05/11/2023  | Criação do documento               | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza)   | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques)  |
|  `1.1` |  06/11/2023  | Adição de introdução e metodologia | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques)  |
|  `1.2` | 06/11/2023  | Adição do resto da documentação | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques)  |
| `1.3` | 29/11/2023 |  Correção das tabelas deixando em formato ABNT, mudando objetivo, chamando referencia, corrigindo erros e linkagem e mudando a estrutura da tabela de backlog deixando ela mais compreenssivél. |[Esther Sena](https://github.com/esmsena)| [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
