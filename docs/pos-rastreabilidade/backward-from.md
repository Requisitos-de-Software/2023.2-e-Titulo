# Backward From

## Introdução
Neste documento, exploraremos a abordagem "Backward From" na elicitação de requisitos, que nos leva do resultado desejado às raízes dos requisitos. Diferente das metodologias convencionais, essa técnica oferece uma compreensão mais profunda do contexto e das variáveis que influenciam os requisitos. Este artefato busca uma abordagem inovadora na engenharia reversa de requisitos, revelando as camadas subjacentes de necessidades para construir uma base sólida utilizando o método de rastreabilidade backward from descritos na monografia de Rastreabilidade de requisitos da Miriam Sayão e Julio Cesar Sampaio do Prado Leite.

## Objetivo 
Este documento é um guia para usar a técnica "Backward From" na obtenção de requisitos. Vamos explorar como essa abordagem nos ajuda a entender melhor o que um sistema precisa, começando pelo resultado desejado e retrocedendo até as necessidades fundamentais. A ideia é oferecer uma ferramentas para aplicar essa técnica de engenharia reversa de requisitos de forma inovadora, ajudando no desenvolvimento de sistemas mais sólidos e claros. 

## Metodologia
Para colocar em prática a metodologia, inicialmente elaboramos duas tabelas distintas: uma dedicada aos requisitos funcionais ( Tabela 1) e outra para os requisitos não funcionais ( Tabela 2). Posteriormente, inserimos a fonte de origem desses requisitos nas tabelas, garantindo a rastreabilidade. Por último, empregando o Meta-modelo de Toranzo, delineamos as interconexões entre esses requisitos por meio dos Elos.

### Legendas:
* RF: Requisito funcional;
* RNF: Requisito não funcional;
* QST: Quetionário;
* ST: Storytelling
* BS: Brainstorm;
* INT: Introspecção;

## Tabelas de requisitos

### Requisitos funcionais:
| ID | Descrição | Origem |
| :--: | :--: | :--: |
| RF01 | |  |
| RF02 | |  |
| RF03 | |  |
| RF04 |  |  |
| RF05 | |  |
| RF06 | |  |
| RF07 | |  |
| RF08 | |  |
| RF9 |  |  |
| RF10 | |  |
| RF11 | |  |
| RF12 | |  |
| RF13 |  |  |
| RF14 |  |  |
| RF15 |  |  |
| RF16 |  |  |
| RF17 |  |  |
| RF18 |  |  |
| RF19 |  |  |
| RF20 |  |  |
| RF21 | |  |
| RF22 |  |  |
| RF23 |  |  |
| RF24 | |  |
| RF25 |  |  |
| RF26 |  |  |
| RF27 |  |  |
| RF28 | |  |
| RF29 |  |  |
| RF30 |  |  |
| RF31 | |  |


<figcaption align="center">Tabela 1: Requisitos funcionais (Fonte: Autores, 2022)</figcaption>

### Requisitos não funcionais:
| ID | Descrição | Origem |
| :--: | :--: | :--: |
| RNF01 | |  |
| RNF02 | |  |
| RNF03 |  |  |
| RNF04 |  |  |
| RNF05 |  |  |
| RNF06 |  |  |
| RNF07 |  |  |
| RNF08 |  |  |
| RNF09 |  |  |
| RNF10 | |  |
| RNF11 | |  |
| RNF12 |  |  |
| RNF13 |  | |
| RNF14 |  |  |  |  |
| RNF17 |  | |
| RNF18 |  | |
| RNF19 |  |  |
| RNF20 |  |  |

<figcaption align="center">Tabela 2: Requisitos não funcionais (Fonte: Autores, 2022)</figcaption>

## Elos

Os elos desenvolvidos neste artefato fazem referência aos requisitos elicitados listados nas <i>tabelas 1 e 2</i>, seguindo o Meta-Modelo de Toranzo para estruturação de seus elos de rastreabilidade.

### Elos de rastreabilidade

| Elo | Especificação |
|:---:| :------------:|
| Agregação | implica na união ou composição de elementos |
| Representação | abrange a tradução ou modelagem de requisitos em diferentes linguagens |
| Satisfação | a classe de origem depende da satisfação proporcionada pela classe de destino |
| Recurso | a classe de origem depende dos recursos fornecidos pela classe de destino |
| Responsabilidade | documenta o envolvimento, responsabilidade e ação de indivíduos em relação aos artefatos |
| Alocado | a classe de origem está associada à classe de destino, representando um subsistema |

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
| `1.0`  | 15/11/2023 |  Criando estrutura do documento com formatação de tabelas, introdução, objetivo e metodologia.  | [Esther Sena](https://github.com/esmsena) | |

