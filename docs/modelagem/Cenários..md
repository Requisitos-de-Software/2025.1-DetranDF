## Introdução
Este documento faz parte do projeto da disciplina de Requisitos de Software e tem como objetivo principal a definição detalhada dos cenários do sistema Detran-DF. Os cenários auxiliam na análise e modelagem de requisitos ao descrever situações específicas que o sistema deve suportar.

## Objetivo
Apresentar de forma clara e estruturada os cenários de uso do sistema Detran-DF

## Metodologia
A elaboração dos cenários foi colaborativa, com cada integrante do grupo responsável por um cenário específico. Todos seguiram um formato padrão para garantir uniformidade

A tabela 1 descreve qual funcionalidade cada integrante vai fazer o cenário

| Integrante |   Cenário    |     
| :----: | :--------: | 
| [Giovana Barbosa](https://github.com/gio221) |Realizar agendamentos presencias (vistoria, CNH, etc.)|
| [Giovana Barbosa](https://github.com/gio221) |Autorização de estacionamento para idosos|

## Realizar agendamentos presencias (vistoria, CNH, etc.)

A tabela 1 descreve o cenário do requisito funcional Realizar agendamentos presencias (vistoria, CNH, etc.), que foi rastreada  pelas técnicas de elecitação IS01 e OBS001

#### Tabela 1: Cenário - Realizar agendamentos presenciais (vistoria, CNH, etc.)

| **Item**       | **Descrição**                                                                 |
|----------------|--------------------------------------------------------------------------------|
| **Título**     | Agendar atendimento presencial no Detran-DF                                   |
| **Objetivo**   | Permitir que o usuário realize o agendamento de serviços presenciais como vistoria, renovação da CNH, entre outros, diretamente pelo aplicativo do Detran-DF |
| **Contexto**   | **Local:** Aplicativo do Detran-DF, na seção de agendamentos  <br>**Tempo:** Em tempo real  <br>**Pré-condição:** O usuário deve possuir cadastro e estar logado no aplicativo |
| **Atores**     | Usuários do aplicativo Detran-DF                                               |
| **Recursos**   | Conexão com a internet  <br>Smartphone com o aplicativo Detran-DF instalado e conta ativa |
| **Episódios**  | 1. O usuário acessa o aplicativo e seleciona a opção "Agendamentos"  <br>2. Escolhe o tipo de serviço (ex: vistoria, CNH)  <br>3. Seleciona o posto de atendimento desejado  <br>4. Escolhe a data e o horário disponíveis  <br>5. Confirma o agendamento  <br>6. Recebe a confirmação via aplicativo ou e-mail |
| **Restrição**  | Os horários disponíveis são limitados à agenda dos postos físicos do Detran-DF |
| **Exceção**    | Falta de vagas no dia/horário desejado  <br>Falta de conexão com a internet  <br>Aplicativo indisponível por manutenção |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

## Sistema de pagamento de taxas e débitos

A tabela 2 descreve o cenário do requisito funcional Sistema de pagamento de taxas e débitos, que foi rastreada  pela técnica de elecitação BS03

#### Tabela 2: Cenário -Sistema de pagamento de taxas e débitos

| **Item**       | **Descrição**                                                                 |
|----------------|--------------------------------------------------------------------------------|
| **Título**     | Pagamento de taxas e débitos no aplicativo Detran-DF                          |
| **Objetivo**   | Permitir que o usuário visualize e realize o pagamento de taxas, multas, IPVA, licenciamento e demais débitos vinculados ao veículo diretamente pelo aplicativo |
| **Contexto**   | **Local:** Aplicativo do Detran-DF, na seção "Débitos e Pagamentos"  <br>**Tempo:** Em tempo real  <br>**Pré-condição:** O usuário deve estar logado e com veículo vinculado ao seu CPF |
| **Atores**     | Usuários do aplicativo Detran-DF                                               |
| **Recursos**   | Conexão com a internet  <br>Smartphone com o aplicativo Detran-DF instalado e conta ativa  <br>Cartão bancário ou acesso ao internet banking |
| **Episódios**  | 1. O usuário acessa a área de "Débitos e Pagamentos" no aplicativo  <br>2. Visualiza os débitos pendentes (multas, taxas, IPVA, etc.)  <br>3. Seleciona os itens que deseja pagar  <br>4. Escolhe a forma de pagamento (cartão, boleto, Pix)  <br>5. Confirma a transação  <br>6. Recebe o comprovante digital e atualização automática no sistema |
| **Restrição**  | Pagamentos apenas de débitos vinculados ao CPF do usuário ou seus veículos autorizados |
| **Exceção**    | Erro na transação bancária  <br>Falta de conexão com a internet  <br>Serviço indisponível temporariamente |


<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 14/05/2025 | criação do documento, introdução, metodologia e objetivo |  [Giovana Barbosa](https://github.com/gio221)   | |
|  1.1   | 15/05/2025 | cenário Realizar agendamentos presencias (vistoria, CNH, etc.)  |  [Giovana Barbosa](https://github.com/gio221)   | |
|  1.2   | 15/05/2025 | cenário Sistema de pagamento de taxas e débitos |  [Giovana Barbosa](https://github.com/gio221)   | |