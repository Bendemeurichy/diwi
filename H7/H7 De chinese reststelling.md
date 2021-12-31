### de chinese reststelling
Veronderstel dat m$_1$, ... ,m$_k$ positieve natuurlijke getallen zijn die 2 aan 2 onderling ondeelbaar zijn m.a.w. gcd( m$_i$, m$_j$ )=1 als i $\neq$  j.
![[Pasted image 20211231131918.png]]

Beschouw verder voor elke i een b$_i$ ∈ N[0, m$_i$-1]. Dan heeft het stelsel lineaire congruenties
![[Pasted image 20211231132054.png]]
juist 1 oplossing modulo M

*bewijs*
beshouw de afbeelding 
![[Pasted image 20211231132133.png]]

Deze afbeelding is goed gedefinieerd, d.w.z. dat de uitrdukking ([t]$_m$$_1$, ... ,[t]$_m$$_k$) onafhankelijk is van de keuze van de representant t ∈Z voor het element [t]$_M$  ∈Z/M. inderdaad, veronderstel dat s $\equiv$ t (mod m); dan is M | s-t , en bijgevolg is m$_i$ | s-t, dwz s$\equiv$ t(mod m$_i$ ) voor elke i ∈ {1, 2, ... , k}.

Vervolgens gaan we na dat deze afbeelding injectief is. Indrdaad, veronderstel dat s, t ∈Z zodanig zijn dat $\theta$ ([s]$_m$) = $\theta$ ([t]$_m$). dan is s$\equiv$ t (mod m$_i$ ) en dus m$_i$ | s-t voor elke i ∈{1, ... ,k}.
Omdat de m$_i$'s onderling ondeelbaar zijn, volgt uit de stelling stelling 6.2.5 nu dat M|s-t, en dus is s$\equiv$ t (mod M). Hieruit volgt dat $\theta$ injectief is.
Merk nu op dat Z/M en Z/m$_1$ x ... x Z/m$_k$ evenveel elementen bevatten (namelijk M).

Een injectie tussen 2 verzamelingen die dezelfde eindige kardinaliteit hebben, is echter noodzakelijk een bijectie, en dus besluiten we dat $\theta$ een bijectie is.
In het bijzonder is err juist één element [t]$_M$ ∈ Z/M waarvoor 
$\theta$( [t]$_M$ ) = ( [b$_1$]$_m$$_1$, ... , [b$_k$]$_m$$_k$ )
en dat is wat we wilden bewijzen