# Matriz de Rastreabilidade

## Introdução

As matrizes de rastreabilidade são uma técnica comum e eficaz para representar e documentar as relações de rastreabilidade entre requisitos, bem como entre requisitos e artefatos anteriores e posteriores no processo de desenvolvimento de software. Essas matrizes fornecem uma visão clara das interdependências entre os diferentes elementos do projeto, permitindo que os stakeholders compreendam facilmente como cada requisito está relacionado a outros requisitos, casos de uso, testes, componentes do sistema e outros artefatos.

## Motivação e Objetivo

O objetivo deste artefato é, de uma maneira mais sucinta, relacionar e rastrear os requisitos entre si, permitindo a organização e o acompanhamento dos requisitos presentes nos documentos do Forward-from e do Backward-from.

## Metodologia
A metodologia começou com a criação do modelo da tabela que será utilizada como Matriz Geral e logo em seguida as responsáveis por esse artefato realizou uma leitura nos artefatos Forward-From e Backward-From para obter dados e inseri-los na tabela geral seguindo o modelo presente da **Tabela 1**. 
 
<center>

**Tabela 1** - Modelo da matriz geral.

| ID | Descrição | Artefatos relacionados (Origem) | Elicitação (Pré-Rastreabilidade) | Implementado | 
| -- | --------- | ------------------------------- | -------------------------------- | ------------ |
| número de identificação | a descrição do requisito | nome dos artefatos relacionados ao requisito | Códigos das elicitações relacionadas ao requisito da descrição | Se está implementado no aplicativo e-Título |

Fonte: Maria Barbosa, 2023.

</center>

## Matriz Geral
A Matriz Geral está presente na Tabela 2, demonstrando informações a respeito do que foi desenvolvido nos artefatos Forward-From e Backward-From, a legenda logo abaixo serve para ajudar na leitura da tabela. 

### Legendas:

* nº: número
* RFnº : Requisito funcional;
* RNFnº : Requisito não funcional;
* [QSTnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) : Requisito do Questionário;
* [STnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/) : Requisito do Storytelling;
* [ENTnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) : Requisito do Entrevista;
* [BSnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/) : Requisito do Brainstorming;
* [INTnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/)  : Requisito do Introspecção;
* [Enº](https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro) : Épico do Backlog;
* [Lnº](https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/)Requisito do Léxico;

<center>

**Tabela 2** - Matriz geral.

| ID | Descrição | Artefatos relacionados (Origem) | Elicitação (Pré-Rastreabilidade) | Implementado | 
| -- | --------- | ------------------------------- | -------------------------------- | ------------ |
| RF01 | No aplicativo deve ser possível realizar o cadastro do usuário com o uso de dados pessoais como senha, endereço, CPF e RG.  | Introspecção, Brainstorming e Entrevista  | [INT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [ENT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)  | Sim |
| RF02 | Deve ser possível o usuário cadastrar sua biometria durante o processo de cadastro.  | Introspecção |  [INT2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)   | Sim |
| RF03 | O usuário deve poder escolher a forma de realizar o login.  | Questionário | [QST02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) |   Sim |
| RF04 | O usuário deve conseguir fazer o login preenchendo os campos de entrada como senha e CPF para acessar o aplicativo caso já tenha se cadastrado.  | Introspecção, Questionario e Brainstorming | [INT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [QST04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) ,  [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |  Sim |
| RF05 | O usuário deve poder realizar o login com a biometria  | Questionario, Entrevista e Brainstorming | [QST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) ,  [ENT2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) ,  [BS2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md)|  Sim |
| RF06 | Deve ser possível o usuário vizualizar a localização da votação.  | Introspecção, Questionario e Storytelling | [INT4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [QST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [ST01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RF07 | Deve ser possível o usuário vizualizar seu documento do título eleiroral.  | Introspecção, Entrevista, Questionario e Storytelling | [INT5](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , [QST05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [ST03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) |  Sim |
| RF08 | Deve ser possível o usuário realizar o download do documento título eleitoral no aplicativo.  |  Introspecção | [INT9](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [ST02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) |  Sim |
| RF09 | O usuário deve conseguir visualizar as notificações do aplicativo, que alertam sobre datas ou informações importantes.  | Introspecção | [INT6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  |  Sim |
| RF10 | O aplicativo deve ter a opção de sair/logoff disponível para o usuário.  | Introspecção | [INT7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  |  Sim |
| RF11 | O usuário deve conseguir fazer alterações em seus dados cadastrais.  | Introspecção | [INT8](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  |  Sim |
| RF12 | No aplicativo deve ser possível o usuário realizar a recuperação da senha.  | Brainstorming | [BS10](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF13 | Deve ser possível o usuário visualizar as dúvidas frequentes do aplicativo  | Brainstorming | [BS12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |   Sim |
| RF14 | O aplicativo deve disponibilizar ao usuário a função de acessar o site do TSE para conseguir relatar feedbacks e problemas do aplicativo  | Brainstorming | [BS13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |  Sim |
| RF15 | No aplicativo deve ser possível o usuário vizualizar os termos de uso.  | Brainstorming | [BS7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |   Sim |
| RF16 | No aplicativo deve ser possível o usuário concordar ou não com os termos de uso.  | Brainstorming | [BS8](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |   Sim | 
| RF17 | Deve ser possível o usuário escolher o formato do arquivo, como pdf ou doc, a ser baixado do aplicativo.  | Introspecção | [INT10](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  |  Sim |
| RF18 | O usuário deve conseguir visualizar no aplicativo todos os dados presentes em um documento de título eleitoral.| Introspecção | [INT11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF19 | Deve ser possível o usuário vizualizar o endereço da localização do local para a votação no aplicativo.| Introspecção | [INT12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF20 |  Deve ser possível o usuário visualizar as rotas de sua localização atual até o seu local de votação pelo aplicativo. | Introspecção e Entrevista| [INT13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)  | Não |
| RF21 | O usuário deve conseguir escolher o local de partida.| Introspecção | [INT14](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Não |
| RF22 | O usuário deve conseguir escolher visualizar sobre as documentações nescessárias.| Introspecção  | [INT15](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RF23 | O usuário deve conseguir vizualizar os dados documentais.| Introspecção | [INT16](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Sim |
| RF24 | No aplicativo deve ser possível que o usuário realize a quitação eleitoral | Entrevista e Storytelling | [ENT04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , [ST05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md), [E07](https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro) e [L08](https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/) e [UC04](https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/casosdeuso/) | Não |
| RF25 | O usuário deve conseguir vizualizar as informações da quitação eleitoral.| Introspecção, Entrevista e Storytelling | [INT17](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [ENT05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) , [ST06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)  | Sim |
| RF26 | O usuário deve conseguir vizualizar dados referentes ao criminal eleitoral.| Introspecção | [INT18](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF27 | O usuário deve conseguir informar a sua justificativa no aplicativo.| Introspecção | [INT19](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Sim |
| RF28 | O usuário deve realizar download da comprovação de sua justificativa. | Introspecção | [INT20](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  | Não |
| RF29 | O usuário deve poder alterar seus dados pessoais, por meio do site do TSE. |Introspecção e Brainstorming| [INT21](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RF30 | Deve ser possível o usuário apagar seus dados pessoais.| Introspecção | [INT22](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)| Sim |
| RF31 | Deve ser possível o usuário ver o histórico de dados apagados.| Introspecção | [INT23](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)   | Não |
| RF32 | Deve ser possível o usuário acompanhar a apuração de votos | Entrevista | [ENT08](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md)| Não |
| RF33 | O usuário deve visualizar o candidato eleito referente ao ano da votação.| Entrevista | [ENT09](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RF34 | Eu como usuário, quero poder visualizar as notificação de datas e horários das eleições | Storytelling | [ST04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md)  | Sim |
| RNF01 | O aplicativo deve possuir um forúm para a retirada de dúvidas dos usuários. (suporte)  | Introspecção, Brainstorming e Entrevista| [INTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) ,  [BSNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [ENTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) |  Não |
| RNF02 | O aplicativo deve permitir que os usuários alterem a foto do documento do título eleitoral.  | Introspecção  | [INTNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |   Não |
| RNF03 | O aplicativo deve permitir que o usuário altere o local de partida.  | Introspecção | [INTNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF04 | O aplicativo deve notificar sobre atualizações eleitorais.  | Introspecção | [INTNF04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |  Sim |
| RNF05 | O aplicativo deve ter lembretes de votação e de mudanças de localização para votação.  | Introspecção, Questionario e Storytelling | [INTNF05](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [QSTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [STNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) |  Sim |
| RNF06 | O aplicativo deve contribuir para a transparência e informações sobre os candidatos sendo disponíveis para os usuários  | Introspecção e Brainstorming | [INTNF06](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BSNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |  Sim |
| RNF07 | O aplicativo deve manter sigilo nos dados do usuário a respeito de sua justificativa, permitindo a proteção dos dados, apenas os responsáveis o vê.  | Introspecção | [INTNF07](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |  Sim |
| RNF08 | O aplicativo deve permitir que o usuário receba a comprovação de seus débitos.  | Introspecção | [INTNF08](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |  Não |
| RNF09 | O aplicativo deve permitir a leitura do qr code do título eleitoral.  | Introspecção e Brainstorming | [INTNF10](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) , [BS04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) |  Sim |
| RNF10 | O aplicativo deve permitir que o usuário visualiza tutoriais a respeito de seus documentos.| Introspecção | [INTNF11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) | Não |
| RNF11 | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança.| Introspecção, Brainstorming, Questionário e Storytelling | [INTNF13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md)  [BSNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) , [QSTNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) , [STNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/storytelling.md) | Sim |
| RNF12 | Deve ser possível o aplicativo permitir que o usuário desloga a qualquer momento.| Introspecção | [INTNF15](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md) |  Sim |
| RNF13 | O aplicativo deve permitir apenas usuários acima de 16 anos, por serem aptos a votar | Brainstorming | [BSNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |
| RNF14 | O aplicativo deve notificar o horário da votação para o usuário| Entrevista | [ENT07](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Não |
| RNF15 | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo| Entrevista | [ENTNF01](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF16 |  O aplicativo deve possuir um design intuitivo com elementos como botão e menu padronizados | Entrevista | [ENTNF02](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF17 |  A navegação do aplicativo não deve ser poluída, como excesso de informações que podem confundir os usuários| Entrevista | [ENTNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF18 | Na navegação do aplicativo deve possuir linkagem com o site do TSE ou outros aplicativos externos, assim o aplicativo possui algumas funcionalidades não sendo pertencentes a ele, mas de fora dele | Entrevista | [ENTNF04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/entrevista.md) | Sim |
| RNF19 | O aplicativo deve possuir uma navegabilidade que não leve o usuário para fora do app | Questionário | [QSTNF03](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/feature-backward/docs/elicitacao/tecnicas/questionario.md) | Não |
| RNF20 | Para o aplicativo ser utilizado, o dispositivo que mantém ele instalado deve precisar ter acesso a internet. | Brainstorming | [E06](https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro) e [BSNF04](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md) | Sim |


Fonte: Maria Barbosa e Maria Marques, 2023.

</center>

## Bibliografia

> 2023.1-BilheteriaDigital. GitHub. Disponível em: https//requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/. Acesso em: 19 de novembro de 2023.

> SERRANO, Milene. Requisitos – Aula 26. Disponivél em: https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 19 de novembro de 2023.

> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://aprender3.unb.br/pluginfile.php/2692882/mod_resource/content/3/05_20_sayao.pdf. Acesso em: 19 de novembro de 2023.

## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `1.0`  | 19/11/2023  | adição da estrutura inicial  | [Maria Barbosa](https://github.com/Madu01) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) |
| `1.1`  | 19/11/2023  | adição do conteúdo de metodologia e a tabela no tópico matriz geral  | [Maria Barbosa](https://github.com/Madu01) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) |
| `1.2`  | 19/11/2023  | adição do conteúdo (de RF01 até RF17 e RNF01 até RNF09) na matriz geral   | [Maria Barbosa](https://github.com/Madu01) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) |
| `1.3`  | 19/11/2023  | Adição da introdução, objetivo e os requisitos RF18 até RF34 | [Maria Marques](https://github.com/EduardaSMarques) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) |
| `1.4`  | 19/11/2023  | Adição dos requisitos RNF10 até RNF20  | [Maria Marques](https://github.com/EduardaSMarques) | [Esther Sena](https://github.com/esmsena) e [Mariiana Siqueira](https://github.com/Maryyscreuza) |
