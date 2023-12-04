# Three Level Scale

## Introdução

É importante utilizar uma técnica de priorização para dar prioridade às tarefas mais importantes a serem implementadas. Será apresentado neste artefato a técnica do Three Level Scale (Escala de três níveis) e como vamos utilizá-lo no projeto.

## Motivação e Objetivo

A técnica Three-Level Scale em projetos de requisitos busca simplificar a identificação e classificação da importância dos requisitos. Isso é alcançado através de uma escala simples que permite a priorização eficaz, melhorando a comunicação entre as partes interessadas. Essa abordagem agiliza a tomada de decisões, otimizando o processo de seleção de requisitos e tornando as escolhas mais transparentes, baseadas em critérios claros e objetivos.

## Metodologia

Uma forma de avaliar a prioridade é considerar as duas dimensões de importância e urgência (Covey 2004)  <a id=anchor_1 href="#REF1">[1]</a>. Cada requisito pode ser considerado importante para atingir os objetivos de negócios ou não tão
importante, e como urgente ou não tão urgente. Esta é uma avaliação relativa entre um conjunto de requisitos e não uma distinção binária absoluta. Como mostra a Figura 1, essas alternativas produzem quatro combinações possíveis, que você pode usar para definir uma escala de prioridade:

Figura 1: Técnica Three Level Scale.

![Figura1](../imgs/tls1.png)

Fonte: Adaptado do livro do WIEGER. 

* Alta Prioridade: Os clientes precisam dele na próxima entrega.Se você puder esperar para implementar um requisito em uma entrega
posterior sem consequências adversas, então ele não será de alta prioridade de acordo com esta definição.
* Média Prioridade: Os clientes podem esperar até uma entrega posterior.
* Baixa Prioridade: Os clientes podem viver sem o requisito,eles podem esperar.
* Não faça isso: Os requisitos do quarto quadrante parecem ser urgentes para algumas partes interessadas, talvez por razões políticas, mas na verdade não são importantes para alcançar os objetivos de negócios. Não é necessário mexer com esse quadrante, pois eles não agregam valor suficiente ao produto.

Para chegarmos nesses resultados na Tabela 2,gravamos uma reunião na qual a [Maria Eduarda Marques](https://github.com/EduardaSMarques) foi a mediadora, a [Mariiana Siqueira](https://github.com/Maryyscreuza) foi auxiliar e nosso usuário foi Marcos Campos, para o preenchimento da tabela disponível neste documento, de onde foi transferido os dados da planilha para markdown. Na tabela 1 há o cronograma da gravação.

**Link para planilha:**

https://docs.google.com/spreadsheets/d/1JE-OPyLhUI5HI7It0TaMQFu_Ujwy_hqld4h1fgtusEM/edit#gid=0

Tabela 1 - Cronograma da gravação de TLS.

| Entrevistadores | Data | Horário | Entrevistado | Local |
| -------- | -------- | -------- | -------- | ----- |
| Maria Eduarda Marques e Mariiana Siqueira  | 03/12/2023 | 19:30 | Marcos Campos | Teams |

Fonte: SIQUEIRA, Mariiana. 2023.

## Resultados

A Tabela 2 contém a priorização dos requisitos elicitados utilizando a técnica Three Level Scale. Nem todos os requisitos estão presentes na tabela pois diferentes métodos elicitaram requisitos semelhantes. 

### Legenda:
* BS: Requisitos de [Brainstorming](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) 
* BSNF: Requisitos não-funcionais de [Brainstorming](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)
* ENT: Requisitos de [Entrevista](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
* ENTNF: Requisitos não-funcionais de [Entrevista](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/)
* INT: Requisitos de [Introspecção](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
* INTNF: Requisitos não-funcionais de [Introspecção](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)
* QSTNF: Requisitos não-funcionais de [Questionário](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/)
* ST: Requisitos de [Storytelling](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)

<p>Tabela 2: Priorização de requisitos utilizando a técnica TLS.</p>
  
| Rastreabilidade | Requisito | Prioridade |
| :-: | :-: | :-: |
| [BS1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | No aplicativo deve ser possível realizar o cadastro do usuário. | Alta |
| [INT2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Deve ser possível o usuário cadastrar sua biometria durante o processo de cadastro. | Média |
| [BS2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Deve ser possível o usuário realizar o login por senha ou biometria para acessar o aplicativo, com a condição de já ter se cadastrado. | Alta |
| [ST1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/)  | eu como usuário, quero poder visualizar a localização do local de votação | Alta |
| [INT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Deve ser possível o usuário vizualizar seu documento do título eleitoral. | Alta |
| [INT6](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O usuário deve conseguir visualizar as notificações do aplicativo, que alertam sobre datas ou informações importantes. | Alta |
| [INT7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve ter a opção de sair/logoff disponível para o usuário. | Alta |
| [INT8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O usuário deve conseguir fazer alterações em seus dados cadastrais. | Alta |
| [INT9](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Deve ser possível o usuário realizar o download do documento título eleitoral no aplicativo. | Alta |
| [INT10](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Deve ser possível o usuário escolher o formato do arquivo, como pdf ou doc, a ser baixado do aplicativo. | Alta |
| [INT11](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O usuário deve conseguir visualizar no aplicativo todos os dados presentes em um documento de título eleitoral. | Alta |
| [INT13](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Deve ser possível o usuário visualizar as rotas de sua localização atual até o seu local de votação pelo aplicativo. | Alta |
| [INT14](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O usuário deve conseguir escolher o local de partida. | Média |
| [INT15](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O usuário deve conseguir escolher visualizar sobre as documentações nescessárias.| Alta |
| [INT16](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O usuário deve conseguir vizualizar os dados documentais. | Alta |
| [ENT5](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | No aplicativo deve ser possível que o usuário visualize a sua situação da quitação eleitoral | Alta |
| [INT18](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O usuário deve conseguir vizualizar dados referentes ao criminal eleitoral. | Alta |
| [INT19](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) |  O usuário deve conseguir informar a sua justificativa no aplicativo. | Alta |
| [INT20](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O usuário deve realizar download da comprovação de sua justificativa. | Alta |
| [INT21](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O usuário deve poder alterar seus dados pessoais. | Alta |
| [INT22](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | Deve ser possível o usuário apagar seus dados pessoais. | Baixa |
| [INT23](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)| Deve ser possível o usuário ver o histórico de dados apagados. | Baixa |
| [INT24](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve permitir que os usuários alterem a foto do documento do título eleitoral. | Média |
| [INT26](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  | O aplicativo deve notificar sobre atualizações eleitorais. | Alta |
| [INT27](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  | O aplicativo deve demonstrar ao usuário os lembretes de votação e de mudanças de localização para votação. | Alta |
| [INT28](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve permitir que o usuário receba a comprovação de seus débitos. | Alta |
| [INT29](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  | O aplicativo deve mostrar ao usuário as autenticidades de seus documento. | Média  |
| [INT30](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve permitir a leitura do qr code do título eleitoral. | Média |
| [INT31](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve permitir que o usuário visualiza tutoriais a respeito de seus documentos. | Alta |
| [INT32](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve permitir que o usuário envie dúvidas. | Alta |
| [ENT7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | O aplicativo deve notificar o horário da votação para o usuário | Alta |
| [ENT8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Deve ser possível o usuário acompanhar a apuração de votos  | Baixa |
| [ENT9](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | O usuário deve visualizar o candidato eleito referente ao ano da votação. | Alta |
| [BS7](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)  | No aplicativo deve ser possível o usuário vizualizar os termos de uso | Alta |
| [BS8](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)  | No aplicativo deve ser possível o usuário concordar ou não com os termos de uso | Alta |
| [BS10](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | No aplicativo deve ser possível o usuário realizar a recuperação da senha | Alta |
| [BS12](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Deve ser possível o usuário visualizar as dúvidas frequentes do aplicativo | Alta | 
| [BS14](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/)  | O aplicativo deve oferecer um meio de ajuda para os usuários que não entenderam alguma coisa de sua utilidade | Alta |
| [BSNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | O aplicativo deve permitir apenas usuários acima de 16 anos, por serem aptos a votar | Alta |
| [BSNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) | Para o aplicativo ser utilizado, o dispositivo que mantém ele instalado deve precisar ter acesso a internet | Alta |
| [INTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve possuir um forúm para a retirada de dúvidas dos usuários. | Alta |
| [INTNF2](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve contribuir para a transparência e informações sobre os candidatos sendo disponíveis para os usuários | Alta |
| [INTNF3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve manter sigilo nos dados do usuário a respeito de sua justificativa, permitindo a proteção dos dados, apenas os responsáveis o vê. | Alta |
| [INTNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/) | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança. | Alta |
| [ENTNF3](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | A navegação do aplicativo não deve ser poluída, como excesso de informações que podem confundir os usuários | Alta |
| [ENTNF4](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) | Na navegação do aplicativo deve possuir linkagem com o site do TSE ou outros aplicativos externos, assim o aplicativo possui algumas funcionalidades não sendo pertencentes a ele, mas de fora dele | Baixa |
| [QSTNF1](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) | O aplicativo deve manter a atualização das informações do local da votação de cada usuário | Alta |

Fonte: [SIQUEIRA, Mariiana](https://github.com/Maryyscreuza) e [MARQUES, Maria Eduarda](https://github.com/EduardaSMarques). 2023.

## Gravação da técnica Three Level Scale

- Caso não consiga assistir dentro da gitPages, [Clique aqui](https://youtu.be/urmH87KvPnM)

<iframe width="560" height="315" src="https://youtu.be/urmH87KvPnM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<font size="3"><p style="text-align: center">Fonte: [SIQUEIRA, Mariiana](https://github.com/Maryyscreuza) e [MARQUES, Maria Eduarda](https://github.com/EduardaSMarques).</p></font>

## Bibliografia

> 2023.1-BilheteriaDigital, Three Level Scale. Disponível em : https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/priorizacao/threeLvlScale/. Acesso em: 04 de out 2023.

## Referência

> <a id="REF1" href="#anchor_1">[1]</a>  WIEGER, Karl E. First Things First: Prioritizing Requirements. Setembro de 1999. Disponível em https://www.processimpact.com/articles/prioritizing.pdf. Acesso em: 02 de out 2023.

## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `1.0`  | 02/10/2023  | Realização da introdução e motivações  | [Maria Marques ](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.1`  | 04/10/2023  | Finalizando o documento | [Maria Marques ](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.2`  | 17/10/2023  | correção | [Maria Marques ](https://github.com/EduardaSMarques) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.4`  | 17/10/2023  | correções pós inspeção, adicionando nova gravação e tabela em markdown | [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |


