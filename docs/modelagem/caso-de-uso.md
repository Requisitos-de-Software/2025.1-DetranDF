# Introdução

O Caso de Uso é um artefato essencial na Engenharia de Requisitos, utilizado para descrever as interações entre os usuários e o sistema. No contexto do aplicativo Detran-DF, ele permite representar de forma clara como os cidadãos interagem com os serviços digitais oferecidos, como agendamentos, emissão de documentos, consulta de débitos, entre outros. Essa abordagem ajuda a alinhar a visão dos stakeholders com a implementação técnica.

# Objetivo

O objetivo do Caso de Uso no projeto do Detran-DF é representar detalhadamente os requisitos funcionais, considerando diferentes fluxos de interação com o sistema. Ele busca garantir que o sistema atenda às necessidades dos usuários, oferecendo uma visão centrada no cidadão e auxiliando no desenvolvimento, testes e rastreabilidade dos requisitos ao longo do ciclo de vida do projeto.

# Metodologia

A construção dos Casos de Uso para o aplicativo Detran-DF segue uma abordagem estruturada com as seguintes etapas:

1. **Identificação da funcionalidade** a ser modelada e definição dos atores envolvidos.
2. **Descrição dos atores e pré-condições**, especificando quem pode iniciar a interação e quais condições devem ser cumpridas.
3. **Modelagem dos fluxos**, com a criação de:
   - Fluxo principal (sucesso);
   - Fluxos alternativos (variações);
   - Fluxos de exceção (falhas ou erros).
4. **Definição de pós-condições**, descrevendo os resultados após a execução do caso.
5. **Validação com stakeholders**, garantindo clareza, completude e alinhamento com os objetivos do sistema.

Essa metodologia assegura que os Casos de Uso representem corretamente o comportamento do sistema Detran-DF, servindo como base para todas as fases do desenvolvimento.

No diagrama de caso de uso , precisamos ter todos esses componentes:

<font size="3"><p style="text-align: center">**Tabela 1 -** Componentes de um diagrama de caso de uso.</p></font>

| **Símbolo**                                                 | **Nome**        | **Função**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ----------------------------------------------------------- | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Ator](../assets/casos_de_uso/simbolos/ator.png)           | **Ator**        | Atores representam algo ou alguém que utiliza o sistema para atingir um objetivo, podendo ser uma pessoa, organização, outro sistema ou dispositivo externo. Atores são objetos externos, que serão representados fora dos limites do projeto. Os atores também podem ser dividos em atores primários e secundários, os primários são aqueles que iniciam a utilização do sistema, que são representados do lado esquerdo do diagrama, e os secundários são os atores que reagem a uma certa ação, representados do lado direito do diagrama. |
| ![casoDeuso](../assets/casos_de_uso/simbolos/casoDeUso.png) | **Caso de Uso** | Representa uma ação que realiza uma tarefa dentro do sistema, são representados dentro do retângulo do sistema pois são funcionalidades realizadas pelo projeto que está sendo implementado.                                                                                                                                                                                                                                                                                                                                                  |
| ![sistema](../assets/casos_de_uso/simbolos/sistema.png)     | **Sistema**     | Projeto que está sendo desenvolvido. O retângulo que abrange o sistema representa os limites do projeto, o que ele deve realizar, separando os casos de uso, que podem ficar dentro do sistema, dos atores, que devem ficar do lado de fora do retângulo.                                                                                                                                                                                                                                                                                     |
| ![setas](../assets/casos_de_uso/simbolos/setas.png)         | **Relações**    | São interações que acontecem entre os atores com os casos de uso ou entre os próprios casos de uso.                                                                                                                                                                                                                                                                                                                                                                                                                                           |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

## Diagrama de Caso de Uso do app Detran-DF

<font size="3"><p style="text-align: center">**Figura 1 -** Diagrama de Casos de Uso.</p></font>



![Diagrama Caso de uso Detran DF](../assets/casos_de_uso/simbolos/diagramaCasodeUsodetran.png)



Acesse a imagem nesse [link](https://drive.google.com/file/d/1cOhTLCXsaTTtm8O7iCZVKvPkB-eZoheT/view?usp=drive_link)

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10), [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

## Especificação do Caso de Uso

A especificação dos casos de uso é uma técnica utilizada para descrever detalhadamente as interações entre os usuários e o sistema. Ela documenta os passos seguidos em cada caso de uso, incluindo os eventos que desencadeiam a interação, as ações realizadas e as respostas esperadas do sistema.

A tabela 2 descreve qual funcionalidade cada integrante fez um caso de uso.

<font size="3"><p style="text-align: center">**Tabela 2 -** Divisão de caso de uso por integrantes da equipe.</p></font>

| Ordem | Código | Funcionalidade                                                   | Responsável                                  |
| ----- | ------ | ---------------------------------------------------------------- | -------------------------------------------- |
| 1     | UC01   | Realizar agendamentos presenciais (vistoria, CNH, etc.)          | [Giovana Barbosa](https://github.com/gio221) |
| 2     | UC02   | Sistema de pagamento de taxas e débitos                          | [Giovana Barbosa](https://github.com/gio221) |
| 3     | UC03   | Chat com IA para tirar dúvidas                                   | [João Lobo](https://github.com/joaolobo10)   |
| 4     | UC04   | Atendimento ao vivo com servidor do DETRAN via chat/vídeo        | [João Lobo](https://github.com/joaolobo10)   |
| 5     | UC05   | Integração com CNH digital e gov.br                              | [Gabriel Mendes](https://github.com/gbevi)   |
| 6     | UC06   | Área para autoescolas com avaliações, comentários e localizações | [Gabriel Mendes](https://github.com/gbevi)   |
| 7     | UC07   | Histórico de Pesquisas e Serviços Recentes                       | [Luiz Bessa](https://github.com/lfelipebessa)  |
| 8     | UC08   | Notificação antecipada da data de vencimento da CNH              | [Luiz Bessa](https://github.com/lfelipebessa)  |
| 9     | UC09   | Área educacional com explicações e vídeos                        |[Pedro Camilo](https://github.com/PedrooCamilo)|
| 10    | UC10   | Explicações acessíveis sobre siglas                              |[Pedro Camilo](https://github.com/PedrooCamilo)|
| 11    | UC11   | Notificação de multas e prazos com desconto                      | [Maria Eduarda](https://github.com/maaduh)  |
| 12    | UC12   | Aviso automático em caso de roubo/recuperação do carro           | [Maria Eduarda](https://github.com/maaduh)  |
| 13    | UC13   | Agendamento online para provas teóricas e práticas               | [Eric Akio](https://github.com/eric-kingu)   |
| 14    | UC14   | Acessibilidade para diferentes perfis de usuários                | [Eric Akio](https://github.com/eric-kingu)   |

Já na tabela 3 temos o modelo base usado em nossas especificações dos casos de uso.

<font size="3"><p style="text-align: center">**Tabela 3 -** Modelo de especificação de caso de uso.</p></font>

| UCxx                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

### Requisitos Realizar agendamento de serviços

Abaixo, na tabela 4, está especificado o caso de uso para a funcionalidade de "Realizar agendamento de serviços".

<font size="3"><p style="text-align: center">**Tabela 4 -** Requisitos Realizar agendamento de serviços.</p></font>

| UC01                  | Nome do caso de uso                                                                                                                                                                                                                                                                                                                                                                              |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **UC01**              | Realizar agendamento de serviços                                                                                                                                                                                                                                                                                                                                                                 |
| **Descrição**         | Este caso de uso descreve como o usuário realiza o agendamento de um serviço presencial (ex: vistoria, CNH, etc.) por meio da plataforma.                                                                                                                                                                                                                                                        |
| **Atores**            | Usuário (ator principal), Sistema                                                                                                                                                                                                                                                                                                                                                                |
| **Pré-condição**      | O usuário deve estar autenticado no sistema e ter acesso aos serviços disponíveis para agendamento.                                                                                                                                                                                                                                                                                              |
| **Pós-condição**      | Um agendamento é criado e armazenado no sistema. O usuário recebe uma confirmação com os detalhes do agendamento.                                                                                                                                                                                                                                                                                |
| **Fluxo principal**   | 1. O usuário acessa a área de agendamentos.<br>2. O sistema exibe os serviços disponíveis.<br>3. O usuário seleciona o serviço desejado.<br>4. O sistema apresenta os horários e locais disponíveis.<br>5. O usuário escolhe data, horário e local.<br>6. O sistema solicita confirmação.<br>7. O usuário confirma.<br>8. O sistema registra o agendamento e apresenta a confirmação ao usuário. |
| **Fluxo alternativo** | <br>- 3a. O usuário decide alterar o serviço selecionado: retorna à lista de serviços.<br>- 5a. O horário selecionado está indisponível: o sistema exibe uma mensagem e solicita nova escolha.                                                                                                                                                                                                   |
| **Fluxo de exceções** | - E1. Falha de conexão com o sistema: exibir mensagem de erro e tentar nova conexão. <br>- E2. Dados obrigatórios não preenchidos: sistema alerta e impede a confirmação do agendamento.                                                                                                                                                                                                         |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

### Sistema de pagamento de taxas e débitos

Abaixo, na tabela 5, está especificado o caso de uso para a funcionalidade de "Sistema de pagamento de taxas e débitos".

<font size="3"><p style="text-align: center">**Tabela 5 -** Sistema de pagamento de taxas e débitos.</p></font>

| **Seção**               | **Descrição**                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**                  | UC02                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Nome**                | Sistema de pagamento de taxas e débitos                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Descrição**           | Este caso de uso descreve como o usuário acessa e realiza o pagamento de taxas e débitos vinculados aos seus serviços no sistema.                                                                                                                                                                                                                                                                                                                                                |
| **Atores**              | Usuário (ator principal), Sistema, Instituição financeira (ator secundário)                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Pré-condição**        | O usuário deve estar autenticado no sistema e possuir débitos ou taxas pendentes.                                                                                                                                                                                                                                                                                                                                                                                                |
| **Pós-condição**        | O pagamento é processado e registrado no sistema. O usuário recebe um comprovante.                                                                                                                                                                                                                                                                                                                                                                                               |
| **Fluxo Principal**     | 1. O usuário acessa a seção de pagamentos. <br>2. O sistema exibe os débitos e taxas pendentes. <br>3. O usuário seleciona os itens que deseja pagar. <br>4. O sistema exibe o valor total e as formas de pagamento disponíveis. <br>5. O usuário escolhe a forma de pagamento (boleto, cartão, Pix, etc.). <br>6. O sistema redireciona para o ambiente seguro de pagamento. <br>7. O usuário realiza o pagamento. <br>8. O sistema confirma o pagamento e gera um comprovante. |
| **Fluxos Alternativos** | - **3a.** O usuário decide parcelar os débitos: o sistema apresenta as opções de parcelamento. <br> - **5a.** A forma de pagamento não está disponível: o sistema sugere alternativas.                                                                                                                                                                                                                                                                                           |
| **Fluxos de Exceção**   | - **E1.** Falha de conexão com o sistema de pagamento: exibir mensagem e oferecer tentativa posterior. <br> - **E2.** Pagamento recusado: notificar o usuário e manter os débitos como pendentes.                                                                                                                                                                                                                                                                                |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

### Chat com IA para tirar dúvidas

Abaixo, na tabela 6, está especificado o caso de uso para a funcionalidade de "Chat com IA para tirar dúvidas".

<font size="3"><p style="text-align: center">**Tabela 6 -** Chat com IA para tirar dúvidas.</p></font>

| UC03                  | Chat com IA para dúvidas gerais                                                                                                                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Permite que o usuário tire dúvidas frequentes sobre os serviços do Detran DF através de uma IA integrada ao aplicativo, de forma prática e automatizada.                                                                                                                  |
| **Atores**            | Usuário do aplicativo, Assistente virtual (IA).                                                                                                                                                                                                                           |
| **Pré-condição**      | O usuário deve estar logado no aplicativo, possuir conexão com a internet e a IA e base de conhecimento devem estar ativas.                                                                                                                                               |
| **Pós-condição**      | O usuário recebe uma resposta adequada à sua dúvida ou é redirecionado para atendimento humano, se necessário.                                                                                                                                                            |
| **Fluxo principal**   | 1. O usuário acessa o aplicativo do Detran DF. <br>2. Clica na opção “Chat de dúvidas”. <br>3. A IA cumprimenta e oferece categorias de ajuda. <br>4. O usuário faz uma pergunta. <br>5. A IA responde com base na base de conhecimento. <br>6. O usuário encerra o chat. |
| **Fluxo alternativo** | O usuário faz uma pergunta fora das categorias mostradas, e a IA tenta redirecioná-lo para uma categoria relevante.                                                                                                                                                       |
| **Fluxo de exceções** | - A IA não entende a pergunta ou o assunto está fora do escopo: a IA informa que não pode ajudar e fornece contato humano. <br>- O limite diário de 10 interações é atingido: a IA informa o limite e sugere tentar no dia seguinte.                                      |
|                       |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

### Atendimento ao vivo com servidor do DETRAN via chat/vídeo

Abaixo, na tabela 7, está especificado o caso de uso para a funcionalidade de "Atendimento ao vivo com servidor do DETRAN via chat/vídeo".

<font size="3"><p style="text-align: center">**Tabela 7 -** Atendimento ao vivo com servidor do DETRAN via chat/vídeo.</p></font>

| UC04                  | Atendimento ao vivo com servidor do Detran via chat/vídeo                                                                                                                                                                                                                                                                  |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Permite que o usuário realize atendimento remoto com um servidor do Detran DF, por chat, voz ou vídeo, em data e hora agendadas.                                                                                                                                                                                           |
| **Atores**            | Usuário do aplicativo, Servidor do Detran DF.                                                                                                                                                                                                                                                                              |
| **Pré-condição**      | O usuário deve estar logado, ter conexão com a internet, e já ter feito um agendamento válido.                                                                                                                                                                                                                             |
| **Pós-condição**      | O atendimento é realizado com sucesso e registrado no sistema.                                                                                                                                                                                                                                                             |
| **Fluxo principal**   | 1. O usuário acessa o app. <br>2. Navega até “Atendimento ao vivo”. <br>3. Escolhe o serviço e agenda o horário. <br>4. No dia e hora marcados, acessa o atendimento. <br>5. O servidor inicia o atendimento por vídeo. <br>6. O atendimento ocorre por vídeo, voz ou chat. <br>7. O atendimento é encerrado e registrado. |
| **Fluxo alternativo** | O usuário opta por não ativar a câmera e é atendido apenas por voz ou chat.                                                                                                                                                                                                                                                |
| **Fluxo de exceções** | - O usuário não comparece no horário agendado: o atendimento é cancelado automaticamente. <br>- Instabilidade de conexão: o servidor pode remarcar. <br>- Tentativa de acesso fora do horário: o sistema bloqueia a conexão.                                                                                               |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

### Integração com CNH Digital e Gov BR  

Abaixo, na Tabela 8, está especificado o caso de uso para a funcionalidade **“Integração com CNH Digital e Gov BR”**.

<font size="3"><p style="text-align: center">**Tabela 8 –** Integração com CNH Digital e Gov BR.</p></font>

| UC05                  | Integração com CNH Digital e Gov BR                                                                                                   |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição**         | Permite que a pessoa usuária autentique-se via Gov BR (OAuth 2.0) e importe automaticamente os dados da sua CNH Digital para o app.   |
| **Atores**            | • Usuário do aplicativo<br>• Serviço de Autenticação Gov BR<br>• API SENATRAN (CNH Digital)                                           |
| **Pré-condição**      | • Usuário possui cadastro ativo no Gov BR.<br>• Dispositivo conectado à internet.                                                     |
| **Pós-condição**      | • Token JWT válido armazenado com segurança.<br>• Dados da CNH sincronizados no perfil do usuárie.                                    |
| **Fluxo principal**   | 1. Usuário seleciona “Entrar com Gov BR”.<br>2. Sistema redireciona para a tela de login Gov BR (OAuth 2.0).<br>3. Usuário autentica-se e concede consentimento.<br>4. Gov BR retorna *authorization code*.<br>5. Sistema troca o código por um token JWT.<br>6. Com o token, o sistema requisita dados da CNH na API SENATRAN.<br>7. Dados são armazenados e exibidos no aplicativo.<br>8. Caso de uso termina com usuário autenticado e CNH validada. |
| **Fluxo alternativo** | **A1 – Usuárie já logade:**<br>• Passo 1: sistema detecta sessão ativa.<br>• Vai direto ao Passo 6.<br><br>**A2 – Consentimento negado:**<br>• Passo 3: usuário nega consentimento.<br>• Sistema exibe mensagem “Integração cancelada” e encerra. |
| **Fluxo de exceções** | **E1 – Falha na autenticação Gov BR:**<br>• Sistema exibe erro e oferece tentar novamente.<br><br>**E2 – API SENATRAN indisponível:**<br>• Sistema armazena token, agenda nova tentativa de sincronização e notifica usuário. |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Dantas](https://github.com/gbevi), 2025.</p></font>



### Área para autoescolas com avaliações, comentários e localização  

Abaixo, na Tabela 9, está especificado o caso de uso para a funcionalidade **“Área para autoescolas com avaliações, comentários e localização”**.

<font size="3"><p style="text-align: center">**Tabela 9 –** Área para autoescolas com avaliações, comentários e localização.</p></font>

| UC06                  | Área para Autoescolas                                                                                                                  |
|-----------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| **Descrição**         | Permite que autoescolas cadastrem perfis, publiquem informações e recebam avaliações e comentários de alunes, exibindo localização no mapa. |
| **Atores**            | • Autoescola (perfil empresarial)<br>• Aluno/cliente<br>• Sistema de Geolocalização                                                    |
| **Pré-condição**      | • Autoescola possui cadastro aprovado.<br>• Aluno autenticade no aplicativo.                                                           |
| **Pós-condição**      | • Avaliação ou comentário registrado e visível.<br>• Média de pontuação atualizada.                                                    |
| **Fluxo principal**   | 1. Aluno acessa perfil de uma autoescola.<br>2. Sistema exibe detalhes (endereço, nota média, comentários).<br>3. Aluno clica em “Avaliar”.<br>4. Insere nota (1-5) e comentário opcional.<br>5. Sistema valida entrada e salva avaliação.<br>6. Nota média da autoescola é recalculada.<br>7. Avaliação aparece na lista pública. |
| **Fluxo alternativo** | **A1 – Avaliação anônima:**<br>• Passo 4: aluno opta por anonimizar nome.<br>• Sistema registra avaliação como “Usuário anônimo”. |
| **Fluxo de exceções** | **E1 – Comentário ofensivo detectado:**<br>• Sistema bloqueia envio, exibe mensagem e oferece editar.<br><br>**E2 – Autoescola desativada:**<br>• Sistema impede novas avaliações e informa indisponibilidade. |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Dantas](https://github.com/gbevi), 2025.</p></font>

### Histórico de Pesquisas e Serviços Recentes

Abaixo, na Tabela 10, está especificado o caso de uso para a funcionalidade de **"Histórico de Pesquisas e Serviços Recentes"**.

<font size="3"><p style="text-align: center">**Tabela 10 -** Histórico de Pesquisas e Serviços Recentes.</p></font>

| UC07                  | Histórico de Pesquisas e Serviços Recentes                                                                                                                                                                                                                       |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Permite ao usuário visualizar rapidamente os últimos serviços acessados ou pesquisas realizadas dentro do aplicativo, facilitando o acesso recorrente.                                                                                                           |
| **Atores**            | Usuário                                                                                                                                                                                                                                                          |
| **Pré-condição**      | O usuário deve estar autenticado no sistema e já ter realizado alguma ação como acessar um serviço ou realizar uma pesquisa.                                                                                                                                     |
| **Pós-condição**      | Os serviços ou pesquisas realizadas são salvos e exibidos em uma seção visível na tela inicial ou área de histórico.                                                                                                                                             |
| **Fluxo principal**   | 1. O usuário realiza o login.<br>2. O sistema verifica as ações mais recentes feitas pelo usuário.<br>3. O sistema armazena essas ações localmente ou no servidor.<br>4. Ao acessar o app novamente, o sistema exibe as últimas pesquisas ou serviços acessados. |
| **Fluxo alternativo** | 1a. Se o usuário não realizou nenhuma ação anterior, a seção de histórico estará vazia ou exibirá uma mensagem "Nenhum histórico encontrado".                                                                                                                    |
| **Fluxo de exceções** | 1e. Em caso de erro no carregamento do histórico, o sistema deve exibir uma mensagem de erro amigável e sugerir que o usuário tente novamente mais tarde.                                                                                                        |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

### Notificação antecipada da data de vencimento da CNH

Abaixo, na Tabela 11, está especificado o caso de uso para a funcionalidade de **"Notificação antecipada da data de vencimento da CNH"**.

<font size="3"><p style="text-align: center">**Tabela 11 -** Notificação antecipada da data de vencimento da CNH.</p></font>

| UC08                  | Notificação antecipada da data de vencimento da CNH                                                                                                                                                                                                                                                    |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Descrição**         | O sistema verifica periodicamente a data de vencimento da CNH registrada e envia uma notificação ao usuário com antecedência de 30 dias.                                                                                                                                                               |
| **Atores**            | Sistema (automação), Usuário                                                                                                                                                                                                                                                                           |
| **Pré-condição**      | O usuário deve ter uma CNH cadastrada no sistema com data de validade registrada.                                                                                                                                                                                                                      |
| **Pós-condição**      | O usuário recebe uma notificação push alertando sobre o vencimento próximo da CNH.                                                                                                                                                                                                                     |
| **Fluxo principal**   | 1. O sistema agenda uma verificação periódica das datas de vencimento da CNH.<br>2. O sistema identifica que a CNH do usuário vencerá em 30 dias.<br>3. O sistema envia uma notificação para o dispositivo do usuário.<br>4. O usuário visualiza a notificação e pode acessar mais informações no app. |
| **Fluxo alternativo** | 1a. Se a CNH já estiver vencida ou for inválida, o sistema não enviará a notificação.                                                                                                                                                                                                                  |
| **Fluxo de exceções** | 1e. Se houver falha no envio da notificação, o sistema registra o erro e tenta reenviar na próxima execução da rotina programada.                                                                                                                                                                      |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

### Área educacional com explicações e vídeos

Abaixo, na tabela 12, está especificado o caso de uso para a funcionalidade de "Área educacional com explicações e vídeos".

<font size="3"><p style="text-align: center">**Tabela 12 -** Área educacional com explicações e vídeos.</p></font>

| **Campo**             | **Descrição**                                                                                                                                                                                                                                                                                                        |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **UC09**              | Área educacional com explicações e vídeos                                                                                                                                                                                                                                                                            |
| **Descrição**         | Este caso de uso descreve a interação do usuário com a área educacional do aplicativo do Detran-DF, onde é possível acessar vídeos e textos educativos sobre trânsito, legislação e cidadania no trânsito.                                                                                                           |
| **Atores**            | Usuário (cidadão), Sistema do Detran-DF                                                                                                                                                                                                                                                                              |
| **Pré-condição**      | O usuário deve estar com o aplicativo instalado e com acesso à internet.                                                                                                                                                                                                                                             |
| **Pós-condição**      | O usuário acessou, visualizou ou interagiu com os conteúdos educacionais da plataforma.                                                                                                                                                                                                                              |
| **Fluxo principal**   | 1. O usuário abre o aplicativo do Detran-DF. <br> 2. O usuário navega até a “Área Educacional”. <br> 3. O sistema exibe os temas disponíveis. <br> 4. O usuário seleciona um tema. <br> 5. O sistema apresenta vídeos e textos explicativos sobre o tema. <br> 6. O usuário assiste aos vídeos ou lê as explicações. |
| **Fluxo alternativo** | A1. O usuário utiliza o campo de busca para encontrar um tema específico. <br> A2. O sistema exibe apenas os conteúdos relacionados ao termo buscado.                                                                                                                                                                |
| **Fluxo de exceções** | E1. Falha na conexão com a internet. <br> → O sistema exibe mensagem de erro: “Conexão indisponível. Verifique sua internet.” <br> E2. Nenhum conteúdo disponível no momento. <br> → O sistema informa que novos conteúdos serão adicionados em breve.                                                               |


<font size="3"><p style="text-align: center">Fonte: [Pedro Camilo](https://github.com/PedrooCamilo) , 2025.</p></font>

### Explicações acessíveis sobre siglas

Abaixo, na tabela 13, está especificado o caso de uso para a funcionalidade de "Explicações acessíveis sobre siglas".

<font size="3"><p style="text-align: center">**Tabela 13 -** Explicacoes acessíveis sobre siglas.</p></font>

| **Campo**             | **Descrição**                                                                                                                                                                                                                                                                             |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **UC10**              | Explicações acessíveis sobre siglas                                                                                                                                                                                                                                                       |
| **Descrição**         | Este caso de uso descreve como o usuário pode acessar explicações simples e claras sobre siglas como RENAVAM, CRLV e CNH diretamente nas telas onde elas aparecem, facilitando o entendimento do conteúdo.                                                                                |
| **Atores**            | Usuário (cidadão), Sistema do Detran-DF                                                                                                                                                                                                                                                   |
| **Pré-condição**      | O usuário deve estar utilizando o aplicativo e visualizar uma sigla desconhecida em alguma funcionalidade.                                                                                                                                                                                |
| **Pós-condição**      | O usuário compreende o significado da sigla consultada.                                                                                                                                                                                                                                   |
| **Fluxo principal**   | 1. O usuário acessa uma funcionalidade no aplicativo (ex: consulta de veículo). <br> 2. O usuário se depara com uma sigla (ex: RENAVAM). <br> 3. O usuário toca no ícone de ajuda ao lado da sigla. <br> 4. O sistema exibe um popup com o significado da sigla e uma explicação simples. |
| **Fluxo alternativo** | A1. O usuário acessa uma seção dedicada com a lista completa de siglas e significados. <br> A2. O sistema exibe a lista e permite busca por sigla.                                                                                                                                        |
| **Fluxo de exceções** | E1. A sigla não possui explicação cadastrada. <br> → O sistema exibe a mensagem: “Estamos trabalhando para adicionar essa explicação. Você pode enviar sua dúvida aqui.”                                                                                                                  |


<font size="3"><p style="text-align: center">Fonte: [Pedro Camilo](https://github.com/PedrooCamilo) , 2025.</p></font>

### Notificação de multas e prazos com desconto

Abaixo, na tabela 14, está especificado o caso de uso para a funcionalidade de "Notificação de multas e prazos com desconto".

<font size="3"><p style="text-align: center">**Tabela 14 -** Notificação de multas e prazos com desconto.</p></font>

| UC12                  | Notificação de multas e prazos com desconto                                                                                                                                            |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Permite que o sistema informe o usuário sobre uma multa registrada, indicando que ainda está dentro do prazo para pagamento com desconto.                                                                                                   |
| **Atores**            | 	Usuário, Sistema do Detran DF                                                                                                           |
| **Pré-condição**      | 	O usuário deve estar autenticado e possuir multa registrada no sistema com prazo de desconto vigente.                                                                            |
| **Pós-condição**      | O usuário é notificado e pode visualizar detalhes da multa e formas de pagamento com desconto.                                                                       |
| **Fluxo principal**   | 	1. O sistema identifica multa com prazo ativo.
2. Notifica o usuário via app.
3. O usuário acessa a notificação.
4. Visualiza valor, vencimento e formas de pagamento.
5. Pode prosseguir para pagar diretamente pelo sistema.                                        |
| **Fluxo alternativo** | O usuário ignora a notificação: o sistema salva o status e exibe lembretes posteriormente. |
| **Fluxo de exceções** | - E1. Falha de comunicação com o servidor: o sistema tenta novamente mais tarde.
- E2. Multa vencida durante o processo: o sistema atualiza o status e remove desconto.                                           |

<font size="3"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/maaduh) , 2025.</p></font>

### Aviso automático em caso de roubo/recuperação do carro

Abaixo, na tabela 15, está especificado o caso de uso para a funcionalidade de "Aviso automático em caso de roubo/recuperação do carro".

<font size="3"><p style="text-align: center">**Tabela 15 -** Aviso automático em caso de roubo/recuperação do carro.</p></font>

| UC12                  | Aviso automático em caso de roubo/recuperação do carro                                                                                                                                          |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Permite que o sistema informe o usuário sobre a existência de uma ocorrência relacionada ao seu veículo (ex.: roubo ou recuperação).                                                                                                   |
| **Atores**            | Usuário, Sistema do Detran DF                                                                                                           |
| **Pré-condição**      | O usuário deve estar logado no sistema e possuir veículo vinculado com ocorrência registrada.                                                                            |
| **Pós-condição**      | O usuário é notificado da ocorrência e pode tomar ações informadas (ex.: bloqueio, denúncia, atualização de dados).                                                                      |
| **Fluxo principal**   | 1. O sistema detecta uma ocorrência no veículo.
2. Notifica o usuário.
3. O usuário acessa a notificação.
4. Visualiza detalhes e orientações.
5. Pode realizar ações como entrar em contato com a autoridade competente.                                        |
| **Fluxo alternativo** | O usuário ignora a notificação: o sistema mantém a notificação em destaque no app até ser lida. |
| **Fluxo de exceções** | Ocorre erro ao recuperar os dados da ocorrência: exibir mensagem e sugerir tentar novamente mais tarde.                                          |

<font size="3"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/maaduh) , 2025.</p></font>

### Agendamento online para provas teóricas e práticas

Abaixo, na tabela 16, está especificado o caso de uso para a funcionalidade de "Agendamento online para provas teóricas e práticas".

<font size="3"><p style="text-align: center">**Tabela 16 -** Agendamento online para provas teóricas e práticas.</p></font>

| UC13                  | Agendamento online para provas teóricas e práticas |
| --------------------- | --------------------------------------- |
| **Descrição**         | Permite que o usuário visualize os dias e horários livres para se realizar as provas, assim como fazer o agendamento das mesmas. |
| **Atores**            | Usuário (ator principal), Sistema |
| **Pré-condição**      | O usuário deve estar autenticado no sistema e ter acesso aos serviços disponíveis para agendamento. |
| **Pós-condição**      | Um agendamento é criado e armazenado no sistema. O usuário recebe uma confirmação com os detalhes do agendamento. |
| **Fluxo principal**   | 1. O usuário acessa a área de agendamentos.<br>2. O sistema exibe os serviços disponíveis.<br>3. O usuário seleciona o serviço desejado.<br>4. O sistema apresenta os horários e locais disponíveis.<br>5. O usuário escolhe data, horário e local.<br>6. O sistema solicita confirmação.<br>7. O usuário confirma.<br>8. O sistema registra o agendamento e apresenta a confirmação ao usuário. |
| **Fluxo alternativo** | 5a. O horário selecionado está indisponível: o sistema exibe uma mensagem e solicita nova escolha. <br>5b. O usuário escolhe outra data/horário/local. |
| **Fluxo de exceções** | - E1. Falha de conexão com o sistema: exibir mensagem de erro e tentar nova conexão. <br>- E2. Dados obrigatórios não preenchidos: sistema alerta e impede a confirmação do agendamento. <br>- E3. Usuário tenta selecionar prova prática mas não fez ou não passou na prova teórica: Sistema alerta e impede a confirmação do agendamento. |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu) , 2025.</p></font>

### Acessibilidade para diferentes perfis de usuários

Abaixo, na tabela 17, está especificado o caso de uso para a funcionalidade de "Acessibilidade para diferentes perfis de usuários".

<font size="3"><p style="text-align: center">**Tabela 17 -** Acessibilidade para diferentes perfis de usuários.</p></font>

| UC14                  | Acessibilidade para diferentes perfis de usuários |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Permite que o usuário utilize o aplicativo da maneira mais confortável |
| **Atores**            | Usuário (ator principal), Sistema, extensões ou aplicativos de terceiros |
| **Pré-condição**      | O usuário possuir o aplicativo instalado e tenta o acessar. |
| **Pós-condição**      | O usuário não tem reclamações sobre o uso do sistema |
| **Fluxo principal**   | 1. O usuário acessa o aplicativo. <br>2. A extensão, aplicativo ou o próprio sistema modifica o aplicativo visual ou sonoramente. |
| **Fluxo alternativo** | 1a. O usuário pede auxílio para outra pessoa para configurar o aplicativo.  |
| **Fluxo de exceções** | - E1. Sistema não tem suporte para a extensão ou aplicativo: Sistema alerta e impede o acesso. <br>- E2. Sistema não possui configurações de acessibilidade: Sistema apresenta um botão de reclamações. |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu) , 2025.</p></font>

### Histórico de versão

| Versão |    Data    |                                                                              Descrição                                                                               |                     Autor                     |                    Revisor                    |
| :----: | :--------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------: | :-------------------------------------------: |
|  1.0   | 14/05/2025 |                                                                         criação do documento                                                                         | [Giovana Barbosa](https://github.com/gio221)  |  [João Lobo](https://github.com/joaolobo10)   |
|        |
|  1.1   | 15/05/2025 |                                                                  introdução, objetivo e metodologia                                                                  | [Giovana Barbosa](https://github.com/gio221)  |  [João Lobo](https://github.com/joaolobo10)   |
|        |
|  1.2   | 16/05/2025 | Criação de todas tabelas de especificação de cenários assim como a tabela modelo, e a tabela adição de símbolos da tabela dos componentes do diagrama de caso de uso |  [João Lobo](https://github.com/joaolobo10)   | [Giovana Barbosa](https://github.com/gio221)  |
|  1.3   | 16/05/2025 |                                    Tabela das funcionalidades Realizar agendamento de serviços e Realizar agendamento de serviços                                    | [Giovana Barbosa](https://github.com/gio221)  | [Luiz Bessa](https://github.com/lfelipebessa) |
|  1.4   | 16/05/2025 |                                                       Tabela de quem ficou responsavel por qual funcionalidade                                                       | [Giovana Barbosa](https://github.com/gio221)  | [Luiz Bessa](https://github.com/lfelipebessa) |
|  1.5   | 17/05/2025 |                                                            Realizando as tabelas 11 e 12 dos casos de uso                                                            | [Luiz Bessa](https://github.com/lfelipebessa) |  [João Lobo](https://github.com/joaolobo10)   |
|  1.6   | 17/05/2025 |            Realização das tabelas de caso de uso das funcionalidades: Chat com IA para tirar dúvidas e Atendimento ao vivo com servidor do Detran-DF uso             |  [João Lobo](https://github.com/joaolobo10)   | [Eric Akio](https://github.com/eric-kingu) |
| 1.7 | 17/05/2025 | Realização das tabelas de caso de uso: Agendamento online para provas teóricas e práticas, e Acessibilidade para diferentes perfis de usuário | [Eric Akio](https://github.com/eric-kingu) | [Pedro Camilo](https://github.com/PedrooCamilo) |
|  1.8   | 17/05/2025 |            Realização das tabelas de caso de uso das funcionalidades, Área educacional com explicações e vídeos, Explicações acessíveis sobre siglas             |  [Pedro Camilo](https://github.com/PedrooCamilo)   |                  [Gabriel Mendes](https://github.com/gbevi)                             |
|  1.9   | 17/05/2025 |            Realização das tabelas de caso de uso das funcionalidades, Integração CNH digital e gov.br, área de autoescolas             |  [Gabriel Mendes](https://github.com/gbevi)   | [Maria Eduarda](https://github.com/maaduh) |
|  2.0   | 17/05/2025 |            Realização das tabelas de caso de uso das funcionalidades, notificação de multas e prazos com desconto, aviso automático em caso de roubo/recuperação do carro             |  [Maria Eduarda](https://github.com/maaduh)   | [Giovana Barbosa](https://github.com/gio221)  |

