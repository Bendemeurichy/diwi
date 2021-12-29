### het aantal deelverzamelingen van een verzameling
###### Het binomium van Newton
Als n een positief getal is, dan geldt voor elke 2 reële getallen a en b, dat 

![[Pasted image 20211227153331.png]]

*bewijs*
de eigenschap kan bewezen worden met de distributieve eigenschap, het product met n factoren (a + b)(a + b) ... (a + b). De coëfficient van a$^k$b$^n$$^-$$^k$ is gelijk aan het aantal combinaties van k uit de n elementen.

###### het veralgemeende inclusie-exclusie principe
Om de kardinaliteit van de unie van 2 verzamelingen te bepalen gebruiken we:
|A$_1$ Ս A$_2$| = |A$_1$ | + |A$_2$| - |A$_1$ ∩ A$_2$| 

indien we meer dan 2 verzamelingen bekijken moeten we rekening houden met de orde van de doorsneden tussen 2 van de verzamelingen in paar en de orde van de doorsnede van alle 3 verzamelingen.

De formules kunnen worden samengevat in het zeefprincipe.

|A$_1$ Ս A$_2$  Ս ... Ս A$_n$| = α$_1$ - α$_2$ +α$_3$ - ... + (-1)$^n$$^-$$^1$ α$_n$
waar α$_k$ met k ∈ {1, 2, ..., n} de som voor van de kardinaalgetallen van al de mogelijke doorsneden die men kan vormen met k dergelijke verzamelingen A$_j$ 

![[Pasted image 20211227163756.png]]

ofwel
![[Pasted image 20211227163812.png]]

we bewijzen dat elk element uit de unie slechts 1 maal wordt geteld in het rechterlid. veronderstel dat x tot t verzamelingen behoort. Dan zal x een bijdrage t leveren in α$_1$ = de som van de kardinaliteiten van Ai.
In de som van α$_2$ zal de bijdrage 1 zijn dan en slechts dan als Ai en Aj zich onder de t verzamelingen bevinden die x bevatten. De bijdrage van x in het rechterlid is bijgevolg.

![[Pasted image 20211227165136.png]]

aangezien echter

![[Pasted image 20211227165152.png]]

is de bijdrage van x tot het rechterlid 1.

###### permutaties zonder fixelementen (element dat op zichzelf wordt afgebeeld): wanorde
volgens het inclusie-exclusie principe is het totaal aantal wanordes d$_n$ van N[1, n] gelijk aan
d$_n$ = n! - α$_1$ + α$_2$  - ... + (-1)$^n$$^-$$^1$ α$_n$
waarbij α$_i$ de som is van het aantal permutaties van N[1 ,n] die i gegeven elementen fixeren.
Het aantal permutaties van N[1, n] die deze i elementen (elementsgewijze) fixeren is het aantal permutaties op de n-i overige elementen (n - i)!. bijgevolg is 

![[Pasted image 20211227172645.png]]

zodat het totaal aantal wanordes gelijk is aan

![[Pasted image 20211227172710.png]]

Dit kunnen we op 2 manieren bewijzen.
**eerste methode**

![[Pasted image 20211227173526.png]]

voor alle n ∈ N \ {0, 1}

we kunnen deze formule ook herschrijven als n >= 3

d$_n$ = (n - 1) ( d$_n$ $_-$$_1$ + d$_n$ $_-$$_2$)

**tweede methode**

zie p 42