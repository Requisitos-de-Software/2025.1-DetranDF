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
|       L05        |  [João Lobo](https://github.com/joaolobo10)   |              Chat com IA para tirar dúvidas               |
|       L06        |  [João Lobo](https://github.com/joaolobo10)   | Atendimento ao vivo com servidor do DETRAN via chat/vídeo |
| L07 | [Eric Akio](https://github.com/eric-kingu) | Realizar agendamentos online de provas teóricas e práticas |
| L08 | [Eric Akio](https://github.com/eric-kingu) | Acessibilidade para diferentes tipos de usuários |
|       L09        |[Pedro Camilo](https://github.com/PedrooCamilo)| Área educacional com explicações e vídeos                 |
|       L010        |[Pedro Camilo](https://github.com/PedrooCamilo)| Acesso rápido a explicações de siglas                     |
|       L011        |[Gabriel Mendes](https://github.com/gbevi)| Integração com CNH digital e gov.br                     |
|       L012        |[Gabriel Mendes](https://github.com/gbevi)| Área para auto-escolas                     |
|       L013        |[Maria Eduarda](https://github.com/maaduh)| Notificação de multas e prazos com desconto                     |
|       L014        |[Maria Eduarda](https://github.com/maaduh)| Aviso automático em caso de roubo/recuperação do carro                  |

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
| L11 - Prova | Objeto | Avaliação de conhecimentos teóricos ou práticos | Permite dar continuidade ao processo de obtenção da CNH | Avaliação | [Eric Akio](https://github.com/eric-kingu) |
| L12 - Acessibilidade | Objeto | Garantia que todos tenham autonomia para realizar tarefas | Facilita o uso do aplicativo para alguns usuários | Alcance, acesso | [Eric Akio](https://github.com/eric-kingu) |
| L13 - Área educacional | Objeto            | Seção do aplicativo dedicada a conteúdos informativos sobre trânsito, legislação e segurança. | Oferece ao usuário vídeos e textos educativos, promovendo a conscientização e o aprendizado. | Central de aprendizado, Conteúdo educativo | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L14 - Explicação de sigla | Objeto            | Texto curto e acessível que esclarece o significado de siglas utilizadas no app (ex: RENAVAM, CRLV). | Facilita a compreensão dos termos técnicos, tornando o aplicativo mais inclusivo. | Definição de sigla, Ajuda de sigla | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L15 - Integração CNH digital e gov.br | Objeto            | Integração de APIs | Permite que usuáries acessem e validem sua CNH Digital dentro do aplicativo, integrando as funcionalidades | [Gabriel Mendes](https://github.com/gbevi) |
| L16 - Área para auto-escolas | Objeto            | Módulo de interação| Cria um espaço dedicado para autoescolas publicarem informações e receberem avaliações e comentários de alunos/clients | [Gabriel Mendes](https://github.com/gbevi) |
|L17 - Notificação de multas e prazos com desconto | Objeto | Alerta enviado ao usuário sobre novas multas, destacando prazos com desconto para pagamento | Facilita o pagamento antecipado com desconto, evitando atrasos e prejuízos | Alerta de infração, Aviso de desconto | [Maria Eduarda](https://github.com/maaduh) |
|L18 - Aviso automático em caso de roubo/recuperação do carro | Objeto | Notificação gerada quando o status do veículo muda para roubado ou recuperado, via integração com sistemas oficiais | Informa rapidamente o usuário sobre situações críticas envolvendo o seu veículo | Alerta de segurança, Notificação de status veicular | [Maria Eduarda](https://github.com/maaduh) |

<font size="3"><p style="text-align: center"> [Giovana Barbosa](https://github.com/gio221), [Luiz Bessa](https://github.com/lfelipebessa), [João Lobo](https://github.com/joaolobo10), [Eric Akio](https://github.com/eric-kingu), [Pedro Camilo](https://github.com/PedrooCamilo), [Gabriel Mendes](https://github.com/gbevi), [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>


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
| L11 - Acessar área educacional    | Verbo             | Acessar os conteúdos explicativos em texto e vídeo. | Inicia a navegação por conteúdos educativos, fortalecendo a educação no trânsito. | Visualizar conteúdo, Explorar material educativo | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L12 - Assistir vídeo educativo | Verbo             | Ação de iniciar a reprodução de um vídeo explicativo dentro da área educacional.  | Proporciona aprendizado visual sobre normas de trânsito e conduta responsável.    | Ver vídeo, Reproduzir conteúdo                   | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L13 - Ler explicação textual   | Verbo             | Ler um conteúdo em texto sobre um tema do Detran.                                    | Oferece conhecimento de forma acessível e rápida.                                 | Consultar texto, Ler conteúdo                    | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L14 - Consultar sigla | Verbo             | Ação de tocar ou clicar sobre uma sigla para obter sua explicação.    | Permite ao usuário compreender imediatamente o significado sem sair da tela atual. | Visualizar significado    | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L15 - Buscar sigla    | Verbo             | Ação de procurar por uma sigla em uma lista geral com campo de busca. | Oferece um canal direto para tirar dúvidas sobre termos técnicos.                  | Pesquisar sigla, Procurar | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L16 - Realizar agendamentos de provas       | Verbo         | Permite ao usuário reservar um horário para realização da prova teórica ou prática | Ação que permite ao usuário marcar previamente a realização das provas | Agendar, Reservar, Marcar horário | [Eric Akio](https://github.com/eric-kingu) |
| L17 - Integração com CNH digital e gov.br      | Verbo         | Possibilita que usuários validem e utilizem a CNH Digital autenticando-se via Gov BR dentro do app. | Garante autenticidade dos dados de habilitação e simplifica o login, reduzindo fraudes e etapas manuais. | Vincular, Conectar, Sincronizar dados|[Gabriel Mendes](https://github.com/gbevi) |
| L18 - Área para auto-escolas      | Verbo         | 	Permite que alunos/clientes publiquem avaliações e comentários sobre serviços de autoescolas. | Melhora a transparência e incentiva a qualidade do serviço por meio de feedback público. | Classificar, Revisar, Comentar | [Eric Akio](https://github.com/eric-kingu) |
| L19 - Notificar multa e prazo com desconto | Verbo | Ação automatizada do sistema que envia ao usuário um aviso sobre nova multa, destacando prazos com desconto para pagamento | Auxilia no pagamento rápido, evitando juros e aproveitando descontos legais | Avisar multa, Alertar desconto | [Maria Eduarda](https://github.com/maaduh) |
| L20 - Avisar sobre roubo ou recuperação do veículo | Verbo | Ação do sistema que comunica automaticamente o usuário quando há registro de roubo ou recuperação do veículo | Garante resposta rápida e aumenta a segurança do usuário ao ser informado em tempo real | Notificar roubo, Comunicar status veicular | [Maria Eduarda](https://github.com/maaduh) |


<font size="3"><p style="text-align: center"> [Giovana Barbosa](https://github.com/gio221), [Luiz Bessa](https://github.com/lfelipebessa), [João Lobo](https://github.com/joaolobo10), [Eric Akio](https://github.com/eric-kingu), [Pedro Camilo](https://github.com/PedrooCamilo), [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>


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
| L08 - Conteúdo carregado  | Estado            | Situação em que o conteúdo (vídeos e texto educativos) foi carregado com sucesso na tela do usuário. | Garante que o usuário pode iniciar o consumo do material educativo.     | Conteúdo disponível    | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L09 - Vídeo em reprodução | Estado            | Momento em que o vídeo está sendo reproduzido no aplicativo.                              | Indica que o usuário está consumindo ativamente o conteúdo. | Vídeo em execução      | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L10 - Sigla explicada    | Estado            | Situação em que a explicação da sigla foi exibida ao usuário com sucesso. | Garante que o usuário teve acesso à informação desejada.                                   | Explicação visível   | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L11 - Sigla desconhecida | Estado            | Situação em que a sigla não possui explicação cadastrada no sistema.      | Informa ao sistema que a sigla deve ser adicionada ou reportada como ausência de conteúdo. | Sigla não encontrada | [Pedro Camilo](https://github.com/PedrooCamilo) |
| L12 - CNH validada   | Estado            | O(a) usuário(a) concluiu a autenticação via Gov BR e sua CNH Digital foi verificada no app. | Desbloqueia recursos que exigem dados oficiais de habilitação (ex.: geração de documentos, consulta de infrações).       | Habilitação confirmada, CNH ativa   | [Gabriel Mendes](https://github.com/gbevi) |
| L13 - Auto-escola validada | Estado            | A ficha de uma autoescola recebeu pelo menos uma avaliação/comentário e foi registrada no sistema.     | Permite exibir média de notas e feedbacks, influenciando decisões de novos(as) alunos. | Avaliação publicada, Feedback recebido | [Gabriel Mendes](https://github.com/gbevi) |
| L14 - Multa notificada com prazo ativo | Estado | Situação em que o sistema já notificou o usuário sobre uma multa, e o prazo com desconto ainda está em vigor | Permite ao usuário se organizar para quitar a multa com redução de valor | Multa com desconto ativo, Alerta vigente | [Maria Eduarda](https://github.com/maaduh) |
| L15 - Veículo com ocorrência registrada | Estado | Indica que o sistema detectou e notificou um registro de roubo ou recuperação do veículo | Informa situação crítica de segurança, permitindo ação imediata do usuário | Roubo detectado, Veículo recuperado | [Maria Eduarda](https://github.com/maaduh) |



<font size="3"><p style="text-align: center">[João Lobo](https://github.com/joaolobo10), [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>

## Histórico de versão

| Versão |    Data    |                                                                    Descrição                                                                     |                     Autor                     |                    Revisor                    |
| :----: | :--------: | :----------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------: | :-------------------------------------------: |
|  1.0   | 14/05/2025 |                                                               criação do documento                                                               | [Giovana Barbosa](https://github.com/gio221)  |  [João Lobo](https://github.com/joaolobo10)   |
|  1.1   | 14/05/2025 |                                                   adicionei introdução, objetivo e metodologia                                                   | [Giovana Barbosa](https://github.com/gio221)  |  [João Lobo](https://github.com/joaolobo10)   |
|  1.2   | 16/05/2025 |                                      Adição de tabelas padronizadas para léxicos de estado, verbo e objeto                                       |  [João Lobo](https://github.com/joaolobo10)   | [Giovana Barbosa](https://github.com/gio221)  |
|  1.3   | 16/05/2025 |                                                             Adição do lexico 01 e 02                                                             | [Giovana Barbosa](https://github.com/gio221)  | [Luiz Bessa](https://github.com/lfelipebessa) |
|  1.4   | 17/05/2025 |                                                             Adição do lexico 03 e 04                                                             | [Luiz Bessa](https://github.com/lfelipebessa) |  [João Lobo](https://github.com/joaolobo10)   |
|  1.5   | 17/05/2025 | Adição dos léxicos de objeto, verbo e estado, das funcionalidade Chat com IA para tirar dúvidas, e Atendimento com servidor do Detran-DF ao vivo |  [João Lobo](https://github.com/joaolobo10)   | [Eric Akio](https://github.com/eric-kingu) |
|  1.6    | 17/06/2025 | Adição dos léxicos de objeto, verbo e estado das funcionalidades: Agendamento online de provas teóricas e práticas, e Acessibilidade para diferentes tipos de usuários | [Eric Akio](https://github.com/eric-kingu) | [Pedro Camilo](https://github.com/PedrooCamilo)  |
|  1.7   | 17/05/2025 | Adição dos léxicos de objeto, verbo e estado, das funcionalidades Área educacional com explicações e vídeos, Acesso rápido a explicações de siglas |  [Pedro Camilo](https://github.com/PedrooCamilo)   | [Maria Eduarda](https://github.com/maaduh) |
|  1.8   | 17/05/2025 | Adição dos léxicos de objeto, verbo e estado, das funcionalidades Integração CNH digital e gov.br, Área de auto-escolas |  [Gabriel Mendes](https://github.com/gbevi)   | [Maria Eduarda](https://github.com/maaduh) |
|  1.9   | 17/05/2025 | Adição dos léxicos de objeto, verbo e estado, das funcionalidades notificação de multas e prazos com desconto, aviso automático em caso de roubo/recuperação do carro |  [Maria Eduarda](https://github.com/maaduh)   |                                        |

