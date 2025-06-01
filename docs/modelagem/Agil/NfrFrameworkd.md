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

- **Fase 5: Propragação de impactos**:
   No NFR Framework, a propagação de impactos consiste em identificar as relações de dependência entre os requisitos não funcionais e analisar como alterações em um requisito podem influenciar outros requisitos relacionados.

   A seguir, são apresentados os tipos de softgoals que representam os impactos e suas respectivas notações:

- ✓ (satisfeito): indica que um requisito não funcional contribui de forma positiva para a satisfação de outro requisito.

- 𝒲+ (fracamente satisfeito): representa uma relação positiva, porém menos intensa do que a notação ✓.

- X (negado): indica que um requisito não funcional prejudica ou contradiz a realização de outro requisito.

- 𝒲- (fracamente negado): similar à notação X, porém com uma influência negativa menos forte.

- 🗲 (conflitante): representa uma relação de conflito, em que os requisitos apresentam aspectos tanto positivos quanto negativos.

- u (indeterminado): indica uma relação desconhecida ou indefinida entre os requisitos, quando não há informações suficientes para avaliar o impacto.

# Cartões de Especificação
Temos um modelo de cartões de especificação para ultilizarmos, especificado na tabela 1

<font size="3"><b>Tabela 1:</b>Modelo de Cartões de Especificação</font>

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

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>


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

#### SIG de Acessibilidade

Na figura monstra o SIG de Acessibilidade 

<font size="3"><p style="text-align: center"><b> Figura 1:</b> SIG-Acessibilidade</font>
![SIG-Acessibilidade](../../assets/Captura%20de%20tela%202025-06-01%20001723.png)
 <font size="3"><p style="text-align: center"><b>Fonte:</b> miro</font>

Na tabela 2 temos os requisitos não funcionais de acessibilidade 

<font size="3"><b>Tabela 2:</b>requisitos não funcionais de acessibilidade </font>

| Código | Requisito |
|--------|-----------|
| RNF05 | Acessibilidade (fonte grande, contraste, modo noturno) |
| RNF06 | Leitor de tela e assistente por voz para pessoas cegas |
| RNF11 | Acessibilidade para diferentes perfis de usuários |
| RNF13 | Texto com fontes ajustáveis e botões grandes |
| RNF14 | Interface adaptada para idosos e iniciantes *(também em Usabilidade)* |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

#### Cartões de Especificação:

Na tabela 3 temos o requisito não funcional 05

<font size="3"><b>Tabela 2:</b>requisito não funcional 05 </font>

|                  Item                   |                                                                      Descrição                                                                       |
| :-------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Nr Requisito** RNF05 |                                       **Classificação**: Acessibilidade Visualcatálogo                                        |
|              **Descrição**              |                                                  O sistema deve permitir uso de fontes grandes, oferecer modo noturno e garantir contraste elevado.         |
|            **Justificativa**            |                                                 Usuários com baixa visão ou sensibilidade à luz precisam de recursos que tornem a leitura confortável.             |
|               **Origem**                |                                               BS17                   |
|        **Critério de Aceitação**        |                                    Conformidade com WCAG 2.1 (nível AA); modo noturno ativável; ajuste de tamanho de fonte ≥ 3 níveis   |
|            **Dependências**             |                                                           RNF13, RNF14              |
|             **Prioridade**              |9|
|              **Conflitos**              |                     Possível conflito com design minimalista padrão    |
|              **História**               |                                                      Criado em 01/06/2025       |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

Na tabela 4 temos o requisito não funcional 06

<font size="3"><b>Tabela 2:</b>requisito não funcional 06 </font>

|                  Item                   |                                                                      Descrição                                                                       |
| :-------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Nr Requisito** RNF06 |                                       **Classificação**:  Acessibilidade Auditiva e Visual                                   |
|              **Descrição**              |                 O sistema deve ser compatível com leitores de tela e possuir assistente por voz funcional.      |
|            **Justificativa**            |               Essencial para usuários cegos ou com baixa visão total.          |
|               **Origem**                |                                            BS18                  |
|        **Critério de Aceitação**        |                                 Compatibilidade com NVDA e VoiceOver; feedback auditivo completo das ações  |
|            **Dependências**             |                                                        RNF11            |
|             **Prioridade**              | 10|
|              **Conflitos**              |                   Nenhum identificado  |
|              **História**               |                                                      Criado em 01/06/2025       |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

Na tabela 5 temos o requisito não funcional 11

<font size="3"><b>Tabela 2:</b>requisito não funcional 11 </font>

|                  Item                   |                                                                      Descrição                                                                       |
| :-------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Nr Requisito** RNF11|                                       **Classificação**:  Acessibilidade Geral   |
|              **Descrição**              |           O sistema deve suportar múltiplos perfis de usuários com diferentes limitações cognitivas, motoras e visuais.      |
|            **Justificativa**            |      Aumenta a inclusão digital e atende normas legais.           |
|               **Origem**                |                                              IS09                  |
|        **Critério de Aceitação**        |     Suporte a navegação por teclado, linguagem simplificada e suporte a múltiplos modos sensoriais (visual, sonoro)  |
|            **Dependências**             |                                                         RNF06, RNF13             |
|             **Prioridade**              |10|
|              **Conflitos**              |                    Nenhum identificado    |
|              **História**               |                                                      Criado em 01/06/2025       |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>


Na tabela 6 temos o requisito não funcional 13

<font size="3"><b>Tabela 2:</b>requisito não funcional 13 </font>

|                  Item                   |                                                                      Descrição                                                                       |
| :-------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Nr Requisito** RNF13 |                                       **Classificação**: Acessibilidade Visual e Motora         |
|              **Descrição**              |                                      O sistema deve permitir ajuste do tamanho das fontes e botões com área de toque ampliada.     |
|            **Justificativa**            |                 Facilita o uso por idosos e pessoas com dificuldades motoras ou visuais.        |
|               **Origem**                |                                Storytelling - Olavo                |
|        **Critério de Aceitação**        |             Fontes ajustáveis em 3 níveis |
|            **Dependências**             |                                                           RNF05, RNF14             |
|             **Prioridade**              |8|
|              **Conflitos**              |                     Pode afetar o layout responsivo em telas menores   |
|              **História**               |                                                      Criado em 01/06/2025       |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

Na tabela 7 temos o requisito não funcional 14

<font size="3"><b>Tabela 7 :</b>requisito não funcional 14 </font>

|                  Item                   |                                                                      Descrição                                                                       |
| :-------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Nr Requisito** RNF14 |                                       **Classificação**: Acessibilidade Cognitiva / Usabilidade          |
|              **Descrição**              |                                         A interface deve ser simplificada, clara e com instruções visuais para facilitar o uso por idosos e iniciantes.      |
|            **Justificativa**            |                     Reduz barreiras de entrada para novos usuários ou com pouca familiaridade tecnológica.   |
|               **Origem**                |                               Storytelling - Olavo, Marina                 |
|        **Critério de Aceitação**        |                             Testes com idosos resultando em taxa de sucesso > 80% nas tarefas básicas  |
|            **Dependências**             |                                                       RNF05, RNF13             |
|             **Prioridade**              |9|
|              **Conflitos**              |                     Pode conflitar com usuários avançados que desejam personalização ou funções avançadas   |
|              **História**               |                                                      Criado em 01/06/2025       |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

#### Propagação de Impactos
Na tabela 8 temos a propagação de impactos da acessibilidade 

<font size="3"><b>Tabela 8:</b>requisito não funcional 14 </font>

| NFR                                                                 | Impacto | Avaliador         |
|----------------------------------------------------------------------|---------|--------------------|
| O sistema deve ser capaz de montar uma atividade de forma fácil      | 𝒲++     | [Giovana Barbosa](https://github.com/gio221)  |
| O sistema deve ser claro de forma que o usuário possa entender e realizar uma tarefa sem dificuldades | 𝒲+      | [Giovana Barbosa](https://github.com/gio221)  |
| Capacidade de Aprendizado                                            | 𝒲++     | [Giovana Barbosa](https://github.com/gio221) |
| Adaptabilidade                                                       | 𝒲+      | [Giovana Barbosa](https://github.com/gio221)  |
| Proteção contra os erros                                             | X       | [Giovana Barbosa](https://github.com/gio221) |
| Intuitivo                                                            | X       | [Giovana Barbosa](https://github.com/gio221) |
| Usabilidade                                                          | 𝒲++     | [Giovana Barbosa](https://github.com/gio221)  |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

#### Validação com o usuário

No video abaixo é feito a validação da parte de acessibilidade pela integrante [Giovana Barbosa](https://github.com/gio221) com a usuária Débora

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/xKJIMlwFndg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p>
<p style="text-align: center"><a href=" https://youtu.be/xKJIMlwFndg" target="blanket">Vídeo da= validação com o usuário</a></p>


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

---
Na figura monstra o SIG de Acessibilidade 

<font size="3"><p style="text-align: center"><b> Figura 10:</b> SIG-Qualidade e feedback</font>
![SIG-QualidadeEFeedback](../../assets/QualidadeeFeedback-2.pdf)
 <font size="3"><p style="text-align: center"><b>Fonte:</b> [Luiz Bessa](https://github.com/lfelipebessa)</font>
---

### Cartão 5 – RNF07  <a id="cartao-rnf07"></a>

|            Item           | Descrição |
|---------------------------|-----------|
| **Nr Requisito**          | **RNF07** |
| **Classificação**         | Requisito Não Funcional → Qualidade e Feedback → Avaliação do usuário |
| **Descrição**             | O sistema deve disponibilizar mecanismo de avaliação *in-app* (1 a 5 estrelas) após a conclusão de serviços chave, permitindo comentários opcionais. |
| **Justificativa**         | Capturar percepção real de qualidade, priorizar melhorias e aumentar a confiabilidade pública do app. |
| **Origem**                | Stakeholders; boas práticas de UX; diretrizes Google Play / App Store. |
| **Critério de Aceitação** | • Solicitação de rating exibida **no máximo 1 vez/mês** por usuário.<br>• Alcançar média ≥ 4,5 estrelas após 6 meses.<br>• Comentários sincronizados com a loja correspondente. |
| **Dependências**          | RNF17 (Feedback visual/sonoro) – usado no prompt;<br>RNF10 (Carregamento rápido) para não atrasar a tela de rating. |
| **Prioridade**            | 8 |
| **Conflitos**             | Pode conflitar com Usabilidade se o prompt for intrusivo; mitigar exibindo só após tarefa concluída. |
| **História**              | Criado: 31-05-2025   Última mod.: 31-05-2025 |

<font size="3"><p align="center">Fonte: <a href="https://github.com/lfelipebessa">Luiz Bessa</a>, 2025.</p></font>

---

### Cartão 6 – RNF08  <a id="cartao-rnf08"></a>

|            Item           | Descrição |
|---------------------------|-----------|
| **Nr Requisito**          | **RNF08** |
| **Classificação**         | Requisito Não Funcional → Qualidade e Feedback → Promoção e Divulgação |
| **Descrição**             | O sistema deve oferecer mecanismos de divulgação (banner interno, push direcionado, redes sociais) para aumentar adesão dos usuários e divulgar novos serviços. |
| **Justificativa**         | Ampliar base de usuários e conscientizar sobre funcionalidades que reduzem filas presenciais. |
| **Origem**                | Stakeholders (Marketing DETRAN-DF). |
| **Critério de Aceitação** | • Push **não-promocional** limitado a 1 envio/semana.<br>• Taxa de *opt-out* ≤ 20 %.<br>• Campanhas internas carregam em < 300 ms. |
| **Dependências**          | RNF01 (Interface intuitiva) – posicionamento dos banners;<br>RNF10 (Desempenho) – carregamento rápido das campanhas. |
| **Prioridade**            | 6 |
| **Conflitos**             | Pode impactar Usabilidade (clutter) e Desempenho; mitigado por regras de frequência e cache local. |
| **História**              | Criado: 31-05-2025   Última mod.: 31-05-2025 |

<font size="3"><p align="center">Fonte: <a href="https://github.com/lfelipebessa">Luiz Bessa</a>, 2025.</p></font>

---


## Histórico de versão

| Versão |    Data    |              Descrição              |                     Autor                     | Revisor |
| :----: | :--------: | :---------------------------------: | :-------------------------------------------: | :-----: |
|  1.0   | 20/05/2025 |       Início da documentação        | [Giovana Barbosa ](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.1   | 20/05/2025 |       Iintrodução, objetivo, meotodologia, cartões de especificação        | [Giovana Barbosa ](https://github.com/gio221) | [João Lobo](https://github.com/joaolobo10) |
|  1.2   | 31/05/2025 |       Adição de cartões para RNF03, 18 e 19, criação de cartão para Disponbilidade e Confiabilidade        | [João Lobo](https://github.com/joaolobo10) | [Luiz Bessa](https://github.com/lfelipebessa) |
|  1.3   | 31/05/2025 |       Adição de cartões para RNF07 e 08 criação de cartão para Qualidade e Feedback | [Luiz Bessa](https://github.com/lfelipebessa) |[Giovana Barbosa ](https://github.com/gio221) |
|  1.4  | 31/05/2025 |       Adição de cartões para acessibilidade, SIG e a Propragação de impactos: | [Giovana Barbosa ](https://github.com/gio221) | [Luiz Bessa](https://github.com/lfelipebessa) |
|  1.5  | 01/06/2025 |       Adição SIG Qualidade e Feedback | [Luiz Bessa](https://github.com/lfelipebessa) | |