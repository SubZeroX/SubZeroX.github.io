## Pontos Principais:

* Quando os genes são encontrados em cromossomos diferentes ou bem distantes mas no mesmo cromossomo, eles ordenam-se independentemente e são ditos ser **não ligados**. [^1]

[^1]: O que são genes não ligados?

* Quando os genes estão bem próximos no mesmo cromossomo, diz-se que estão **ligados**. Isso significa que os alelos, ou as versões gênicas, juntas em um cromossomo serão mais frequentemente herdadas como uma unidade do que separadamente. [^2]

[^2]: O que são genes ligados?

* Podemos ver se dois genes estão ligados, e quão próximos estão, usando informação de cruzamentos genéticos para calcular a **frequência de recombinação**.
* Encontrando as frequências de recombinação para muitos pares de genes, podemos formar **mapas de ligação** que mostram a ordem e as distâncias relativas dos genes nos cromossomos.

## Introdução

De forma geral , os organismos têm muito mais genes do que cromossomos[^3]. 

[^3]: Os organismos têm mais genes ou cromossomos?

Por exemplo, nós humanos possuímos cerca de 19000 genes em 23 cromossomos (presentes em pares). Da mesma forma, a humilde mosca da fruta - o objeto de estudo favorito dos geneticistas - tem cerca de 13000 genes em 4 cromossomos (também presentes em pares).

A consequência? Cada gene não terá seu próprio cromossomo. De fato, nem se aproxima disso! Muitos genes estarão alinhados em sequência em cada cromossomo e alguns deles estarão realmente muito próximos uns dos outros.

Isso afeta como os genes são herdados? Em alguns casos, a resposta é sim. Genes que estão suficientemente próximos em um cromossomo tendem a "permanecer juntos" e as versões (alelos) desses genes que estão juntas em um cromossomo tenderão a ser herdadas como um par mais frequentemente que separadas.

Esse fenômeno é chamado **ligação genética**. Quando genes estão ligados, cruzamentos genéticos envolvendo esses genes levam a razões de gametas (óvulos e espermatozoides) e tipos de descendentes que não são preditos por Mendel [Lei da Segregação Independente](https://pt.khanacademy.org/science/biology/classical-genetics/mendelian--genetics/a/the-law-of-independent-assortment). Vamos olhar mais de perto porquê é esse o caso.

## O que é ligação genética?

Quando os genes estão em cromossomos separados ou muito distantes em um mesmo cromossomo, eles **segregam independentemente**. Isto é, quando os genes vão para os gametas, o alelo recebido para um gene não afeta o alelo recebido pelo outro. Em um organismo duplo heterozigoto (*AaBb*), esse é o resultado na formação dos 4 possíveis tipos de gametas com frequência igual, ou seja 25%. [^4]

[^4]: O que é a ligação genética?

![](Imagens/Pasted%20image%2020201001180111.png)

Por que isso acontece? Genes em cromossomos separados segregam de maneira independente devido a orientação aleatória dos pares de cromossomos homólogos durante a [meiose](https://pt.khanacademy.org/science/biology/cellular-molecular-biology/meiosis/v/chromosomal-crossover-in-meiosis-i). **Cromossomos homólogos** são pares de cromossomos que carregam os mesmos genes, mas podem ter alelos diferentes desses mesmos genes. Um membro de cada par de homólogo de um organismo vem de sua mãe e o outro de seu pai.

![](Imagens/Pasted%20image%2020201001180504.png)

Como ilustrado no diagrama abaixo, os homólogos de cada par separam-se no primeiro estágio da meiose. Nesse processo, os cromossomos do pai ou da mãe de cada par de homólogo são organizados aleatoriamente. Quando nós estamos seguindo dois genes, isto resulta em quatro tipos de gametas que são produzidos em igual frequência.

![](Imagens/Pasted%20image%2020201001180514.png)

Quando dois genes estão no mesmo cromossomo, mas muito distantes entre si, eles segregam independentemente devido ao **Crossing Over** (**recombinação homóloga**). [^9]Esse é um processo que acontece bem no inicio da meiose, no qual cromossomos homólogos aleatoriamente trocam fragmentos equivalentes. Crossing over pode colocar novos alelos juntos em combinação no mesmo cromossomo, levando\-os para o mesmo gameta. Quando os genes estão distantes, a recombinação acontece com tal regularidade que todos os tipos de gametas são produzidos na frequência de 25%.

[^9]: Por que dois genes em um mesmo cromossomo, mas distantes um do outro, se segregam independentemente?

![](Imagens/Pasted%20image%2020201001180526.png)

Quando genes estão muito próximos em um mesmo cromossomo, crossing over até ocorre, mas o que se vê (em termos de tipos de gametas produzidos) é diferente. Ao contrário da segregação independente, os genes tendem a "permanecer juntos" durante a meiose. Isto é, os alelos dos genes que já estão juntos em um cromossomo tenderão a passar como uma unidade para os gametas. Nesse caso, os genes estão **ligados**. Por exemplo, dois genes ligados devem se comportar assim:

![](Imagens/Pasted%20image%2020201001180535.png)

Agora, nós vemos tipos de gametas que estão presentes em proporções bem desiguais. Os tipos de gametas comuns têm configurações **parentais** dos alelos - isto é, os que já estavam juntos no cromossomo em um organismo antes da meiose (i.e., no cromossomo que recebeu de seus pais). Os tipos raros de gametas contêm configurações **recombinantes** de alelos, isto é, aquelas que podem ser formadas apenas se um evento de recombinação (crossover) ocorrer entre os genes.

Por que os tipos de gametas recombinantes são raros? A razão básica é que as recombinações entre dois genes que estão juntos não é muito comum. Recombinações durante a meiose acontecem em posições mais ou menos aleatórias ao logo do cromossomo, então a frequência de recombinação entre dois genes depende da distância entre eles. Uma distância muito curta é, efetivamente, um "alvo" muito pequeno para os eventos de recombinação, o que significa que poucos eventos acontecerão (quando comparado ao número de eventos entre dois genes mais distantes). [^5]

[^5]: Por que eventos de recombinação são raros em linkage?

![](Imagens/Pasted%20image%2020201001180543.png)

Graças a essa relação, nós podemos usar a frequência de eventos de recombinação entre dois genes (i.e., seu grau de ligação genética) para estimar a distância relativa entre eles no cromossomo. Dois genes muito próximos terão uma baixa frequência de eventos de recombinação e serão ligados fortemente, enquanto dois genes que estão relativamente mais distantes terão mais eventos de recombinação e estarão ligados com menor intensidade. Na próxima sessão, nós veremos como calcular a **frequência de recombinação** entre dois genes, usando a informação dos cruzamentos genéticos.

## Determinação da frequência de recombinação

Vamos supor que estamos interessados em ver se os dois genes da mosca-da-fruta (*Drosophila*) estão ligados um ao outro, e, caso estejam, o quão fortemente ligados eles estão. No nosso exemplo, os genes são:

* O gene *roxo*, com o alelo dominante *$pr^{+}$* que especifica o fenótipo normal, olhos vermelhos; e o alelo recessivo *pr* que especifica olhos roxos.
* O gene *vestigial*, com o alelo dominante *$vg^{+}$* que especifica o fenótipo normal, asas longas; e o alelo recessivo *vg* que especifica asas curtas, "vestigiais".

Se queremos medir a frequência de recombinação entre esses genes, primeiro precisamos desenhar uma mosca em que possamos observar a recombinação. Ou seja, precisamos fazer uma mosca que não é apenas heterozigota para ambos os genes, mas também na qual sabemos exatamente quais genes estão juntos no cromossomo. Para fazer isso, podemos começar pelo cruzamento de duas moscas homozigotas como mostrado abaixo:

![](Imagens/Pasted%20image%2020201001180737.png)

Este cruzamento nos dá exatamente o que precisamos para observar o fenômeno de recombinação: uma mosca que é heterozigota para os genes *roxo* e *vestigial*, na qual nós sabemos claramente quais alelos estão juntos em um único cromossomo.

Agora, precisamos de uma maneira de "ver" os eventos de recombinação. A abordagem mais direta seria olhar os gametas feitos pela mosca heterozigota e ver quais alelos eles tinham em seus cromossomos. Na prática, porém, é muito mais simples usar esses gametas em um cruzamento e ver quais são os fenótipos da prole!

Para fazermos isso, podemos cruzar uma mosca duplamente heterozigota com uma **mosca-teste**, a qual é homozigota recessiva para todos os genes de interesse (neste caso, para os alelos *pr* e *vg* ). A finalidade de usar uma mosca\-teste é garantir que os alelos fornecidos pelo genitor duplo heterozigoto possam determinar totalmente o fenótipo, ou aparência, da descendência. Quando cruzamos a mosca de interesse com uma mosca\-teste, podemos "ler" diretamente o genótipo de cada gameta a partir da aparência física da descendência.

![](Imagens/Pasted%20image%2020201001180754.png)

Abaixo, podemos ver um quadro de Punnett modificado mostrando os resultados do cruzamento entre a nossa mosca duplo heterozigota com a mosca-teste. Quatro diferentes tipos de óvulos são produzidos por uma mosca fêmea duplo heterozigota, sendo que cada um deles se combina com um espermatozoide da mosca-teste macho. Quatro diferentes classes fenotípicas (aparências) da prole são produzidas neste cruzamento, cada uma correspondendo a um determinado gameta da mãe:

![](Imagens/Pasted%20image%2020201001180805.png)

As quatro classes fenotípicas da prole *não* são geradas em quantidades iguais, o que nos mostra que os genes *roxo* e *vestigial* estão ligados. Como é esperado para genes ligados entre si, as configurações do cromossomo parental são super-representadas na prole, enquanto as configurações do cromossomo recombinante são sub-representadas.[^7]Para medir quantitativamente a ligação dos genes, nós podemos calcular a **frequência de recombinação** (**FR**) entre os genes *roxo* e *vestigial* :

[^7]: Qual é a representação dos genes recombinantes quando estão ligados?

$Frequência de recombinação  (\mathrm{FR})=\frac{\text { Recombinantes }}{\text { Prole total }} \times 100 \%$[^6]

[^6]: Como calcular quantitativamente a frequência de recombinação?

Em nosso caso, as classes dos descendentes recombinantes são as de moscas com olhos vermelhos e asas vestigiais; e moscas de olhos roxos e asas longas. Nós podemos identificar essas moscas como sendo as classes recombinantes por duas razões: primeira, nós sabemos que, a partir das séries de cruzamentos que fizemos, que elas devem ter herdado um cromossomo da mãe que provém de um evento de recombinação; e segunda, elas são classes sub-representadas (em relação às classes sobre-representadas, parentais).

Então, para o cruzamento acima, podemos escrever nossa equação da seguinte forma:

$$
 \mathrm{FR}=\frac{151+154}{1339+1195+151+154} \times 100 \%=10,7 \% 
$$

A frequência de recombinação entre os genes *roxo* e *vestigial* é 10,7.

## Frequência de recombinação e mapas de ligação

Qual é a vantagem de se calcular a frequência de recombinação? Historicamente, uma forma pela qual as frequências de recombinação foram usadas é a construção de **mapas genéticos**, mapas de cromossomos baseados nas frequências de recombinação. Na verdade, estudar o "linkage" ajudou os primeiros geneticistas a estabelecer que os cromossomos eram, na verdade, lineares, e que cada gene possuía o seu local específico no cromossomo.

A frequência de recombinação não é uma medida direta do quanto os genes estão fisicamente distantes nos cromossomos. No entanto, fornece uma estimativa ou aproximação da distância física. Então, podemos dizer que um par de genes com uma frequência de recombinação maior está provavelmente mais distante, enquanto um par com uma frequência de recombinação menor está provavelmente mais próximo.

Igualmente importante, a frequência de recombinação "chega a seu máximo" em 50% (o que corresponde aos genes estarem não ligados, ou combinados independentemente).[^8] Ou seja, 50% é a maior frequência de recombinação que poderá ser medida diretamente entre os genes. Então, se quisermos descobrir a distância entre genes que estão ainda mais afastados do que isso, teremos de fazê-lo adicionando as frequências de recombinação de vários pares de genes, "construindo" um mapa que se estende entre os dois genes distantes.

[^8]:Qual a máxima frequência de recombinação?

A comparação das frequências de recombinação também pode ser usada para descobrir a ordem dos genes num cromossomo. Por exemplo, vamos supor que temos três genes, *A*, *B*, e *C*, e queremos saber a sua ordem no cromossomo (*ABC*? *ACB*? *CAB*?) Se olharmos para as frequências de recombinação entre todos os três possíveis pares de genes (*AC*, *AB*, *BC*), podemos descobrir quais genes ficam mais distante, e qual gene encontra-se no meio. Especificamente, o par de genes com a maior frequência de recombinação deve ladear o terceiro gene:

![](Imagens/Pasted%20image%2020201001181038.png)

As frequências de recombinação são baseadas nas frequências de genes de moscas *v*, *cv* e *ct*, conforme determinado em D. C Bergmann 4^4 4 start superscript, 4, end superscript.

Ao fazer este tipo de análise com cada vez mais genes (por exemplo, ao adicionar-se os genes *D*, *E* e *F* e descobrir suas relações com *A*, *B* e *C*), podemos construir mapas de ligação de cromossomos inteiros. Em mapas de ligação, você pode ver as distâncias expressas em centimorgan ou unidades de mapa, em vez de frequências de recombinação. Felizmente, há uma relação direta entre esses valores: uma frequência de recombinação 1% é equivalente a 1 **centimorgan** ou 1 **unidade de mapa**.

Será que a distância é sempre igual à frequência de recombinação? 

Às vezes, a frequência de recombinação medida diretamente entre dois genes não é a medida mais exata da sua distância. Isso porque, além dos crossovers simples que discutimos neste artigo, também podem ocorrer crossovers duplos (dois crossovers separados entre os dois genes):

![](Imagens/Pasted%20image%2020201001181132.png)

Os crossovers duplos são "invisíveis" se estamos apenas monitorando dois genes, no sentido de que eles colocam os dois genes originais de volta no mesmo cromossomo (mas com um pedaço desativado no meio). Por exemplo, o crossover duplo mostrado acima não seria detectável se estivéssemos apenas olhando os genes *A* e *C*, uma vez que estes genes acabam voltando à sua configuração original.

Devido a isso, os crossovers duplos não são contados na frequência de recombinação medida diretamente, resultando em uma leve subestimativa do número real de eventos de recombinação. É por isso que, no exemplo abaixo, a frequência de recombinação medida diretamente entre *A* e *C* é um pouco menor do que a soma das frequências de recombinação entre *A\-B* e *B\-C*. Quando *B* é incluído, podem ser detectados e contabilizados crossovers duplos entre *A* e *C*.

![](Imagens/Pasted%20image%2020201001181213.png)

Medindo as frequências de recombinação de pares de genes que estão mais próximos e somando\-os, podemos minimizar os crossovers duplos "invisíveis" e obter distâncias de mapa mais precisas.

- [x] Processo 

## Next
[[05 01 2021]]
## Processo:
Created: [[02-11-2020]]
*+2 *  *Ctrl+0*
- [x] Molho  

*+7*  *Ctrl+1*

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

# Anki

---

TARGET DECK
Enem::Natureza::Biologia

Q: Como calcular quantitativamente a frequência de recombinação?
A: Recombinates/prole total x 100
Z: Ligação genética e mapeamento
<!--ID: 1605053494668-->

---
