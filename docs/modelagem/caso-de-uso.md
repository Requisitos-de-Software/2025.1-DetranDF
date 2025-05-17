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

## Diagram de Caso de Uso do app Detran- DF

## Especifiação do Caso de Uso

A especificação dos casos de uso é uma técnica utilizada para descrever detalhadamente as interações entre os usuários e o sistema. Ela documenta os passos seguidos em cada caso de uso, incluindo os eventos que desencadeiam a interação, as ações realizadas e as respostas esperadas do sistema.

A tabela 2 descreve qual funcionalidade cada integrante fez um caso de uso.

<font size="3"><p style="text-align: center">**Tabela 2 -** Divisão de caso de uso por integrantes da equipe.</p></font>

|                  Integrante                  |                        Cenário                         |
| :------------------------------------------: | :----------------------------------------------------: |
| [Giovana Barbosa](https://github.com/gio221) | Realizar agendamentos presencias (vistoria, CNH, etc.) |
| [Giovana Barbosa](https://github.com/gio221) |       Autorização de estacionamento para idosos        |

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

| UC01                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

### Sistema de pagamento de taxas e débitos

Abaixo, na tabela 5, está especificado o caso de uso para a funcionalidade de "Sistema de pagamento de taxas e débitos".

<font size="3"><p style="text-align: center">**Tabela 5 -** Sistema de pagamento de taxas e débitos.</p></font>

| UC02                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

### Chat com IA para tirar dúvidas

Abaixo, na tabela 6, está especificado o caso de uso para a funcionalidade de "Chat com IA para tirar dúvidas".

<font size="3"><p style="text-align: center">**Tabela 6 -** Chat com IA para tirar dúvidas.</p></font>

| UC03                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

### Atendimento ao vivo com servidor do DETRAN via chat/vídeo

Abaixo, na tabela 7, está especificado o caso de uso para a funcionalidade de "Atendimento ao vivo com servidor do DETRAN via chat/vídeo".

<font size="3"><p style="text-align: center">**Tabela 7 -** Atendimento ao vivo com servidor do DETRAN via chat/vídeo.</p></font>

| UC04                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

### Integração com CNH digital e gov br

Abaixo, na tabela 8, está especificado o caso de uso para a funcionalidade de "Integração com CNH digital e gov br".

<font size="3"><p style="text-align: center">**Tabela 8 -** Integração com CNH digital e gov br.</p></font>

| UC05                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Dantas](https://github.com/gbevi) , 2025.</p></font>

### Área para autoescolas com avaliações, comentários e localizações

Abaixo, na tabela 9, está especificado o caso de uso para a funcionalidade de "Área para autoescolas com avaliações, comentários e localizações".

<font size="3"><p style="text-align: center">**Tabela 9 -** Área para autoescolas com avaliações, comentários e localizações.</p></font>

| UC06                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Dantas](https://github.com/gbevi) , 2025.</p></font>

### Histórico de Pesquisas e Serviços Recentes

Abaixo, na tabela 10, está especificado o caso de uso para a funcionalidade de "Histórico de Pesquisas e Serviços Recentes".

<font size="3"><p style="text-align: center">**Tabela 10 -** Histórico de Pesquisas e Serviços Recentes.</p></font>

| UC07                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa ](https://github.com/lfelipebessa) , 2025.</p></font>

### Notificação antecipada da data de vencimento da CNH

Abaixo, na tabela 11, está especificado o caso de uso para a funcionalidade de "Notificação antecipada da data de vencimento da CNH".

<font size="3"><p style="text-align: center">**Tabela 11 -** Notificação antecipada da data de vencimento da CNH.</p></font>

| UC08                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa ](https://github.com/lfelipebessa) , 2025.</p></font>

### Área educacional com explicações e vídeos

Abaixo, na tabela 12, está especificado o caso de uso para a funcionalidade de "Área educacional com explicações e vídeos".

<font size="3"><p style="text-align: center">**Tabela 12 -** Área educacional com explicações e vídeos.</p></font>

| UC09                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Pedro Camilo](https://github.com/PedrooCamilo) , 2025.</p></font>

### Explicacoes acessíveis sobre siglas

Abaixo, na tabela 13, está especificado o caso de uso para a funcionalidade de "Explicacoes acessíveis sobre siglas".

<font size="3"><p style="text-align: center">**Tabela 13 -** Explicacoes acessíveis sobre siglas.</p></font>

| UC10                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Pedro Camilo](https://github.com/PedrooCamilo) , 2025.</p></font>

### Notificação de multas e prazos com desconto

Abaixo, na tabela 14, está especificado o caso de uso para a funcionalidade de "Notificação de multas e prazos com desconto".

<font size="3"><p style="text-align: center">**Tabela 14 -** Notificação de multas e prazos com desconto.</p></font>

| UC11                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/maaduh) , 2025.</p></font>

### Aviso automático em caso de roubo/recuperação do carro

Abaixo, na tabela 15, está especificado o caso de uso para a funcionalidade de "Aviso automático em caso de roubo/recuperação do carro".

<font size="3"><p style="text-align: center">**Tabela 15 -** Aviso automático em caso de roubo/recuperação do carro.</p></font>

| UC12                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/maaduh) , 2025.</p></font>

### Agendamento online para provas teóricas e práticas

Abaixo, na tabela 16, está especificado o caso de uso para a funcionalidade de "Agendamento online para provas teóricas e práticas".

<font size="3"><p style="text-align: center">**Tabela 16 -** Agendamento online para provas teóricas e práticas.</p></font>

| UC13                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu) , 2025.</p></font>

### Acessibilidade para diferentes perfis de usuários

Abaixo, na tabela 17, está especificado o caso de uso para a funcionalidade de "Acessibilidade para diferentes perfis de usuários".

<font size="3"><p style="text-align: center">**Tabela 17 -** Acessibilidade para diferentes perfis de usuários.</p></font>

| UC14                  | Nome do caso de uso                                                                                                                                           |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Descrição**         | Uma breve explicação do que o caso de uso faz ou descreve.                                                                                                    |
| **Atores**            | Os papéis ou entidades que interagem com o sistema.                                                                                                           |
| **Pré-condição**      | As condições que devem ser verdadeiras antes que o caso de uso possa ser iniciado.                                                                            |
| **Pós-condição**      | As condições que devem ser verdadeiras após a conclusão bem-sucedida do caso de uso.                                                                          |
| **Fluxo principal**   | A sequência de passos que descreve a interação típica entre o ator e o sistema para atingir o objetivo do caso de uso.                                        |
| **Fluxo alternativo** | Sequências de passos que ocorrem se condições específicas forem atendidas durante a execução do caso de uso, mas não são necessariamente o caminho principal. |
| **Fluxo de exceções** | Sequências de passos que descrevem como lidar com erros ou situações inesperadas durante a execução do caso de uso.                                           |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu) , 2025.</p></font>

### Histórico de versão

| Versão |    Data    |                                                                              Descrição                                                                               |                    Autor                     |                  Revisor                   |
| :----: | :--------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------: | :----------------------------------------: |
|  1.0   | 14/05/2025 |                                                                         criação do documento                                                                         | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|        |
|  1.1   | 15/05/2025 |                                                                  introdução, objetivo e metodologia                                                                  | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|        |
|  1.2   | 16/05/2025 | Criação de todas tabelas de especificação de cenários assim como a tabela modelo, e a tabela adição de símbolos da tabela dos componentes do diagrama de caso de uso |  [João Lobo](https://github.com/joaolobo10)  |
|        |
