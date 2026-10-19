# Preço: Introdução Alimentar sem Medo, 14 dias

**O que falta:** o painel de consumidoras não rodou, então não há faixa de preço de Van Westendorp. Também não achei o preço dos concorrentes: as páginas das lojas de aplicativos do BLW Brasil e do Mundo BLW falam em plano mensal e anual, mas não mostram valores nas buscas. Valores a conferir direto nas lojas (Google Play e App Store) e no Instagram deles. Nada aqui é faixa aceita de mercado: é conta de margem e volume.

Fontes: [BLW Brasil na App Store](https://apps.apple.com/BR/app/id1478347645) (gratuito com compras dentro do app, planos mensal e anual, premium com mais de 650 receitas).

## A ideia: preço baixo para ganhar adesão

Faz sentido como porta de entrada, com duas ressalvas dos números:

| Preço | Contribuição por venda | Equilíbrio (vendas/mês) | Lucro ano 1 com 441 vendas | Vendas para igualar o lucro de R$ 39,90 | Custo máx. por cliente |
|---|---:|---:|---:|---:|---:|
| R$ 14,90 | R$ 10,72 | 22 | R$ 1,8 mil | 1.284 (2,9x) | R$ 10,70 |
| R$ 19,90 | R$ 14,82 | 16 | R$ 3,7 mil | 929 (2,1x) | R$ 14,80 |
| R$ 24,90 | R$ 18,92 | 13 | R$ 5,5 mil | 728 (1,65x) | R$ 18,90 |
| R$ 29,90 | R$ 23,02 | 10 | R$ 7,3 mil | 598 (1,36x) | R$ 23,00 |
| R$ 39,90 | R$ 31,22 | 8 | R$ 10,9 mil | 441 (1x) | R$ 31,20 |
| R$ 59,90 | R$ 47,62 | 5 | R$ 18,1 mil | 289 (0,66x) | R$ 47,60 |

Calculado com a ferramenta do CFO, com a taxa de pagamento (10% + R$ 1) e a reserva de reembolso (8%) escaladas com o preço. Todas as taxas são estimativas.

1. **Preço baixo exige muito mais vendas.** Em R$ 24,90 é preciso vender 65% a mais para ganhar o mesmo; em R$ 19,90, mais que o dobro.
2. **Anúncio deixa de ser possível.** Em R$ 24,90 o custo máximo por cliente é R$ 18,90, e o teste anterior custou R$ 100. A adesão tem que vir de canal próprio.
3. **Conteúdo de saúde barato demais pode passar desconfiança** ("será que é confiável?"). É hipótese minha, sem dado. O painel e as conversas com mães devem medir isso.

## Recomendação

**Preço de entrada: R$ 24,90**, com R$ 19,90 só na abertura. Fica abaixo de R$ 30, que costuma ser decisão rápida, e ainda deixa margem de 76%. R$ 14,90 não compensa a conta.

### Escada

| Degrau | O quê | Preço | Por que subir |
|---|---|---|---|
| Grátis | Guia "Primeira semana da introdução alimentar sem medo" | R$ 0 | Capta o contato e prova o jeito da Giovana |
| Entrada | Programa "Introdução Alimentar sem Medo: 14 dias" | R$ 24,90 | Resolve o medo e a rotina |
| Melhor | Programa + 6 meses de acesso (biblioteca, novos cardápios, "O que preparar hoje?") | R$ 59,90 | Oferecido no checkout e no fim do programa. Para o bebê que ainda vai ampliar a dieta |
| Topo | Consulta com a Dilienda | a definir por ela | Caso individual |

A segunda venda é o que fecha a conta do preço baixo. Exemplo (hipótese, não previsão): se 20% das compradoras levassem o pacote de 6 meses pagando R$ 35 a mais, cada venda renderia em média cerca de R$ 7 a mais (20% × R$ 35, antes das taxas). Isso cobre parte da diferença entre R$ 24,90 e R$ 39,90.

### Oferta de abertura
R$ 19,90 para as 30 primeiras famílias, com data de término e vagas verdadeiras, em troca de feedback. Depois volta a R$ 24,90. Não use "de R$ 39,90 por R$ 24,90": esse preço nunca foi cobrado, então seria uma âncora falsa. Depoimentos e fotos de crianças precisam de autorização e de conferência das regras do conselho de nutrição pela Dilienda.

## O que testar com compradoras de verdade
Duas páginas de venda (ou duas pré-vendas) para grupos parecidos: **R$ 24,90 contra R$ 39,90**, com a mesma oferta.
- Regra de decisão: R$ 24,90 só ganha se converter **pelo menos 65% mais** que R$ 39,90. Exemplo: se R$ 39,90 converte 3%, R$ 24,90 precisa converter 5% ou mais.
- Métrica extra: parcela que leva o pacote de 6 meses.
- Quantidade mínima: o suficiente para ver diferença; com poucas vendas o resultado é ruído. Defina o tamanho antes de começar.

## Objeções de preço
Sem o painel não há citações. Dúvidas esperadas, do perfil: "tem muita coisa grátis", "é caro para poucos meses de uso", "já tenho aplicativo ou e-book". O marketing responde a elas com a prova de aceitação e a rotina de freezer.

## Se o preço mudar
Atualizar `founder/numbers.json` (preço, taxa e reserva de reembolso, e o ritmo de vendas) e rodar `/founder-cfo` de novo.

---

# Atualização com o painel de 20 compradoras

**Primeira rodada (oferta sem CRN e sem amostra):** faixa de R$ 9 a R$ 40, ponto de indiferença em R$ 19.
**Segunda rodada (com CRN e amostra grátis):** faixa de **R$ 9 a R$ 49**, ponto de indiferença em **R$ 19**, caro demais acima de cerca de R$ 49. R$ 24,90 e R$ 39,90 ficam dentro da faixa. (A ferramenta imprime "$", mas os valores são em reais.)

- O limite de "caro demais" subiu de R$ 40 para R$ 49 quando a oferta ganhou nome da nutricionista, CRN e amostra. Isso sugere que confiança sustenta preço mais alto. É indício de um painel simulado, não prova.
- O ponto de indiferença, perto de R$ 19, não mudou. Por isso a abertura de R$ 19,90 continua fazendo sentido.
- **Recomendação mantida:** entrada em R$ 24,90, abertura em R$ 19,90 para as 30 primeiras famílias, e teste de R$ 24,90 contra R$ 39,90 com famílias de fora. Com o limite subindo, vale testar com mais atenção o R$ 39,90, que dá cerca de R$ 7 a mais por venda e exige 35% menos vendas para o mesmo lucro.
- O painel não valida o preço baixo como motor de adesão: a recusa por preço quase sumiu, e a recusa que restou é de confiança e de hábito.
