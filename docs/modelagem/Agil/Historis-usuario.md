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
|US20 a US26| [João Lobo](https://github.com/joaolobo10) |    |

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

<font size="3"><p style="text-align: center">**Tabela 3 -** US20</p></font>

|            Item            |                                                                                       Descrição                                                                                       |
| :------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          **US20**          |                                                                                          US20                                                                                         |
|          **Tema**          |                                                                        Solicitação de segunda via de CNH e CRLV                                                                       |
|        **Descrição**       |                                     Eu, como usuário, desejo solicitar a segunda via da CNH e do CRLV de forma digital para facilitar a reposição.                                    |
| **Critérios de Aceitação** | - O usuário deve conseguir solicitar a segunda via da CNH.<br>- O usuário deve conseguir solicitar a segunda via do CRLV.<br>- O sistema deve confirmar o recebimento da solicitação. |
|   **Prioridade Usuário**   |                                                                                          Alta                                                                                         |
|         **Status**         |                                                                                           x                                                                                           |
|     **Rastreabilidade**    |                                                                                          RF18                                                                                         |
|        **Validação**       |                                                                                           x                                                                                           |


<font size="3"><p style="text-align: center">**Tabela 4 -** US21</p></font>

|            Item            |                                                                                             Descrição                                                                                            |
| :------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          **US21**          |                                                                                               US21                                                                                               |
|          **Tema**          |                                                                               Acompanhamento de processos no DETRAN                                                                              |
|        **Descrição**       |                                       Eu, como usuário, desejo acompanhar o andamento dos meus processos no DETRAN para saber o status de cada solicitação.                                      |
| **Critérios de Aceitação** | - O usuário deve visualizar todos os processos em andamento.<br>- O sistema deve exibir o status atualizado de cada processo.<br>- O usuário deve receber notificações sobre mudanças no status. |
|   **Prioridade Usuário**   |                                                                                               Alta                                                                                               |
|         **Status**         |                                                                                                 x                                                                                                |
|     **Rastreabilidade**    |                                                                                               RF21                                                                                               |
|        **Validação**       |                                                                                                 x                                                                                                |


<font size="3"><p style="text-align: center">**Tabela 5 -** US22</p></font>

|            Item            |                                                                                         Descrição                                                                                         |
| :------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          **US22**          |                                                                                            US22                                                                                           |
|          **Tema**          |                                                                         Solicitação de reposição da placa Mercosul                                                                        |
|        **Descrição**       |                              Eu, como usuário, desejo solicitar a reposição da placa Mercosul pelo aplicativo para regularizar meu veículo de forma prática.                              |
| **Critérios de Aceitação** | - O usuário deve preencher os dados do veículo para solicitar a reposição.<br>- O sistema deve confirmar a solicitação.<br>- O usuário deve receber orientações para retirada ou entrega. |
|   **Prioridade Usuário**   |                                                                                           Média                                                                                           |
|         **Status**         |                                                                                             x                                                                                             |
|     **Rastreabilidade**    |                                                                                            RF31                                                                                           |
|        **Validação**       |                                                                                             x                                                                                             |


<font size="3"><p style="text-align: center">**Tabela 6 -** US23</p></font>

|            Item            |                                                                              Descrição                                                                             |
| :------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          **US23**          |                                                                                US23                                                                                |
|          **Tema**          |                                                                    Conversão para placa Mercosul                                                                   |
|        **Descrição**       |             Eu, como usuário, desejo solicitar a conversão da placa para o padrão Mercosul diretamente pelo app para facilitar o processo de adequação.            |
| **Critérios de Aceitação** | - O usuário deve informar os dados do veículo.<br>- O sistema deve gerar a solicitação de conversão.<br>- O usuário deve receber informações sobre taxas e prazos. |
|   **Prioridade Usuário**   |                                                                                Média                                                                               |
|         **Status**         |                                                                                  x                                                                                 |
|     **Rastreabilidade**    |                                                                                RF32                                                                                |
|        **Validação**       |                                                                                  x                                                                                 |


<font size="3"><p style="text-align: center">**Tabela 7 -** US24</p></font>

|            Item            |                                                                         Descrição                                                                        |
| :------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          **US24**          |                                                                           US24                                                                           |
|          **Tema**          |                                                            Conversão de autuação em penalidade                                                           |
|        **Descrição**       |                  Eu, como usuário, desejo converter uma autuação em penalidade pelo aplicativo para agilizar a resolução das infrações.                  |
| **Critérios de Aceitação** | - O usuário deve consultar autuações pendentes.<br>- O usuário deve poder converter a autuação em penalidade.<br>- O sistema deve confirmar a conversão. |
|   **Prioridade Usuário**   |                                                                           Média                                                                          |
|         **Status**         |                                                                             x                                                                            |
|     **Rastreabilidade**    |                                                                           RF35                                                                           |
|        **Validação**       |                                                                             x                                                                            |


<font size="3"><p style="text-align: center">**Tabela 8 -** US25</p></font>

|            Item            |                                                                                          Descrição                                                                                          |
| :------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          **US25**          |                                                                                             US25                                                                                            |
|          **Tema**          |                                                                              Nova solicitação pelo Protocolo-e                                                                              |
|        **Descrição**       |                                      Eu, como usuário, desejo iniciar uma nova solicitação pelo Protocolo-e para fazer requerimentos formais ao DETRAN.                                     |
| **Critérios de Aceitação** | - O usuário deve acessar o Protocolo-e pelo aplicativo.<br>- O sistema deve permitir o preenchimento dos dados para nova solicitação.<br>- O sistema deve confirmar o envio da solicitação. |
|   **Prioridade Usuário**   |                                                                                             Alta                                                                                            |
|         **Status**         |                                                                                              x                                                                                              |
|     **Rastreabilidade**    |                                                                                             RF36                                                                                            |
|        **Validação**       |                                                                                              x                                                                                              |


<font size="3"><p style="text-align: center">**Tabela 9 -** US26</p></font>

|            Item            |                                                                                          Descrição                                                                                          |
| :------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|          **US25**          |                                                                                             US25                                                                                            |
|          **Tema**          |                                                                              Nova solicitação pelo Protocolo-e                                                                              |
|        **Descrição**       |                                      Eu, como usuário, desejo iniciar uma nova solicitação pelo Protocolo-e para fazer requerimentos formais ao DETRAN.                                     |
| **Critérios de Aceitação** | - O usuário deve acessar o Protocolo-e pelo aplicativo.<br>- O sistema deve permitir o preenchimento dos dados para nova solicitação.<br>- O sistema deve confirmar o envio da solicitação. |
|   **Prioridade Usuário**   |                                                                                             Alta                                                                                            |
|         **Status**         |                                                                                              x                                                                                              |
|     **Rastreabilidade**    |                                                                                             RF36                                                                                            |
|        **Validação**       |                                                                                              x                                                                                              |


## Histórico de versão

| Versão |    Data    |              Descrição              |                     Autor                     | Revisor |
| :----: | :--------: | :---------------------------------: | :-------------------------------------------: | :-----: |
|  1.0   | 20/05/2025 |       Início da documentação        | [Giovana Barbosa ](https://github.com/gio221) |  |
|  1.1   | 20/05/2025 |      Introdução, objetivo, metodologia, e modelo     | [Giovana Barbosa ](https://github.com/gio221) |  |