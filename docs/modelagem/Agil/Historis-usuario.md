# Introdução
Este documento tem como foco a documentação das histórias de usuário do aplicativo Detran-DF, um elemento essencial em métodos ágeis como o Scrum. As histórias de usuário foram desenvolvidas para refletir, de forma clara e simples, as necessidades do usuário final, facilitando o entendimento comum entre a equipe de desenvolvimento e os stakeholders. Além disso, elas ajudam a alinhar os objetivos do projeto e a priorizar funcionalidades que entreguem maior valor ao usuário.

# Objetivo 
O propósito principal é garantir que as funcionalidades do sistema estejam alinhadas às expectativas dos usuários, promovendo uma comunicação eficaz entre as partes envolvidas e orientando o desenvolvimento com base na entrega de valor real.

# Metodologia
A metodologia adotada para criar essas histórias foi dividida em três etapas:

Elicitação de Requisitos – Foram aplicadas técnicas como brainstorming, observação, glossário e instronspecção para identificar o que os usuários realmente precisam, considerando tanto os requisitos funcionais quanto os não funcionais.

Rastreabilidade e Priorização – Os requisitos foram organizados e relacionados com funcionalidades específicas, e a priorização foi feita utilizando métodos como In or out, moscow, First Things First e o método dos $100.

Criação das Histórias de Usuário – As histórias foram escritas em um formato padronizado (“como usuário, eu quero... para que...”), acompanhadas de critérios de aceitação. Elas passaram por validações com stakeholders para garantir aderência às expectativas.

# Quem fez cada História de Usuário

Cada história de usuário foi validada com o PO. Com o objetivo de organização, a tabela 1 mostra a história de usuário, o integrante responsável por tal e usuário participante. Todos os requisitos elicitados estão presentes no artefato [Requisitos Elicitados](http://127.0.0.1:8000/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/)

<font size="3"><p style="text-align: center">**Tabela 1 -**Distribuição de requisitos entre os integrantes para elaboração das historias de usuário .</p></font>

| História de Usuario |              Desenvolvedor               | Usuário | 
| :-----------------: | :--------------------------------------: | :-----: | 
|US01 a US06| [Giovana Barbosa](https://github.com/gio221) |    |
|US07 a US12| [Gabriel Mendes](https://github.com/gbevi) |[Mayara Marques](https://github.com/maymarquee)    |

<a id="tabela-us"></a>

# Modelo de História de Usuário

<font size="3"><b>Tabela 2:</b>Modelo para História de Usuário</font>

|             Item             |                             Descrição                              |
| :--------------------------: | :----------------------------------------------------------------: |
| **USx(número de identificação)** |                                USx                                 |
|             **Tema**             |                               Título                               |
|          **Descrição**           | Eu, como [tipo de usuário], desejo [ação desejada] para [objetivo] |
|    **Critérios de Aceitação**    |            - [Critério 1] <br> - [Critério 2] <br> ...             |
|      **Prioridade Usuário**      |                         Alta, Média, Baixa                         |
|            **Status**            |           Se a história foi Validada ou não pelo usuário           |
|       **Rastreabilidade**        |                        Código do requisito                         |
|          **Validação**           |            link levando ao vídeo no minuto da validação            |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

# Histórias de Usuário

As tabelas abaixo apresentam as histórias de usuário organizadas de maneira ordenada, seguindo a [tabela modelo de história de usuários](./Historis-usuario.md#tabela-us). Todas as tabelas utilizam esse formato para garantir uniformidade e facilitar a rastreabilidade com os requisitos funcionais.

# [US01] - Consultar multas e débitos do veículo

### Tabela 3: História de Usuário – Consultar multas e débitos

| Item                        | Descrição                                                                 |
|-----------------------------|---------------------------------------------------------------------------|
| USx(número de identificação)| US01                                                                      |
| Tema                        | Consultar multas e débitos do veículo                                     |
| Descrição                   | Eu, como usuário, desejo consultar multas e débitos do meu veículo para saber se há pendências financeiras. |
| Critérios de Aceitação      | - O sistema deve exibir as multas ativas associadas ao veículo.<br>- O sistema deve listar os débitos pendentes como IPVA, DPVAT ou licenciamento.<br>- O usuário deve ser informado se não houver nenhuma pendência. |
| Prioridade Usuário          | Alta                                                                      |
| Status                      | Validada                                                                  |
| Rastreabilidade             | RF01                                                                      |
| Validação                   |                                                              |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

# [US02] - Visualizar CNH e pontuação

### Tabela 4: História de Usuário – Visualizar informações da CNH

| Item                        | Descrição                                                                 |
|-----------------------------|---------------------------------------------------------------------------|
| USx(número de identificação)| US02                                                                      |
| Tema                        | Acompanhar status da CNH                                                  |
| Descrição                   | Eu, como usuário, desejo visualizar minhas informações da CNH e minha pontuação para acompanhar meu status como condutor. |
| Critérios de Aceitação      | - O sistema deve exibir os dados principais da CNH (número, validade, categoria).<br>- O sistema deve exibir a pontuação atual do usuário.<br>- O sistema deve alertar o usuário se a pontuação estiver próxima do limite. |
| Prioridade Usuário          | Alta                                                                      |
| Status                      | Validada                                                                  |
| Rastreabilidade             | RF03, RF19, RF20                                                          |
| Validação                   | a definir                                                                 |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

# [US03] -  Consultar CNH, documentos e multas em um só lugar

### Tabela 5: História de Usuário – Consultar CNH, documentos e multas

| Item                        | Descrição                                                                 |
|-----------------------------|---------------------------------------------------------------------------|
| USx(número de identificação)| US03                                                                      |
| Tema                        | Consulta unificada de informações                                         |
| Descrição                   | Eu, como usuário, desejo consultar a CNH, documentos e multas em um só lugar para facilitar meu acesso às informações. |
| Critérios de Aceitação      | - O sistema deve exibir uma tela com as seções CNH, documentos e multas integradas.<br>- O usuário deve conseguir navegar entre as seções de forma intuitiva.<br>- As informações devem ser atualizadas em tempo real. |
| Prioridade Usuário          | Alta                                                                      |
| Status                      | Validada                                                                  |
| Rastreabilidade             | RF10                                                                      |
| Validação                   | a definir                                                                 |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

# [US04] - Visualizar status do licenciamento e do IPVA

### Tabela 6: História de Usuário – Visualizar status do licenciamento e IPVA

| Item                        | Descrição                                                                 |
|-----------------------------|---------------------------------------------------------------------------|
| USx(número de identificação)| US04                                                                      |
| Tema                        | Acompanhar regularização do veículo                                       |
| Descrição                   | Eu, como usuário, desejo visualizar o status do licenciamento e do IPVA do veículo para manter a documentação regularizada. |
| Critérios de Aceitação      | - O sistema deve exibir o status atual do licenciamento.<br>- O sistema deve exibir o status do pagamento do IPVA.<br>- O sistema deve emitir alertas em caso de pendências. |
| Prioridade Usuário          | Alta                                                                      |
| Status                      | Validada                                                                  |
| Rastreabilidade             | RF17                                                                      |
| Validação                   | a definir                                                    |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

# [US05] -  Consultar status do licenciamento em tempo real

### Tabela 7: História de Usuário – Consultar licenciamento em tempo real

| Item                        | Descrição                                                                 |
|-----------------------------|---------------------------------------------------------------------------|
| USx(número de identificação)| US05                                                                      |
| Tema                        | Consulta em tempo real do licenciamento                                   |
| Descrição                   | Eu, como usuário, desejo consultar o status do licenciamento do veículo em tempo real para garantir que estou em dia. |
| Critérios de Aceitação      | - O sistema deve exibir o status atualizado do licenciamento com data e hora da última verificação.<br>- O sistema deve emitir alertas se houver irregularidades. |
| Prioridade Usuário          | Alta                                                                      |
| Status                      | Validada                                                                  |
| Rastreabilidade             | RF23                                                                      |
| Validação                   | a definir                                                                 |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

# [US06] - Ver detalhes das infrações com imagens

### Tabela 8: História de Usuário – Ver detalhes de infrações com imagens

| Item                        | Descrição                                                                 |
|-----------------------------|---------------------------------------------------------------------------|
| USx(número de identificação)| US06                                                                      |
| Tema                        | Detalhamento de infrações com evidências                                  |
| Descrição                   | Eu, como usuário, desejo ver detalhes das infrações com imagens para entender melhor a penalidade. |
| Critérios de Aceitação      | - O sistema deve exibir a imagem vinculada à infração (se disponível).<br>- O sistema deve apresentar detalhes como local, data e hora da infração.<br>- As imagens devem ser exibidas com boa resolução e sem distorções. |
| Prioridade Usuário          | Alta                                                                      |
| Status                      | Validada                                                                  |
| Rastreabilidade             | RF25                                                                      |
| Validação                   | a definir                                                                 |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

# [US07] - Recurso de multa

<font size="3"><b>Tabela 9:</b>História do usuário de recurso de multa</font>

|             Item             |                             Descrição                              |
|:---------------------------:|:--------------------------------------------------------------------:|
| US07                        | US07                                                                 |
| Tema                        | Recurso de Multa                                                    |
| Descrição                   | Eu, como usuário, desejo iniciar e acompanhar recursos de multa pelo app para facilitar a contestação. |
| Critérios de Aceitação      | - Permitir envio de recurso com documentos anexos <br> - Permitir visualizar status do recurso em tempo real <br> - Notificar o usuário sobre mudanças no andamento do recurso |
| Prioridade Usuário          | Alta                                                                 |
| Status                      | Validada                                                         |
| Rastreabilidade             | RF26                                                                 |
| Validação                   | [vídeo de validação](https://youtu.be/B7w5KqO4HYU)                             |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Mendes](https://github.com/gbevi) , 2025.</p></font>

# [US08] - Histórico de Infrações (Condutor)   

<font size="3"><b>Tabela 10:</b>História do usuário de histórico de Infrações (Condutor)</font>

|             Item             |                             Descrição                              |
|:---------------------------:|:--------------------------------------------------------------------:|
| US08                        | US08                                                                 |
| Tema                        | Histórico de Infrações (Condutor)                                   |
| Descrição                   | Eu, como usuário, desejo visualizar o histórico de infrações como condutor para acompanhar meu comportamento no trânsito. |
| Critérios de Aceitação      | - Listar infrações por data e pontuação <br> - Exibir detalhes como local, data e tipo da infração <br> - Informar status de pagamento e recurso, se houver |
| Prioridade Usuário          | Alta                                                                 |
| Status                      | Validada                                                         |
| Rastreabilidade             | RF33                                                                 |
| Validação                   | [vídeo de validação](https://youtu.be/B7w5KqO4HYU)                              |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Mendes](https://github.com/gbevi) , 2025.</p></font>

# [US09] - Histórico de Infrações (Veículo) 

<font size="3"><b>Tabela 11:</b>História do usuário de histórico de Infrações (Veículo)</font>

|             Item             |                             Descrição                              |
|:---------------------------:|:--------------------------------------------------------------------:|
| US09                        | US09                                                                 |
| Tema                        | Histórico de Infrações (Veículo)                                    |
| Descrição                   | Eu, como usuário, desejo consultar o histórico de infrações do meu veículo para saber o que já ocorreu com ele. |
| Critérios de Aceitação      | - Listar infrações associadas ao veículo <br> - Exibir data, tipo e status de cada infração <br> - Possibilitar filtro por período ou status |
| Prioridade Usuário          | Média                                                                |
| Status                      | Validada                                                         |
| Rastreabilidade             | RF34                                                                 |
| Validação                   | [vídeo de validação](https://youtu.be/B7w5KqO4HYU)                                |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Mendes](https://github.com/gbevi) , 2025.</p></font>

# [US10] - Leilão de Veículos   

<font size="3"><b>Tabela 12:</b>História do usuário de leilão de Veículos </font>

|             Item             |                             Descrição                              |
|:---------------------------:|:--------------------------------------------------------------------:|
| US10                        | US10                                                                 |
| Tema                        | Leilão de Veículos                                                  |
| Descrição                   | Eu, como cidadão, desejo acessar informações sobre leilões de veículos para participar ou acompanhar os processos. |
| Critérios de Aceitação      | - Listar leilões com data, local e lote <br> - Permitir visualização dos veículos disponíveis <br> - Informar regras e etapas para participação |
| Prioridade Usuário          | Média                                                                |
| Status                      | Validada                                                         |
| Rastreabilidade             | RF42                                                                 |
| Validação                   | [vídeo de validação](https://youtu.be/B7w5KqO4HYU)                                |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Mendes](https://github.com/gbevi) , 2025.</p></font>

# [US11] - Notificações de Prazos e Documentos   

<font size="3"><b>Tabela 13:</b>História do usuário de notificações de Prazos e Documentos  </font>

|             Item             |                             Descrição                              |
|:---------------------------:|:--------------------------------------------------------------------:|
| US11                        | US11                                                                 |
| Tema                        | Notificações de Prazos e Documentos                                 |
| Descrição                   | Eu, como usuário, desejo receber notificações de prazos e documentos vencidos para não perder prazos importantes. |
| Critérios de Aceitação      | - Enviar notificações automáticas sobre vencimentos <br> - Permitir configuração da frequência e canal das notificações <br> - Mostrar painel com alertas pendentes |
| Prioridade Usuário          | Alta                                                                 |
| Status                      | Validada                                                         |
| Rastreabilidade             | RF05, RF22                                                           |
| Validação                   | [vídeo de validação](https://youtu.be/B7w5KqO4HYU)                                |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Mendes](https://github.com/gbevi) , 2025.</p></font>

# [US12] - Alerta de Roubo/Recuperação

<font size="3"><b>Tabela 14:</b>História do usuário de alerta de Roubo/Recuperação </font>

|             Item             |                             Descrição                              |
|:---------------------------:|:--------------------------------------------------------------------:|
| US12                        | US12                                                                 |
| Tema                        | Alerta de Roubo/Recuperação                                         |
| Descrição                   | Eu, como usuário, desejo receber alertas automáticos em caso de roubo ou recuperação do meu veículo para agir rapidamente. |
| Critérios de Aceitação      | - Enviar alerta em tempo real ao registrar roubo ou recuperação <br> - Exibir alerta com detalhes relevantes (local, data, status) <br> - Permitir ativar ou desativar notificações desse tipo |
| Prioridade Usuário          | Alta                                                                 |
| Status                      | Validada                                                         |
| Rastreabilidade             | RF09                                                                 |
| Validação                   | [vídeo de validação](https://youtu.be/B7w5KqO4HYU)                                |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## Histórico de versão

| Versão |    Data    |              Descrição              |                     Autor                     | Revisor |
| :----: | :--------: | :---------------------------------: | :-------------------------------------------: | :-----: |
|  1.0   | 20/05/2025 |       Início da documentação        | [Giovana Barbosa ](https://github.com/gio221) | [Gabriel Mendes ](https://github.com/gbevi) |
|  1.1   | 20/05/2025 |      Introdução, objetivo, metodologia, e modelo     | [Giovana Barbosa ](https://github.com/gio221) | [Gabriel Mendes ](https://github.com/gbevi) |
|  1.2   | 29/05/2025 |      Histórias de usuário 7 a 12    | [Gabriel Mendes ](https://github.com/gbevi) |  |