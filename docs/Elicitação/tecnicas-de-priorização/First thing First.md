## Introdução
<p align="justify">
Em um cenário cada vez mais digital e dinâmico, a organização das demandas de desenvolvimento de produtos digitais é essencial para garantir eficiência, usabilidade e entrega de valor ao usuário. O aplicativo Detran Digital do Distrito Federal reúne diversos serviços voltados para motoristas e proprietários de veículos, exigindo uma gestão eficaz de prioridades para evolução e manutenção de suas funcionalidades. Neste contexto, a técnica de priorização "First Things First", baseada no conceito da Matriz de Eisenhower, se apresenta como uma ferramenta poderosa para classificar tarefas conforme sua urgência e importância, promovendo decisões mais estratégicas no planejamento do produto.
</p>

## Objetivos
<p align="justify">

- Compreender a técnica "First Things First" e sua aplicação no gerenciamento de prioridades.
- Analisar as funcionalidades do aplicativo Detran Digital DF sob a ótica da priorização estratégica.
- Classificar essas funcionalidades segundo os quatro quadrantes da matriz de urgência/importância.
- Propor um plano de ação com foco em eficiência e melhoria contínua da experiência do usuário.

</p>

## Metodologia

**Critérios atribuídos:**

- **Benefício** e **Penalidade**: definidos pela persona.
- **Custo** e **Risco**: definidos pelo desenvolvedor.

### Fórmulas Utilizadas

- `Valor Total = (Benefício * Peso) + (Penalidade * Peso)`
- `Valor (%) = (Valor Total / Soma dos Valores Totais) * 100`
- `Custo (%) = (Custo / Soma dos Custos) * 100`
- `Risco (%) = (Risco / Soma dos Riscos) * 100`
- `Prioridade = (Valor (%) / (Custo (%) * Peso + Risco (%) * Peso)) * 100`

### Pesos Relativos

| Critério    | Peso |
|-------------|------|
| Benefício   | 8    |
| Penalidade  | 5    |
| Custo       | 7    |
| Risco       | 7    |

## Tabela de Priorização – First Things First 

| Código | Descrição                                                | Implementado | B | P | C | R | V. Total | V. (%) | C. (%) | R. (%) | Prioridade |
|--------|-----------------------------------------------------------|--------------|---|---|---|---|----------|--------|--------|--------|------------|
| F01    | Agendamento de serviços presenciais                      | Não          | 9 | 9 | 3 | 3 | 117      | 18,0%  | 10,3%  | 9,4%   | 41,26      |
| F02    | Geração de guias de pagamento                            | Não          | 9 | 8 | 3 | 2 | 111      | 17,0%  | 10,3%  | 6,3%   | 47,45      |
| F03    | Acesso à CNH digital e CRLV‑e                            | Sim          | 8 | 7 | 2 | 2 | 101      | 15,5%  | 6,9%   | 6,3%   | 49,77      |
| F04    | Notificações sobre vencimentos e multas                  | Não          | 8 | 6 | 2 | 3 | 94       | 14,4%  | 6,9%   | 9,4%   | 37,15      |
| F05    | Consulta de infrações e pontos da CNH                    | Sim          | 9 | 7 | 3 | 3 | 111      | 17,0%  | 10,3%  | 9,4%   | 39,70      |
| F06    | Agendamento de exames para habilitação                   | Não          | 9 | 9 | 3 | 4 | 117      | 18,0%  | 10,3%  | 12,5%  | 34,76      |
| F07    | Opção de acessibilidade (fonte grande, contraste)        | Não          | 9 | 9 | 5 | 5 | 117      | 18,0%  | 17,2%  | 15,6%  | 27,31      |
| F08    | Consulta ao status de processos administrativos          | Não          | 8 | 6 | 3 | 4 | 94       | 14,4%  | 10,3%  | 12,5%  | 33,51      |
| F09    | Emissão de segunda via de documentos                     | Não          | 8 | 7 | 3 | 3 | 120      | 17,8%  | 10,3%  | 9,4%   | 41,10      |
| F10    | Alteração de endereço da CNH e do veículo                | Não          | 7 | 6 | 4 | 3 | 104      | 15,4%  | 13,8%  | 9,4%   | 34,12      |
| F11    | Pagamento do licenciamento veicular (DPVAT, seguro)      | Não          | 9 | 8 | 3 | 4 | 136      | 20,2%  | 10,3%  | 12,5%  | 45,12      |
| F12    | Consulta de débitos e taxas pendentes                    | Sim          | 9 | 7 | 2 | 3 | 128      | 19,0%  | 6,9%   | 9,4%   | 48,53      |
| F13    | Histórico de infrações e multa por ano                   | Não          | 8 | 6 | 3 | 3 | 112      | 16,6%  | 10,3%  | 9,4%   | 36,20      |
| F14    | Central de ajuda / FAQ integrada                         | Não          | 7 | 7 | 2 | 2 | 96       | 14,2%  | 6,9%   | 6,3%   | 53,45      |
| F15    | Opção de chat/suporte dentro do app                      | Não          | 7 | 6 | 4 | 4 | 104      | 15,4%  | 13,8%  | 12,5%  | 30,68      |
| F16    | Pagamento via cartão ou PIX dentro do app                | Não          | 8 | 7 | 3 | 3 | 120      | 17,8%  | 10,3%  | 9,4%   | 44,55      |
| F17    | Integração com Gov.br (login único)                      | Não          | 9 | 8 | 4 | 5 | 136      | 20,2%  | 13,8%  | 15,6%  | 42,65      |



## Bibliografia

> 1. Aplicativo do DetranDF. Disponível em: Apple Store. Acesso em: 12 abr 2025.

## Histórico de versão

| Versão |    Data    |       Descrição        |                     Autor                      |                  Revisor                   |
| :----: | :--------: | :--------------------: | :--------------------------------------------: | :----------------------------------------: |
|  1.0   | 03/05/2025 | Início da documentação | [Maria Eduarda](https://github.com/maaduh)     |  [Giovana Barbosa ](https://github.com/gio221) |
|  1.1   | 04/05/2025 | correção de erros | [Maria Eduarda](https://github.com/maaduh)     |       [Giovana Barbosa ](https://github.com/gio221) | 
|  1.2   | 20/06/2025 | correção das partes erradas | [Maria Eduarda](https://github.com/maaduh)     |    [Giovana Barbosa ](https://github.com/gio221)      | 