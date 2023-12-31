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
| **Prioridade:** | É um número que decide o nível de importância do requisito em relaçaõ aos outros, em uma escala seguindo o que foi realizado no artefato conforme o artefato [Three Level Scale](https://github.com/Requisitos-de-Software/2023.2-e-Titulo/blob/main/docs/elicitacao/priorizacao/threeLevelScale.md#three-level-scale) |
| **Conflitos:** | Requisitos conflitantes ao requisito especificado |
| **História:** | Data da criação e de modificações |

Fonte: Adaptado de (ROBERTSON; ROBERTSON, 2012).

## Metodologia

Inicialmente foram selecionados os requisitos não funcionais já elicitados e presentes no artefato Especificação Suplementar, para que os softgoals principais sejam definidos, esses foram utilizados no NFR00 - Geral, e logo após foram criados os NFRs com base no geral, além dos impactos deles e no final foram criados os Cartões de especificação. No desenvolvimento dos NFRs envolveu a criação do gráfico de interdependência de softgoal conhecido como "Softgoal Interdependency Graph (SIG)" por meio da ferramenta Draw.io.

## Requisitos Não-Funcionais utilizados


<center>

Tabela 3 - Requisitos Não-Funcionais 

| ID | Descrição    | 
| -- | --- | 
| <a id=anchor_a1 href="#REF01">USAB01</a>   | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo    |    
| <a id=anchor_a2 href="#REF02">USAB02</a>  | O design deve garantir uma navegação clara e eficiente, facilitando a localização de funcionalidades pelos usuários.  |    
|  <a id=anchor_a3 href="#REF03">USAB03</a> | Todas as interações do usuário devem ser acompanhadas por feedback visual ou auditivo para fornecer orientação imediata.|  
|  <a id=anchor_a4 href="#REF04">USAB04</a>   | O aplicativo deve ser acessível a usuários com deficiências, seguindo as diretrizes de acessibilidade relevantes.   |    
|  <a id=anchor_a5 href="#REF05">USAB05</a>  | As atualizações de status ou notificações devem ser apresentadas de maneira não intrusiva, mantendo a experiência do usuário fluida. | 
| <a id=anchor_a6 href="#REF06">USAB06</a> | A interface do aplicativo deve ser intuitiva, proporcionando uma experiência fácil para todos os usuários.  |    
| <a id=anchor_c1 href="#REF1">CONF01</a> |  Garantir 99,9% de disponibilidade de tempo, principalmente durante períodos eleitorais, evitando interrupções não programadas.| 
| <a id=anchor_c2 href="#REF2">CONF02</a> | Implementar backups regulares e procedimentos de recuperação eficazes para evitar perda significativa de dados em falhas inesperadas. |
| <a id=anchor_d1 href="#REF3">DES01</a> | Manter um tempo de resposta inferior a 2 segundos para interações do usuário, assegurando uma experiência ágil. |
| <a id=anchor_s3 href="#REF4">SUP03</a> | No sistema deve haver um plano de suporte ao usuário para responder a dúvidas e problemas de forma eficaz. |
| <a id=anchor_c3 href="#REF5">CONF03</a> | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança, como por exemplo: login por meio da biometria digital. | 
| <a id=anchor_c4 href="#REF6">CONF04</a> | O usuário deve poder alterar os seus dados pessoais caso desejar. |
| <a id=anchor_c5 href="#REF7">CONF05</a> | O aplicativo deve oferecer segurança ao usuário, em relação aos dados emitidos nos documentos, certificando e garantindo que estão corretos. |

Fonte: BARBOSA, maria;MARQUES,maria. 2023.  


</center>

## NFRs Definidas

### NFR00 - Geral

A figura 6 é uma representação visual do diagrama geral do SIG , adaptado do livro do Reginaldo Silva, para que todos os requisitos não funcionais priorizados do grupo fossem ilustrados.

Figura 6 - Diagrama Geral do Sig

![geral](../../planejamento/img/DiagramaGeralSig.png)

Fonte: MARQUES,maria. 2023.

### NFR01 - Usabilidade

Para elaboração do SIG da usabilidade, se encaixaram com usabilidade os seguintes requisitos não funcionais, retirados da especificação suplementar, <a id="REF01" href="#anchor_a1">USAB01</a>, <a id="REF02" href="#anchor_a2">USAB02</a>,<a id="REF03" href="#anchor_a3">USAB03</a>,<a id="REF04" href="#anchor_a4">USAB04</a>,<a id="REF05" href="#anchor_a5">USAB05</a> e <a id="REF06" href="#anchor_a6">USAB06</a>.


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

Foi utilizados os requisitos <a id="REF1" href="#anchor_c1">CONF01</a>, <a id="REF2" href="#anchor_c2">CONF02</a>, <a id="REF3" href="#anchor_d1">DES01</a> e <a id="REF4" href="#anchor_s3">SUP03</a>, para a realização do SIG de confiabilidade com e sem impactos.


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

Foi utilizado os requisitos <a id="REF5" href="#anchor_c3">CONF03</a>, <a id="REF6" href="#anchor_c4">CONF04</a> e <a id="REF7" href="#anchor_c5">CONF05</a>  para a criação do SIG de segurança com e sem impactos.


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
 <a id="REF01" href="#anchor_a1">USAB01</a>, <a id="REF02" href="#anchor_a2">USAB02</a>,<a id="REF03" href="#anchor_a3">USAB03</a>,<a id="REF04" href="#anchor_a4">USAB04</a>,<a id="REF05" href="#anchor_a5">USAB05</a> e <a id="REF06" href="#anchor_a6">USAB06</a>.
### Cartões de especificação do NFR01 - Usabilidade

<center>

Tabela 3 - Cartão de especificação da Usabilidade

| **Nº Requisito: 1** <a id="REF01" href="#anchor_a1">(USAB01)</a>  <br> **Classificação:** Usabilidade/Suporte | |
| ------------------------ | --------- |
| **Descrição:** | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo |
| **Justificativa:** | Disponibilizar um termo de uso acessível e explicar a utilidade do aplicativo de maneira clara promove transparência, constrói confiança com os usuários e evita mal-entendidos.|
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | O aplicativo deve ter o termo de uso facilmente acessível e explicar sua utilidade de forma clara para evitar problemas de entendimento. |
| **Dependência:** | Precisa que o usuário acesse o aplicativo |
| **Prioridade:** | Alta |
| **Conflitos:** | nenhum |
| **História:** | 05/12/2023 |

Fonte: MARQUES,maria. 2023.

</center>

<center>

Tabela 4 - Cartão de especificação da Usabilidade

| **Nº Requisito: 2** <a id="REF02" href="#anchor_a2">(USAB02)</a>  <br> **Classificação:** Usabilidade/Consistência | |
| ------------------------ | --------- |
| **Descrição:** | O design deve garantir uma navegação clara e eficiente, facilitando a localização de funcionalidades pelos usuários.|
| **Justificativa:** |Garantir uma navegação eficiente e clara é essencial para a satisfação do usuário, promovendo uma experiência positiva e facilitando a localização de funcionalidades. |
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | O design deve organizar elementos de maneira lógica, oferecer menus e botões intuitivos e manter consistência na navegação.|
| **Dependência:** | Depende da avaliação contínua dos usuários e atualizações periódicas para atender às evoluções nas necessidades e tecnologias. |
| **Prioridade:** | Alta |
| **Conflitos:** | nenhum |
| **História:** | 05/12/2023 |

Fonte: MARQUES,maria. 2023.

</center>

<center>

Tabela 5 - Cartão de especificação da Usabilidade

| **Nº Requisito: 3** <a id="REF03" href="#anchor_a3">(USAB03)</a>  <br> **Classificação:** Usabilidade/Consistência | |
| ------------------------ | --------- |
| **Descrição:** | Todas as interações do usuário devem ser acompanhadas por feedback visual ou auditivo para fornecer orientação imediata.|
| **Justificativa:** | É crucial para orientação imediata, melhorando a experiência ao manter os usuários informados sobre suas ações e o estado do sistema.|
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | Garantir feedback visual imediato, como animações ou ícones, e, quando apropriado, feedback auditivo, mantendo clareza, consistência e relevância na experiência do usuário. |
| **Dependência:** | Testar regularmente a eficácia com avaliações de usuários, adaptar a necessidades específicas. |
| **Prioridade:** | Alta |
| **Conflitos:** | nenhum |
| **História:** | 05/12/2023 |

Fonte: MARQUES,maria. 2023.

</center>

<center>

Tabela 6 - Cartão de especificação da Usabilidade

| **Nº Requisito: 4** <a id="REF04" href="#anchor_a4">(USAB04)</a>  <br> **Classificação:** Usabilidade/Suporte | |
| ------------------------ | --------- |
| **Descrição:** |  O aplicativo deve ser acessível a usuários com deficiências, seguindo as diretrizes de acessibilidade relevantes. |
| **Justificativa:** | Garantir acessibilidade no aplicativo é essencial para promover inclusão, proporcionando uma experiência equitativa para usuários com diferentes habilidades. |
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | O aplicativo deve seguir diretrizes de acessibilidade, ser compatível com tecnologias assistivas, oferecer contraste adequado, navegação simplificada e alternativas para mídia. |
| **Dependência:** | Realizar testes com usuários diversos e manter atualizações conforme mudanças nas diretrizes e tecnologias de acessibilidade. |
| **Prioridade:** | Alta |
| **Conflitos:** | nenhum |
| **História:** | 05/12/2023 |

Fonte: MARQUES,maria. 2023.

</center>

<center>

Tabela 7 - Cartão de especificação da Usabilidade

| **Nº Requisito: 5** <a id="REF05" href="#anchor_a5">(USAB05)</a>  <br> **Classificação:** Usabilidade/Consistência | |
| ------------------------ | --------- |
| **Descrição:** | As atualizações de status ou notificações devem ser apresentadas de maneira não intrusiva, mantendo a experiência do usuário fluida.|
| **Justificativa:** | É essencial para preservar a fluidez da experiência do usuário, proporcionando um ambiente de uso agradável.|
| **Origem:** | Especificação Suplementar  |
| **Critério de aceitação:** | Apresentar atualizações de forma discreta, oferecer opções de personalização, evitar interrupções excessivas e fornecer feedback oportuno. |
| **Dependência:** | Realizar testes com usuários e manter feedback contínuo para ajustar as notificações com base nas preferências e experiências dos usuários. |
| **Prioridade:** | Alta |
| **Conflitos:** | nenhum |
| **História:** | 05/12/2023 |

Fonte: MARQUES,maria. 2023.

</center>

<center>

Tabela 8 - Cartão de especificação da Usabilidade

| **Nº Requisito: 6** <a id="REF06" href="#anchor_a6">(USAB06)</a>  <br> **Classificação:** Usabilidade | |
| ------------------------ | --------- |
| **Descrição:** | A interface do aplicativo deve ser intuitiva, proporcionando uma experiência fácil para todos os usuários. |
| **Justificativa:** | Assegurar uma interface intuitiva é essencial para proporcionar uma experiência de usuário acessível e satisfatória, promovendo a usabilidade do aplicativo.|
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | Garantir uma navegação lógica, uso de ícones e rótulos claros, feedback imediato, apresentação clara de informações e realizar testes de usabilidade. |
| **Dependência:** | Manter feedback contínuo dos usuários para ajustar a interface conforme necessário e realizar avaliações com uma diversidade de usuários para garantir acessibilidade universal. |
| **Prioridade:** | Alta |
| **Conflitos:** | nenhum |
| **História:** | 05/12/2023 |

Fonte: MARQUES,maria. 2023.

</center>

### Cartões de especificação do NFR02 - Confiabilidade

<center>

Tabela 9 - Cartão de especificação de Confiabilidade 

| **Nº Requisito: 7**  <a id="REF1" href="#anchor_c1">(CONF01)</a>   <br> **Classificação:** Confiabilidade/Disponibilidade para uso  | |
| ------------------------ | --------- |
| **Descrição:** | Garantir 99,9% de disponibilidade de tempo, principalmente durante períodos eleitorais, evitando interrupções não programadas. |
| **Justificativa:** | É utilizado esse requisito, pois durante os momentos de alta demanda, interrupções não programadas podem comprometer a transparência do aplicativo e prejudicar a confiança do público.  |
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | Durante testes, o sistema deve demonstrar uma disponibilidade mínima de 99,9% durante períodos simulados de alta demanda, como os observados em períodos eleitorais. |
| **Dependência:** | Nenhum |
| **Prioridade:** | Alta |
| **Conflitos:** | Nenhum |
| **História:** | 05/11/2023 |


Fonte: BARBOSA, maria. 2023.

</center>

<center>

Tabela 10 - Cartão de especificação de Confiabilidade 

| **Nº Requisito: 8**  <a id="REF2" href="#anchor_c2">(CONF02)</a>   <br> **Classificação:**  Confiabilidade/Tolerância a falhas | |
| ------------------------ | --------- |
| **Descrição:** | Implementar backups regulares e procedimentos de recuperação eficazes para evitar perda significativa de dados em falhas inesperadas. |
| **Justificativa:** | É fundamental para garantir a preservação e a disponibilidade contínua dos dados, prevenindo perdas catastróficas e assegurando a rápida recuperação em casos de falhas ou eventos inesperados. |
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** |  O sistema do aplicativo deve ser capaz de recuperar dados a partir de backups recentes em um tempo estabelecido. <br> Os backups devem ser realizados automaticamente em intervalos regulares conforme definido na política de backup, garantindo a retenção de dados |
| **Dependência:** | Nenhum |
| **Prioridade:** | Alta |
| **Conflitos:** | Nenhum |
| **História:** | 05/11/2023 |

Fonte: BARBOSA, maria. 2023.

</center>

<center>

Tabela 11 - Cartão de especificação de Confiabilidade 

| **Nº Requisito: 9**  <a id="REF3" href="#anchor_d1">(DES01)</a>  <br> **Classificação:** Confiabilidade/Tempo de resposta  | |
| ------------------------ | --------- |
| **Descrição:** | Manter um tempo de resposta inferior a 2 segundos para interações do usuário, assegurando uma experiência ágil. |
| **Justificativa:** | É essencial para garantir uma experiência de usuário ágil, favorecendo a interação contínua e minimizando a frustração com possíveis atrasos, mantendo uma confiabilidade no aplicativo. |
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | Deve demonstrar um tempo de resposta médio para interações do usuário inferior a 2 segundos, assegurando uma experiência fluida. |
| **Dependência:** | Nenhum |
| **Prioridade:** | Alta |
| **Conflitos:** | Nenhum |
| **História:** | 05/11/2023 |

Fonte: BARBOSA, maria. 2023.

</center>

<center>

Tabela 12 - Cartão de especificação de Confiabilidade 

| **Nº Requisito: 10**  <a id="REF4" href="#anchor_s3">(SUP03)</a> <br> **Classificação:** Confiabilidade/Suporte ao usuário  | |
| ------------------------ | --------- |
| **Descrição:** | No sistema deve haver um plano de suporte ao usuário para responder a dúvidas e problemas de forma eficaz. |
| **Justificativa:** | Um plano de suporte eficaz fortalece a confiabilidade do sistema ao garantir respostas rápidas e soluções para problemas, assegurando a continuidade e a confiança dos usuários na plataforma. |
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | As consultas e problemas reportados pelos usuários devem ser respondidos e resolvidos, garantindo um plano de suporte eficaz. |
| **Dependência:** | Nenhum |
| **Prioridade:** | Alta |
| **Conflitos:** | Nenhum |
| **História:** | 05/11/2023 |

Fonte: BARBOSA, maria. 2023.

</center>


## Cartões de especificação do NFR03 - Segurança

<center>

Tabela 13 - Cartão de especificação de Segurança 

| **Nº Requisito: 11**  <a id="REF5" href="#anchor_c3">(CONF03)</a> <br> **Classificação:** Segurança/Proteção dos dados  | |
| ------------------------ | --------- |
| **Descrição:** | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança, como por exemplo: login por meio da biometria digital. |
| **Justificativa:** | Ajuda na proteção dos dados do usuário, promovendo uma experiência mais segura e confiável no aplicativo. |
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | Deve garantir a autenticação, atestando a proteção dos dados do usuário contra acessos não autorizados. <br> Deve haver etapas de segurança.|
| **Dependência:** | Nenhum |
| **Prioridade:** | Alta |
| **Conflitos:** | Nenhum |
| **História:** | 05/11/2023 |

Fonte: BARBOSA, maria. 2023.

</center>

<center>

Tabela 14 - Cartão de especificação de Segurança 

| **Nº Requisito: 12**  <a id="REF6" href="#anchor_c4">(CONF04)</a> <br> **Classificação:** Segurança/Proteção dos dados  | |
| ------------------------ | --------- |
| **Descrição:** | O usuário deve poder alterar os seus dados pessoais caso desejar. |
| **Justificativa:** | Permitir que o usuário altere seus dados pessoais promove autonomia, controle e conformidade com regulamentações de privacidade, garantindo uma experiência personalizada e transparente reforçando a confiabilidade no aplicativo. |
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | deve permitir que o usuário modifique suas informações pessoais de forma intuitiva e segura, refletindo as atualizações realizadas. |
| **Dependência:** | Nenhum |
| **Prioridade:** | Alta |
| **Conflitos:** | Nenhum |
| **História:** | 05/11/2023 |

Fonte: BARBOSA, maria. 2023.

</center>

<center>

Tabela 15 - Cartão de especificação de Segurança 

| **Nº Requisito: 13**  <a id="REF7" href="#anchor_c5">(CONF05)</a> <br> **Classificação:** Segurança/Autenticidade dos documentos  | |
| ------------------------ | --------- |
| **Descrição:** | O aplicativo deve oferecer segurança ao usuário, em relação aos dados emitidos nos documentos, certificando e garantindo que estão corretos. |
| **Justificativa:** | Assegurar a segurança dos dados presentes nos documentos do usuário é crucial para garantir a precisão, autenticidade e integridade das informações, fortalecendo a confiabilidade e a credibilidade do aplicativo. |
| **Origem:** | Especificação Suplementar |
| **Critério de aceitação:** | Deve ser verificável e precisamente certificar a exatidão dos dados presentes nos documentos dos usuários, mantendo sua integridade e assegurando proteção contra manipulações não autorizadas. |
| **Dependência:** | Nenhum |
| **Prioridade:** | Alta |
| **Conflitos:** | Nenhum |
| **História:** | 05/11/2023 |

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
| 2.0 | 05/12/2023 | Correção em cartões de especificação de confiabilidade e segurança e correção na imagem do SIG sem impacto de confiabilidade |  [Maria Barbosa](https://github.com/Madu01)  | [João Costa ](https://github.com/jvcostta) |
| 2.1  | 05/12/2023  | Adição dos cartões da usabilidade | [Maria Marques ](https//github.com/EduardaSMarques)  | [João Victor](https//github.com/jvcostta) |

