---
title: "Early Exercise of Options"
categories:
  - Option Pricing
tags:
  - Option Pricing
  - Binomial Model
---

## Introduction

Em Merton (1973) [[TheoryRationalOptionPricing]](#1), conclui-se que, exceto nos momentos imediatamente anteriores ao vencimento ou ao pagamento de dividendos, não é racional exercer uma opção de compra antecipadamente.
O objetivo deste trabalho é aprofundar essa conclusão e estendê-la ao caso das opções de venda. Adicionalmente, busca-se compreender em quais cenários o exercício antecipado pode eventualmente ser justificável.

## Revisão da Literatura

### Options, Futures and Other Derivatives - John Hull 

Afim de se criar a intuição sobre o problema, utiliza-se um exemplo encontrado em [[Options, Futures and Other Derivatives - John Hull]](#2). Nele, há uma opção de compra Americana ITM, que podemos sem perda de generalidade assumir que o strike seja R$ 40.00 e o preço spot da ação é de R$ 70.00. Aqui,
é importante apenas que a ação não pague dividendos.

Agora, iremos dividir o cenário de acordo com a intenção do investidor:

- O Investidor acredita que a ação está supervalorizada e não deseja manter a ação em sua carteira;
- O Investidor acredita que o valor da ação é devido e deseja manter a ação em sua carteira;

No primeiro caso, a venda da opção, que possui o valor intrínseco e o valor do tempo, renderá um payoff superior ao investidor, a venda da opção, que possui o valor intrínseco e o valor do tempo, renderá um payoff superior ao investidor, do que  A venda da opção, que possui o valor intrínseco e o valor do tempo, renderá um payoff superior ao investidor, do que o exercício da opção. \n
Já no segundo caso, o custo de aquisição do ativo se mantém constante através da opção, assim, faz sentido postergar ao máximo o dispêndio. Dessa forma, caso a opção apresente uma rentabilidade positiva no período, o investidor receberá a rentabilidade da ação acrescida da taxa de juros sob o qual seu capital está aplicado. Já se a ação apresentar uma queda do preço, o investidor terá uma perda limitada no valor da opção, ao invés do valor da ação.


### Option Pricing: A Simplified Approach - Cox, John C. , Stephen A. Ross and Mark Rubinstein

A partir do trabalho [[Option Pricing: A simplified approach]](#3), é possível encontrar os resultados previamente apresentados via modelo binomial. Dessa forma, primeiro, introduzimos o modelo binomial.

#### Modelo Binomial

O Modelo Binomial refere-se não a modelagem da opção, mas do ativo subjacente a qual a opção se refere. Nesse caso, utilizaremos uma ação, em que, via modelo binomial, apresentará em períodos discretos, um possível aumento $u$ com probabilidade $p$ ou uma queda $d$ com probabilidade $1-p$.
Assim, denotando o preço da ação por $S$, temos dois cenários: $uS$ com probabilidade $p$ ou $dS$ com probabilidade $1-p$. Dai, o nome modelo binomial.


### Theory of Rational Option Pricing - Merton 

## References

<a id="1">[Theory of Rational Option Pricing]</a> 
Merton, Robert C. “Theory of Rational Option Pricing.”
The Bell Journal of Economics and Management Science 4, no. 1 (1973): 141–83.
https://doi.org/10.2307/3003143.Merton_TheoryRationalOptionPricing 
\n
<a id="2">[Options, Futures and Other Derivatives - John Hull]</a>
Hull, John C. 2017. Options, Futures, and Other Derivatives. 9th ed. Boston: Pearson Education. 
https://books.google.com.br/books?id=yfr0DQAAQBAJ.3.
\n
<a id="3">[Option Pricing: A simplified approach]</a>
Cox, John C., Stephen A. Ross, and Mark Rubinstein. 1979. “Option Pricing: A Simplified Approach.”
Journal of Financial Economics 7 (3): 229–63.
https://doi.org/10.1016/0304-405X(79)90015-1.