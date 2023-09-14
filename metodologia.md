# Metodologia

## Introdução
É de suma importância a utilização de uma metodologia para o desenvolvimento do projeto, pois servirá como um guia para ajudar o grupo a atingir os objetivos de forma planejada. A equipe escolheu a metodologia ágil Scrum, mas de forma adaptável para simplificar sua utilização no decorrer da produção do projeto.

## Motivação e objetivo
A motivação da escolha do Scrum adaptável é a facilidade que a equipe tem de utilizá-lo, além de ser aberto a adaptações que vão precisar para facilitar a agilidade e dinâmica do grupo. O objetivo que o grupo tem com a utilização dessa metodologia é aumentar a produtividade, facilitar o gerenciamento do projeto e minimizar os riscos que podem surgir durante o projeto.

## Scrum 
O scrum é uma série de atividades que propiciam um progresso contínuo em um desenvolvimento de projeto, sendo objetivo, definindo papéis e fases. Os papéis mais comuns do scrum são o Product Owner, ScrumMaster e o Scrum Team. As fases do scrum, primeiro começa com uma reunião de planejamento (Sprint Planning Meeting) depois a execução da sprint com reuniões diárias rápidas (Daily), após terminar a sprint realizar uma reunião de revisão (Sprint Review) e em seguida reunião de retrospectiva (Sprint Retrospective).

### Fases
Reunião de planejamento: É realizada antes da cada sprint, é decidido o que será realizado dentro da sprint que está por vir, antes dessa reunião é desenvolvido o Product Backlog que contém uma lista de itens priorizados que incluem tudo o que precisa ser realizado. 

Execução da sprint: A sprint é ciclos com atividades, cada um com duração de 2 a 4 semanas, a sua execução é a realização das atividades.

Reunião de revisão: é demonstrado o que foi feito na Sprint e valida se o objetivo foi concluído. 

Reunião de retrospectiva: é relatado as lições aprendidas com o intuito de melhorar o time, produto e o desenvolvimento para a próxima sprint. 

### Papéis e suas responsabilidades
Scrum Master: Administra a equipe, garantindo que esteja produtiva e seguindo com os objetivos e atividades. 

Product Owner: O que mais conhece o produto, priorizando os itens de Product Backlog.

Scrum Team: Realizam as atividades definidas em cada sprint.

## Sprint adaptada
Como já foi apresentado o que é o scrum, agora será apresentado o que vamos utilizar dessa metodologia no projeto.

### Fases

Será usado apenas a Reunião de planejamento e Execução da sprint, a Reunião de retrospectiva será inserida na de planejamento para ganharmos mais tempo. Não vamos usar a daily por não acharmos eficiente para o nosso caso.

Foi feito um Roadmap com os integrantes para definir qual dia seria possível fazer as Reuniões de planejamento, o dia definido foi todas as quartas de cada semana a partir das 20h até 21h, o intuito da reunião é ter 15 minutos de duração.

### Responsáveis para cada papel

O Scrum Master e Product Owner não terá no projeto, pois a equipe não sentiu nessecidade, mas haverá o Scrum Team.    

Scrum Team: todos os 6 integrantes presentes no projeto.

Essas definições podem sofrer alterações futuras.

## Políticas 
As políticas servem para definir regras com o objetivo de manter a organização do desenvolvimento

### política de issue
As issues é onde serão colocado as atividades a serem feitas durante cada sprint. Ela seguira este modelo

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

### política de Branch
A divisão das branches tem o intuito de melhorar a dinâmica e a organização do fluxo de trabalho no GitHub. A criação dessa divisão foi inspirada no [Git Flow](https://leanpub.com/git-flow/read).

Utilizaremos 3 tipos de branches

#### main

Ela é a principal branch, é onde que vai estar os documentos estável em nível de produção. 

#### develop
É a branch onde as feature vão mergar, ela contem os documentos ou informações que podem está instáveis. 

#### feature

São branches que serão criadas a partir da branch develop para que possa ser desenvolvido novos recursos ao projeto. Quando uma feature for concluída deverá ser juntada na develop seguindo a restrição de estar estável, caso ocorra instabilidade terá que abrir uma nova branch chamada fix para corrigir algum problema e logo após mesclar de volta a feature.

### política do Pull request

# Bibliografia

# Referência

# Histórico de Versões


## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| `0.1`  | 12/09/2023  | início da criação dos tópicos da introdução | Maria Barbosa | -- |