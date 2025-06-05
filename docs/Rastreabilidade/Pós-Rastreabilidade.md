# Introdução
No presente documento, abordamos conceitos e métodos baseados no Meta-modelo de Toranzo, que orienta a organização e representação dos principais elementos e suas relações na análise de requisitos, promovendo uma compreensão estruturada e rastreável

Adotamos os elos Backward-from e Forward-from, essenciais para a rastreabilidade dos requisitos:

Elos Backward-from: Apontam a origem de um requisito ou elemento, permitindo identificar de onde ele foi derivado e compreender o motivo de sua existência.
Elos Forward-from: Indicam como um requisito ou elemento se relaciona com outros, evidenciando sua contribuição para a implementação ou satisfação de outros elementos do sistema.

# Objetivo
O objetivo deste documento é detalhar a estruturação dos requisitos do aplicativo detran-df, utilizando o Meta-modelo de Toranzo como base.

# Metodologia
Para fazermos esse modelo ultilizamos o template da tabela abaixo

<font size="3"><b>Tabela 1:</b> Modelo de cartão </font>

| **Item** | **Descrição** |
|:-----:|:--------:|
| **Descrição do requisito** | qual requisito está tratando |
| **Categoria** | Ambiental, Organizacional, Gerencial ou Desenvolvimento |
| **Elementos** | Elementos rastreavéis |
| **Elos Backward-from** | Tipo de elo - Origem |
| **Elos Forward-from** | Tipo de elo - Relação | 
| **Print** | Imagem |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

## Legenda

- Categoria: Classificadas em quatro níveis. 
    - Ambiental: Refere-se ao contexto externo no qual o sistema será inserido. Considera todos os fatores e restrições externas que podem influenciar o sistema, como fatores legais; cultura e sociedade; tecnologia disponível. 
    - Organizacional: Foca na organização que está desenvolvento. Analisa elementos internos, como objetivos; estratégias.
    - Gerencial: Refere-se a informações que auxiliam a gerência do projeto, como planejamento; comunicação.
    - Desenvolvimento: Abrange os aspectos técnicos diretamente relacionados à construção e implementação do sistema, como artefatos de requisitos; códigos.

- Elementos: Identificadores para:
    - requisito (RFx - para requisitos funcionais e RNFx - para requisitos não funcionais)
    -  Caso de uso(UCx)
    -  Cenário(CENx)
    -  História de usuário (USx)
    -  Técnica de elicitação(OBx - Observação, ISx - Introspecção funcional, NIS - Introspecção para os não funcionais, BTx - Brainstorm, QTx - Questionário)
    - NFR Framework (NFRx)
    - Especificação suplementar (RUx, RCx, RDx, RSx, RDEx, RINx, RFIx)

- Elos Backward-from: Mostra-se o tipo de elo e a origem do requisito.

- Elos Forward-from: Mostra-se o tipo de elo e como o requisito é satisfeito ou relacionado a outros elementos.

- Tipos de Elos: 
    - Satisfação: Relacionado ao cumprimento de expectativas ou demandas.
    - Recurso: Conecta elementos que fornecem ou utilizam recursos necessários, podendo ser uma pessoa, equipe, tempo, orçamento, etc.
    - Responsabilidade: Relaciona quem ou o que é responsável por determinados elementos ou atividades. 
    - Representação: Conecta elementos de representação ou abstração de algo. 
    - Alocado: Representa a alocação de recursos, funcionalidades ou responsabilidades.
    - Agregação: Indica a composição de elementos para formar um todo.

- Print: Imagem/protótipo da implementação

# Rastreabilidade

### RF05

<details>

<summary> Exibir notificações de prazos e documentos vencidos </summary>

| **Item** | **Descrição** |
|:-----:|:--------:|

</details>

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 31/05/2025 | criação do documento |  [Giovana Barbosa](https://github.com/gio221)   |   |
|  1.1   | 05/06/2025| introdução, objetiva. metodologia, e template da rastreabilidade |  [Giovana Barbosa](https://github.com/gio221)   |   |