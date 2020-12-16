Para introduzirmos o conceito de **combinação com repetição**, é importante relembrar a definição formal de [combinação simples](https://www.infoescola.com/matematica/combinacao-simples/).

Considere _n_ objetos diferentes. Se tratarmos da contagem do número de maneiras de escolher _k_ dentre esses _n_ objetos sem considerarmos a ordem, então criamos uma combinação destes elementos sem repetição. A fórmula para obter esta combinação é dada por:

$C_{n,k}=\frac{n!}{k!(n-k)!}$

Por exemplo, imagine o seguinte cenário: Estamos organizando um campeonato de xadrez com 12 participantes. De quantas maneiras possíveis podemos criar as duplas para disputar a primeira partida? Este problema pode ser solucionado calculando a combinação de 12 jogadores organizados de 2 em 2. Que nos traz:

$C_{12, 2}=\frac{12!}{2!(12-2)!}=\frac{12!}{2!\cdot 10!}=\frac{12\cdot 11\cdot 10!}{2!\cdot 10!}=\frac{12\cdot 11}{2}=66$

Temos então 66 formas diferentes de organizar as duplas a partir dos 12 primeiros participantes. Há uma outra notação para a operação de combinação, ou coeficiente binomial, que é dada por:

$C_{n,k}=\binom{n}{k}=\frac{n!}{k!(n-k)!}$

Agora, quando a ordem dos elementos _pode ser repetida_, então tratamos de uma **combinação com repetição**. A fórmula será dada, neste caso, por:

$C_{n+k-1,k}=\binom{n+k-1}{k}=\frac{(n+k-1)!}{k!(n+k-1-k)!}$

Ou seja:

$C_{n+k-1,k}=\frac{(n+k-1)!}{k!(n-1)!}$ [^1]

[^1]: Qual a fórmula para combinações com repetição?

Vejamos agora um exemplo aplicado:

Exemplo 1) Supondo que você queira comprar um sorvete com 4 bolas em uma sorveteria que possui 3 sabores disponíveis: chocolate, baunilha e morango. De quantos modos diferentes você pode fazer esta compra?

Note que nesta combinação, é possível repetir a ordem de dois ou mais sabores, assim tratando de uma combinação com repetição. Se temos 3 sabores disponíveis e queremos uma combinação para 4 bolas, pela fórmula obtemos:

$C_{n+k-1,k}=\frac{(n+k-1)!}{k!(n-1)!}$

$C_{3+4-1,4}=\frac{(3+4-1)!}{4!(3-1)!}$

$C_{6,4}=\frac{6!}{4!\cdot 2!}=\frac{6\cdot 5\cdot 4!}{4!\cdot 2!}=\frac{6\cdot 5}{2}=\frac{30}{2}=15$

Logo, temos 15 combinações possíveis para esta compra!

ENEM 2017) Um brinquedo infantil caminhão-cegonha é formado por uma carreta e dez carrinhos nela transportados, conforme a figura.

![](https://www.infoescola.com/wp-content/uploads/2018/07/img_5b5f543601677.png)

No setor de produção da empresa que fabrica esse brinquedo, é feita a pintura de todos os carrinhos para que o aspecto do brinquedo fique mais atraente. São utilizadas as cores: **amarelo, branco, laranja e verde**, e cada carrinho é **pintado apenas com uma cor**. O caminhão-cegonha **deve haver pelo menos um carrinho de cada uma das quatro cores disponíveis**. Mudança de posição dos carrinhos no caminhão-cegonha **não gera um novo modelo do brinquedo**. Com base nessas informações, quantos são os modelos distintos do brinquedo que essa empresa poderá produzir?

Note as palavras em negrito no texto. Pela interpretação da questão percebe-se que ela se trata de uma combinação com repetição. Então, se temos 4 cores disponíveis e 10 carrinhos a ser colocados no brinquedo a questão pode ser solucionada da seguinte maneira:

Pelo exercício, teremos pelo menos um carrinho de cada cor. Então podemos supor que existe uma quantidade (amarelo), (branco), (laranja) e (verde) e mais um de cada, no mínimo. Então podemos dizer:

*   Carrinho amarelo: a+1
*   Carrinho branco: b+1
*   Carrinho laranja: L+1
*   Carrinho verde: v+1

Somando então estas quantidades, sabemos que o total deve ser igual a 10 carrinhos, o que nos leva a:

$a+1+b+1+L+1+v+1=10$

Isolando as variáveis temos que:

$a+b+L+v=10-4$

$a+b+L+v=6$

Ora, perceba que agora temos um cenário onde já sabemos que ao mínimo teremos um carrinho de cada cor, que já ocupa 4 posições no caminhão-cegonha restando apenas 6 posições. Então é necessário pensar que devemos organizar agora 4 carrinhos em 6 posições considerando a repetição. O que nos leva a formula:

$C_{n+k-1,k}=\frac{(n+k-1)!}{k!(n-1)!}$

$C_{4+6-1,6}=\frac{(4+6-1)!}{6!(4-1)!}$

$C_{9,6}=\frac{9!}{6!\cdot 3!}=84$

## Next
[[10 01 2021]]
## Processo:
Created: [[06-11-2020]]
*+2 *  *Ctrl+0*
- [x] Molho  

*+7*  *Ctrl+1

- [x] Primeira 

*+10*  *Ctrl+2*

- [x] Segunda

*+15*  *Ctrl+3*

- [x] Terceira 

*+30*  *Ctrl+4*

- [ ] Quarta 

*+60*  *Ctrl+5*

- [ ] Quinta 

*+120*  *Ctrl+6*

- [ ] Sexta 

*+240*  *Ctrl+7*


