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

<a id="desempenho"></a>

#### Desempenho

Desempenho refere-se à capacidade do sistema de responder de forma rápida e eficiente às solicitações dos usuários. Engloba tempo de resposta, uso de recursos, escalabilidade e suporte a múltiplos acessos simultâneos. Um bom desempenho assegura uma experiência ágil mesmo em situações de alta demanda. A Tabela 3 mostra os requisitos não funcionais que se encaixam em desempenho.

<font size="3"><p style="text-align: center">**Tabela 3 -** Requisitos Não Funcionais – Desempenho.</p></font>

|  ID  |                                                                                     Descrição                                                                                      | Rastreabilidade |
| :--: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------: |
| US01 | Relaciona-se ao desempenho pois o sistema deve manter sua performance estável em diferentes ambientes (Android, iOS, navegadores), exigindo otimização para múltiplas plataformas. |      RNF02      |
| US02 |                            Aumenta o número de acessos simultâneos; o sistema deve ter bom desempenho sob picos de tráfego sem lentidão ou travamentos.                            |      RNF08      |
| US03 |                                 Está diretamente ligado ao desempenho, pois exige respostas rápidas do sistema para garantir fluidez na navegação.                                 |      RNF10      |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

<a id="suportabilidade"></a>

#### Suportabilidade
 
Esta seção apresenta os requisitos não-funcionais já elicitados que impactam diretamente a **manutenibilidade, instalação, operação e atualização** do aplicativo — ou seja, sua suportabilidade ao longo do ciclo de vida.

<font size="3"><p style="text-align: center">**Tabela 1 –** Requisitos Não Funcionais – Suportabilidade.</p></font>

| ID    | Descrição originalmente elicitada | Rastreabilidade |
|:-----:|:----------------------------------|:---------------:|
| RNF02 | Compatibilidade com diferentes dispositivos e sistemas | RNF02 |
| RNF10 | Carregamento rápido das páginas | RNF10 |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>


#### Ajuda e Documentação
A seção de Ajuda e Documentação de um aplicativo é composta por uma série de recursos projetados para instruir e informar os usuários acerca da operação, funcionalidades e práticas recomendadas para o uso do aplicativo. Esta parte é essencial para assegurar que os usuários consigam empregar o aplicativo eficientemente, esclarecer incertezas e extrair o máximo proveito de suas capacidades. Na tabela 5 temos os requitos elicitados para tal.

| ID    | Descrição                                              | Rastreabilidade                                                                                  |
| --------- | ------------------------------------------------------ | ----------------------------------------------------------------------------------------------- |
| AD01 | Interface intuitiva e fácil de navegar                 | [RNF01](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais)      |
| AD02 | Acessibilidade (fonte grande, contraste, modo noturno) | **RNF05**      |
| AD03 | Leitor de tela e assistente por voz para pessoas cegas | **RNF05**      |
| AD04 | Acessibilidade para diferentes perfis de usuários      | **RNF11**      |
| AD05 | Explicações acessíveis sobre siglas                    | **RNF12**      |


<font size="3"><p style="text-align: center">Fonte: [Pedro Camilo](https://github.com/PedrooCamilo) , 2025.</p></font>
<a id="restri"></a>

#### Restrições de Design

As restrições de design definem limitações e diretrizes que devem ser respeitadas no desenvolvimento do aplicativo, garantindo coerência visual, aderência a padrões institucionais e compatibilidade técnica.

<font size="3"><p style="text-align: center">**Tabela 6 –** Requisitos Não Funcionais – Restrições de Design.</p></font>

| ID    | Descrição                                                                                         | Rastreabilidade |
|-------|---------------------------------------------------------------------------------------------------|-----------------|
| RD01  | O aplicativo deve seguir a identidade visual do Governo do Distrito Federal                       | RNF09           |
| RD02  | A interface deve adotar layout responsivo                                                         | RNF01, RNF02    |
| RD03  | O aplicativo deve utilizar componentes nativos dos sistemas Android e iOS                         | RNF02           |
| RD04  | Os textos devem ser exibidos em português do Brasil                                               | RNF01           |
| RD05  | O aplicativo deve manter compatibilidade com o design system do gov.br sempre que possível        | RF15            |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

### Requisitos de Implementação

Os requisitos de implementação definem aspectos técnicos e operacionais necessários para a construção, integração e entrega do sistema. Eles abordam práticas de codificação, ambiente de desenvolvimento, integração contínua e critérios específicos adotados durante a fase de desenvolvimento do aplicativo.

<font size="3"><p style="text-align: center">**Tabela 7 –** Requisitos Não Funcionais – Requisitos de Implementação.</p></font>


| ID    | Descrição                                                                                                                  | Rastreabilidade |
|-------|----------------------------------------------------------------------------------------------------------------------------|-----------------|
| RI01  | O sistema deve ser desenvolvido utilizando frameworks compatíveis com Android, iOS e Web. | RNF06           |
| RI02  | O repositório do projeto deve ser hospedado no GitHub, com versionamento contínuo.                                          | RNF07           |
| RI03  | Devem ser utilizados pipelines de integração contínua para execução automática de testes a cada novo commit.               | RNF07           |
| RI04  | O ambiente de desenvolvimento deve ser compatível com sistemas operacionais Windows, Linux e macOS.                        | RNF06           |
| RI05  | O projeto deve seguir boas práticas de desenvolvimento seguro, como criptografia de senhas e proteção contra injeções de código. | RNF03           |

<font size="3"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>

<a id="requi"></a>

#### Requisitos Físicos

Os requisitos físicos descrevem as necessidades de hardware e ambiente para o uso do aplicativo. Embora voltado principalmente para dispositivos móveis, o sistema deve considerar as condições de uso típicas dos usuários.

<font size="3"><p style="text-align: center">**Tabela 8 –** Requisitos Não Funcionais – Requisitos Físicos.</p></font>

| ID    | Descrição                                                                                             | Rastreabilidade |
|-------|-------------------------------------------------------------------------------------------------------|-----------------|
| RF01  | O aplicativo deve funcionar em dispositivos com Android 8.0 ou superior                               | RNF02           |
| RF02  | O aplicativo deve funcionar em dispositivos com iOS 13 ou superior                                    | RNF02           |
| RF03  | O aplicativo deve ter desempenho satisfatório em redes móveis 3G, 4G ou Wi-Fi                         | RNF10           |
| RF04  | O tamanho do aplicativo não deve ultrapassar 100 MB                                                   | RNF10           |
| RF05  | O aplicativo deve permitir funcionamento offline para consultas básicas (ex: histórico de pesquisas)  | RF03, RF21      |

<font size="3"><p style="text-align: center">Fonte: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

## Histórico de versão

| Versão |    Data    |                                     Descrição                                      |                    Autor                     |                  Revisor                   |
| :----: | :--------: | :--------------------------------------------------------------------------------: | :------------------------------------------: | :----------------------------------------: |
|  1.0   | 14/05/2025 |                                criação do documento                                | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.1   | 14/05/2025 |                    adicionei introdução, obejtivo e metodlogia                     | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.2   | 14/05/2025 |                       adicionei funcionalidade e usabilidade                       | [Giovana Barbosa](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.3   | 17/05/2025 | Adição de tabelas de Confiabilida e desempenho, relacionando as mesmas com as RNFS |  [João Lobo](https://github.com/joaolobo10)  |        [Gabriel Mendes](https://github.com/gbevi)                                    |
|  1.4   | 17/05/2025 | Adição de tabelas de Ajuda e Documentação |  [Pedro Camilo](https://github.com/PedrooCamilo)  |     [Gabriel Mendes](https://github.com/gbevi)                                       |
|  1.5  | 17/05/2025 | Adição de tabelas de Suportabilidade |  [Gabriel Mendes](https://github.com/gbevi)  |    [Luiz Bessa](https://github.com/lfelipebessa)|
|  1.6  | 17/05/2025 | Adição de tabelas de Restrições de Design |   [Luiz Bessa](https://github.com/lfelipebessa)| [Maria Eduarda](https://github.com/maaduh) |
|  1.7  | 17/05/2025 | Adição de tabelas de Requisitos Físicos |   [Luiz Bessa](https://github.com/lfelipebessa)  | [Maria Eduarda](https://github.com/maaduh) |
|  1.8  | 17/05/2025 | Adição de tabelas de Requisitos de implementação | [Maria Eduarda](https://github.com/maaduh) |               [Giovana Barbosa](https://github.com/gio221)                             |
|  1.9  | 21/06/2025 | Adicionando Requisito Explicações acessíveis sobre siglas em ajuda e documentação  | [Pedro Camilo](https://github.com/PedrooCamilo) | [João Lobo](https://github.com/joaolobo10)|
