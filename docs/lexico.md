# Léxico

## Introdução
Léxico é um modelo de requisitos e busca descrever os símbolos de uma linguagem em que cada símbolo é representado por noção(denotação) e impacto(Conotação). Um símbolo é uma palavra ou uma frase. A noção é sobre o que significa o símbolo e o impacto é sobre o efeito do símbolo no sistema ou da consequência de alguma coisa no sistema sobre o símbolo. As regras gerais deste modelo são: 

- Para cada símbolo é contido zero ou mais sinônimos.

- Para cada símbolo tem uma ou mais noções. 

- Em cada símbolo contém um ou mais impactos.

Existe também as regras por tipo os quais são: Objeto, verbo e estado. Para uma melhor explicação dessa regra observe a Tabela 1. Esse modelo ajuda a identificar, a analisar, compreender e classificar os termos e palavras-chave usados na documentação de requisitos, agregando para uma comunicação mais eficaz entre as partes envolvidas no desenvolvimento de software.

## Motivação e Objetivo

## Metodologia

A metodologia consiste primeiro em definir quais são os símbolos, em seguida seguir as regras gerais e as regras por tipo para cada símbolo definido preenchendo as informações em tabelas. Os símbolos definidos foram: 
Usuário, Aparelho, Entrar, Visualizar documento, Visualizar local, Notificar, Ajuda, Emitir certificado, Aplicativo está aberto e Desbloqueio com biometria está ativado.

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

### Usuário
### Aparelho
### Entrar
### Visualizar documento
### Visualizar local

### Notificar

Tabela 8 - exemplo

| **L06** | **descrição** |
| --------------------------- | ------------- |
| Noção | |
| Classificação | |
| Impacto(s) | |
| Sinônimo(s) | |

Fonte: Maria eduarda Barbosa, 2023.

### Ajuda

Tabela 9 - exemplo

| **L07** | **descrição** |
| --------------------------- | ------------- |
| Noção | |
| Classificação | |
| Impacto(s) | |
| Sinônimo(s) | |

Fonte: Maria eduarda Barbosa, 2023.

### Emitir certificado

Tabela 10 - exemplo

| **L08** | **descrição** |
| --------------------------- | ------------- |
| Noção | |
| Classificação | |
| Impacto(s) | |
| Sinônimo(s) | |

Fonte: Maria eduarda Barbosa, 2023.

### Aplicativo está aberto

Tabela 11 - exemplo

| **L09** | **descrição** |
| --------------------------- | ------------- |
| Noção | |
| Classificação | |
| Impacto(s) | |
| Sinônimo(s) | |

Fonte: Maria eduarda Barbosa, 2023.

### Desbloqueio com biometria está ativado

Tabela 12 - exemplo

| **L10** | **descrição** |
| --------------------------- | ------------- |
| Noção | |
| Classificação | |
| Impacto(s) | |
| Sinônimo(s) | |

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
