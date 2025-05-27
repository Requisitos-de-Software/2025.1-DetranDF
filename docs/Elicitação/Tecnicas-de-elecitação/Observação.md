#Introdução
<p align="justify">
Com o avanço das tecnologias móveis, órgãos públicos passaram a disponibilizar serviços por meio de aplicativos, visando otimizar o atendimento à população e reduzir a necessidade de deslocamentos presenciais. O aplicativo do Departamento de Trânsito do Distrito Federal (DETRAN-DF) integra essa tendência, oferecendo funcionalidades como consulta de débitos, agendamento de serviços, acompanhamento de processos, entre outras. A análise do uso real desses sistemas digitais é essencial para entender como ocorrem as interações dos usuários e quais obstáculos surgem durante a navegação. A observação direta se apresenta como uma técnica eficaz de elicitação de requisitos, permitindo identificar, com base no comportamento espontâneo dos usuários, problemas de usabilidade e oportunidades de melhoria.
</p>

#Objetivo
<p align="justify">
Identificar aspectos relacionados à usabilidade, navegação e desempenho do aplicativo DETRAN-DF por meio da técnica de elicitação por observação, analisando o comportamento dos usuários durante o uso e apontando possíveis ajustes que contribuam para a melhoria da experiência e eficiência no uso do sistema.
</p>


## Requisitos funcionais

São as funcionalidades que o sistema deve oferecer.
**A tabela 1** descreve as funcionalidades

<font size="3"><p style="text-align: center">**Tabela 1:** Requisitos Funcionais.</p></font>

| Código | Requisito Funcional                                              | Nome | Nível de Prioridade | Sugestão de Melhoria |
|--------|------------------------------------------------------------------|---------------------------|----------------------|-----------------------|
| RF01   | Permitir consulta de multas e débitos do veículo                |       OBS001                        | Alta                 |   Tornar a opção mais visível e acessível na tela principal                    |
| RF02   | Realizar agendamento de serviços (vistoria, CNH, etc.)         |        OBS002                       | Alta                 |            Simplificar o fluxo e adicionar barra de progresso           |
| RF03   | Exibir informações da CNH e pontuação                           |       OBS003                        | Média                |          Melhorar desempenho e indicar carregamento em andamento             |
| RF04   | Permitir acompanhamento de processos                            |       OBS004                        | Média                |          	Renomear menu com termos mais claros e autoexplicativos             |
| RF05   | Exibir notificações de prazos e documentos vencidos            |       OBS005                       | Alta                 |       Corrigir sistema de push notifications                |
| RF06  | Reposição de placa Mercosul          |       OBS006                       | Alta                 |    Torna opção mais visivel     |
| RF07  | Conversão de placa Mercosul          |       OBS007                       | Alta                 |    Torna opção mais visivel     |
|RF08|Histórico de infração do condutor|OBS008|média| Ser de fácil acesso|
|RF09|Histórico de infração do veículo|OBS009|média|Ser de fácil acesso|
|RF10|Converção de autuação em penalidade|OBS010|média| Ter menos passos|
|RF11|Protocolo-e, nova solicitação|OBS011|média|Ter menos passos, ser mais acessivel|
|RF12|Protocolo-e, acompanhar solicitação|OBS012|média| Ter menos passos, ser mais acessivel|
|RF13|Credencial de estacionamento : Autorização de estacionamento de idoso|OBS013| baixa|Ser mais acessivel |
|RF14|Credencial de estacionamento: Transtorno espectro autista|OBS014|baixa|Ser mais acessivel |
|RF15|Opção de pagamento para liberação do carro no patio|OBS015|baixa| Funcionalidade nova|
|RF16|Simulado de prova teorica na parte das autos escolas|OBS016|baixa|Funcionalidade nova|
|RF17|Ter uma parte sobre leilão|OBS017| baixa| Funcionalidade nova|
|RF18|Verificar se o veiculo tem autorização para transporte escolar|OBS018|media|Funcionalidade nova|
|RF19|O veiculo conseguir solicitar autorização para trnaspporte escolar|OBS019|baixa|Funcionalidade nova|

<font size="3"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>



## Requisitos Não-Funcionais

São as qualidades que o sistema deve ter (desempenho, usabilidade, segurança, etc.).
**A tabela 2** descreve as qualidades

<font size="3"><p style="text-align: center">**Tabela 2:** Requisitos Não-Funcionais.</p></font>

| Código | Requisito Não-Funcional                                         |Nome | Nível de Prioridade | Sugestão de Melhoria |
|--------|------------------------------------------------------------------|---------------------------|----------------------|-----------------------|
| RNF01  | Interface intuitiva e fácil de navegar                          |          OBS001                 | Alta                 |    Redesenhar o layout e menus com foco na hierarquia visual                   |
| RNF02  | Carregamento rápido das páginas                                 |         OBS002                  | Alta                 |                 Otimizar chamadas à API e melhorar tempo de resposta      |
| RNF03  | Acessibilidade para diferentes perfis de usuário                |        OBS003                   | Média                |              Adotar padrões de acessibilidade e contraste adequado         |
| RNF04  | Compatibilidade com diferentes dispositivos e sistemas          |        OBS004                   | Alta                 |               Melhorar testes de compatibilidade e otimização por modelo        |
| RNF05  | Segurança na exibição de dados pessoais                         |         OBS005                  | Alta                 |                	Adicionar autenticação de dois fatores para dados críticos       |

<font size="3"><p style="text-align: center">Fonte: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>



## Bibliografia

> 1. Aplicativo do DetranDF. Disponível em: Apple Store. Acesso em: 12 abr 2025.

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 21/04/2025 | Início da documentação | [Maria Eduarda](https://github.com/maaduh)     |[Luiz Bessa](https://github.com/lfelipebessa), [Giovana Barbosa](https://github.com/gio221) |
|  1.1   | 01/05/2025 | adicionando nomeclatura | [Giovana Barbosa](https://github.com/gio221) | [Maria Eduarda](https://github.com/maaduh)  |
|  1.2   | 03/05/2025 | adicionando sugestão de melhoria | [Maria Eduarda](https://github.com/maaduh)     | [Giovana Barbosa ](https://github.com/gio221) |

