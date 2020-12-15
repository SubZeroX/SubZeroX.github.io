O **determinante** de uma [matriz](https://brasilescola.uol.com.br/matematica/matriz.htm) **possui várias aplicações atualmente**. Utilizamos o determinante para verificar se três pontos estão alinhados no plano cartesiano, para calcular áreas de triângulos, para resolução de sistemas lineares, entre outras aplicações na matemática. O estudo de determinantes **não se limita à matemática**, há algumas aplicações na física, como no estudo de campos elétricos.

**Calculamos determinantes somente de matrizes quadradas**, ou seja, matrizes em que a quantidade de colunas e a quantidade de linhas são iguais. Para calcular o determinante de uma matriz, precisamos analisar a ordem dela, ou seja, se ela é 1x1, 2x2, 3x3 e assim sucessivamente, quanto maior a sua ordem, mais difícil será encontrar o determinante. No entanto, há métodos importantes realizar-se o exercício, como a **regra de Sarrus**, utilizada para calcular-se determinantes de matrizes 3x3.

![Cálculo do determinante de uma matriz de ordem
2.](https://s4.static.brasilescola.uol.com.br/be/2020/08/determinante.jpg)

Cálculo do determinante de uma matriz de ordem 2.

# Determinante de matriz de ordem 1

Uma matriz é conhecida como de ordem 1 quando possui exatamente **uma linha e uma coluna**. Quando isso ocorre, a matriz possui **um único elemento**, o a~11~. Nesse caso o determinante da matriz coincide com esse seu único termo.

A = (a<sub>11</sub>)

det(A) = | a<sub>11</sub> | = a<sub>11</sub>

**Exemplo**:

A = [2]

det(A) = |2| = 2


Para calcular-se determinantes de matrizes de ordem 1, é necessário então apenas conhecer o seu único elemento. [^1]

[^1]: Qual o determinante de uma matriz de ordem 1?

# Determinantes de matrizes de ordem 2

A matriz quadrada 2x2, conhecida também como matriz de ordem 2, possui **quatro elementos**, nesse caso, para calcular o determinante, é necessário conhecermos o que é a diagonal principal e a diagonal secundária.

Para calcular o determinante de uma matriz de ordem 2, calculamos a **** [**diferença**](https://brasilescola.uol.com.br/matematica/subtracao.htm) **entre o produto dos termos da diagonal principal e os termos da diagonal secundária**. Utilizando o exemplo algébrico que construímos, o det(A) será:

![](https://s2.static.brasilescola.uol.com.br/be/2020/08/1-det2x2.jpg)

**Exemplo**:

![](https://s4.static.brasilescola.uol.com.br/be/2020/08/2-exemplo-2x2.jpg)

[^2]

[^2]: Como calcular o determinante de uma matriz de ordem 2?

# Determinante de matriz de ordem 3

A matriz de ordem três é **mais trabalhosa** para obter-se o determinante do que as anteriores, na verdade, quanto maior a ordem de uma matriz, mais difícil será esse trabalho. Nela é necessário **utilizar o que conhecemos como** [**regra de Sarrus**](https://brasilescola.uol.com.br/matematica/regra-sarrus.htm).

## Regra de Sarrus

A regra de Sarrus é um método para calcular-se determinantes de matrizes de ordem 3. É necessário seguir alguns passos, sendo o primeiro **duplicar as duas primeiras colunas no final da matriz**, conforme o exemplo a seguir.

![](https://s4.static.brasilescola.uol.com.br/be/2020/08/3-matriz-3x3.jpg)

Agora vamos **multiplicar os termos de cada uma das três diagonais** que estão no mesmo sentido da diagonal principal.

![](https://s2.static.brasilescola.uol.com.br/be/2020/08/5-diagonal-principal.jpg)

Realizaremos um processo parecido com a diagonal secundária e as outras duas diagonais que estão no mesmo sentido que ela.

![](https://s4.static.brasilescola.uol.com.br/be/2020/08/6-determinante3x3.jpg)

Note que **os termos da diagonal secundária estão sempre acompanhados com o sinal negativo**, ou seja, sempre trocaremos o sinal do resultado da multiplicação dos termos da diagonal secundária.

**Exemplo**:

![](https://s1.static.brasilescola.uol.com.br/be/2020/08/7-exemplo3x3.jpg)

# Propriedades do determinante

## 1ª propriedade

Caso uma das linhas da matriz seja igual a 0, então o seu determinante será igual a 0.

**Exemplo**:

![](https://s4.static.brasilescola.uol.com.br/be/2020/08/8-propriedade-1.jpg)

## 2ª propriedade

Seja A e B duas matrizes, det(A·B) = det(A) · det(B).

**Exemplo**:

![](https://s5.static.brasilescola.uol.com.br/be/2020/08/9-2-propriedade.jpg)

Calculando os determinantes separados, temos que:

det(A) = 2 · (-6) – 5 · 3\
 det(A) = -12 – 15 = -27

det(B) = 4 · 1 – 2 · (-2)\
 det(B) = 4 + 4 = +8

Então det(A) · det(B) = -27 · 8 =  -216

Agora vamos calcular det(A·B)

![](https://s3.static.brasilescola.uol.com.br/be/2020/08/10-propriedade2p2.jpg)

## 3ª propriedade

Seja A uma matriz e A’ uma nova matriz construída trocando-se as linhas da matriz A, então det(A’) =  -det(A), ou seja, ao inverter-se a posição das linhas de uma matriz, o seu determinante terá o mesmo valor, porém de sinal trocado.

**Exemplo**:

![](https://s2.static.brasilescola.uol.com.br/be/2020/08/11-propriedade3.jpg)

## 4ª propriedade

Linhas iguais ou [proporcionais](https://brasilescola.uol.com.br/o-que-e/matematica/o-que-e-proporcao.htm) fazem com que o determinante da matriz seja igual a 0.

**Exemplo**:

Note que, na matriz A, os termos da linha dois são o dobro dos termos da linha um.

![](https://s1.static.brasilescola.uol.com.br/be/2020/08/12-propriedade-4.jpg

- [x] Processo

## Next
[[17 12 2020]]
## Processo:
Created: [[28-11-2020]]
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