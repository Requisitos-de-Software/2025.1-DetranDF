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

No diagram de caso de uso , precisamos ter todos esses componentes:

| **Nome**                  | **Função**                                                                                                                                   | 
|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| **Ator**                  | Representam os diferentes tipos de usuários externos que interagem com o sistema                                                             | 
| **Elipse (Caso de Uso)**  | É usada para representar os casos de uso no diagrama. Um caso de uso descreve uma funcionalidade ou uma ação específica que o sistema pode realizar em resposta às interações dos atores. A elipse contém o nome do caso de uso |
| **Retângulo (Sistema)**   | Usado para representar o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados                                     |
| **Flecha (Relações)**     | As flechas são usadas para representar as relações ou interações entre atores e casos de uso                                                  | 

## Diagram de Caso de Uso do app Detran- DF

## Especifiação do Caso de Uso

A tabela 1 descreve qual funcionalidade cada integrante vai fazer o caso de uso

| Integrante |   Cenário    |     
| :----: | :--------: | 
| [Giovana Barbosa](https://github.com/gio221) |Realizar agendamentos presencias (vistoria, CNH, etc.)|
| [Giovana Barbosa](https://github.com/gio221) |Autorização de estacionamento para idosos|

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 14/05/2025 | criação do documento |  [Giovana Barbosa](https://github.com/gio221)   | |
|  1.1   | 15/05/2025 | introdução, objetivo e metodologia |  [Giovana Barbosa](https://github.com/gio221)   | |