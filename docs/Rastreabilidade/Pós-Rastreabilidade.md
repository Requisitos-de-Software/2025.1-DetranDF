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

## RF05 E05
<details>
  <summary>RF05 - Exibir notificações de prazos e documentos vencidos</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Exibir notificações de prazos e documentos vencidos</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/">RF05</a>, <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/">IS05</a>,<a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS06</a>,<a href="http://127.0.0.1:8000/2025.1-DetranDF/modelagem/Agil/Historis-usuario/">US011</a></td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – IS05, BS06. O requisito originou-se da Introspecção funcional e da técnica de Brainstorm</td>
    </tr>
   <tr>
  <td><strong>Elos Forward-from</strong></td>
  <td>
    Satisfação – O requisito será utilizado para alertar o usuário sobre pendências documentais<br>
    Agregação – O requisito será alocado no Módulo de Notificações
  </td>
</tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>

</details>

## RF06 E06
<details>
  <summary>RF06 - Realizar transferência de documento do veículo</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Realizar transferência de documento do veículo</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/">RF06</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/">IS06</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/">US018</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – IS06. O requisito originou-se da técnica de Introspecção funcional</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à necessidade de serviços veiculares digitais<br>
        Agregação – O requisito será classificado no Módulo de Serviços do Veículo
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

## RF07 E07
<details>
  <summary>RF07 - Trocar a PPD para CNH definitiva pelo app</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Trocar a PPD para CNH definitiva pelo app</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/">RF07</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS02</a>
         <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/">US19</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS02. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito satisfaz a jornada de renovação de CNH dentro do app<br>
        Agregação – O requisito será alocado no Módulo de CNH
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

## RF08 E08
<details>
  <summary>RF08 - Sistema de pagamento de taxas e débitos</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Sistema de pagamento de taxas e débitos</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/">RF08</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS03</a>
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/caso-de-uso/">UC02</a>
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/">US32</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS03. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à necessidade de quitação de pendências pelo app<br>
        Agregação – O requisito será classificado no Módulo Financeiro
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

## RF09 E09
<details>
  <summary>RF09 - Aviso automático em caso de roubo/recuperação do carro</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Aviso automático em caso de roubo/recuperação do carro</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/">RF09</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS04</a>
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/caso-de-uso/">UC12</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">US12</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS04. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito prevê segurança e alerta em caso de incidentes com o veículo<br>
        Agregação – O requisito será incluído no Módulo de Segurança e Alertas
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

## RF10 E010
<details>
  <summary>RF10 - Consulta de CNH, documentos e multas</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Consulta de CNH, documentos e multas</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/">RF10</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS05</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/">US03</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS05. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito facilita o acesso do usuário à sua situação veicular<br>
        Agregação – O requisito será classificado no Módulo de Consultas
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>


## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 31/05/2025 | criação do documento |  [Giovana Barbosa](https://github.com/gio221)   |   |
|  1.1   | 05/06/2025| introdução, objetiva. metodologia, e template da rastreabilidade |  [Giovana Barbosa](https://github.com/gio221)   |   |