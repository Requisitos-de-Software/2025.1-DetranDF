# Introdução
A rastreabilidade de requisitos permite acompanhar cada requisito durante todo o desenvolvimento, ligando-os tanto aos documentos iniciais quanto aos resultados das etapas seguintes. De acordo com Wiegers e Beatty (2013), essa prática é essencial para a gestão de requisitos, facilitando o desenvolvimento de software e sendo indispensável para atividades como análise de impacto e manutenção. Este documento apresenta uma matriz que reúne as informações necessárias para rastrear os requisitos deste projeto.

# Objetivo
Com a matriz de rastreabilidade buscamos representar as informações de ligação entre requisitos, suas fontes e seus artefatos derivados de maneira clara e objetiva.

# Metodologia
A matriz é apresentada com 7 colunas sendo elas:

- Requisito	
- Descrição
- Implementado
- Versão
- Elicitação
- Modelagem
- Elos
- Autor

**Tabela 1:** modelo da matriz de rastreabilidade

| Requisito  | Descrição | Implementado | Versão |     Elicitação      |       Modelagem        | Elos | Autor |
| :--------: | :-------: | :----------: | :----: | :-----: |:-----------------: | :--------------------: | :--: |
| RFxx/RNFxx |    --     |   SIM/NÃO    |  x.x   | OBxx/ISxx/QTxx/BTxx | CENxx/UCxx/SE/USxx/NFR | Cxx  | Integrante responsável |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

### Legenda

- **Requisito:** código identificador do requisito. Requisitos funcionais tem o código no formato RFxx, já requisitos não funcionais apresentam código no formato RNFxx;
- **Descrição:** descrição do requisito elicitado;
- **Implementado:** indica o status de implementação do requisito. Requisitos implementados são preenchidos com 'SIM' e não implementados são preenchidos com 'NÃO';
- **Versão:** indica a versão do requisito;
- **Elicitação:** indica os artefatos nos quais o requisito foi elicitado.
	1. OBxx - Requisito elicitado pela observação.
	2. ISxx - Requisito elicitado pela introspecção.
	3.  GLxx - Requisito elicitado pelo Glossário.
	4. BTxx - Requisito elicitado pelo Brainstorming.
    5. STOxx-  Requisito elicitado pelo Storytelling
- **Modelagem:** indica os artefatos de modelagem do requisito.
	1. CENxx - cenários
	2. UCxx - casos de uso
	3. SE - especificação suplementar
	4. USxx - histórias de usuário
	5. NFR - NFR framework
- **Elos:** indica cartão de elos referente ao requisito. 

## Matriz de Rastreabilidade

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 31/05/2025 | criação do documento |  [Giovana Barbosa](https://github.com/gio221)   |   |
|  1.1   | 05/06/2025 | introdução.objetiva e metodologia |  [Giovana Barbosa](https://github.com/gio221)   |   |