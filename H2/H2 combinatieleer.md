# Combinatieleer

###### variatie
Een variatie van k uit de n elementen is een geordend k-tal van k verschillende elementen gekozen uit een verzameling van n elementen. 

P(n, k) of V$_n$$^k$ = n! / (n - k)!

voor alle n,k ∈ N* met k<=n geldt
V$_n$$^k$ = n (n - 1) ... (n - (k - 1))

*bewijs*
Als we het 1ste element kiezen, kan dit op n manieren.  het 2de element op n-1 manieren enz tot de kde keuze die dan op n-(k-1) manieren gekozen kan worden. In totaal zijn er dus 
n (n-1)... (n - (k - 1)) mogelijke variaties voor k uit de n elementen

###### permutatie
Een variatie van n uit de n elementen. De volgorde is belangrijk en de elementen zijn verschillend.

P(n, n) of P$_n$= n!

0! =1

###### combinaties
een combinatie van n uit de k elementen is een deelverzameling met k elementen uit een gegeven verzameling n. combinaties worden ook wel binomiaalcoëfficienten of binomiaalgetallen genoemd. De volgorde is niet van belang maar de elementen zijn wel verschillend.

C$_n$$^k$ of C(n, k) of ($_k$$^n$) = V$_n$$^k$  / k! = n! / (n-k)! k!

  V$_n$$^k$ = ($_k$$^n$) \* k! 
*bewijs* 
een variatie van k uit de n elementen kan gevormd worden door eerst een deelverzameling van k uit de n elementen te nemen ($_k$$^n$). Daarna kan de volgorde bepaald worden met een permutatie van k!.

[[H2 Driehoek van pascal en eigenschappen combinaties]]

###### herhalingsvariaties
de volgorde is van belang maar herhaling is toegestaan.
P(n,k)\_=n$^k$

###### herhalingscombinaties
Bij herhalingscombinaties is de volgorde niet van belang en is herhaling toegestaan.
C$_n$$_+$$_k$$_-$$_1$$^k$ 

