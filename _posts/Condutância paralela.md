# Condutância paralela

Condutância é o inverso da resistência. [^1]

[^1]: O que é a condutância?

A unidade de condutância é o siemens (S). [^2]

[^2]: Qual a unidade de condutância?

Você pode analisar os resistores em paralelo descrevendo cada resistor como uma condutância. 

Em um artigo anterior estudamos [resistores em paralelo](Resistores%20em%20paralelo.md)

![](https://cdn.kastatic.org/ka-perseus-images/f84dc8f7aa0ad09db6897028cfe43d93615e3070.svg)

Derivamos esta equação para combinar os resistores paralelos em um único resistor equivalente,

$\mathrm{R}_{\text {paralela }}=\frac{1}{\left(\frac{1}{\mathrm{R} 1}+\frac{1}{\mathrm{R} 2}+\ldots+\frac{1}{\mathrm{R}_{\mathrm{N}}}\right)}$

Esta é uma expressão bastante complexa, com $1 / \mathrm{R}$ termos incorporados. Há uma maneira alternativa para abordar este problema, utilizando o conceito de *condutância*.

## Condutância

A Lei de Ohm, $v=i \mathrm{R}$, define a resistência como a razão de tensão sobre corrente,

$\mathrm{R}=\frac{v}{i}$

O termo *condutância* é o inverso dessa expressão. É a razão da corrente sobre tensão,

$\mathrm{G}=\frac{i}{v}$

Isto nos dá ainda uma outra maneira de escrever a Lei de Ohm,

$i=v G$ [^3]

[^3]: Como descrever a Lei de Ohm usando a condutância?


A unidade de condutância é o *siemens*, abreviado $S$. Recebe esse nome por ser uma homenagem a Werner von Siemens, fundador da empresa alemã de eletrônica industrial e telecomunicações que leva seu nome. Há um *s* no final do *siemens* mesmo se for singular,$ 1 siemens$. Você pode encontrar referências antigas para condutância especificada em unidades de *mhos*, que é apenas "ohms" soletrado de trás pra frente. Esta unidade não é mais usada.

Usando *condutância* ao invés de *resistência* para o mesmo objeto físico enfatiza um aspecto diferente de seu comportamento. Resistência reduz ou impede o fluxo de corrente, enquanto condutância permite que a corrente passe. Os termos são dois aspectos da mesma ideia.

[\[resistividade e condutividade\]](javascript:void(0))

Um resistor de $100 \Omega$ apresenta a mesma condutância de $\frac{1}{100 \Omega}=0,01 \mathrm{S}$  [^4]

[^4]: Como calcular a condutância usando a resistência?


![](https://cdn.kastatic.org/ka-perseus-images/9314d8633e131f3ae8976087f222a35bfa4dddc7.svg)

## Condutância paralela

Nesta seção iremos repetir a análise de resistores paralelos, mas desta vez, em vez de chamar cada componente de resistor, vamos chamá\-lo de condutância. O resultado para condutância paralela terá uma forte semelhança com resistores em série.

Este é um circuito com condutâncias em paralelo. Vamos analisá\-lo usando a linguagem de condutância e a Lei de Ohm na forma de condutância, $i=v \mathrm{G}$

![](https://cdn.kastatic.org/ka-perseus-images/8c5da88c8c0487fd2e52679c83c2a80cbe977d8c.svg)

O valor da corrente $i$ é uma dada constante. Ainda não sabemos $v$ ou como $i$ se divide em três correntes através das condutâncias.

Duas coisas que sabemos são:

*   As três correntes de condutância somam $i$.
*   Tensão $v$ aparece em todas as três condutâncias.

Sabendo apenas isso e a Lei de Ohm na forma de condutância, podemos escrever essas expressões:

$i=i_{\mathrm{G} 1}+i_{\mathrm{G} 2}+i_{\mathrm{G} 3}$
$i_{\mathrm{G} 1}=v \cdot \mathrm{G} 1 \quad i_{\mathrm{G} 2}=v \cdot \mathrm{G} 2 \quad i_{\mathrm{G} 3}=v \cdot \mathrm{G} 3$

Isso é suficiente para continuar. Combinando as equações:

$i=v \cdot \mathrm{G} 1+v \cdot \mathrm{G} 2+v \cdot \mathrm{G} 3$

Fatorar o termo de tensão e reagrupar os valores de condutância em um só lugar:

$i=v(\mathrm{G} 1+\mathrm{G} 2+\mathrm{G} 3)$

Isto parece com a Lei de Ohm para uma única condutância, com as condutâncias paralelas aparecendo como uma soma.

Concluímos:

*Para as condutâncias em paralelo, a condutância total é a soma das condutâncias individuais.* [^5]

[^5]: Como se calcula a condutância total em paralelo?

Observe o quanto isto parece ser a fórmula para resistores em série. Condutâncias em paralelo são como resistências em série, elas se somam.

### Condutâncias paralelas equivalentes

Podemos imaginar uma nova condutância, equivalente à soma das condutâncias paralelas. É equivalente no sentido de que a mesma tensão aparece.

$\mathrm{G}_{\text {paralela }}=\mathrm{G} 1+\mathrm{G} 2+\mathrm{G} 3$

![](https://cdn.kastatic.org/ka-perseus-images/d661bed34fa2344980911299e079fb11b5b45b27.png)

### Exemplo de condutância

Vamos resolver o mesmo circuito que fizemos para resistores paralelos, mas usando a nova representação.

Este é o circuito com condutâncias, $\mathrm{G}=\frac{1}{\mathrm{R}}$

![](https://cdn.kastatic.org/ka-perseus-images/7e67c138c7b7fc0f2c5f843a4c99d8ab34569031.svg)

Você pode tentar resolver isto sozinho antes de olhar para a resposta. Queremos encontrar a tensão vv v v e as correntes individuais, $i_{\mathrm{G} 1}, i_{\mathrm{G} 2}, \mathrm{e} i_{\mathrm{G} 3}$, usando a forma de condutância da Lei de Ohm, $i=v \mathrm{G}$

**Encontre $v$ e a corrente através das três condutâncias.**
**Mostre que as correntes individuais somam $i$.**

As etapas para uma solução são:

1.  Ache a condutância paralela equivalente $G_{paralela}$
2.  Ache a tensão $v$ usando $i=v \mathrm{G}$
3.  Ache as correntes individuais novamente, usando a Lei de Ohm.
4.  Verifique que a soma das correntes individuais dá o resultado esperado.

$\mathrm{A} G_{\text {paralela}}$ equivalente é a soma dos valores das três condutâncias.
$G_{\text {paralela}}=0,02 \mathrm{S}+0,01 \mathrm{S}+0,002 \mathrm{S}=0,032 \mathrm{S}$
Agora podemos encontrar $v$,
$i_{\mathrm{S}}=v G_{\text {paralela}}$
$100 \mathrm{mA}=v \cdot 0,032 \mathrm{S}$
$v=\frac{100 \mathrm{mA}}{0,032 \mathrm{S}}=3,125 \mathrm{V}$

![](https://cdn.kastatic.org/ka-perseus-images/5a3a7645376d3e8de8b8e9757275000d4de3377d.svg)

Como esperado, isto dá a mesma $v$ que a análise convencional de resistor paralelo.

Agora trabalhe nas correntes individuais,

$i_{\mathrm{G} 1}=v \cdot \mathrm{G} 1=3,125 \mathrm{V} \cdot 0,02 \mathrm{S}=62,50 \mathrm{mA}$
$i_{\mathrm{G} 2}=v \cdot \mathrm{G} 2=3,125 \mathrm{V} \cdot 0,01 \mathrm{S}=31,25 \mathrm{mA}$
$i_{\mathrm{G} 3}=v \cdot \mathrm{G} 3=3,125 \mathrm{V} \cdot 0,02 \mathrm{S}=6,25 \mathrm{mA}$

A solução completa se parece com esta,

![](https://cdn.kastatic.org/ka-perseus-images/de38336c98f6905a89366fa15c37086d02bfbca7.svg)

E termine verificando se a soma das correntes individuais é igual à corrente da fonte,

$62,5 \mathrm{mA}+31,25 \mathrm{mA}+6,25 \mathrm{mA}=100 \mathrm{mA}$ Isso!

- [x] Processo 

## Next
[[20 12 2020]]
## Processo:
Created: [[01-12-2020]]
*+2 *  *Ctrl+0*
- [x] Molho  

*+7*  *Ctrl+1*

- [x] Primeira 

*+10*  *Ctrl+2*

- [ ] Segunda

*+15*  *Ctrl+3*

- [ ] Terceira 

*+30*  *Ctrl+4*

- [ ] Quarta 

*+60*  *Ctrl+5*

- [ ] Quinta 

*+120*  *Ctrl+6*

- [ ] Sexta 

*+240*  *Ctrl+7*