# Introdução

<p align="justify">
Com o avanço das tecnologias móveis, órgãos públicos têm adotado aplicativos para melhorar o atendimento à população e reduzir a necessidade de deslocamentos presenciais. O aplicativo do Departamento de Trânsito do Distrito Federal (DETRAN-DF) segue essa tendência, oferecendo funcionalidades como consulta de débitos, agendamento de serviços e acompanhamento de processos. A análise do uso real desses sistemas é crucial para entender as interações dos usuários, identificar problemas de usabilidade e sugerir melhorias. A técnica de observação direta se mostra eficaz nesse contexto, permitindo a elicitação de requisitos com base no comportamento espontâneo dos usuários.
</p>

# Objetivo

<p align="justify">
Identificar aspectos relacionados à usabilidade, navegação e desempenho do aplicativo DETRAN-DF por meio da técnica de elicitação por observação. Analisaremos o comportamento dos usuários durante o uso, destacando oportunidades de melhoria que contribuam para uma melhor experiência e eficiência no sistema.
</p>

# Observações com Usuários

Durante a elicitação de requisitos, aplicamos a técnica de observação com dois usuários diferentes utilizando sistemas semelhantes ao que está sendo proposto. O objetivo foi compreender o uso espontâneo de funcionalidades e identificar requisitos reais a partir do comportamento e das decisões dos usuários. A análise das observações foi feita com base nas personas previamente definidas no projeto.

## Primeira Observação – Usuária 1

<p align="justify">
A primeira observação foi conduzida com uma usuária que utilizou a plataforma de IA para adaptar seu currículo com base em vagas específicas. Durante a realização da tarefa, a usuária explicou verbalmente as etapas do processo, o que possibilitou uma observação ativa. A observadora pôde fazer perguntas sobre as funcionalidades mais utilizadas, dificuldades percebidas e contexto de uso. A usuária também relatou outros usos da IA, como suporte na escrita de documentos e organização profissional.
</p>

**Persona associada:** [Marina Souza](#persona-2---primária)  

---

## Segunda Observação – Usuário 2

<p align="justify">
A segunda observação foi realizada com um usuário que demonstrou duas interações distintas com a IA. Na primeira, solicitou a geração de um e-mail formal em inglês para pedir férias no trabalho. Na segunda, utilizou a ferramenta para buscar informações sobre algoritmos para resolução de cubo mágico, atividade que faz parte de seus interesses pessoais. Esta observação foi passiva, sem interferência da observadora, com foco em captar o uso natural da interface e das funcionalidades.
</p>

**Persona associada:** [Diego Martins](#persona-3---secundária)  


---

> As observações contribuíram para a identificação de funcionalidades essenciais, além de levantarem oportunidades de melhoria na usabilidade e acessibilidade do sistema com base em situações reais de uso.


# Requisitos Funcionais

**A tabela abaixo descreve os requisitos funcionais observados.**

### Tabela 1: Requisitos Funcionais

| Código | Requisito Funcional                                       | Nome   | Nível de Prioridade | Sugestão de Melhoria                                                |
|--------|-----------------------------------------------------------|--------|----------------------|----------------------------------------------------------------------|
| RF01   | Permitir consulta de multas e débitos do veículo          | OBS001 | Alta                 | Tornar a opção mais visível e acessível na tela principal           |
| RF02   | Realizar agendamento de serviços (vistoria, CNH, etc.)    | OBS002 | Alta                 | Simplificar o fluxo e adicionar barra de progresso                  |
| RF03   | Exibir informações da CNH e pontuação                      | OBS003 | Média                | Melhorar desempenho e indicar carregamento em andamento             |
| RF04   | Permitir acompanhamento de processos                       | OBS004 | Média                | Renomear menu com termos mais claros e autoexplicativos             |
| RF05   | Exibir notificações de prazos e documentos vencidos       | OBS005 | Alta                 | Corrigir sistema de push notifications                              |
| RF06   | Reposição de placa Mercosul                               | OBS006 | Alta                 | Tornar opção mais visível                                           |
| RF07   | Conversão de placa Mercosul                                | OBS007 | Alta                 | Tornar opção mais visível                                           |
| RF08   | Histórico de infração do condutor                          | OBS008 | Média                | Ser de fácil acesso                                                 |
| RF09   | Histórico de infração do veículo                           | OBS009 | Média                | Ser de fácil acesso                                                 |
| RF10   | Conversão de autuação em penalidade                        | OBS010 | Média                | Ter menos passos                                                    |
| RF11   | Protocolo-e, nova solicitação                              | OBS011 | Média                | Ter menos passos, ser mais acessível                                |
| RF12   | Protocolo-e, acompanhar solicitação                        | OBS012 | Média                | Ter menos passos, ser mais acessível                                |
| RF13   | Autorização de estacionamento de idoso                     | OBS013 | Baixa                | Ser mais acessível                                                  |
| RF14   | Autorização de estacionamento: Transtorno espectro autista| OBS014 | Baixa                | Ser mais acessível                                                  |
| RF15   | Pagamento para liberação do carro no pátio                 | OBS015 | Baixa                | Funcionalidade nova                                                 |
| RF16   | Simulado de prova teórica (autoescolas)                   | OBS016 | Baixa                | Funcionalidade nova                                                 |
| RF17   | Ter uma seção sobre leilão                                 | OBS017 | Baixa                | Funcionalidade nova                                                 |
| RF18   | Verificar se o veículo tem autorização para transporte escolar | OBS018 | Média           | Funcionalidade nova                                                 |
| RF19   | Solicitar autorização para transporte escolar              | OBS019 | Baixa                | Funcionalidade nova                                                 |

<sub>Fonte: [Maria Eduarda](https://github.com/maaduh), 2025.</sub>

# Requisitos Não-Funcionais

**A tabela abaixo descreve os requisitos não-funcionais observados.**

### Tabela 2: Requisitos Não-Funcionais

| Código | Requisito Não-Funcional                                  | Nome   | Nível de Prioridade | Sugestão de Melhoria                                          |
|--------|-----------------------------------------------------------|--------|----------------------|----------------------------------------------------------------|
| RNF01  | Interface intuitiva e fácil de navegar                    | OBS001 | Alta                 | Redesenhar o layout e menus com foco na hierarquia visual      |
| RNF02  | Carregamento rápido das páginas                           | OBS002 | Alta                 | Otimizar chamadas à API e melhorar tempo de resposta           |
| RNF03  | Acessibilidade para diferentes perfis de usuário          | OBS003 | Média                | Adotar padrões de acessibilidade e contraste adequado           |
| RNF04  | Compatibilidade com diferentes dispositivos e sistemas    | OBS004 | Alta                 | Melhorar testes de compatibilidade e otimização por modelo      |
| RNF05  | Segurança na exibição de dados pessoais                   | OBS005 | Alta                 | Adicionar autenticação de dois fatores para dados críticos      |

<sub>Fonte: [Maria Eduarda](https://github.com/maaduh), 2025.</sub>

### Video da validação com o usuario 1

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/YKwzHX9pFpQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p>
<p style="text-align: center"><a href=" https://youtu.be/YKwzHX9pFpQ" target="blanket">Vídeo da validação com o usuário</a></p>

### Video da validação com o usuario 2

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/H6mO8NqY6gg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p>
<p style="text-align: center"><a href=" https://youtu.be/H6mO8NqY6gg" target="blanket">Vídeo da validação com o usuário</a></p>

# Bibliografia

> 1. Aplicativo do DetranDF. Disponível em: Apple Store. Acesso em: 12 abr. 2025.

# Histórico de Versão

| Versão | Data       | Descrição                          | Autor                                           | Revisor                                                                              |
|--------|------------|------------------------------------|------------------------------------------------|--------------------------------------------------------------------------------------|
| 1.0    | 21/04/2025 | Início da documentação             | [Maria Eduarda](https://github.com/maaduh)     | [Luiz Bessa](https://github.com/lfelipebessa), [Giovana Barbosa](https://github.com/gio221) |
| 1.1    | 01/05/2025 | Adicionando nomenclatura           | [Giovana Barbosa](https://github.com/gio221)   | [Maria Eduarda](https://github.com/maaduh)                                           |
| 1.2    | 03/05/2025 | Adicionando sugestão de melhoria   | [Maria Eduarda](https://github.com/maaduh)     | [Giovana Barbosa](https://github.com/gio221)                                         |
| 1.3    | 07/06/2025 | Adição de anchors nas tabelas      | [Gabriel Mendes](https://github.com/gbevi)     |   [Maria Eduarda](https://github.com/maaduh)        |
| 1.4    | 20/06/2025 | Melhorando erros     | [Maria Eduarda](https://github.com/maaduh)     |  [Pedro Camilo](https://github.com/PedrooCamilo)       |
| 1.5    | 21/06/2025 | Validação da técnica com usuário     | [Pedro Camilo](https://github.com/PedrooCamilo)     | [Maria Eduarda](https://github.com/maaduh)    |
| 1.6    | 22/06/2025 | Validação da técnica com usuário     | [Maria Eduarda](https://github.com/maaduh)     |     |

