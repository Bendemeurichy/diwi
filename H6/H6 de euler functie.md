### de euler functie
Veronderstel dat n een positief getal is waar met Φ(n) het aantal natuurlijke getallen uit N[1, n] die copriem zijn met n. Indien n=p een priemgetal is dan is Φ(p)=p-1

veronderstel dat n>= 2 een natuurlijk getal is met priemfactorontbinding n =p$_1$$^e$$^1$ p$_2$$^e$$^2$ ...p$_k$$^e$$^k$ waarbij p$_1$ ,p$_2$ ,...p$_k$ onderling verschillende priemgetallen zijn en e$_1$,e$_2$, ... ,e$_k$ ∈ N*. Dan is

![[Pasted image 20211230192932.png]]

*bewijs*
Voor elke j ∈ N[1,k], noem A$_j$ de deelverzameling van N[1,n] die de veelvouden van p$_j$ bevat. Dan geldt
![[Pasted image 20211230194813.png]]

Hierbij is α$_i$ ([[H2 toepassingen op combinatieleer#het veralgemeende inclusie-exclusie principe|veralgemeend inclusie-exclusie principe]]) de som van de kardinaalgetallen van al de mogelijke doorsneden die men kan vormen met i dergelijke verzamelingen (i ∈ N[1,k] ). De doorsnede van i dergelijke verzamelingen, zoals

![[Pasted image 20211230200048.png]]

bevat de veelvouden in N[1,n] van P = p$_j$$_1$ p$_j$$_2$ ...p$_j$$_i$ en bevat bijgevolg de natuurlijke getallen
P, 2P, ..., (n/P)P

Deze doorsnede bevat bijgevolg n/P getallen,en α$_i$ is de som van alle termen van de vorm
n/P= n(1 / p$_j$$_1$) (1 / p$_j$$_2$) ...(1 / p$_j$$_i$ )
waarbij 1<=j$_1$ < j$_2$ < ... <j$_i$ <= k. Hieruit volgt dat

![[Pasted image 20211230201835.png]]

___
###### gevolgen eulerfunctie
1) indien de positieve natuurlijke getallen n en m geen gemeenschappelijke priemfactoren hebben is Φ(mn)=Φm\*Φn
dit volgt onmiddelijk uit de formule voor de euler functie

2) voor elk natuurlijk getal n geldt dat de som van Φ van alle delers van n  =n

**bewijs**
het aantal positieve breuken kleiner dan of gelijk aan 1 met noemer gelijk aan n, maw van de vorm k/n met k<=n
is uiteraard gelijk aan n. als we deze breuken nu zo ver mogelijk vereenvoudigen , dan krijgen we voor elke deler d van n een aantal breuken van de vorm j/d met j<=d en gcd(j,d)=1

Voor elke d zijn er bijgevolg Φ(d) dergelijke breuken.Elk van de n breuken heeft juist één vereenvoudigde vorm, zodat de stelling bewezen is.