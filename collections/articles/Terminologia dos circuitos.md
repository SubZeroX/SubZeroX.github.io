[Terminologia dos circuitos questions](Terminologia%20dos%20circuitos%20questions.md)

Estamos desenvolvendo métodos para analisar um circuito. Por hora, definimos os componentes (resistor, capacitor e indutor) e as fontes (tensão e corrente) mais comuns. Agora, vamos precisar de um vocabulário claro para falar de circuitos. Esse artigo é um glossário de termos e conceitos que usamos em análise e projeto de circuitos.

## Circuito

*Circuito* vem da palavra *círculo*. Um circuito é uma porção de componentes reais, fontes de potência e fontes de sinal, todos conectados de modo que a corrente possa fluir em um círculo completo

**Circuito fechado** – Um circuito é *fechado* se o círculo é completo, se todas as correntes têm uma percurso de volta para onde elas vieram.

**Circuito aberto** – Um circuito é *aberto* se o círculo não é completo, se existe uma lacuna ou uma abertura no percurso.

**Curto circuito** – Um *curto* ocorre quando um percurso de baixa resistência é conectado (usualmente por engano) a um componente. Na ilustração abaixo, o resistor é o percurso preferencial e o fio curvo em torno dele é o curto. A corrente é desviada de seu percurso preferencial, às vezes com resultados nocivos. O fio *põe em curto* o resistor, fornecendo um caminho de baixa resistência para a corrente (provavelmente não aquele que o projetista pretendia).

![](Imagens/Pasted%20image%2020200930121506.png)

**Fechar ou abrir** – Você *fecha* um circuito ao fechar o caminho da corrente, do mesmo jeito quando você acende um interruptor. *Abrir* um circuito é a ação contrária, ou seja, apagar um interruptor *abre* o circuito.

![](Imagens/Pasted%20image%2020200930121514.png)

## Diagrama

Um *diagrama* é um desenho de um circuito. Um diagrama representa elementos do circuito com símbolos e conexões como linhas.

**Elementos** – O termo *elementos* significa "componentes e fontes."

**Símbolos** – Os elementos são representados em esquemas por *símbolos*. Os símbolos para elementos comuns de 2 terminais são mostrados aqui,

![](Imagens/Pasted%20image%2020200930121525.png)

**Linhas** – As conexões entre elementos são desenhadas como linhas, que muitas vezes tratamos como "fios". Em um diagrama, estas linhas representam condutores perfeitos com resistência nula. Cada terminal de um componente ou uma fonte tocado por uma mesma linha possui a mesma tensão.

**Pontos** – As conexões entre linhas podem ser indicadas por *pontos*. Os pontos são uma indicação inequívoca de que as linhas estão conectadas. Se a conexão é óbvia, você não precisa usar um ponto.

![](Imagens/Pasted%20image%2020200930121532.png)

(a) e (b) são bons
(c) sem ponto indica não conexão
(d) também indica que não há conexão; o fio horizontal "pula" sobre o fio vertical. (d) é muito claro, mas exige esforço e espaço extra para desenhar.
(e) para cruzar linhas conectadas, (e) é aceitável, mas corre o risco de se parecer muito com (c), então, (f) é a melhor opção.

**Nó** – Uma junção onde 2 *ou mais* elementos se conectam é chamada de um *nó*. O diagrama abaixo mostra um único nó (o ponto preto) formado pela junção de cinco elementos (abstratamente representados por retângulos laranja).

![](Imagens/Pasted%20image%2020200930121607.png)

Uma vez que as linhas num diagrama representam condutores perfeitos com resistência nula, não há nenhuma regra que diga que as linhas de vários elementos vão necessariamente se reunir em um único ponto de junção. Podemos desenhar o mesmo nó como um nó *distribuído*, como no esquema abaixo. Estas duas representações do nó significam exatamente a mesma coisa.

![](Imagens/Pasted%20image%2020200930121615.png)

Um nó distribuído pode ser espalhado, com segmentos de linha, cotovelos e pontos. Não se confunda, é tudo apenas um único nó. Conectar elementos esquemáticos com condutores perfeitos significa que a tensão em todo nó distribuído é a mesma.

Aqui está um diagrama realista com os nós distribuídos rotulados:

![](Imagens/Pasted%20image%2020200930121625.png)

problema 1

**Quantos nós existem neste diagrama?**

![](Imagens/Pasted%20image%2020200930121635.png)

4


**Ramo** – Os *ramos* são conexões entre nós. Um ramo é um elemento (resistor, capacitor, fonte, etc.). O número de ramos em um circuito é igual ao número de elementos.

problema 2

**Quantos ramos há neste diagrama?**

![](Imagens/Pasted%20image%2020200930121803.png)

![](Imagens/Pasted%20image%2020200930121822.png)

**Laço** – Um *laço* é qualquer caminho fechado passando por elementos do circuito. Para desenhar um laço, selecione um nó qualquer como ponto de partida e desenhe um percurso através de elementos e nós até retornar ao nó de partida. Existe apenas uma regra: um laço pode visitar (passar por) um nó apenas *uma vez*. Tudo bem se um laço se sobrepõe ou contém outro laço. Alguns dos laços em nosso circuito são mostrados aqui. (Você pode achar outras, também. Se eu contei certo, há seis.)

![](Imagens/Pasted%20image%2020200930121838.png)


**Malha** – Uma *malha* é um laço que não apresenta outros laços dentro dele. Você pode imaginar isso como sendo uma malha para cada "janela aberta" do circuito.

problema 3

**Quantas malhas há neste circuito?**

![](Imagens/Pasted%20image%2020200930121903.png)

![](Imagens/Pasted%20image%2020200930121911.png)

3

**Nó de Referência** – Em análise de circuitos, normalmente escolhemos um dos nós para ser o *nó de referência*. As tensões de todos os outros nós são medidas em relação ao nó de referência. Qualquer nó pode ser o de referência, mas duas escolhas comuns que simplificam a análise de circuitos são:

*   o terminal negativo da fonte de tensão ou de corrente que alimenta o circuito, ou
*   o nó conectado ao maior número de ramos.

**Terra** – O nó de referência é muitas vezes chamado de *terra*. O conceito de *terra* tem três significados importantes.

![](Imagens/Pasted%20image%2020200930121940.png)

*Uma estaca de metal aterrada perto de uma casa. O fio afixado na estaca se curva para a direita para garantir o referencial terra de segurança para o sistema elétrico da casa. Às vezes, o fio terra é afixado em um cano de água, o qual desaparece dentro da Terra.*

O terra é

*   o ponto de referência a partir do qual as tensões são medidas.
*   o caminho de retorno da corrente elétrica para a sua fonte.
*   uma conexão física direta para a Terra, que é importante para a segurança.

O nó terra tem esse nome devido ao terceiro significado. Mas os outros dois são igualmente importantes.

Você vai se deparar com vários símbolos para o terra:

![](Imagens/Pasted%20image%2020200930122002.png)

- [x] Processo 
