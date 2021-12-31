### verzamelingen
##### basisnotaties

![[basisnotaties verzamelingen.png]]

##### definities

*verzameling*:  een groep van verschillende en duidelijk gedefinieerde dingen (=*elementen*), indien de elementen niet verschillend moeten zijn spreken we van een *familie* of *multiverzameling*

*singelton*: verzameling van 1 element

##### eigenschappen
1. *Commutatieve eigenschap*
	A Ս B = B Ս A
	A ∩ B = B ∩ A
	
2. *Associatieve eigenschap* 
	A ∩ (B ∩ C) = (A ∩ B) ∩ C
	A Ս (B Ս C) = (A Ս B) Ս C
3. *Distributieve eigenschap*
	A ∩ (B Ս C) = (A ∩ B) Ս (A ∩ C)
	A Ս (B ∩ C) = (A Ս B) ∩ (A Ս C)
4. *Wetten van de Morgan*
	(A Ս B)$^c$ = A$^c$  ∩ B$^c$
	(A ∩ B)$^c$ = A$^c$ Ս B$^c$
	
[[paradox van Russel]]
### relaties
*cartesisch product*
	A x B = { (a,b) | a∈A, b∈B }
>**algemenere notatie voor cartesisch product van k verzamelingen:**
>A$_1$xA$_2$x...xA$_k$ = { (a$_1$,a$_2$,...,a$_k$) | a$_i$ ∈ A$_i$ , i = 1,2,...,k }

vanzelfsprekend is AxB ≠  BxA
##### relatie
Een relatie van de verzameling A naar verzameling B is een deelverzameling van het cartesisch product van de 2 verzamelingen en kan genoteerd worden als:
- aRb (*infix*)
- R(a,b) (*prefix*)
###### bijzondere relaties
*een functie:* een functie van A naar B is een relatie waarbij elk element van A ==hoogstens== 1 beeld in B heeft.

*Een afbeelding:* een relatie van A naar B waarbij elk element van A ==juist 1== beeld heeft.

*injectieve relatie:* een relatie van A naar B waarbij elk element van B het beeld is van ==hoogstens 1== element van A.

*surjectieve relatie:* een relatie van A naar B is een relatie waarbij elk element van B het beeld is van ==minstens 1== element van A.

*bijectie;* een afbeelding van A naar B die zowel een injectie is als een surjectie. (elk element van A heeft 1 beeld in B)

*permutatie:* een bijectie van A op zichzelf.

###### equivalentierelaties
*reflexieve relatie:* een relatie R ⊆ A² waar het elk element in relatie staat met zichzelf m.a.w. het identieke koppel (x,x) behoort tot de relatie R. 
Een *antireflexieve relatie* is een relatie waarbij geen enkel element in relatie staat met zichzelf.
Als de relatie *niet reflexief* is betekent dat niet alle elementen in relatie staan met zichzelf maar wel een aantal.

*symmetrische relatie:* een relatie R ⊆ A² waar als x in relatie staat met y, y ook in relatie staat met x. (xRy --> yRx)
De relatie is *antisymmetrisch* indien als x in relatie staat met y, y enkel in relatie staat met y als x=y. (xRy en yRx --> x=y)
*niet symmetrisch* is als de niet voor alle koppels x,y geldt dat als x in relatie staat met y,  y ook in relatie staat met x

*transitieve relatie:* een relatie R ⊆ A² waar als x in relatie staat met y en y met z, dan staat x ook in relatie met z (xRy en yRz --> xRz)

> een equivalentierelatie is een relatie R ⊆ A² die zowel reflexief, symmetrisch en transitief is. Dit betekent dus dat als aRb dat a≡b

Alle elementen die equivalent zijn met a is een verzameling die een equivalentieklasse wordt genoemd, a is dan de representant voor deze klasse en wordt genoteerd als [a].
Hieruit volgt dat geen enkele equivalentieklasse ledig kan zijn, de doorsnede van 2 equivalentieklassen ledig is en de unie ervan de volledige verzameling is waarvoor de equivalentierelatie geldt.
>elke deelverzameling waarvoor elk element niet tot een andere deelverzameling hoort wordt een partitie genoemd. In een equivalentierelatie geldt dat 2 elementen enkel in relatie staan met elkaar als ze tot dezelfde partitie behoren.



	
	
	
	
	