### toevalsgebeurtenissen
##### probabiliteitsmaat
De uitkomstenruimte is de verzameling van alle mogelijke uitkomsten van een bepaalde gebeurtenis.
We veronderstellen altijd dat een uitkomstenverzameling [[H2 eindige en oneindige verzamelingen#eindige verzameling|eindig]] is bij een discrete probabiliteit. bv. 52 kaarten, kop of munt,.... = *sample space, S*

Een gebeurtenis (event, E) is 1 of meerdere elementen uit deze uitkomstenruimte.
2 gebeurtenissen worden disjunct genoemd als ze niet op hetzelfde moment kunnen voorkomen en dus A ∩ B = Ø

Om kansen te berekenen kennen we een probabiliteitsgewicht P(x) toe aan elk element van S waarbij de volgende regels gelden:
* elk gewicht is een reëel getal gelegen tussen 0 en 1
* de som van de gewichten in de uitkomstenruimte is 1

P(E)= som van P(x)

elke  P (kansfunctie) wordt een probabiliteitsmaat/ probabiliteitsdistributie genoemd als deze voldoet aan de volgende eigenschappen:
* P(A) >= 0 voor elke A ⊆ S
* P(S) = 1
* P(A Ս B) = P(A) +P(B) voor 2 disjuncte gebeurtenissen

##### complementaire gebeurtenissen
Als 2 gebeurtenissen A en B complement zijn dan is A Ս B = S en A ∩ B =Ø.
Het complement van A wordt vaak geschreven als A$^c$.

P(F) = 1 - P(E)
*bewijs*
1 = P(S) = P (E Ս F) = P(E) +P(F) omdat E en F disjuncte gebeurtenissen zijn.

##### uniforme probabiliteitsmaten
Een probabiliteitsmaat is uniform als elk element uit s evenveel kans heeft om voor te komen/ als elk element hetzelfde probabiliteitsgewicht heeft.

Als P uniform is verdeeld dan geld voor elke gebeurtenis E⊆ S  dat
P(E) = |E| / |S|
*bewijs*
stel S = {x$_1$,x$_2$,...,x$_k$} ,  met n = |S|; dan is, voor elke i ∈{1, ... , n}
1 = P(S) = P (x$_1$) + ... + P (x$_n$) = n \* P (x$_i$) 

en dus is P (x$_i$)  = 1/ n . Voor elke E ⊆ S geldt dan

![[Pasted image 20211227220613.png]]
