# Introdução
Os **Requisitos Não-Funcionais (RNFs)** são essenciais para a qualidade de sistemas de software, influenciando usabilidade, desempenho e conformidade. No entanto, são frequentemente mal definidos, o que afeta negativamente a satisfação dos stakeholders e a qualidade do produto.

Devido à sua **subjetividade e complexidade**, a documentação e análise dos RNFs são desafiadoras.

Para lidar com essas dificuldades, foi proposto o **NFR Framework** (Chung et al., 2000), que modela RNFs como **softgoals** — objetivos sem critérios de satisfação claros — organizados em **Softgoal Interdependency Graphs (SIGs)**, que mostram as relações de apoio ou conflito entre os RNFs.

# Tipos de Softgoals

- **Softgoals NFR**: Representam os requisitos não-funcionais (ex: segurança, usabilidade).
- **Softgoals de Operacionalização**: Soluções práticas para atender aos RNFs (ex: processos, estruturas de dados).
- **Softgoals de Afirmação**: Características do domínio que justificam decisões (ex: prioridades, carga de trabalho).


<font size="3"><p style="text-align: center"><b> Figura 1:</b> Tipos de Softgoals </font>
![Tipos de Softgoals](../../assets/nfr.png)
 <font size="3"><p style="text-align: center"><b>Fonte:</b> (CHUNG et al., 2000)</font>

# Objetivo 
O objetivo deste trabalho é construir um artefato baseado no NFR Framework que permita a identificação, representação e avaliação dos requisitos não-funcionais para o aplicativo Detran-DF

# Metodologia  
Para uma abordagem completa, dividimos a metodologia em algumas fases, sendo elas:

- **Fase 1: Elicitação de Requisitos Não-Funcionais**:  
Primeiro fizemos a elicitação de requisitos na etapa anterior, que pode ser encontrada nesse link [Requisitos Elicitados](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md).

- **Fase 2: Criação de Grafos de Decomposição de Softgoals e Criação de Cartões de Especificação**:

    Inspirando-se em técnicas de especificação (como as descritas no livro Requirements Engineering Fundamentals) faremos o cartão de especificação para cada decomposição:

    -	Para cada softgoal, criar cartões que detalhem:

    -	Descrição do RNF.

    -	Alternativas de implementação.

    -	Dependências e restrições.

    -	Os cartões ajudam a capturar os trade-offs entre alternativas e priorizações.

- **Fase 3: SIG**:

    Após a criação dos grafos de decomposição, o SIG é consolidado:

    -	SIG: Integrar todos os softgoals, suas contribuições e refinamentos no grafo final, criando uma visão abrangente dos RNFs para o aplicativo Detran-DF.

- **Fase 4: Avaliação e Validação**:

    Por fim, validar o artefato construído, considerando os seguintes passos:

    -	Seleção entre alternativas: Comparar diferentes abordagens utilizando critérios de qualidade, custos e impacto para selecionar a melhor solução.

    -	Revisão com stakeholders: Submeter o SIG final para análise dos stakeholders e ajustar conforme o feedback recebido.

# Cartões de Especificação
Temos um modelo de cartões de especificação para ultilizarmos

|                  Item                   |                                                                      Descrição                                                                       |
| :-------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Nr Requisito** (Um número sequencial) |                                       **Classificação**: Classificação do RNF conforme hierarquia do catálogo                                        |
|              **Descrição**              |                                                     Declaração única do significado do requisito                                                     |
|            **Justificativa**            |                                                      Justificativa sobre a criação do requisito                                                      |
|               **Origem**                |                                                Origem do requisito (stakeholder, norma técnica, etc)                                                 |
|        **Critério de Aceitação**        |                                         Métrica do requisito que possa ser testada e que deve ser satisfeita                                         |
|            **Dependências**             |                                                            Requisitos relacionados a este                                                            |
|             **Prioridade**              | Um número usado para decidir a importância relativa deste requisito entre os outros RNFs (varia de 1 a 10). A prioridade mínima é 1 e a máxima é 10 |
|              **Conflitos**              |                                                           Requisitos conflitantes com este                                                           |
|              **História**               |                                                          Data de criação e de modificações                                                           |

<p align="center"><b>Fonte:</b> [Giovana Barbosa](https://github.com/gio221), 2025</p> 


## 1. Usabilidade

Foco na experiência e facilidade de uso pelo usuário.

| Código | Requisito |
|--------|-----------|
| RNF01 | Interface intuitiva e fácil de navegar |
| RNF04 | Área educacional com explicações e vídeos |
| RNF09 | Layout com foco em simplicidade e legibilidade |
| RNF12 | Explicações acessíveis sobre siglas (ex: RENAVAM) |
| RNF14 | Interface adaptada para idosos e iniciantes |
| RNF17 | Feedback visual e sonoro nas interações do usuário |
| RNF20 | Interface com poucos elementos por tela para facilitar leitura |

---

## 2. Acessibilidade

Adequação da interface e funcionalidade para diferentes públicos.

| Código | Requisito |
|--------|-----------|
| RNF05 | Acessibilidade (fonte grande, contraste, modo noturno) |
| RNF06 | Leitor de tela e assistente por voz para pessoas cegas |
| RNF11 | Acessibilidade para diferentes perfis de usuários |
| RNF13 | Texto com fontes ajustáveis e botões grandes |
| RNF14 | Interface adaptada para idosos e iniciantes *(também em Usabilidade)* |

---

##  3. Desempenho e Eficiência

Tempo de resposta, leveza do app e uso eficiente de recursos.

| Código | Requisito |
|--------|-----------|
| RNF10 | Carregamento rápido das páginas |
| RNF15 | Aplicativo leve e com baixo consumo de dados |
| RNF16 | Tempo de resposta inferior a 2 segundos |

---

##  4. Segurança

Proteção de dados pessoais e veiculares.

| Código | Requisito |
|--------|-----------|
| RNF03 | Alta segurança no tratamento de dados pessoais e veiculares |

---

##  5. Confiabilidade e Disponibilidade

Continuidade do sistema e recuperação de falhas.

| Código | Requisito |
|--------|-----------|
| [RNF03](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos) | Alta segurança no tratamento de dados pessoais e veiculares |
| [RNF18](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos) | Disponibilidade do sistema 24/7 |
| [RNF19](../../Elicitação/Tecnicas-de-elecitação/requisitos-elicitados.md#tabela-requisitos) | Confiabilidade: recuperação de falhas e continuidade da navegação |

<font size="3"><p style="text-align: center">**Cartão 1 -** RNF03.</p></font>

|            Item           |                                                                         Descrição                                                                        |
| :-----------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------: |
|      **Nr Requisito**     |                                                                           RNF03                                                                          |
|     **Classificação**     |                                                   Requisito Não Funcional → Confiabilidade → Segurança                                                   |
|       **Descrição**       |     O sistema deve garantir alta segurança no tratamento de dados pessoais e veiculares, assegurando confidencialidade, integridade e autenticidade.     |
|     **Justificativa**     |     Proteger informações sensíveis contra acessos não autorizados, vazamentos e violações de privacidade, conforme LGPD e boas práticas de segurança.    |
|         **Origem**        |                     Stakeholders (usuários e administradores do sistema); Normas técnicas como LGPD (Lei Geral de Proteção de Dados).                    |
| **Critério de Aceitação** | Todos os dados devem ser criptografados em repouso e em trânsito; autenticação de dois fatores implementada; testes de segurança realizados e aprovados. |
|      **Dependências**     |                       RNF18 (Disponibilidade) e RNF19 (Confiabilidade), pois segurança impacta continuidade e confiança do sistema.                      |
|       **Prioridade**      |                                                                            10                                                                            |
|       **Conflitos**       |                 Pode gerar conflito com requisitos de desempenho, já que mecanismos de segurança podem impactar a velocidade do sistema.                 |
|        **História**       |                                                       Criado em: 31-05-2025; Última modificação: 31-05-2025                                                       |

<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

<font size="3"><p style="text-align: center">**Cartão 2 -** RNF18.</p></font>

|            Item           |                                                                    Descrição                                                                    |
| :-----------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: |
|      **Nr Requisito**     |                                                                      RNF18                                                                      |
|     **Classificação**     |                                            Requisito Não Funcional → Confiabilidade → Disponibilidade                                           |
|       **Descrição**       |        O sistema deve estar disponível para acesso e uso contínuo, 24 horas por dia, 7 dias por semana, sem interrupções significativas.        |
|     **Justificativa**     | Garantir que os usuários possam acessar os serviços a qualquer momento, independentemente do horário, aumentando a confiabilidade e satisfação. |
|         **Origem**        |                              Stakeholders; necessidade operacional do serviço e boas práticas de sistemas críticos.                             |
| **Critério de Aceitação** |                     Tempo médio de disponibilidade ≥ 99,9% mensal; manutenção programada comunicada com 48h de antecedência.                    |
|      **Dependências**     |                     RNF19 (Confiabilidade), já que falhas precisam ser rapidamente recuperadas para manter disponibilidade.                     |
|       **Prioridade**      |                                                                        9                                                                        |
|       **Conflitos**       |    Pode gerar conflito com requisitos de custo, pois alta disponibilidade pode exigir investimentos elevados em infraestrutura e redundância.   |
|        **História**       |                                                   Criado em: 31-05-2025; Última modificação: 31-05-2025                                                  |


<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

<font size="3"><p style="text-align: center">**Cartão 3 -** RNF19.</p></font>

|            Item           |                                                                       Descrição                                                                      |
| :-----------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: |
|      **Nr Requisito**     |                                                                         RNF19                                                                        |
|     **Classificação**     |                                            Requisito Não Funcional → Confiabilidade → Tolerância a falhas                                            |
|       **Descrição**       |      O sistema deve assegurar mecanismos de recuperação automática em caso de falhas e garantir a continuidade da navegação sem perda de dados.      |
|     **Justificativa**     |                 Evitar que falhas do sistema comprometam a experiência do usuário e causem perda de dados ou interrupção no serviço.                 |
|         **Origem**        |                           Stakeholders; boas práticas de engenharia de software; normas de qualidade de sistemas críticos.                           |
| **Critério de Aceitação** | O sistema deve conseguir se recuperar automaticamente de falhas em até 5 segundos; logs de falhas devem ser registrados e analisados periodicamente. |
|      **Dependências**     |                                   RNF18 (Disponibilidade), pois a recuperação rápida garante alta disponibilidade.                                   |
|       **Prioridade**      |                                                                          10                                                                          |
|       **Conflitos**       | Pode gerar conflito com requisitos de simplicidade e custo, já que mecanismos de redundância e recuperação podem aumentar a complexidade do sistema. |
|        **História**       |                                                     Criado em: 31-05-2025; Última modificação: 31-05-2025                                                      |


<font size="3"><p style="text-align: center">Fonte: [João Lobo](https://github.com/joaolobo10) , 2025.</p></font>

---

##  6. Portabilidade / Compatibilidade

Funcionamento do sistema em diferentes plataformas.

| Código | Requisito |
|--------|-----------|
| RNF02 | Compatibilidade com diferentes dispositivos e sistemas |

---

##  7. Qualidade e Feedback

Relacionados à avaliação do sistema e comunicação com o público.

| Código | Requisito |
|--------|-----------|
| RNF07 | Sistema de avaliação com base em uso real (ex-alunos) |
| RNF08 | Propaganda efetiva para promover o app |


## Histórico de versão

| Versão |    Data    |              Descrição              |                     Autor                     | Revisor |
| :----: | :--------: | :---------------------------------: | :-------------------------------------------: | :-----: |
|  1.0   | 20/05/2025 |       Início da documentação        | [Giovana Barbosa ](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.1   | 20/05/2025 |       Iintrodução, objetivo, meotodologia, cartões de especificação        | [Giovana Barbosa ](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.1   | 31/05/2025 |       Adição de cartões para RNF03, 18 e 19, criação de cartão para Disponbilidade e Confiabilidade        | [João Lobo](https://github.com/joaolobo10) |  |