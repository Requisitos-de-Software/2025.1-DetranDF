# Introdução
Este documento tem como finalidade verificar todos os resultados elicitados , ultilizando várias técnicas de elicitação

# Objetivo
O objetivo desse documento é apresentar os requisitos levantados através das técnicas de elicitação de requisitos

# Metodologia
Para alcançar os objetivos propostos, foram aplicadas as seguintes técnicas de elicitação de requisitos:

- Brainstorming
- Glossário
- Introspecção
- Observação

<a id="req-funcionais"></a>

# Requisitos Funcionais
| Código | Requisito Funcional                                                                 | Fonte (ID Original)         |
|--------|--------------------------------------------------------------------------------------|-----------------------------|
| RF01   | Permitir consulta de multas e débitos do veículo                                    | IS01, OBS001                        |
| RF02   | Realizar agendamento de serviços (vistoria, CNH, etc.)                              | IS02 ,OBS002                        |
| RF03   | Exibir informações da CNH e pontuação                                                | IS03, BS01,OBS003                 |
| RF04   | Realizar a transferência da autuação de infração                                    | IS04                        |
| RF05   | Exibir notificações de prazos e documentos vencidos                                 | IS05, BS06                  |
| RF06   | Realizar transferência de documento do veículo                                       | IS06                        |
| RF07   | Trocar a PPD para CNH definitiva pelo app                                            | BS02                        |
| RF08   | Sistema de pagamento de taxas e débitos                                              | BS03                        |
| RF09   | Aviso automático em caso de roubo/recuperação do carro                              | BS04                        |
| RF10   | Consulta de CNH, documentos e multas                                                 | BS05                        |
| RF11   | Agendamento online para provas teóricas e práticas                                   | BS07                        |
| RF12   | Opção para adicionar quilometragem do seu carro                    | BS08                        |
| RF13   | Guia de documentos necessários para cada tipo de serviço                            | BS09                        |
| RF14   | Chat com IA para tirar dúvidas                                                       | BS10                        |
| RF15   | Integração com CNH Digital e Gov.br                                                  | BS11                        |
| RF16   | Atendimento ao vivo com servidor do DETRAN via chat/vídeo                           | BS12                        |
| RF17   | Exibir status do licenciamento e do IPVA do veículo                                 | GLO03                       |
| RF18   | Gerar segunda via da CNH e CRLV digitalmente                                         | GLO04                       |
| RF19   | Deve ser possível consultar a pontuação da CNH diretamente no aplicativo.                                                 |GLO01                         |
| RF20   | O aplicativo deve permitir o agendamento de serviços presenciais.                                        | GLO02                        |
| RF21   | Permitir acompanhamento de processos                                            | OBS004                        |
| RF22   | Exibir notificações de prazos e documentos vencidos                                            | OBS005                        |
| RF23   | Permitir consulta do status do licenciamento em tempo real                      | Storytelling - Lucas        |
| RF24   | Permitir geração de boleto e pagamento integrado no app                         | Storytelling - Lucas        |
| RF25   | Permitir consulta e detalhamento de infrações com imagens                       | Storytelling - Marina, Olavo|
| RF26   | Iniciar e acompanhar recurso de multa pelo app                                  | Storytelling - Olavo        |
| RF27   | Permitir agendamento de exame médico para CNH                                   | Storytelling - Diego        |
| RF28   | Enviar notificações de vencimento da CNH, multas e licenciamento                | Storytelling - Diego        |
| RF29   | Oferecer explicações simples sobre termos técnicos (ex: infração, RENACH)       | STO07       |
| RF30   | Oferecer canal de atendimento humano (chat ou WhatsApp)                         | STO08|
|RF31|Reposição de placa Mercosul   |OBS006  |
|RF32|Conversão de placa Mercosul   |OBS007  |
|RF33|Histórico de infração do condutor|OBS008|
|RF34|Histórico de infração do veículo|OBS009|
|RF35|Converção de autuação em penalidade|OBS010|
|RF36|Protocolo-e, nova solicitação|OBS011|
|RF37|Protocolo-e, acompanhar solicitação|OBS012|
|RF38|Credencial de estacionamento : Autorização de estacionamento de idoso|OBS013| 
|RF39|Credencial de estacionamento: Transtorno espectro autista|OBS014|
|RF40|Opção de pagamento para liberação do carro no patio|OBS015|
|RF41|Simulado de prova teorica na parte das autos escolas|OBS016|
|RF42|Ter uma parte sobre leilão|OBS017|
|RF43|Verificar se o veiculo tem autorização para transporte escolar|OBS018|
|RF44|O veiculo conseguir solicitar autorização para trnaspporte escolar|OBS019|



<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>
<a id="req-nao-funcionais"></a>

# Requisitos Não funcionais 
| Código | Requisito Não-Funcional                                                             | Fonte (ID Original)         |
|--------|--------------------------------------------------------------------------------------|-----------------------------|
| RNF01  | Interface intuitiva e fácil de navegar                                               | BS13, IS07                  |
| RNF02  | Compatibilidade com diferentes dispositivos e sistemas                               | BS14, IS10                  |
| RNF03  | Alta segurança no tratamento de dados pessoais e veiculares                         | BS15, IS11, GLO06           |
| RNF04  | Área educacional com explicações e vídeos                                            | BS16                        |
| RNF05  | Acessibilidade (fonte grande, contraste, modo noturno)                              | BS17                        |
| RNF06  | Leitor de tela e assistente por voz para pessoas cegas                              | BS18                        |
| RNF07  | Sistema de avaliação com base em uso real (ex-alunos)                               | BS19                        |
| RNF08  | Propaganda efetiva para promover o app                                               | BS20                        |
| RNF09  | Layout com foco em simplicidade e legibilidade                                       | BS21                        |
| RNF10  | Carregamento rápido das páginas                                                      | IS08                        |
| RNF11  | Acessibilidade para diferentes perfis de usuários                                    | IS09                        |
| RNF12  | Explicações acessíveis sobre siglas (ex: RENAVAM)                                   | GLO05                       |
| RNF13  | Texto com fontes ajustáveis e botões grandes                                   | Storytelling - Olavo        |
| RNF14  | Interface adaptada para idosos e iniciantes                                    | Storytelling - Olavo, Marina|
| RNF15  | Aplicativo leve e com baixo consumo de dados                                   | Storytelling - Diego        |
| RNF16  | Tempo de resposta inferior a 2 segundos                                        | Storytelling - Lucas        |
| RNF17  | Feedback visual e sonoro nas interações do usuário                             | Storytelling - Diego, Olavo |
| RNF18  | Disponibilidade do sistema 24/7                                                 | Storytelling - Lucas        |
| RNF19  | Confiabilidade: recuperação de falhas e continuidade da navegação              | Storytelling - Diego        |
| RNF20  | Interface com poucos elementos por tela para facilitar leitura                 | Storytelling - Olavo        |


<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

## Bibliografia

> 1. Aplicativo do DetranDF. Disponível em: Play Store. Acesso em: 22 abr 2025.

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 01/05/2025 | requisitos funcionais e não funcionais |  [Giovana Barbosa](https://github.com/gio221)   | [Gabriel Dantas](https://github.com/gbevi) |
|  1.1  | 07/06/2025 | adição de anchors nas tabelas | [Gabriel Mendes](https://github.com/gbevi)       |                           [Giovana Barbosa ](https://github.com/gio221)                 | 