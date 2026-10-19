# Nota do CFO: Introdução Alimentar sem Medo, 14 dias

**Aviso:** todos os custos e o ritmo de vendas são estimativas minhas, sem cotação nem dados de clientes (ver `cfo-sources.md`). O modelo não inclui o trabalho das sócias nem qualquer divisão de resultado com a Dilienda. Confira com uma contadora antes de mexer em dinheiro: o enquadramento (MEI ou outro), o teto de faturamento e os impostos.

## A margem
- Cada venda de R$ 39,90 deixa **R$ 31,22 (78%)** depois das taxas, da reserva de reembolso e da hospedagem. É margem alta porque o produto é digital.
- O ponto de equilíbrio é de **cerca de 8 vendas por mês** (R$ 240 de custos fixos ÷ R$ 31,22). A tabela diz "1 por dia" porque arredonda.
- No ritmo previsto, o ano 1 fecha com **441 vendas, R$ 17,6 mil de faturamento e R$ 10,9 mil de lucro operacional**, antes de qualquer pagamento às sócias.

## O ponto que decide tudo: o custo de trazer cada cliente
O modelo supõe vendas orgânicas, sem anúncio pago. Se o cliente vem de anúncio, o lucro some:
- Custo médio para conquistar cada cliente de **R$ 22 ou menos**: ainda dá lucro no ano 1, depois do investimento inicial (R$ 9,8 mil ÷ 441 vendas).
- Em **R$ 40 por cliente**: prejuízo de cerca de R$ 6,8 mil no ano (441 × R$ 40 = R$ 17,6 mil de anúncio contra R$ 10,9 mil de lucro).
- No teste anterior, R$ 100 de anúncio geraram 1 venda, depois reembolsada. É uma amostra de um, mas fica longe de R$ 22.

Conclusão: com R$ 39,90 e venda única, **o negócio só fecha com canal próprio e barato** (redes da Giovana e da Dilienda, indicação de pediatras, Reels, grupos de mães) ou com um preço e uma escada que paguem mais por cliente.

## Se as sócias quiserem ser pagas
Cálculo feito à mão a partir das entradas, não pela ferramenta: com R$ 3.000 por mês divididos entre as três (R$ 240 de fixos + R$ 3.000 ÷ R$ 31,22), o equilíbrio sobe para **cerca de 104 vendas por mês, 3,5 por dia**. O ano 1 só chega perto disso no fim (o ritmo previsto chega a 57 por mês). Hoje o projeto é um complemento de renda, não um salário.

## Caixa
Para começar: **cerca de R$ 1.050** (página e área de membros, teste de aceitação, anúncios de teste, marca). Recuperados no mês 4 do cenário base.

## Três formas de melhorar o resultado
1. **Preço de R$ 59,90 no lugar de R$ 39,90** (a ferramenta calcula): contribuição de R$ 51,22 e lucro do ano 1 de R$ 19,7 mil contra R$ 10,9 mil, no mesmo volume. O volume provavelmente cai, então o preço precisa ser testado (`/founder-pricing`).
2. **Escada de vendas:** o programa de 14 dias leva ao acesso de 6 meses (R$ 59,90 na hipótese original). Hoje o modelo não inclui essa segunda venda, que é o que melhora o ganho por cliente.
3. **Segurar o custo por cliente** nas redes próprias. Cada R$ 10 a menos por cliente vale R$ 4,4 mil no ano 1 (441 vendas × R$ 10).

## Sensibilidade (da ferramenta)
- Preço R$ 29,90: lucro do ano 1 de R$ 6,5 mil.
- Volume 50% menor: lucro de R$ 4,0 mil.
- Preço 10% menor: R$ 9,1 mil.
- Custos 15% maiores: R$ 10,3 mil.
Nenhum cenário dá prejuízo, desde que não haja anúncio pago e o trabalho das sócias seja de graça.

## Condições do conselho sobre dinheiro
- Preço de pacote de 6 meses em vez de mensalidade: **ainda em aberto**.
- Acordo entre as três sócias sobre percentuais e direitos: **em aberto, e é decisivo**. O modelo não divide nada.
- Meta de decisão (10 pagantes entre 20 famílias): não testada.

## Próximos passos
Rodar `/founder-pricing` (preço e escada) e, depois, o painel com a oferta nova.

---

# Unit economics: Dinda Nutri: Introdução Alimentar sem Medo, 14 dias (valores em R$, ESTIMATIVAS)

Every number below comes from the input file. Nothing is looked up or guessed. Todos os valores de entrada são estimativas.

## One venda do programa

| line | per venda do programa |
| --- | ---: |
| Price | R$39.90 |
| Plataforma de pagamento e checkout (estimativa: 10% + R$ 1,00) | -R$4.99 |
| Reserva para reembolsos (estimativa: 8% das vendas) | -R$3.19 |
| Hospedagem de vídeo e e-mail por cliente (estimativa) | -R$0.50 |
| **Contribution** (what each venda do programa leaves to pay the fixed costs) | **R$31.22** (78%) |

## The margin that matters

Fixed costs: R$240 a month (Plataforma web, domínio e e-mail (estimativa) R$100, Imposto fixo de MEI (estimativa; teto de faturamento anual a conferir) R$80, Ferramentas de edição e design (estimativa) R$60).

- **Break-even: 1 vendas a day.** Below that you lose money every month.
- **Profit margin at your plan** (2 a day): **65%** of every sale, after every cost.
- Capacity: 100 a day.

## Year 1, month by month

| month | vendas a day | revenue | profit | cumulative (after R$1,050 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 0 | R$359 | R$41 | -R$1,009 |
| 2 | 0 | R$598 | R$228 | -R$781 |
| 3 | 1 | R$838 | R$416 | -R$365 |
| 4 | 1 | R$1,077 | R$603 | R$238 |
| 5 | 1 | R$1,317 | R$790 | R$1,028 |
| 6 | 1 | R$1,556 | R$978 | R$2,006 |
| 7 | 1 | R$1,676 | R$1,071 | R$3,077 |
| 8 | 2 | R$1,796 | R$1,165 | R$4,242 |
| 9 | 2 | R$1,915 | R$1,259 | R$5,500 |
| 10 | 2 | R$2,035 | R$1,352 | R$6,853 |
| 11 | 2 | R$2,155 | R$1,446 | R$8,298 |
| 12 | 2 | R$2,274 | R$1,540 | R$9,838 |

- **Year 1 operating profit: R$10,888** on R$17,596 of revenue.
- After the R$1,050 startup spend: R$9,838.
- Startup money earned back: month 4.
- Cash you need before it pays for itself: **R$1,050**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 65% | 1 | R$10,888 |
| Price -10% | 61% | 1 | R$9,128 |
| Volume -20% | 62% | 1 | R$8,134 |
| Unit costs +15% | 62% | 1 | R$10,314 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a quote or invoice.
