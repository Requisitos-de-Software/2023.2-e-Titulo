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
  | GLO | Glossário |
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
| Elicitação            | INT         |
| Léxico                | L           |
| Casos de Uso          | UC          |
| Storytelling          | ST          |
| Especificação suplementar| C           |
| Introspeção              | INT         |
| Questionário             | C           |
| funcionalidade        | Representação em imagem/video       |

<details>
  <summary>RF01 - Realizar o cadastro</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US01</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT13</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B02</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L06</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/">UC01</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C01</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1dL8Yt5TpStJwF17_wTCMiNc_ZbwBryY_/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 2: Requisito funcional 1 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF02 - Realizar login</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US02</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://github.com/Requisitos-de-Software/2023.1note/blob/main/docs/elicitacao/Introspec%C3%A7%C3%A3o.md">INT06</a>
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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C03</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1snMVs47tUh-hujS08d6KbFOM3KZqv47t/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 3: Requisito funcional 2 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF03 - Emitir Título</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US03</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT13</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B02</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L02</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/">UC02</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C04</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1itBYrqoBlDab_GbQU-5b9APxl-d6dt-w/preview" width="640" height="480"></iframe>
</td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 4: Requisito funcional 3 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF04 - Acessar QR code</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US07</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT02</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B03</a></td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L11</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C02</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1stno3pYUBPtD70FP_GXmdt2nXZHqGAvD/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 5: Requisito funcional 4 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF05 - Visualizar local de votação</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E1</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US04</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT03</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L08</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C09</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/16MHAt63E04b1b1tDPAxT8LPonxZJ8fK2/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 6: Requisito funcional 5 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF06 - Receber notificações</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E2</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US08</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Organização</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT14</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/">L04</a></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/casos_de_uso/">UC03</a></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C05/C013</a>
        </td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1cYuq9hB-Dk8bYRyFRf5o17a128KgyMtJ/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 7: Requisito funcional 6 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF07 - Acesso ao termo de uso</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E2</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US09</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Organização</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT03</a>
        </td>
      </tr>
      <tr>
        <td>Léxico</td>
        <td></td>
      </tr>
      <tr>
        <td>Caso de Uso</td>
        <td></td>
      </tr>
      <tr>
        <td>Cenário</td>
        <td></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1IDD-gZT1IvufTL3E8KvJFxISODgqCxgr/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 8: Requisito funcional 7 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF08 - Recuperar senha</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E3</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US10</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Suporte a formatos avançados de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td>-</td>
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
        <td><iframe src="https://drive.google.com/file/d/1oKd3A_4mWGxV7yFkGeEVoE9CUVmWrz3z/preview" width="640" height="480"></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 9: Requisito funcional 8 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF09 - Sair do aplicativo</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E3</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US11</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Suporte a formatos avançados de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/Introspec%C3%A7%C3%A3o/">INT05</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO04</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST2</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT04</a></td>
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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C06</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1Hu8RKJsbN0NDwkE4gvLLmXuV0vaJOE3e/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>


  <p>Tabela 10: Requisito funcional 9 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF10 - Visualizar dúvidas frequentes</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E3</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US12</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Suporte a formatos avançados de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B10</a></td>
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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C10</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1dtGUscbXALihip2gOxY5N7MBXbuLswIl/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 11: Requisito funcional 10 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF11 - Alterar dados cadastrais</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US05</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Sincronização e armazenamento de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT02</a></td>
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
        <td><img src=../../img/Sincronizar.PNG width="400"></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 12: Requisito funcional 11 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF12 - Usuários apenas acima de 16 anos</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US05</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Sincronização e armazenamento de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST04</a></td>
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
        <td><iframe src="https://drive.google.com/file/d/1dtGUscbXALihip2gOxY5N7MBXbuLswIl/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 13: Requisito funcional 12 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF13 - Acesso a internet para o uso</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US13</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Sincronização e armazenamento de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/storytelling/">ST06</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO06</a></td>
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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/cen%C3%A1rios/">C09</a></td>
      </tr>
      <tr>
        <td>Funcionalidade</td>
        <td><iframe src="https://drive.google.com/file/d/1Uoh7bTqas_D2VmTzhlEFCsnFdPa_dYCx/preview" width="640" height="480"></iframe></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 14: Requisito funcional 13 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF14 - Realizar a quitação eleitoral</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US14</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Sincronização e armazenamento de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT07</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO05</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B19</a></td>
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
        <td><img src=../../img/Sincronizar.PNG width="400"></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 15: Requisito funcional 14 (Fonte: Autores, 2023).</p>

</details>

<details>
  <summary>RF14 - Realizar a quitação eleitoral</summary>

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
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/backlog/">E4</a></td>
      </tr>
      <tr>
        <td>História de usuário</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/agil/User_story/">US14</a>
        </td>
      </tr>
      <tr>
        <td>Tema</td>
        <td>Sincronização e armazenamento de notas</td>
      </tr>
      <tr>
        <td>Elicitação</td>
        <td><a href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/entrevista/">ENT07</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/glossario/">GLO05</a>/<a
            href="https://requisitos-de-software.github.io/2023.1-Simplenote/elicitacao/brainstorming/">B19</a></td>
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
        <td><img src=../../img/Sincronizar.PNG width="400"></td>
      </tr>
    </tbody>
  </table>

  <p>Tabela 15: Requisito funcional 14 (Fonte: Autores, 2023).</p>

</details>


<br>
