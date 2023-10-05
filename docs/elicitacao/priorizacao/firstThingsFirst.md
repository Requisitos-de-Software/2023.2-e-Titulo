# First Things First

## Introdução
É importante utilizar uma técnica de priorização para dar prioridade às tarefas mais importantes a serem implementadas. Será apresentado neste artefato a técnica do FTF(First Things First) e como vamos utilizá-lo no projeto.

## Motivação e Objetivo

A motivação de se usar a técnica First Things First, deve-se ao fato de que a técnica ajuda a garantir que os recursos sejam alocados de forma eficaz desde o início do projeto, focando assim nos requistos que realmente importam. Isso contribui para o sucesso geral do projeto e ajuda a evitar o desperdício de tempo e recursos em requistos menos críticos, maximizando as chances de sucesso. Dessa forma, o objetivo principal de se usar a técnica FTF é devido à sua eficácia, proporcionando clareza, foco e direção às equipes de desenvolvimento.

## Metodologia

A técnica de priorização first things first (FTF) tem como objetivo apresentar em forma de tabela os riscos, custos, benefícios e a penalidade relativa de cada requisito elicitado para o projeto, estabelecendo uma ordem de prioridade de implementação. A seguir, são explicados os passos fundamentais para a elaboração dessa técnica, encontrados no livro na Referência[1]:

Passo 1: Listar todos os requisitos, funcionalidades ou casos de uso que você deseja priorizar em uma planilha;

Passo 2: Estimar o benefício relativo que cada funcionalidade oferece ao cliente ou ao negócio em uma escala de 1 a 9, sendo 1 indicando muito pouco benefício e 9 sendo o benefício máximo possível. 

Passo 3: Estime a penalização relativa que o cliente ou o negócio sofreria se a funcionalidade não fosse incluída. Novamente, use uma escala de 1 a 9, onde 1 significa essencialmente nenhuma penalização e 9 indica uma desvantagem muito séria.

Passo 4: A coluna "Valor Total" é a soma do benefício relativo e da penalização. Por padrão, benefício e penalização têm o mesmo peso. Como refinamento, alteramos o benefício relativo para peso 2, assim, todas as classificações de benefício têm o dobro do peso das classificações de penalização. A planilha totaliza os valores das funcionalidades e calcula a porcentagem do valor total do produto que é atribuída a cada funcionalidade.

Passo 5: Estime o custo relativo de implementar cada funcionalidade, novamente em uma escala de 1 a 9. A planilha calculará a porcentagem do custo total para cada funcionalidade. 

Passo 6: Os desenvolvedores estimam o grau relativo de risco técnico ou outro risco associado a cada funcionalidade em uma escala de 1 a 9. planilha calculará a porcentagem do risco total que vem de cada funcionalidade.

Passo 7: Calcular um número de prioridade para cada funcionalidade. A fórmula para a coluna de Prioridade é: prioridade = valor % / (custo % * peso do custo + risco % * peso do risco).

Passo 8: Ordenar a lista de funcionalidades em ordem decrescente de prioridade calculada. 

Para o passo 2 e passo 3 gravamos uma reunião na qual a [Mariiana Siqueira](https://github.com/Maryyscreuza) foi a gerente e utilizamos a persona Maria Andrade, interpretada por [Esther Sena](https://github.com/esmsena) como representante dos clientes, para a obtenção de respostas. Para o passo 5 e o passo 6 a gerente se reuniu com a representante dos desenvolvedores [Maria Eduarda Marques](https://github.com/EduardaSMarques) para montagem, porém não pôde ser gravado. Por fim, novamente foram reunidas [Mariiana Siqueira](https://github.com/Maryyscreuza) e [Maria Eduarda Marques](https://github.com/EduardaSMarques) para o total preenchimento da tabela.

## Resultados 
A Figura 1 contém a priorização dos requisitos elicitados utilizando o FTF. Nem todos os requisitos estão presentes na tabela pois diferentes métodos elicitaram requisitos semelhantes.

### Legenda:

* BS: Requisitos de Brainstorming
* BSNF: Requisitos não-funcionais de Brainstorming
* ENT: Requisitos de Entrevista
* ENTNF: Requisitos não-funcionais de Entrevista
* INT: Requisitos de Introspecção
* INTNF: Requisitos não-funcionais de Introspecção

Link para planilha: https://docs.google.com/spreadsheets/d/1IaulZhzmAaYoMchSbfAYqr7WoQPFcA7TdL3vA5ieUT4/edit#gid=0

Figura 1: Priorização de requisitos utilizando a técnica First Things First.

![Tabela first things first](docs/elicitacao/firstTF.png)

Fonte: Planilhas; SIQUEIRA, Mariiana e MARQUES, Maria Eduarda 2023.

## Gravação
Link para a gravação:

## Referencia
> [1] WIEGER, Karl E. First Things First: Prioritizing Requirements. Setembro de 1999. Disponível em https://www.processimpact.com/articles/prioritizing.pdf. Acesso em: 02 de out 2023.

> 2023.1-VLC, First Things First. 01 mai 2023. Disponível em https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/elicitacao/first_things_first.md. Acesso em: 04 de out 2023.
 
## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `1.0`  | 02/10/2023  | Realização da intro. , metologia e uma das técnicas  | [Maria Marques ](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
| `1.1`  | 04/10/2023  | Edição de metodologia, adicionando a gravação | [Maria Marques ](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
