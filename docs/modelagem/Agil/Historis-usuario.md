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
|US013 a US18| [Luiz Bessa](https://github.com/lfelipebessa) |[André Meyer](https://github.com/andremeyerr)    |
|US019 a US24| [João Lobo](https://github.com/joaolobo10) | Nicole Neves    |

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

# [US13] – Alertas de Vencimento da CNH, Multas e Licenciamento  

<font size="3"><b>Tabela 15: </b>História de Usuário – Alertas de Vencimento Gerais </font>

| Item                        | Descrição                                                                                                                                     |
|-----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| USx (número de identificação) | US13                                                                                                                                          |
| Tema                        | Alertas de Vencimento (CNH, Multas, Licenciamento)                                                                                             |
| Descrição                   | Eu, como usuário, desejo receber alertas de vencimento da CNH, multas e licenciamento para não perder prazos e evitar penalidades.            |
| Critérios de Aceitação      | - Enviar alertas automáticos antes do vencimento de CNH, multas e licenciamento.<br>- Permitir que o usuário escolha antecedência e canal dos alertas.<br>- Exibir painel com itens a vencer e respectivos prazos. |
| Prioridade Usuário          | Alta                                                                                                                                           |
| Status                      | Validada                                                                                                                                       |
| Rastreabilidade             | RF28                                                                                                                                           |
| Validação                   | [Link do vídeo](https://youtube.com/OPNeqpJgCC8)                                                                                                                                      |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

# [US14] – Agendar Serviços (Vistoria / Renovação da CNH)

<font size="3"><b>Tabela 16: </b>História de Usuário – Agendar Serviços Diversos </font>

| Item                        | Descrição                                                                                                                          |
|-----------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| USx (número de identificação)| US14                                                                                                                               |
| Tema                        | Agendamento de Serviços (Vistoria / Renovação)                                                                                     |
| Descrição                   | Eu, como usuário, desejo agendar serviços como vistoria ou renovação da CNH para evitar filas e otimizar meu tempo.                |
| Critérios de Aceitação      | - Permitir selecionar tipo de serviço, local e data disponível.<br>- Confirmar agendamento com protocolo digital.<br>- Enviar lembrete 24 h antes do horário marcado. |
| Prioridade Usuário          | Alta                                                                                                                                |
| Status                      | Validada                                                                                                                            |
| Rastreabilidade             | RF02                                                                                                                                |
| Validação                   | [Link do vídeo](https://youtube.com/OPNeqpJgCC8)                                                                                                                           |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

# [US15] – Agendar Provas Teóricas e Práticas

<font size="3"><b>Tabela 17: </b>História de Usuário – Agendar Provas</font>

| Item                        | Descrição                                                                                                                         |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| USx (número de identificação)| US15                                                                                                                              |
| Tema                        | Agendamento de Provas (Teórica e Prática)                                                                                         |
| Descrição                   | Eu, como usuário, desejo agendar online provas teóricas e práticas para obter ou renovar minha habilitação.                        |
| Critérios de Aceitação      | - Listar datas próximas para provas teóricas e práticas.<br>- Gerar comprovante com código QR.<br>- Permitir reagendamento uma vez sem custo adicional. |
| Prioridade Usuário          | Alta                                                                                                                               |
| Status                      | Validada                                                                                                                           |
| Rastreabilidade             | RF11                                                                                                                               |
| Validação                   | [Link do vídeo](https://youtube.com/OPNeqpJgCC8)                                                                                                                          |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

# [US16] – Agendar Exames Médicos para CNH

<font size="3"><b>Tabela 18: </b>História de Usuário – Agendar Exames Médicos</font>

| Item                        | Descrição                                                                                                                         |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| USx (número de identificação)| US16                                                                                                                              |
| Tema                        | Agendamento de Exames Médicos                                                                                                     |
| Descrição                   | Eu, como usuário, desejo agendar exames médicos para CNH diretamente no app para otimizar meu tempo.                              |
| Critérios de Aceitação      | - Exibir clínicas credenciadas com horários disponíveis.<br>- Permitir anexar documentos pré-consulta.<br>- Notificar resultado ou necessidade de retorno. |
| Prioridade Usuário          | Média                                                                                                                               |
| Status                      | Validada                                                                                                                           |
| Rastreabilidade             | RF27                                                                                                                               |
| Validação                   | [Link do vídeo](https://youtube.com/OPNeqpJgCC8)                                                                                                                          |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

# [US17] – Transferir Autuação de Infração para Outro Condutor

<font size="3"><b>Tabela 19: </b>História de Usuário – Transferir Autuação</font>

| Item                        | Descrição                                                                                                                         |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| USx (número de identificação)| US17                                                                                                                              |
| Tema                        | Transferência de Autuação                                                                                                          |
| Descrição                   | Eu, como usuário, desejo transferir a autuação de uma infração para outro condutor para corrigir a responsabilidade.               |
| Critérios de Aceitação      | - Permitir indicar dados do real infrator e anexar CNH.<br>- Gerar protocolo e prazo de análise.<br>- Notificar ambas as partes sobre a conclusão do processo. |
| Prioridade Usuário          | Média                                                                                                                               |
| Status                      | Validada                                                                                                                           |
| Rastreabilidade             | RF04                                                                                                                               |
| Validação                   | [Link do vídeo](https://youtube.com/OPNeqpJgCC8)                                                                                                                          |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

# [US18] – Transferir Documentação do Veículo

<font size="3"><b>Tabela 20: </b>História de Usuário – Transferir Documento do Veículo</font>

| Item                        | Descrição                                                                                                                         |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------|
| USx (número de identificação)| US18                                                                                                                              |
| Tema                        | Transferência de Documento do Veículo                                                                                             |
| Descrição                   | Eu, como usuário, desejo transferir a documentação do veículo para um novo proprietário de forma prática e digital.               |
| Critérios de Aceitação      | - Permitir preencher dados do comprador e do veículo.<br>- Gerar guia de pagamento e protocolo de transferência.<br>- Notificar quando o novo CRLV estiver disponível. |
| Prioridade Usuário          | Alta                                                                                                                               |
| Status                      | Validada                                                                                                                           |
| Rastreabilidade             | RF06                                                                                                                               |
| Validação                   | [Link do vídeo](https://youtube.com/OPNeqpJgCC8)                                                                                                                          |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

# [US19] - Solicitar troca de PPD para CNH definitiva

<p align="center"><strong>Tabela 15 -</strong> Solicitar troca de PPD para CNH definitiva.</p>

| Item                         | Descrição                                                                                                      |
| :--------------------------: | :-----------------------------------------------------------------------------------------------------------: |
| **US19**                     | US19                                                                                                          |
| **Tema**                     | Solicitar troca de PPD para CNH definitiva                                                                    |
| **Descrição**                 | Eu, como usuário, desejo solicitar a troca da minha PPD para a CNH definitiva diretamente no aplicativo para obter minha habilitação definitiva de forma prática. |
| **Critérios de Aceitação**    | - Permitir envio de solicitação via app <br> - Validar se o usuário cumpre os requisitos (tempo, infrações, etc.) <br> - Gerar protocolo de solicitação <br> - Permitir acompanhar o andamento |
| **Prioridade Usuário**        | Alta                                                                                                          |
| **Status**                    | Validada                                                                                                             |
| **Rastreabilidade**           | [RF07](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos)                   |
| **Validação**                 | [Link do vídeo](https://youtu.be/O_bsmIPCW6U?si=Lnsu8rd3vR0l5mxu)                                                                                                             |

<p align="center">Fonte: <a href="https://github.com/joaolobo10">João Lobo</a>, 2025.</p>

---

# [US20] - Solicitar segunda via da CNH e CRLV

<p align="center"><strong>Tabela 16 -</strong> Solicitar segunda via da CNH e CRLV.</p>

| Item                         | Descrição                                                                                                      |
| :--------------------------: | :-----------------------------------------------------------------------------------------------------------: |
| **US20**                     | US20                                                                                                          |
| **Tema**                     | Solicitar segunda via da CNH e CRLV                                                                           |
| **Descrição**                 | Eu, como usuário, desejo solicitar a segunda via da CNH e do CRLV de forma digital para facilitar a reposição desses documentos. |
| **Critérios de Aceitação**    | - Permitir solicitação da segunda via pelo app <br> - Gerar boleto ou guia de pagamento <br> - Disponibilizar versão digital dos documentos após compensação <br> - Emitir protocolo de solicitação |
| **Prioridade Usuário**        | Alta                                                                                                          |
| **Status**                    | Validada                                                                                                             |
| **Rastreabilidade**           | [RF18](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos)                   |
| **Validação**                 | [Link do vídeo](https://youtu.be/O_bsmIPCW6U?si=Lnsu8rd3vR0l5mxu)                                                                                                             |

<p align="center">Fonte: <a href="https://github.com/joaolobo10">João Lobo</a>, 2025.</p>

---

# [US21] - Acompanhar andamento dos processos

<p align="center"><strong>Tabela 17 -</strong> Acompanhar andamento dos processos.</p>

| Item                         | Descrição                                                                                                      |
| :--------------------------: | :-----------------------------------------------------------------------------------------------------------: |
| **US21**                     | US21                                                                                                          |
| **Tema**                     | Acompanhar andamento dos processos                                                                            |
| **Descrição**                 | Eu, como usuário, desejo acompanhar o andamento dos meus processos no DETRAN para saber o status de cada solicitação. |
| **Critérios de Aceitação**    | - Exibir lista de processos ativos e finalizados <br> - Mostrar status atualizado <br> - Exibir prazos e pendências <br> - Notificar atualizações importantes |
| **Prioridade Usuário**        | Alta                                                                                                          |
| **Status**                    | Validada                                                                                                             |
| **Rastreabilidade**           | [RF21](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos)                   |
| **Validação**                 | [Link do vídeo](https://youtu.be/O_bsmIPCW6U?si=Lnsu8rd3vR0l5mxu)                                                                                                             |

<p align="center">Fonte: <a href="https://github.com/joaolobo10">João Lobo</a>, 2025.</p>

---

# [US22] - Solicitar reposição da placa Mercosul

<p align="center"><strong>Tabela 18 -</strong> Solicitar reposição da placa Mercosul.</p>

| Item                         | Descrição                                                                                                      |
| :--------------------------: | :-----------------------------------------------------------------------------------------------------------: |
| **US22**                     | US22                                                                                                          |
| **Tema**                     | Solicitar reposição da placa Mercosul                                                                         |
| **Descrição**                 | Eu, como usuário, desejo solicitar a reposição da placa Mercosul pelo aplicativo para regularizar meu veículo de forma prática. |
| **Critérios de Aceitação**    | - Permitir envio de solicitação via app <br> - Permitir envio de documentos e fotos necessários <br> - Gerar guia de pagamento <br> - Emitir protocolo e informar prazo de entrega |
| **Prioridade Usuário**        | Média                                                                                                         |
| **Status**                    | Validada                                                                                                             |
| **Rastreabilidade**           | [RF31](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos)                   |
| **Validação**                 | [Link do vídeo](https://youtu.be/O_bsmIPCW6U?si=Lnsu8rd3vR0l5mxu)                                                                                                             |

<p align="center">Fonte: <a href="https://github.com/joaolobo10">João Lobo</a>, 2025.</p>

---

# [US23] - Solicitar conversão de placa para Mercosul

<p align="center"><strong>Tabela 19 -</strong> Solicitar conversão de placa para Mercosul.</p>

| Item                         | Descrição                                                                                                      |
| :--------------------------: | :-----------------------------------------------------------------------------------------------------------: |
| **US23**                     | US23                                                                                                          |
| **Tema**                     | Solicitar conversão de placa para Mercosul                                                                    |
| **Descrição**                 | Eu, como usuário, desejo solicitar a conversão da placa para o padrão Mercosul diretamente pelo app para facilitar o processo de adequação. |
| **Critérios de Aceitação**    | - Permitir solicitação via app <br> - Verificar se o veículo atende aos critérios legais <br> - Gerar guia de pagamento <br> - Emitir protocolo e prazo para troca |
| **Prioridade Usuário**        | Média                                                                                                         |
| **Status**                    | Validada                                                                                                             |
| **Rastreabilidade**           | [RF32](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos)                   |
| **Validação**                 | [Link do vídeo](https://youtu.be/O_bsmIPCW6U?si=Lnsu8rd3vR0l5mxu)                                                                                                             |

<p align="center">Fonte: <a href="https://github.com/joaolobo10">João Lobo</a>, 2025.</p>

---

# [US24] - Converter autuação em penalidade

<p align="center"><strong>Tabela 20 -</strong> Converter autuação em penalidade.</p>

| Item                         | Descrição                                                                                                      |
| :--------------------------: | :-----------------------------------------------------------------------------------------------------------: |
| **US24**                     | US24                                                                                                          |
| **Tema**                     | Converter autuação em penalidade                                                                              |
| **Descrição**                 | Eu, como usuário, desejo converter uma autuação em penalidade pelo aplicativo para agilizar a resolução das infrações. |
| **Critérios de Aceitação**    | - Permitir solicitação de conversão via app <br> - Exibir detalhes da autuação <br> - Validar elegibilidade da autuação <br> - Gerar protocolo e guia de pagamento (se aplicável) |
| **Prioridade Usuário**        | Alta                                                                                                          |
| **Status**                    | Validada                                                                                                             |
| **Rastreabilidade**           | [RF35](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos)                   |
| **Validação**                 | [Link do vídeo](https://youtu.be/O_bsmIPCW6U?si=Lnsu8rd3vR0l5mxu)                                                                                                             |

<p align="center">Fonte: <a href="https://github.com/joaolobo10">João Lobo</a>, 2025.</p>

---

## US25 - Iniciar nova solicitação pelo Protocolo-e

| Item                   | Descrição                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------|
| **US25**               | US25                                                                                                             |
| **Tema**               | Iniciar nova solicitação pelo Protocolo-e                                                                       |
| **Descrição**          | Eu, como usuário, desejo iniciar uma nova solicitação pelo Protocolo-e para fazer requerimentos formais ao DETRAN. |
| **Critérios de Aceitação** | - Permitir criação de nova solicitação via app  <br> - Exibir lista de tipos de requerimento disponíveis <br> - Gerar protocolo ao finalizar envio |
| **Prioridade Usuário** | Alta                                                                                                             |
| **Status**             | validada                                                                                                                 |
| **Rastreabilidade**    |                       |
| **Validação**          | x                                                                                                                |

<p align="center">Fonte: <a href="https://github.com/maaduh">Maria Eduarda</a>, 2025.</p>
---

## US26 - Acompanhar solicitação feita pelo Protocolo-e

| Item                   | Descrição                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------|
| **US26**               | US26                                                                                                             |
| **Tema**               | Acompanhar solicitação feita pelo Protocolo-e                                                                   |
| **Descrição**          | Eu, como usuário, desejo acompanhar a solicitação feita pelo Protocolo-e para saber o andamento do meu pedido. |
| **Critérios de Aceitação** | - Permitir consulta ao status da solicitação via app <br> - Mostrar histórico de movimentações <br> - Exibir prazos estimados de resposta |
| **Prioridade Usuário** | Alta                                                                                                             |
| **Status**             | validada                                                                                                                 |
| **Rastreabilidade**    |                      |
| **Validação**          | x                                                                                                                |

<p align="center">Fonte: <a href="https://github.com/maaduh">Maria Eduarda</a>, 2025.</p>

---

## US27 - Solicitar credencial de estacionamento para idoso

| Item                   | Descrição                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------|
| **US27**               | US27                                                                                                             |
| **Tema**               | Solicitar credencial de estacionamento para idoso                                                               |
| **Descrição**          | Eu, como usuário, desejo solicitar a credencial de estacionamento para idoso para ter acesso aos benefícios legais de mobilidade. |
| **Critérios de Aceitação** | - Permitir envio de solicitação via app <br> - Enviar documentos comprobatórios <br> - Gerar protocolo e prazo de entrega |
| **Prioridade Usuário** | Alta                                                                                                             |
| **Status**             | validada                                                                                                                 |
| **Rastreabilidade**    |                       |
| **Validação**          | x                                                                                                                |

<p align="center">Fonte: <a href="https://github.com/maaduh">Maria Eduarda</a>, 2025.</p>

---

## US28 - Solicitar credencial para pessoas com TEA

| Item                   | Descrição                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------|
| **US28**               | US28                                                                                                             |
| **Tema**               | Solicitar credencial de estacionamento para pessoas com Transtorno do Espectro Autista                          |
| **Descrição**          | Eu, como usuário, desejo solicitar a credencial de estacionamento para pessoas com Transtorno do Espectro Autista para garantir o direito de vaga especial. |
| **Critérios de Aceitação** | - Permitir solicitação via app <br> - Permitir envio de laudos médicos e documentos exigidos <br> - Gerar protocolo e informar prazos |
| **Prioridade Usuário** | Alta                                                                                                             |
| **Status**             | validada                                                                                                                 |
| **Rastreabilidade**    |                      |
| **Validação**          | x                                                                                                                |

<p align="center">Fonte: <a href="https://github.com/maaduh">Maria Eduarda</a>, 2025.</p>

---

## US29 - Pagamento de débitos para liberação de veículo

| Item                   | Descrição                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------|
| **US29**               | US29                                                                                                             |
| **Tema**               | Pagamento de débitos para liberação de veículo                                                                  |
| **Descrição**          | Eu, como usuário, desejo realizar o pagamento de débitos diretamente pelo app para liberar meu veículo do pátio de forma rápida. |
| **Critérios de Aceitação** | - Exibir lista de débitos vinculados ao veículo <br> - Permitir pagamento via app <br> - Atualizar status de liberação após pagamento |
| **Prioridade Usuário** | Alta                                                                                                             |
| **Status**             | validada                                                                                                                |
| **Rastreabilidade**    |                    |
| **Validação**          | x                                                                                                                |

<p align="center">Fonte: <a href="https://github.com/maaduh">Maria Eduarda</a>, 2025.</p>

---

## US30 - Verificar autorização para transporte escolar

| Item                   | Descrição                                                                                                        |
|------------------------|------------------------------------------------------------------------------------------------------------------|
| **US30**               | US30                                                                                                             |
| **Tema**               | Verificar autorização para transporte escolar                                                                   |
| **Descrição**          | Eu, como usuário, desejo verificar se um veículo possui autorização para transporte escolar para garantir a segurança dos estudantes. |
| **Critérios de Aceitação** | - Permitir consulta de placa <br> - Exibir status de autorização para transporte escolar <br> - Mostrar validade e dados do condutor (se permitido legalmente) |
| **Prioridade Usuário** | Média                                                                                                            |
| **Status**             | validada                                                                                                             |
| **Rastreabilidade**    |                       |
| **Validação**          | x                                                                                                                |

<p align="center">Fonte: <a href="https://github.com/maaduh">Maria Eduarda</a>, 2025.</p>

---

# [US39] - Integração com Sistemas Oficiais

<font size="3"><b>Tabela 41:</b> História do usuário de Integração com Sistemas Oficiais</font>

| Item | Descrição |
|------|-----------|
| **US39** | US39 |
| **Tema** | Integração com Sistemas Oficiais |
| **Descrição** | Eu, como usuário, desejo integrar minha conta com a CNH Digital e com o Gov.br para autenticação segura e acesso facilitado. |
| **Critérios de Aceitação** | - O usuário deve conseguir acessar o aplicativo pelo Gov.br.<br> - O sistema deve permitir a autenticação pelo Gov.br. |
| **Prioridade Usuário** | Alta |
| **Status** | Validada |
| **Rastreabilidade** | [RF15](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos) |
| **Validação** | [Link do vídeo](https://youtu.be/2gKGRSStj7s) |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

# [US40] - Área de auto-escolas

<font size="3"><b>Tabela 42:</b> História do usuário de Área de auto-escolas</font>

| Item | Descrição |
|------|-----------|
| **US40** | US40 |
| **Tema** | Área de auto-escolas |
| **Descrição** | Eu, como usuário, desejo acessar uma área de autoescolas com avaliações, comentários e localização para escolher a melhor opção. |
| **Critérios de Aceitação** | - O usuário deve conseguir acessar uma sessão chamada "auto-escolas".<br> - O sistema deve exibir avaliações de auto-escolas.<br> - O sistema deve exibir comentários sobre as auto-escolas.<br> - O sistema deve exibir a localização das auto-escolas.<br> - O usuário deve conseguir avaliar e comentar sobre a auto-escola. |
| **Prioridade Usuário** | Média |
| **Status** | Validada |
| **Rastreabilidade** | [RF12](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos) |
| **Validação** | [Link do vídeo](https://youtu.be/2gKGRSStj7s) |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

# [US41] - Guia com Documentos para Serviços

<font size="3"><b>Tabela 43:</b> História do usuário de Guia com Documentos para Serviços</font>

| Item | Descrição |
|------|-----------|
| **US41** | US41 |
| **Tema** | Guia de Documentos para Serviços |
| **Descrição** | Eu, como usuário, desejo acessar um guia com os documentos necessários para cada tipo de serviço, a fim de me preparar corretamente. |
| **Critérios de Aceitação** | - O usuário deve ter acesso a um guia de documentos para cada tipo de serviço.<br> - O sistema deve exibir os documentos necessários para cada tipo de serviço. |
| **Prioridade Usuário** | Média |
| **Status** | Validada |
| **Rastreabilidade** | [RF13](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos) |
| **Validação** | [Link do vídeo](https://youtu.be/2gKGRSStj7s) |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

# [US42] - Simulados de Prova Teórica

<font size="3"><b>Tabela 44:</b> História do usuário de Simulados de Prova Teórica</font>

| Item | Descrição |
|------|-----------|
| **US42** | US42 |
| **Tema** | Simulados de Prova Teórica |
| **Descrição** | Eu, como aluno de autoescola, desejo realizar simulados da prova teórica pelo app para me preparar melhor para o exame oficial. |
| **Critérios de Aceitação** | - O usuário deve ter acesso a simulados da prova teórica.<br> - O sistema deve permitir que o usuário realize simulados da prova teórica. |
| **Prioridade Usuário** | Média |
| **Status** | Validada |
| **Rastreabilidade** | [RF41](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos) |
| **Validação** | [Link do vídeo](https://youtu.be/2gKGRSStj7s) |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## Histórico de versão

| Versão |    Data    |              Descrição              |                     Autor                     | Revisor |
| :----: | :--------: | :---------------------------------: | :-------------------------------------------: | :-----: |
|  1.0   | 20/05/2025 |       Início da documentação        | [Giovana Barbosa ](https://github.com/gio221) | [Gabriel Mendes ](https://github.com/gbevi) |
|  1.1   | 20/05/2025 |      Introdução, objetivo, metodologia, e modelo     | [Giovana Barbosa ](https://github.com/gio221) | [Gabriel Mendes ](https://github.com/gbevi) |
|  1.2   | 29/05/2025 |      Histórias de usuário 7 a 12    | [Gabriel Mendes ](https://github.com/gbevi) | [Eric Akio](https://github.com/eric-kingu) |
|  1.3  | 30/05/2025 |      Documentação das histórias de usuário 19 a 24, faltando apenas a validação com o usuário    | [João Lobo](https://github.com/joaolobo10) | [Eric Akio](https://github.com/eric-kingu) |
| 1.4 | 30/05/2025 | Documentação das histórias de usuário 39 a 42, faltando apenas a validação com o usuário | [Eric Akio](https://github.com/eric-kingu) |  [Luiz Bessa](https://github.com/lfelipebessa)  |
| 1.5 | 30/05/2025 | Documentação das histórias de usuário 13 a 18 | [Luiz Bessa](https://github.com/lfelipebessa) | [Eric Akio](https://github.com/eric-kingu) |
| 1.6 | 30/05/2025 | Validação das histórias de usuário 39 a 42 | [Eric Akio](https://github.com/eric-kingu) | [Maria Eduarda](https://github.com/maaduh)  |
| 1.7 | 31/05/2025 | Documentação das histórias de usuário 25 a 30 | [Maria Eduarda](https://github.com/maaduh) |  |
| 1.8 | 31/05/2025 | Adição dos vídeos de validação das Histórias de usuário US19 até a US24 |  [João Lobo](https://github.com/joaolobo10) |  |