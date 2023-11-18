# Backward From

## Introdução
Neste documento, exploraremos a abordagem "Backward From" na elicitação de requisitos, que nos leva do resultado desejado às raízes dos requisitos. Diferente das metodologias convencionais, essa técnica oferece uma compreensão mais profunda do contexto e das variáveis que influenciam os requisitos. Este artefato busca uma abordagem inovadora na engenharia reversa de requisitos, revelando as camadas subjacentes de necessidades para construir uma base sólida utilizando o método de rastreabilidade backward from descritos no Slide ["Requisitos-Aula 26"](https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf) da Miriam Sayão e Julio Cesar Sampaio do Prado Leite.

## Objetivo 
Este documento é um guia para usar a técnica "Backward From" na obtenção de requisitos. Vamos explorar como essa abordagem nos ajuda a entender melhor o que um sistema precisa, começando pelo resultado desejado e retrocedendo até as necessidades fundamentais. A ideia é oferecer uma ferramentas para aplicar essa técnica de engenharia reversa de requisitos de forma inovadora, ajudando no desenvolvimento de sistemas mais sólidos e claros. 

## Metodologia

A rastreabilidade transcende sua função na gestão de requisitos; ela emerge como um aliado crucial na busca pela excelência na GERÊNCIA DA QUALIDADE. O Meta-modelo proposto por Toranzo, habilmente, proporciona uma metodologia que simplifica a especificação do rastro, tornando o processo mais claro e eficiente.

Ao seguir o Meta-modelo de Toranzo para a elaboração do artefato, embarcamos em duas etapas fundamentais, delineadas nos slides 19 e 21 do inspirador arquivo "Requisitos-Aula 26" de Miriam Sayão e Julio Cesar Sampaio do Prado Leite.

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

Para colocar em prática a metodologia, inicialmente elaboramos duas tabelas distintas: uma dedicada aos requisitos funcionais ( Tabela 1) e outra para os requisitos não funcionais ( Tabela 2). Posteriormente, inserimos a fonte de origem desses requisitos nas tabelas, garantindo a rastreabilidade. Por último, empregando o Meta-modelo de Toranzo, delineamos as interconexões entre esses requisitos por meio dos Elos.

## Tabelas de requisitos

Este segmento tem como foco a criação da tabela de rastreamento de requisitos funcionais, a qual é apresentada de forma detalhada na Tabela 1 abaixo:

### Legendas:
* RF : Requisito funcional;
* RNF : Requisito não funcional;
* [QST](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) : Questionário;
* [ST](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) : Storytelling
* [ENT](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) : Entrevista;
* [BS](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) : Brainstorm;
* [INT](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  : Introspecção;

### Requisitos funcionais:

Tabela 1: Requisitos funcionais 

| ID | Descrição | Origem | Implementado | 
| :--: | :--: | :--: | :--: |
| RF01 | No aplicativo deve ser possível realizar o cadastro do usuário com o uso de dados pessoais como senha, endereço, CPF e RG | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , | Sim |
| RF02 | Deve ser possível o usuário cadastrar sua biometria durante o processo de cadastro. |  [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RF03 | O usuário deve poder escolher a forma de realizar o login. | [QST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) | Sim |
| RF04 | O usuário deve conseguir fazer o login preenchendo os campos de entrada como senha e CPF para acessar o aplicativo caso já tenha se cadastrado. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [QST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) | Sim |
| RF05 | O usuário deve poder realizar o login com a biometria | [QST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) | Sim |
| RF06 | Deve ser possível o usuário vizualizar a localização da votação. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [QST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [ST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RF07 | Deve ser possível o usuário vizualizar seu documento do título eleiroral. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , [QST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [ST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RF08 | Deve ser possível o usuário realizar o download do documento título eleitoral no aplicativo. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [ST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RF09 | O usuário deve conseguir visualizar as notificações do aplicativo, que alertam sobre datas ou informações importantes. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF10 | O aplicativo deve ter a opção de sair/logoff disponível para o usuário. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  |
| RF11 | O usuário deve conseguir fazer alterações em seus dados cadastrais. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF12 | No aplicativo deve ser possível o usuário realizar a recuperação da senha. | [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF13 | Deve ser possível o usuário visualizar as dúvidas frequentes do aplicativo | [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF14 | O aplicativo deve disponibilizar ao usuário a função de acessar o site do TSE para conseguir relatar feedbacks e problemas do aplicativo | [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF15 | No aplicativo deve ser possível o usuário vizualizar os termos de uso. | [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF16 | No aplicativo deve ser possível o usuário concordar ou não com os termos de uso. | [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim | 
| RF17 | Deve ser possível o usuário escolher o formato do arquivo, como pdf ou doc, a ser baixado do aplicativo. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF18 | O usuário deve conseguir visualizar no aplicativo todos os dados presentes em um documento de título eleitoral. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RF19 | Deve ser possível o usuário vizualizar o endereço da localização do local para a votação no aplicativo. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF20 |  Deve ser possível o usuário visualizar as rotas de sua localização atual até o seu local de votação pelo aplicativo. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RF21 | O usuário deve conseguir escolher o local de partida. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Não |
| RF22 | O usuário deve conseguir escolher visualizar sobre as documentações nescessárias. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RF23 | O usuário deve conseguir vizualizar os dados documentais. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RF24 | No aplicativo deve ser possível que o usuário realize a quitação eleitoral | [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , [ST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)  | Não |
| RF25 | O usuário deve conseguir vizualizar as informações da quitação eleitoral. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , [ST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)  | Sim |
| RF26 | O usuário deve conseguir vizualizar dados referentes ao criminal eleitoral. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF27 | O usuário deve conseguir informar a sua justificativa no aplicativo. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF28 | O usuário deve realizar download da comprovação de sua justificativa. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RF29 | O usuário deve poder alterar seus dados pessoais, por meio do site do TSE. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF30 | Deve ser possível o usuário apagar seus dados pessoais. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RF31 | Deve ser possível o usuário ver o histórico de dados apagados. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Não |
| RF32 | Deve ser possível o usuário acompanhar a apuração de votos | [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RF33 | O usuário deve visualizar o candidato eleito referente ao ano da votação. | [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RF34 | Eu como usuário, quero poder visualizar as notificação de datas e horários das eleições | [ST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)  | Sim |

(Fonte: Autores, 2023)

A tabela de rastreamento de requisitos não-funcionais, está apresentada de forma detalhada na Tabela 2 abaixo:

### Requisitos não funcionais:

Tabela 2: Requisitos não funcionais 

| ID | Descrição | Origem | Implementado |
| :--: | :--: | :--: | :--: |
| RNF01 | O aplicativo deve possuir um forúm para a retirada de dúvidas dos usuários. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) ,  [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RNF02 | O aplicativo deve permitir que os usuários alterem a foto do documento do título eleitoral. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF03 | O aplicativo deve permitir que o usuário altere o local de partida. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF04 | O aplicativo deve notificar sobre atualizações eleitorais. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RNF05 | O aplicativo deve ter lembretes de votação e de mudanças de localização para votação. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [QST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [ST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RNF06 | O aplicativo deve contribuir para a transparência e informações sobre os candidatos sendo disponíveis para os usuários | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RNF07 | O aplicativo deve manter sigilo nos dados do usuário a respeito de sua justificativa, permitindo a proteção dos dados, apenas os responsáveis o vê. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RNF08 | O aplicativo deve permitir que o usuário receba a comprovação de seus débitos. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF09 | O aplicativo deve permitir a leitura do qr code do título eleitoral. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RNF10 | O aplicativo deve permitir que o usuário visualiza tutoriais a respeito de seus documentos.| [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF11 | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [QST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [ST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RNF12 | Deve ser possível o aplicativo permitir que o usuário desloga a qualquer momento. | [INT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |  Sim |
| RNF13 | O aplicativo deve permitir apenas usuários acima de 16 anos, por serem aptos a votar | [BS](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RNF14 | O aplicativo deve notificar o horário da votação para o usuário | [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RNF15 | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo | [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF16 |  O aplicativo deve possuir um design intuitivo com elementos como botão e menu padronizados | [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF17 |  A navegação do aplicativo não deve ser poluída, como excesso de informações que podem confundir os usuários| [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF18 | Na navegação do aplicativo deve possuir linkagem com o site do TSE ou outros aplicativos externos, assim o aplicativo possui algumas funcionalidades não sendo pertencentes a ele, mas de fora dele | [ENT](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF18 | O aplicativo deve possuir uma navegabilidade que não leve o usuário para fora do app | [QST](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) | Não |

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

### EFXX

* Categoria: xx

* Elementos Rastreáveis: 
    * RFxx:
        * xx: xx
        * xx: xx
* Elos:
    * Agregacão: xx agrega xx
    * Representação: XX representa XX


## Elos não funcionais

### ENF01

* Categoria: xx

* Elementos Rastreáveis: 
    * RNFxx: 
        * xx: xx
* Elos:  
    * xx: xx agrega xx

## Referências

  > LOPES, Pedro, RAISE - UM METAMODELO DE INFORMAÇÃO DE RASTREABILIDADEBackward From - Disponível em: <https://repositorio.ufmg.br/bitstream/1843/SLSS-8HTLX6/1/pedrolopesrochalealjr.pdf>. Acesso em: 15 Novembro. 2023.
  > Slide, Requisitos, professora Milene e Maurício Serrano - Disponível em: <https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf>  Acesso em: 15 Novembro. 2023.

## Histórico de versão
| Versão | Data | Descrição | Autor | Revisor |
| :--: | :--: | :-------: | :---: | :-----: |
| `1.0`  | 15/11/2023 |  Criando estrutura do documento com formatação de tabelas, introdução, objetivo e metodologia. | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [João Victor](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy) |
| `1.1`  | 17/11/2023 |  Adicionando RF e RNF nas tabelas | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [João Victor](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy) |
