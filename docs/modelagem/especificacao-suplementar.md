# 1. Introdução:

| Aplicativo    | Versão do Aplicativo |  Documento                | Data       |
|---------------|----------------------|---------------------------|------------|
|  e-Título     |         2.6.2        | Especificação Suplementar | 23/10/2023 |

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

# 4. Usabilidade:

Aborda a facilidade de uso do sistema, incluindo interface do usuário e experiência do usuário litados na Tabela 3.

**Legenda da Tabela 3:**

- Identificador: USABxx
- Descrição: Informa qual o requisito em específico foi elicitado

**Tabela 3 - requisitos de usabilidade**

| ID         | Descrição                                                                               |
|------------|-----------------------------------------------------------------------------------------|
|  `USAB01`  | No aplicativo o usuário deve realizar seu cadastro.                                     | 
|  `USAB02`  | No aplicativo o usuário deve emitir título de eleitor.                                  |
|  `USAB03`  | No aplicativo o usuário deve acessar QR Code para leitura do título.                    |
|  `USAB04`  | No aplicativo o usuário deve visualizar o local de votação.                             |
|  `USAB05`  | No aplicativo o usuário deve receber notificação.                                       |
|  `USAB06`  | No aplicativo o usuário deve ter a opção de sair do aplicativo.                         |
|  `USAB07`  | No aplicativo o usuário deve conseguir fazer alterações em seu cadastro.                |
|  `USAB08`  | No aplicativo o usuário deve realizar quitação eleitoral.                               |
|  `USAB09`  | No aplicativo o usuário deve informar a justificativa no aplicativo.                    |
|  `USAB10`  | No aplicativo o usuário deve conseguir alterar foto do título.                          |
|  `USAB11`  | No aplicativo o usuário deve acompanhar a apuração de votos.                            |
|  `USAB12`  | No aplicativo o usuário deve visualizar o candidato eleito referente ao ano da votação. |

**Fonte:** NERIS, Mariiana 2023.

# 5. Confiabilidade:

Explora a capacidade do sistema em ser confiável, estável e resistente a falhas, listados na Tabela 4.

**Legenda da Tabela 4:**

- Identificador: CONFxx
- Descrição: Informa qual o requisito em específico foi elicitado

**Tabela 4 - requisitos de confiabilidade**

| ID         | Descrição   |
|------------|----------|
|  `CONF01`  | No aplicativo o usuário deve realizar o login por senha ou biometria para acessá-lo, com a condição de já ter se cadastrado |
|  `CONF02`  | No aplicativo o usuário deve realizar a recuperação da senha. |
|  `CONF03`  | No aplicativo o usuário deve ter 16 anos ou mais para acessá-lo, por ser apto a votar. |
|  `CONF04`  | No aplicativo o usuário deve visualizar a autenticidade de seus documentos. |
|  `CONF05`  | No aplicativo o usuário deve ter segurança, com a proteção nos dados, utilizando etapas de segurança. | 

**Fonte:** NERIS, Mariiana 2023.

# 6. Desempenho:

Define os requisitos de desempenho esperados do sistema, como velocidade, eficiência e capacidade listados na Tabela 5.

**Legenda da Tabela 5:**

- Identificador: DESxx
- Descrição: Informa qual o requisito em específico foi elicitado

**Tabela 5 - requisitos de desempenho** 

| ID        | Descrição                                                                                   |
|-----------|---------------------------------------------------------------------------------------------|
|  `DES01`  | O aplicativo, para ser utilizado precisa ter acesso a internet.                             |
|  `DES02`  | O aplicativo deve possuir um design intuitivo com elementos como botão e menu padronizados. |

**Fonte:** NERIS, Mariiana 2023.

# 7. Suportabilidade:

Avalia a facilidade com que o sistema pode ser mantido e suportado ao longo do tempo, além de suporte ao usuário listados na Tabela 6.

**Legenda da Tabela 6:**

- Identificador: SUPxx
- Descrição: Informa qual o requisito em específico foi elicitado.

**Tabela 6 - requisitos de suportabilidade**

| ID        | Descrição                    |
|-----------|------------------------------|
|  `SUP01`  | O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo. |
|  `SUP02`  | O aplicativo deve ter as dúvidas frequentes para o usuário acessar.|
|  `SUP03`  | O aplicativo deve possuir linkagem com o site do TSE ou outros aplicativos externos em sua navegação, assim o aplicativo possui algumas funcionalidades não sendo pertencentes a ele, mas de fora dele. |
|  `SUP04`  | O aplicativo deve oferecer suporte ao usuário. |
|  `SUP05`  | O aplicativo deve notificar o horário da votação para o usuário. |

**Fonte:** NERIS, Mariiana 2023.

# 8. Interfaces:

## 8.1 Interfaces do Usuário:
Descreve como os usuários interagem com o sistema.

## 8.2 Interfaces de Hardware:
Especifica como o sistema interage com hardware externo.

## 8.3 Interfaces de Software:
Define como o sistema se integra a outros softwares.

## 8.4 Interfaces de Comunicação:
Detalha os requisitos para comunicação entre diferentes partes do sistema.

# 9. Requisitos de Licenciamento:

Esclarece os requisitos relacionados a licenças de software, propriedade intelectual ou outros acordos legais.

# 10. Requisitos Físicos:

## Referências Bibliográficas


## Bibliografia


## Histórico de Versões

| Versão | Data       | Descrição        | Autor(es)      | Revisor(es)    |
| ------ | ---------- | -----------------| -------------- | -------------- |
| 1.0    | 26/09/2023 | Montagem de estrutura com explicação, adicionando introdução completa, metodologia, modelo de resposta da Funcionalidade, e estrutura de tabela nos tópicos nescessário. | [Esther Sena](https://github.com/esmsena) | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
| 1.1    | 24/10/2023 | Montagem das tabelas de Usabilidade, Confiabilidade, Desempenho e Suportabilidade | [Mariiana Siqueira](https://github.com/Maryyscreuza) | [Maria Barbosa](https://github.com/Madu01) e [Maria Marques ](https://github.com/EduardaSMarques) |
