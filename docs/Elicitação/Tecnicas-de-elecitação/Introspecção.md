# Introdução

<p align="justify">
A técnica de introspecção, na elicitação de requisitos, envolve o analista se colocar no lugar do usuário para imaginar como ele usaria o sistema e quais funcionalidades seriam importantes. No caso do aplicativo do Detran-DF, essa técnica pode ajudar a pensar em recursos como agendamento de serviços, consulta de multas ou emissão de documentos, mesmo antes de conversar diretamente com os usuários. Em outras palavras, é um exercício de empatia que serve para interpretar um requisito possível do sistema.
</p>

# Objetivo

<p align="justify">
Identificar aspectos relacionados à usabilidade, navegação e desempenho do aplicativo DETRAN-DF por meio da técnica de elicitação por introspecção, analisando o comportamento possível dos usuários durante o uso e apontando possíveis ajustes que contribuam para a melhoria da experiência e eficiência no uso do sistema.
</p>

# Resultados

<p align="justify">
Para realizar a técnica de introspecção, as funcionalidades do aplicativo foram idealizadas e, posteriormente, verificadas se coincidem com funcionalidades já implementadas.
</p>

# Gravação da Técnica de Introspecção

<p align="justify"> Para tornar o processo de elicitação mais transparente e rastreável, foi realizada uma gravação onde um dos analistar navegava pelo aplicativo e o outro ajudava na concepção das ideias. Durante a gravação, o analista se colocou no lugar do usuário, explorando funcionalidades, navegando pela interface e verbalizando percepções, dificuldades e sugestões de melhoria. </p>

<p style="text-align: center"><iframe width="560" height="315" src="https://youtu.be/uMro1M4lL9w?si=AUC9TiV3eS7Xhcn6"  title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></p>
<p style="text-align: center"><a href="https://youtu.be/uMro1M4lL9w?si=AUC9TiV3eS7Xhcn6" target="blanket">Link para o vídeo</a></p>

## Requisitos funcionais

São as funcionalidades que o sistema deve oferecer.
<a id="req-funcionais"></a>
**A tabela 1** descreve as funcionalidades
<font size="3"><p style="text-align: center">**Tabela 1:** Requisitos Funcionais.</p></font>

| Código | Requisito Funcional                                              | ID | implementado |
|--------|------------------------------------------------------------------|---------------------------|----------------------|
| RF01   | Permitir consulta de multas e débitos do veículo                | IS01 | Sim |
| RF02   | Realizar agendamento de serviços (vistoria, CNH, etc.)         | IS02 | Sim |
| RF03   | Exibir informações da CNH e pontuação                           | IS03 | Sim |
| RF04   | Realizar a transferência da autuação de infração                | IS04 | Sim |
| RF05   | Exibir notificações de prazos e documentos vencidos            | IS05 | Sim |
| RF06   | Realizar transferência de documento do veículo                 | IS06 | Sim |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu), [João Lobo](https://github.com/joaolobo10), 2025.</p></font>


## Requisitos Não-Funcionais

São as qualidades que o sistema deve ter (desempenho, usabilidade, segurança, etc.).
<a id="req-nao-funcionais"></a>
**A tabela 2** descreve as qualidades

<font size="3"><p style="text-align: center">**Tabela 2:** Requisitos Não-Funcionais.</p></font>

| Código | Requisito Não-Funcional                                         | ID | Implementado |
|--------|-----------------------------------------------------------------|---------------------------|----------------------|
| RNF01  | Interface intuitiva e fácil de navegar                          | IS07 |  |
| RNF02  | Carregamento rápido das páginas                                 | IS08 |  |
| RNF03  | Acessibilidade para diferentes perfis de usuário                | IS09 |  |
| RNF04  | Compatibilidade com diferentes dispositivos e sistemas          | IS10 |  |
| RNF05  | Segurança na exibição de dados pessoais                         | IS11 |  |

<font size="3"><p style="text-align: center">Fonte: [Eric Akio](https://github.com/eric-kingu), [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## Bibliografia

> 1. Aplicativo do DetranDF. Disponível em: Play Store. Acesso em: 22 abr 2025.

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 21/04/2025 | Início da documentação | [Eric Akio](https://github.com/eric-kingu)  |  [Giovana Barbosa ](https://github.com/gio221) |
|  1.1  | 07/06/2025 | adição de anchors nas tabelas | [Gabriel Mendes](https://github.com/gbevi)       |      [Giovana Barbosa ](https://github.com/gio221)                                       | 
