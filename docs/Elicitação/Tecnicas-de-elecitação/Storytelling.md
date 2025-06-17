# Introdução
Outra tecnica que ultilizamos para elicitar requisitos, é aplicada com base nas personas

# Metodologia 
O storytelling é uma técnica que usa narrativas para facilitar a comunicação e a troca de experiências. No levantamento de requisitos, ele ajuda os usuários a contarem suas vivências com o sistema, revelando necessidades, dificuldades e expectativas. Essas histórias são repassadas à equipe do projeto, enriquecendo a compreensão sobre os usuários e o que eles realmente precisam.

# Participantes

| Nome | Data que foi realizada                                                               | 
|--------|--------------------------------------------------------------------------------------|
| [Giovana Barbosa](https://github.com/gio221)|23/05/2025|
|Lucas Ferreira(persona)|23/05/2025|
|Marina Souza(persona)|23/05/2025|
|Diego Martins(persona)|23/05/2025|
| Olavo Mendes(persona)|23/05/2025|

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

<a id="story-lucas"></a>

### Lucas Ferreira (Persona Primária)
Lucas Ferreira, 28 anos, é engenheiro civil e mora em Brasília. Sempre conectado, Lucas resolve tudo pelo celular e odeia perder tempo com burocracias.

Numa manhã de segunda-feira, Lucas recebeu uma notificação no app do Detran-DF informando que o licenciamento do seu carro estava prestes a vencer. Durante o café, ele abriu o aplicativo e, em poucos minutos, acessou a área de “Licenciamento”, onde o valor e as datas já estavam visíveis.

Com poucos cliques, ele gerou o boleto, pagou direto pelo banco integrado ao app e recebeu o comprovante automaticamente. Lucas também aproveitou para verificar se havia multas em aberto e ficou satisfeito em ver que o histórico estava zerado.

No fim, comentou com um amigo:
— “Cara, resolver isso em 10 minutos no app me salvou de uma manhã inteira perdida em fila no Detran.”

### Marina Souza (Persona Primária)
Marina Souza, 35 anos, é professora e mora em Ceilândia. Usa o celular com frequência, mas prefere fazer algumas coisas pessoalmente por achar os aplicativos confusos.

Numa sexta-feira à noite, Marina precisou verificar os pontos na sua CNH após ser parada em uma blitz educativa. Ao abrir o app do Detran-DF, ficou confusa com os nomes técnicos como “infrações”, “pontuação” e “renach”.

Ela tentou sozinha por alguns minutos, mas acabou fechando o app. No sábado de manhã, sua sobrinha a ajudou a acessar a seção correta. Juntas, descobriram que ela tinha apenas 3 pontos acumulados.

Marina desabafou com a sobrinha:
— “Se o app tivesse ícones maiores e uma linguagem mais simples, eu até usaria com mais frequência!”

<a id="story-diego"></a>

### Diego Martins (Persona Secundária)
Diego Martins, 20 anos, é motorista de aplicativo e depende do carro para o seu sustento. Ele vive em Taguatinga e sempre busca praticidade.

Em um dia normal de trabalho, Diego percebeu que sua CNH venceria no mês seguinte. Enquanto esperava uma corrida, ele abriu o app do Detran-DF para verificar como renovar. Achou rápido: a tela inicial já destacava a renovação de CNH como opção.

Diego seguiu os passos, agendou o exame médico em uma clínica credenciada e recebeu a confirmação por SMS. Ele ficou impressionado com a eficiência e ainda conseguiu escolher a data mais conveniente para seu dia de trabalho.

Comentou depois com um colega de profissão:
— “Antigamente, eu perdia um dia inteiro no Detran. Agora, com o app, resolvi tudo entre uma corrida e outra.”

### Gustavo Silva (Persona Primária)
Gustavo Silva, 67 anos, é aposentado e mora no Lago Norte. Gosta de dirigir, mas não tem tanta afinidade com smartphones.

Quando seu carro foi multado por estacionar em local proibido, Gustavo quis entender o motivo e como recorrer. Seu neto o ajudou a instalar o app do Detran-DF. Ao abrir, Gustavo achou as letras pequenas e ficou um pouco confuso com os ícones.

Com ajuda, ele acessou a infração, viu a imagem do flagrante e leu as orientações para recurso. O neto também o ajudou a preencher o formulário digital. No fim, Gustavo conseguiu protocolar a defesa sem sair de casa.

Comentou satisfeito:
— “É bom não precisar ir ao Detran. Só precisava mesmo de letras maiores e um botão escrito ‘Recorrer’, aí até eu usava sem ajuda.”

<a id="req-funcionais"></a>

## Requisitos Funcionais

| Identificador | Requisito                                                                 | 
|---------------|---------------------------------------------------------------------------|
|RF01 – Consulta de Licenciamento|O app deve permitir que o usuário consulte o status e a data de vencimento do licenciamento do veículo.|
|RF02 – Geração e pagamento de boletos|O app deve permitir a geração de boleto do licenciamento e possibilitar o pagamento através de bancos integrados.|
|RF03 – Consulta de multas e pontuação da CNH|O app deve exibir as infrações e a pontuação atual da CNH de forma clara e acessível.|
|RF04 – Agendamento de serviços|O app deve permitir que o usuário agende serviços como exames médicos para renovação da CNH.|
|RF05 – Notificações push|O app deve enviar lembretes sobre vencimentos de CNH, licenciamento, multas e outras obrigações.|
|RF06 – Visualização de infrações detalhadas| O app deve exibir detalhes de cada multa, incluindo imagem, local, data e hora da infração.|
|RF07 – Recurso de infrações|O app deve permitir iniciar o processo de recurso de multas com preenchimento de formulário online.|
|RF08 – Cadastro e gerenciamento de conta bancária (se necessário para pagamentos)|O app pode permitir a vinculação de contas ou carteiras digitais para facilitar pagamentos.|
|RF09 – Histórico do veículo e condutor|O app deve mostrar um histórico completo de serviços realizados, pontuação e pagamentos.|
|RF10 – Acesso por biometria ou reconhecimento facial|Para segurança e agilidade, o app deve permitir login usando biometria.|
|RF11 – Ajuda contextual e glossário|Deve haver explicações simples e acessíveis para termos técnicos como “RENACH”, “infrações”, “pontuação”.|
|RF12 – Suporte para atendimento humano (chat ou integração com WhatsApp)|O app deve oferecer canal direto de ajuda com atendente, caso o usuário não consiga resolver uma demanda.|

## Requisitos Não funcionais
<a id="req-nao-funcionais"></a>

| Identificador | Requisito                                                                                   |
|---------------|---------------------------------------------------------------------------------------------|
| RNF01-Usabilidade e acessibilidade         | O app deve ter fontes ajustáveis, ícones intuitivos e uma interface adaptada a usuários com pouca experiência digital (ex: Olavo e Marina). |
| RNF02 Tempo de resposta rápido        | Todas as funções devem carregar em até 2 segundos para manter a fluidez da navegação (importante para perfis como Diego). |
| RNF03    Compatibilidade com múltiplos dispositivos     | O app deve funcionar em smartphones Android e iOS, com suporte a versões antigas do sistema operacional. |
| RNF04   Privacidade e segurança de dados      | O app deve garantir criptografia de dados, autenticação segura e proteção de informações pessoais. |
| RNF05     Acessibilidade para idosos     | Deve incluir suporte a leitores de tela, contraste alto e botões grandes.                   |
| RNF06    Baixo consumo de dados e espaço      | O app deve ter tamanho reduzido e consumir poucos dados, especialmente em localidades com conexão limitada. |
| RNF07    Interface multilíngue (eventual)     | Deve haver possibilidade futura de incluir idiomas adicionais, como libras, para acessibilidade. |
| RNF08   Confiabilidade e tolerância a falhas      | O sistema deve garantir estabilidade e recuperação automática de falhas ou quedas de conexão. |
| RNF09    Feedback visual e sonoro     | O app deve dar retorno imediato sobre ações realizadas (ex: solicitação de recurso ou pagamento confirmado). |
| RNF10   Disponibilidade 24/7      | O sistema deve estar disponível para uso a qualquer momento, sem depender de horário comercial. |

## Bibliografia 
> 1. [Engenharia de requisitos](https://aprender3.unb.br/pluginfile.php/3096085/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf)

## Histórico de versões

| Versão |    Data    |                           Descrição                            |                    Autor                     |                   Revisor                    |
| :----: | :--------: | :------------------------------------------------------------: | :--------: | :--------: | 
|  1.0   | 01/05/2025 | Início da documentação, criação dos storytelling e elicitação dos requisitos| [Giovana Barbosa ](https://github.com/gio221) | [Gabriel Dantas](https://github.com/gbevi)|
|  1.1  | 07/06/2025 | adição de anchors nas tabelas | [Gabriel Mendes](https://github.com/gbevi)       |      [Giovana Barbosa ](https://github.com/gio221)                                      | 
