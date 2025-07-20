---
title: "Early Exercise of Options"
categories:
  - Option Pricing
tags:
  - Option Pricing
  - Binomial Model
---

## Introduction

Em Merton (1973) [[Merton_TheoryRationalOptionPricing]](#1), conclui-se que, exceto nos momentos imediatamente anteriores ao vencimento ou ao pagamento de dividendos, não é racional exercer uma opção de compra antecipadamente.
O objetivo deste trabalho é aprofundar essa conclusão e estendê-la ao caso das opções de venda. Adicionalmente, busca-se compreender em quais cenários o exercício antecipado pode eventualmente ser justificável.

## Revisão da Literatura

### Options, Futures and Other Derivatives - John Hull 

Afim de se criar a intuição sobre o problema, utiliza-se um exemplo encontrado em \cite{Hull}. Nele, há uma opção de compra Americana ITM, que podemos sem perda de generalidade assumir que o strike seja R\$ 40.00 e o preço spot da ação é de R\$ 70.00. Aqui,
é importante apenas que a ação não pague dividendos.

Agora, iremos dividir o cenário de acordo com a intenção do investidor:

- O Investidor acredita que a ação está supervalorizada e não deseja manter a ação em sua carteira;
- O Investidor acredita que o valor da ação é devido e deseja manter a ação em sua carteira;

No primeiro caso. A venda da opção, que possui o valor intrínseco e o valor do tempo, renderá um payoff superior ao investidor, do que  A venda da opção, que possui o valor intrínseco e o valor do tempo, renderá um payoff superior ao investidor, do que  A venda da opção, que possui o valor intrínseco e o valor do tempo, renderá um payoff superior ao investidor, do que  A venda da opção, que possui o valor intrínseco e o valor do tempo, renderá um payoff superior ao investidor, do que 
o exercício da opção.
Já no segundo caso, o custo de aquisição do ativo se mantém constante através da opção, assim, faz sentido postergar ao máximo o dispêndio. Dessa forma, caso a opção apresente uma rentabilidade positiva no período, o
investidor receberá a rentabilidade da ação acrescida da taxa de juros sob o qual seu capital está aplicado. Já se a ação apresentar uma queda do preço, o investidor terá uma perda limitada no valor da opção, ao invés do valor da ação.


## Header two

### Header three

#### Header four

##### Header five

###### Header six

## References
<a id="Merton_TheoryRationalOptionPricing">[1]</a> 
Merton, Robert C. “Theory of Rational Option Pricing.”
The Bell Journal of Economics and Management Science 4, no. 1 (1973): 141–83.
https://doi.org/10.2307/3003143.Merton_TheoryRationalOptionPricing
