# NFR Framework

## Introdução
   
O NFR Framework é uma estrutura orientada a processos para representar e analisar requisitos não funcionais. Ele fornece diretrizes claras para a identificação, análise e priorização desses requisitos, levando em consideração as características específicas do domínio e do sistema em desenvolvimento. Isso ajuda os desenvolvedores a tomar decisões informadas sobre as alternativas de desenvolvimento, garantindo que as soluções atendam aos requisitos não funcionais de forma eficaz. O NFR Framework também promove a comunicação e colaboração entre as partes interessadas, facilitando a compreensão mútua dos requisitos e metas do sistema.

## Motivação e Objetivo

A utilização do NFR Framework neste projeto é motivada pela necessidade de representar de forma eficaz os Requisitos Não-Funcionais (RNFs). A framework oferece uma solução específica e rica para abordar esses requisitos, permitindo sua representação por meio de um grafo chamado SIG (Softgoal Interdependency Graph). O NFR Framework destaca-se por sua capacidade de expressar não apenas os próprios RNFs, mas também suas relações e correlações de maneira clara e compreensível. Isso facilita a análise e a gestão de RNFs, contribuindo para um entendimento mais profundo de como esses requisitos influenciam o sistema.

Com o uso deste framework, o projeto tem como objetivo melhorar a gestão e a compreensão dos Requisitos Não-Funcionais.


## SIG

O funcionamento do NFR framework pode ser visualizado em termos da construção, elaboração, análise e revisão incremental e interativa de um gráfico de interdependência de softgoal conhecido como "Softgoal Interdependency Graph (SIG)".Este gráfico registra as considerações do desenvolvedor sobre os softgoals e mostra suas interdependências. O registro gráfico das decisões tomadas inclui Requisitos Não-funcionais e suas alternativas, decisões e justificativas associadas às decisões. Sendo possível a realização de um procedimento de avaliação para verificar se os requisitos de nível superior são atendidos.

### Softgoal

O NFR Framework  utiliza o conceito de softgoal, que é um objetivo sem uma definição clara ou critérios precisos de satisfação. Os softgoals são usados para representar Requisitos Não-Funcionais e podem estar inter-relacionados, expressando a influência de um softgoal em outro. O Framework também possui um método de análise qualitativa para determinar o status dos softgoals, levando em consideração se outros softgoals relacionados foram ou não satisfeitos (CHUNG et al., 2000).

#### Tipos de Softgoals

O framework possue três tipos de softgoals Softgoals NFR, Softgoals de Operacionalização e Softgoals
de Afirmação. Abaixo será explicado cada um deles e na figura 1 serão ilustrados esses softgoals.

- *Softgoals NFR* Nuvens claras são utilizadas para representar esse tipo de softgoal. E segundo os autores Chung; Nixon; Yu e Mylopoulos (2000), Softgoals NFR, nada mais é do que, basicamente, os Requisitos Não-Funcionais e podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica no desenvolvimento do projeto.

- *Softgoals de Operacionalização* Já este softgoal é representado por nuvens com linhas mais grossas e segundo os mesmos autores citados no tópico acima, softgoals de operacionalização representam soluções de implementação para satisfazer softgoals NFR ou outros softgoals de operacionalização. Essas soluções incluem operações, processos, representações de dados, estruturações e restrições no sistema alvo para atender às necessidades indicadas pelos softgoals NFR e de operacionalização.

- *Softgoals de Afirmação* São usados para apoiar e justificar as decisões de desenvolvimento, levando em consideração as características do domínio, prioridades e carga de trabalho. nuvens com linhas tracejadas que são usadas para representá-lo. Eles servem como justificativa para apoiar ou negar a forma como os softgoals são priorizados, refinados e os componentes são selecionados, facilitando a revisão, a justificativa e a mudança do sistema, bem como o aprimoramento da rastreabilidade.


Figura 1 - Tipos de softgoals

![TiposSoftGo](../../planejamento/img/tiposSoftGo.png)

Fonte: SILVA, Reinaldo. 2019.

### Interdependências

Os softgoals estão inter-relacionados por meio de interdependências, tanto na direção descendente quanto ascendente. Na direção descendente, os refinamentos produzem softgoals descendentes a partir de um softgoal pai. Na direção ascendente, os softgoals descendentes contribuem positiva ou negativamente para a realização do softgoal pai.
As interdependências no framework são definidas por meio dos tipos de refinamentos e contribuições.

#### Refinamentos

 Os refinamentos definem uma interdependência hierárquica,ou seja de cima para baixo, na qual um softgoals ascendente (pai) produz um ou mais softgoals descendentes (filhos) e esses softgoals se relacionam com o softgoal ascendente. Os refinamentos são classificados em decomposição, operacionalização e afirmação. Abaixo será explicado os três tipos de refinamentos utilizados pelo NFR Framework e nas figuras 2,3 e 4 ilustrados esses refinamentos.

 As decomposições têm o objetivo de refinar softgoals para obter softgoals mais especializados e estes possam auxiliar na construção do projeto (SILVA,2019). Os quatro tipos de decomposições utilizadas pelo NFR Framework são Decomposição de Softgoal NFR, Decomposição de Operacionalização, Decomposição de Afirmação (Claims) e Priorização.

 - *Decomposição de Softgoal NFR* envolve a subdivisão de um softgoals NFR em outros mais específicos, o que ajuda a lidar com problemas maiores e prioridades, além de enfrentar ambiguidades.

 - *Decomposição de Operacionalização* é a subdivisão de um softgoal de operacionalização em softgoals mais específicos, o que permite definir uma solução geral e refiná-la em soluções mais detalhadas.

 - *Decomposição de Afirmação (Claims)* refinamento de um softgoal de afirmação em outros softgoals de afirmação, o que é importante para apoiar ou negar justificativas específicas de projeto.

 - *Priorização* é uma forma especial de decomposição em que um softgoal é refinado em outro softgoal do mesmo tipo e tópico, mas com uma prioridade associada. Isso permite estabelecer a importância relativa dos softgoals na tomada de decisões.

Figura 2 - Tipos de decomposições

![TiposDecomposição](../../planejamento/img/tiposDecomposicao.png)

Fonte: SILVA, Reinaldo. 2019.

As operacionalizações são técnicas de desenvolvimento que transformam os softgoals NFR em softgoals de operacionalização, visando alcançar os objetivos desejados. A figura 3 mostra algumas possíveis formas de operalizações de softgoals.

Figura 3 - Operalizações

![operalizações](../../planejamento/img/operalizacao.png)

Fonte: SILVA, Reinaldo. 2019.

As afirmações refinam os softgoals de afirmação em outros softgoals de afirmação (Claim). Isso é útil para apoiar ou negar motivos específicos de projeto(SILVA,2019). A figura 4 mostra algumas possíveis formas de afirmações.

Figura 4 - Afirmações

![afirmações](../../planejamento/img/afirmacoes.png)

Fonte: SILVA, Reinaldo. 2019.


#### Contribuições

No NFR framework, são usados vários tipos de contribuições para descrever como a satisfação de um softgoal descendente (filho) afeta a satisfação do softgoal ascendente (pai). Esses tipos são demonstrados na Tabela 1.

Tabela 1 - Tipos de contribuições

| **Tipo de contribuição** | **Notação da contribuição** | **Descrição** |
| ------------------------ | --------- | ------- |
| AND | **AND** | Se todos os softgoals filhos forem satisfeitos, o softgoal pai será satisfeito.| 
| OR | **OR** | Se pelo menos um softgoal filho for satisfeito, o pai também será satisfeito.| 
| MAKE | **++** | Fornece uma contribuição suficientemente positiva, garantindo que, se o softgoal filho for satisfeito, o pai também será.| 
| BREAK | **- -** | Fornece uma contribuição suficientemente negativa, indicando que, se o softgoal filho for suficientemente satisfeito, o pai será negado. | 
| HELP | **+** | Fornece uma contribuição parcialmente positiva, o que significa que, se o softgoal filho for parcialmente satisfeito, o pai será parcialmente satisfeito. | 
| HURT | **-** | Fornece uma contribuição parcialmente negativa, indicando que, se o softgoal filho for satisfeito, o pai será parcialmente negado. |
| UNKNOWN | **?** | Fornece uma contribuição desconhecida, podendo ser tanto positiva quanto negativa. |
| EQUALS | **EQUALS** | O softgoal filho só será satisfeito se o pai for satisfeito, e será negado se o pai for negado. |
| SOME + | **SOME +** | Usado quando há incerteza entre HELP ou MAKE. |
| SOME - | **SOME -** | Usado quando não há certeza entre HURT ou BREAK. |

Fonte: Maria Eduarda Barbosa. 2023.

### Procedimento de avaliação

O procedimento de avaliação determina o grau de satisfação dos requisitos não funcionais por meio de decisões, atribuindo rótulos aos softgoals no SIG, os rótulos estão representados na Figura 5. Essa análise parte dos softgoals de nível mais baixo, onde são tomadas decisões sobre a aceitação ou rejeição de alternativas no projeto. Essas decisões geram rótulos iniciais que são utilizados pelo procedimento de avaliação para determinar o impacto das decisões nos softgoals de nível mais alto na hierarquia do SIG, até chegar aos softgoals no nível mais alto.

Figura 5 - Tipos de rótulos.

![tiposRotulosSIG](../../planejamento/img/tiposRotulosSIG.png)

Fonte: SILVA, Reinaldo. 2019.

#### Explicação dos rótulos:

- **Satisfeito:** Significa que um requisito não funcional contribui positivamente para a realização de outro requisito, resultando em satisfação.
- **Fracamente Satisfeito:** Denota uma relação de impacto positiva, porém menos forte do que o rótulo satisfeito.
- **Negado:** indica que um requisito não funcional afeta de forma discordante a outro requisito, contrariando ou contradizendo sua realização.
- **Fracamente Negado:** Nesse, representa a forma menos intensa do rótulo negado.
- **Conflitante:** Mostra uma relação de conflito entre requisitos não funcionais, sugerindo que esses requisitos têm características tanto positivas quanto negativas.
- **Indeterminado:** Significa uma relação desconhecida entre requisitos não funcionais, quando não se dispõe de dados suficientes para avaliar o impacto de um requisito sobre outro.

## Cartão de especificação
Os cartões de especificação, também conhecidos como "snowcards," desenvolvidos por James Robertson e Suzanne Robertson, são uma ferramenta utilizada na engenharia de requisitos e na metodologia de desenvolvimento de sistemas. Esses cartões são usados para capturar e organizar informações relacionadas aos requisitos de um sistema ou projeto.

No caso deste projeto será utilizado o modelo adaptado desses cartões desenvolvido por Reinaldo Silva com o objetivo de representar os Requisitos Não-Funcionais utilizados na construção dos NFR Frameworks, esse modelo se encontra na tabela 2. 


Tabela 2 - Exemplo de modelo do Cartão de especificação 

| **Nº Requisito: X** (id_Requisito)  <br> **Classificação:** Nome do(s) softgoal(s)| |
| ------------------------ | --------- |
| **Descrição:** | descrição do requisito |
| **Justificativa:** | justificativa da criação do requisito |
| **Origem:** | Origem do requisito |
| **Critério de aceitação:** | métrica do requisito que possa ser testada e satisfeita |
| **Dependência:** | Requisitos relacionados ao especificado |
| **Prioridade:** | É um número que decide o nível de importância do requisito em relaçaõ aos outros, em uma escala de 0 a 10 seguindo o que foi realizado no artefato conforme o artefato [Three Level Scale](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/priorizacao/threeLevelScale.md#three-level-scale) |
| **Conflitos:** | Requisitos conflitantes ao requisito especificado |
| **História:** | Data da criação e de modificações |

Fonte: Adaptado de (ROBERTSON; ROBERTSON, 2012).

## Metodologia

Inicialmente foram selecionados os requisitos não funcionais já elicitados e presentes no artefato Especificação Suplementar, para que os softgoals principais sejam definidos, esses foram utilizados no NFR00 - Geral, e logo após foram criados os NFRs com base no geral, além dos impactos deles e no final foram criados os Cartões de especificação. No desenvolvimento dos NFRs envolveu a criação do gráfico de interdependência de softgoal conhecido como "Softgoal Interdependency Graph (SIG)" por meio da ferramenta Draw.io.

## Requisitos Não-Funcionais utilizados


<center>

Tabela 9 - Requisitos Não-Funcionais 

| ID | Descrição    | 
| -- | --- | 
|  USAB01 | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo    |    
|  USAB02 | O design deve garantir uma navegação clara e eficiente, facilitando a localização de funcionalidades pelos usuários.  |    
|  USAB03 | Todas as interações do usuário devem ser acompanhadas por feedback visual ou auditivo para fornecer orientação imediata.|  
|  USAB04  | O aplicativo deve ser acessível a usuários com deficiências, seguindo as diretrizes de acessibilidade relevantes.   |    
|  USAB05 | As atualizações de status ou notificações devem ser apresentadas de maneira não intrusiva, mantendo a experiência do usuário fluida. | 
|  USAB06 | A interface do aplicativo deve ser intuitiva, proporcionando uma experiência fácil para todos os usuários.  |    
| CONF01 |  Garantir 99,9% de disponibilidade de tempo, principalmente durante períodos eleitorais, evitando interrupções não programadas.| 
| CONF02 | Implementar backups regulares e procedimentos de recuperação eficazes para evitar perda significativa de dados em falhas inesperadas. |
| DES01 | Manter um tempo de resposta inferior a 2 segundos para interações do usuário, assegurando uma experiência ágil. |
| SUP03 | No sistema deve haver um plano de suporte ao usuário para responder a dúvidas e problemas de forma eficaz. |
| CONF03 | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança, como por exemplo: login por meio da biometria digital. | 
| CONF04 | O usuário deve poder alterar os seus dados pessoais caso desejar. |
| CONF05 | O aplicativo deve oferecer segurança ao usuário, em relação aos dados emitidos nos documentos, certificando e garantindo que estão corretos. |

Fonte: BARBOSA, maria;MARQUES,maria. 2023. 

</center>

## NFRs Definidas

### NFR00 - Geral

A figura 6 é uma representação visual do diagrama geral do SIG , adaptado do livro do Reginaldo Silva, para que todos os requisitos não funcionais priorizados do grupo fossem ilustrados.

Figura 6 - Diagrama Geral do Sig

![geral](../../planejamento/img/DiagramaGeralSig.png)

Fonte: MARQUES,maria. 2023.

### NFR01 - Usabilidade
Para elaboração do SIG da usabilidade, se encaixaram com usabilidade os seguintes requisitos não funcionais, retirados da especificação suplementar.

- USAB01: O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo.
- USAB02: O design deve garantir uma navegação clara e eficiente, facilitando a localização de funcionalidades pelos usuários.     
- USAB03: Todas as interações do usuário devem ser acompanhadas por feedback visual ou auditivo para fornecer orientação imediata.  
- USAB04: O aplicativo deve ser acessível a usuários com deficiências, seguindo as diretrizes de acessibilidade relevantes.       
- USAB05: As atualizações de status ou notificações devem ser apresentadas de maneira não intrusiva, mantendo a experiência do usuário fluida. 
- USAB06: A interface do aplicativo deve ser intuitiva, proporcionando uma experiência fácil para todos os usuários.    

#### Sem impactos propagados
A figura 7, se encontra o diagrama do SIG de usabilidade sem impactos propagados 

Figura 7 - Diagrama do Sig de usabilidade sem impactos propagados

![semPropa](../../planejamento/img/usasempropa.png)

Fonte: MARQUES, maria. 2023.

#### Com impactos propagados

A figura 8, se encontra o diagrama do SIG de usabilidade com impactos propagados

Figura 8 - Diagrama do Sig de usabilidade com impactos propagados 

![ComPropa](../../planejamento/img/UsaImpacto.png)

Fonte: MARQUES,maria. 2023.
  
### NFR02 - Confiabilidade

Foi utilizados os requisitos , para a realização do SIG.

#### Sem impactos propagados

<center>

Figura 9 - SIG de Confiabilidade sem impactos. E representado sem e com impactos.

![confGrafoSIG1](../../planejamento/img/confiaSem.png)

Fonte: BARBOSA, maria. 2023.

</center>


#### Com impactos propagados

<center>

Figura 10 - SIG de Confiabilidade com impactos.

![confGrafoSIG2](../../planejamento/img/confiaComImpacto.png)

Fonte: MARQUES, maria. 2023.

</center>


### NFR03 - Segurança

Figura 9 - SIG de Confiabilidade sem impactos. E representado sem e com impactos.

#### Sem impactos propagados

<center>

Figura 11 - SIG de Segurança sem impactos.

![seguGrafoSIG1](../../planejamento/img/seguGrafoSIG1.png)

Fonte: BARBOSA, maria. 2023.

</center>

#### Com impactos propagados

<center>

Figura 12 - SIG de Segurança com impactos.

![seguGrafoSIG2](../../planejamento/img/seguGrafoSIG2.png)

Fonte: BARBOSA, maria. 2023.

</center>

## Cartões de especificação Definidos

<center>

Tabela 3 - Cartão de especificação da Usabilidade

| **Nº Requisito: 1** (ENTNF1)  <br> **Classificação:** Usabilidade | |
| ------------------------ | --------- |
| **Descrição:** | O e-título deve ser fácil de ser encontrado e ter informações relevantes para o usuário não ficar perdido|
| **Justificativa:** | O aplicativo é voltado para a visualiazação do e-título e por isso o documento precisa ser fácil de ser achado e o app precisa ser de fácil compreensão.|
| **Origem:** | Projetista de software |
| **Critério de aceitação:** | O aplicativo deve ter o termo de uso facilmente acessível e explicar sua utilidade de forma clara para evitar problemas de entendimento. |
| **Dependência:** | Precisa que o usuário acesse o aplicativo |
| **Prioridade:** | Alta |
| **Conflitos:** | nenhum |
| **História:** | 06/11/2023 |

Fonte: MARQUES,maria. 2023.

</center>

<center>

Tabela 4 - Cartão de especificação da Usabilidade

| **Nº Requisito: 2** (ENTNF2)  <br> **Classificação:** Usabilidade | |
| ------------------------ | --------- |
| **Descrição:** | O aplicativo deve ter um design intuitivo com elementos padronizados, como botões e menus, para facilitar a navegação do usuário.|
| **Justificativa:** | visa melhorar a usabilidade do aplicativo, tornando-o mais intuitivo e fácil de usar para os usuários. |
| **Origem:** | Projetista de software |
| **Critério de aceitação:** |  a presença de botões e menus padronizados em todo o aplicativo, garantindo uma aparência consistente e uma experiência de navegação intuitiva. |
| **Dependência:** | Do desenvolvimento |
| **Prioridade:** | Alta |
| **Conflitos:** | Nenhum |
| **História:** | 06/11/2023 |

Fonte: MARQUES,maria. 2023.

</center>

<center>

Tabela 5 - Cartão de especificação de Confiabilidade 

| **Nº Requisito: 3** (  )  <br> **Classificação:**   | |
| ------------------------ | --------- |
| **Descrição:** |  |
| **Justificativa:** | |
| **Origem:** |  |
| **Critério de aceitação:** | |
| **Dependência:** | Nenhum |
| **Prioridade:** |  |
| **Conflitos:** | Nenhum |
| **História:** | /11/2023 |

Fonte: BARBOSA, maria. 2023.

</center>


## Bibliografia

> 2023.1-Simplenote. GitHub. Disponível em: https//requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/nfr/. Acesso em: 1 de novembro de 2023.  

> 2023.1-BilheteriaDigital. GitHub. Disponível em: https//requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/. Acesso em: 1 de novembro de 2023.  

> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 26/06/2023


## Histórico de Versões

| Versão |     Data    | Descrição   | Autor(es) | Revisor(es) |
| ------ | ----------- | ----------- | --------- | ----------- |
| 1.0  | 03/11/2023  | adição do esqueleto do artefato | [Maria Barbosa](https//github.com/Madu01) | [João Victor](https//github.com/jvcostta) e [Mateus Orlando](https//github.com/MateusPy) |
| 1.1  | 04/11/2023  | adição do conteúdo no tópico Motivação e Objetivo e melhoramento do esqueleto do artefato | [Maria Barbosa](https//github.com/Madu01) | [João Victor](https//github.com/jvcostta) e [Mateus Orlando](https//github.com/MateusPy) |
| 1.2  | 05/11/2023  | adição da introdução e do SIG | [Maria Marques ](https//github.com/EduardaSMarques) | [João Victor](https//github.com/jvcostta) e [Mateus Orlando](https//github.com/MateusPy) |
| 1.3  | 06/11/2023  | acrescentando outros tópicos do SIG até refinamentos | [Maria Marques ](https//github.com/EduardaSMarques) | [João Victor](https//github.com/jvcostta) e [Mateus Orlando](https//github.com/MateusPy) |
| 1.4  | 06/11/2023  | Adicionando conteúdos nos tópicos Contribuições, Procedimento de avaliação, Cartão de especificação e Metodologia e atualização no tópico NFR Definidas | [Maria Barbosa](https//github.com/Madu01) | [João Victor](https//github.com/jvcostta) e [Mateus Orlando](https//github.com/MateusPy) |
| 1.5  | 06/11/2023  | Adicionando diagramas geral e de usabilidade e cartões | [Maria Marques ](https//github.com/EduardaSMarques)  | [João Victor](https//github.com/jvcostta) e [Mateus Orlando](https//github.com/MateusPy) |
| 1.6  | 06/11/2023  | Adicionando conteúdos nos tópicos contidos nos NFRs de Confiabilidade e segurança além do tópico de requisitos utilizados | [Maria Barbosa](https//github.com/Madu01) | [João Victor](https//github.com/jvcostta) e [Mateus Orlando](https//github.com/MateusPy) |
| 1.7  | 06/11/2023  | Arrumando rotas das imagens | [Mateus Orlando](https//github.com/MateusPy) e [João Victor](https//github.com/jvcostta) | [Esther Sena](https://github.com/esmsena) |
| 1.8 | 02/11/2023 | Correção em metodologia, adicionando novas imagens em NFR02(sem impactos) e NFR03(sem impactos e com impactos), atualização em requisitos não funcionais utilizados |  [Maria Barbosa](https://github.com/Madu01)  | [João Costa ](https://github.com/jvcostta) |
| 1.9  | 03/12/2023  | Corrigindo sig de usabilidade e de confiabilidade com impacto | [Maria Marques ](https//github.com/EduardaSMarques)  | [João Victor](https//github.com/jvcostta) |
