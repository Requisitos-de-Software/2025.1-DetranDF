# Introdução

O léxico é uma ferramenta essencial na Engenharia de Requisitos, utilizada para descrever detalhadamente os termos específicos de um domínio. No contexto do aplicativo Detran-DF, o léxico contribui para identificar expressões e conceitos relevantes ao sistema de serviços digitais relacionados ao trânsito, garantindo clareza e padronização na comunicação entre os envolvidos no projeto.

# Objetivo

O objetivo do léxico no projeto do aplicativo Detran-DF é documentar de forma clara e consistente os termos técnicos e operacionais do sistema. Essa prática facilita o entendimento comum entre os stakeholders, reduz ambiguidades e contribui para uma definição precisa dos requisitos, promovendo alinhamento durante todo o ciclo de desenvolvimento.

# Metodologia

A aplicação do léxico no Detran-DF envolve a identificação de termos relevantes por meio de entrevistas, análises de documentos e cenários de uso. Os termos são classificados (verbo, substantivo ou estado) e descritos com uma noção (significado) e impacto (efeitos no sistema). O léxico é validado com os stakeholders e atualizado continuamente conforme mudanças no projeto. Ele é integrado às atividades de engenharia de requisitos, como casos de uso, especificações e testes, garantindo consistência semântica em toda a aplicação.

<font size="3"><p style="text-align: center">**Tabela 1 -** Formato do Léxico.</p></font>

| Léxico      | Classificação          | Noção                   | Impacto                                 | Sinônimo       | Autor                               |
| ----------- | ---------------------- | ----------------------- | --------------------------------------- | -------------- | ----------------------------------- |
| LXX - Nome. | Objeto, Verbo, Estado. | Significado do símbolo. | Efeito, uso ou ocorrência na aplicação. | Termo similar. | Integrante responsável pelo léxico. |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

<font size="3"><p style="text-align: center">**Tabela 2 -**Distribuição de funcionalidades entre os integrantes para elaboração dos lexicos .</p></font>

| Numero do Lexico |                  Integrante                   |                          Cenário                          |
| :--------------: | :-------------------------------------------: | :-------------------------------------------------------: |
|       L01        | [Giovana Barbosa](https://github.com/gio221)  |  Realizar agendamentos presenciais (vistoria, CNH, etc.)  |
|       L02        | [Giovana Barbosa](https://github.com/gio221)  |          Sistema de pagamento de taxas e débitos          |
|       L03        | [Luiz Bessa](https://github.com/lfelipebessa) |        Histórico de Pesquisas e Serviços Recentes         |
|       L04        | [Luiz Bessa](https://github.com/lfelipebessa) |    Notificação antecipada da data de vencimento da CNH    |
|       L03        |  [João Lobo](https://github.com/joaolobo10)   |              Chat com IA para tirar dúvidas               |
|       L04        |  [João Lobo](https://github.com/joaolobo10)   | Atendimento ao vivo com servidor do DETRAN via chat/vídeo |

## Objeto

Nos léxicos do tipo Objeto é definido: o objeto, outros objetos com os quais se relacionam e as ações que poderão ser empregadas ao objeto. Na tabela 02 logo abaixo estão descritos os léxicos do tipo objeto.

<font size="3"><p style="text-align: center">**Tabela 2 -** Léxicos do tipo Objeto.</p></font>

| Léxico                                           | Classificação | Noção                                                                                               | Impacto                                                                                                      | Sinônimo                            | Autor                                         |
| ------------------------------------------------ | ------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | ----------------------------------- | --------------------------------------------- |
| L02 - Autorização de estacionamento              | Objeto.       | Concede ao idoso o direito de utilizar vagas preferenciais em áreas públicas e privadas             | Documento físico ou digital que comprova o direito de estacionar em vaga especial de idoso                   | Permissão, Cartão de Estacionamento | [Giovana Barbosa](https://github.com/gio221)  |
| L03 - Histórico de Pesquisas e Serviços Recentes | Objeto        | Registro que armazena os últimos acessos a serviços ou pesquisas feitas pelo usuário dentro do app. | Permite que o sistema exiba atalhos rápidos baseados em ações anteriores do usuário, otimizando a navegação. | Histórico, Atividades Recentes      | [Luiz Bessa](https://github.com/lfelipebessa) |
| L04 -Usuário                                     | Objeto        | Pessoa que utiliza o aplicativo do Detran DF.                                                       | Interage com o sistema para tirar dúvidas ou ser atendido.                                                   | Cidadão, Cliente                    | [João Lobo](https://github.com/joaolobo10)    |
| L05 - Aplicativo                                 | Objeto        | Plataforma móvel do Detran DF.                                                                      | Canal para acessar os serviços digitais, como chat com IA ou atendimento ao vivo.                            | App                                 | [João Lobo](https://github.com/joaolobo10)    |
| L06 - Chat de dúvidas                            | Objeto        | Interface de comunicação com a IA.                                                                  | Permite interação automática para esclarecer dúvidas frequentes.                                             | Chatbot, Assistente virtual         | [João Lobo](https://github.com/joaolobo10)    |
| L07 - Inteligência Artificial                    | Objeto        | Sistema automatizado de resposta.                                                                   | Consulta a base de dados e responde perguntas.                                                               | IA, Bot                             | [João Lobo](https://github.com/joaolobo10)    |
| L08 - Servidor                                   | Objeto        | Funcionário do Detran DF responsável pelo atendimento.                                              | Presta atendimento remoto ao cidadão.                                                                        | Atendente, Funcionário              | [João Lobo](https://github.com/joaolobo10)    |
| L09 - Agendamento                                | Objeto        | Ato de marcar data e horário para atendimento.                                                      | Pré-requisito para iniciar o atendimento ao vivo.                                                            | Reserva de horário                  | [João Lobo](https://github.com/joaolobo10)    |
| L10 - Atendimento ao vivo                        | Objeto        | Sessão de conversa com servidor via chat, voz ou vídeo.                                             | Resolve dúvidas com presença humana.                                                                         | Sessão remota                       | [João Lobo](https://github.com/joaolobo10)    |

<font size="3"><p style="text-align: center"> [Giovana Barbosa](https://github.com/gio221), [Luiz Bessa](https://github.com/lfelipebessa), [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## Verbo

Nos léxicos do tipo Verbo, se referem às ações que os usuários podem fazer dentro do aplicativo. Deve-se descrever: quem realiza, quando realiza, quais os processos realizados e quais os reflexos da ação no ambiente. Abaixo na tabela 03 estão descritos os léxicos do tipo verbo.

<font size="3"><p style="text-align: center">**Tabela 3 -** Léxicos do tipo Verbo.</p></font>

| Léxico                                        | Classificação | Noção                                                                                                  | Impacto                                                                                       | Sinônimo                          | Autor                                         |
| --------------------------------------------- | ------------- | ------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | --------------------------------- | --------------------------------------------- |
| L01 - Realizar agendamentos presenciais       | Verbo         | Permite ao usuário reservar um horário para atendimento presencial (vistoria, CNH, etc.)               | Ação que permite ao usuário marcar previamente um atendimento em unidades físicas do serviço. | Agendar, Reservar, Marcar horário | [Giovana Barbosa](https://github.com/gio221)  |
| L02 - Solicitar autorização de estacionamento | Verbo         | Permite que idosos requisitem formalmente o direito de estacionar em vagas preferenciais               | Ação de enviar uma solicitação ao sistema para obter uma autorização de estacionamento.       | Requerer, Pedir autorização       | [Giovana Barbosa](https://github.com/gio221)  |
| L03 - Notificar vencimento da CNH             | Verbo         | Ação automatizada do sistema que envia um lembrete ao usuário sobre a proximidade do vencimento da CNH | Garante que o usuário seja alertado com antecedência e possa renovar sua habilitação a tempo  | Avisar, Alertar                   | [Luiz Bessa](https://github.com/lfelipebessa) |
| L04 - Acessar aplicativo                      | Verbo         | Ação de abrir o aplicativo do Detran DF.                                                               | Etapa inicial para uso dos serviços.                                                          | Entrar no app                     | [João Lobo](https://github.com/joaolobo10)    |
| L05 - Perguntar                               | Verbo         | Ação do usuário ao formular uma dúvida.                                                                | Gera consulta na base de dados da IA.                                                         | Questionar                        | [João Lobo](https://github.com/joaolobo10)    |
| L06 - Responder                               | Verbo         | Ação da IA ao apresentar uma solução.                                                                  | Fornece a informação solicitada.                                                              | Informar                          | [João Lobo](https://github.com/joaolobo10)    |
| L07 - Fechar chat                             | Verbo         | Ação do usuário ao encerrar a conversa com a IA.                                                       | Finaliza a sessão.                                                                            | Encerrar atendimento              | [João Lobo](https://github.com/joaolobo10)    |
| L08 - Agendar                                 | Verbo         | Escolher data e horário para atendimento ao vivo.                                                      | Garante que o atendimento ocorra no momento apropriado.                                       | Marcar horário                    | [João Lobo](https://github.com/joaolobo10)    |
| L09 - Iniciar atendimento                     | Verbo         | Ação de começar a conversa com o servidor.                                                             | Dá início ao processo de atendimento remoto.                                                  | Começar sessão                    | [João Lobo](https://github.com/joaolobo10)    |
| L10 - Comparecer                              | Verbo         | Entrar na sessão no horário marcado.                                                                   | Requisito para que o atendimento ocorra.                                                      | Participar                        | [João Lobo](https://github.com/joaolobo10)    |

<font size="3"><p style="text-align: center"> [Giovana Barbosa](https://github.com/gio221), [Luiz Bessa](https://github.com/lfelipebessa), [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## Estado

Os léxicos do tipo Estado se referem às condições ou situações específicas que o aplicativo pode apresentar. São definidos: qual o significado das ações e quais levaram a esse estado, e mostrar quais outros estados e ações que pode-se chegar e realizar a partir do estado atual. Abaixo na tabela 04 são elencados os léxicos do tipo estado.

<font size="3"><p style="text-align: center">**Tabela 4 -** Léxicos do tipo Estado.</p></font>

| Léxico                     | Classificação | Noção                                                                 | Impacto                                                          | Sinônimo               | Autor                                      |
| -------------------------- | ------------- | --------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------------------- | ------------------------------------------ |
| L01 - Conectado            | Estado        | Situação em que o usuário está online.                                | Necessário para utilizar IA ou participar de atendimento remoto. | Online                 | [João Lobo](https://github.com/joaolobo10) |
| L02 - Fora do escopo       | Estado        | Quando a dúvida do usuário não pertence à base de conhecimento da IA. | A IA redireciona o usuário para atendimento humano.              | Dúvida não reconhecida | [João Lobo](https://github.com/joaolobo10) |
| L03 - Limite de interações | Estado        | Quantidade máxima de perguntas que o usuário pode fazer por dia.      | Impede o uso excessivo do chat com IA.                           | Cota diária            | [João Lobo](https://github.com/joaolobo10) |
| L04 - Ausente              | Estado        | Situação em que o usuário não comparece no horário agendado.          | Atendimento é cancelado automaticamente.                         | Não comparecimento     | [João Lobo](https://github.com/joaolobo10) |
| L05 - Fora do horário      | Estado        | Tentativa de acesso antes ou depois do horário marcado.               | O sistema bloqueia a conexão.                                    | Atraso                 | [João Lobo](https://github.com/joaolobo10) |
| L06 - Em atendimento       | Estado        | Situação em que o usuário está conectado ao servidor.                 | Indica que a sessão está em andamento.                           | Sessão ativa           | [João Lobo](https://github.com/joaolobo10) |
| L07 - Conexão instável     | Estado        | Falha na comunicação entre usuário e servidor.                        | Pode provocar reagendamento do atendimento.                      | Problema de rede       | [João Lobo](https://github.com/joaolobo10) |

<font size="3"><p style="text-align: center">[João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## Histórico de versão

| Versão |    Data    |                                                                    Descrição                                                                     |                     Autor                     |                    Revisor                    |
| :----: | :--------: | :----------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------: | :-------------------------------------------: |
|  1.0   | 14/05/2025 |                                                               criação do documento                                                               | [Giovana Barbosa](https://github.com/gio221)  |  [João Lobo](https://github.com/joaolobo10)   |
|  1.1   | 14/05/2025 |                                                   adicionei introdução, objetivo e metodologia                                                   | [Giovana Barbosa](https://github.com/gio221)  |  [João Lobo](https://github.com/joaolobo10)   |
|  1.2   | 16/05/2025 |                                      Adição de tabelas padronizadas para léxicos de estado, verbo e objeto                                       |  [João Lobo](https://github.com/joaolobo10)   | [Giovana Barbosa](https://github.com/gio221)  |
|  1.3   | 16/05/2025 |                                                             Adição do lexico 01 e 02                                                             | [Giovana Barbosa](https://github.com/gio221)  | [Luiz Bessa](https://github.com/lfelipebessa) |
|  1.4   | 17/05/2025 |                                                             Adição do lexico 03 e 04                                                             | [Luiz Bessa](https://github.com/lfelipebessa) |  [João Lobo](https://github.com/joaolobo10)   |
|  1.5   | 17/05/2025 | Adição dos léxicos de objeto, verbo e estado, das funcionalidade Chat com IA para tirar dúvidas, e Atendimento com servidor do Detran-DF ao vivo |  [João Lobo](https://github.com/joaolobo10)   |                                               |
