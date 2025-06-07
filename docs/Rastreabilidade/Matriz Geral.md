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

| Requisito  | Descrição | Implementado | Versão |     Elicitação      |       Modelagem        | Elos | Autor |
| :--------: | :-------: | :----------: | :----: | :-----: |:-----------------: | :--------------------: | :--: |
| RF05|   Exibir notificações de prazos e documentos vencidos    |   SIM    |  1.1   | [IS05](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/) [BS06](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/) | [US011](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E05](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |
|RF06| Realizar transferência de documento do veículo|SIM    |  1.1   |[IS06](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/)|[US018](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E06](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |
|RF07|Trocar a PPD para CNH definitiva pelo app|SIM    |  1.1   |[BS02](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/)|[US019](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E07](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |
|RF08|Sistema de pagamento de taxas e débitos|SIM    |  1.1   |[BS03](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/)|[US032](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E08](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |
|RF09|Aviso automático em caso de roubo/recuperação do carro| Não|1.1   |[BS04](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/)|[US012](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E09](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |
|RF10| Consulta de CNH, documentos e multas|SIM    |  1.1   |[BS05](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/)|[US03](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E10](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |
|RNF01| Interface intuitiva e fácil de navegar|SIM    |  1.1   |[IS017](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/) [BS05](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/)|[US01 - Usabilidade](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E45](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |
|RNF02|Compatibilidade com diferentes dispositivos e sistemas|SIM    |  1.1   |[IS010](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/) [BS15](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/)|[US02 - Desempenho](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E46](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |
|RNF03| Alta segurança no tratamento de dados pessoais e veiculares|SIM    |  1.1   |[IS010](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/) [BS15](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/)[GLO06](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/glossario/)|[ US03 - Confiabilidade](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E47](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |
|RNF04| Área educacional com explicações e vídeos|Não  |  1.1   |[BS01](https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/)|[US04 - Usabilidade](http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/)| [E48](https://requisitos-de-software.github.io/2025.1-DetranDF/Rastreabilidade/Matriz%20Geral/)  |  [Giovana Barbosa](https://github.com/gio221)  |

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 31/05/2025 | criação do documento |  [Giovana Barbosa](https://github.com/gio221)   |   |
|  1.1   | 05/06/2025 | introdução,objetivo e metodologia |  [Giovana Barbosa](https://github.com/gio221)   |   |
|  1.2   | 05/06/2025 | adicionei na matriz RF01 a RF10 e RNF01 a RNF04 |  [Giovana Barbosa](https://github.com/gio221)   |   |