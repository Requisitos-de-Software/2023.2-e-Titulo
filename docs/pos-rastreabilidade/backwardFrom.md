# Backward From

## Introdução
Neste documento, exploraremos a abordagem "Backward From" na elicitação de requisitos, que nos leva do resultado desejado às raízes dos requisitos. Diferente das metodologias convencionais, essa técnica oferece uma compreensão mais profunda do contexto e das variáveis que influenciam os requisitos. Este artefato busca uma abordagem inovadora na engenharia reversa de requisitos, revelando as camadas subjacentes de necessidades para construir uma base sólida utilizando o método de rastreabilidade backward from descritos no Slide ["Requisitos-Aula 26"](https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da Miriam Sayão e Julio Cesar Sampaio do Prado Leite.

## Objetivo 
Este documento é um guia para usar a técnica "Backward From" na obtenção de requisitos. Vamos explorar como essa abordagem nos ajuda a entender melhor o que um sistema precisa, começando pelo resultado desejado e retrocedendo até as necessidades fundamentais. A ideia é oferecer uma ferramentas para aplicar essa técnica de engenharia reversa de requisitos de forma inovadora, ajudando no desenvolvimento de sistemas mais sólidos e claros. 

## Metodologia

A rastreabilidade transcende sua função na gestão de requisitos; ela emerge como um aliado crucial na busca pela excelência na GERÊNCIA DA QUALIDADE. O Meta-modelo proposto por Toranzo, habilmente, proporciona uma metodologia que simplifica a especificação do rastro, tornando o processo mais claro e eficiente.

Ao seguir o Meta-modelo de Toranzo para a elaboração do artefato, embarcamos em duas etapas fundamentais, delineadas nos slides 19 e 21 do arquivo "Requisitos-Aula 26" de Miriam Sayão e Julio Cesar Sampaio do Prado Leite.

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
* RF : Requisito funcional;
* RNF : Requisito não funcional;
* [QST](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) : Questionário;
* [ST](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) : Storytelling;
* [ENT](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) : Entrevista;
* [BS](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) : Brainstorming;
* [INT](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  : Introspecção;

### Requisitos funcionais:

Tabela 1: Requisitos funcionais 

| ID | Descrição | Origem | Implementado | 
| :--: | :--: | :--: | :--: |
| RF01 | No aplicativo deve ser possível realizar o cadastro do usuário com o uso de dados pessoais como senha, endereço, CPF e RG | [INT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [ENT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)  | Sim |
| RF02 | Deve ser possível o usuário cadastrar sua biometria durante o processo de cadastro. |  [INT2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RF03 | O usuário deve poder escolher a forma de realizar o login. | [QST02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) | Sim |
| RF04 | O usuário deve conseguir fazer o login preenchendo os campos de entrada como senha e CPF para acessar o aplicativo caso já tenha se cadastrado. | [INT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [QST04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) ,  [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF05 | O usuário deve poder realizar o login com a biometria | [QST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) ,  [ENT2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) ,  [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)| Sim |
| RF06 | Deve ser possível o usuário vizualizar a localização da votação. | [INT4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [QST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [ST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RF07 | Deve ser possível o usuário vizualizar seu documento do título eleiroral. | [INT5](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , [QST05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [ST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RF08 | Deve ser possível o usuário realizar o download do documento título eleitoral no aplicativo. | [INT9](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [ST02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RF09 | O usuário deve conseguir visualizar as notificações do aplicativo, que alertam sobre datas ou informações importantes. | [INT6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF10 | O aplicativo deve ter a opção de sair/logoff disponível para o usuário. | [INT7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF11 | O usuário deve conseguir fazer alterações em seus dados cadastrais. | [INT8](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF12 | No aplicativo deve ser possível o usuário realizar a recuperação da senha. | [BS10](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF13 | Deve ser possível o usuário visualizar as dúvidas frequentes do aplicativo | [BS12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF14 | O aplicativo deve disponibilizar ao usuário a função de acessar o site do TSE para conseguir relatar feedbacks e problemas do aplicativo | [BS13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF15 | No aplicativo deve ser possível o usuário vizualizar os termos de uso. | [BS7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF16 | No aplicativo deve ser possível o usuário concordar ou não com os termos de uso. | [BS8](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim | 
| RF17 | Deve ser possível o usuário escolher o formato do arquivo, como pdf ou doc, a ser baixado do aplicativo. | [INT10](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF18 | O usuário deve conseguir visualizar no aplicativo todos os dados presentes em um documento de título eleitoral. | [INT11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RF19 | Deve ser possível o usuário vizualizar o endereço da localização do local para a votação no aplicativo. | [INT12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF20 |  Deve ser possível o usuário visualizar as rotas de sua localização atual até o seu local de votação pelo aplicativo. | [INT13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RF21 | O usuário deve conseguir escolher o local de partida. | [INT14](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Não |
| RF22 | O usuário deve conseguir escolher visualizar sobre as documentações nescessárias. | [INT15](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RF23 | O usuário deve conseguir vizualizar os dados documentais. | [INT16](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RF24 | No aplicativo deve ser possível que o usuário realize a quitação eleitoral | [ENT04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , [ST05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)  | Não |
| RF25 | O usuário deve conseguir vizualizar as informações da quitação eleitoral. | [INT17](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , [ST06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)  | Sim |
| RF26 | O usuário deve conseguir vizualizar dados referentes ao criminal eleitoral. | [INT18](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF27 | O usuário deve conseguir informar a sua justificativa no aplicativo. | [INT19](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF28 | O usuário deve realizar download da comprovação de sua justificativa. | [INT20](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RF29 | O usuário deve poder alterar seus dados pessoais, por meio do site do TSE. | [INT21](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF30 | Deve ser possível o usuário apagar seus dados pessoais. | [INT22](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RF31 | Deve ser possível o usuário ver o histórico de dados apagados. | [INT23](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Não |
| RF32 | Deve ser possível o usuário acompanhar a apuração de votos | [ENT08](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RF33 | O usuário deve visualizar o candidato eleito referente ao ano da votação. | [ENT09](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RF34 | Eu como usuário, quero poder visualizar as notificação de datas e horários das eleições | [ST04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)  | Sim |
| RNF35 | O aplicativo deve notificar o horário da votação para o usuário | [ENT07](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |

(Fonte: Autores, 2023)

A tabela de rastreamento de requisitos não-funcionais, está apresentada de forma detalhada na Tabela 2 abaixo:

### Requisitos não funcionais:

Tabela 2: Requisitos não funcionais 

| ID | Descrição | Origem | Implementado |
| :--: | :--: | :--: | :--: |
| RNF01 | O aplicativo deve possuir um forúm para a retirada de dúvidas dos usuários. (suporte) | [INTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) ,  [BSNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [ENTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RNF02 | O aplicativo deve permitir que os usuários alterem a foto do documento do título eleitoral. | [INTNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF03 | O aplicativo deve permitir que o usuário altere o local de partida. | [INTNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF04 | O aplicativo deve notificar sobre atualizações eleitorais. | [INTNF04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RNF05 | O aplicativo deve ter lembretes de votação e de mudanças de localização para votação. | [INTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [QSTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [STNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RNF06 | O aplicativo deve contribuir para a transparência e informações sobre os candidatos sendo disponíveis para os usuários | [INTNF06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BSNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RNF07 | O aplicativo deve manter sigilo nos dados do usuário a respeito de sua justificativa, permitindo a proteção dos dados, apenas os responsáveis o vê. | [INTNF07](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RNF08 | O aplicativo deve permitir que o usuário receba a comprovação de seus débitos. | [INTNF08](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF09 | O aplicativo deve permitir a leitura do qr code do título eleitoral. | [INTNF10](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RNF10 | O aplicativo deve permitir que o usuário visualiza tutoriais a respeito de seus documentos.| [INTNF11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF11 | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança. | [INTNF13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  [BSNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [QSTNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [STNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RNF12 | Deve ser possível o aplicativo permitir que o usuário desloga a qualquer momento. | [INTNF15](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |  Sim |
| RNF13 | O aplicativo deve permitir apenas usuários acima de 16 anos, por serem aptos a votar | [BSNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RNF14 | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo | [ENTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF15 |  O aplicativo deve possuir um design intuitivo com elementos como botão e menu padronizados | [ENTNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF16 |  A navegação do aplicativo não deve ser poluída, como excesso de informações que podem confundir os usuários| [ENTNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF17 | Na navegação do aplicativo deve possuir linkagem com o site do TSE ou outros aplicativos externos, assim o aplicativo possui algumas funcionalidades não sendo pertencentes a ele, mas de fora dele | [ENTNF04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF17 | O aplicativo deve possuir uma navegabilidade que não leve o usuário para fora do app | [QSTNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) | Não |
| RNF18 | Para o aplicativo ser utilizado, o dispositivo que mantém ele instalado deve precisar ter acesso a internet. | [BSNF04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |

(Fonte: Autores, 2023)

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

(Fonte: Autores, 2023)

## Elos Funcionais

### EF01

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF01:
        * Introspecção: [INT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) 
        * Brainstorming: [BS1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
        * Entrevista: [ENT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) 
        
* Elos:
    * Agregacão: [INT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) agrega [BS1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
    * Agregação: [INT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) agrega [ENT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) 
    * Representação: [BS1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) representa [ENT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)
 
### EF02

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF04:
        * Introspecção: [INT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
        * Questionário: [QST04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md)
        * Brainstorming: [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) 
        
* Elos:
    * Representação: [INT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) representação [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
    * Agregação: [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) agrega [QST04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md)
    * Agregação: [INT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) agrega [QST04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md)

### EF03

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF05:
        * Entrevista: [ENT2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)
        * Questionário: [QST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) 
        * Brainstorming: [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
        
* Elos:
    * Representação: [QST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) representa [ENT2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) 
    * Agregação: [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) agrega [ENT2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)
    * Agregação: [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) agrega [QST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md)
      
### EF04

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF06:
        * Introspecção: [INT4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
        * Questionário: [QST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) 
        * Storytelling: [ST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
        
* Elos:
    * Representação: [INT4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) representa [QST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) 
    * Representação: [QST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) representa [ST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
    * Representação: [ST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) representa [INT4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)

### EF05

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF07:
        * Introspecção: [INT5](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
        * Entrevista: [ENT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)
        * Questionário: [QST05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) 
        * Storytelling: [ST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
        
* Elos:
    * Representação: [INT5](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) representa [ENT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) 
    * Representação: [ENT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) representa [QST05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) 
    * Representação: [QST05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) representa [ST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
    * Representação: [ST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) representa [INT5](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)

### EF06

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF08:
        * Introspecção: [INT09](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
        * Brainstorming: [BS03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
        * Storytelling: [ST02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
        
* Elos:
    * Representação: [INT09](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) representa [BS03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
    * Representação: [BS03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) representa [ST02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
    * Representação: [ST02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) representa [INT09](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)


 ### EF07

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF20:
        * Introspecção: [INT13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) 
        * Entrevista: [ENT06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) 
        
* Elos:
    * Recurso: [INT13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) recursa [ENT06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)
 

### EF08

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF24:
        * Entrevista: [ENT4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) 
        * Storytelling: [ST05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
           
* Elos:
     * Representação: [ENT4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) representa [ST05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
 
       
### EF09

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF25:
        * Introspecção: [INT17](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) 
        * Entrevista: [ENT05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) 
        * Storytelling: [ST06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
           

 * Elos:
    * Representação: [INT17](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) representa [ENT05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) 
    * Representação: [ENT05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) representa [ST06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
    * Representação: [ST06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) representa [INT17](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)

### EF10

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RF29:
        * Introspecção: [INT21](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
        * Brainstorming: [BS11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)       

 * Elos:
    * Agregação: [BS11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) agrega [INT21](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
      
## Elos não funcionais

### ENF01

* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RNF01: 
       * Introspecção: [INTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
       * Brainstorming: [BSNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
       * Entrevista: [ENTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) 
* Elos:  
    * Agregação: [INTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) agrega [BSNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
    * Agregação: [INTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) agrega [ENTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)
    * Representação: [BSNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) representa [ENTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)

### ENF02
 
* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RNF05: 
       * Introspecção: [INTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
       *  Questionário: [QSTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md)
       *  Storytelling: [STNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
* Elos:  
    * Agregação: [INTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) agrega [QSTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md)
    * Agregação: [INTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) agrega [STNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
    * Representação: [QSTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) representa [STNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)

 ### ENF03
 
* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RNF06: 
       * Introspecção: [INTNF06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
       * Brainstorming: [BSNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
* Elos: 
    * Representação: [INTNF06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) representa [BSNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)

 ### ENF04
 
* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RNF09: 
       * Introspecção: [INTNF10](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
       * Brainstorming: [BS04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
* Elos: 
    * Representação: [INTNF10](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) representa [BS04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)

### ENF05
 
* Nível: Desenvolvimento

* Elementos Rastreáveis: 
    * RNF11: 
       * Introspecção: [INTNF13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)
       * Brainstorming: [BSNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
       * Questionário: [QSTNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md)
       * Storytelling: [STNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)
* Elos:
    * Agregação: [INTNF13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) agrega [BSNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)
    * Representação: [BSNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) representa [QSTNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md)
    * Representação: [QSTNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) representa [STNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)  
  
## Referências

> LOPES, Pedro. RAISE - UM METAMODELO DE INFORMAÇÃO DE RASTREABILIDADE Backward From. Disponível em: <https://repositorio.ufmg.br/bitstream/1843/SLSS-8HTLX6/1/pedrolopesrochalealjr.pdf>. Acesso em: 15 Novembro. 2023.

> SERRANO, Milene e SERRANO, Maurício. Slide Requisitos. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>. Acesso em: 15 Novembro. 2023.

## Histórico de versão
| Versão | Data | Descrição | Autor | Revisor |
| :--: | :--: | :-------: | :---: | :-----: |
| `1.0`  | 15/11/2023 |  Criando estrutura do documento com formatação de tabelas, introdução, objetivo e metodologia. | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [João Victor](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy) |
| `1.1`  | 17/11/2023 |  Adicionando RF e RNF nas tabelas | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [João Victor](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy) |
| `1.2`  | 17/11/2023 |  Adicionando e preenchendo os Elos | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [João Victor](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy) |
