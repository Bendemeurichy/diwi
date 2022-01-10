### lcm en gcd
###### stelling van Bézout
Als a en b gehele getallen zijn die niet beide nul zijn en dat d =gcd(a,b). dan bestaan er gehele getallen m en n zodanig dat am+bn=d

###### gevolgen stelling bézout
als voor drie gehele getallen a,b,c met (b,c)≠(0,0) geldt dat c|ab en dat gcd(b,c)=1, dan is c|a

*bewijs*
uit gcd(b,c)=1 volgt dat er m,n ∈ Z bestaan zodat mb+nc=1; hieruit volgt dat mab +nac=a. Aangezien c|ab per veronderstelling, is ook c |mab , en uiteraard ook c|nac, zodat c|mab+nac en bijgevolg c|a
___

indien p een priemgetal is en indien x$_1$, x$_2$, ... ,x$_n$ gehele getallen zijn zodanig dat p een deler is van hun product,
p | x$_1$ x$_2$ ... x$_n$
dan is p een deler van ten minste één x$_i$ ( i ∈ N[1,n] )

*bewijs*
Indien p | ab met a,b ∈ Z, dan p|a of p|b het algemene resultaat volgt dan per inductie op n.
Stel dus dat p | ab, en veronderstel dat p $\nmid$ b; we moeten bewijzen dat dan p|a. Merk op dat p $\nmid$ b impliceert dat gcd(b, p)=1. We kunnen dus de vorige stelling toepassen met c=p, en we besluiten dat p | a.
___
De ontbinding van een natuurlijk getal n>= 2 in priemfactoren is uniek op de volgorde van de factoren na

*bewijs*
we gebruiken het principe van het [[H2 inductie en het kleinste tegenvoorbeeld#het kleinste tegenvoorbeeld|kleinste tegenvoorbeeld]]. veronderstel dus dat er een kleinste natuurlijke getal >=2 bestaat waarvoor dit niet waar is, daarom is
![[Pasted image 20211230171540.png]]

waarbij p$_i$ ( i ∈ N[1,k] ), evenals p$^´$$_j$  ( j ∈ N[2,l] ) (niet noodzakelijk onderling verschillende) priemgetallen zijn. Hieruit volgt dat
![[Pasted image 20211230172233.png]]

en dus wegens voorgaande stelling dat p$_1$ ten minste één van de getallen p$^´$$_j$ deelt.
Zonder de algemeenheid te schaden, mogen we veronderstellen dat p$_1$ | p$^´$$_1$ ,
Aangezien beide getallen echter priemgetallen zijn, volgt hieruit dat p$_1$ = p$^´$$_1$
![[Pasted image 20211230173142.png]]

dit is echter in strijd met de veronderstelling dat n$_0$ het kleinste getal is dat 2 verschillende ontbindingen in priemfactoren bezit. bijgevolg bestaat n$_0$ niet en mogen we besluiten dat de stelling bewezen is voor elke n>=2