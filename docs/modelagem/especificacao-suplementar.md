# 1. Introdução:

Este documento, datado de 23/10/2023, fornece uma estrutura abrangente para o desenvolvimento e utilização do aplicativo "e-título" (versão 2.6.2). O objetivo é facilitar o acesso e a gestão de informações relacionadas à participação cidadã em processos eleitorais. O escopo abrange todas as características, requisitos e funcionalidades do aplicativo, definindo claramente seus limites. São apresentadas definições, acrônimos e abreviações, incluindo o significado do termo "e-título". As informações são fundamentadas nas diretrizes do TSE, nas melhores práticas de desenvolvimento de aplicativos móveis e nas normativas eleitorais. A visão geral destaca o "e-título" como uma solução inovadora para modernizar e simplificar a participação eleitoral, promovendo a cidadania digital e facilitando o exercício do voto.

# 2. Motivação e Objetivo:

Esse artefato de especificação suplementar é como um mapa do tesouro para os desenvolvedores. Ele não apenas fornece direções técnicas, mas também inspira e esclarece. A motivação é transformar requisitos em uma obra-prima funcional, enquanto o objetivo é ser claro, preciso e inspirador, guiando os desenvolvedores na construção de algo extraordinário. Cada palavra deve ser uma faísca de criatividade, transformando códigos em magia e prometendo uma experiência que deixará uma marca duradoura.


# 3. Metodologia:

A definição dos requisitos foi elaborada com base no modelo FURPS+, que se relaciona a um sistema para a categorização de requisitos (*QualidadeBR, 2008*) com base no conhecimento adquirido na referência  <a id=anchor_4 href="#REF4">[1]</a>.

O acrônimo FURPS+ representa categorias que são aplicáveis na especificação de requisitos.

- *F - Funcionalidade:* Abrange todos os aspectos funcionais do software, ou seja, os requisitos já delineados nos casos de uso.

- *U - Usabilidade:* Refere-se ao atributo que avalia a interação com o usuário, em conformidade com os princípios de usabilidade propostos por Nielsen (*PREECE; ROGERS; SHARP; 2005, p. 48-49*); "Quão fácil é para o usuário realizar suas tarefas por meio do software?".

- *R - Confiabilidade:* Relaciona-se à integridade, conformidade e interoperabilidade do software. Os requisitos nessa categoria podem incluir aspectos como frequência e gravidade de falhas, tempo médio entre falhas e capacidade de recuperação.

- *P - Desempenho:* Avalia os requisitos de desempenho do software, utilizando medidas como tempo de resposta, consumo de memória e disponibilidade da aplicação.

- *S - Suportabilidade:* Agrupa requisitos relacionados a características como testabilidade, adaptabilidade, manutenibilidade, compatibilidade, escalabilidade, localizabilidade, entre outros.

- *"+":* Este símbolo no acrônimo incorpora outros requisitos não-funcionais que devem ser considerados, tais como:

    - *Requisitos de Design:* Muitas vezes denominados restrições de design, incluindo, por exemplo, o uso de ferramentas de desenvolvimento.
    
    - *Requisitos de Implementação:* Especificam ou restringem o código ou a construção do sistema, como padrões obrigatórios ou linguagens de implementação.
    
    - *Requisitos de Interface:* Especificam ou restringem as funcionalidades inerentes à interface do sistema com o usuário.
    
    - *Requisitos Físicos:* Especificam limitações físicas impostas pelo hardware, como material, forma, tamanho ou peso.

Nessa versão os requisitos de interface, além da seção de componentes adquiridos serão omitidos, dado que são atributos já especificados em outros artefatos, como os requisitos não-funcionais elicitados pelas técnicas de [Entrevista](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/) de [Introspecção](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/), de [Questionário](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/) e de [Brainstorming](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/).

# 4. Funcionalidade:

Os requisitos funcionais estão definidos por meio dos Casos de uso.

# 5. Usabilidade:

Aborda a facilidade de uso do sistema, incluindo interface do usuário e experiência do usuário litados na Tabela 1.

**Legenda da Tabela 1:**

- Identificador: USABxx
- Descrição: Informa qual o requisito em específico foi elicitado

**Tabela 1 - requisitos de usabilidade**

| ID         | Descrição        | 
|------------|------------------|
|  `USAB01`  | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo    |    
|  `USAB02`  | O design deve garantir uma navegação clara e eficiente, facilitando a localização de funcionalidades pelos usuários.  |    
|  `USAB03`  | Todas as interações do usuário devem ser acompanhadas por feedback visual ou auditivo para fornecer orientação imediata.     |    
|  `USAB04`  | O aplicativo deve ser acessível a usuários com deficiências, seguindo as diretrizes de acessibilidade relevantes.   |    
|  `USAB05`  | As atualizações de status ou notificações devem ser apresentadas de maneira não intrusiva, mantendo a experiência do usuário fluida. | 
|  `USAB06`  | A interface do aplicativo deve ser intuitiva, proporcionando uma experiência fácil para todos os usuários.  |    

<div style="text-align: center">
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.</p>
</div>

# 5. Confiabilidade:

Explora a capacidade do sistema em ser confiável, estável e resistente a falhas, listados na Tabela 2.

**Legenda da Tabela 2:**

- Identificador: CONFxx
- Descrição: Informa qual o requisito em específico foi elicitado

**Tabela 2 - requisitos de confiabilidade**

| ID         | Descrição        | 
|------------|------------------|
|  `CONF01`  | Garantir 99,9% de disponibilidade de tempo, principalmente durante períodos eleitorais, evitando interrupções não programadas. |    
|  `CONF02`  | Implementar backups regulares e procedimentos de recuperação eficazes para evitar perda significativa de dados em falhas inesperadas.|
|  `CONF03`  | O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança, como por exemplo; login por meio da biometria digital.|  
|  `CONF04`  | O usuário deve poder alterar os seus dados pessoais caso desejar.| 
|  `CONF05`  | O aplicativo deve oferecer segurança ao usuário, em relação aos dados emitidos nos documentos, certificando e garantindo que estão corretos. | 


<div style="text-align: center">
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.</p>
</div>

# 6. Desempenho:

Define os requisitos de desempenho esperados do sistema, como velocidade, eficiência e capacidade listados na Tabela 3.

**Legenda da Tabela 3:**

- Identificador: DESxx
- Descrição: Informa qual o requisito em específico foi elicitado

**Tabela 3 - requisitos de desempenho** 

| ID         | Descrição        | 
|------------|------------------|
|  `DES01`  | Manter um tempo de resposta inferior a 2 segundos para interações do usuário, assegurando uma experiência ágil. |  
|  `DES02`  | O sistema deve ser capaz de lidar com um aumento de 50% no tráfego de usuários simultâneos durante o período eleitoral.  |  

<div style="text-align: center">
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.</p>
</div>

# 7. Suportabilidade:

Avalia a facilidade com que o sistema pode ser mantido e suportado ao longo do tempo, além de suporte ao usuário listados na Tabela 4.

**Legenda da Tabela 4:**

- Identificador: SUPxx
- Descrição: Informa qual o requisito em específico foi elicitado.

**Tabela 4 - requisitos de suportabilidade**

| ID         | Descrição        | 
|------------|------------------|
|  `SUP01`  | O sistema deve ser compatível com versões anteriores, garantindo que os usuários possam migrar para novas versões sem problemas.|    
|  `SUP02`  | O sistema deve ser projetado para permitir a adição de novos recursos ou funcionalidades sem alterações significativas no código existente.|  
|  `SUP03`  | O sistema deve ser compatível com padrões de segurança reconhecidos, como o ISO 27001.|    
|  `SUP03`  | O sistema deve haver um plano de backup e recuperação bem definido para proteger os dados e garantir a recuperação em caso de falhas.|  
|  `SUP03`  | No sistema deve haver um plano de suporte ao usuário para responder a dúvidas e problemas de forma eficaz.|    

<div style="text-align: center">
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.</p>
</div>

# 8. Restrições de Design :

O aplicativo "e-Título", desenvolvido pelo Tribunal Superior Eleitoral (TSE) do Brasil, está sujeito a várias restrições de design para garantir sua usabilidade, acessibilidade, segurança e conformidade com padrões governamentais. Essas restrições incluem a necessidade de design responsivo, acessibilidade para pessoas com deficiências, proteção de dados e segurança robusta, conteúdo oficial e atualizado, além de integração com sistemas oficiais e identidade visual governamental. O aplicativo também deve priorizar a privacidade dos dados, fornecer suporte técnico eficaz, notificações responsáveis e proteção contra fraudes. Essas medidas são essenciais para garantir a confiabilidade e a integridade das informações eleitorais e a segurança dos eleitores.

# 9. Requisitos de Licenciamento:

O sistema deve restringir o uso através de termos de uso.

# 10. Requisitos de Implementação:

Relaciona-se aos requisitos de hardware e dispositivos nos quais o aplicativo será executado, garantindo que seja otimizado para diferentes plataformas, como smartphones Android e iOS, e que atenda a requisitos mínimos de hardware para funcionar de maneira eficaz, mostrados na Tabela 5.

**Legenda da Tabela 5:**

- Identificador: FISxx
- Descrição: Informa qual o requisito em específico foi elicitado.

**Tabela 5 - requisitos de Implementação**

| ID         | Descrição        | 
|------------|------------------|
|  `FIS01`  | O aplicativo deve ser otimizado para funcionar em dispositivos com configurações de hardware mínimas, assegurando uma ampla base de usuários. |  
|  `FIS01`  | Os dispositivos deverão ter acesso a internet para acessar o aplicativo. |  
|  `FIS01`  | O software necessário para a compatibilidade é Android 6.0 ou superior, e a versão do IOS 3.0 ou superior. |  

<div style="text-align: center">
<p> Fonte: SENA, Esther; SIQUEIRA, Mariiana. 2023.</p>
</div>

# 11. Requisitos físicos:

O sistema deve funcionar em tablets e smartphones com loja de aplicativo online.

## Referências Bibliográficas

> <a id=anchor_4 href="#REF4">[1]</a>  FURPS+. Disponivél em: <https://qualidadebr.wordpress.com/2008/07/10/furps/>. Acesso em: 23 de outubro de 2023.

> MINISTÉRIO DA CIÊNCIA, TECNOLOGIA, INOVAÇÕES E COMUNICAÇÕES. Especificação Suplementar. Disponível em: <https://aprender3.unb.br/pluginfile.php/2754631/mod_resource/content/2/SiglaProjeto_EspecificacaoSuplementar.pdf>. Acesso em: 23 out 2023.

> GOIS, Samily Rocha, SOBRINHO, Francisco Luiz. Projeto de Software Floricultura Beija-Flor: Especificação Suplementar. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692808/mod_resource/content/1/Especificacao_Suplementar_Exemplo.pdf>. Acesso em: 23 out 2023.

> 2023.1-BilheteriaDigital, Especificação Suplementar. 12 mai 2023. Disponível em: <https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital/blob/main/docs/modelagem/especificacao-suplementar.md>. Acesso em: 24 out 2023.

> 2022.1-TikTok, Especificação Suplementar. 19 jul 2022. Disponível em: <https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/modelagem/especificao-suplementar.md>. Acesso em: 24 out 2023.

## Histórico de Versões

| Versão | Data       | Descrição        | Autor(es)      | Revisor(es)    |
| ------ | ---------- | -----------------| -------------- | -------------- |
| `1.0` | 26/09/2023 | Montagem de estrutura com explicação, adicionando introdução completa, metodologia, modelo de resposta da Funcionalidade, e estrutura de tabela nos tópicos nescessário. | [Esther Sena](https://github.com/esmsena) e  [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
| `1.1` | 24/10/2023 | Montagem das tabelas de Usabilidade, Confiabilidade, Desempenho, Suportabilidade, Restrições de Design, Requisitos de Licenciamento e Requisitos Físicos | [Mariiana Siqueira](https://github.com/Maryyscreuza) e [Esther Sena](https://github.com/esmsena)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
| `1.2` | 24/10/2023 | Adição de referências bibliográficas | [Mariiana Siqueira](https://github.com/Maryyscreuza) e [Esther Sena](https://github.com/esmsena)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
| `1.3` | 30/11/2023 | Correção em fontes das tabelas, refazendo a Introdução, adicionando Motivação e Objetivo adicionando descrição na metodologia e referênciando ela. |  [Esther Sena](https://github.com/esmsena)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
| `1.3` | 01/12/2023 | Adicionando requisitos em confiabilidade (CONF04 e CONF05) e alterando os requisitos fisicos para de implementação e add outra descrição de requisitos físicos. |  [Esther Sena](https://github.com/esmsena)  | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
