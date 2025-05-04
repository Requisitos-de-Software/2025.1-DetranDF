## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
O método MoSCoW é uma técnica de priorização usada para ajudar equipes e partes interessadas a definirem quais requisitos ou funcionalidades são mais importantes em um projeto. A sigla representa quatro categorias: Must (deve ter), Should (deveria ter), Could (poderia ter) e Won’t (não terá por enquanto). Essa abordagem facilita a tomada de decisões ao estabelecer um consenso sobre o que é essencial para a entrega mínima viável do produto e o que pode ser adicionado posteriormente. É amplamente utilizado em metodologias ágeis, pois permite adaptar o escopo do projeto de forma estratégica, de acordo com o tempo, orçamento e recursos disponíveis. Ao aplicar o MoSCoW, torna-se mais fácil focar no que realmente agrega valor ao usuário final, ao mesmo tempo em que se mantém a flexibilidade para ajustes conforme o projeto evolui.
</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
Para realizar a priorização dos requisitos, utilizou-se como base os requisitos funcionais e não funcionais previamente elicitados.
</p>
<p style="text-indent: 20px; text-align: justify">
A classificação foi feita com base na técnica de priorização MoSCoW, que permite categorizar os requisitos conforme sua importância para o produto final. A decisão sobre a prioridade de cada item considerou o contexto das personas e os storytellings desenvolvidos durante o processo de levantamento de requisitos. 
</p>
<p style="text-indent: 20px; text-align: justify">
Vale ressaltar que, por se tratar de um exercício teórico, não houve a participação direta de usuários reais; portanto, as escolhas refletem uma análise projetada a partir de perfis e cenários hipotéticos.
</p>

### 3.1 Must

<div style="text-align: center">
<p>Tabela 1: Tabela Must</p>
</div>

| Identificador | Requisito | Justificativa |
|:-------------:|:----------|:-------------|
| RF01 | Permitir consulta de multas e débitos do veículo | Essencial para que o usuário tenha controle sobre as multas e débitos, facilitando o gerenciamento de suas obrigações legais. |
| RF02 | Realizar agendamento de serviços (vistoria, CNH, etc.) | Funcionalidade chave para garantir que o usuário consiga realizar os serviços essenciais diretamente pelo app. |
| RF03 | Exibir informações da CNH e pontuação | Crucial para o usuário acompanhar sua habilitação e evitar surpresas relacionadas à pontuação. |
| RF08 | Sistema de pagamento de taxas e débitos | Permite que o usuário realize pagamentos diretamente no app, evitando deslocamentos e facilitando a vida do usuário. |
| RF10 | Consulta de CNH, documentos e multas | Necessário para acesso rápido aos documentos e informações essenciais do motorista. |
| RF17 | Exibir status do licenciamento e do IPVA do veículo | Garantir que o usuário tenha acesso aos status dos documentos e impostos de seu veículo. |
| RF19 | Consultar a pontuação da CNH diretamente no aplicativo | Funcionalidade importante para o usuário controlar sua pontuação e evitar penalidades. |
| RF21 | Permitir acompanhamento de processos | Permite que o usuário acompanhe a evolução de processos relacionados ao seu veículo ou habilitação. |
| RNF01 | Interface intuitiva e fácil de navegar | A usabilidade é fundamental para garantir que todos os perfis de usuários consigam utilizar o app facilmente. |
| RNF02 | Compatibilidade com diferentes dispositivos e sistemas | Garante que o app seja acessível em uma ampla gama de dispositivos, atendendo a uma maior base de usuários. |
| RNF03 | Alta segurança no tratamento de dados pessoais e veiculares | Proteger os dados sensíveis dos usuários é fundamental para a confiabilidade e conformidade com regulamentos. |
| RNF05 | Acessibilidade (fonte grande, contraste, modo noturno) | Fundamental para garantir a inclusão de todos os perfis de usuários, especialmente aqueles com deficiências visuais. |
| RNF10 | Carregamento rápido das páginas | Essencial para proporcionar uma boa experiência ao usuário, especialmente em ambientes com conexões de internet lentas. |

<div style="text-align: center">
<p>Fonte: Autoria própria</p>
</div>

### 3.2 Should

<div style="text-align: center">
<p>Tabela 2: Tabela Should</p>
</div>

| Identificador | Requisito | Justificativa |
|:-------------:|:----------|:-------------|
| RF05 | Exibir notificações de prazos e documentos vencidos | Auxilia o usuário a manter o controle de prazos importantes, evitando multas e outros transtornos. |
| RF06 | Realizar transferência de documento do veículo | Facilita o processo de atualização de documentos diretamente no aplicativo, agilizando o atendimento. |
| RF07 | Trocar a PPD para CNH definitiva pelo app | Melhora a experiência do usuário permitindo uma transição mais prática para a CNH definitiva. |
| RF11 | Agendamento online para provas teóricas e práticas | Funcionalidade importante para que o usuário consiga agendar provas de forma rápida e sem burocracia. |
| RF13 | Guia de documentos necessários para cada tipo de serviço | Garante que o usuário saiba exatamente o que precisa para cada serviço, economizando tempo e esforço. |
| RF15 | Integração com CNH Digital e Gov.br | Facilita o acesso a documentos digitais e aumenta a praticidade para o usuário. |
| RF18 | Gerar segunda via da CNH e CRLV digitalmente | A possibilidade de gerar documentos digitais traz comodidade e evita necessidade de deslocamentos. |
| RNF04 | Área educacional com explicações e vídeos | Ajuda os usuários a entenderem melhor o funcionamento do aplicativo e dos processos envolvidos. |
| RNF09 | Layout com foco em simplicidade e legibilidade | Essencial para que o app seja acessível a todos, especialmente usuários com dificuldades visuais ou cognitivas. |
| RNF11 | Acessibilidade para diferentes perfis de usuários | Permite que o aplicativo atenda a um público mais amplo, considerando necessidades especiais. |
| RNF12 | Explicações acessíveis sobre siglas (ex: RENAVAM) | Fundamental para facilitar o entendimento do usuário sobre termos técnicos ou siglas, garantindo uma melhor experiência. |

<div style="text-align: center">
<p>Fonte: Autoria própria</p>
</div>

### 3.3 Could

<div style="text-align: center">
<p>Tabela 3: Tabela Could</p>
</div>

| Identificador | Requisito | Justificativa |
|:-------------:|:----------|:-------------|
| RF04 | Realizar a transferência da autuação de infração | A funcionalidade facilita o processo para o usuário, mas não é essencial para o funcionamento básico do app. |
| RF09 | Aviso automático em caso de roubo/recuperação do carro | Embora seja útil, não é um requisito imediato para a maioria dos usuários, mas pode agregar valor. |
| RF12 | Área para autoescolas com avaliações, comentários e localização | Funcionalidade interessante para usuários que estão em busca de autoescolas, mas não essencial para todos. |
| RF14 | Chat com IA para tirar dúvidas | Uma ferramenta útil, mas não crítica para a funcionalidade principal do aplicativo. |
| RF22 | Exibir notificações de prazos e documentos vencidos (repetido do RF05) | Repetição que poderia ser evitada, mas ainda assim uma funcionalidade desejável. |
| RNF06 | Leitor de tela e assistente por voz para pessoas cegas | Funcionalidade inclusiva, embora não seja um requisito imediato para todos os usuários. |
| RNF07 | Sistema de avaliação com base em uso real (ex-alunos) | Útil para melhorar a escolha de serviços, mas não essencial para a operação do aplicativo. |
| RNF08 | Propaganda efetiva para promover o app | Estratégia de marketing que pode agregar valor ao app, mas não essencial para seu funcionamento. |

<div style="text-align: center">
<p>Fonte: Autoria própria</p>
</div>

### 3.4 Won’t

<div style="text-align: center">
<p>Tabela 4: Tabela Won’t</p>
</div>

| Identificador | Requisito | Justificativa |
|:-------------:|:----------|:-------------|
| RF16 | Atendimento ao vivo com servidor do DETRAN via chat/vídeo | Embora útil, este requisito é considerado fora do escopo inicial devido ao custo e à complexidade operacional que envolvem a implementação do atendimento ao vivo. |

<div style="text-align: center">
<p>Fonte: Autoria própria</p>
</div>

## 4. Referências

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 50 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 3 maio. 2025.

## 5. Versionamento

| Versão | Data    | Autor                         | Alterações                                                           |         Revisor         |
|:------:| --- | ----------------------------- | -------------------------------------------------------------------- |:-----------------------:|
|  1.0   |  03/005/2025   | [Gabriel Dantas](https://github.com/gbevi) | Confecção da primeira versão da técnica de priorização MosCoW                          | Pedro Camilo (https://github.com/PedrooCamilo)  |
