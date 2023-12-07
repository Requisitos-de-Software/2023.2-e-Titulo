# Léxico

## Introdução
Léxico é um modelo de requisitos e busca descrever os símbolos de uma linguagem em que cada símbolo é representado por noção(denotação) e impacto(Conotação). Um símbolo é uma palavra ou uma frase. A noção é sobre o que significa o símbolo e o impacto é sobre o efeito do símbolo no sistema ou da consequência de alguma coisa no sistema sobre o símbolo. As regras gerais deste modelo são: 

- Para cada símbolo é contido zero ou mais sinônimos.

- Para cada símbolo tem uma ou mais noções. 

- Em cada símbolo contém um ou mais impactos.

Existe também as regras por tipo os quais são: Objeto, verbo e estado. Para uma melhor explicação dessa regra observe a Tabela 1. Esse modelo ajuda a identificar, a analisar, compreender e classificar os termos e palavras-chave usados na documentação de requisitos, agregando para uma comunicação mais eficaz entre as partes envolvidas no desenvolvimento de software.

## Motivação e Objetivo

A principais motivações e objetivos que levaram a equipe a utilizar léxico é devido que p léxico é uma ferramenta crucial para promover a clareza, a precisão e a compreensão mútua em projetos de desenvolvimento de software. Ao utilizar um vocabulário padronizado e bem definido, as organizações podem melhorar a qualidade do software, reduzir riscos e garantir que o produto final atenda às expectativas dos clientes e das partes interessadas.

## Metodologia

A metodologia consiste primeiro em definir quais são os símbolos, em seguida seguir as regras gerais e as regras por tipo para cada símbolo definido preenchendo as informações em tabelas. Os símbolos definidos foram: 
Usuário, Aparelho, Entrar, Visualizar documento, Visualizar local, Notificação, Ajuda, Emitir certificado, Aplicativo está aberto e Desbloqueio com biometria está ativado.

A explicação da regra por tipo está na tabela 1, conforme a regra geral. Para cada tabela de um símbolo seguira as informações da tabela 1.

#### identificador do léxico:

O identificador do léxico tem a estrutura **Lxx** no qual os x são números.

<center>

**Tabela 1** - Explicação da regra por tipo com a regra geral.

| **tipo** <br> (sujeito) | **Noção** <br> (quem é o sujeito?) | **Impacto** <br> (quais ações executa?) |
| -------- | --------- | ----------- |
| VERBO | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos da ação no ambiente e quais os novos estados decorrentes |
| OBJETO | Definir o objeto e identificar outros objetos com os quais se relaciona | Ações que podem ser aplicadas ao objeto |
| ESTADO | O que significa e quais ações levaram a esse estado | Identificar outros estados e ações que podem ocorrer a partir do estado que se descreve |

Fonte: SERRANO Milene; SERRANO Maurício.

</center>

<center>

**Tabela 2** - Modelo de tabela para os léxicos

| **identificador do léxico** | **descrição** |
| --------------------------- | ------------- |
| Noção | São as noções do léxico conforme o tipo ( VERBO/OBJETO/ESTADO ) presente na tabela 1 |
| Classificação | é o tipo usado no símbolo ( VERBO/OBJETO/ESTADO ) |
| Impacto(s) | São os impactos do léxico conforme o tipo ( VERBO/OBJETO/ESTADO ) presente na tabela 1 |
| Sinônimo(s) | são os sinônimos do símbolo |

Fonte: BARBOSA, Maria. 2023.

</center>

## Léxicos definidos

### L01: Usuário <a id=anchor_11 href="#REF1"></a>

No primeiro léxico, que está na tabela 3, a funcionalidade utilizada é o usuário precisa ter acima de 16 anos (<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BSNF1</a>), estando essa funcionalidade implementada no aplicativo.

#### Funcionalidades

Para acessar todas as funcionalidades presentes podem serem acessadas na pasta de [técnicas](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/tree/main/docs/elicitacao/tecnicas).

<center>

**Tabela 3** - exemplo

| **L01** | **descrição** |
| --------------------------- | ------------- |
| Noção | A pessoa que fará uso do aplicativo. <br> Possui mais de 16 anos(<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BSNF1</a>). |
| Classificação | Objeto |
| Impacto(s) |Se encaixa no critério de ter mais de 16 anos (<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BSNF1</a>). <br> O usuário possui acesso  as [funcionalidades](#funcionalidades) do aplicativo. |
| Sinônimo(s) | Cliente e consumidor. |

Fonte: MARQUES, Maria. 2023.

</center>

### L02: Dispositivo

Neste segundo léxico, presente na tabela 4, apresenta a funcionalidade o dispositivo que mantém ele instalado deve precisar ter acesso a internet(<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BSNF4</a>), a funcionalidade está implementada no aplicativo.

Tabela 4 - exemplo

| **L02** | **descrição** |
| --------------------------- | ------------- |
| Noção | O dispositivo se conecta à internet(<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BSNF4</a>).  |
| Classificação | Objeto |
| Impacto(s) | O <a id="REF1" href="#anchor_11">usuário</a> instala o aplicativo. <br> O usuário consegue ter acesso as [funcionalidades](#funcionalidades) do aplicativo. |
| Sinônimo(s) | Aparelho e equipamento. |

Fonte: MARQUES, Maria. 2023.

### L03: Cadastrar 

Já neste léxico, na tabela 5, as funcionalidades usadas foram  realizar o cadastro do usuário com o uso de dados pessoais como senha, endereço, CPF e RG(<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT1</a>) e usuário cadastrar sua biometria durante o processo de cadastro([INT2](<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT2</a>)),ambas as funcionalidades foram implementadas.

Tabela 5 - exemplo

| **L03** | **descrição** |
| --------------------------- | ------------- |
| Noção | Ocorre no primeiro acesso do <a id="REF1" href="#anchor_11">usuário</a> com aplicativo. <br> O <a id="REF1" href="#anchor_11">usuário</a> informa seus dados pessoais quando se cadastra(<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT1</a>). <br> O <a id="REF1" href="#anchor_11">usuário</a> cadastra sua biometria ao se cadatrar(<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT2</a>).  |
| Classificação | Verbo |
| Impacto(s) | O <a id="REF1" href="#anchor_11">usuário</a> tem acesso as funcionalidades do aplicativo. <br> O <a id="REF1" href="#anchor_11">usuário</a> armazena suas informações no aplicativo. <br> O <a id="REF1" href="#anchor_11">usuário</a> tem um acesso mais rápido as funcionalidades do sistema com a biometria. |
| Sinônimo(s) | Registrar e inscrever.|

Fonte: MARQUES, Maria. 2023.

### L04: Visualizar documento

O quarto léxico, presente na tabela 6, mostra as funcionalidades  visualizar no aplicativo todos os dados presentes em um documento de título eleitoral, escolher visualizar sobre as documentações nescessárias e conseguir vizualizar os dados documentais, sendo seus id's <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT11</a>, <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT15</a> e <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT16</a> respectivamente. Essas funcionalidades foram implementadas no aplicativo.

Tabela  6 - exemplo

| **L04** | **descrição** |
| --------------------------- | ------------- |
| Noção | O <a id="REF1" href="#anchor_11">usuário</a> consegue visualizar as funcionalidades <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT11</a>, <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT15</a> e <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT16</a> ao fazer login no aplicativo.|
| Classificação | Verbo |
| Impacto(s) | O <a id="REF1" href="#anchor_11">usuário</a> consegue ver os dados de seu interesse no documento. |
| Sinônimo(s) | Ver, observar, contemplar, constatar e verificar. |

Fonte: MARQUES, Maria. 2023.

### L05: Visualizar local

No léxico 5, presente na tabela 7, as funcionalidades mostradas foram, deve ser possível o usuário vizualizar a localização do Local de Votação( <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS6</a>) e deve ser possível o usuário visualizar as rotas de sua localização atual até o seu local de votação pelo aplicativo( <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT13</a>), apenas a primeira funcionalidade citada foi implementada.

Tabela 7 - exemplo

| **L05** | **descrição** |
| --------------------------- | ------------- |
| Noção | O <a id="REF1" href="#anchor_11">usuário</a> consegue visualizar o local da votação quando acessa a funcionalidade no aplicativo( <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS6</a>). <br> O <a id="REF1" href="#anchor_11">usuário</a> consegue traçar uma rota do seu local atual até o local da realizaçao da votação( <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT13</a>). |
| Classificação | Verbo |
| Impacto(s) | O <a id="REF1" href="#anchor_11">usuário</a> visualiza local da votação. <br> O <a id="REF1" href="#anchor_11">usuário</a> encontra a melhor rota para chegar ao local. |
| Sinônimo(s) | Ver, observar, contemplar, constatar e verificar. |

Fonte: MARQUES, Maria. 2023.

### L06: Notificação

Neste léxico presente na Tabela 8 as funcionalidades apresentadas são o aplicativo notifica o horário da votação para o usuário, o usuário deve conseguir visualizar as notificações do aplicativo, que alertam sobre datas ou informações importantes, e no aplicativo deve ser possível o usuário receber notificações ( <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT7</a>, <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT6</a> e <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS6</a> ), sendo que o primeiro não foi implementado no aplicativo e o restante sim. 

<center>

**Tabela 8** - exemplo

| **L06** | **descrição** |
| --------------------------- | ------------- |
| Noção | O <a id="REF1" href="#anchor_11">usuário</a> recebe a notificação quando o aplicativo carrega os dados de informações importantes como data da votação <br> O <a id="REF1" href="#anchor_11">usuário</a> seleciona as funcionalidades <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT7</a>, <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT6</a> e <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS6</a> para poder visualizar as notificações  |
| Classificação | Verbo |
| Impacto(s) | As funcionalidades <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT7</a>, <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT6</a> e <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS6</a> são utilizadas |
| Sinônimo(s) | Comunicar, informar e transmitir |

Fonte: BARBOSA, Maria. 2023.

</center>

### L07: Ajuda

O sétimo léxico(tabela 9) utiliza as funcionalidades de visualizar dúvidas frequentes e o termo de uso com explicações sobre a sua utilidade ( <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS12</a> e <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENTNF1</a> ). Nas dúvidas frequentes foi implementado e no termo de uso não foi. 

<center>

**Tabela 9** - exemplo

| **L07** | **descrição** |
| --------------------------- | ------------- |
| Noção | O aplicativo oferece a ajuda para o <a id="REF1" href="#anchor_11">usuário</a> quando o <a id="REF1" href="#anchor_11">usuário</a> seleciona a funcionalidade <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS12</a> ou a <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENTNF1</a> <br> A funcionalidade <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENTNF1</a> é acessada pelo <a id="REF1" href="#anchor_11">usuário</a> quando a funcionalidade <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS12</a> não está selecionada <br> É acessado pelo <a id="REF1" href="#anchor_11">usuário</a> a funcionalidade <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS12</a> e a <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENTNF1</a>  não estará selecionada |
| Classificação | Verbo |
| Impacto(s) | O <a id="REF1" href="#anchor_11">usuário</a> visualiza as perguntas e respostas disponíveis no aplicativo quando acessar a funcionalidade <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS12</a> <br> O <a id="REF1" href="#anchor_11">usuário</a> visualiza termo de uso presente no aplicativo quando acessar a funcionalidade <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENTNF1</a> |
| Sinônimo(s) |  Amparo e auxílio |

Fonte: BARBOSA, Maria. 2023.

</center>

### L08: Emitir certificado

A funcionalidade usada nesse léxico presente na Tabela 10 é  vizualizar as informações da quitação eleitoral ( <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT17</a> ) em que está implementado no aplicativo.

<center>

**Tabela 10** - exemplo

| **L08** | **descrição** |
| --------------------------- | ------------- |
| Noção | O <a id="REF1" href="#anchor_11">usuário</a> emite o cetificado quando acessa a funcionalidade <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT17</a> <br> O <a id="REF1" href="#anchor_11">usuário</a> vai para o menu inferior e seleciona a função <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT17</a> |
| Classificação | Verbo |
| Impacto(s) | O <a id="REF1" href="#anchor_11">usuário</a> visualiza o documento emitido pela função []() |
| Sinônimo(s) | Enviar, lançar, quitamento e remitir |

Fonte: BARBOSA, Maria. 2023.

</center>

### L09: Aplicativo está aberto

No léxico L09 presente na Tabela 11 as funcionalidades utilizadas são o usuário realizar login e o sair/logoff ( <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT3</a> e <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT7</a> ), ambos são implementados.


#### Funcionalidades

Para acessar todas as funcionalidades presentes podem serem acessadas na pasta de [técnicas](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/tree/main/docs/elicitacao/tecnicas).

<center>

**Tabela 11** - exemplo

| **L09** | **descrição** |
| --------------------------- | ------------- |
| Noção | O aplicativo encontra-se em uso por um <a id="REF1" href="#anchor_11">usuário</a> Acontece quando o <a id="REF1" href="#anchor_11">usuário</a> faz um login bem sucedido no aplicativo |
| Classificação | Estado |
| Impacto(s) | Quando o <a id="REF1" href="#anchor_11">usuário</a> entra no aplicativo por meio do <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT3</a> todas as [funcionalidades](#funcionalidades) presentes podem ser acessadas: ESTADO - Funcionalidades estão disponíveis <br> Quando o <a id="REF1" href="#anchor_11">usuário</a> sai do aplicativo realizando a funcionalidade <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT7</a>: ESTADO - Apricativo está desligado  e funcionalidades não disponíveis |
| Sinônimo(s) | Acesso e desconexão |

Fonte: BARBOSA, Maria. 2023.

</center>

### L10: Desbloqueio com biometria está ativado

Nesse léxico presente na Tabela 12 a funcionalidade em uso que é implementada no aplicativo é a realização do login com a biometria ( <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/">QST3</a> ).

<center>

**Tabela 12** - exemplo

| **L10** | **descrição** |
| --------------------------- | ------------- |
| Noção | O desbloqueio com biometria encontra-se em uso por um <a id="REF1" href="#anchor_11">usuário</a> <br> Ocorre quando o <a id="REF1" href="#anchor_11">usuário</a> seleciona a opção de ativar biometria, exercendo a função <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/">QST3</a> |
| Classificação | Estado |
| Impacto(s) | Quando o <a id="REF1" href="#anchor_11">usuário</a> desativa a opção de realizar desbloqueio por biometria no aplicativo: ESTADO - Biometria desativada <br>  |
| Sinônimo(s) | Liberado e despertar |

Fonte: BARBOSA, Maria. 2023.

</center>

## Bibliografia

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

> SERRANO M.; SERRANO M. Requisitos - Aula 10. Aprender 3. Disponível em: https://aprender3.unb.br/pluginfile.php/2692795/mod_resource/content/1/Aula%2010.pdf. Acesso em: 18 de outubro de 2023.

> 2022.2-MEI. GitHub. Disponível em: https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/. Acesso em: 18 de outubro de 2023.



## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `1.0`  | 17/10/2023  |  Criação da estrutura do artefato e tabela exemplo | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `1.1`  | 18/10/2023  |  Criação do conteúdo do tópico introdução | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `1.2`  | 18/10/2023  |  Criação do conteúdo do tópico metodologia e adicionando tabelas em léxicos definidos | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `1.3`  | 18/10/2023  |  Adicionando conteúdo nas tabelas dos léxicos L06 até L10 | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `1.4`  | 19/10/2023  |  Adicionando conteúdo de contexto nos léxicos L06 até L10 com hyperlinks | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `1.5` | 20/10/2023  |  Adicionando conteúdo da motivação e objetivo | [Maria Marques ](https://github.com/EduardaSMarques) | [João Victor](https://github.com/jvcostta) |
| `1.6` | 20/10/2023  |  Adicionando léxico L01 à L05 | [Maria Marques ](https://github.com/EduardaSMarques) | [João Victor](https://github.com/jvcostta) |
| `1.7` | 21/10/2023  | Chamando tabelas no texto| [Maria Marques ](https://github.com/EduardaSMarques) | [João Victor](https://github.com/jvcostta) |
| `1.8`  | 01/12/2023  |  Correção no histórico de versão, ABNT nas tabelas e linkagens dos léxicos L06 até L10| [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `1.9` | 03/12/2023  | Correção nas linkagens dos léxicos L01 até L05| [Maria Marques ](https://github.com/EduardaSMarques) | [João Victor](https://github.com/jvcostta) |

