### Piso e teto

O piso (= _floor_) de um número real x é o resultado do arredondamento de x para baixo. Em outras palavras, o piso de x é o único número inteiro i tal que

i   ≤   x   <   i + 1 .

Por exemplo, o piso de 3.99 é 3.   Em notação C, podemos denotar o piso de x por  [(int)](cast.html) x ,  desde que x não seja estritamente negativo.  Em notação mais tradicional, o piso de x é denotado por

⌊ x ⌋ .

O teto (= _ceiling_) de um número real x é o resultado do arredondamento de x para cima. Em outras palavras, o teto de x é o único número inteiro j tal que

j − 1   <   x   ≤   j .

Por exemplo, o teto de 3.01 é 4.   Em notação tradicional, o teto de x é denotado por

⌈ x ⌉ .