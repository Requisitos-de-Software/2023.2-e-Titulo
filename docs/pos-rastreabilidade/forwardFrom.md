# Forward-From

## Introdução

O conceito de rastreabilidade, conforme definido por Klaus Pohl no livro "Requirements Engineering Fundamentals", refere-se à capacidade de acompanhar um requisito ao longo do ciclo de vida de desenvolvimento de um sistema. Sua aplicação inclui:

1. **Garantir a implementação correta dos requisitos.**
2. **Identificar e resolver conflitos entre requisitos.**
3. **Monitorar o progresso do desenvolvimento do sistema.**
4. **Documentar o histórico do sistema.**

A rastreabilidade desempenha um papel crucial na engenharia de requisitos, contribuindo para garantir que os requisitos sejam implementados corretamente e que o sistema atenda às necessidades dos usuários. 

A rastreabilidade, quando aplicada adequadamente, é uma ferramenta poderosa para aprimorar a qualidade do software. 

## Objwtivo

Existem dois tipos de rastreabilidade:

A pré-rastreabilidade desempenha o papel fundamental de permitir que os desenvolvedores identifiquem a origem dos requisitos, isto é, a qual documento ou fonte eles estão vinculados. Essa informação é crucial para compreender o contexto e a justificativa de cada requisito. Adicionalmente, a pré-rastreabilidade simplifica a identificação de inconsistências, redundâncias ou omissões nos requisitos, possibilitando correções e melhorias antes do início do desenvolvimento.

Por outro lado, a pós-rastreabilidade concentra-se em estabelecer as relações entre os requisitos e os artefatos gerados durante o desenvolvimento do software. Isso abrange a identificação de quais requisitos foram implementados em cada componente do sistema, quais casos de teste foram criados para validar esses requisitos e quais partes da arquitetura estão associadas a cada requisito. Essa informação é valiosa para garantir a consistência e a completude do sistema, além de auxiliar na manutenção e evolução do software ao longo do tempo.

No caso do presente artefato, ele representa a ratreabilidade forward-from(para frente de, a partir de) que liga requisitos a artefatos de desenho e implementação com o objetivo de estabelecer as relações entre os requisitos e os artefatos gerados durante o desenvolvimento do software.

## Metodologia

A metodologia adotada para rastreabilidade entre requisitos e artefatos é o "forward-from", uma abordagem de pós-rastreabilidade. Isso envolve criar relações entre requisitos e artefatos gerados no desenvolvimento. No contexto da rastreabilidade entre requisitos, "forward-from" mapeia dependências, revelando se um requisito refina ou substitui outro. Isso é vital para compreender as relações entre requisitos e garantir atendimento durante o desenvolvimento. Além disso, abrange a rastreabilidade entre requisitos e artefatos de implementação, como código-fonte e testes, facilitando a identificação do que foi implementado, testado e sua relação com a arquitetura. Em resumo, "forward-from" é essencial para estabelecer relações claras, facilitando a compreensão e manutenção do software ao longo do tempo.


## Mapeamento
Para realizar o mapeamento dos requisitos, será utilizado a tabela 1 na qual contém todos os simbolos necessários para o
bom entendimento dos tópicos abaixo:

<center>

  **Tabela 1** 

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

  ></iframe>
<font size="3"><p style="text-align: center">Fonte: [João Costa](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy).</p></font>
</figure>
  
</center>

## Requisitos Funcionais
A representação dos requisitos funcionais seguirão o padrão da tabela 2:
<center>
Tabela 2

| Tópico                | Referência |
| :--                   | :--        |
| Épico                 | E          |
| História de usuário   | US         |
| Tema                  | Assunto    |
| Elicitação            | Item da tabela 1 |
| Léxico                | L           |
| Casos de Uso          | UC          |
| Funcionalidade        | Representação em imagem/video + Implementado/ Não implementado      |

></iframe>
<font size="3"><p>Fonte: [João Costa](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy).</p></font>
</figure>

</center>

A seguir estarão presentes nas tabelas 3 a 28 os requisitos funcionais de acordo com o [backlog](https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/backlog/)

<details>
  <summary> RF1 - Realizar o cadastro</summary>
<p>Tabela 3: Requisito funcional 1 </p>
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
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT1</a>,<a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS1</a>,
            <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT1</a>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href= "https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L03</a></td>
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
        <td><img src=../imgs/cadastro.jpg></td><td>Implementado</td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF2 - Realizar login</summary>
<p>Tabela 4: Requisito funcional 2.</p>
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
        <td>Funcionalidade</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT3</a>,<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS2</a>,<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/">QST04</a>
        </td>
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
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/Cenarios/">C02</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/login.jpeg></td>
      </tr>
    </tbody>
  </table>


  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF3 - Emitir Título</summary>
<p>Tabela 5: Requisito funcional 3.</p>
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
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT9</a>,<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS3</a>,<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/">ST02</a>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/emitir_titulo.jpeg>
</td>
      </tr>
    </tbody>
  </table>


  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF4 - Acessar QR code</summary>
<p>Tabela 6: Requisito funcional 4.</p>
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
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS04</a></td>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/qrcode.jpeg></td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF5 - Visualizar local de votação</summary>
<p>Tabela 7: Requisito funcional 5.</p>
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
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT4</a>,<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS5</a>,<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/questionario/">QST1</a>,<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/storytelling/">ST1</a>
        </td>
        </td>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/local_votacao.jpeg></td>
      </tr>
    </tbody>
  </table>


  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF6 - Receber notificações</summary>
<p>Tabela 8: Requisito funcional 6.</p>
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
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT4</a>,<a
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
        <td>Funcionalidade</td><td>Não implementado</td>
        <td><iframe src="https://drive.google.com/file/d/1zh9v94_KrINMAaaX4W4KMmaNkz_JLMUo/view?usp=drivesdk" width="640" height="480"></iframe>
</td>
      </tr>
    </tbody>
  </table>


  <p>Fonte Protótipo: SENA, Esther Martins - Figma, 2023.</td>
  <p>Fonte tabela: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF7 - Acesso ao termo de uso</summary>
<p>Tabela 9: Requisito funcional 7.</p>
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
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT</a>,<a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS7</a>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/termo.jpeg></td>
      </tr>
    </tbody>
  </table>


  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF8 - Recuperar senha</summary>
<p>Tabela 10: Requisito funcional 8.</p>
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
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS10</a></td>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/senha.jpeg></td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF9 - Sair do aplicativo</summary>
<p>Tabela 11: Requisito funcional 9.</p>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/sair.jpeg></td>
      </tr>
    </tbody>
  </table>


  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF10 - Visualizar dúvidas frequentes</summary>
<p>Tabela 12: Requisito funcional 10.</p>
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
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS12</a>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/ajuda_suporte.jpeg></td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF11 - Alterar dados cadastrais</summary>
<p>Tabela 13: Requisito funcional 11.</p>
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
        <td>Funcionalidade</td><td>Não Implementado</td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>


<details>
  <summary> RF12 - Realizar a quitação eleitoral</summary>
<p>Tabela 14: Requisito funcional 12.</p>
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
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT17</a>,
            <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT05</a>,
            <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">ST5</a>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/quitacao.jpeg></td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF13 - Links para app/sites externos</summary>
<p>Tabela 15: Requisito funcional 13.</p>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/links.jpeg></td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF14 - Suporte ao usuário</summary>
<p>Tabela 16: Requisito funcional 14.</p>
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
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/brainstorming/">BS</a>,
            <a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT</a>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/ajuda_suporte.jpeg></td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF15 - Justificativa no app</summary>
<p>Tabela 17: Requisito funcional 15.</p>
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
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT19</a><td>
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
        <td>Funcionalidade</td><td>Não implementada</td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF16 - Alterar foto do documento</summary>
<p>Tabela 18: Requisito funcional 16.</p>
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
        <td>Funcionalidade</td><td>Não implementada</td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF17 - Autenticidade do documento</summary>
<p>Tabela 19: Requisito funcional 17.</p>
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
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT</a></td>
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
        <td>Funcionalidade</td><td>Implementado</td>
        <td><img src=../imgs/autenticidade.jpeg></td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF18 - Horário da votação</summary>
<p>Tabela 20: Requisito funcional 18.</p>
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
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT07</a>
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
        <td>Funcionalidade</td><td>Não implementada</td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF19 - Acompanhar apuração</summary>
<p>Tabela 21: Requisito funcional 19.</p>
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
        <td>Funcionalidade</td><td>Não Implementado</td>
        <td><a href="https://youtube.com/shorts/OoPy48TFiac?si=JFCpIPgKnAZx0Kv7">Clique aqui</a></td>
      </tr>
    </tbody>
  </table>

  <td>Fonte Prototipação: João Víctor Costa Andrade, Figma -2023</td>
  <p>Fonte Tabela: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF20 - Visualizar candidato eleito</summary>
<p>Tabela 22: Requisito funcional 20.</p>
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
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/entrevista/">ENT9</a>
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
        <td>Funcionalidade</td><td>Não implementado</td>
         <td><iframe src="https://drive.google.com/file/d/1TIH55jd4XUJxzC_jXfzOp_Co5Xn987p-/view" width="640" height="480"></iframe>
        <td></td>
      </tr>
    </tbody>
  </table>

  <p>Fonte Prototipação: MARQUES, Maria Eduarda - Figma, 2023.</p>
  <p>Fonte Tabela: Orlando, Mateus e Costa, João. 2023.</p>

</details>


<details>
  <summary> RF21 - Local de partida</summary>
<p>Tabela 23: Requisito funcional 21.</p>
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
        <td>-</td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td>-</td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Documento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT14</a></td>
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
        <td>-</td>
      </tr>
      <tr>
        <td>Funcionalidade</td><td>Não Implementado</td>
         	<td><iframe src="https://drive.google.com/file/d/1P5Q_XO7-ju6cvlYcgPOuPlxFqiZjzU1f/view?usp=sharing" width="640" height="480"></iframe> </td>
        <td>
  </td>
      </tr>
    </tbody>
  </table>


  <p>Fonte Prototipação: Maria Barbosa - Figma, 2023.</p> 
  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary> RF22 - Visualizar documentação necessária</summary>
<p>Tabela 24: Requisito funcional 22.</p>
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
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/historiasdeusuario/">US08</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Documento</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/tecnicas/introspeccao/">INT15</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/lexico/">L04</a></td>
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
        <td>Funcionalidade</td><td>Não implementado</td>
        <td><iframe src="https://drive.google.com/file/d/1U1UttUA0461fHh5noAEw4TzeKkeWM62g/view?usp=drive_link" width="640" height="480"></iframe>
</td>
      </tr>
    </tbody>
  </table>


  <p>Fonte Prototipação: NERIS, Mariiana Siqueira - Figma, 2023.</p>
  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<br>


## Requisitos Não funcionais
A representação dos requisitos não funcionais seguirão o seguinte padrão da tabela 29:

<p>Tabela 29: Modelo para os requisitos não funcionais.</p>

| Tópico                | Referência |
| :--                   | :--        |
| Especificação Suplementar   | USAB, CONF, DES, SUP ou FIS |
| NFR   Framework             | NFR      |

<p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

### Legenda

#### Especificação suplementar

- USAB: reuqisito de USABILIDADE
- CONF: requisito de CONFIABILIDADE
- DES: requisito de DESEMPENHO
- SUP: requisito de SUPORTABILIDADE
- FIS: requisito do tipo FÍSICO

### NFR Framework

- NFR01: Usabilidade
- NFR02: Confiabilidade
- NFR03: Segurança

### Tabela dos Requisitos

A seguir será apresentado os requisitos não funcionais presentes nas tabelas 30 a 48.
<details>
  <summary>RNF01 - O aplicativo deve oferecer o termo de uso de forma fácil de ser encontrado, além de explicar ao usuário a sua utilidade de modo a evitar problemas de entendimento a respeito de informações do aplicativo</summary>
<p>Tabela 30: Requisito não funcional 01.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">USAB01</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR01</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF02 - O design deve garantir uma navegação clara e eficiente, facilitando a localização de funcionalidades pelos usuários.</summary>
<p>Tabela 31: Requisito não funcional 02.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">USAB02</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR01</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF03 - Todas as interações do usuário devem ser acompanhadas por feedback visual ou auditivo para fornecer orientação imediata.</summary>
<p>Tabela 32: Requisito não funcional 03.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">USAB03</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR01</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF04 - O aplicativo deve ser acessível a usuários com deficiências, seguindo as diretrizes de acessibilidade relevantes.</summary>
<p>Tabela 33: Requisito não funcional 04.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">USAB04</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR01</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF05 - As atualizações de status ou notificações devem ser apresentadas de maneira não intrusiva, mantendo a experiência do usuário fluida.</summary>
<p>Tabela 34: Requisito não funcional 05.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">USAB05</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR01</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF06 - A interface do aplicativo deve ser intuitiva, proporcionando uma experiência fácil para todos os usuários.</summary>
<p>Tabela 35: Requisito não funcional 06.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">USAB06</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR01</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF07 - Garantir 99,9% de disponibilidade de tempo, principalmente durante períodos eleitorais, evitando interrupções não programadas.</summary>
<p>Tabela 36: Requisito não funcional 07.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">CONF01</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR02</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF08 - Implementar backups regulares e procedimentos de recuperação eficazes para evitar perda significativa de dados em falhas inesperadas.</summary>
 <p>Tabela 37: Requisito não funcional 08.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">CONF02</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR02</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF09 - O aplicativo deve oferecer segurança ao usuário, com a proteção nos dados, utilizando etapas de segurança, como por exemplo; login por meio da biometria digital.</summary>
<p>Tabela 38: Requisito não funcional 09.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">CONF03</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR02</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF10 - Manter um tempo de resposta inferior a 2 segundos para interações do usuário, assegurando uma experiência ágil.</summary>
<p>Tabela 39: Requisito não funcional 10.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">DES01</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">--</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF11 - O sistema deve ser capaz de lidar com um aumento de 50% no tráfego de usuários simultâneos durante o período eleitoral.</summary>
<p>Tabela 40: Requisito não funcional 11.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">DES02</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">--</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF12 - O sistema deve ser compatível com versões anteriores, garantindo que os usuários possam migrar para novas versões sem problemas.</summary>
<p>Tabela 41: Requisito não funcional 12.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">SUP01</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">--</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF13 - O sistema deve ser projetado para permitir a adição de novos recursos ou funcionalidades sem alterações significativas no código existente.</summary>
<p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">SUP02</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">--</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF14 - O sistema deve ser compatível com padrões de segurança reconhecidos, como o ISO 27001.</summary>
<p>Tabela 43: Requisito não funcional 14.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">SUP03</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR03</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF15 - O sistema deve haver um plano de backup e recuperação bem definido para proteger os dados e garantir a recuperação em caso de falhas.</summary>
<p>Tabela 44: Requisito não funcional 15.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">SUP04</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">NFR03</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF16 - No sistema deve haver um plano de suporte ao usuário para responder a dúvidas e problemas de forma eficaz.</summary>
<p>Tabela 45: Requisito não funcional 16.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">SUP05</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">--</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF17 - O aplicativo deve ser otimizado para funcionar em dispositivos com configurações de hardware mínimas, assegurando uma ampla base de usuários.</summary>
<p>Tabela 46: Requisito não funcional 17.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">FIS01</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">--</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF18 - Os dispositivos deverão ter acesso a internet para acessar o aplicativo.</summary>
<p>Tabela 47: Requisito não funcional 18.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">FIS02</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">--</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

<details>
  <summary>RNF19 - O software necessário para a compatibilidade é Android 6.0 ou superior, e a versão do IOS 3.0 ou superior.</summary>
<p>Tabela 48: Requisito não funcional 19.</p>
  <table>
    <thead>
      <tr>
        <th>Tópico</th>
        <th>Referência</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Especificação Suplementar</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/especificacao-suplementar/">FIS03</a></td>
      </tr>
      <tr>
        <td>NFR Framework</td>
        <td><a href="https://requisitos-de-software.github.io/2023.2-e-Titulo/modelagem/agil/nfr/">--</a>
        </td>
      </tr>
    </tbody>
  </table>

  <p>Fonte: Orlando, Mateus e Costa, João. 2023.</p>

</details>

></iframe>
<font size="3"><p>Fonte: [João Costa](https://github.com/jvcostta) e [Mateus Orlando](https://github.com/MateusPy).</p></font>
</figure>

## Bibliografia e Referências

> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. 2019. Acesso em: 18 nov. 2023.

> POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamental.. Acesso em: 18 nov. 2023.

> Ana, Beatriz e Kauã. Forward-from. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: https://requisitos-de-software.github.io/2023.1-Simplenote/pos-rastreabilidade/Forward-From/. Acesso em: 16 nov. 2023.

> Bosi, Rafael. Forward-from. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: https://requisitos-de-software.github.io/2023.1-VLC/#/pos_rastreabilidade/forward_from. Acesso em: 17 nov. 2023.


## Histório de Versão

| Versão | Data       | Descrição                           | Autor(es)                                                                                           | Revisor(es)                                                                                                    |
| ------ | ---------- | ----------------------------------- | --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| `1.0`  | 19/11/2023 | Criação da introdução, metodologia e requisitos funcionais | [Mateus Orlando](https://github.com/MateusPy) e [João Victor](https://github.com/jvcostta) | [Maria Marques](https://github.com/EduardaSMarques) e [Maria Barbosa](https//github.com/Madu01) |
| `1.1`  | 20/11/2023 | Ajustando rastreamento | [Mateus Orlando](https://github.com/MateusPy) e [João Victor](https://github.com/jvcostta) | [Maria Marques](https://github.com/EduardaSMarques) e [Maria Barbosa](https//github.com/Madu01) |
| `1.2`  | 20/11/2023 | Adicionando Bibliografia | [Mateus Orlando](https://github.com/MateusPy) e [João Victor](https://github.com/jvcostta) | [Maria Marques](https://github.com/EduardaSMarques) e [Maria Barbosa](https//github.com/Madu01) |
| `1.3`  | 20/11/2023 | Concertando rotas das imagens e dos protótipos | [Mateus Orlando](https://github.com/MateusPy)  |  [João Victor](https://github.com/jvcostta) | [Maria Marques](https://github.com/EduardaSMarques) e [Maria Barbosa](https//github.com/Madu01) |
| `1.4`  | 30/11/2023 | Corrigindo erros da inspeção | [Mateus Orlando](https://github.com/MateusPy)  e  [João Victor](https://github.com/jvcostta) | [Maria Marques](https://github.com/EduardaSMarques) e [Maria Barbosa](https//github.com/Madu01) |
| `1.5`  | 01/12/2023 | Corrigindo erros da inspeção | [Mateus Orlando](https://github.com/MateusPy)  e  [João Victor](https://github.com/jvcostta) | [Maria Marques](https://github.com/EduardaSMarques) e [Maria Barbosa](https//github.com/Madu01) |
| `1.5`  | 04/12/2023 | Corrigindo erros da inspeção | [Mateus Orlando](https://github.com/MateusPy)  e  [João Victor](https://github.com/jvcostta) | [Maria Marques](https://github.com/EduardaSMarques) e [Maria Barbosa](https//github.com/Madu01) |