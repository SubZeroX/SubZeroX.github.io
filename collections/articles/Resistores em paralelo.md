Componentes estão em _paralelo_ se eles compartilham dois nós, como este:
![](Imagens/Pasted%20image%2020200930110858.png)

Neste artigo nós vamos trabalhar com resistores em paralelo, para revelar as propriedades da conexão paralela. Os artigos seguintes irão cobrir capacitores e indutores em série e paralelo.

Resistores em paralelo
----------------------

Resistores estão em paralelo quando seus dois terminais conectam-se aos mesmos nós.

Na imagem seguinte, R1, R2 e R3 estão em paralelo. Os dois nós distribuídos estão representados pelas duas linhas horizontais.

![](Imagens/Pasted%20image%2020200930110922.png)

Resistores em paralelo compartilham a mesma tensão em seus terminais.

Os resistores na imagem seguinte _não_ estão em paralelo. Há componentes extras (caixas laranjas) separando os nós dos resistores. Esse circuito tem quatro nós separados, então R1, R2 e R3 _não_ compartilham a mesma tensão.

![](Imagens/Pasted%20image%2020200930111258.png)

### Propriedades dos resistores em paralelo

Descobrir resistores paralelos é um pouco mais complicado que os resistores em série. Aqui está um circuito com resistores em paralelo. (Esse circuito tem uma fonte de corrente. Nós não usamos esse com frequência, então isso será divertido.)

![](Imagens/Pasted%20image%2020200930111321.png)

A fonte de corrente $I_{s}$ está fornecendo corrente i na direção de R1, R2 e R3. Sabemos que o valor da corrente i é uma constante, mas ainda não sabemos a tensão v ou como i se divide em correntes nos três resistores.

Duas coisas que sabemos são:

*   As correntes nos três resistores têm de somar i.
*   A tensão v aparece em todos os três resistores.

Com esse pouco conhecimento e a Lei de Ohm, nós podemos escrever estas expressões:

![](Imagens/Pasted%20image%2020200930111930.png)

Isso é suficiente para continuarmos. As três expressões da Lei de Ohm são reorganizadas para resolver para a corrente em termos de tensão e resistência:

![](Imagens/Pasted%20image%2020200930111952.png)

Substitua essas expressões para a soma das correntes:

![](Imagens/Pasted%20image%2020200930112004.png)

Coloque em evidência o termo comum v,

![](Imagens/Pasted%20image%2020200930112013.png)

Lembre-se que nós já conhecemos i ( esta é uma propriedade da fonte da corrente), então podemos resolver para v:

![](Imagens/Pasted%20image%2020200930112023.png)

Essa expressão parece igual a Lei de Ohm, $v={i}.{R}$, mas com os resistores paralelos aparecendo em um duplo recíproco no lugar de um único resistor.

> _Para resistores em paralelo, a resistência total é recíproca a soma de recíprocos nos resistores individuais._

(Isso parece complicado, mas nós vamos chegar a algo mais simples antes de terminarmos.)

### Resistor paralelo equivalente

A equação anterior sugere que nós podemos definir um novo resistor equivalente aos resistores em paralelo. O novo resistor é equivalente no sentido que, para uma certa corrente i, a mesma tensão v aparece.

![](Imagens/Pasted%20image%2020200930112136.png)

O resistor paralelo equivalente é o recíproco da soma de recíprocos. Nós podemos escreve essa equação de outra maneira rearranjando a recíproca gigante,

![](Imagens/Pasted%20image%2020200930112143.png)

A Lei de Ohm aplicada a resistores paralelos,

![](Imagens/Pasted%20image%2020200930112153.png)

Do "ponto de vista" da fonte de corrente, o resistor equivalente $R_{paralelo}$ é indistinguível dos três resistores em paralelo, porque em ambos os circuitos a tensão v é a mesma.

Se você tiver vários resistores em paralelo, a forma geral da resistência equivalente paralela é,

![](Imagens/Pasted%20image%2020200930112231.png)

### Corrente distribuída entre resistores em paralelo

Nós trabalhamos com a tensão v através da conexão paralela, então o que sobra para descobrir são as correntes através dos resistores individuais.

Faça isso aplicando a Lei de Ohm para os resistores individuais.

![](Imagens/Pasted%20image%2020200930112246.png)

Isso se torna mais informativo em um exemplo com números reais.

![](Imagens/Pasted%20image%2020200930112305.png)

**Encontre a tensão v e as correntes através dos três resistores.**  
**Mostre que as correntes individuais no resistor somam i.**

Os passos para a solução são,

1.  Encontre a resistência paralela equivalente $R_{paralelo}$
2.  Em seguida, encontre a tensão v usando a Lei de Ohm.
3.  Em seguida, encontre as correntes individuais, usando de novo a Lei de Ohm.
4.  Verifique se as correntes do resistor somam o que deveriam.

O equivalente $R_{paralelo}$ é igual ao recíproco da soma das três resistências recíproca.

![](Imagens/Pasted%20image%2020200930112656.png)

Agora nós sabemos a resistência equivalente. Nós podemos resolver para a tensão v entre os dois nós,

![](Imagens/Pasted%20image%2020200930112720.png)

Como conhecemos v, podemos calcular as correntes dos resistores individuais,

![](Imagens/Pasted%20image%2020200930112742.png)

Aqui está como a solução parece:

![](Imagens/Pasted%20image%2020200930112750.png)

Checando: A soma das correntes do resistor se igualam à corrente original?

![](Imagens/Pasted%20image%2020200930112803.png)

$\checkmark Sim!$

#### Reflexão
> A maior parte da corrente passa através do menor resistor\
> A menor parte da corrente passa através do maior resistor\
> O resistor equivalente em paralelo é menor que o menor dos resistores\
> Todos resistores em paralelo apresentam a mesma tensão

Caso especial - dois resistores em paralelo
-------------------------------------------
![](Imagens/Pasted%20image%2020200930113035.png)
Dois resistores em paralelo tem uma resistência equivalente de:

![](Imagens/Pasted%20image%2020200930113046.png)

É possível fazer um pouco de manipulação para eliminar os recíprocos e inventar outra expressão com apenas uma fração. Ao invés de apenas dizer a resposta, é um rito de passagem trabalhar através da álgebra pela primeira vez. A resposta está escondida para que você possa tentar por conta própria antes de ver a solução.

![](Imagens/Pasted%20image%2020200930113100.png)

Vamos trabalhar no denominador para eliminar as frações. O denominador comum é ${R1}.{R2}$

![](Imagens/Pasted%20image%2020200930113200.png)

Esta é a equação para dois resistores em paralelo.
O produto sobre a soma. Isto vale a pena memorizar.

Caso especial - dois resistores iguais em paralelo
--------------------------------------------------

Se dois resistores em paralelo têm o mesmo valor, qual é o $R_{paralelo}$ equivalente?

Seja R1, R2 = R

![](Imagens/Pasted%20image%2020200930113304.png)

Dois resistores idênticos em paralelo têm uma resistência equivalente a metade do valor de cada resistor. A corrente se divide igualmente entre os dois.

- [x] Processo 
