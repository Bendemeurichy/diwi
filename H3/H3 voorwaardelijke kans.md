### voorwaardelijke kans
De voorwaardelijke kans is de kans dat een gebeurtenis zich voordoet na een andere gebeurtenis zich al heeft voorgedaan.
P(A | B) = P(A ∩ B) / P(B)

Tenzij als P(B)=0 is dan is P(A | B) niet gedefinieerd.

De gebeurtenissen A en B waarvoor P(A) ≠ 0 kunnen herschreven worden als 
P(A ∩ B)= P(A | B)\* P(B)

###### vermenigvuldigingsregel
![[Pasted image 20211228144815.png]]

###### de totalekansformule
veronderstel een uitkomstenverzameling S met A$_i$ onderling disjuncte partities waarbij P(A$_i$)≠ 0. Dan geldt voor een willekeurige gebeurtenis B ⊆ S dat 
P(B)=P(A$_1$) P(B | A$_1$) + ... + P(A$_n$) P(B | A$_n$)

*bewijs*
we hebben B = de doorsnede van B met alle A$_i$ waarbij de doorsnedes onderling disjunct zijn. Door de vermenigvuldigingsregel toe te passen op de doorsnedes verkrijgen we de totalekansformule voor P(B)

###### regel van Bayes
indien we een uitkomstenverzameling hebben met A$_i$ gebeurtenissen die een partitie vormen waarvoor alle P(A$_i$)≠0. dan geldt voor een willekeurige gebeurtenis B ⊆ S waarvoor P(B) ≠ 0

P(A$_i$ | B) = P(A$_i$) P( B | A$_i$) / P(B)

*bewijs*
aangezien P(B) P(A$_i$ | B) en P(A$_i$) P( B | A$_i$) beiden gelijk is P (A$_i$ ∩ B). Met de totalekansformule kunnen we de noemer van het rechterlid ook nog verder uitschrijven.

 >inferentie (inference)
 >Om de kans dat een bepaalde oorzaak een effect veroorzaken kunnen we ook de regel van Bayes gebruiken. de kans op een bepaalde oorzaak na het voordoen van een bepaald effect = P (A$_i$ | B)

