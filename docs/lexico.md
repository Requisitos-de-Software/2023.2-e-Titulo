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

Tabela 1 - Explicação da regra por tipo com a regra geral.

| **tipo** <br> (sujeito) | **Noção** <br> (quem é o sujeito?) | **Impacto** <br> (quais ações executa?) |
| -------- | --------- | ----------- |
| VERBO | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos da ação no ambiente e quais os novos estados decorrentes |
| OBJETO | Definir o objeto e identificar outros objetos com os quais se relaciona | Ações que podem ser aplicadas ao objeto |
| ESTADO | O que significa e quais ações levaram a esse estado | Identificar outros estados e ações que podem ocorrer a partir do estado que se descreve |

Fonte: SERRANO Milene e SERRANO Maurício.

Tabela 2 - Modelo de tabela para os léxicos

| **identificador do léxico** | **descrição** |
| --------------------------- | ------------- |
| Noção | São as noções do léxico conforme o tipo ( VERBO/OBJETO/ESTADO ) presente na tabela 1 |
| Classificação | é o tipo usado no símbolo ( VERBO/OBJETO/ESTADO ) |
| Impacto(s) | São os impactos do léxico conforme o tipo ( VERBO/OBJETO/ESTADO ) presente na tabela 1 |
| Sinônimo(s) | são os sinônimos do símbolo |

Fonte: Maria eduarda Barbosa, 2023.

## Léxicos definidos

###  L01: Usuário

No primeiro léxico(tabela 3), a funcionalidade utilizada é o usuário precisa ter acima de 16 anos ([BSNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados)), estando essa funcionalidade implementada no aplicativo.

#### Funcionalidades

Para acessar todas as funcionalidades presentes podem serem acessadas na pasta de [técnicas](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/tree/main/docs/elicitacao/tecnicas).

Tabela 3 - exemplo

| **L01** | **descrição** |
| --------------------------- | ------------- |
| Noção | A pessoa que fará uso do aplicativo. <br> Possui mais de 16 anos([BSNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados)). |
| Classificação | Objeto |
| Impacto(s) |Se encaixa no critério de ter mais de 16 anos ([BSNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados)). <br> O usuário possui acesso  as [funcionalidades](#funcionalidades) do aplicativo. |
| Sinônimo(s) | Cliente e consumidor. |

Fonte: Maria eduarda Marques, 2023.

### L02: Dispositivo

Neste segundo léxico(Tabela 04), apresenta a funcionalidade o dispositivo que mantém ele instalado deve precisar ter acesso a internet([BSNF4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados)), a funcionalidade está implementada no aplicativo.

Tabela 4 - exemplo

| **L02** | **descrição** |
| --------------------------- | ------------- |
| Noção | O dispositivo se conecta à internet([BSNF4](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados)).  |
| Classificação | Objeto |
| Impacto(s) | O [usuário](#usuário) instala o aplicativo. <br> O usuário consegue ter acesso as [funcionalidades](#funcionalidades) do aplicativo. |
| Sinônimo(s) | Aparelho e equipamento. |

Fonte: Maria eduarda Marques, 2023.

### L03: Cadastrar 

Já neste léxico(tabela 5) as funcionalidades usadas foram  realizar o cadastro do usuário com o uso de dados pessoais como senha, endereço, CPF e RG([INT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados)) e usuário cadastrar sua biometria durante o processo de cadastro([INT2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados)),ambas as funcionalidades foram implementadas.

Tabela 5 - exemplo

| **L03** | **descrição** |
| --------------------------- | ------------- |
| Noção | Ocorre no primeiro acesso do usuário com aplicativo. <br> O usuário informa seus dados pessoais quando se cadastra([INT1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados)). <br> O usuário cadastra sua biometria ao se cadatrar([INT2](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados)).  |
| Classificação | Verbo |
| Impacto(s) | O usuário tem acesso as funcionalidades do aplicativo. <br> O usuário armazena suas informações no aplicativo. <br> O usuário tem um acesso mais rápido as funcionalidades do sistema com a biometria. |
| Sinônimo(s) | Registrar e inscrever.|

Fonte: Maria eduarda Marques, 2023.

### L04: Visualizar documento

O quarto léxico(tabela 6), mostra as funcionalidades  visualizar no aplicativo todos os dados presentes em um documento de título eleitoral, escolher visualizar sobre as documentações nescessárias e conseguir vizualizar os dados documentais, sendo seus id's [INT11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados), [INT15](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) e [INT16](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) respectivamente. Essas funcionalidades foram implementadas no aplicativo.

Tabela  6 - exemplo

| **L04** | **descrição** |
| --------------------------- | ------------- |
| Noção | O usuário consegue visualizar as funcionalidades [INT11](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados), [INT15](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) e [INT16](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) ao fazer login no aplicativo.|
| Classificação | Verbo |
| Impacto(s) | O usuário consegue ver os dados de seu interesse no documento. |
| Sinônimo(s) | Ver, observar, contemplar, constatar e verificar. |

Fonte: Maria eduarda Marques, 2023.

### L05: Visualizar local

No léxico 5(tabela 7), as funcionalidades mostradas foram, deve ser possível o usuário vizualizar a localização do Local de Votação([BS6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados)) e deve ser possível o usuário visualizar as rotas de sua localização atual até o seu local de votação pelo aplicativo([INT13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados)), apenas a primeira funcionalidade citada foi implementada.

Tabela 7 - exemplo

| **L05** | **descrição** |
| --------------------------- | ------------- |
| Noção | O usuário consegue visualizar o local da votação quando acessa a funcionalidade no aplicativo([BS6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados)). <br> O usuário consegue traçar uma rota do seu local atual até o local da realizaçao da votação([INT13](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados)). |
| Classificação | Verbo |
| Impacto(s) | O usuário visualiza local da votação. <br> O usuário encontra a melhor rota para chegar ao local. |
| Sinônimo(s) | Ver, observar, contemplar, constatar e verificar. |

Fonte: Maria eduarda Marques, 2023.

### L06: Notificação

Neste léxico as funcionalidades apresentados são o aplicativo notifica o horário da votação para o usuário, o usuario visualiza a notificação e deve ser possível o usuário receber a notificação ( [ENT7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md#requisitos-elicitados), [INT6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) e [BS6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados) ), sendo que o primeiro não foi implementado no aplicativo e o restante sim. 

Tabela 8 - exemplo

| **L06** | **descrição** |
| --------------------------- | ------------- |
| Noção | O [usuário](#l01:-usuario) recebe a notificação quando o aplicativo carrega os dados de informações importantes como data da votação <br> O [usuário](#l01:-usuario) seleciona as funcionalidades [ENT7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md#requisitos-elicitados), [INT6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) e [BS6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados) para poder visualizar as notificações  |
| Classificação | Verbo |
| Impacto(s) | As funcionalidades [ENT7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md#requisitos-elicitados), [INT6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) e [BS6](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados) são utilizadas |
| Sinônimo(s) | Comunicar, informar e transmitir |

Fonte: Maria eduarda Barbosa, 2023.

### L07: Ajuda

O sétimo léxico utiliza as funcionalidades de visualizar dúvidas frequentes e o termo de uso com explicações sobre a utilidade do aplicativo ( [BS12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados) e [ENTNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md#requisitos-elicitados) ). Nas dúvidas frequentes foi implementado e no termo de uso não foi. 

Tabela 9 - exemplo

| **L07** | **descrição** |
| --------------------------- | ------------- |
| Noção | O aplicativo oferece a ajuda para o [usuário](#l01:-usuario) quando o [usuário](#l01:-usuario) seleciona a funcionalidade [BS12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados) ou a [ENTNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md#requisitos-elicitados) <br> A funcionalidade [ENTNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md#requisitos-elicitados) é acessada pelo [usuário](#l01:-usuario) quando a funcionalidade [BS12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados) não está selecionada <br> É acessado pelo [usuário](#l01:-usuario) a funcionalidade [BS12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados) e a [ENTNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md#requisitos-elicitados)  não estará selecionada |
| Classificação | Verbo |
| Impacto(s) | O [usuário](#l01:-usuario) visualiza as perguntas e respostas disponíveis no aplicativo quando acessar a funcionalidade [BS12](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/brainstorming.md#requisitos-elicitados) <br> O [usuário](#l01:-usuario) visualiza termo de uso presente no aplicativo quando acessar a funcionalidade [ENTNF1](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/entrevista.md#requisitos-elicitados) |
| Sinônimo(s) |  Amparo e auxílio |

Fonte: Maria eduarda Barbosa, 2023.

### L08: Emitir certificado

A funcionalidade usada nesse léxico é  vizualizar as informações da quitação eleitoral ( [INT17](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) ) em que está implementado no aplicativo.

Tabela 10 - exemplo

| **L08** | **descrição** |
| --------------------------- | ------------- |
| Noção | O [usuário](#l01:-usuario) emite o cetificado quando acessa a funcionalidade [INT17](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) <br> O [usuário](#l01:-usuario) vai para o menu inferior e seleciona a função [INT17](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) |
| Classificação | Verbo |
| Impacto(s) | O [usuário](#l01:-usuario) visualiza o documento emitido pela função []() |
| Sinônimo(s) | Enviar, lançar, quitamento e remitir |

Fonte: Maria eduarda Barbosa, 2023.

### L09: Aplicativo está aberto

No léxico L09 as funcionalidades utilizadas são o usuário realizar login e o sair/logoff ( [INT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) e [INT7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) ), ambos são implementados.

#### Funcionalidades

Para acessar todas as funcionalidades presentes podem serem acessadas na pasta de [técnicas](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/tree/main/docs/elicitacao/tecnicas).

Tabela 11 - exemplo

| **L09** | **descrição** |
| --------------------------- | ------------- |
| Noção | O aplicativo encontra-se em uso por um [usuário](#l01:-usuario) Acontece quando o [usuário](#l01:-usuario) faz um login bem sucedido no aplicativo |
| Classificação | Estado |
| Impacto(s) | Quando o [usuário](#l01:-usuario) entra no aplicativo por meio do [INT3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados) todas as [funcionalidades](#funcionalidades) presentes podem ser acessadas: ESTADO - Funcionalidades estão disponíveis <br> Quando o [usuário](#l01:-usuario) sai do aplicativo realizando a funcionalidade [INT7](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/introspeccao.md#requisitos-elicitados): ESTADO - Apricativo está desligado  e funcionalidades não disponíveis |
| Sinônimo(s) | Acesso e desconexão |

Fonte: Maria eduarda Barbosa, 2023.

### L10: Desbloqueio com biometria está ativado

Nesse léxico a funcionalidade em uso que é implementada no aplicativo é a realização do login com a biometria ( [Q3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/questionario.md#requisitos-funcionais) ).

Tabela 12 - exemplo

| **L10** | **descrição** |
| --------------------------- | ------------- |
| Noção | O desbloqueio com biometria encontra-se em uso por um [usuário](#l01:-usuario) <br> Ocorre quando o [usuário](#l01:-usuario) seleciona a opção de ativar biometria, exercendo a função [Q3](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/tecnicas/questionario.md#requisitos-funcionais) |
| Classificação | Estado |
| Impacto(s) | Quando o [usuário](#l01:-usuario) desativa a opção de realizar desbloqueio por biometria no aplicativo: ESTADO - Biometria desativada <br>  |
| Sinônimo(s) | Liberado e despertar |

Fonte: Maria eduarda Barbosa, 2023.


## Bibliografia

> 2022.2-MEI. GitHub. Disponível em: https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/. Acesso em: 18 de outubro de 2023.

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

> SERRANO M.; SERRANO M. Requisitos - Aula 10. Aprender 3. Disponível em: https://aprender3.unb.br/pluginfile.php/2692795/mod_resource/content/1/Aula%2010.pdf. Acesso em: 18 de outubro de 2023.

## Referencia

> Referencia_1

> Referencia_2

## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `0.1`  | 17/10/2023  |  Criação da estrutura do artefato e tabela exemplo | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `0.2`  | 18/10/2023  |  Criação do conteúdo do tópico introdução | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `0.3`  | 18/10/2023  |  Criação do conteúdo do tópico metodologia e adicionando tabelas em léxicos definidos | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `0.4`  | 18/10/2023  |  Adicionando conteúdo nas tabelas dos léxicos L06 até L10 | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `0.5`  | 19/10/2023  |  Adicionando conteúdo de contexto nos léxicos L06 até L10 com hyperlinks | [Maria Barbosa](https://github.com/Madu01) | [João Victor](https://github.com/jvcostta) |
| `0.6` | 20/10/2023  |  Adicionando conteúdo da motivação e objetivo | [Maria Marques ](https://github.com/EduardaSMarques) | [João Victor](https://github.com/jvcostta) |
| `0.7` | 20/10/2023  |  Adicionando léxico L01 à L05 | [Maria Marques ](https://github.com/EduardaSMarques) | [João Victor](https://github.com/jvcostta) |


