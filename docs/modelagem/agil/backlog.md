# Backlog do Produto

## Introdução

O backlog de um produto é uma ferramenta essencial em desenvolvimento ágil, é como um cardápio de opções, listando todas as ideias e melhorias planejadas. Essa lista é constantemente atualizada e priorizada com base no valor que cada item traz ao produto e nas necessidades dos usuários e do negócio e funciona como um guia estratégico, ajudando a equipe a priorizar e desenvolver funcionalidades alinhadas com metas e expectativas, mantendo o produto flexível diante de mudanças. 

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

O backlog é dividido em três áreas: temas, épicos e [histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/modelagem/agil/historiasdeusuario.md), onde os temas são as formas mais abstratas e as histórias de usuário as menos abstratas, com base no conhecimento adquirido na referência  <a id=anchor_1 href="#REF1">[1]</a>.

A elaboração do backlog do produto partiu da análise e verificação dos requisitos funcionais elicitados anteriormente no projeto, seguida pelo agrupamento destes requisitos em temas e épicos, baseados nas [histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/historiasdeusuario.md).

## Requisitos Elicitados

Na Tabela 1 estão registrados todos os requisitos elicitados durante o processo de [elicitação](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/tree/feature-Backlogs/docs/elicitacao/tecnicas), juntamente com a origem de cada requisito.

**Tabela 1 - requisitos elicitados**

| Identificador | Requisito | Rastreabilidade |
| :-: | :-: | :-: |
| <a id=anchor_2 href="#RF01">RF01</a> | No aplicativo deve ser possível realizar o cadastro do usuário. | [BS1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) |
| <a id=anchor_3 href="#RF02">RF02</a> | Deve ser possível o usuário cadastrar sua biometria durante o processo de cadastro. | [INT2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_4 href="#RF03">RF03</a> | Deve ser possível o usuário realizar o login por senha ou biometria para acessar o aplicativo, com a condição de já ter se cadastrado. | [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) |
| <a id=anchor_5 href="#RF04">RF04</a> | eu como usuário, quero poder visualizar a localização do local de votação | [ST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) |
| <a id=anchor_6 href="#RF05">RF05</a> | Deve ser possível o usuário vizualizar seu documento do título eleitoral. | [INT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_7 href="#RF06">RF06</a> | O usuário deve conseguir visualizar as notificações do aplicativo, que alertam sobre datas ou informações importantes. | [INT6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_8 href="#RF07">RF07</a> | O aplicativo deve ter a opção de sair/logoff disponível para o usuário. | [INT7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_9 href="#RF08">RF08</a> | O usuário deve conseguir fazer alterações em seus dados cadastrais. | [INT8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_10 href="#RF09">RF09</a> | Deve ser possível o usuário realizar o download do documento título eleitoral no aplicativo. | [INT9](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_11 href="#RF10">RF10</a> | Deve ser possível o usuário escolher o formato do arquivo, como pdf ou doc, a ser baixado do aplicativo. | [INT10](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_12 href="#RF11">RF11</a> | O usuário deve conseguir visualizar no aplicativo todos os dados presentes em um documento de título eleitoral. | [INT11](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_13 href="#RF12">RF12</a> | Deve ser possível o usuário visualizar as rotas de sua localização atual até o seu local de votação pelo aplicativo. | [INT13](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_14 href="#RF13">RF13</a> | O usuário deve conseguir escolher o local de partida. | [INT14](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_15 href="#RF14">RF14</a> | O usuário deve conseguir escolher visualizar sobre as documentações nescessárias.| [INT15](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  |
| <a id=anchor_16 href="#RF15">RF15</a> | O usuário deve conseguir vizualizar os dados documentais. | [INT16](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_17 href="#RF16">RF16</a> | No aplicativo deve ser possível que o usuário visualize a sua situação da quitação eleitoral | [ENT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)  |
| <a id=anchor_18 href="#RF17">RF17</a> | O usuário deve conseguir vizualizar dados referentes ao criminal eleitoral. | [INT18](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_19 href="#RF18">RF18</a> |  O usuário deve conseguir informar a sua justificativa no aplicativo. | [INT19](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_20 href="#RF19">RF19</a> | O usuário deve realizar download da comprovação de sua justificativa. | [INT20](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_21 href="#RF20">RF20</a> | O usuário deve poder alterar seus dados pessoais. | [INT21](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_22 href="#RF21">RF21</a> | Deve ser possível o usuário apagar seus dados pessoais. | [INT22](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_23 href="#RF22">RF22</a> | Deve ser possível o usuário ver o histórico de dados apagados. | [INT23](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_24 href="#RF23">RF23</a> | O aplicativo deve permitir que os usuários alterem a foto do documento do título eleitoral. | [INT24](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  |
| <a id=anchor_25 href="#RF24">RF24</a> | O aplicativo deve notificar sobre atualizações eleitorais. | [INT26](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  |
| <a id=anchor_26 href="#RF25">RF25</a> | O aplicativo deve demonstrar ao usuário os lembretes de votação e de mudanças de localização para votação. | [INT27](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  |
| <a id=anchor_27 href="#RF26">RF26</a> | O aplicativo deve permitir que o usuário receba a comprovação de seus débitos. | [INT28](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)   |
| <a id=anchor_28 href="#RF27">RF27</a> | O aplicativo deve mostrar ao usuário as autenticidades de seus documento. |  [INT29](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)   |
| <a id=anchor_29 href="#RF28">RF28</a> | O aplicativo deve permitir a leitura do qr code do título eleitoral. |  [INT30](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_30 href="#RF29">RF29</a> | O aplicativo deve permitir que o usuário visualiza tutoriais a respeito de seus documentos. | [INT31](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  |
| <a id=anchor_31 href="#RF30">RF30</a> | O aplicativo deve permitir que o usuário envie dúvidas. | [INT32](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_33 href="#RF32">RF32</a> | O aplicativo deve notificar o horário da votação para o usuário | [ENT7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) |
| <a id=anchor_32 href="#RF31">RF31</a> | Deve ser possível o usuário acompanhar a apuração de votos  | [ENT8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) |
| <a id=anchor_34 href="#RF33">RF33</a> | O usuário deve visualizar o candidato eleito referente ao ano da votação. | [ENT9](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) |
| <a id=anchor_35 href="#RF34">RF34</a> | No aplicativo deve ser possível o usuário vizualizar os termos de uso | [BS7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) |
| <a id=anchor_36 href="#RF35">RF35</a> | No aplicativo deve ser possível o usuário concordar ou não com os termos de uso | [BS8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) |
| <a id=anchor_37 href="#RF36">RF36</a> | No aplicativo deve ser possível o usuário realizar a recuperação da senha | [BS10](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) |
| <a id=anchor_38 href="#RF37">RF37</a> | Deve ser possível o usuário visualizar as dúvidas frequentes do aplicativo | [BS12](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | 
| <a id=anchor_39 href="#RF38">RF38</a> | O aplicativo deve oferecer um meio de ajuda para os usuários que não entenderam alguma coisa de sua utilidade | [BS14](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) |
| <a id=anchor_40 href="#RF39">RF39</a> | O aplicativo deve permitir apenas usuários acima de 16 anos, por serem aptos a votar | [BSNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) |
| <a id=anchor_41 href="#RF40">RF40</a> | Para o aplicativo ser utilizado, o dispositivo que mantém ele instalado deve precisar ter acesso a internet | [BSNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) |
| <a id=anchor_42 href="#RF41">RF41</a> | O aplicativo deve possuir um forúm para a retirada de dúvidas dos usuários. | [INTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_43 href="#RF42">RF42</a> | O aplicativo deve contribuir para a transparência e informações sobre os candidatos sendo disponíveis para os usuários | [INTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_44 href="#RF43">RF43</a> | O aplicativo deve manter sigilo nos dados do usuário a respeito de sua justificativa, permitindo a proteção dos dados, apenas os responsáveis o vê. | [INTNF3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_45 href="#RF44">RF44</a> | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança. | [INTNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |
| <a id=anchor_46 href="#RF45">RF45</a> | A navegação do aplicativo não deve ser poluída, como excesso de informações que podem confundir os usuários | [ENTNF3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) |
| <a id=anchor_47 href="#RF46">RF46</a> | Na navegação do aplicativo deve possuir linkagem com o site do TSE ou outros aplicativos externos, assim o aplicativo possui algumas funcionalidades não sendo pertencentes a ele, mas de fora dele | [ENTNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) |
| <a id=anchor_48 href="#RF47">RF47</a> | O aplicativo deve manter a atualização das informações do local da votação de cada usuário | [QSTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) |

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

#### <a id=anchor_49 href="#RF49"> E01 - Cadastro</a>

Eu, como cidadão, gostaria de realizar o cadastro e login de usuário.

#### <a id=anchor_50 href="#RF50"> E02 - Título </a>

Eu, como cidadão, gostaria de realizar a emissão do meu título de eleitor no aplicativo.

#### <a id=anchor_51 href="#RF51"> E03 - Visualização</a>

Eu, como cidadão, gostaria de visualizar o candidato eleito referente ao ano da votação.

#### <a id=anchor_51 href="#RF52"> E04 - Termos de uso</a>

Eu, como usuário, gostaria de acessar o termo de uso de forma fácil para leitura do mesmo.

#### <a id=anchor_53 href="#RF53"> E05 - Alterações</a>

Eu, como usuário, gostaria de realizar a recuperação de senha.

#### <a id=anchor_54 href="#RF54"> E06 - Restrições</a> 

Eu, como usuário, gostaria que a aplicação fosse restrita para pessoas a partir de 16 anos.

#### <a id=anchor_55 href="#RF55"> E07 - Autenticação</a> 

Eu, como usuário, gostaria poder visualizar a autenticidade dos meus documentos.
 
#### <a id=anchor_56 href="#RF56"> E08 - Notificações</a> 

Eu, como usuário, gostaria poder visualizar por meio de notificações, os horários disponíveis para votação.

#### <a id=anchor_57 href="#RF57"> E09 - Segurança</a> 

Eu, como usuário, gostaria que meus dados fossem protegidos por etapas de segurança.

#### <a id=anchor_58 href="#RF58"> E10 - Design apropriado</a> 

Eu, como usuário, gostaria poder visualizar um design intuitivo, contemporâneo e padronizado.

## Histórias de usuário

Elas especificam os temas e épicos e serão detalhadas melhor no artefato de [histórias de usuário](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/modelagem/agil/historiasdeusuario.md) . Se apresentam como descrições concisas e de alto nível de uma funcionalidade desejada em termos do cliente. Usualmente seguem a forma "Eu, como ___, gostaria ___ para ___."


**Tabela 2 - relaciona a prioridade de cada história:**

Tabela 2: Backlog do produto 

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
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a ><a id="RF49" href="#anchor_49">E01</a> </a></td>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, gostaria de realizar o cadastro e login de usuáio.</td>
        <td><a >US01</a></td>
        <td>Alta</td>
        <td><a ><a id="RF01" href="#anchor_2">RF01</a> </td>
    </tr>
        <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, gostaria de realizar o cadastro de biometria durante o processo de cadastro.</td>
        <td><a >US01</a></td>
        <td>Média</td>
        <td><a ><a id="RF02" href="#anchor_3">RF02</a></td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Segurança </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, desejo efetuar o login por meio de senha ou biometria no aplicativo, com a condição prévia de ter realizado o cadastro.</td>
        <td><a >US01</a></td>
        <td>Alta</td>
        <td><a > <a id="RF03" href="#anchor_4">RF03</a></td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=4 style="vertical-align: middle; text-align: center"> <a ><a id="RF50" href="#anchor_50">E02</a> </a></td>
        <!-- Tema  -->
        <td rowspan=3 style="vertical-align: middle"> Documento </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, anseio pela facilidade de emitir meu Título no aplicativo.</td>
        <td><a >US02</a></td>
        <td>Alta</td>
        <td><a ><a id="RF09" href="#anchor_10">RF09</a></td>
    </tr>
    <tr>
        <td>Eu, como cidadão, quero a facilidade de acessar um QR Code no aplicativo para a leitura do meu Título. </td>
        <td><a >US08</a></td>
        <td>Média</td>
        <td><a > <a id="RF28" href="#anchor_29">RF28</a> </td>
    <tr>
        <td>Eu, como cidadão, desejo a capacidade de fazer o download da comprovação da minha justificativa. </td>
        <td><a >US07</a></td>
        <td>Alta</td>
        <td><a ><a id="RF27" href="#anchor_28">RF27</a></td>
    </tr>
        <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, desejo a capacidade de escolher o formato do arquivo, como PDF ou DOC, ao realizar o download de documentos no aplicativo, proporcionando-me flexibilidade na utilização dos arquivos baixados.</td>
        <td><a >US15</a></td>
        <td>Alta</td>
        <td><a > <a id="RF10" href="#anchor_11">RF10</a> <a id="RF19" href="#anchor_20">RF19</a></td>
    </tr>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=7 style="vertical-align: middle; text-align: center"> <a ><a id="RF51" href="#anchor_51">E03</a> </a></td>
        <!-- Tema  -->
        <td rowspan=7 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, gostaria de visualizar a localização do meu local de votação no aplicativo.</td>
        <td><a >US10</a></td>
        <td>Alta</td>
        <td><a > <a id="RF04" href="#anchor_5">RF04</a>  <a id="RF12" href="#anchor_13">RF12</a>  <a id="RF13" href="#anchor_14">RF13</a> <a id="RF47" href="#anchor_48">RF47</a></td>
    </tr>
    <tr>
        <td>Eu, como cidadão, desejo a capacidade de visualizar meu documento do título eleitoral de forma fácil e acessível. </td>
        <td><a >US02</a></td>
        <td>Alta</td>
        <td><a > <a id="RF05" href="#anchor_6">RF05</a> </td>
    </tr>
    <tr>
        <td>Eu, como cidadão, desejo a capacidade de escolher visualizar informações sobre as documentações necessárias pelo aplicativo.</td>
        <td><a >US07</a></td>
        <td>Alta</td>
        <td><a > <a id="RF14" href="#anchor_15">RF14</a><a id="RF15" href="#anchor_16">RF15</a></td>
    </tr>
    <tr>
        <td>Eu, como cidadão, desejo a capacidade de visualizar todos os dados presentes no meu documento de título eleitoral diretamente no aplicativo, proporcionando-me acesso fácil e conveniente às informações relevantes. </td>
        <td><a >US02</a></td>
        <td>Alta</td>
        <td><a > <a id="RF11" href="#anchor_12">RF11</a></td>
    </tr>
    <tr>
        <td>Eu, como cidadão, desejo a capacidade de visualizar a minha situação de quitação eleitoral pelo aplicativo. </td>
        <td><a >US13</a></td>
        <td>Alta</td>
        <td><a> <a id="RF16" href="#anchor_17">RF16</a></td>
    </tr>
    <tr>
        <td>Eu, como cidadão, desejo a capacidade de visualizar tutoriais a respeito dos meus documentos no aplicativo. </td>
        <td><a >US14</a></td>
        <td>Alta</td>
        <td><a ><a id="RF29" href="#anchor_30">RF29</a> </td>
    <tr>
        <td>Eu, como cidadão, gostaria de visualizar de forma clara no aplicativo o candidato eleito referente ao ano da votação. </td>
        <td><a >US03</a></td>
        <td>Alta</td>
        <td><a > <a id="RF33" href="#anchor_34">RF33</a> </td>
    </tr>
     <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a ><a id="RF52" href="#anchor_52">E04</a> </a></td>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, valorizo a facilidade de encontrar o termo de uso no aplicativo. </td>
        <td><a >US04</a></td>
        <td>Alta</td>
        <td><a ><a id="RF34" href="#anchor_35">RF34</a></td>
    </tr>
    <tr>
        <td>Eu, como cidadão, desejo a capacidade de concordar ou não com os termos de uso no aplicativo. </td>
        <td><a >US04</a></td>
        <td>Alta</td>
        <td><a > <a id="RF35" href="#anchor_36">RF35</a></td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a ><a id="RF53" href="#anchor_53">E05</a> </a></td>
        <!-- Tema  -->
        <td rowspan=3 style="vertical-align: middle"> Segurança</td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, espero a facilidade de recuperar minha senha no aplicativo quando necessário. </td>
        <td><a >US05</a></td>
        <td>Alta</td>
        <td><a ><a id="RF36" href="#anchor_37">RF36</a></td>
    </tr>
    <tr>
        <td>Eu, como cidadão, quero a capacidade de fazer alterações nos meus dados cadastrais no aplicativo para manter as informações atualizadas. </td>
        <td><a >US12</a></td>
        <td>Alta</td>
        <td><a ><a id="RF08" href="#anchor_9">RF08</a> <a id="RF20" href="#anchor_21">RF20</a></td>
    </tr>
    <tr>
        <td>Eu, como cidadão, desejo a capacidade de alterar a foto do documento do título eleitoral pelo aplicativo.</td>
        <td><a >US02</a></td>
        <td>Alta</td>
        <td><a ><a id="RF23" href="#anchor_24">RF23</a> </td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=1 style="vertical-align: middle; text-align: center"> <a ><a id="RF54" href="#anchor_54">E06</a> </a></td>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Segurança</td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, sugiro que o aplicativo permita o acesso apenas a usuários com 16 anos ou mais, considerando sua aptidão para votar. </td>
        <td><a >US06</a></td>
        <td>Alta</td>
        <td><a ><a id="RF39" href="#anchor_40">RF39</a></td>
    </tr>
     <tr>
        <!-- Épico -->
        <td rowspan=3 style="vertical-align: middle; text-align: center"> <a ><a id="RF55" href="#anchor_55">E07</a> </a></td>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade</td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, gostaria de poder informar minha justificativa diretamente no aplicativo, proporcionando uma forma conveniente de cumprir esse procedimento. </td>
        <td><a >US18</a></td>
        <td>Alta</td>
        <td><a ><a id="RF18" href="#anchor_19">RF18</a></td>
    </tr>
     <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Documento </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, desejo a capacidade de receber comprovação de meus débitos pelo aplicativo,</td>
        <td><a >US17</a></td>
        <td>Alta</td>
        <td><a> <a id="RF26" href="#anchor_27">RF26</a></td>
    </tr>
     <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Segurança </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, desejo que o aplicativo me forneça a visualização das autenticidades dos meus documentos, garantindo transparência e confiança. </td>
        <td><a >US07</a></td>
        <td>Média</td>
        <td><a ><a id="RF27" href="#anchor_28">RF27</a> </td>
    </tr>
     <tr>
        <!-- Épico -->
        <td rowspan=1 style="vertical-align: middle; text-align: center"> <a ><a id="RF56" href="#anchor_56">E08</a> </a>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade</td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, desejo a capacidade de visualizar notificações no aplicativo que me alertem sobre datas cruciais ou informações importantes.</td>
        <td><a >US08</a></td>
        <td>Alta</td>
        <td><a > <a id="RF06" href="#anchor_7">RF06</a> <a id="RF24" href="#anchor_25">RF24</a><a id="RF25" href="#anchor_26">RF25</a> <a id="RF32" href="#anchor_33">RF32</a></td>
    </tr>
     <tr>
        <!-- Épico -->
        <td rowspan=4 style="vertical-align: middle; text-align: center"> <a ><a id="RF57" href="#anchor_57">E09</a> </a>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, desejo a presença da opção de sair ou realizar logoff no aplicativo, proporcionando-me o controle sobre a minha sessão e garantindo a segurança das minhas informações. </td>
        <td><a >US11</a></td>
        <td>Alta</td>
        <td><a > <a id="RF07" href="#anchor_8">RF07</a> </td>
    </tr>
    <tr>
        <td>Eu, como cidadão, valorizo a presença de suporte no aplicativo para me auxiliar em eventuais dúvidas ou problemas, caso eu não entenda alguma coisa de sua utilidade. </td>
        <td><a >US14</a></td>
        <td>Alta</td>
        <td><a > <a id="RF30" href="#anchor_31">RF30</a><a id="RF37" href="#anchor_38">RF37</a><a id="RF38" href="#anchor_39">RF38</a> <a id="RF41" href="#anchor_42">RF41</a></td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=2 style="vertical-align: middle"> Segurança</td>
        <!-- Histórias de Usuário (2) -->
        <td>Eu, como cidadão, considero crucial que o aplicativo ofereça segurança robusta, protegendo meus dados por meio de etapas de segurança eficazes. </td>
        <td><a >US07</a></td>
        <td>Alta</td>
        <td><a > <a id="RF44" href="#anchor_45">RF44</a> <a id="RF43" href="#anchor_44">RF43</a> </td>
    </tr>
    <tr>
        <td>Eu, como cidadão, desejo que o aplicativo contribua para a transparência ao disponibilizar informações abrangentes e acessíveis sobre os candidatos. </td>
        <td><a >US03</a></td>
        <td>Alta</td>
        <td><a ><a id="RF42" href="#anchor_43">RF42</a></td>
    </tr>
    <tr>
        <!-- Épico -->
        <td rowspan=2 style="vertical-align: middle; text-align: center"> <a ><a id="RF58" href="#anchor_58">E10</a> </a>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Funcionalidade </td>
        <!-- Histórias de Usuário (1) -->
        <td>Eu, como cidadão, aprecio a integração do aplicativo com links para o site do TSE e outras funcionalidades externas, ampliando suas capacidades além do seu escopo próprio. </td>
        <td><a >--</a></td>
        <td>Baixa</td>
        <td><a ><a id="RF46" href="#anchor_47">RF46</a></td>
    </tr>
    <tr>
        <!-- Tema  -->
        <td rowspan=1 style="vertical-align: middle"> Documento </td>
        <!-- Histórias de Usuário (1) -->
        <td> Eu, como cidadão, desejo que a navegação no aplicativo seja limpa e intuitiva, sem excesso de informações que possam causar confusão.</td>
        <td><a >--</a></td>
        <td>Alta</td>
        <td><a ><a id="RF45" href="#anchor_46">RF45</a></td>
    </tr>

</table>

<div align="center">
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023. </p>
</div>

## Bibliografia

> RADIGAN, Dan. O backlog do produto: sua lista de tarefas definitiva. Atlassian. Disponível em: [Backlog](https://www.atlassian.com/br/agile/scrum/backlogs). Acesso em 22 out, 2023.

> O QUE É BACKLOG DO PRODUTO SCRUM E COMO FAZER UM. Lucidchart. Disponível em: [Backlog](https://www.lucidchart.com/blog/pt/como-fazer-um-backlog-do-produto). Acesso em 22 out, 2023.

> SANTOS, Cris. Como Construir Um Product Backlog: Guia Em Pdf. Disponível em> [Backlog](https://awari.com.br/como-construir-um-product-backlog-guia-em-pdf-4/?utm_source=blog&utm_campaign=projeto+blog&utm_medium=Como%20Construir%20Um%20Product%20Backlog:%20Guia%20Em%20Pdf). Acesso em 06 nov, 2023.

> 2022.2-Lichess. Backlog. Disponível em: [Backlog](https://github.com/Requisitos-de-Software/2022.2-Lichess/blob/main/docs/modelagem/agil/backlog.md). Acesso em 06 nov, 2023.

> <a id="REF1" href="#anchor_1">[1]</a> SERRANO, Milene e SERRANO, Maurício. Requisitos - Aula 15. Disponível em: [Backlog](https://aprender3.unb.br/pluginfile.php/2692826/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf).Acesso em 06 nov, 2023.

## Histórico de Versões
|  Versão    | Data | Descrição                   |    Autor(es)     |  Revisor(es) |
| :--------: | :----: | :-------------------------: | :--------------: | :---------: |
|  `1.0`  |  05/11/2023  | Criação do documento               | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza)   | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques)  |
|  `1.1` |  06/11/2023  | Adição de introdução e metodologia | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques)  |
|  `1.2` | 06/11/2023  | Adição do resto da documentação | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques)  |
| `1.3` | 29/11/2023 |  Correção das tabelas deixando em formato ABNT, mudando objetivo, chamando referencia, corrigindo erros e linkagem e mudando a estrutura da tabela de backlog deixando ela mais compreenssivél. |[Esther Sena](https://github.com/esmsena)| [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
| `1.4` | 05/12/2023 |  Adição dos requisitos corrigidos, linkagens de REF e Épicos na tabela de backlog e adicionando os novos requisitos a tabela de backlog, modificando os antigos | [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
| `1.5` | 06/12/2023 |  Adição dos ID's das Histórias de Usuário na tabela de backlog | [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |s
