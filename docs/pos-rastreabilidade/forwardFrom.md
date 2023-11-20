# Forward-From

## Introdução

O conceito de rastreabilidade, conforme definido por Klaus Pohl no livro "Requirements Engineering Fundamentals", refere-se à capacidade de acompanhar um requisito ao longo do ciclo de vida de desenvolvimento de um sistema. Sua aplicação inclui:

1. **Garantir a implementação correta dos requisitos.**
2. **Identificar e resolver conflitos entre requisitos.**
3. **Monitorar o progresso do desenvolvimento do sistema.**
4. **Documentar o histórico do sistema.**

A rastreabilidade desempenha um papel crucial na engenharia de requisitos, contribuindo para garantir que os requisitos sejam implementados corretamente e que o sistema atenda às necessidades dos usuários. 

A rastreabilidade, quando aplicada adequadamente, é uma ferramenta poderosa para aprimorar a qualidade do software. 

Existem dois tipos de rastreabilidade:

A pré-rastreabilidade desempenha o papel fundamental de permitir que os desenvolvedores identifiquem a origem dos requisitos, isto é, a qual documento ou fonte eles estão vinculados. Essa informação é crucial para compreender o contexto e a justificativa de cada requisito. Adicionalmente, a pré-rastreabilidade simplifica a identificação de inconsistências, redundâncias ou omissões nos requisitos, possibilitando correções e melhorias antes do início do desenvolvimento.

Por outro lado, a pós-rastreabilidade concentra-se em estabelecer as relações entre os requisitos e os artefatos gerados durante o desenvolvimento do software. Isso abrange a identificação de quais requisitos foram implementados em cada componente do sistema, quais casos de teste foram criados para validar esses requisitos e quais partes da arquitetura estão associadas a cada requisito. Essa informação é valiosa para garantir a consistência e a completude do sistema, além de auxiliar na manutenção e evolução do software ao longo do tempo.

No caso do presente artefato, ele representa a ratreabilidade forward-from(para frente de, a partir de) que liga requisitos a artefatos de desenho e implementação.


## Metodologia

A metodologia adotada para rastreabilidade entre requisitos e artefatos é o "forward-from", uma abordagem de pós-rastreabilidade. Isso envolve criar relações entre requisitos e artefatos gerados no desenvolvimento. No contexto da rastreabilidade entre requisitos, "forward-from" mapeia dependências, revelando se um requisito refina ou substitui outro. Isso é vital para compreender as relações entre requisitos e garantir atendimento durante o desenvolvimento. Além disso, abrange a rastreabilidade entre requisitos e artefatos de implementação, como código-fonte e testes, facilitando a identificação do que foi implementado, testado e sua relação com a arquitetura. Em resumo, "forward-from" é essencial para estabelecer relações claras, facilitando a compreensão e manutenção do software ao longo do tempo.


## Mapeamento
Para realizar o mapeamento dos requisitos, será utilizado a tabela 1 na qual contém todos os simbolos necessários para o
bom entendimento dos tópicos abaixo:

<center>

  | Legenda | Artefato |
  | ------- | ------------------------- |
  | B | Brainstorming |
  | C | Cenários |
  | E | Épico |
  | ENT | Entrevista |
  | ES | Especificação Suplementar |
  | INT | Introspecção |
  | L | Léxico |
  | P | Personas |
  | Q | Questionário |
  | RF | Requisitos Funcionais |
  | RNF | Requisitos não Funcionais |
  | ST | Storytelling |
  | UC | Casos de Uso |
  | US | Histórias de usuário |
  
</center>

## Requisitos Funcionais
A representação dos requisitos funcionais seguirão o seguinte padrão:

| Tópico                | Referência |
| :--                   | :--        |
| Épico                 | E          |
| História de usuário   | US         |
| Tema                  | Assunto    |
| Elicitação            | INT/B/C/ES/L/P/Q |
| Léxico                | L           |
| Casos de Uso          | UC          |
| funcionalidade        | Representação em imagem/video       |

<details>
  <summary>Realizar o cadastro</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E01</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US01</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT1</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS1</a>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C01</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 2: Requisito funcional 1 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Realizar login</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US01</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Segurança</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT3</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS2</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L04</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C02</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 3: Requisito funcional 2 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Emitir Título</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E02</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US02</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Dcocumento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT9</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS3</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C03</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td>
</td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 4: Requisito funcional 3 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Acessar QR code</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E02</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US02</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Documento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT10</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS4</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 5: Requisito funcional 4 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Visualizar local de votação</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E03</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Documento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT13</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS5</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L05</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/casosdeuso/">UC03</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 6: Requisito funcional 5 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Receber notificações</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E08</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT4</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS6</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L06</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/casosdeuso/">UC05</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C08</a>
        </td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 7: Requisito funcional 6 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Acesso ao termo de uso</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E04</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US04</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENTNF1</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS7/BS8</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L07</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/casosdeuso/">UC06</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C04</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 8: Requisito funcional 7 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Recuperar senha</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E05</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US05</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Segurança</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS9/BS10</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C05</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 9: Requisito funcional 8 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Sair do aplicativo</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E09</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT7</a>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L09</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 10: Requisito funcional 9 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Visualizar dúvidas frequentes</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E09</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Segurança</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT1</a></td>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS12</a>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L07</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/casosdeuso/">UC06</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 11: Requisito funcional 10 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Alterar dados cadastrais</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E05</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Documento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT2</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 12: Requisito funcional 11 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Usuários apenas acima de 16 anos</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E06</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US06</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Segurança</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BSNF1</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L01</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C06</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 13: Requisito funcional 12 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Acesso a internet para o uso</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E06</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BSNF4</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 14: Requisito funcional 13 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Realizar a quitação eleitoral</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E07</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Documento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT17</a>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L08</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/casosdeuso/">UC04</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 15: Requisito funcional 14 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Links para app/sites externos</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E10</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENTNF4</a>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 16: Requisito funcional 15 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Suporte ao usuário</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E09</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Segurança</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BSNF5</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L07</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/casosdeuso/">UC06</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 17: Requisito funcional 16 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Justificativa no app</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E07</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Documento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT19/INT20</a><td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/casosdeuso/">UC01</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 18: Requisito funcional 17 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Alterar foto do documento</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E05</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Documento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT2</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 19: Requisito funcional 18 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Autenticidade do documento</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E07</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US07</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Segurança</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT9</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C07</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 20: Requisito funcional 19 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Horário da votação</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E08</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US08</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT5</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS5</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L06</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/casosdeuso/">UC05</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C08</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 21: Requisito funcional 20 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Acompanhar apuração</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E03</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT8</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 22: Requisito funcional 21 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Visualizar candidato eleito</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E03</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US03</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT6</a>/<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT9</a>
            /<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BSNF2</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 23: Requisito funcional 22 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Proteção de dados</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E09</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US09</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Segurança</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT7</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C08</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 24: Requisito funcional 23 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>Design intuitivo</summary>

  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Épico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/#e01-cadastro">E10</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US10</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Documento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENTNF2</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C10</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 25: Requisito funcional 24 (Fonte: Autores, 2023).</p>

</details>

<br>

| Versão | Data       | Descrição                           | Autor(es)                                                                                           | Revisor(es)                                                                                                    |
| ------ | ---------- | ----------------------------------- | --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `1.0`  | 19/11/2023 | Criação da introdução, metodologia e requisitos funcionais | [Matheus Orlando](https://github.com/MateusPy) e [João Victor](https://github.com/jvcostta) | [Maria Marques](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) |
| `1.1`  | 19/11/2023 | Ajustando rastreamento | [Matheus Orlando](https://github.com/MateusPy) e [João Victor](https://github.com/jvcostta) | [Maria Marques](https://github.com/EduardaSMarques) e [Mariiana Siqueira](https://github.com/Maryyscreuza) |
