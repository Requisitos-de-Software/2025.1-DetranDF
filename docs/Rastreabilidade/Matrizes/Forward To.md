# Introdução
A rastreabilidade forward-to (para frente) diz respeito à conexão entre os documentos produzidos durante a elicitação — como os provenientes do plano de negócios — e os requisitos do sistema. Ou seja, ela estabelece um vínculo que começa no contexto do negócio e segue até a definição dos requisitos funcionais e não funcionais.

# Legenda
A legenda para cada sigla é:

- RF - Requisito Funcional nº
- RNF - Requisito Não Funcional nº
- RFB - Requisito Funcional de Brainstorming nº
- RFI - Requisito Funcional de Instrospecção nº
- RFO - Requisito Funcional de Observação nº
- RFG - Requisito Funcional de Glossário nº
- RFS - Requisito Funcional de Storytelling nº

### Requisitos Funcionais

<font size="3" style="text-align: center"><p>**Tabela 1 -** Matriz de requisitos funcionais.</p></font>

| Requisito  | Descrição | Implementado |      Elicitação      |   
| :--------: | :-------: | :----------: | :----: | 
| RF01      | Permitir consulta de multas e débitos do veículo          | SIM          | [RFI01 / RFO001](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-funcionais) [RFB06](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)      | 
| RF02      | Realizar agendamento de serviços (vistoria, CNH, etc.)    | SIM          | [RFI02 / RFO002](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)        | 
| RF03      | Exibir informações da CNH e pontuação                     | SIM          |  [RFI03 / RFB01 / RFO003](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais) |
| RF04      | Realizar a transferência da autuação de infração          | SIM          |  [RFI04](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)                 | 
| RF05|   Exibir notificações de prazos e documentos vencidos    |   SIM    |   [RFI05](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-funcionais) [RFB06](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais) | 
| RF06| Realizar transferência de documento do veículo|SIM    | [RFI06](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-funcionais)|
| RF07|Trocar a PPD para CNH definitiva pelo app|SIM    | [RFB02](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF08|Sistema de pagamento de taxas e débitos|SIM    |  [RFB03](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF09|Aviso automático em caso de roubo/recuperação do carro| Não|[RFB04](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF10| Consulta de CNH, documentos e multas|SIM    |  [RFB05](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF11| Agendamento online para provas teóricas e práticas | Não   |  [RFB07](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF12| Área para autoescolas com avaliações, comentários e localização	|Não     |  [RFB08](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF13| Guia de documentos necessários para cada tipo de serviço| Não    |  [RFB09](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF14| Chat com IA para tirar dúvidas | Não    |  [RFB10](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF15| Integração com CNH Digital e Gov.br | SIM    |  [RFB11](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF16| Atendimento ao vivo com servidor do DETRAN via chat/vídeo | Não    | [RFB12](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-funcionais)|
| RF17 | Exibir status do licenciamento e do IPVA do veículo | SIM | [RFG03](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario/#req-funcionais) | 
| RF18 | Gerar segunda via da CNH e CRLV digitalmente | SIM | [RFG04](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario/#req-funcionais) | 
| RF19 | Deve ser possível consultar a pontuação da CNH diretamente no aplicativo | SIM | [RFG01](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario/#req-funcionais) |
| RF20 | O aplicativo deve permitir o agendamento de serviços presenciais | SIM |  [RFG02](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario/#req-funcionais) | 
| RF21 | Permitir acompanhamento de processos | SIM | [RFO004](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais) |
| RF22 | Exibir notificações de prazos e documentos vencidos | SIM | [RFO005](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais) |
| RF23 | Consulta do status do licenciamento em tempo real                        | SIM          |  [RFSO01](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)            |
| RF24 | Geração de boleto e pagamento integrado no app                           | SIM          |   [RFSO02](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)             |
| RF25 | Consulta e detalhamento de infrações com imagens                         | NÃO          |  [RFSO03](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)              | 
| RF26 | Iniciar e acompanhar recurso de multa pelo app                           | SIM          |   [RFSO04](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)              | 
| RF27 | Agendamento de exame médico para CNH                                     | NÃO          |  [RFSO05](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)              | 
| RF28 | Notificações de vencimento da CNH, multas e licenciamento                | NÃO          |  [RFSO06](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)              |
| RF29 | Explicações simples sobre termos técnicos     | NÃO          |  [RFSO07](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)              |
| RF30 | Canal de atendimento humano     | NÃO          | [RFSO08](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)              |
| RF31 | Solicitar reposição de placa Mercosul     | SIM         |  [RFO006](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação/)              | 
| RF32 | Conversão de placa para Mercosul     | SIM         |  [RFO007](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação/)              | 
| RF33 | Histórico de infração do condutor     | SIM         |  [RFO008](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação/)              | 
| RF34 | Histórico de infração do veículo     | SIM         |  [RFO009](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação/)              | 
| RF35 | Conversão de autuação em penalidade | SIM |  [RFO010](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais) |
| RF36 | Protocolo-e, nova solicitação | SIM |  [RFO011](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais) |
| RF37 | Protocolo-e, acompanhar solicitação | SIM | [RFO012](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais) | 
| RF38 | Solicitar credencial de estacionamento para idoso | SIM |[RFO013](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais) |
| RF39 | Solicitar credencial de estacionamento para pessoas com TEA | SIM | [RFO014](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais) |
| RF40 | Pagamento de débitos para liberação de veículo | NÃO |[RFO015](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais) | 
| RF41 | Simulado de prova teórica | NÃO |  [RFO016](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais) | 
| RF42      | Disponibilizar seção de leilões de veículos               | NÃO          |  [RFO017](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-funcionais)               | 
| RF43      | Verificar autorização de veículo p/ transporte escolar    | NÃO          |  [RFO018](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-funcionais)               | 
| RF44      | Solicitar autorização de transporte escolar pelo app      | NÃO          |  [RFO019](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-funcionais)              |

### Requisitos não funcionais

<font size="3" style="text-align: center"><p>**Tabela 4 -** Matriz para os Requisitos Não funcionais.</p></font>

| Requisito  | Descrição | Implementado |      Elicitação      |   
| :--------: | :-------: | :----------: | :----: | 
| RNF01| Interface intuitiva e fácil de navegar|SIM    | [IS017](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-nao-funcionais) [BS13](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-nao-funcionais)|
| RNF02|Compatibilidade com diferentes dispositivos e sistemas|SIM    |  [IS010](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-nao-funcionais) [BS15](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-nao-funcionais)|
| RNF03| Alta segurança no tratamento de dados pessoais e veiculares|SIM    |  [IS010](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-nao-funcionais) [BS16](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-nao-funcionais)[GLO06](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario/#glo06)|
| RNF04| Área educacional com explicações e vídeos|Não  |  [BS17](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#req-nao-funcionais)|
| RNF05 | Acessibilidade (fonte grande, contraste, modo noturno) | Não |  [BS17](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#bs17) | 
| RNF06 | Leitor de tela e assistente por voz para pessoas cegas | Não | [BS18](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#bs18) | 
| RNF07 | Sistema de avaliação com base em uso real (ex-alunos) | Não | [BS19](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#bs19) | 
| RNF08 | Propaganda efetiva para promover o app | NÃO |  [BS20](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#bs20) | 
| RNF09 | Layout com foco em simplicidade e legibilidade | NÃO |  [BS21](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#bs21) |  
| RNF10 | Carregamento rápido das páginas | NÃO | [IS08](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-nao-funcionais) |  
| RNF11     | Acessibilidade para diferentes perfis de usuários                     | NÃO          | [IS09](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-nao-funcionais)           | 
| RNF12     | Explicações acessíveis sobre siglas (ex: RENAVAM)                    | NÃO          |  [GL05](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario)         | 
| RNF13     | Texto com fontes ajustáveis e botões grandes                          | NÃO          |  [STO07](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)         |
| RNF14     | Interface adaptada para idosos e iniciantes                          | NÃO          |  [STO-RNF05](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)         | 
| RNF15     | Aplicativo leve e com baixo consumo de dados                          | SIM          |  [STO-RNF06](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)         | 
| RNF16     | Tempo de resposta rápido                         | NÃO          |  [STO-RNF02](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling)         | 
| RNF17 | Feedback visual e sonoro nas interações do usuário | NÃO |  [STO2.09](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling/#req-nao-funcionais) | 
| RNF18 | Disponibilidade do sistema 24/7 | SIM |  [STO2.10](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling/#req-nao-funcionais) | 
| RNF19 | Confiabilidade: recuperação de falhas e continuidade da navegação | NÃO |[STO2.08](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling/#req-nao-funcionais) | 
| RNF20     | Interface com poucos elementos por tela (leitura fácil)       | SIM         | [STO2.08](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling/#req-nao-funcionais)      |

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 12/06/2025 | criação do documento |  [Giovana Barbosa](https://github.com/gio221)   |[Gabriel Mendes](https://github.com/gbevi)   |
|  1.0   | 12/06/2025 | Peguei a matriz geral e montei o foward to |  [Giovana Barbosa](https://github.com/gio221)   |[Gabriel Mendes](https://github.com/gbevi)   |