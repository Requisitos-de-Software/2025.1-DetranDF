# Técnica de Elicitação: Brainstorming

## Introdução
<p align="justify">
O Brainstorming é uma técnica colaborativa utilizada para a geração de ideias em grupo, muito comum nas fases iniciais de desenvolvimento de sistemas. Ao reunir diversos participantes com perspectivas distintas, busca-se levantar o maior número possível de necessidades, desejos e expectativas dos usuários sobre um produto ou serviço. Para o projeto de avaliação do aplicativo DETRAN-DF, a técnica de Brainstorming foi utilizada como um dos métodos de elicitação de requisitos, complementando a observação direta. Esta técnica nos ajudou a entender como o grupo enxerga os problemas e oportunidades de melhoria no uso de um possível sistema, antes de partir para propostas de soluções.
</p>

## Objetivo
<p align="justify">
Coletar percepções e ideias dos participantes acerca de um futuro aplicativo do DETRAN-DF, de forma a levantar necessidades, expectativas e possíveis melhorias no sistema, com base em suas experiências com serviços do DETRAN e sugestões de funcionalidades úteis. A técnica foi registrada e analisada para identificação de requisitos funcionais e não-funcionais.
</p>

## Metodologia
<p align="justify">
A sessão de Brainstorming foi realizada na plataforma Microsoft Teams, com a participação de 5 pessoas. Um dos membros atuou como moderador da sessão, responsável por manter o foco da discussão e guiar a conversa com perguntas estratégicas. Outro membro atuou como secretário, registrando todas as ideias sugeridas pelos participantes. Embora o número ideal de participantes seja entre 8 a 12 pessoas, foi possível obter bons resultados com os presentes, considerando a dificuldade de reunir voluntários em meio à rotina. As ideias levantadas foram posteriormente organizadas e categorizadas.
</p>

## Participantes da sessão
<font size="3"><p style="text-align: center">**Tabela 1: Participantes da Sessão de Brainstorming DETRAN-DF**</p></font>

| Nome                 | Função na Sessão     |
|----------------------|----------------------|
| <span style="background-color:#d0f0c0">Luiz Felipe Bessa</span> | Moderador (Membro do grupo) |
| <span style="background-color:#d0f0c0">Eric Akio</span>         | Secretário (Membro do grupo) |
| Giovanni Dornelas    | Cliente convidado    |
| Eduardo Waski        | Cliente convidado    |
| Jose Gabriel         | Cliente convidado    |

## Registro da Sessão
<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/DfFPVr6Fm6g" 
  title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Principais Perguntas da Sessão de Brainstorming

<p align="justify">
Durante a sessão de Brainstorming, o moderador guiou os participantes com perguntas específicas, focadas em imaginar um aplicativo eficiente, intuitivo e útil para o DETRAN-DF. As principais perguntas feitas foram:
</p>

<ul>
  <li>Quais funcionalidades vocês acham que seriam essenciais em um aplicativo do DETRAN-DF?</li>
  <li>Que tipos de serviços vocês gostariam de resolver diretamente pelo celular sem precisar ir presencialmente ao DETRAN?</li>
  <li>Que dificuldades vocês enfrentaram no passado ao lidar com documentação de veículos ou CNH? Como um aplicativo poderia ajudar?</li>
  <li>Vocês acham importante que o aplicativo envie notificações? Sobre quais temas?</li>
  <li>Quais medidas de segurança seriam importantes para confiar em um app governamental como esse?</li>
  <li>Quais recursos de acessibilidade seriam importantes para tornar o aplicativo mais inclusivo?</li>
  <li>Que tipo de suporte ou atendimento vocês gostariam de ter dentro do app?</li>
  <li>Se pudessem inventar qualquer funcionalidade nova, o que vocês sugeririam para esse aplicativo?</li>
  <li>O que poderia tornar o aplicativo mais fácil de usar, mesmo para pessoas que têm pouca familiaridade com tecnologia?</li>
</ul>

---

## Resumo e Conclusões da Sessão de Brainstorming

<p align="justify">
A sessão de Brainstorming resultou na identificação de diversos requisitos funcionais e não funcionais importantes para o futuro aplicativo do DETRAN-DF. As principais conclusões foram:
</p>

<ul>
  <li><b>Necessidade de centralização de serviços:</b> Os participantes apontaram a importância de reunir em um único app a consulta de multas, agendamento de serviços, acompanhamento de processos, acesso à CNH e documentação do veículo.</li>
  <li><b>Importância das notificações automáticas:</b> Foi destacado que o aplicativo deve notificar os usuários sobre prazos, vencimentos e descontos em multas, melhorando a organização pessoal dos motoristas.</li>
  <li><b>Preocupação com a segurança dos dados:</b> Os participantes reforçaram a necessidade de protocolos de segurança robustos, especialmente considerando que o app lidaria com informações sensíveis.</li>
  <li><b>Acessibilidade como prioridade:</b> Foram sugeridos recursos como fonte ampliada, modo noturno, leitor de tela e assistente por voz, para garantir que o app seja acessível para todos os públicos.</li>
  <li><b>Facilidade de uso e simplicidade:</b> Houve consenso sobre a necessidade de uma interface intuitiva, com foco em usabilidade, especialmente para públicos que não têm familiaridade com tecnologia.</li>
  <li><b>Inovação e apoio educativo:</b> Além dos serviços tradicionais, surgiram ideias inovadoras, como área educacional sobre processos do DETRAN, guia para provas da autoescola, avaliações de autoescolas licenciadas e integração com sistemas já existentes como CNH Digital e Gov.br.</li>
  <li><b>Atendimento humanizado:</b> Sugeriu-se a criação de um atendimento online direto com servidores do DETRAN, via chat ou videoconferência, para suporte em dúvidas mais complexas.</li>
</ul>

<p align="justify">
Apesar do número de participantes ser menor que o ideal (5 participantes ao invés de 8-12), a qualidade das ideias e a diversidade de sugestões superaram as expectativas, proporcionando uma base rica para a definição dos requisitos do projeto.
</p>

## Requisitos Funcionais
<font size="3"><p style="text-align: center">**Tabela 2:** Requisitos funcionais elicitados através do Brainstorm.</p></font>

| ID         | Requisito Funcional                                                                 |
|------------|--------------------------------------------------------------------------------------|
| BS01 (RF01)| Visualizar pontuação da carteira                                                    |
| BS02 (RF02)| Trocar a PPD para CNH definitiva pelo app                                           |
| BS03 (RF03)| Sistema de pagamento de taxas e débitos                                             |
| BS04 (RF04)| Aviso automático em caso de roubo/recuperação do carro                              |
| BS05 (RF05)| Consulta de CNH, documentos e multas                                                |
| BS06 (RF06)| Notificação de multas e prazos com desconto                                         |
| BS07 (RF07)| Agendamento online para provas teóricas e práticas                                  |
| BS08 (RF08)| Área para autoescolas licenciadas com avaliações, comentários e localização         |
| BS09 (RF09)| Guia de documentos necessários para cada tipo de serviço                            |
| BS10 (RF10)| Chat com IA para tirar dúvidas                                                      |
| BS11 (RF11)| Integração com CNH Digital e Gov.br                                                |
| BS12 (RF12)| Atendimento ao vivo com servidor do DETRAN via chat/vídeo                          |

## Requisitos Não Funcionais
<font size="3"><p style="text-align: center">**Tabela 3:** Requisitos não-funcionais elicitados através do Brainstorm.</p></font>

| ID          | Requisito Não-Funcional                                                                      |
|-------------|-----------------------------------------------------------------------------------------------|
| BS13 (RNF01)| Interface intuitiva e fácil de usar                                                           |
| BS14 (RNF02)| Compatibilidade com dispositivos móveis                                                       |
| BS15 (RNF03)| Alta segurança no tratamento de dados (confiança por ser app do governo)                     |
| BS16 (RNF04)| Área educacional sobre processos do DETRAN (explicações, vídeos, etc.)                        |
| BS17 (RNF05)| Acessibilidade: fonte grande, alto contraste, modo noturno                                    |
| BS18 (RNF06)| Leitor de tela e assistente por voz para pessoas cegas                                        |
| BS19 (RNF07)| Sistema de avaliação com estrelas baseado em comprovante de uso real (ex-alunos)             |
| BS20 (RNF08)| Propaganda mais efetiva para aumentar o conhecimento da existência do app                     |
| BS21 (RNF09)| Layout com foco em simplicidade e legibilidade                                                |

## Lista de Verificação da Técnica de Brainstorming

<font size="3"><p style="text-align: center">**Tabela 4:** Verificação da Aplicação da Técnica de Brainstorming.</p></font>

| ID | Critérios                                                                                       | Sim/Não | Print                                                                                                           |
|----|--------------------------------------------------------------------------------------------------|---------|-----------------------------------------------------------------------------------------------------------------|
| 1  | Resultou em uma lista priorizada de necessidades e desejos dos usuários?                        | Sim     | [Print](https://drive.google.com/file/d/1BuyXt2ezq9XBqEjKBnHJdMd0UAuK23up/view?usp=sharing)                     |
| 2  | Existe uma ou mais perguntas que sumarizam o objetivo de entender o que os usuários precisam?   | Sim     | [Print](https://drive.google.com/file/d/1INYFZEu25fTqrJAK4wDCHLEnhT0v7ED_/view?usp=sharing)                     |
| 3  | A sessão teve um moderador?                                                                      | Sim     | [Print](https://drive.google.com/file/d/1-QP0-a0z2e8U7cYLxz3fT518g09_1bQs/view?usp=sharing)                     |
| 4  | A sessão teve um secretário?                                                                      | Sim     | [Print](https://drive.google.com/file/d/1-QP0-a0z2e8U7cYLxz3fT518g09_1bQs/view?usp=sharing)                 
| 5  | Os participantes foram informados sobre o objetivo e procedimento da atividade no início?       | Sim     | [Print](https://drive.google.com/file/d/1Haj1240SuxqUpjPsE5SveiLIZAvHxVda/view?usp=sharing)                     |
| 6  | A sessão de Brainstorming gerou uma tabela/lista com os desejos sumarizados dos usuários?       | Sim     | [Print](https://drive.google.com/file/d/1Lm-TkN5EEnZt45q09bU2IwItP-LE6Bsr/view?usp=sharing)                     |
| 7  | A sessão teve duração aproximada de uma hora?                                                    | Sim     | [Gravação](https://www.youtube.com/embed/DfFPVr6Fm6g) *(pode ser comprovado pela gravação)*                                                                 |
| 8  | A sessão contou com aproximadamente 8 a 12 participantes?                                        | Não     | *(Justificativa: difícil conseguir voluntários para um app ainda hipotético; em um caso real seria diferente)* |

## Bibliografia

> 1. Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/3096073/mod_resource/content/2/ihc-ux-%20Personas.pdf).  
> 2. Aplicativo do DetranDF. Disponível em: Apple Store. Acesso em: 12 abr. 2025.

## Histórico de versão

| Versão |    Data    |              Descrição               |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :----------------------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 23/04/2025 | Criação da estrutura da página de Brainstorming | [Luiz Felipe Bessa](https://github.com/)       |                                            |
|  1.1   | 25/04/2025 | Preenchimento do dados após a Reunião | [Luiz Felipe Bessa](https://github.com/)       |                                            |