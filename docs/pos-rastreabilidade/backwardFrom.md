# Backward From

## Introdução

Neste documento, exploraremos a abordagem "Backward From" na elicitação de requisitos, que nos leva do resultado desejado às raízes dos requisitos. Diferente das metodologias convencionais, essa técnica oferece uma compreensão mais profunda do contexto e das variáveis que influenciam os requisitos.

## Objetivo 

Este documento é um guia para usar a técnica "Backward From" na obtenção de requisitos. Vamos explorar como essa abordagem nos ajuda a entender melhor o que um sistema precisa, começando pelo resultado desejado e retrocedendo até as necessidades fundamentais. A ideia é oferecer uma ferramentas para aplicar essa técnica de engenharia reversa de requisitos de forma inovadora, ajudando no desenvolvimento de sistemas mais sólidos e claros. 

## Metodologia

A rastreabilidade vai além de apenas gerenciar requisitos; ela se torna um importante aliado na busca pela excelência na gerência de qualidade. O Meta-modelo proposto por Toranzo oferece uma abordagem que facilita a especificação do rastreamento, tornando o processo mais simples e eficaz.

Ao usar o Meta-modelo de Toranzo para a elaboração do artefato, passamos por dois passos importantes, que estão explicados nos slides 19 e 21 do arquivo "Requisitos-Aula 26"<a id=anchor_1 href="#REF1">[1]</a> de Miriam Sayão e Julio Cesar Sampaio do Prado Leite.

Essas etapas iniciais compreendem os conceitos de níveis e elos, fundamentais para a construção de um rastro eficaz.

Níveis:

   - Ambiental: Envolvendo informações provenientes do contexto em que a organização está inserida;
   - Organizacional: Compreendendo dados intrínsecos à organização, como missão, objetivos e estratégias;
   - Gerencial: Incluindo informações cruciais para a gerência do projeto;
   - Desenvolvimento: Abordando dados associados aos diversos artefatos gerados ao longo do processo de desenvolvimento, tais como artefatos de requisitos, diagramas, códigos, casos de teste, entre outros.

Elos Principais:

   - Satisfação: Estabelece uma dependência da classe origem em relação à satisfação da classe destino.
   - Recurso: Delimita uma dependência da classe origem em relação ao recurso da classe destino.
   - Responsabilidade: Registra a participação, responsabilidade e ação de pessoas sobre os artefatos.
   - Representação: Captura a representação ou modelagem dos requisitos em outras linguagens.
   - Alocado: Relaciona a classe origem à classe destino, representando um subsistema.
   - Agregação: Indica a "composição" de elementos.

Para colocar em prática a metodologia, inicialmente elaboramos duas tabelas distintas: uma dedicada aos requisitos funcionais ( Tabela 1 ) e outra para os requisitos não funcionais ( Tabela 2 ). Posteriormente, inserimos a fonte de origem desses requisitos nas tabelas, garantindo a rastreabilidade. Por último, empregando o Meta-modelo de Toranzo, delineamos as interconexões entre esses requisitos por meio dos Elos.

## Tabelas de requisitos

Este segmento tem como foco a criação da tabela de rastreamento de requisitos funcionais, a qual é apresentada de forma detalhada na Tabela 1 abaixo:

### Legendas:
* RFnº : Requisito funcional;
* RNFnº : Requisito não funcional;
* [QSTnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) : Questionário;
* [QSTNFnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) : Questionário não-funcional;
* [STnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) : Storytelling;
* [STNFnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) : Storytelling não-funcional;
* [ENTnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) : Entrevista;
* [ENTNFnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) : Entrevista não-funcional;
* [BSnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) : Brainstorming;
* [BSNFnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) : Brainstorming não-funcional;
* [INTnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  : Introspecção;
* [INTNFnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  : Introspecção não-funcional;

### Requisitos funcionais:

Tabela 1: Requisitos funcionais 

| ID | Descrição | Origem | Implementado | 
| :--: | :--: | :--: | :--: |
|  <a id=anchor_2 href="#RF01">RF01</a> | No aplicativo deve ser possível realizar o cadastro do usuário com o uso de dados pessoais como senha, endereço, CPF e RG | [INT1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [BS1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) , [ENT1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Sim |
| RF02 | Deve ser possível o usuário cadastrar sua biometria durante o processo de cadastro. |  [INT2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Sim |
| RF03 | O usuário deve poder escolher a forma de realizar o login. | [QST2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) | Sim |
| <a id=anchor_5 href="#RF04">RF04</a> | O usuário deve conseguir fazer o login preenchendo os campos de entrada como senha e CPF para acessar o aplicativo caso já tenha se cadastrado. | [INT3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [QST4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) ,  [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| <a id=anchor_6 href="#RF05">RF05</a> | O usuário deve poder realizar o login com a biometria | [QST3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) ,  [ENT2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) ,  [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)| Sim |
| <a id=anchor_7 href="#RF06">RF06</a> | Deve ser possível o usuário vizualizar a localização da votação. | [INT4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [QST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) , [ST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) , [ENT6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) , [BS5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| <a id=anchor_8 href="#RF07">RF07</a> | Deve ser possível o usuário vizualizar seu documento do título eleitoral. | [INT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [ENT3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) , [QST5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) , [ST3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) | Sim |
| <a id=anchor_9 href="#RF08">RF08</a> | Deve ser possível o usuário realizar o download do documento título eleitoral no aplicativo. | [INT9](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [BS3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) , [ST2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) | Sim |
| RF09 | O usuário deve conseguir visualizar as notificações do aplicativo, que alertam sobre datas ou informações importantes. | [INT6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) ,  [BS6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)  | Sim |
| RF10 | O aplicativo deve ter a opção de sair/logoff disponível para o usuário. | [INT7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Sim |
| <a id=anchor_12 href="#RF11">RF11</a> | O usuário deve conseguir fazer alterações em seus dados cadastrais. | [INT8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/), [BS11](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| RF12 | No aplicativo deve ser possível o usuário realizar a recuperação da senha. | [BS10](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| RF13 | Deve ser possível o usuário visualizar as dúvidas frequentes do aplicativo | [BS12](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| RF14 | O aplicativo deve disponibilizar ao usuário a função de acessar o site do TSE para conseguir relatar feedbacks e problemas do aplicativo | [BS13](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| RF15 | No aplicativo deve ser possível o usuário vizualizar os termos de uso. | [BS7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| RF16 | No aplicativo deve ser possível o usuário concordar ou não com os termos de uso. | [BS8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim | 
| RF17 | Deve ser possível o usuário escolher o formato do arquivo, como pdf ou doc, a ser baixado do aplicativo. | [INT10](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  | Sim |
| RF18 | O usuário deve conseguir visualizar no aplicativo todos os dados presentes em um documento de título eleitoral. | [INT11](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Sim |
| RF19 |  Deve ser possível o usuário visualizar as rotas de sua localização atual até o seu local de votação pelo aplicativo. | [INT13](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Não |
| RF20 | O usuário deve conseguir escolher o local de partida. | [INT14](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  | Não |
| RF21 | O usuário deve conseguir escolher visualizar sobre as documentações nescessárias. | [INT15](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Não |
| RF22 | O usuário deve conseguir vizualizar os dados documentais. | [INT16](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Sim |
| <a id=anchor_24 href="#RF23">RF23</a> | No aplicativo deve ser possível que o usuário realize a quitação eleitoral | [ENT4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) , [ST5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)  | Não |
| <a id=anchor_25 href="#RF24">RF24</a> | O usuário deve conseguir vizualizar as informações da quitação eleitoral. | [INT17](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [ENT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Sim |
| RF25 | O usuário deve conseguir vizualizar dados referentes ao criminal eleitoral. | [INT18](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  | Sim |
| RF26 | O usuário deve conseguir informar a sua justificativa no aplicativo. | [INT19](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  | Sim |
| RF27 | O usuário deve realizar download da comprovação de sua justificativa. | [INT20](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Não |
| <a id=anchor_29 href="#RF28">RF28</a> | O usuário deve poder alterar seus dados pessoais, por meio do site do TSE. | [INT21](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [BS11](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| RF29 | Deve ser possível o usuário apagar seus dados pessoais. | [INT22](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Sim |
| RF30 | Deve ser possível o usuário ver o histórico de dados apagados. | [INT23](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  | Não |
| RF31 | Deve ser possível o usuário acompanhar a apuração de votos | [ENT8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Não |
| RF32 | O usuário deve visualizar o candidato eleito referente ao ano da votação. | [ENT9](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Não |
| <a id=anchor_34 href="#RF33">RF33</a> | Eu como usuário, quero poder visualizar as notificação de datas e horários das eleições | [ST4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) , [ENT7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Não |
| RF34 | O aplicativo deve permitir que os usuários alterem a foto do documento do título eleitoral. |  [INT24](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Não |
| RF35 | O aplicativo deve permitir que o usuário altere o local de partida. |  [INT25](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Não |
| RF36 | O aplicativo deve notificar sobre atualizações eleitorais. |  [INT26](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Não |
| RF37 | O aplicativo deve demonstrar ao usuário os lembretes de votação e de mudanças de localização para votação. |  [INT27](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Sim |
| RF38 | O aplicativo deve permitir que o usuário receba a comprovação de seus débitos. |  [INT28](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Sim |
| RF39 | O aplicativo deve mostrar ao usuário as autenticidades de seus documento.|  [INT29](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Sim |
| <a id=anchor_41 href="#RF40">RF40</a> | O aplicativo deve permitir a leitura do qr code do título eleitoral. |  [INT30](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [BS4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| RF41 | O aplicativo deve permitir que o usuário visualize tutoriais a respeito de seus documentos. |  [INT31](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Não |
| RF42 | O aplicativo deve permitir que o usuário envie dúvidas. | [INT32](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Não |
| RF43 | O aplicativo deve oferecer um meio de ajuda para os usuários que não entenderam alguma coisa de sua utilidade | [BS14](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Não |

<div style="text-align: center">
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.</p>
</div>

A tabela de rastreamento de requisitos não-funcionais, está apresentada de forma detalhada na Tabela 2 abaixo:

### Requisitos não funcionais:

Tabela 2: Requisitos não funcionais 

| ID | Descrição | Origem | Implementado |
| :--: | :--: | :--: | :--: |
| <a id=anchor_42 href="#RNF01">RNF01</a> | O aplicativo deve possuir um forúm para a retirada de dúvidas dos usuários. | [INTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [ENTNF5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Não |
| RNF02 | O aplicativo deve permitir apenas usuários acima de 16 anos, por serem aptos a votar | [BSNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)  | Sim |
| <a id=anchor_43 href="#RNF03">RNF03</a> | O aplicativo deve contribuir para a transparência e Eficiência das Eleições com os dados das eleições sendo disponíveis para os usuários | [BSNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) , [INTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Não |
| RNF04 | O aplicativo deve ser confiável para o usuário | [BSNF3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Sim |
| RNF05 | Para o aplicativo ser utilizado, o dispositivo que mantém ele instalado deve precisar ter acesso a internet | [BSNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)  | Sim |
| RNF06 | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo. | [ENTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Sim |
| RNF07 | O aplicativo deve possuir um design intuitivo com elementos como botão e menu padronizados | [ENTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Sim |
| RNF08 | A navegação do aplicativo não deve ser poluída, como excesso de informações que podem confundir os usuários. | [ENTNF3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)  | Sim |
| RNF09 | Na navegação do aplicativo deve possuir linkagem com o site do TSE ou outros aplicativos externos, assim o aplicativo possui algumas funcionalidades não sendo pertencentes a ele, mas de fora dele.| [ENTNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)  | Sim |
| RNF10 | O aplicativo deve oferecer suporte ao usuário. | [ENTNF5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)  | Sim |
| RNF11 | O aplicativo deve manter sigilo nos dados do usuário a respeito de sua justificativa, permitindo a proteção dos dados, apenas os responsáveis o vê. | [INTNF3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Sim |
| <a id=anchor_44 href="#RNF12">RNF12</a> | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança. | [INTNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) , [QSTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) , [STNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) | Sim |
| <a id=anchor_45 href="#RNF13">RNF13</a> | O aplicativo deve manter a atualização das informações do local da votação de cada usuário. | [QSTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) , [STNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) | Sim |


<div style="text-align: center">
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.</p>
</div>

## Elos

Os elos desenvolvidos neste artefato fazem referência aos requisitos elicitados listados nas <i>tabelas 1 e 2</i>, seguindo o Meta-Modelo de Toranzo para estruturação de seus elos de rastreabilidade, vistos abaixo na tabela 3.

### Elos de rastreabilidade

Tabela 3 - Elos de rastreabilidade.

| Elo | Especificação |
|:---:| :------------:|
| Agregação | implica na união ou composição de elementos |
| Representação | abrange a tradução ou modelagem de requisitos em diferentes linguagens |
| Satisfação | a classe de origem depende da satisfação proporcionada pela classe de destino |
| Recurso | a classe de origem depende dos recursos fornecidos pela classe de destino |
| Responsabilidade | documenta o envolvimento, responsabilidade e ação de indivíduos em relação aos artefatos |
| Alocado | a classe de origem está associada à classe de destino, representando um subsistema |

<div style="text-align: center">
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.</p>
</div>

## Elos Funcionais

### EF01

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF01" href="#anchor_2">RF01</a> :
        * Introspecção: [INT1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) 
        * Brainstorming: [BS1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
        * Entrevista: [ENT1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) 
        
* Elos:
    * Agregacão: [INT1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) agrega [BS1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
    * Agregação: [INT1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) agrega [ENT1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) 
    * Representação: [BS1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) representa [ENT1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
 
### EF02

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF04" href="#anchor_5">RF04</a> :
        * Introspecção: [INT3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
        * Questionário: [QST4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/)
        * Brainstorming: [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) 
        
* Elos:
    * Representação: [INT3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) representação [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
    * Agregação: [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) agrega [QST04](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/)
    * Agregação: [INT3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) agrega [QST04](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/)

### EF03

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF05" href="#anchor_6">RF05</a> :
        * Entrevista: [ENT2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
        * Questionário: [QST3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) 
        * Brainstorming: [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
        
* Elos:
    * Representação: [QST3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) representa [ENT2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) 
    * Agregação: [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) agrega [ENT2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
    * Agregação: [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) agrega [QST3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/)
      
### EF04

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF06" href="#anchor_7">RF06</a> :
        * Introspecção: [INT4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
        * Questionário: [QST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) 
        * Storytelling: [ST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
        * Entrevista: [ENT6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
        * Brainstorming: [BS5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
        
* Elos:
    * Representação: [INT4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) representa [QST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) 
    * Representação: [QST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) representa [ST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
    * Representação: [ST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) representa [ENT6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
    * Representação: [ENT6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) representa [BS5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
    * Representação: [BS5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) representa [INT4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)

### EF05

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF07" href="#anchor_8">RF07</a> :
        * Introspecção: [INT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
        * Entrevista: [ENT3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
        * Questionário: [QST05](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) 
        * Storytelling: [ST3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
        
* Elos:
    * Representação: [INT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) representa [ENT3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) 
    * Representação: [ENT3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) representa [QST5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) 
    * Representação: [QST5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) representa [ST3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
    * Representação: [ST3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) representa [INT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)

### EF06

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF08" href="#anchor_9">RF08</a> :
        * Introspecção: [INT9](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
        * Brainstorming: [BS3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
        * Storytelling: [ST2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
        
* Elos:
    * Representação: [INT9](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) representa [BS3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
    * Representação: [BS3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) representa [ST2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
    * Representação: [ST2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) representa [INT9](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)

### EF07

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF09" href="#anchor_10">RF09</a> :
        * Introspecção: [INT6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
        * Brainstorming: [BS6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
        
* Elos:
    * Agregação: [INT6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) agrega [BS6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)

### EF08
* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF11" href="#anchor_12">RF11</a> :
        * Introspecção: [INT](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
        * Brainstorming: [BS11](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
        
* Elos:
    * Agregação: [BS11](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) agrega [INT8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)


### EF09

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF23" href="#anchor_24">RF23</a> :
        * Entrevista: [ENT4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) 
        * Storytelling: [ST5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
           
* Elos:
     * Representação: [ENT4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) representa [ST5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
 
       
### EF10

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF24" href="#anchor_25">RF24</a> :
        * Introspecção: [INT17](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) 
        * Entrevista: [ENT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) 

           

 * Elos:
    * Representação: [INT17](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) representa [ENT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) 
    

### EF11

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF28" href="#anchor_29">RF28</a> :
        * Introspecção: [INT21](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
        * Brainstorming: [BS11](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)       

 * Elos:
    * Agregação: [BS11](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) agrega [INT21](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)

### EF12

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF33" href="#anchor_34">RF33</a> :
       * Storytelling: [ST4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
       * Entrevista: [ENT7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) 

           

 * Elos:
    * Agregação: [ST4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) agrega [ENT7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) 
    
### EF13

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RF40" href="#anchor_41">RF40</a> :
        * Introspecção: [INT30](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
        * Brainstorming: [BS04](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)       

 * Elos:
    * Representação : [BS04](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) representa [INT30](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)


      
## Elos não funcionais

### ENF01

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RNF01" href="#anchor_42">RNF01</a> : 
       * Introspecção: [INTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
       * Entrevista: [ENTNF5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) 
* Elos:  

    * Agregação: [INTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) agrega [ENTNF5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)


### ENF02
 
* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RNF03" href="#anchor_43">RNF03</a> : 
       * Introspecção: [INTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
       * Brainstorming: [BSNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) 

* Elos:  

    * Representação: [INTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) representa [BSNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)

### ENF03
 
* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RNF12" href="#anchor_44">RNF12</a> : 
       * Introspecção: [INTNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
       * Questionário: [QSTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) 
       * Storytelling: [STNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)


* Elos:  

    * Agregação: [INTNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) agrega [QSTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) 
     * Agregação: [INTNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) agrega [STNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
    * Representação:  [QSTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/)  representa [STNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)

### ENF04
 
* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * <a id="RNF13" href="#anchor_45">RNF13</a> : 
       * Questionário: [QSTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) 
       * Storytelling: [STNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)


* Elos:  
    * Representação: [QSTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) representa [STNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)
  
## Bibliografia

> LOPES, Pedro. RAISE - UM METAMODELO DE INFORMAÇÃO DE RASTREABILIDADE Backward From. Disponível em: <https://repositorio.ufmg.br/bitstream/1843/SLSS-8HTLX6/1/pedrolopesrochalealjr.pdf>. Acesso em: 15 Novembro. 2023.

# Referências

> <a id="REF1" href="#anchor_1">[1]</a> SERRANO, Milene e SERRANO, Maurício. Slide Requisitos. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 15 Novembro. 2023.

## Histórico de versão
| Versão | Data | Descrição | Autor | Revisor |
| :--: | :--: | :-------: | :---: | :-----: |
| `1.0`  | 15/11/2023 |  Criando estrutura do documento com formatação de tabelas, introdução, objetivo e metodologia. | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [João Victor](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy) |
| `1.1`  | 17/11/2023 |  Adicionando RF e RNF nas tabelas | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [João Victor](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy) |
| `1.2`  | 17/11/2023 |  Adicionando e preenchendo os Elos | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [João Victor](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy) |
| `1.3`  | 02/12/2023 |  Correções de rastreabilidade e elos após inspeção | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [João Victor](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy) |
