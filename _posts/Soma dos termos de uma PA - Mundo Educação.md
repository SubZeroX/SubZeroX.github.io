Uma [progressão aritmética](https://mundoeducacao.uol.com.br/matematica/progressao-aritmetica.htm) (PA) é uma [sequência numérica](https://mundoeducacao.uol.com.br/matematica/sequencia-numerica.htm) que segue a lógica a seguir: um elemento é igual ao anterior somado com uma constante [real](https://mundoeducacao.uol.com.br/matematica/conjunto-dos-numeros-reais.htm). Assim, é uma propriedade das progressões aritméticas que a [diferença](https://mundoeducacao.uol.com.br/matematica/adicao-subtracao-racionais.htm) entre dois termos consecutivos quaisquer tenha sempre o mesmo resultado. Esse resultado é chamado de razão. A **soma dos termos de uma PA** pode ser calculada de maneira fácil por meio de uma fórmula, que será discutida a seguir.

***O primeiro a somar termos***

Gauss, matemático alemão, foi o primeiro a **somar os termos de uma PA** sem precisar somar todos os termos um por um. Quando criança, sua turma na escola sofreu um castigo do professor: eles deveriam somar todos os números de 1 a 100. Gauss foi o primeiro a terminar, em tempo recorde, e o único a acertar o resultado: 5050.

A explicação para isso está no fato de Gauss ter percebido que a soma do primeiro número com o último tinha 101 como resultado e que o mesmo acontecia para o segundo e penúltimo, terceiro e antepenúltimo e assim por diante. Não passou muito tempo para ele calcular que, ao final, teria 50 resultados iguais a 101 e que a soma exigida pelo professor era igual ao produto 50 por 100.

O pensamento de Gauss norteia a ideia central usada para demonstrar a fórmula da **soma dos n primeiros termos de uma PA.**

***Fórmula para a soma dos n primeiros termos de uma PA***

Dada a PA (a1, a2, a3, …, an – 2, an – 1, an), que possui n termos, observe que o primeiro termo é a1, o segundo é a2, …, o penúltimo é an – 1 e o último é an.

Representando a soma desses termos por Sn, teremos a seguinte expressão:

Sn = a1 + a2 + a3 + … + an – 2 + an – 1 + an

Em vez de **somar os termos** do mesmo modo que Gauss, reescreveremos a soma como outra **soma de termos** de PA logo abaixo dessa, de modo que o último termo fique abaixo do primeiro, o penúltimo fique abaixo do segundo e assim por diante.

Sn = a1 + a2 + a3 + … + an – 2 + an – 1 + an

Sn = an + an – 1 + an – 2 + … + a3 + a2 + a1

Não pare agora... Tem mais depois da publicidade ;)

Observe que, se somarmos as duas expressões, teremos o dobro da mesma soma que Gauss fez.

Sn = a1 + a2 + a3 + … + an – 2 + an – 1 + an

\+ Sn = an + an – 1 + an – 2 + … + a3 + a2 + a1

2Sn = (a1 + an) + (a2 + an – 1) + (a3 + an – 2) + … + (an – 2 + a3) + (an – 1 + a2) + (an + a1)

Mantendo o mesmo pensamento de Gauss, os resultados dessas somas entre parênteses serão iguais aos do primeiro termo somado ao último. Podemos substituir, portanto, todos os termos por (a1 + an). Observe:

2Sn = (a1 + an) + (a1 + an) + (a1 + an) + ... + (a1 + an) + (a1 + an) + (a1 + an)

Para finalizar, observe que a soma que obtivemos aqui é diferente da soma que Gauss obteve, pois possui exatamente os n termos que a PA possui. A de Gauss possuía apenas metade, pois ele somou os termos de uma mesma PA. A soma que desenvolvemos, contudo, possui todos, pois nós duplicamos cada termo antes de somá-los. Desse modo, podemos trocar toda a soma acima pela multiplicação por n, que é o número inicial de termos. Assim, resolvendo a equação, teremos a fórmula pretendida:

2Sn = (a1 + an) + (a1 + an) + (a1 + an) + ... + (a1 + an) + (a1 + an) + (a1 + an)

2Sn = n(a1 + an)

Sn = n(a1 + an)  
       2

\*n é o número de termos; a1 e an são o primeiro e o último termo, respectivamente.

***Exemplo***

Dada a PA (2, 4, 6, 8, 10, …), calcule a soma dos seus 100 primeiros termos.

Para calcular essa soma, é necessário conhecer o último termo dessa PA. Para tanto, usaremos a fórmula do **termo geral** de uma PA.

an = a1 + (n – 1)r

a100 = 2 + (100 – 1)2

a100 = 2 + (99)2

a100 = 2 + 198

a100 = 200

Agora, usando a fórmula para **soma dos n primeiros termos de uma PA,** teremos:

S100 = 100(2 + 200)  
         2

S100 = 100(202)  
          2

S100 = 20200  
          2

S100 = 10100

![Organizando termos de modo que o posterior sempre seja a soma do anterior com uma constante](https://static.mundoeducacao.uol.com.br/mundoeducacao/conteudo_legenda/de6265ad56a699b84924930f96657fec.jpg "Progressão aritmética")  
Organizando termos de modo que o posterior sempre seja a soma do anterior com uma constante