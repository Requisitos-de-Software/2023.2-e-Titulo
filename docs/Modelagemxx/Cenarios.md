# Introdução

De acordo com a definição de Jacobson e Rosson/Carroll, cenários representam as interações que ocorrem entre um sistema e atores externos. Enquanto Jacobson associa o termo "caso de uso" a tipos específicos de cenários, destacando instâncias particulares ou conjuntos possíveis de interações, Rosson e Carroll veem os cenários como descrições abrangentes que englobam atores, informações, ambientes, objetivos e sequências de ações.
Eles enfatizam que os cenários desempenham um papel crucial como histórias compartilhadas durante o processo de design do sistema, envolvendo colaboradores como clientes, gerentes de projeto e usuários. Essas narrativas podem assumir diversas formas, como texto, storyboards, modelos em vídeo ou protótipos, com expressões que podem ser formais ou informais. Cenários são de importância fundamental ao longo de todo o ciclo de design, permitindo uma compreensão profunda das interações entre seres humanos e computadores.



## Metodologia
A metodologia usada será representada por tabelas, nas quais serão representadas pelo modelo a seguir na Tabela 1

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Nome do Cenário |
| **Objetivo**    | Objetivo do Cenário |
| **Contexto**    | Local: Local onde acontece o Cenário. <br /> Tempo: Tempo do Cenário. <br /> Pré-condição: Condição para que o Cenário aconteça |
| **Atores**      | Ator(es) do Cenário |
| **Recursos**    | Recursos do Cenário |
| **Episódios**   | Episódios do Cenário da aplicação |
| **Exceção**     | Exceção do Cenário |

Tabela 1 - Representação dos cenários

</center>

## Cenários
A seguir, as tabelas de 2 a 11 representarão os cenários referentes aos requisitos funcionais de alta prioridade do aplicatico e-título, priozizados pela técnica [Three Level-Scale](https://requisitos-de-software.github.io/2023.2-e-Titulo/elicitacao/priorizacao/threeLevelScale/)

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Realizar o cadastro do usuário |
| **Objetivo**    | Facilitar que os eleitores se registrem no aplicativo e-Título para usufruir dos serviços disponibilizados pelo Tribunal Superior Eleitoral (TSE). |
| **Contexto**    | Local: Página inicial do aplicativo <br /> Tempo: 5 minutos <br /> Pré-condição: ter o aplicativo instalado|
| **Atores**      | 1. Usuário: O cidadão que deseja utilizar os serviços do e-Título. <br /> 2. Sistema e-Título: O aplicativo ator do sistema.|
| **Recursos**    | 1. Dispositivo Móvel: Smartphone ou tablet com sistema operacional compatível. <br /> 2. Conexão com a Internet: Para realizar o download do aplicativo e a verificação de dados durante o cadastro. |
| **Episódios**   | 1. Abertura do Aplicativo: O usuário realiza o download do aplicativo e-Título na loja de aplicativos do seu dispositivo. Ao abrir o aplicativo, é apresentada a tela inicial de boas-vindas. <br /> 2. Início do Cadastro: O usuário seleciona a opção "Realizar Cadastro" na tela inicial. O sistema solicita informações pessoais, incluindo nome completo, número do CPF e data de nascimento. <br /> 3. Validação de Dados: O aplicativo realiza a verificação dos dados fornecidos, garantindo a autenticidade das informações. <br /> 4. Criação de Senha: O usuário escolhe uma senha segura para proteger o acesso ao e-Título. <br /> 5. Conclusão do Cadastro: Após a confirmação, o sistema exibe uma mensagem de sucesso e direciona o usuário para a tela de login.|
| **Exceção**     | 1. Dados pessoais inválidos como nome, cpf, rg e nome dos pais. <br /> 2. Caso o usuário encontre dificuldades durante o processo de cadastro, o aplicativo oferece suporte online e instruções para solucionar problemas. |

Tabela 2 - Representação dos cenários

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Login e autenticação segura |
| **Objetivo**    | Permitir a eficiencia e segurança aos eleitores quando acessarem o e-Título, utilizando autenticação por senha ou biometria e em alguns casos reconhecimento facial. |
| **Contexto**    | Local: Página inicial do aplicativo <br /> Tempo: 1 minuto <br /> Pré-condição: já ter realizado o cadastro. |
| **Atores**      | 1. Usuário: Usuário do aplicativo e-titulo. <br /> 2. Sistema e-Título: ator do sistema. |
| **Recursos**    | 1. Cadastro Prévio: O usuário deve ter realizado o cadastro no e-Título previamente. <br /> 2. Senha: Opção de autenticação por meio de senha cadastrada durante o processo de registro. <br /> 3. Biometria: Alternativa de autenticação utilizando os dados biométricos previamente registrados no dispositivo móvel. |
| **Episódios**   | 1. Acesso ao Aplicativo: O usuário abre o aplicativo e-Título no seu dispositivo móvel. <br /> 2. Escolha do Método de Autenticação: Na tela de login, o usuário escolhe entre autenticação por senha ou biometria. <br /> 3. Autenticação por Senha: O usuário insere sua senha previamente cadastrada e confirma. <br /> 4. Autenticação por Biometria: Se escolhida a autenticação por biometria, o usuário realiza a verificação biométrica no dispositivo. <br /> 5. Validação da Autenticação: O sistema valida as informações inseridas ou a biometria, concedendo ou negando o acesso. <br /> 6. Acesso ao Menu Principal: Em caso de sucesso na autenticação, o usuário é direcionado ao menu principal do e-Título. |
| **Exceção**     | 1. Cpf e/ou senha inválidos. <br /> 2. Em caso de falha na autenticação, o sistema notifica o usuário e fornece instruções para recuperar acesso à conta, como redefinição de senha. |

Tabela 3 - Representação dos cenários

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Emissão do título de eleitor |
| **Objetivo**    | Possibilitar aos eleitores a obtenção da via digital do título de eleitor. |
| **Contexto**    | Local: Página "Emitir título de eleitor" <br /> Tempo: 3 minutos <br /> Pré-condição: Estar logado com sucesso na conta e os dados verificados. |
| **Atores**      | 1. Eleitor: Usuário do aplicativo e-titulo. <br /> 2. Sistema e-Título: Aplicativo ator do sistema. |
| **Recursos**    | 1. Dados Cadastrais: Informações pessoais do eleitor previamente cadastradas. <br /> 2. Conexão com a Base de Dados Eleitorais: Para verificação e autenticação dos dados do eleitor.<br /> 3. Módulo de Emissão Digital: Ferramenta que gera a via digital do título de eleitor. <br /> 4. Notificações: Sistema de alertas para informar o eleitor sobre o sucesso da emissão. |
| **Episódios**   | 1. Autenticação: O eleitor acessa o aplicativo e-Título e realiza a autenticação utilizando seu CPF e senha. <br /> 2. Verificação de Dados: O sistema valida os dados do eleitor por meio da conexão com a base de dados eleitorais. <br /> 3. Acesso à Opção "Meu Título": Após autenticação bem-sucedida, o eleitor navega até a seção "Meu Título" no menu principal do aplicativo. <br /> 4. Seleção da Opção "Emitir Título Digital": O eleitor escolhe a opção específica para emitir a via digital do título de eleitor. <br /> 5. Geração da Via Digital: O módulo de emissão digital utiliza os dados do eleitor para gerar a versão digital do título. <br /> 6. Notificação de Sucesso: O eleitor recebe uma notificação informando que a emissão foi concluída com sucesso. <br /> 7. Download do Título Digital: O eleitor pode baixar a via digital do título de eleitor diretamente para o seu dispositivo. |
| **Exceção**     | 1. Cpf e/ou senha inválidos. <br /> 2. Em caso de falha na autenticação ou verificação de dados, o sistema exibirá uma mensagem de erro, orientando o eleitor a revisar as informações ou contatar o suporte técnico. |

Tabela 4 - Representação dos cenários

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Aceitação dos termos de uso |
| **Objetivo**    | Implementar um processo eficiente para que os usuários do aplicativo e-Título visualizem e concordem com os termos de uso antes de acessar as funcionalidades.|
| **Contexto**    | Local: Página seguinte a finalização do cadastro <br /> Tempo: 5 minutos <br /> Pré-condição: Ter feito o cadastro. |
| **Atores**      | 1. Eleitor: Usuário do aplicativo e-titulo. <br /> 2. Sistema e-Título: O aplicativo ator do sistema.|
| **Recursos**    | 1. Interface do usuário para exibição dos termos de uso. <br /> 2. Banco de dados para armazenamento do consentimento do usuário.|
| **Episódios**   | 1. Abertura do Aplicativo: O usuário inicia o aplicativo e-Título. <br /> 2. Exibição dos Termos de Uso: O sistema apresenta os termos de uso de forma clara e acessível na tela inicial do aplicativo. <br /> 3. Leitura dos Termos: O usuário tem a opção de ler os termos na íntegra. <br /> 4. Aceitação dos Termos: Após a leitura, o usuário tem a opção de aceitar os termos para prosseguir. <br /> 5. Registro do Consentimento: O sistema registra o consentimento do usuário, indicando que ele leu e concordou com os termos de uso. <br /> 6. Acesso às Funcionalidades: Com os termos aceitos, o usuário tem acesso completo às funcionalidades do e-Título.|
| **Exceção**     | 1. Não ter realizado o cadastro corretamente <br /> 2. Recusar. <br /> Em caso de recusa dos termos de uso, o usuário é direcionado para encerrar o aplicativo. |

Tabela 5 - Representação dos cenários

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Processo de Recuperação de Senha |
| **Objetivo**    | Permitir que usuários do aplicativo e-Título recuperem suas senhas de forma segura e eficiente. |
| **Contexto**    | Local: Página inicial <br /> Tempo: 5 minutos <br /> Pré-condição: Ter um cadastro  |
| **Atores**      | 1. Eleitor: Usuário do aplicativo e-titulo. <br/> 2. Sistema e-Título: O aplicativo ator do sistema. |
| **Recursos**    | 1. Mecanismo seguro de recuperação de senha. <br/> 2. Comunicação por e-mail ou SMS para verificação de identidade. |
| **Episódios**   | 1. Solicitação de Recuperação: O usuário seleciona a opção de recuperação de senha no aplicativo. <br/> 2. Identificação do Usuário: O sistema solicita informações para identificar o usuário, como CPF ou e-mail cadastrado. <br/> 3. Envio de Código de Verificação: Um código de verificação é enviado para o e-mail ou número de telefone associado à conta do usuário. <br/> 4. Inserção do Código: O usuário insere o código de verificação recebido. <br/> 5. Redefinição da Senha: Após a verificação bem-sucedida, o sistema permite que o usuário defina uma nova senha. <br/ > 6. Confirmação da Recuperação: O usuário recebe uma notificação de confirmação da recuperação bem-sucedida. <br /> 7. Acesso ao e-Título: Com a nova senha definida, o usuário pode acessar novamente o aplicativo. |
| **Exceção**     | 1. redefinir senha com a que estava em uso. <br /> 2. Identidade não verificada. <br /> Usuário é orientado a entrar em contato com o suporte. |

Tabela 6 - Representação dos cenários

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Restrição de idade |
| **Objetivo**    | Garantir que apenas usuários com idade igual ou superior a 16 anos, aptos a votar, possam acessar o aplicativo e-Título. |
| **Contexto**    | Local: Página de cadastro <br /> Tempo: 1 minutos <br /> Pré-condição: Ter iniciado o cadastro |
| **Atores**      | 1. Eleitor: Usuário do aplicativo e-titulo. <br /> 2. Sistema e-Título: O aplicativo ator do sistema. |
| **Recursos**    | 1. Verificação da idade do usuário no momento do cadastro. <br/> 2. Atualização automática da idade com base na data de nascimento fornecida. |
| **Episódios**   | 1. Registro do Usuário: O usuário fornece sua data de nascimento durante o processo de cadastro. <br/> 2. Verificação da Idade: O sistema verifica se a idade do usuário é igual ou superior a 16 anos. <br/> 3. Acesso Permitido: Se a idade atender ao requisito, o usuário tem acesso total ao aplicativo. <br/> 4. Acesso Negado: Se a idade for inferior a 16 anos, o acesso ao aplicativo é negado. |
| **Exceção**     | 1. Data de nascimento registrada errada. <br /> Em caso de identificação de dados falsos ou suspeitos, o sistema pode bloquear o acesso e solicitar verificações adicionais |

Tabela 7 - Representação dos cenários

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Verificação de Autenticidade de Documentos |
| **Objetivo**    | Fornecer aos usuários do aplicativo e-Título a capacidade de verificar a autenticidade de seus documentos eleitorais de forma confiável. |
| **Contexto**    | Local: Página "Verificar a autenticidade do documento" <br /> Tempo: 5 minutos <br /> Pré-condição: Ter cadastro e obter um documento para análise.  |
| **Atores**      | 1. Eleitor: Usuário do aplicativo e-titulo. <br/> 2. Sistema e-Título: O aplicativo ator do sistema. |
| **Recursos**    | 1. Mecanismo de verificação de autenticidade integrado ao aplicativo. <br/> 2. Criptografia e tecnologias de segurança para proteger a integridade dos documentos. |
| **Episódios**   | 1. Visualização do Documento Eleitoral: O usuário acessa a seção "Meu Título" no aplicativo e-Título para visualizar seu documento eleitoral digital. <br/> 2. Opção de Verificação: O sistema oferece uma opção para verificar a autenticidade do documento. <br/> 3. Processo de Verificação: O aplicativo realiza uma verificação interna para garantir que o documento seja genuíno e não tenha sido adulterado. <br/> 4. Resultado da Verificação: O usuário recebe uma notificação indicando que o documento é autêntico. |
| **Exceção**     | 1. Envio de documento não correspondente <br /> Se a verificação identificar qualquer irregularidade no documento, o usuário é notificado e orientado a entrar em contato com o suporte técnico. |

Tabela 8 - Representação dos cenários

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Notificação de Horário de Votação |
| **Objetivo**    | Informar os usuários do aplicativo e-Título sobre o horário de votação nas eleições para garantir a participação ativa dos eleitores. |
| **Contexto**    | Local: Página "Locais de votação" <br /> Tempo: 1 minutos <br /> Pré-condição: Cadastro e dados pessoais atualizados. |
| **Atores**      | 1. Eleitor: Usuário do aplicativo e-titulo. <br/> 2. Sistema e-Título: O aplicativo ator do sistema. |
| **Recursos**    | 1. Sistema de notificação push integrado ao aplicativo. <br/> 2. Banco de dados de informações sobre as eleições, incluindo horários de votação. |
| **Episódios**   | 1. Atualização de Informações Eleitorais: O sistema mantém informações atualizadas sobre as próximas eleições, incluindo horários de votação. <br/> 2. Notificação Antecipada: Antes do dia da eleição, o aplicativo envia notificações aos usuários para informar sobre os horários de votação. <br/> 3. Lembrete no Dia da Eleição: No dia da eleição, uma notificação é enviada aos usuários para lembrá-los do horário de abertura e fechamento das seções de votação. <br/> 4. Acesso Rápido aos Locais de Votação: A notificação pode incluir um link rápido para a seção "Locais de Votação" no aplicativo, permitindo aos usuários encontrar facilmente onde votar. |
| **Exceção**     | 1. Dados cadastrais desatualizados. <br /> 2. Mudança de locais e/ou horarios de votação. <br /> Em caso de mudanças de última hora nos horários de votação devido a circunstâncias excepcionais, uma notificação urgente é enviada aos usuários. |

Tabela 9 - Representação dos cenários

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Segurança de Dados |
| **Objetivo**    | Garantir a segurança dos dados dos usuários no aplicativo e-Título, implementando medidas eficazes de proteção. |
| **Contexto**    | Local: Página de login e cadastro <br /> Tempo: 1 min <br /> Pré-condição: Preencher os campos com dados pessoais  |
| **Atores**      | 1. Eleitor: Usuário do aplicativo e-titulo. <br/> 2. Sistema e-Título: O aplicativo ator do sistema. |
| **Recursos**    | 1. Criptografia de ponta a ponta para dados sensíveis. <br/> 2. Mecanismos de autenticação segura, como senha e biometria. <br/> 3. Atualizações regulares de segurança para corrigir vulnerabilidades. <br/> 4. Políticas de privacidade claras e transparentes. |
| **Episódios**   | 1. Registro Seguro: Durante o processo de registro, os dados pessoais do usuário são criptografados e armazenados de forma segura no banco de dados. <br/> 2. Autenticação Protegida: Mecanismos de autenticação, como senha e/ou biometria, são exigidos para garantir que apenas usuários autorizados acessem o aplicativo. <br/> 3. Comunicação Segura: Todas as comunicações entre o aplicativo e o servidor são protegidas por criptografia SSL para evitar interceptações não autorizadas. <br/> 4. Atualizações de Segurança: O aplicativo é regularmente atualizado para corrigir possíveis vulnerabilidades de segurança e garantir a conformidade com as últimas práticas de segurança.<br/> 5. Políticas de Privacidade Transparentes: O aplicativo exibe claramente suas políticas de privacidade, informando os usuários sobre como seus dados são coletados, usados e protegidos.|
| **Exceção**     | 1. Dados suspeitos com más intenções. <br /> Em caso de detecção de atividade suspeita ou violação de segurança, são acionados procedimentos de resposta a incidentes para proteger os dados e os usuários. |

Tabela 10 - Representação dos cenários

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

| **Cenário**     | **Número do Cenário** |
| :--------------:| :-------------- |
| **Titulo**      | Design Intuitivo e personalizado  |
| **Objetivo**    | Criar uma experiência de usuário intuitiva no aplicativo e-Título, utilizando um design consistente com botões e menus padronizados.|
| **Contexto**    | Local: Aplicativo por completo <br /> Tempo: Durante o uso do aplicativo <br /> Pré-condição: Baixar aplicativo. |
| **Atores**      | 1. Eleitor: Usuário do aplicativo e-titulo. 2. Sistema e-Título: O aplicativo ator do sistema. |
| **Recursos**    | 1. Padrões de design consistentes em toda a interface. <br/> 2. Botões e menus com elementos visuais claros e compreensíveis. <br/> 3. Feedback visual para ações do usuário. |
| **Episódios**   | 1. Botões Padronizados: Os botões em todo o aplicativo seguem um padrão visual consistente, facilitando o reconhecimento e uso pelos usuários. <br/> 2. Menus Intuitivos: Menus são organizados de maneira lógica e intuitiva, garantindo que os usuários possam encontrar facilmente as funcionalidades desejadas. <br/> 3. Feedback Visual: O aplicativo fornece feedback visual imediato quando um botão é pressionado ou uma ação é executada,garantindo que os usuários saibam que sua interação foi reconhecida. <br/> 4. Cores e Elementos Visuais Coerentes: Cores e elementos visuais são utilizados de forma coerente em todo o aplicativo, reforçando a identidade visual e facilitando a compreensão.|
| **Exceção**     | 1. Atualizações que causem mudanças na visualização e interpretação do usuário. <br /> Em casos de melhorias significativas no design que possam afetar a usabilidade, os usuários recebem notificações e orientações claras sobre as mudanças. |

Tabela 11 - Representação dos cenários

</center>


## Histórico de versões
| Versão | Data       | Descrição                   | Autor(es)     | Revisor(es) |
|--------|------------|:-----------------------------|---------------|-------------|
| 1.0    | 22/10/2023 | itrodução, conceito e metodologia   |  [João Costa](https://github.com/jvcostta)   |  [Mateus Orlando](https://github.com/MateusPy)           |
| 1.1    | 23/10/2023 | criação dos cenários | [João Costa](https://github.com/jvcostta) |  [Mateus Orlando](https://github.com/MateusPy)  |
| 1.2    | 24/10/2023 | Ajustes dos cenários | [João Costa](https://github.com/jvcostta) |  [Mateus Orlando](https://github.com/MateusPy)  |
