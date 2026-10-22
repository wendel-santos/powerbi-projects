# Dashboard de Fluxo de Caixa (Power BI)

Dashboard para acompanhar entradas, saídas e saldo ao longo do tempo, e entender para onde o dinheiro vai.

## Pergunta de negócio

Para onde vai o caixa da empresa e como o saldo evolui mês a mês?

## Dados

Projeto de estudo com dados de exemplo, cobrindo o período de 01/01/2019 a 31/12/2021. Os dados são fictícios, não representam nenhuma empresa real.

## Principais indicadores

| Indicador | Valor |
|---|---|
| Entradas | R$ 3,92 Mi |
| Saídas | R$ 2,06 Mi |
| Saldo | R$ 1,86 Mi |
| Margem de caixa (saldo ÷ entradas) | 47,41% |

> A margem exibida é de caixa. Ela não equivale à margem de lucro contábil, porque impostos, despesas financeiras e retiradas de sócios entram nas saídas.

## O que os dados mostram

- **Composição das saídas:** produtos (31%), despesas administrativas (23%), pessoal (19%), impostos (11%), despesas financeiras (11%) e retirada de sócios (4%).
- **Despesa administrativa maior que a de pessoal:** R$ 477,7 mil contra R$ 393,7 mil, o que equivale a cerca de 75% do gasto com produtos.
- **Meses negativos:** abril e julho fecharam com saldo negativo (-R$ 0,11 Mi cada) no gráfico mensal.

## Funcionalidades

- Filtro por período
- Filtro por centro de custos (Administrativo, Comercial, Financeiro, Marketing e Operacional)
- Gráfico em cascata com a evolução do saldo mensal
- Despesas por tipo
- Tabela de detalhamento por nota fiscal, centro de custos e local

## Prints

![Visão geral](img/visao-geral.png)

![Tabela de notas](img/tabela-notas.png)

![Filtros](img/filtros.png)

## Ferramentas

Power BI Desktop

## Próximas melhorias

- Padronizar as unidades dos indicadores (R$ ou Mi)
- Substituir o indicador duplicado de saldo por melhor e pior mês
- Incluir meta ou comparativo para a margem de caixa
- Validar a agregação mensal quando o filtro cobre mais de um ano

## Autor

**Wendel Santos** · Analista de Dados · Business Intelligence

[LinkedIn](https://www.linkedin.com/in/wendel-santos-analista/) · [GitHub](https://github.com/wendel-santos)
