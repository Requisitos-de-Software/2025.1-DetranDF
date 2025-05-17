## Introdução

Este documento apresenta a Especificação Suplementar do aplicativo do Detran-DF, utilizando o modelo FURPS+ para garantir que o sistema atenda não apenas aos requisitos funcionais, mas também aos aspectos de qualidade como segurança, desempenho, usabilidade e suporte. A proposta é assegurar uma aplicação eficiente, confiável e acessível para os cidadãos do Distrito Federal.

## Objetivo

O objetivo deste documento é descrever os requisitos suplementares que complementam os funcionais, visando a construção de um aplicativo que ofereça serviços como consulta de multas, agendamento de atendimentos, emissão de documentos e acompanhamento de processos administrativos de forma segura, prática e acessível.

## Metodologia

A especificação segue o modelo FURPS+, que organiza os requisitos nas seguintes categorias:

- **Funcionalidade:** Regras de negócio, validações e exigências legais específicas do Detran-DF.
- **Usabilidade:** Interface intuitiva, acessibilidade e experiência do usuário.
- **Confiabilidade:** Segurança dos dados, disponibilidade e tolerância a falhas.
- **Desempenho:** Tempos de resposta, capacidade de atendimento em horários de pico e escalabilidade.
- **Suporte:** Manutenção, documentação e compatibilidade com múltiplas plataformas (Android, iOS e Web).
- **Outros:** Restrições legais, padrões de identidade digital e integração com sistemas governamentais.

## Especificação Suplementar

#### Funcionalidades

Os requisitos foram coletados por meio das técinas de elicitação:

- Brainstorm
- Glossário
- Introspecção
- Observação

Os requisitos elicitados são organizados no artefato [Requisitos elicitados](http://127.0.0.1:8000/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/)

#### Usabilidade

A usabilidade trata da experiência do usuário ao interagir com o sistema. Foca em tornar a interface intuitiva, fácil de usar e acessível a diferentes tipos de usuários, garantindo que o sistema seja eficiente e agradável. A tabela 1 mostra os requisitos não funcionais que se encaixam em "usabilidade"

<font size="3"><p style="text-align: center">**Tabela 1 -** Requisitos Não Funcionais – Usabilidade.</p></font>

|  ID  |                                           Descrição                                           | Rastreabilidade |
| :--: | :-------------------------------------------------------------------------------------------: | :-------------: |
| US01 |        Relaciona-se diretamente à facilidade de uso e organização lógica da interface         |      RNF01      |
| US02 | Melhora a compreensão do sistema, auxiliando usuários a entenderem funcionalidades complexas. |      RNF04      |
| US03 |         Garante acesso a usuários com diferentes necessidades visuais ou preferências         |      RNF05      |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

#### Confiabilidade

Confiabilidade diz respeito à operação correta e estável do sistema ao longo do tempo. Inclui tolerância a falhas, recuperação de erros e integridade dos dados e processos. Um sistema confiável transmite segurança e reduz riscos. A Tabela 2 mostra os requisitos não funcionais que se encaixam em confiabilidade.

<font size="3"><p style="text-align: center">**Tabela 2 -** Requisitos Não Funcionais – Confiabilidade.</p></font>

|  ID  |                                                            Descrição                                                             | Rastreabilidade |
| :--: | :------------------------------------------------------------------------------------------------------------------------------: | :-------------: |
| US01 |    Segurança é parte da confiabilidade, pois falhas na proteção de dados comprometem a integridade e a confiança no sistema.     |      RNF03      |
| US02 | Garante que as informações sejam compreendidas corretamente, evitando erros de uso, o que reforça a confiabilidade da interação. |      RNF12      |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

#### Desempenho

Desempenho refere-se à capacidade do sistema de responder de forma rápida e eficiente às solicitações dos usuários. Engloba tempo de resposta, uso de recursos, escalabilidade e suporte a múltiplos acessos simultâneos. Um bom desempenho assegura uma experiência ágil mesmo em situações de alta demanda. A Tabela 3 mostra os requisitos não funcionais que se encaixam em desempenho.

<font size="3"><p style="text-align: center">**Tabela 3 -** Requisitos Não Funcionais – Desempenho.</p></font>

|  ID  |                                                                                     Descrição                                                                                      | Rastreabilidade |
| :--: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------: |
| US01 | Relaciona-se ao desempenho pois o sistema deve manter sua performance estável em diferentes ambientes (Android, iOS, navegadores), exigindo otimização para múltiplas plataformas. |      RNF02      |
| US02 |                            Aumenta o número de acessos simultâneos; o sistema deve ter bom desempenho sob picos de tráfego sem lentidão ou travamentos.                            |      RNF08      |
| US03 |                                 Está diretamente ligado ao desempenho, pois exige respostas rápidas do sistema para garantir fluidez na navegação.                                 |      RNF10      |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

#### Ajuda e Documentação
A seção de Ajuda e Documentação de um aplicativo é composta por uma série de recursos projetados para instruir e informar os usuários acerca da operação, funcionalidades e práticas recomendadas para o uso do aplicativo. Esta parte é essencial para assegurar que os usuários consigam empregar o aplicativo eficientemente, esclarecer incertezas e extrair o máximo proveito de suas capacidades. Na tabela 5 temos os requitos elicitados para tal.

| ID    | Descrição                                              | Rastreabilidade                                                                                  |
| --------- | ------------------------------------------------------ | ----------------------------------------------------------------------------------------------- |
| US01 | Interface intuitiva e fácil de navegar                 | **RNF01**      |
| US02 | Acessibilidade (fonte grande, contraste, modo noturno) | **RNF05**      |
| US03 | Leitor de tela e assistente por voz para pessoas cegas | **RNF05**      |
| US04 | Acessibilidade para diferentes perfis de usuários      | **RNF11**      |

<font size="3"><p style="text-align: center">Fonte: [Pedro Camilo](https://github.com/PedrooCamilo) , 2025.</p></font>


## Histórico de versão

| Versão |    Data    |                                     Descrição                                      |                    Autor                     |                  Revisor                   |
| :----: | :--------: | :--------------------------------------------------------------------------------: | :------------------------------------------: | :----------------------------------------: |
|  1.0   | 14/05/2025 |                                criação do documento                                | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.1   | 14/05/2025 |                    adicionei introdução, obejtivo e metodlogia                     | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.1   | 14/05/2025 |                       adicionei funcionalidade e usabilidade                       | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.2   | 17/05/2025 | Adição de tabelas de Confiabilida e desempenho, relacionando as mesmas com as RNFS |  [João Lobo](https://github.com/joaolobo10)  |                                            |
|  1.3   | 17/05/2025 | Adição de tabelas de Ajuda e Documentação |  [Pedro Camilo](https://github.com/PedrooCamilo)  |                                            |
