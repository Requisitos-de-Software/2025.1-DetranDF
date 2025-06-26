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

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

## Legenda

<font size="3"><p style="text-align: center">**Tabela 2:** Níveis de informação.</p></font>

| **Nível de Informação**       | **Descrição**                                                                                                                                                                                                     |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ambiental**       | Refere-se ao contexto externo no qual o sistema será inserido. Considera todos os fatores e restrições externas que podem influenciar o sistema, como fatores legais; cultura e sociedade; tecnologia disponível. |
| **Organizacional**  | Foca na organização que está desenvolvendo. Analisa elementos internos, como objetivos; estratégias.                                                                                                              |
| **Gerencial**       | Refere-se a informações que auxiliam a gerência do projeto, como planejamento; comunicação.                                                                                                                       |
| **Desenvolvimento** | Abrange os aspectos técnicos diretamente relacionados à construção e implementação do sistema, como artefatos de requisitos; códigos. |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221), [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

<font size="3"><p>**Tabela 3:** Elementos identificadores.</p></font>

| **Elemento**                  | **Identificador / Descrição**                                                                                                           |
| ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| **Requisito**                 | RFx - para requisitos funcionais<br>RNFx - para requisitos não funcionais                                                               |
| **Caso de uso**               | UCx                                                                                                                                     |
| **Cenário**                   | CENx                                                                                                                                    |
| **História de usuário**       | USx                                                                                                                                     |
| **Técnica de elicitação**     | OBx - Observação<br>ISx - Introspecção funcional<br>NIS - Introspecção para os não funcionais<br>BTx - Brainstorm<br>QTx - Questionário |
| **NFR Framework**             | NFRx                                                                                                                                    |
| **Especificação suplementar** | Rux, RCx, RDx, RSx, RDEx, RINx, RFIx     

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221), [João Lobo](https://github.com/joaolobo10), 2025.</p></font>                                                                                               

<font size="3" style="text-align: center"><p>**Tabela 4:** Tipos de Elo.</p></font>

| **Tipo de Elo**        | **Descrição**                                                                              |
| ---------------------- | ------------------------------------------------------------------------------------------ |
| **Elos Backward-from** | Mostra-se o tipo de elo e a origem do requisito.                                           |
| **Elos Forward-from**  | Mostra-se o tipo de elo e como o requisito é satisfeito ou relacionado a outros elementos. |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221), [João Lobo](https://github.com/joaolobo10), 2025.</p></font> 

<font size="3" style="text-align: center"><p>**Tabela 5:** Relacionamento entre informações.</p></font>

| **Relacionamento**      | **Descrição**                                                                                                           |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| **Satisfação**       | Relacionado ao cumprimento de expectativas ou demandas.                                                                 |
| **Recurso**          | Conecta elementos que fornecem ou utilizam recursos necessários, podendo ser uma pessoa, equipe, tempo, orçamento, etc. |
| **Responsabilidade** | Relaciona quem ou o que é responsável por determinados elementos ou atividades.                                         |
| **Representação**    | Conecta elementos de representação ou abstração de algo.                                                                |
| **Alocado**          | Representa a alocação de recursos, funcionalidades ou responsabilidades.                                                |
| **Agregação**        | Indica a composição de elementos para formar um todo.                                                                   |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221), [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

- Print: Imagem/protótipo da implementação

# Rastreabilidade

### Quem fez cada requisito

|Nome de quem verificou| quais requisitos verificados|
| :----: | --------- |
| [Luiz Bessa](https://github.com/lfelipebessa)|RF 01 a 04, 42 a 44, e RNF 20|
| [Giovana Barbosa](https://github.com/gio221) |RF 05 a 10 e RNF 01 a 04|
| [João Lobo](https://github.com/joaolobo10)   | RF 11, 13, 14, 16, 17, 21 e RNF 05 a 07|
|[Gabriel Mendes](https://github.com/gbevi)|RF 12, 15, 18, 19, 20, 22 e RNF 8 a 10|
| [Maria Eduarda](https://github.com/maaduh) | RF 23 a 28 e RNF 11 a 13|
| [Pedro Camilo](https://github.com/PedrooCamilo)  |RF 29 a 34 e RNF 14 a 16|
| [Eric Akio](https://github.com/eric-kingu)|RF 35 a 41 e RNF 17 a 19|


<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa ](https://github.com/gio221), 2025.</p></font>

## Requisitos Funcionais

## RF01 E01
<details open>
  <summary>RF01 - Permitir consulta de multas e débitos do veículo</summary>

  <table>
    <tr>
      <th>Item</th><th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Permitir consulta de multas e débitos do veículo</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>RF01, IS01, BS01<!-- linkaqui --></td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – IS01, OBS001. O requisito originou-se da Introspecção funcional e de Observações de usuários.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação – viabiliza transparência sobre débitos do veículo.<br>Agregação – alocado no Módulo de Consultas.</td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/RF01aRF03.PNG"
             alt="Print RF01 a RF03"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

## RF02 E02
<details open>
  <summary>RF02 - Realizar agendamento de serviços</summary>

  <table>
    <tr><th>Item</th><th>Descrição</th></tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Realizar agendamento de serviços (vistoria, CNH, etc.)</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>RF02, IS02, BS02<!-- linkaqui --></td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – IS02, OBS002. Originado por Introspecção funcional e Observações.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação – permite ao usuário reservar horários sem filas.<br>Agregação – alocado no Módulo de Agendamento.</td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/RF01aRF03.PNG"
             alt="Print RF01 a RF03"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

## RF03 E03
<details open>
  <summary>RF03 - Exibir informações da CNH e pontuação</summary>

  <table>
    <tr><th>Item</th><th>Descrição</th></tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Exibir informações da CNH e pontuação</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>RF03, IS03, BS01, OBS003<!-- linkaqui --></td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – IS03, BS01, OBS003. Derivado de Introspecção, Brainstorm e Observações.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação – fornece monitoramento da situação da carteira.<br>Agregação – alocado no Módulo Carteira Digital.</td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/RF01aRF03.PNG"
             alt="Print RF01 a RF03"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

## RF04 E04
<details open>
  <summary>RF04 - Realizar a transferência da autuação de infração</summary>

  <table>
    <tr><th>Item</th><th>Descrição</th></tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Realizar a transferência da autuação de infração</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>RF04, IS04<!-- linkaqui --></td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – IS04. Originado da Introspecção funcional.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – facilita transferência de responsabilidade pela infração.<br>
        Agregação – alocado no Módulo de Infrações.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/RF04.PNG"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

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
      <td><br> <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF05</a>, <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/#req-funcionais">IS05</a>,<a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS06</a>,<a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us11">US11</a></td>
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
      <td>
        <img src="../../assets/rastrea/gi rf05.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>

</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

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
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF06</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/#req-funcionais">IS06</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us18">US18</a>
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
     <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/rastrea/girf06.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

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
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF07</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS02</a>
         <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us19">US19</a>
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
         <td>
        <img src="../../assets/rastrea/rf07.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

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
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF08</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS03</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/caso-de-uso/">UC02</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us32">US32</a>
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
      <td>
        <img src="../../assets/rastrea/rf07.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

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
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF09</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS04</a>
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/caso-de-uso/">UC12</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us12">US12</a>
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
       <td>
        <img src="../../assets/rastrea/gi rf05.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
     <tr>
       <td>
        <a href="https://www.figma.com/proto/ohrsL5pYJxKWrbSbha2sQE/Detran-DF?node-id=74-3132&t=DBGuf4RHISFNe3IO-0&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1">Link do prototipo</a>
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

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
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF10</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS05</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us03">US03</a>
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
        <td>
        <img src="../../assets/rastrea/rf07.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

## RF11 E011
<details>
  <summary>RF11 - Agendamento online para provas teóricas e práticas</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Seção dentro do aplicativo, onde um usuário que está no processo de obter a sua CNH, consegue agendar a prova teórica e prática de forma online.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Ambiental</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF11</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS07</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us15">UC15</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS07. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito facilita o acesso do usuário ao agendamento de provas, eliminando a necessidade de deslocamento até a autoescola.<br>
        Agregação – O requisito será classificado no Módulo de Consultas.<br>
        Recurso - API do Detran, banco de dados, equipe de desenvolvimento.<br>
        Responsabilidade - Time de backend responsável pela implementação.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem - Não implementado</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## RF12 E012
<details>
  <summary>RF12 - Opção para adicionar quilometragem do seu carro</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Uma Área dentro do aplicativo para autoescolas que contém,avaliações, comentários e localização.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Ambiental</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF12</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS08</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us40">US40</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS08. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à necessidade do usuário ao oferecer uma área no aplicativo dedicada às autoescolas, com avaliações, comentários e localização, facilitando a escolha da instituição.<br>
        Agregação – O requisito será classificado no Módulo de Consultas.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
      <img src="../../assets/rastrea/rf12.png"
             alt="Tela de editar quilometragem"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
    <tr>
       <td>
        <a href="https://www.figma.com/design/ohrsL5pYJxKWrbSbha2sQE/Detran-DF?node-id=32-480&t=Zg0B6U9icKFhECIM-1">Link do protótipo</a>
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## RF13 E013
<details>
  <summary>RF13 - Guia de documentos necessários para cada tipo de serviço</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Um guia de documentos necessários para cada tipo de serviço, para facilitar o conhecimento do usuário sobre cada documento.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Ambiental</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF13</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS09</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us41">US41</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS09. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à expectativa do usuário ao fornecer um guia claro sobre os documentos exigidos para cada tipo de serviço, facilitando o entendimento e evitando deslocamentos desnecessários por falta de informação.<br>
        Agregação – O requisito será classificado no Módulo de Consultas.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem - Não Implementado</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## RF14 E014
<details>
  <summary>RF14 - Chat com IA para tirar dúvidas</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Um chat com uma inteligência artificial para tirar dúvidas, sobre qualquer tema que se relacione ao Detran e ao aplicativo, mas tendo suas limitações.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF14</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS10</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us34">US34</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS010. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à necessidade do usuário ao oferecer um chat com inteligência artificial para tirar dúvidas relacionadas ao Detran e ao aplicativo, proporcionando suporte imediato e acessível, mesmo com suas limitações.<br>
        Agregação – O requisito será classificado no Módulo de Consultas.<br>
        Recurso	- Serviço de IA e infraestrutura para chat.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/rf14.png"
             alt="RF14"
             width="90%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## RF15 E015
<details>
  <summary>RF15 - Integração com CNH Digital</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Ter a possibilidade de entrar no aplicativo, utilizando a CNH Digital, onde utiliza as mesmas credenciais e facilita a autenticação.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF15</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS11</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us39">US39</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS11. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à expectativa do usuário ao permitir o acesso ao aplicativo utilizando as credenciais do Gov.br, facilitando a autenticação por meio de um login unificado e já conhecido.<br>
        Agregação – O requisito será classificado no Módulo de Consultas<br>
        Recurso	- Integração com sistema Gov.br para autenticação.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
      <img src="../../assets/rastrea/rf15.png"
             alt="integração cnh digital"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
    <tr>
       <td>
        <a href="https://www.figma.com/design/ohrsL5pYJxKWrbSbha2sQE/Detran-DF?node-id=29-230&t=Zg0B6U9icKFhECIM-1">Link do protótipo</a>
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## RF16 E016
<details>
  <summary>RF16 - Atendimento ao vivo com servidor do DETRAN via chat/vídeo</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Ter um atendimento via chat/vídeo com um servidor do Detran-DF.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Ambiental</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF16</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-funcionais">BS12</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us35">US35</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS05. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à necessidade do usuário ao oferecer atendimento via chat ou vídeo com um servidor do Detran-DF, proporcionando suporte direto e personalizado para esclarecer dúvidas e resolver questões.<br>
        Agregação – O requisito será classificado no Módulo de Consultas <br>
        Recurso - Plataforma de chat/vídeo e equipe de atendimento do Detran.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/rf16.png"
             alt="RF16"
             width="90%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## RF17 E17
<details>
  <summary>RF17 - Exibir status do licenciamento e do IPVA do veículo</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Exibir status do licenciamento e do IPVA do veículo</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/requisitos-elicitados/#req-funcionais">RF17</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario/#req-funcionais">GLO03</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us04">US04</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – GLO03. O requisito originou-se do Glossário.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite ao usuário acompanhar a regularidade do veículo.<br>
        Agregação – O requisito será alocado no Módulo de Consultas Veiculares.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/rastrea/rf17.PNG"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## RF18 E18
<details>
  <summary>RF18 - Gerar segunda via da CNH e CRLV digitalmente</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Gerar segunda via da CNH e CRLV digitalmente</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/requisitos-elicitados/#req-funcionais">RF18</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario/#req-funcionais">GLO04</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us20">US20</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – GLO04. O requisito originou-se do Glossário.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito facilita a obtenção de documentos digitais.<br>
        Agregação – O requisito será alocado no Módulo de Documentos Digitais.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/rastrea/rf18_1.PNG"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
      <td>
        <img src="../../assets/rastrea/rf18_2.PNG"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## RF19 E19
<details>
  <summary>RF19 - Deve ser possível consultar a pontuação da CNH diretamente no aplicativo</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Deve ser possível consultar a pontuação da CNH diretamente no aplicativo</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/requisitos-elicitados/#req-funcionais">RF19</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario/#req-funcionais">GLO01</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us02">US02</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – GLO01. O requisito originou-se do Glossário.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite ao usuário acompanhar sua pontuação.<br>
        Agregação – O requisito será alocado no Módulo de CNH.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/rastrea/rf19.PNG"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## RF20 E20
<details>
  <summary>RF20 - O aplicativo deve permitir o agendamento de serviços presenciais</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>O aplicativo deve permitir o agendamento de serviços presenciais</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/requisitos-elicitados/#req-funcionais">RF20</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario/#req-funcionais">GLO02</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us02">US02</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – GLO02. O requisito originou-se do Glossário.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito facilita o agendamento de serviços pelo app.<br>
        Agregação – O requisito será alocado no Módulo de Agendamento.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/rastrea/rf20.PNG"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## RF21 E21
<details>
  <summary>RF21 - Permitir acompanhamento de processos</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Permitir acompanhamento de processos</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/requisitos-elicitados/#req-funcionais">RF21</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS004</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us21">US21</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS004. O requisito originou-se da Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite ao usuário acompanhar processos em andamento.<br>
        Agregação – O requisito será alocado no Módulo de Processos.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/rastrea/rf21.PNG"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## RF22 E22
<details>
  <summary>RF22 - Exibir notificações de prazos e documentos vencidos</summary>

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
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/requisitos-elicitados/#req-funcionais">RF22</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS005</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us11">US11</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS005. O requisito originou-se da Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite alertar o usuário sobre pendências documentais.<br>
        Agregação – O requisito será alocado no Módulo de Notificações.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/rastrea/rf22.PNG"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>


<font size="3"><p style="text-align: center">Autor: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## RF23 E23
<details>
  <summary>RF23 - Permitir consulta do status do licenciamento em tempo real</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Permitir consulta do status do licenciamento em tempo real</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF23</a>,

         Storytelling, US42
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. O requisito originou-se da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à demanda por acompanhamento ativo de documentação<br>
        Agregação – O requisito será alocado no Módulo de Licenciamento
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/licenciamento.jpg"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>


## RF24 E24
<details>
  <summary>RF24 - Permitir geração de boleto e pagamento integrado no app</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Permitir geração de boleto e pagamento integrado no app</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF24</a>
, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO01</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us43">US43</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. O requisito originou-se da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à necessidade de quitar débitos diretamente no app<br>
        Agregação – Módulo Financeiro
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/boleto.png"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>


## RF25 E25
<details>
  <summary>RF25 - Permitir consulta e detalhamento de infrações com imagens</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Permitir consulta e detalhamento de infrações com imagens</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF25</a>
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO02</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us43">US44</a>      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. O requisito originou-se da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Proporciona transparência sobre multas<br>
        Agregação – Módulo de Infrações
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/multas.png"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>


## RF26 E26
<details>
  <summary>RF26 - Iniciar e acompanhar recurso de multa pelo app</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Iniciar e acompanhar recurso de multa pelo app</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF26</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO03</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us43">US45</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. O requisito originou-se da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Facilita o processo de defesa do usuário<br>
        Agregação – Módulo de Recursos
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/recurso.png"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>


## RF27 E27
<details>
  <summary>RF27 - Permitir agendamento de exame médico para CNH</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Permitir agendamento de exame médico para CNH</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF27</a>,

        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO04</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us43">US46</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. O requisito originou-se da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Automatiza agendamento necessário para renovação CNH<br>
        Agregação – Módulo CNH
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/agendamento.png"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>


## RF28 E28
<details>
  <summary>RF28 - Enviar notificações de vencimento da CNH, multas e licenciamento</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Enviar notificações de vencimento da CNH, multas e licenciamento</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF28</a>,

                <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO05</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us43">US47</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. O requisito originou-se da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Melhora o acompanhamento do usuário sobre prazos<br>
        Agregação – Módulo de Notificações
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/notiicaçao.png"
             alt="Tela de avisos"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>

## Requisito Funcional 29 - Elo 29
<details open>
  <summary>RF29 - Explicações simples sobre termos técnicos</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Explicações simples de termos técnicos para entender melhor os processos.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF29</a>,

                <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO07</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us36">US36</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. O requisito originou-se da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Representação - Ajuda o usuário a compreender termos técnicos
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
      <img src="../../assets/RF29-pt0.png"
             alt="Print RF29"
             width="30%"
             style="height:auto;">
      <img src="../../assets/RF29-pt4.png"
             alt="Print RF29"
             width="30%"
             style="height:auto;">
      <img src="../../assets/RF29-pt3.png"
             alt="Print RF29"
             width="30%"
             style="height:auto;">
      <img src="../../assets/RF29-pt1.png"
             alt="Print RF29"
             width="30%"
             style="height:auto;">
          <img src="../../assets/RF29-pt2.png"
             alt="Print RF29"
             width="30%"
             style="height:auto;">   
             </td>
    </tr>
    
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>

## Requisito Funcional 30 - Elo 30
<details open>
  <summary>RF30 - Canal de atendimento humano</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Oferecer canal de atendimento humano (chat ou WhatsApp) para sanar dúvidas ou resolver questões pendentes.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF30</a>,

                <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO08</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us35">US36</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Recurso – Storytelling. O requisito originou-se da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito atende à necessidade do usuário ao oferecer atendimento via chat ou WhatsApp com um servidor do Detran-DF, proporcionando suporte direto e personalizado para esclarecer dúvidas.<br>
        Recurso – Requer a integração com uma plataforma de mensagens e a alocação de equipe para o atendimento.<br>
        Agregação – O requisito será incluído no Módulo de Suporte ao Cidadão.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
      <img src="../../assets/RF30-PT1.png"
             alt="Print RF30"
             width="30%"
             style="height:auto;">
      <img src="../../assets/RF30.png"
             alt="Print RF30"
             width="30%"
             style="height:auto;"></td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>


## Requisito Funcional 31 - Elo 31
<details open>
  <summary>RF31 - Reposição de placa Mercosul</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Desejo solicitar uma nova placa Mercosul</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF31</a>,

                <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS006</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us22">US22</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Responsabilidade – O requisito originou-se da técnica de Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Responsabilidade – O requisito delega ao sistema a função de intermediar o processo de reposição da placa, incluindo instruções, documentos necessários e encaminhamento para o órgão competente.<br>
        Agregação – Será incorporado ao Módulo de Veículos, dentro da seção de serviços.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td><img src="../../assets/RF31.png"
             alt="Print RF31"
             width="30%"
             style="height:auto;"></td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>

## Requisito Funcional 32 - Elo 32
<details open>
  <summary>RF32 - Conversão de placa Mercosul</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Desejo solicitar a troca da placa antiga para uma placa Mercosul</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF31</a>,

                <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS007</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us23">US23</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Responsabilidade – O requisito originou-se da técnica de Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        	Responsabilidade – O requisito define a responsabilidade do sistema em guiar o usuário no processo de conversão, informando etapas, prazos e vínculos com normativas vigentes.<br>
          Agregação – Este serviço será parte do Módulo de Veículos, agrupado com outros serviços de placa.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td><img src="../../assets/RF31.png"
             alt="Print RF32"
             width="30%"
             style="height:auto;"></td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>


## Requisito Funcional 33 - Elo 33
<details open>
  <summary>RF33 - Histórico de infração do condutor</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Ver o histórico de infração do condutor</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF33</a>,

                <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS008</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us08">US08</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – O requisito originou-se da técnica de Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        		Representação – O requisito será refletido na interface como uma lista de infrações organizadas cronologicamente, com detalhes sobre data, local e pontuação.<br>
            Agregação – Será integrado ao Módulo de Condutor, servindo de base para outras funcionalidades como recurso de multa e consulta de pontos.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td><img src="../../assets/RF33.png"
             alt="Print RF33"
             width="30%"
             style="height:auto;"></td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>

## Requisito Funcional 34 - Elo 34
<details open>
  <summary>RF34 - Histórico de infração do veículo	</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Ver o histórico de infração do veículo</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF34</a>,

                <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS009</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us09">US08</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – O requisito originou-se da técnica de Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        			Representação – O requisito é representado por uma interface clara que exibe todas as infrações vinculadas ao veículo, incluindo status de pagamento e penalidades.<br>
              Agregação – Será parte do Módulo de Veículos, com integração ao banco de dados de autuações.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td><img src="../../assets/RF34.png"
             alt="Print RF34"
             width="30%"
             style="height:auto;"></td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>


## RF35 E35
<details>
  <summary>RF35 - Conversão de autuação em penalidade</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Conversão de autuação em penalidade</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF35</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS010</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us24">US24</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS010. O requisito originou-se da Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite o usuário converter autuação em penalidades.<br>
        Agregação – O requisito será alocado no Módulo de Infrações.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RF36 E36
<details>
  <summary>RF36 - Nova solicitação de Protocolo-e</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Nova solicitação de protocolo-e</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF36</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS011</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us25">US25</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS011. O requisito originou-se da Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite o usuário fazer uma nova solicitação de Protocolo-e.<br>
        Agregação – O requisito será alocado no Módulo de Protocolo-e.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RF37 E37
<details>
  <summary>RF37 - Acompanhar solicitação de protocolo-e</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Acompanhar solicitação de protocolo-e</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF37</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS012</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us26">US26</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS012. O requisito originou-se da Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite o usuário acomapanhar solicitação de protocolo-e.<br>
        Agregação – O requisito será alocado no Módulo de Protocolo-e.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RF38 E38
<details>
  <summary>RF38 - Solicitar credencial de estacionamento para idoso</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Solicitar credencial de estacionamento para idoso</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF38</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS013</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us27">US27</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS013. O requisito originou-se da Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite o usuário solicitar credencial de idoso.<br>
        Agregação – O requisito será alocado no Módulo de credenciais.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RF39 E39
<details>
  <summary>RF38 - Solicitar credencial de estacionamento para TEA</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Solicitar credencial de estacionamento para TEA</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF39</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS014</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us28">US28</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS014. O requisito originou-se da Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite o usuário solicitar credencial para pessoas com TEA.<br>
        Agregação – O requisito será alocado no Módulo de Credenciais.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RF40 E40
<details>
  <summary>RF40 - Pagamento de débitos para liberação de veículo</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Pagamento de débitos para liberação de veículo</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF40</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS015</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us29">US29</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS015. O requisito originou-se da Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite o usuário pagar débitos para liberar veículo do pátio.<br>
        Agregação – O requisito será alocado no Módulo de Infrações.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td><img src="../assets/RF40.png"
              alt="Tela pagamento de débitos"
              width=60%></td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RF41 E41
<details>
  <summary>RF41 - Simulado de prova teórica</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Simulado de prova teórica</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-funcionais">RF41</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Observação#req-funcionais">OBS016</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/Historis-usuario/#us42">US42</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS016. O requisito originou-se da Observação.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito permite o usuário fazer simulados de prova teórica.<br>
        Alocado – O requisito será alocado no Módulo de Simulados.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td><img src="../assets/RF41-1.png"
              alt="Tela inicial com Simulados"
              width=60%>
          <img src="../assets/RF41-2.png"
              alt="Tela do módulo de Simulados"
              width=60%></td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RF42 E42

<!-- Bloco sempre ABERTO + print visível 100% do tempo -->
<details open>
  <summary>RF42 - Informações sobre leilão</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Ter uma parte sobre leilão</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>RF42, OBS017<!-- linkaqui --></td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS017. Identificado por observação de usuários.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – oferece acesso a editais e lances de leilões.<br>
        Agregação – alocado no Módulo de Leilões.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <!-- 
          Use width="600" (ou outro valor em px) para garantir que a imagem
          seja exibida no Preview local. Se preferir, ajuste para width="100%"
          mas só funciona se o seu renderer suportar.
        -->
        <img src="../../assets/Leilao.png" 
             alt="Tela do módulo de leilões" 
             width=60%>
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

## RF43 E43

<details open>
  <summary>RF43 - Verificar autorização para transporte escolar</summary>

  <table>
    <tr><th>Item</th><th>Descrição</th></tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Verificar se o veículo tem autorização para transporte escolar</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>RF43, OBS018<!-- linkaqui --></td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS018. Identificado por Observação de usuários.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – permite consulta rápida da regularidade do serviço.<br>
        Agregação – alocado no Módulo Transporte Escolar.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/TransporteEscolar.png"
             alt="Tela do módulo de transporte escolar"
             width="60%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

## RF44 E44

<details open>
  <summary>RF44 - Solicitar autorização para transporte escolar</summary>

  <table>
    <tr><th>Item</th><th>Descrição</th></tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>O veículo conseguir solicitar autorização para transporte escolar</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>RF44, OBS019<!-- linkaqui --></td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – OBS019. Identificado por Observação de usuários.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – simplifica o processo de autorização junto ao DETRAN.<br>
        Agregação – alocado no Módulo Transporte Escolar.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>
        <img src="../../assets/TransporteEscolar.png"
             alt="Tela do módulo de solicitação de transporte escolar"
             width="60%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

---

## Requisitos Não Funcionais

## RNF01 E045

<details>
  <summary>RNF01 - Interface intuitiva e fácil de navegar</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Interface intuitiva e fácil de navegar</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/#req-nao-funcionais">BS14</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/#req-nao-funcionais">IS07</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#usabilidade">US01 - Usabilidade</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/">RNFR01 - Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS13, IS07. O requisito originou-se das técnicas de Brainstorm e Introspecção funcional</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação – O requisito contribui para a usabilidade da interface</td>
    </tr>
    <tr>
       <td>
        <img src="../../assets/rastrea/rf07.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

## RNF02 E046
<details>
  <summary>RNF02 - Compatibilidade com diferentes dispositivos e sistemas</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Compatibilidade com diferentes dispositivos e sistemas</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS15</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/">IS10</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#funcionalidades">US02 - Desempenho</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/">RNFR02 - Desempenho</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS14, IS10. O requisito originou-se das técnicas de Brainstorm e Introspecção funcional</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação – O requisito garante acessibilidade em múltiplos dispositivos e plataformas</td>
    </tr>
    <tr>
        <td>
        <img src="../../assets/rastrea/rf07.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

## RNF03 E047
<details>
  <summary>RNF03 - Alta segurança no tratamento de dados pessoais e veiculares</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Alta segurança no tratamento de dados pessoais e veiculares</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS16</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Introspec%C3%A7%C3%A3o/">IS11</a>, 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/glossario/">GLO06</a>,
         <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#funcionalidades">US03 - Confiabilidade</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/">RNFR03 - Confiabilidade</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS15, IS11, GLO06. O requisito originou-se das técnicas de Brainstorm, Introspecção funcional e Glossário</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação – O requisito assegura a proteção e integridade dos dados do usuário</td>
    </tr>
    <tr>
       <td>
        <img src="../../assets/rastrea/rf07.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

## RNF04 E048
<details>
  <summary>RNF04 - Área educacional com explicações e vídeos</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Área educacional com explicações e vídeos</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS1</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#funcionalidades">US04 - Usabilidade</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/">RNFR04 - Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS16. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação – O requisito auxilia na educação e orientação dos usuários</td>
    </tr>
   <tr>
       <td>
        <img src="../../assets/rastrea/rnf.png"
             alt="Tela de transferência de autuação"
             width="30%"
             style="height:auto;">
      </td>
    </tr>
     <tr>
       <td>
        <a href="https://www.figma.com/proto/ohrsL5pYJxKWrbSbha2sQE/Detran-DF?node-id=76-3340&t=DBGuf4RHISFNe3IO-0&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1">Link do prototipo</a>
      </td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Giovana Barbosa](https://github.com/gio221), 2025.</p></font>

## RNF05 E049
<details>
  <summary>RNF05 - Acessibilidade (fonte grande, contraste, modo noturno)</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Acessibilidade (fonte grande, contraste, modo noturno)</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS17</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#funcionalidades">US04 - Usabilidade</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/">RNFR04 - Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS17. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação- Atende usuários com baixa visão ou sensibilidade visual, oferecendo conforto e inclusão na interface.<br>
      Recurso - Biblioteca de design responsivo e componentes de acessibilidade.<br>
      Responsabilidade - Equipe de design e frontend responsável por implementar os estilos e modos acessíveis.</td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## RNF06 E050
<details>
  <summary>RNF06 - Leitor de tela e assistente por voz para pessoas cegas</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Leitor de tela e assistente por voz para pessoas cegas.</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS18</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#funcionalidades">US04 - Usabilidade</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/">RNFR04 - Usabilidade</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS18. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação - Garante que usuários cegos ou com deficiência visual possam utilizar o app com autonomia.<br>
      Recurso - APIs de acessibilidade do sistema operacional<br>
      Responsabilidade - Desenvolvedores mobile responsáveis por adaptar os elementos da interface para leitura por assistentes de voz.</td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem - nao implementado</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## RNF07 E051
<details>
  <summary>RNF07 - Sistema de avaliação com base em uso real (ex-alunos)</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Sistema de avaliação com base em uso real (ex-alunos)</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br> 
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/Brainstorming/">BS19</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/#quali">Qualidade e Feedback</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS19. O requisito originou-se da técnica de Brainstorm</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>Satisfação -	Ajuda novos usuários a escolherem autoescolas com base em experiências reais, promovendo confiança e transparência.<br>
        Recurso -	Banco de dados com registros de ex-alunos, formulário de avaliação, sistema de autenticação para validação dos dados.<br>
        Responsabilidade -	Time de backend responsável por armazenar e validar as avaliações; time de UX por garantir usabilidade da ferramenta.</td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td> Imagem - Não implementado</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [João Lobo](https://github.com/joaolobo10), 2025.</p></font>

## RNF08 E052
<details>
  <summary>RNF08 - Propaganda efetiva para promover o app</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Propaganda efetiva para promover o app</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF08</a>,
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#desempenho">US02 - Desempenho</a>,
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/#quali">RNFR08 - Qualidade e Feedback</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#bs20">BS20</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS20. O requisito originou-se da técnica de Brainstorming.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito contribui para o aumento da base de usuários do app.<br>
        Agregação – O requisito será alocado no Módulo de Divulgação.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## RNF09 E053
<details>
  <summary>RNF09 - Layout com foco em simplicidade e legibilidade</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Layout com foco em simplicidade e legibilidade</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF09</a>,
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#restri">RD01 - Restrições de design</a>,
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/#usa">RNFR09 - Usabilidade</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Brainstorming/#bs21">BS21</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – BS21. O requisito originou-se da técnica de Brainstorming.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito garante uma experiência de uso mais agradável e acessível.<br>
        Agregação – O requisito será alocado no Módulo de Interface.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## RNF10 E054
<details>
  <summary>RNF10 - Carregamento rápido das páginas</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Carregamento rápido das páginas</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td>
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF10</a>,
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#desempenho">US03 - Desempenho</a>,
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#suportabilidade">RNF10 - Suportabilidade</a>,
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/especifica%C3%A7%C3%A3o-suplementar/#requi">RF03 E RF04 - Requisitos físicos</a>,
      <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/#desempenho">RNFR10 - Desempenho e eficiência</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-nao-funcionais">IS08</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – IS08. O requisito originou-se da técnica de Introspecção.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito melhora a experiência do usuário ao reduzir o tempo de espera.<br>
        Agregação – O requisito será alocado no Módulo de Desempenho.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Gabriel Mendes](https://github.com/gbevi), 2025.</p></font>

## RNF11 E55
<details>
  <summary>RNF11 - Acessibilidade para diferentes perfis de usuários</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Acessibilidade para diferentes perfis de usuários</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF11</a>,

        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Introspecção/#req-nao-funcionais">IS09</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – IS09. Originado por introspecção.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Contribui para a usabilidade e inclusão
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>


## RNF12 E56
<details>
  <summary>RNF12 - Explicações acessíveis sobre siglas (ex: RENAVAM)</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Explicações acessíveis sobre siglas (ex: RENAVAM)</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF12</a>,

        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/glossario">GL05</a>

      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – GLO05. Originado do glossário.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Melhora a compreensão do usuário sobre termos técnicos
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>


## RNF13 E57
<details>
  <summary>RNF13 - Texto com fontes ajustáveis e botões grandes</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Texto com fontes ajustáveis e botões grandes</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF13</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO07</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. Originado da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Reforça a acessibilidade para idosos e pessoas com baixa visão
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Maria Eduarda](https://github.com/maaduh), 2025.</p></font>

## RNF14 E58
<details>
  <summary>RNF14 - Interface adaptada para idosos e iniciantes</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Texto com fontes ajustáveis e botões grandes</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF14</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO-RNF05	</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/#usa">NFR-Usabilidade	</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Satisfação - Originado da técnica de Storytelling de Olavo e Marina.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – O requisito busca atender às expectativas dos usuários com pouca familiaridade digital, oferecendo uma interface intuitiva, com ícones maiores, linguagem simplificada e menos passos por tarefa.<br>
        Agregação – O requisito será refletido em todos os módulos principais, como Consultas e Serviços, influenciando diretamente o design geral do aplicativo.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>


## RNF15 E59
<details>
  <summary>RNF15 - Aplicativo leve e com baixo consumo de dados</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Aplicativo leve que não consuma muita memória do dispositivo do usuário</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF15</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO-RNF06	</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/#desempenho">NFR-Desempenho	</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Recurso - Originado da técnica de Storytelling de Diego.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Recurso – O requisito orienta a equipe a otimizar os recursos do aplicativo, reduzindo tamanho dos pacotes, compressão de imagens e evitando requisições desnecessárias.<br>
        Responsabilidade – Define a responsabilidade da equipe de desenvolvimento em aplicar práticas de performance e eficiência energética. <br>
        Agregação – Será observado de forma transversal em todos os módulos, especialmente em serviços que consomem imagens e dados.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>

## RNF16 E60
<details>
  <summary>RNF16 - Tempo de resposta rápido</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Aplicativo rápido com tempo de respota inferior a 2 segundos para às atividades</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF16</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO-RNF02	</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/modelagem/Agil/NfrFrameworkd/#desempenho">NFR-Desempenho	</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Recurso - Originado da técnica de Storytelling de Diego.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Recurso – O requisito orienta a equipe a otimizar os recursos do aplicativo, reduzindo tamanho dos pacotes, compressão de imagens e evitando requisições desnecessárias.<br>
        Responsabilidade – Define a responsabilidade da equipe de desenvolvimento em aplicar práticas de performance e eficiência energética.<br>
        Agregação – Será observado de forma transversal em todos os módulos, especialmente em serviços que consomem imagens e dados.
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Pedro Camilo](https://github.com/PedrooCamilo), 2025.</p></font>

## RNF17 E61
<details>
  <summary>RNF17 - Feedback visual e sonoro</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Feedback visual e sonoro nas interações do usuário</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF17</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO2.09</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. Originado da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Reforça a acessibilidade para idosos e pessoas com baixa visão
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RNF18 E62
<details>
  <summary>RNF18 - Disponibilidade do sistema 24/7</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Disponibilidade do sistea24/7</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF18</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO2.010</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. Originado da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Reforça a Disponibilidade do sistema
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RNF19 E63
<details>
  <summary>RNF19 - Recuperação de falhas e continuidade da navegação</summary>

  <table>
    <tr>
      <th>Item</th>
      <th>Descrição</th>
    </tr>
    <tr>
      <td><strong>Descrição do requisito</strong></td>
      <td>Confiabilidade: recuperação de falhas e continuidade da navegação</td>
    </tr>
    <tr>
      <td><strong>Categoria</strong></td>
      <td>Requisito Não Funcional</td>
    </tr>
    <tr>
      <td><strong>Elementos</strong></td>
      <td><br>
              <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF19</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO2.08</a>
      </td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from</strong></td>
      <td>Agregação – Storytelling. Originado da técnica de Storytelling.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from</strong></td>
      <td>
        Satisfação – Reforça a confiabilidade do sistema
      </td>
    </tr>
    <tr>
      <td><strong>Print</strong></td>
      <td>Imagem</td>
    </tr>
  </table>
</details>
<font size="3"><p style="text-align: center">Autor: [Eric Akio](https://github.com/eric-kingu), 2025.</p></font>

## RNF20 E64
<details>
  <summary>RNF20 - Interface com poucos elementos por tela</summary>

  <table>
    <tr><th>Item</th><th>Descrição</th></tr>
    <tr><td><strong>Descrição do requisito</strong></td><td>Interface com poucos elementos por tela para facilitar leitura</td></tr>
    <tr><td><strong>Categoria</strong></td><td>Usabilidade</td></tr>
    <tr><td><strong>Elementos</strong></td><td>
    <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicita%C3%A7%C3%A3o/Tecnicas-de-elecita%C3%A7%C3%A3o/requisitos-elicitados/#req-nao-funcionais">RNF20</a>,
        <a href="https://requisitos-de-software.github.io/2025.1-DetranDF/Elicitação/Tecnicas-de-elecitação/Storytelling">STO2.08</a></td></tr>
    <tr><td><strong>Elos Backward-from</strong></td><td>Agregação – Storytelling de usuários (Olavo). Surgiu de relatos de dificuldade de leitura em telas sobrecarregadas.</td></tr>
    <tr><td><strong>Elos Forward-from</strong></td><td>Satisfação – aumenta a legibilidade e reduz a carga cognitiva.<br>Agregação – aplicado em todas as telas, regido pelo Guia de UI/UX.</td></tr>
    <tr><td><strong>Print</strong></td><td>Imagem</td></tr>
  </table>
</details>

<font size="3"><p style="text-align: center">Autor: [Luiz Bessa](https://github.com/lfelipebessa), 2025.</p></font>

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 31/05/2025 | criação do documento |  [Giovana Barbosa](https://github.com/gio221)   |[Gabriel Mendes](https://github.com/gbevi)   |
|  1.1   | 05/06/2025| introdução, objetiva. metodologia, e template da rastreabilidade |  [Giovana Barbosa](https://github.com/gio221)   | [Gabriel Mendes](https://github.com/gbevi)  |
|  1.2   | 05/06/2025| E05 a 10, E045 e E048|  [Giovana Barbosa](https://github.com/gio221)   | [Gabriel Mendes](https://github.com/gbevi)  |
|  1.3   | 07/06/2025 | E17 a 22, E052 e E054 |  [Gabriel Mendes](https://github.com/gbevi)   | [Maria Eduarda](https://github.com/maaduh)  |
|  1.4   | 07/06/2025 | adicionei RF11 a RF16  |  [João Lobo](https://github.com/joaolobo10)   | [Maria Eduarda](https://github.com/maaduh)  |
|  1.5   | 07/06/2025 | adicionei RNF05 a RNF7  |  [João Lobo](https://github.com/joaolobo10)   |  [Maria Eduarda](https://github.com/maaduh) |
|  1.6   | 07/06/2025 | adicionei RNF11 a RNF13 e RF 23 a RF 28  |  [Maria Eduarda](https://github.com/maaduh)  | [Eric Akio](https://github.com/eric-kingu) |
|  1.7   | 07/06/2025 | adicionei RNF17 a RNF19 e RF 35 a RF 41  | [Eric Akio](https://github.com/eric-kingu) |[Pedro Camilo](https://github.com/PedrooCamilo)  |
|  1.8   | 08/06/2025 | adicionei RNF14 a RNF16 e RF 29 a RF 34  | [Pedro Camilo](https://github.com/PedrooCamilo) | [Luiz Bessa](https://github.com/lfelipebessa) |
|  1.9   | 08/06/2025 | adicionei RNF20 e RF 01 a RF 04 e 42 a 44  | [Luiz Bessa](https://github.com/lfelipebessa) | [Giovana Barbosa](https://github.com/gio221)   |
|  2.0   | 08/06/2025 | Consertei print da funcionalidade RF15  | [João Lobo](https://github.com/joaolobo10) |   [Giovana Barbosa](https://github.com/gio221)  |
|  2.1   | 16/06/2025 | Adicionando imagens do protótipo e do aplicativo das quais já estavam implementadas  | [Luiz Bessa](https://github.com/lfelipebessa) | [Giovana Barbosa](https://github.com/gio221) |
|  2.2   | 16/06/2025 | Adicionando imagens do protótipo RF14 e RF16, em que não estavam implementados   | [João Lobo](https://github.com/joaolobo10) | [Eric Akio](https://github.com/eric-kingu) |
| 2.3 | 22/06/2025 | Adicionando imagens do protótipo RF40 e RF41 | [Eric Akio](https://github.com/eric-kingu) |  |