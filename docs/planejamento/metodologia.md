# Metodologia

## Introdução
É de suma importância a utilização de uma metodologia para o desenvolvimento do projeto, pois servirá como um guia para ajudar o grupo a atingir os objetivos de forma planejada. A equipe escolheu a metodologia ágil Scrum, mas de forma adaptável para simplificar sua utilização no decorrer da produção do projeto.

## Motivação e objetivo
A motivação da escolha do Scrum adaptável é a facilidade que a equipe tem de utilizá-lo, além de ser aberto a adaptações que vão precisar para facilitar a agilidade e dinâmica do grupo. O objetivo que o grupo tem com a utilização dessa metodologia é aumentar a produtividade, facilitar o gerenciamento do projeto e minimizar os riscos que podem surgir durante o projeto.

## Scrum 
O scrum é uma série de atividades que propiciam um progresso contínuo em um desenvolvimento de projeto, sendo objetivo, definindo papéis e fases. Os papéis mais comuns do scrum são o Product Owner, ScrumMaster e o Scrum Team. As fases do scrum, primeiro começa com uma reunião de planejamento (Sprint Planning Meeting) depois a execução da sprint com reuniões diárias rápidas (Daily), após terminar a sprint realizar uma reunião de revisão (Sprint Review) e em seguida reunião de retrospectiva (Sprint Retrospective).

### Fases
**Reunião de planejamento:** É realizada antes da cada sprint, é decidido o que será realizado dentro da sprint que está por vir, antes dessa reunião é desenvolvido o Product Backlog que contém uma lista de itens priorizados que incluem tudo o que precisa ser realizado. 

**Execução da sprint:** A sprint é ciclos com atividades, cada um com duração de 2 a 4 semanas, a sua execução é a realização das atividades.

**Reunião de revisão:** é demonstrado o que foi feito na Sprint e valida se o objetivo foi concluído. 

**Reunião de retrospectiva:** é relatado as lições aprendidas com o intuito de melhorar o time, produto e o desenvolvimento para a próxima sprint. 

### Papéis e suas responsabilidades
**Scrum Master:** Administra a equipe, garantindo que esteja produtiva e seguindo com os objetivos e atividades. 

**Product Owner:** O que mais conhece o produto, priorizando os itens de Product Backlog.

**Scrum Team:** Realizam as atividades definidas em cada sprint.

## Sprint adaptada
Como já foi apresentado o que é o scrum, agora será apresentado o que vamos utilizar dessa metodologia no projeto.

### Fases

Será usado apenas a Reunião de planejamento e Execução da sprint, a Reunião de retrospectiva será inserida na de planejamento para ganharmos mais tempo. Não vamos usar a daily por não acharmos eficiente para o nosso caso.

Foi feito um Heatmap com os integrantes para definir qual dia seria possível fazer as Reuniões de planejamento, o dia definido foi todas as quartas de cada semana a partir das 20h até 21h, o intuito da reunião é ter 15 minutos de duração. O Heatmap está disponível em [LinkParaHeatmap](https://requisitos-de-software.github.io/2023.2-e-Titulo/planejamento/heatmap/).

### Responsáveis para cada papel

O Scrum Master e Product Owner não terá no projeto, pois a equipe não sentiu nessecidade, mas haverá o Scrum Team.    

Scrum Team: todos os 6 integrantes presentes no projeto.

Essas definições podem sofrer alterações futuras.

## Padrão no artefato
Foi definido um padrão a ser seguido para os membros do trabalho quando forem desenvolver algum artefato, o intuito é manter uma consistência no projeto. 

Esse padrão contém a estrutura do artefato já pré montada para o integrante copiá-la e realizar a sua tarefa, porém dependendo do artefato o realizador dela pode fazer modificações nesse padrão apenas em seu próprio artefato, por haver a chance de ter características diferenciadas. essa estrutura está disponível em [EsqueletoDeArtefatos](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/planejamento/esqueletoArtefatos).

### Padrão em citar
Será utilizado as normas da ABNT para as citações nas bibliografias e referências, assim como nas figuras, diagramas e tabelas, entre outros.

Exemplo ao Fazer citação em figuras, diagramas e tabelas:

```
Figura 1 - nome descritivo referente a figura
(colocar a figura aqui!)
Fonte: citar a fonte.
```
Observando o exemplo logo acima, é preciso que mude a palavra Figura de acordo com qual for usar, se é diagrama ou tabelas.

## Políticas 
As políticas servem para definir regras com o objetivo de manter a organização do desenvolvimento

### política de issue
As issues é onde que será colocadas as atividades a serem feitas durante cada sprint. 

A estrutura a ser seguida ao criar uma issue:

```
# Descrição
    Breve descrição sobre a issue.

# Tarefas
    Checklist de ações que devem ser realizadas.

    [ ] Tarefa 1
    [ ] Tarefa 2

# Critérios de Aceitação
    Definir os critérios para a issue ser considerada concluída.
	
    [ ] Critério 1
    [ ] Critério 2

# Informações Adicionais
    Se precisar informar algo a mais utilize esse espaço. 
```

### política de commit
As descrições das alterações devem ser feitas seguindo um padrão, indicando a issue resolvida e a funcionalidade (ou correção) adicionada.

Utilize tags para definir o propósito do commit:

- `ADD` : Quando adicionar alguma coisa nova no projeto   

- `DEL` : Caso seja relacionado a remoção de algo

- `UPDATE` : Quando atualizar algum documento ou algo 

- `PAGES` : quando for algo específico relacionado ao gitHub Pages

A estrutura do commit é:

```
[tag]: mensagem descritiva
```

O exemplo logo abaixo é um comando de como é feito a estrutura no terminal

Ex:

``` 
git commit -m "[tag]: mensagem descritiva"
```


### política de Branch
A divisão das branches tem o intuito de melhorar a dinâmica e a organização do fluxo de trabalho no GitHub. A criação dessa divisão foi inspirada no [Git Flow](https://leanpub.com/git-flow/read).

Utilizaremos 2 tipos de branches:

#### main

Ela é a principal branch, é onde que vai estar os documentos em nível de produção. 

#### feature

São branches que serão criadas a partir da branch main para que possa ser desenvolvido novos recursos ao projeto. Quando uma feature for concluída deverá ser juntada na main e logo em seguida deverá ser excluída para não acumular branches não utilizadas.

###### O padrão a ser seguido para nomear uma feature: 
`feature-nomeDaNovaBranch` 

### política do Pull request
O pull request é onde serão feitas as revisões do que foi feito, deverá ter um revisor que irá aceitar ou não o pull request. Para caso o revisor encontrar algum problema, ele mesmo irá corrigir e avisar o responsável que fez alterações.

A estrutura a ser seguida ao criar um Pull request:

```
## Descrição 

Descrever de forma objetiva e coerente o que foi feito

## Tarefas realizadas

- [ ] Tarefa

- [ ] Tarefa

## Resolve 

Issues que foram resolvidas com o pull request

## Critérios de aceitação

- [ ] O Pull Request deve ser revisado e aceito
```

## Bibliografia
> PEREIRA Paulo; TORREÃO Paula; MARÇAL Ana. Entendendo Scrum para Gerenciar Projetos de Forma Ágil. MundoPM, 2007. Disponível em: https://d1wqtxts1xzle7.cloudfront.net/49393858/EntendendoScrumparaGerenciarProjetosdeFormaAgil-libre.pdf?1475741991=&response-content-disposition=inline%3B+filename%3DEntendendo_Scrum_para_Gerenciar_Projetos.pdf&Expires=1694639672&Signature=WvZeA2J4NVoTgddZl8hQHX-6eix~poH8BhEUBmJ1o8H-8VKfizN7CpEOIGS2i1PLHjqKl5OsoN7kRdlu0DUVnE~Ey3XVVk-fGccHVnTETOBa~m5Tf59CSVX2N3AISWAg7UOBL~C-muBHuPj-oJUmmgo88ckl736j9HgjePbqgRyOQVpC9sgysyUMmo4cCusaEOMMXIYE3qE709wrXXuJfXYmS-GPdP3e1jgau1oQSG~OyJluVy9gVG99G9hwX-0L9Jd~i8J4PLJZZ5p~oD30702fQleBNeSCliyAxi9UJydZB5NnhNQ3BEF8sGR7B8ao1WB6co1LtSyLcINFpeBuPg__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA. Acesso em: 12 de setembro de 2023.

> 2021.2-Sigaa-Plus. GitHub. Disponível em: https://github.com/Madu01/2021.2-Sigaa-Plus/blob/main/docs/CONTRIBUTING.md. Acesso em: 12 de setembro de 2023.  

## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `1.0`  | 12/09/2023  | início da criação dos tópicos da introdução | [Maria Barbosa](https://github.com/Madu01) | [Mateus Orlando](https://github.com/MateusPy) |
| `1.1`  | 12/09/2023  | atualização e adicionamento de novo tópico | [Maria Barbosa](https://github.com/Madu01) | [Mateus Orlando](https://github.com/MateusPy) |
| `1.2`  | 12/09/2023  | atualização no documento, adicionamento de padrões | [Maria Barbosa](https://github.com/Madu01) | [Mateus Orlando](https://github.com/MateusPy) |
| `1.3`  | 12/09/2023  | atualização no documento, alterando tags  e explicação para o commit | [Maria Barbosa](https://github.com/Madu01) | [Mateus Orlando](https://github.com/MateusPy) |
