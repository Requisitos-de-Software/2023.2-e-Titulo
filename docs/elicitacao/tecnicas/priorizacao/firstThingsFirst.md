# First Things First

## Introdução
É importante utilizar uma técnica de priorização para dar prioridade às tarefas mais importantes a serem implementadas. Será apresentado neste artefato a técnica do FTF(First Things First) e como vamos utilizá-lo no projeto.

## Motivação e Objetivo

A motivação de se usar a técnica First Things First, deve-se ao fato de que a técnica ajuda a garantir que os recursos sejam alocados de forma eficaz desde o início do projeto, focando assim nos requistos que realmente importam. Isso contribui para o sucesso geral do projeto e ajuda a evitar o desperdício de tempo e recursos em requistos menos críticos, maximizando as chances de sucesso. Dessa forma, o objetivo principal de se usar a técnica FTF é devido à sua eficácia, proporcionando clareza, foco e direção às equipes de desenvolvimento.

## Metodologia

A técnica de priorização first things first (FTF) tem como objetivo apresentar em forma de tabela os riscos, custos, benefícios e a penalidade relativa de cada requisito elicitado para o projeto, estabelecendo uma ordem de prioridade de implementação. A seguir, são explicados os passos fundamentais para a elaboração dessa técnica, encontrados no livro na Referência[1]:

Passo 1: Liste todos os requisitos, funcionalidades ou casos de uso que você deseja priorizar em uma planilha; usaremos funcionalidades neste exemplo. Todos os itens devem estar no mesmo nível de abstração. Por exemplo, não misture requisitos individuais com funcionalidades do produto. Se certas funcionalidades estiverem logicamente relacionadas (ou seja, você só implementaria a funcionalidade B se a funcionalidade A também estivesse incluída), inclua apenas a funcionalidade principal na análise. Esse modelo funcionará com até algumas dezenas de funcionalidades antes de se tornar difícil de gerenciar. Se você tiver mais itens do que isso, agrupe funcionalidades relacionadas para criar uma lista inicial mais gerenciável. Você pode realizar uma segunda rodada de análise em um nível mais detalhado de requisitos, se necessário.

Passo 2: Estime o benefício relativo que cada funcionalidade oferece ao cliente ou ao negócio em uma escala de 1 a 9, sendo 1 indicando muito pouco benefício e 9 sendo o benefício máximo possível. Esses benefícios indicam a conformidade com os requisitos comerciais do produto. Seus representantes de clientes são as melhores pessoas para julgar esses benefícios.

Passo 3: Estime a penalização relativa que o cliente ou o negócio sofreria se a funcionalidade não fosse incluída. Novamente, use uma escala de 1 a 9, onde 1 significa essencialmente nenhuma penalização e 9 indica uma desvantagem muito séria. Por exemplo, não cumprir uma regulamentação governamental pode incorrer em uma penalização alta, mesmo que o benefício para o cliente seja baixo, assim como omitir uma funcionalidade que qualquer cliente razoável esperaria, independentemente de solicitá-la explicitamente. Requisitos que têm tanto um baixo benefício quanto uma baixa penalização adicionam custo, mas pouco valor; eles podem ser instâncias de excesso de detalhes.

Passo 4: A coluna "Valor Total" é a soma do benefício relativo e da penalização. Por padrão, benefício e penalização têm o mesmo peso. Como refinamento, você pode alterar os pesos para esses dois fatores. Na Tabela 2, todas as classificações de benefício têm o dobro do peso das classificações de penalização. A planilha totaliza os valores das funcionalidades e calcula a porcentagem do valor total do produto que é atribuída a cada funcionalidade.

Passo 5: Estime o custo relativo de implementar cada funcionalidade, novamente em uma escala de 1 a 9. A planilha calculará a porcentagem do custo total para cada funcionalidade. Os desenvolvedores estimam as classificações de custo com base em fatores como complexidade dos requisitos, extensão do trabalho de interface do usuário necessário, potencial para reutilizar designs ou código existentes e níveis de teste e documentação necessários.

Passo 6: Os desenvolvedores estimam o grau relativo de risco técnico ou outro risco associado a cada funcionalidade em uma escala de 1 a 9. Uma estimativa de 1 significa que você pode programá-la facilmente, enquanto 9 indica preocupações sérias quanto à viabilidade, disponibilidade de pessoal com a experiência necessária ou uso de ferramentas e tecnologias não comprovadas ou não familiares. A planilha calculará a porcentagem do risco total que vem de cada funcionalidade.

Por padrão, custo e risco têm o mesmo peso e cada um carrega o mesmo peso que os termos de benefício e penalização. Você pode ajustar os pesos de custo e risco na planilha. Na Tabela 2, o risco tem metade do peso do fator de custo, que tem o mesmo peso que o termo de penalização. Se você não quiser considerar o risco no modelo, defina o valor de ponderação do risco como zero.

Passo 7: Uma vez que você insere as estimativas na planilha, ela calcula um número de prioridade para cada funcionalidade. A fórmula para a coluna de Prioridade é: prioridade = valor % / (custo % * peso do custo + risco % * peso do risco).

Passo 8: Ordene a lista de funcionalidades em ordem decrescente de prioridade calculada. As funcionalidades no topo da lista têm o equilíbrio mais favorável entre valor, custo e risco e, portanto, devem ter maior prioridade de implementação. Os principais representantes de clientes e desenvolvedores devem revisar a planilha concluída para concordar com as classificações e a sequência resultante.

## Resultados 

Link https://docs.google.com/spreadsheets/d/1IaulZhzmAaYoMchSbfAYqr7WoQPFcA7TdL3vA5ieUT4/edit#gid=0


## Bibliografia

>
> 

## Referencia


> [1] WIEGER, Karl E. First Things First: Prioritizing Requirements. Setembro de 1999. Disponível em .[link]..(https://www.processimpact.com/articles/prioritizing.pdf). Acesso em: 02 de out 2023.

> 

## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `0.1`  | 02/10/2023  | Realização da intro. , metologia e uma das técnicas  | [Maria Marques ](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Esther Sena](https://github.com/esmsena) e [Maria Barbosa](https://github.com/Madu01) |
