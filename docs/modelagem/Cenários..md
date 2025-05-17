## Introdução

Este documento faz parte do projeto da disciplina de Requisitos de Software e tem como objetivo principal a definição detalhada dos cenários do sistema Detran-DF. Os cenários auxiliam na análise e modelagem de requisitos ao descrever situações específicas que o sistema deve suportar.

## Objetivo

Apresentar de forma clara e estruturada os cenários de uso do sistema Detran-DF

## Metodologia

A elaboração dos cenários foi realizada de forma colaborativa, sendo que cada integrante do grupo ficou responsável pelo desenvolvimento de um cenário específico conforme mencionado na tabela 2. Como metodologia, utilizou-se o modelo descrito por meio do qual um cenário deve conter os seguintes elementos característicos: contexto, atores, objetivos, planejamento, ações, eventos e avaliações (CARROLL, 2002; COOPER, 1999).

Cada cenário foi estruturado conforme o modelo apresentado na Tabela 1, que organiza esses atributos acompanhados de seus respectivos títulos e descrições, assegurando a padronização e a clareza na apresentação das informações.

<font size="3"><p style="text-align: center">**Tabela 1 -** Estrutura de um cenário.</p></font>

| **Item**      | Cenário                                                                                                                                                                                                                                                                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Um nome que identifica o cenário.                                                                                                                                                                                                                                                                                                                           |
| **Objetivo**  | A finalidade do cenário.                                                                                                                                                                                                                                                                                                                                    |
| **Contexto**  | Descreve o estado inicial do cenário, suas pré-condições e locais físicos e tempo.                                                                                                                                                                                                                                                                          |
| **Atores**    | Pessoa ou estruturaorganizacional que tem o papel no cenário.                                                                                                                                                                                                                                                                                               |
| **Recursos**  | Identifica os objetos passivos com os quais lidam os atores.                                                                                                                                                                                                                                                                                                |
| **Episódios** | Cada episódio apresenta uma ação realizada por um ator, na qual participam outros atores utilizando os recursos disponíveis. Um episódio pode pertencer a outro cenário, e neles podemos ter restrições e exceções. As restrições são qualquer coisa que limite um episódio em um cenário. Uma exceção é o tratamento para uma ação excepcional ou de erro. |
| **Restrição** | As características que o cenário deve seguir                                                                                                                                                                                                                                                                                                                |
| **Exceção**   | O que impedem a realização do cenário                                                                                                                                                                                                                                                                                                                       |

<font size="3"><p style="text-align: center">**Tabela 2 -**Distribuição de funcionalidades entre os integrantes para elaboração dos cenários .</p></font>

|                  Integrante                  |                        Cenário                         |
| :------------------------------------------: | :----------------------------------------------------: |
| [Giovana Barbosa](https://github.com/gio221) | Realizar agendamentos presencias (vistoria, CNH, etc.) |
| [Giovana Barbosa](https://github.com/gio221) |       Autorização de estacionamento para idosos        |
|  [Gabriel Mendes](https://github.com/gbevi)  |          Integração com CNH digital e gov.br           |
|  [Gabriel Mendes](https://github.com/gbevi)  |   área para autoescolas com avaliações e comentários   |
|  [Eric Akio](https://github.com/eric-kingu)  |       Agendamento de provas teóricas e práticas        |
|  [Eric Akio](https://github.com/eric-kingu)  |    Acessibilidade para diferentes tipos de usuário     |

## Realizar agendamentos presencias (vistoria, CNH, etc.)

A tabela 3 descreve o cenário do requisito funcional Realizar agendamentos presencias (vistoria, CNH, etc.), que foi rastreada pelas técnicas de elicitação IS01 e OBS001

#### Tabela 3: Cenário - Realizar agendamentos presenciais (vistoria, CNH, etc.)

| **Item**      | **Descrição**                                                                                                                                                                                                                                                                                              |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Agendar atendimento presencial no Detran-DF                                                                                                                                                                                                                                                                |
| **Objetivo**  | Permitir que o usuário realize o agendamento de serviços presenciais como vistoria, renovação da CNH, entre outros, diretamente pelo aplicativo do Detran-DF                                                                                                                                               |
| **Contexto**  | **Local:** Aplicativo do Detran-DF, na seção de agendamentos <br>**Tempo:** Em tempo real <br>**Pré-condição:** O usuário deve possuir cadastro e estar logado no aplicativo                                                                                                                               |
| **Atores**    | Usuários do aplicativo Detran-DF                                                                                                                                                                                                                                                                           |
| **Recursos**  | Conexão com a internet <br>Smartphone com o aplicativo Detran-DF instalado e conta ativa                                                                                                                                                                                                                   |
| **Episódios** | 1. O usuário acessa o aplicativo e seleciona a opção "Agendamentos" <br>2. Escolhe o tipo de serviço (ex: vistoria, CNH) <br>3. Seleciona o posto de atendimento desejado <br>4. Escolhe a data e o horário disponíveis <br>5. Confirma o agendamento <br>6. Recebe a confirmação via aplicativo ou e-mail |
| **Restrição** | Os horários disponíveis são limitados à agenda dos postos físicos do Detran-DF                                                                                                                                                                                                                             |
| **Exceção**   | Falta de vagas no dia/horário desejado <br>Falta de conexão com a internet <br>Aplicativo indisponível por manutenção                                                                                                                                                                                      |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

## Sistema de pagamento de taxas e débitos

A tabela 4 descreve o cenário do requisito funcional Sistema de pagamento de taxas e débitos, que foi rastreada pela técnica de elicitação BS03

#### Tabela 4: Cenário -Sistema de pagamento de taxas e débitos

| **Item**      | **Descrição**                                                                                                                                                                                                                                                                                                                                 |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Pagamento de taxas e débitos no aplicativo Detran-DF                                                                                                                                                                                                                                                                                          |
| **Objetivo**  | Permitir que o usuário visualize e realize o pagamento de taxas, multas, IPVA, licenciamento e demais débitos vinculados ao veículo diretamente pelo aplicativo                                                                                                                                                                               |
| **Contexto**  | **Local:** Aplicativo do Detran-DF, na seção "Débitos e Pagamentos" <br>**Tempo:** Em tempo real <br>**Pré-condição:** O usuário deve estar logado e com veículo vinculado ao seu CPF                                                                                                                                                         |
| **Atores**    | Usuários do aplicativo Detran-DF                                                                                                                                                                                                                                                                                                              |
| **Recursos**  | Conexão com a internet <br>Smartphone com o aplicativo Detran-DF instalado e conta ativa <br>Cartão bancário ou acesso ao internet banking                                                                                                                                                                                                    |
| **Episódios** | 1. O usuário acessa a área de "Débitos e Pagamentos" no aplicativo <br>2. Visualiza os débitos pendentes (multas, taxas, IPVA, etc.) <br>3. Seleciona os itens que deseja pagar <br>4. Escolhe a forma de pagamento (cartão, boleto, Pix) <br>5. Confirma a transação <br>6. Recebe o comprovante digital e atualização automática no sistema |
| **Restrição** | Pagamentos apenas de débitos vinculados ao CPF do usuário ou seus veículos autorizados                                                                                                                                                                                                                                                        |
| **Exceção**   | Erro na transação bancária <br>Falta de conexão com a internet <br>Serviço indisponível temporariamente                                                                                                                                                                                                                                       |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

## Integração com a CNH digital e gov.br

A tabela 5 descreve o cenário do requisito funcional Integração com a CNH digital e gov.br, que foi rastreada pela técnica de elicitação BS11.

#### Tabela 5: Cenário -Integração com a CNH digital e gov.br

| **Item**      | **Descrição**                                                                                                                                                                                                                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Integração com a CNH digital e gov.br                                                                                                                                                                                                                                                                             |
| **Objetivo**  | Permitir que o usuário tenha todas as infromações referentes ao DETRAN centralizadas em um só aplicativo.                                                                                                                                                                                                         |
| **Contexto**  | **Local:** Aplicativo do Detran-DF <br>**Tempo:** Em tempo real <br>**Pré-condição:** O usuário deve estar logado, com CNH ativa e conta no gov.br.br                                                                                                                                                             |
| **Atores**    | Usuários do aplicativo Detran-DF                                                                                                                                                                                                                                                                                  |
| **Recursos**  | Conexão com a internet <br>Smartphone com o aplicativo Detran-DF instalado e conta ativa <br>Conta ativa no gov.br e CNH digital                                                                                                                                                                                  |
| **Episódios** | 1. O usuário acessa o aplicativo DetranDF<br>2. Conecta sua conta do gov.br e CNH digital <br>3. Consegue visualizar e consultar informações da sua CNH digital (dados cadastrais, validade, categorias, etc.) <br>4. Consegue visualizar e consultar informações do gov.br relacionadas ao Detran(débitos, etc.) |
| **Restrição** | A integração depende da disponibilidade e correto funcionamento das APIs do gov.br e da CNH digital.                                                                                                                                                                                                              |
| **Exceção**   | Falha na conexão com a internet.&lt;br>Indisponibilidade temporária dos serviços do gov.br ou da CNH digital.&lt;br>Dados inconsistentes entre as plataformas.                                                                                                                                                    |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Mendes](https://github.com/gbevi) , 2025.</p></font>

## Área para auto-escolas com avaliações, comentários e localização

A tabela 6 descreve o cenário do requisito funcional área para auto-escolas com avaliações, comentários e localização, que foi rastreada pela técnica de elicitação BS08.

#### Tabela 6: Cenário -Área para auto-escolas com avaliações, comentários e localização

| **Item**      | **Descrição**                                                                                                                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Área para auto-escolas com avaliações, comentários e localização                                                                                                                                                  |
| **Objetivo**  | Permitir que o usuário visualize auto-escolas credenciadas na região, visualize as avaliações, avalie, comente sobre outras avaliações e visualize a localização da auto-escola.                                  |
| **Contexto**  | **Local:** Aplicativo do Detran-DF, na seção "Empresas credenciadas" <br>**Tempo:** Em tempo real <br>**Pré-condição:** O usuário deve estar logado                                                               |
| **Atores**    | Usuários do aplicativo Detran-DF                                                                                                                                                                                  |
| **Recursos**  | Conexão com a internet <br>Smartphone com o aplicativo Detran-DF instalado e conta ativa                                                                                                                          |
| **Episódios** | 1. O usuário acessa a área de "Empresas credenciadas" no aplicativo <br>2. Visualiza as auto-escolas da região <br>3. Visualiza as avaliações e localização <br>4. Avalia uma auto-escola ou deixa um comentário. |
| **Restrição** | Auto-escolas desatualizadas ou baixo engajamento de usuários ocorre em informações erradas.                                                                                                                       |
| **Exceção**   | Localização errada <br>Falta de conexão com a internet <br>Serviço indisponível temporariamente                                                                                                                   |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Mendes](https://github.com/gbevi) , 2025.</p></font>

## Agendamento online para provas teóricas e práticas

A tabela 7 descreve o cenário do requisito funcional agendamento online para provas teóricas e práticas, que foi rastreada pela técnica de elicitação BS07

### Tabela 7: Cenário - Agendamento online para provas teóricas e práticas

| **Item**      | **Descrição**                                                                                                                                                                                                                                                                                  |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Agendamento online para provas teóricas e práticas                                                                                                                                                                                                                                             |
| **Objetivo**  | Permitir que o usuário visualize os dias e horários livres para se realizar as provas, assim como fazer o agendamento das mesmas.                                                                                                                                                              |
| **Contexto**  | **Local:** Aplicativo do Detran-DF, na seção "Agendamentos" <br>**Tempo:** Em tempo real <br>**Pré-condição:** O usuário deve estar logado                                                                                                                                                     |
| **Atores**    | Usuários do aplicativo Detran-DF                                                                                                                                                                                                                                                               |
| **Recursos**  | Conexão com a Internet <br>Smartphone com o aplicativo Detran-DF instalado e conta ativa                                                                                                                                                                                                       |
| **Episódios** | 1. O usuário acessa a sessão "Agendamentos" no aplicativo <br>2. Acessa atendimento presencial <br>3. Seleciona a categoria "Provas" <br>4. Seleciona a Unidade de atendimento <br>5. Seleciona data e hora <br>6. Confirma o agendamento <br>7. Recebe a confirmação via aplicativo ou e-mail |
| **Restrição** | Os horários disponíveis são limitados à agenda dos postos físicos do Detran-DF                                                                                                                                                                                                                 |
| **Exceção**   | Falta de vagas no dia/horário desejado <br>Falta de conexão com a internet <br>Aplicativo indisponível por manutenção                                                                                                                                                                          |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu) , 2025.</p></font>

## Acessibilidade para diferentes perfis de usuários

A tabela 8 descreve o cenário do requisito não funcional acessibilidade para diferentes perfis de usuários, que foi rastreada pela técnica de elicitação BS17

### Tabela 8: Cenário - Acessibilidade para diferentes perfis de usuários

| **Item**      | **Descrição**                                                                                                                                                              |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Acessibilidade para diferentes perfis de usuários                                                                                                                          |
| **Objetivo**  | Permitir que o usuário utilize o aplicativo da maneira mais confortável                                                                                                    |
| **Contexto**  | **Local:** Aplicativo do Detran-DF <br>**Tempo:** Em tempo real <br>**Pré-condição:** O usuário deve estar logado, com ao menos uma configuração de acessibilidade ativada |
| **Atores**    | Usuários do aplicativo Detran-DF                                                                                                                                           |
| **Recursos**  | Conexão com a Internet <br>Smartphone com o aplicativo Detran-DF instalado e conta ativa                                                                                   |
| **Episódios** | 1. O usuário acessa o aplicativo <br>2. Utiliza o aplicativo normalmente                                                                                                   |
| **Restrição** | As configurações de acessibilidade são limitadas a algumas necessidades especiais                                                                                          |
| **Exceção**   | Necessidade não atendida (fonte de tamanho fixo, cores do tema fixas, ...) <br>Falta de conexão com a internet <br>Aplicativo indisponível por manutenção                  |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu) , 2025.</p></font>

## Chat com IA para tirar dúvidas

A tabela 9 descreve o cenário do requisito funcional Chat com IA para tirar dúvidas, que foi rastreada pela técnica de elicitção BS10.

<font size="3"><p style="text-align: center">**Tabela 9 -** Chat com IA para tirar dúvidas.</p></font>

| **Item**      | **Cenário**                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Chat de atendimento com Inteligência Artificial para dúvidas gerais                                                                                                                                                                                                                                                                                                                                  |
| **Objetivo**  | Permitir que usuários tirem dúvidas comuns sobre serviços do Detran DF de forma prática, rápida e automatizada pelo aplicativo, sem a necessidade de atendimento humano.                                                                                                                                                                                                                             |
| **Contexto**  | **Local:** Aplicativo do Detran DF, acessado via smartphone. <br>**Tempo:** Qualquer dia da semana, 24h por dia. <br>**Pré-condição:** O usuário deve estar logado no aplicativo e possuir conexão com a internet. A IA e a base de conhecimento devem estar operacionais.                                                                                                                           |
| **Atores**    | Usuário do aplicativo; Assistente virtual (IA de atendimento).                                                                                                                                                                                                                                                                                                                                       |
| **Recursos**  | Aplicativo do Detran DF; Base de conhecimento com perguntas frequentes; Sistema de IA; Sistema de registro de interações.                                                                                                                                                                                                                                                                            |
| **Episódios** | 1. O usuário acessa o aplicativo do Detran DF. <br>2. Ele clica na opção “Chat de dúvidas”. <br>3. A IA cumprimenta o usuário e oferece ajuda com uma lista de categorias (documentação, agendamento, CNH, IPVA, etc). <br>4. O usuário pergunta: “Como agendar vistoria?” <br>5. A IA consulta a base de dados e responde com o passo a passo atualizado. <br>6. O usuário agradece e fecha o chat. |
| **Restrição** | O usuário pode realizar no máximo 10 interações por dia com a IA. Perguntas fora do escopo pré-definido não serão respondidas, e o usuário será auxiliado pela IA a procurar uma ajuda humana, ou seja oferecendo o número do Detran-DF por exemplo.                                                                                                                                                 |
| **Exceção**   | Se a IA não entender a pergunta ou detectar uma solicitação fora do escopo (ex: “Como recorrer a uma multa judicialmente?”), ela informará que não pode ajudar e sugerirá contato com um atendente humano. Se o limite de perguntas for excedido, a IA avisará o usuário e sugerirá tentar novamente no dia seguinte.                                                                                |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

## Atendimento ao vivo com servidor do DETRAN via chat/vídeo

A tabela 10 descreve o cenário do requisito funcional Atendimento ao vivo com servidor do DETRAN via chat/vídeos, que foi rastreada pela técnica de elicitção BS12.

<font size="3"><p style="text-align: center">**Tabela 10 -** Atendimento ao vivo com servidor do DETRAN via chat/vídeo.</p></font>

| **Item**      | **Cenário**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Título**    | Atendimento remoto ao vivo com servidor do Detran DF                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Objetivo**  | Permitir que o cidadão seja atendido por um servidor do Detran DF de forma remota, por chat ou chamada de voz, sem precisar se deslocar fisicamente até um posto de atendimento.                                                                                                                                                                                                                                                                                                                                  |
| **Contexto**  | **Local:** Aplicativo do Detran DF, acessado via smartphone. <br>**Tempo:** Em data e horário previamente agendado pelo usuário, dentro do horário de funcionamento do atendimento. <br>**Pré-condição:** O usuário deve estar logado no aplicativo, ter acesso à internet, e já ter realizado o agendamento no app.                                                                                                                                                                                              |
| **Atores**    | Usuário do aplicativo; Servidor do Detran DF responsável pelo atendimento remoto.                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Recursos**  | Aplicativo do Detran DF; Sistema de agendamento; Módulo de atendimento por chat/voz/vídeo; Sistema de autenticação de usuários; Base de dados dos serviços prestados.                                                                                                                                                                                                                                                                                                                                             |
| **Episódios** | 1. O usuário acessa o aplicativo do Detran DF. <br>2. Navega até a área de “Atendimento ao vivo”. <br>3. Escolhe o serviço desejado e agenda uma data e horário disponíveis. <br>4. No dia e hora marcados, o usuário entra novamente no aplicativo e inicia o atendimento. <br>5. O servidor aparece em vídeo e se comunica com o usuário, que pode optar por usar apenas voz ou chat. <br>6. O servidor realiza o atendimento e esclarece as dúvidas. <br>7. O atendimento é encerrado e registrado no sistema. |
| **Restrição** | O atendimento só é possível mediante agendamento prévio. O usuário pode optar por não ativar sua câmera, sendo atendido por voz ou chat. O servidor deve estar com a câmera ativada. O usuário deve respeitar o horário marcado, com tolerância de atraso de até 5 minutos.                                                                                                                                                                                                                                       |
| **Exceção**   | Se o usuário não comparecer no horário agendado, o atendimento é cancelado automaticamente. Caso haja instabilidade de conexão, o servidor poderá reagendar uma nova sessão. Se o usuário tentar acessar o atendimento fora do horário agendado, o sistema não permitirá a conexão.                                                                                                                                                                                                                               |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

## Histórico de versão

| Versão |    Data    |                                               Descrição                                                |                    Autor                     |                  Revisor                   |
| :----: | :--------: | :----------------------------------------------------------------------------------------------------: | :------------------------------------------: | :----------------------------------------: |
|  1.0   | 14/05/2025 |                        criação do documento, introdução, metodologia e objetivo                        | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.1   | 15/05/2025 |                     cenário Realizar agendamentos presencias (vistoria, CNH, etc.)                     | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.2   | 15/05/2025 |                            cenário Sistema de pagamento de taxas e débitos                             | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.3   | 15/05/2025 |                               Ajuste de metodologia e ajuste de tabelas                                |  [João Lobo](https://github.com/joaolobo10)  | [Gabriel Mendes](https://github.com/gbevi) |
|  1.4   | 16/05/2025 |                                    cenário Integração CNH e gov.br                                     |  [Gabriel Mendes](https://github.com/gbevi)  | [Eric Akio](https://github.com/eric-kingu) |
|  1.5   | 16/05/2025 |                                     cenário área para auto-escolas                                     |  [Gabriel Mendes](https://github.com/gbevi)  | [Eric Akio](https://github.com/eric-kingu) |
|  1.6   | 16/05/2025 | Cenários: agendamento de provas teóricas e práticas, e acessibilidade para diferentes tipos de usuário |  [Eric Akio](https://github.com/eric-kingu)  |                                            |
|  1.7   | 16/05/2025 | Cénarios de Chat com IA para tirar dúvidas e Atendimento ao vivo com servidor do DETRAN via chat/vídeo |  [João Lobo](https://github.com/joaolobo10)  |                                            |
