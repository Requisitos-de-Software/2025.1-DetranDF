# Introdução
Nessa artefato vamos fazer a analise de documentos do app Detran- DF

De acordo com Vazquez [1], para identificar os termos candidatos ao glossário, deve-se prestar atenção a termos:

- Únicos para o domínio;
- Com mais de uma definição;
- Com definição distinta do senso comum;
- Com definições não intuitivas;
- Técnicos do negócio;
- Abreviações e siglas;
- Sinônimos e antônimos.

# Objetivo
Esse artefato tem como objetivo documentar o glossário do app detran-df

# Glossário
Para uma maior compreensão do aplicativo DETRAN-DF, foram elencados termos relativos ao domínio de trânsito e serviços veiculares, representados na Tabela 1. Muitos termos são siglas ou jargões técnicos que podem gerar dúvidas para usuários leigos.

| Termo                    | Definição |
|--------------------------|----------|
| **CNH**                     | Carteira Nacional de Habilitação. Documento que autoriza o cidadão a conduzir veículos automotores. |
| **CRLV**                    | Certificado de Registro e Licenciamento de Veículo. Documento que comprova que o veículo está licenciado. |
| **RENAVAM**                 | Registro Nacional de Veículos Automotores. Número único que identifica cada veículo no país. |
| **IPVA**                    | Imposto sobre a Propriedade de Veículos Automotores. Tributo estadual obrigatório. |
| **Licenciamento**           | Processo de renovação anual do CRLV mediante pagamento de taxas obrigatórias. |
| **Pontuação**               | Acúmulo de infrações cometidas pelo condutor, que pode levar à suspensão da CNH. |
| **Autuação**                | Registro formal de uma infração de trânsito, anterior à multa. |
| **Recurso de Multa**        | Procedimento pelo qual o condutor contesta uma infração de trânsito. |
| **Agendamento**             | Sistema para marcar atendimento presencial nos postos do DETRAN. |
| **Prova teórica**           | Exame que avalia o conhecimento do candidato à CNH sobre legislação de trânsito. |
| **Prova prática**           | Exame de direção veicular para obtenção da CNH. |
| **Segunda via**             | Solicitação de reemissão de documentos (como CNH ou CRLV) em caso de perda, furto ou danificação. |
| **Processo de Habilitação** | Conjunto de etapas necessárias para obter a CNH: exames médicos, aulas, provas e emissão do documento. |
| **AIT**                     | Auto de Infração de Trânsito. Documento que formaliza a infração cometida. |
| **Gravame**                 | Registro de restrição financeira sobre o veículo, como alienação fiduciária. |
| **Transferência de veículo** | Procedimento de mudança de propriedade de um veículo junto ao DETRAN. |
| **Penalidade**              | Sanção aplicada ao condutor infrator, como multa ou suspensão da CNH. |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

**Tabela 1: Glossário dos termos do app DETRAN-DF (Fonte: autor, 2025).**

## Requisitos Elicitados

Após o levantamento e definição dos termos do glossário, foi possível identificar requisitos funcionais e não funcionais associados à compreensão e utilização dos serviços digitais oferecidos pelo aplicativo DETRAN-DF. Esses requisitos estão listados na Tabela 2.

<a id="req-funcionais"></a>

| Identificador | Requisito                                                                 | Tipo  |
|---------------|---------------------------------------------------------------------------|-------|
| **GLO01**         | Deve ser possível consultar a pontuação da CNH diretamente no aplicativo. | RF    |
| **GLO02**         | O aplicativo deve permitir o agendamento de serviços presenciais.         | RF    |
| **GLO03**         | O sistema deve exibir o status do licenciamento e do IPVA do veículo.     | RF    |
| **GLO04**         | O usuário deve poder gerar a segunda via da CNH e CRLV digitalmente.      | RF    |
| **GLO05**         | O app deve apresentar explicações acessíveis sobre siglas como RENAVAM.   | RNF   |
| **GLO06**         | O sistema deve garantir a segurança dos dados pessoais e veiculares.      | RNF   |

<font size="3"><p style="text-align: center">Fonte: [Giovana Barbosa](https://github.com/gio221) , 2025.</p></font>

**Tabela 2: Requisitos elicitados a partir do Glossário (Fonte: autor, 2025).**

## Bibliografia 
> 1. [Engenharia de requisitos](https://aprender3.unb.br/pluginfile.php/3096085/mod_resource/content/4/Elicitacao%20de%20Req%202.pdf)

## Histórico de versões

| Versão |    Data    |                           Descrição                            |                    Autor                     |                   Revisor                    |
| :----: | :--------: | :------------------------------------------------------------: | :--------: | :--------: | 
|  1.0   | 01/05/2025 | Início da documentação, glossario | [Giovana Barbosa ](https://github.com/gio221) | [Gabriel Dantas](https://github.com/gbevi)|
|  1.2  | 07/06/2025 | adição de anchors nas tabelas | [Gabriel Mendes](https://github.com/gbevi)       |                                           | 
