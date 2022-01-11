### eindige verzameling
Een verzameling X, zodanig dat er een natuurlijk getal n ∈ N is waarvan er een [[H1 verzamelingen en relaties#bijzondere relaties|bijectie]]
bestaat van de verzameling N[1, n] naar X. n wordt dan de kardinaliteit of orde van X genoemd en wordt genoteerd als:
|X|=n of \[[X]] = n.
>elke verzameling die niet eindig is wordt een oneindige verzameling genoemd.

### aftelbare en overaftelbare verzamelingen
Een oneindige verzameling X wordt aftelbaar genoemd als er een [[H1 verzamelingen en relaties#bijzondere relaties|bijectie]] bestaat van N naar X. Indien dit niet het geval is, dan is X een niet-aftelbare of overaftelbare verzameling.
Alle eindige verzamelingen zijn aftelbaar.

###### de verzameling van Z is aftelbaar
beschouw de afbeelding van N naar Z gedefineerd door

f(n)= n/2 als n even is
		-(n+1)/2 als n oneven is

hieraan zien we dat de afbeelding inderdaad een bijectie is want de rij ziet er uit als (0, -1, 1, -2, 2, ...)

###### verzameling van Q is ook aftelbaar
Er bestaat terug een bijectie van N naar Q waarvan de rij van waarde er uitziet als:
(0, -1, 1, -2, -1/2, 1/2, 2, -3, -3/2, -2/3, -1/3, 1/3, 2/3, 3/2, 3,...)

om de plaats van a/b in de rij te bepalen, maken we gebruik van niveaus.
We nemen max(|a| / b) als niveau van a/b. binen elk niveau worden de getallen geranschikt van klein naar groot 

![[niveaus aftelbaarheid Q.png]]

aangezien er voor elk niveau een eindig aantal rationale getallen a/b bestaat volgt dat Q aftelbaar is.

###### de verzameling R is een niet aftelbare verzameling
We bewijzen dit door aan te tonen dat het interval [0, 1] van R een niet-aftelbare verzameling is, we gebruiken hiervoor cantor's diagonaalmethode.
veronderstel dat [0, 1] wel aftelbaar is dan zou de bijectie f van N naar [0, 1] er als volgt uitzien.

f(0) = 0, a$_0$ b$_0$ c$_0$ d$_0$...
f(1) = 0, a$_1$ b$_1$ c$_1$ d$_1$...
f(2) = 0, a$_2$ b$_2$ c$_2$ d$_2$...
f(3) = 0, a$_3$ b$_3$ c$_3$ d$_3$...

hierbij staan a,b,... voor één van de cijfers van 0 tot en met 9. getallen met een oneindige rij aan 0 of 9 kunnen op meerdere manieren geschreven worden, andere getallen zijn uniek.
We nemen een getal x tussen 0 en 1 dat niet in de lijst kan voorkomen.
x=0, x$_1$ x$_2$ x$_3$ x$_4$...

waarbij
x$_i$ = a/b/c/...$_i$ + 1 als a/b/c/...$_i$ <= 7
1 als a/b/c/...$_i$ ∈ {8, 9}

omdat x$_i$ nooit gelijk is aan 0 of 9 is de definitie van x altijd uniek. nu zal voor elke n ∈ N het getal x verschillend zijn van f(n) als beide getallen verschillen op de (n+1)ste plaats na de komma. bijgevolg is het interval [0, 1] en dus ook de verameling R niet aftelbaar zijn