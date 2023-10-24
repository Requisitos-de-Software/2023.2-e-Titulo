# 1. Introdução:

## 1.1 Finalidade:
O presente documento tem como objetivo fornecer uma estrutura abrangente para o desenvolvimento e utilização do aplicativo "e-título", visando facilitar o acesso e a gestão de informações relacionadas à participação cidadã em processos eleitorais.

## 1.2 Escopo: 
Este documento abrange todas as características, requisitos e funcionalidades do aplicativo "e-título". Define seus limites, especificando as áreas cobertas e excluídas no contexto da experiência do usuário e das funcionalidades eleitorais.

## 1.3 Definições, Acrônimos e Abreviações:
Para garantir uma compreensão uniforme, algumas definições importantes, acrônimos e abreviações são apresentados abaixo:
- **e-título:** Aplicativo eletrônico para dispositivos móveis que visa oferecer serviços eleitorais de forma digital.
- **TSE:** Tribunal Superior Eleitoral, a instância máxima da justiça eleitoral no Brasil.
- **CPF:** Cadastro de Pessoa Física, documento de identificação fiscal no Brasil.

## 1.4 Referências:
As informações contidas neste documento baseiam-se nas diretrizes fornecidas pelo TSE, nas melhores práticas de desenvolvimento de aplicativos móveis e nas normativas eleitorais vigentes.

## 1.5 Visão Geral:
O "e-título" surge como uma solução inovadora para modernizar e simplificar a participação eleitoral, oferecendo aos cidadãos uma plataforma intuitiva e segura para acessar informações relevantes, como local de votação, situação cadastral e documentos eleitorais. Esta visão geral delineia os principais elementos do aplicativo, destacando seu papel na promoção da cidadania digital e na facilitação do exercício do voto.

| Aplicativo    | Versão do Aplicativo |  Documento                | Data       |
|---------------|----------------------|---------------------------|------------|
|  e-Título     |         2.6.2        | Especificação Suplementar | 23/10/2023 |

# 2. Metodologia:

A definição dos requisitos foi elaborada com base no modelo FURPS+, que se relaciona a um sistema para a categorização de requisitos (*QualidadeBR, 2008*).

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

# 3. Funcionalidade:

Os requisitos funcionais estão definidos por meio dos Casos de uso, listados na Tabela 1.

<details>
   <summary>Tabela 1 - requisitos funcionais </summary>

   **Legenda da Tabela 1:**

- RFx: Requisito Funcional nºx
- BSx: Requisito funcionais nºx elicitado pelo Brainstorming
- Na coluna de Implementado, informa se o requisito em específico está presente ou não no aplicativo

<center>

| <a id="anchor_BS" style="color:black;">ID</a> | Descrição                                                                          | Código | Implementado |
| ---------------------------------------------- | ---------------------------------------------------------------------------------- | ------ | :------: |
| BS1                                            |  No aplicativo deve ser possível realizar o cadastro do usuário    | RF1    |    Sim      |
| BS2                                            |  Deve ser possível o usuário realizar o login por senha ou biometria para acessar o aplicativo, com a condição de já ter se cadastrado | RF2    |      Sim    |
| BS3                                            | Deve ser possível realizar a emissão do Título do usuário no aplicativo | RF3    |     Sim     |
| BS4                                            | No aplicativo deve ser possível o usuário acessar o QR Code para a leitura do seu título  | RF4    |   Sim       |
| BS5                                            | No aplicativo deve ser possível o usuário vizualizar a localização do Local de Votação         | RF5    |     Sim     | 
| BS6                                            | No aplicativo deve possível o usuário receber notificações        | RF6    |    Sim      |
| BS7                                            | No aplicativo deve ser possível o usuário vizualizar os termos de uso      | RF7    |    Sim      |
| BS8                                            | No aplicativo deve ser possível o usuário concordar ou não com os termos de uso    | RF8    |    Sim      | 
| BS9                                            | No aplicativo deve ser possível o usuário trocar a senha      | RF9    |      Sim    | 
| BS10                                            | No aplicativo deve ser possível o usuário realizar a recuperação da senha   | RF10    |    Sim      |
| BS11                                           | O aplicativo deve disponibilizar ao usuário realizar a atualização de suas informações pessoais por meio do site do TSE | RF11    |   Sim       | 
| BS12                                            | Deve ser possível o usuário visualizar as dúvidas frequentes do aplicativo            | RF12    |    Sim      | 
| BS13                                           | O aplicativo deve disponibilizar ao usuário a função de acessar o site do TSE para conseguir relatar feedbacks e problemas do aplicativo  | RF13    |    Sim      | 



</center>

   <div style="text-align: center">
      <p> Tabela 1: Requisitos funcionais (Fonte: Autor, 2023).</p>
   </div>
</details>

## 3.1 Requisitos não Funcionais:
Os requisitos não funcionais estabelece critérios que não estão relacionados diretamente às funções do sistema, como desempenho, confiabilidade e segurança, listaods na tebela 2.

<details>
   <summary>Tabela 2 - requisitos naõ funcionais </summary>
  
**Legenda da Tabela 2:**

- RNFx: Requisito Não-Funcional nºx
- BSNx: Requisito não funcionais nºx elicitado pelo Brainstorming
- Na coluna de Implementado, informa se o requisito em específico está presente ou não no aplicativo
  
<center>

| <a id="anchor_BSNF" style="color:black;">ID</a> | Descrição                                                                         | Código | Implementado |
| ----------------------------------------------- | --------------------------------------------------------------------------------- | ------ | :------: |
| BSNF1                                          | O aplicativo deve permitir apenas usuários acima de 16 anos, por serem aptos a votar | RNF1   |     Sim     |
| BSNF2                                          |  O aplicativo deve contribuir para a transparência e Eficiência das Eleições com os dados das eleições sendo disponíveis para os usuários | RNF2   |   Não       |
| BSNF3                                          |  O aplicativo deve ser confiável para o usuário | RNF3   |    Sim      |
| BSNF4                                          |  Para o aplicativo ser utilizado, o dispositivo que mantém ele instalado deve precisar ter acesso a internet | RNF4   |      Sim    |
| BSNF5                                          |  O aplicativo deve oferecer um meio de ajuda para os usuários que não entenderam alguma coisa de sua utilidade | RNF5   |     Sim     |


</center>

   <div style="text-align: center">
      <p> Tabela 9: Requisitos não funcionais (Fonte: Autor, 2023).</p>
   </div>
</details>

# 4. Usabilidade:

Aborda a facilidade de uso do sistema, incluindo interface do usuário e experiência do usuário litados na Tabela 3.

**Legenda da Tabela 3:**

- Identificador: Usab0x
- Descrição: Informa qual o requisito em específico foi elicitado

<font size="3"><p style="text-align: center">**Tabela 3 - requisitos de usabilidade** </p></font>

<center>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES01`  | O usuário deve se cadastrar. |

</center>

<font size="3"><p style="text-align: center">**Fonte:** Autor, 2023.</p></font>

# 5. Confiabilidade:

Explora a capacidade do sistema em ser confiável, estável e resistente a falhas, listados na Tabela 4.

**Legenda da Tabela 4:**

- Identificador: Conf0X
- Descrição: Informa qual o requisito em específico foi elicitado

<font size="3"><p style="text-align: center">**Tabela 4 - requisitos de confiabilidade** </p></font>

<center>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES01`  | O usuário deve se cadastrar. |

</center>

<font size="3"><p style="text-align: center">**Fonte:** Autor, 2023.</p></font>

# 6. Desempenho:

Define os requisitos de desempenho esperados do sistema, como velocidade, eficiência e capacidade listados na Tabela 5.

**Legenda da Tabela 5:**

- Identificador: Des0X
- Descrição: Informa qual o requisito em específico foi elicitado

<font size="3"><p style="text-align: center">**Tabela 5 - requisitos de desempenho** </p></font>

<center>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES01`  | O usuário deve se cadastrar. |

</center>

<font size="3"><p style="text-align: center">**Fonte:** Autor, 2023.</p></font>

# 7. Suportabilidade:

Avalia a facilidade com que o sistema pode ser mantido e suportado ao longo do tempo listados na Tabela 6.

**Legenda da Tabela 6:**

- Identificador: Sup0X
- Descrição: Informa qual o requisito em específico foi elicitado.

<font size="3"><p style="text-align: center">**Tabela 6 - requisitos de suportabilidade** </p></font>

<center>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES01`  | O usuário deve se cadastrar. |

</center>

<font size="3"><p style="text-align: center">**Fonte:** Autor, 2023.</p></font>

# 8. Restrições de Design:

Estabelece limitações ou restrições específicas listados na Tabela 7, que devem ser consideradas durante o design do sistema.

**Legenda da Tabela 7:**

- Identificador: RD0X
- Descrição: Informa qual o requisito em específico foi elicitado.

<font size="3"><p style="text-align: center">**Tabela 7 - requisitos de restrições de design** </p></font>

<center>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES01`  | O usuário deve se cadastrar. |

</center>

<font size="3"><p style="text-align: center">**Fonte:** Autor, 2023.</p></font>

# 9. Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line:

Especifica os requisitos para a documentação do usuário e sistemas de ajuda online listados na Tabela 8.

**Legenda da Tabela 8:**

- Identificador: SADU0X
- Descrição: Informa qual o requisito em específico foi elicitado.

<font size="3"><p style="text-align: center">**Tabela 8 - requisitos de sistema de ajuda e de documentação de usuário on-line** </p></font>

<center>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES01`  | O usuário deve se cadastrar. |

</center>

<font size="3"><p style="text-align: center">**Fonte:** Autor, 2023.</p></font>

# 10. Componentes Adquiridos:

Identifica os componentes que serão adquiridos de fontes externas em vez de serem desenvolvidos internamente como listados na Tabela 9.

**Legenda da Tabela 9:**

- Identificador: CA0X
- Descrição: Informa qual o requisito em específico foi elicitado.

<font size="3"><p style="text-align: center">**Tabela 9 - requisitos de componentes adquiridos:** </p></font>

<center>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES01`  | O usuário deve se cadastrar. |

</center>

<font size="3"><p style="text-align: center">**Fonte:** Autor, 2023.</p></font>

# 11. Interfaces:

## 11.1 Interfaces do Usuário:
Descreve como os usuários interagem com o sistema.

## 11.2 Interfaces de Hardware:
Especifica como o sistema interage com hardware externo.

## 11.3 Interfaces de Software:
Define como o sistema se integra a outros softwares.

## 11.4 Interfaces de Comunicação:
Detalha os requisitos para comunicação entre diferentes partes do sistema.

# 12. Requisitos de Licenciamento:

Esclarece os requisitos relacionados a licenças de software, propriedade intelectual ou outros acordos legais.

# 13. Observações Legais, de Copyright e Outras:

Inclui informações legais relevantes para o uso, distribuição e propriedade do sistema.

# 14. Padrões Aplicáveis:

Especifica os padrões relevantes que devem ser seguidos durante o desenvolvimento e implementação do sistema.

## Referências Bibliográficas


## Bibliografia


## Histórico de Versões

| Versão | Data       | Descrição                            | Autor(es)                                      | Revisor(es)                                    |
| ------ | ---------- | ------------------------------------ | ---------------------------------------------- | ---------------------------------------------- |
| 1.0 | 26/09/2023 | Motagem de estrutura com explicação, adicionando introdução completa, metodologia, modelo de resposta da Funcionalidade, e estrutura de tabela nos tópicos nescessário. | [Esther Sena](https://github.com/esmsena) |  |
