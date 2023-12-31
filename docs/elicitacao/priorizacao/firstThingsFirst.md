# First Things First

## Introdução
É importante utilizar uma técnica de priorização para dar prioridade às tarefas mais importantes a serem implementadas. Será apresentado neste artefato a técnica do FTF(First Things First) e como vamos utilizá-lo no projeto.

## Motivação e Objetivo

A motivação de se usar a técnica First Things First, deve-se ao fato de que a técnica ajuda a garantir que os recursos sejam alocados de forma eficaz desde o início do projeto, focando assim nos requistos que realmente importam. Isso contribui para o sucesso geral do projeto e ajuda a evitar o desperdício de tempo e recursos em requistos menos críticos, maximizando as chances de sucesso. Dessa forma, o objetivo principal de se usar a técnica FTF é devido à sua eficácia, proporcionando clareza, foco e direção às equipes de desenvolvimento.

## Metodologia

A técnica de priorização first things first (FTF) tem como objetivo apresentar em forma de tabela os riscos, custos, benefícios e a penalidade relativa de cada requisito elicitado para o projeto, estabelecendo uma ordem de prioridade de implementação. A seguir, são explicados os passos fundamentais para a elaboração dessa técnica, encontrados no livro na Referência<a id=anchor_1 href="#REF1">[1]</a>:

**Passo 1:** Listar todos os requisitos, funcionalidades ou casos de uso que você deseja priorizar em uma planilha;

**Passo 2:** Estimar o benefício relativo que cada funcionalidade oferece ao cliente ou ao negócio em uma escala de 1 a 9, sendo 1 indicando muito pouco benefício e 9 sendo o benefício máximo possível. 

**Passo 3:** Estime a penalização relativa que o cliente ou o negócio sofreria se a funcionalidade não fosse incluída. Novamente, use uma escala de 1 a 9, onde 1 significa essencialmente nenhuma penalização e 9 indica uma desvantagem muito séria.

**Passo 4:** A coluna "Valor Total" é a soma do benefício relativo e da penalização. Por padrão, benefício e penalização têm o mesmo peso. Como refinamento, alteramos o benefício relativo para peso 2, assim, todas as classificações de benefício têm o dobro do peso das classificações de penalização. A planilha totaliza os valores das funcionalidades e calcula a porcentagem do valor total do produto que é atribuída a cada funcionalidade.

**Passo 5:** Estime o custo relativo de implementar cada funcionalidade, novamente em uma escala de 1 a 9. A planilha calculará a porcentagem do custo total para cada funcionalidade. 

**Passo 6:** Os desenvolvedores estimam o grau relativo de risco técnico ou outro risco associado a cada funcionalidade em uma escala de 1 a 9. planilha calculará a porcentagem do risco total que vem de cada funcionalidade.

**Passo 7:** Calcular um número de prioridade para cada funcionalidade. A fórmula para a coluna de Prioridade é: prioridade = valor % / (custo % * peso do custo + risco % * peso do risco).

**Passo 8:** Ordenar a lista de funcionalidades em ordem decrescente de prioridade calculada. 

- Para o passo 2 e passo 3 gravamos uma reunião na qual a [Mariiana Siqueira](https://github.com/Maryyscreuza) foi a gerente e utilizamos a persona Felipe Augusto, interpretada por [João Victor](https://github.com/jvcostta) como representante dos clientes, para a obtenção de respostas. Para o passo 5 e o passo 6 a gerente se reuniu com a representante dos desenvolvedores [Maria Eduarda Marques](https://github.com/EduardaSMarques) para montagem. Por fim, novamente foram reunidas [Mariiana Siqueira](https://github.com/Maryyscreuza) e [Maria Eduarda Marques](https://github.com/EduardaSMarques) para o total preenchimento da tabela disponível neste documento, de onde foi transferido os dados da planilha para markdown.

- Para a priorização foi definido:

    - Alta = 1 ou mais;
    - Média = 0,50 até 0,99;
    - Baixa = 0,49 ou menos.

**Link para planilha:**[https://docs.google.com/spreadsheets/d/e/2PACX-1vTrkooXhe3LtDRe1x7E2ZCuzIunN-dLViwi6FxfRSX_KoGhP0fSiT1S4JJ1xgfN5oYwq4r40GNap6S9/pubhtml](https://docs.google.com/spreadsheets/d/e/2PACX-1vTrkooXhe3LtDRe1x7E2ZCuzIunN-dLViwi6FxfRSX_KoGhP0fSiT1S4JJ1xgfN5oYwq4r40GNap6S9/pubhtml)

## Requisitos Elicitados

Na Tabela 1 estão registrados todos os requisitos elicitados durante o processo de [elicitação](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/tree/feature-Backlogs/docs/elicitacao/tecnicas), juntamente com a origem de cada requisito.

### Legenda:
* BS: Requisitos de [Brainstorming](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) 
* BSNF: Requisitos não-funcionais de [Brainstorming](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
* ENT: Requisitos de [Entrevista](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
* ENTNF: Requisitos não-funcionais de [Entrevista](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
* INT: Requisitos de [Introspecção](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
* INTNF: Requisitos não-funcionais de [Introspecção](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
* QSTNF: Requisitos não-funcionais de [Questionário](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/)
* ST: Requisitos de [Storytelling](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)

<p> Tabela 1: Requisitos elicitados </p>
  
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

Fonte: Fonte: SIQUEIRA, Mariiana e MARQUES, Maria Eduarda. 2023.

## Resultados

A Tabela 2, contém a priorização dos requisitos elicitados utilizando a técnica First Things First. Nem todos os requisitos estão presentes na tabela pois diferentes métodos elicitaram requisitos semelhantes.

Tabela 2: Priorização de requisitos utilizando a técnica First Things First. 
| Peso relativo | 2| 1 |  | | 1 |  | 1 |  |  | 
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| **ID** | **Benefício Relativo** | **Penalidade Relativa** | **Valor Total** | **Valor %** | **Custo Relativo** | **Custo %** | **Risco Relativo**  | **Risco %** |**Prioridade** |
 | <a id="RF01" href="#anchor_2">RF01</a> | 9 | 9 |  27 | 2,94% | 3 |	3,09%	|3|	2,31%|	0,54|
 | <a id="RF02" href="#anchor_3">RF02</a> | 7 | 1 |  15| 1,63% |  5	|5,15%|7	|5,38%	|0,15|
 | <a id="RF03" href="#anchor_4">RF03</a> | 8 | 9 | 25 | 2,72% |  1	|1,03%|	2	|1,54%	|1,06|
 | <a id="RF04" href="#anchor_5">RF04</a> | 9 | 5 | 23 | 2,50% |  2	|2,06%|	3	|2,31%	|0,57|
 | <a id="RF05" href="#anchor_6">RF05</a> | 9 | 3 | 21 | 2,29% |  2	|2,06%	|1 |	0,77%	|0,81| 
 | <a id="RF06" href="#anchor_7">RF06</a> | 7 | 5 | 19 | 2,07% |  4	|4,12%	|6	|4,62%	|0,24| 
 | <a id="RF07" href="#anchor_8">RF07</a> | 8 | 1 | 17 | 1,85% | 1	|1,03%	|1	|0,77%	|1,03| 
 | <a id="RF08" href="#anchor_9">RF08</a> | 9 | 9 | 27 | 2,94% | 3 |3,09%	|5	|3,85%	|0,42|  
 | <a id="RF09" href="#anchor_10">RF09</a> | 7 | 5 | 19 | 2,07% | 1	|1,03%	|2	|1,54%	|0,80|
 | <a id="RF10" href="#anchor_11">RF10</a> | 5 | 1 | 11 | 1,20% | 1	|1,03%|	1	|0,77%	|0,66|
 | <a id="RF11" href="#anchor_12">RF11</a> | 8 | 5 | 21 |2,29%  | 1	|1,03%	|2	|1,54%	|0,89| 
 | <a id="RF12" href="#anchor_13">RF12</a> | 7 | 1 | 15 | 1,63% |3	|3,09%	|3	|2,31%	|0,30|  
 | <a id="RF13" href="#anchor_14">RF13</a> | 6 | 1 | 13 | 1,41% | 1	|1,03%	|3|	2,31%	|0,42| 
 | <a id="RF14" href="#anchor_15">RF14</a> | 9 | 7 | 25 | 2,72% | 1 |	1,03%|	1|	0,77%	|1,51|  
 | <a id="RF15" href="#anchor_16">RF15</a> | 8 | 7 | 23 | 2,50% | 1	|1,03% |	1|	0,77% |	1,39| 
 | <a id="RF16" href="#anchor_17">RF16</a> | 9 | 9 | 27 | 2,94% | 2|	2,06%|	1	|0,77%	|1,04|  
 | <a id="RF17" href="#anchor_18">RF17</a> | 5 | 2 | 12 | 1,31% | 2	|2,06%|	2	|1,54%	|0,36| 
 | <a id="RF18" href="#anchor_19">RF18</a> | 6 | 5 | 17 | 1,85% | 1|	1,03%|	1	|0,77%	|1,03| 
 | <a id="RF19" href="#anchor_20">RF19</a> | 6 | 2 | 14 | 1,52% | 1	|1,03%	|1	|0,77%	|0,85|
 | <a id="RF20" href="#anchor_21">RF20</a> | 8 | 9 | 25 | 2,72% | 2	|2,06%|	4	|3,08%	|0,53|  
 | <a id="RF21" href="#anchor_22">RF21</a> | 2 | 2 | 6 | 0,65% | 1	|1,03%	|1	|0,77%	|0,36|  
 | <a id="RF22" href="#anchor_23">RF22</a> | 1 | 1 | 2 | 0,33% | 2	|2,06%	|3	|2,31%|	0,07|  
 | <a id="RF23" href="#anchor_24">RF23</a> | 3 | 1 | 7 | 0,76% | 2	|2,06%|	2	|1,54%	|0,21|  
 | <a id="RF24" href="#anchor_25">RF24</a> | 8 | 8 | 24 | 2,61% | 3	|3,09%|	4|	3,08%	|0,42| 
 | <a id="RF25" href="#anchor_26">RF25</a> | 9 | 5 | 23 | 2,50% | 5	|5,15%|	7|	5,38%|	0,24| 
 | <a id="RF26" href="#anchor_27">RF26</a> | 7 | 6 | 20 | 2,18% | 3	|3,09%|	3	|2,31%	|0,40|   
 | <a id="RF27" href="#anchor_28">RF27</a> | 7 | 7 | 21 | 2,29% | 2	|2,06%	|3	|2,31%	|0,52| 
 | <a id="RF28" href="#anchor_29">RF28</a> | 9 | 9  | 27 | 2,94% | 2	|2,06%	|4	|3,08%	|0,57| 
 | <a id="RF29" href="#anchor_30">RF29</a> | 5 | 4 | 14 | 1,52% | 1	|1,03%	|2	|1,54%	|0,59|  
 | <a id="RF30" href="#anchor_31">RF30</a> | 5 | 5 | 15 | 1,63% | 2	|2,06%	|2	|1,54%	|0,45| 
 | <a id="RF31" href="#anchor_32">RF31</a> | 9 | 8 | 26 | 2,83% | 1	|1,03%	|1	|0,77%	|1,57|  
 | <a id="RF32" href="#anchor_33">RF32</a> | 8 | 5 | 21 | 2,26% | 4	|4,12%	|6	|4,62%	|0,26|   
 | <a id="RF33" href="#anchor_34">RF33</a> | 1 | 1 | 3 | 0,33% | 1	|1,03%	|3	|2,31%	|0,10|  
 | <a id="RF34" href="#anchor_35">RF34</a> | 9 | 9 | 27 | 2,94% | 1	|1,03%	|1	|0,77%	|1,63| 
 | <a id="RF35" href="#anchor_36">RF35</a> | 9 | 9 | 27 | 2,94% | 1	|1,03%	|1	|0,77%	|1,63|  
 | <a id="RF36" href="#anchor_37">RF36</a> | 9 | 9 | 27 | 2,94% | 2	|2,06%	|4	|3,08%	|0,57| 
 | <a id="RF37" href="#anchor_38">RF37</a> | 8 | 4 | 20 | 2,18% | 1	|1,03%	|3	|2,31%	|0,65| 
 | <a id="RF38" href="#anchor_39">RF38</a> | 7 | 3 | 17 | 1,85% | 1	|1,03%	|1	|0,77%	|1,03|  
 | <a id="RF39" href="#anchor_40">RF39</a> | 9 | 9 | 27 | 2,94% | 1	|1,03%	|1	|0,77%	|1,63|  
 | <a id="RF40" href="#anchor_41">RF40</a> | 7 | 7 | 21 | 2,29% | 3	|3,09%	|3	|2,31%	|0,42|
 | <a id="RF41" href="#anchor_42">RF41</a> | 5 | 7  | 17 | 1,85% | 2	|2,06%	|2	|1,54%	|0,51| 
 | <a id="RF42" href="#anchor_43">RF42</a> | 6 | 4 | 16 | 1,74% | 1	|1,03%	|4	|3,08%	|0,42| 
 | <a id="RF43" href="#anchor_44">RF43</a> | 9 | 9 | 27 | 2,94% | 4	|4,12%	|6	|4,62%	|0,34| 
 | <a id="RF44" href="#anchor_45">RF44</a> | 9 | 9 | 27 | 2,94% | 6	|6,19%	|6	|4,62%	|0,27| 
 | <a id="RF45" href="#anchor_46">RF45</a> | 9 | 7 | 25 | 2,72% | 2	|2,06%	|2	|1,54%	|0,76|  
 | <a id="RF46" href="#anchor_47">RF46</a> | 3 | 3 | 9 | 0,98% | 2	|2,06%	|1	|0,77%	|0,35|  
 | <a id="RF47" href="#anchor_48">RF47</a> | 9 | 8 | 26 | 2,83% | 3	|3,09%	|4	|3,08%	|0,46|  
 | **Total** | 332 | 255 | 919 | 100% | 97 |100%	|130	|100%	|31,08|

Fonte: Fonte: SIQUEIRA, Mariiana e MARQUES, Maria Eduarda. 2023.

## Gravação da técnica First Things First

Para a elaboração desta técnica, foram feitas duas gravações. A primeira, presente no vídeo 1, foi realizada com o cliente; e a segunda parte, que está no vídeo 2, foi feita com o desenvolvedor.

- Caso não consiga assistir dentro da gitPages, [Clique aqui para assistir a elaboração da técnica com o cliente](https://youtu.be/A-0zXLsl0Mw)
  
**Vídeo 1** - elaboração da técnica com o cliente.
  
<iframe width="560" height="315" src="https://www.youtube.com/embed/A-0zXLsl0Mw?si=9MHxu1ojL78opd6T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center">Fonte: [SIQUEIRA, Mariiana](https://github.com/Maryyscreuza) e [MARQUES, Maria Eduarda](https://github.com/EduardaSMarques).</p></font>


- Caso não consiga assistir dentro da gitPages, [Clique aqui para assistir a elaboração da técnica com o desenvolvedor](https://youtu.be/3XISq-vDI6M)

**Vídeo 2** - elaboração da técnica com o desenvolvedor.
  
<iframe width="560" height="315" src="https://youtu.be/3XISq-vDI6M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center">Fonte: SIQUEIRA, Mariiana e MARQUES, Maria Eduarda.</p></font>


## Bibliografia

> 2023.1-VLC, First Things First. 01 mai 2023. Disponível em https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/elicitacao/first_things_first.md. Acesso em: 04 de out 2023.

## Referencia

> <a id="REF1" href="#anchor_1">[1]</a>  WIEGER, Karl E. First Things First: Prioritizing Requirements. Setembro de 1999. Disponível em https://www.processimpact.com/articles/prioritizing.pdf. Acesso em: 02 de out 2023.
 
## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `1.0`  | 02/10/2023  | Realização da intro. , metologia e uma das técnicas  | [Maria Marques ](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.1`  | 04/10/2023  | Edição de metodologia, adicionando a gravação | [Maria Marques ](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.2`  | 01/12/2023  | Adicionando tabela do FTF | [Maria Marques ](https://github.com/EduardaSMarques) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.3`  | 01/12/2023  | Adição dos novos requisitos elicitados | [Maria Marques ](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.4`  | 02/12/2023  | Adição na tabela dos resultados obtidos com a persona  | [Maria Marques ](https://github.com/EduardaSMarques) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.5`  | 03/12/2023  | Add o resultado com o desenvolvedor e add os vídeos da técnica | [Maria Marques ](https://github.com/EduardaSMarques) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.6`  | 05/12/2023  | Ajuste nas fontes das tabelas e link do vídeo | [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |