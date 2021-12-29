# De gehele getallen
---
##### notaties voor de verzamelingen
**natuurlijke getallen**
N = {0, 1, 2, 3,...}
N*= {1, 2, 3,...} = N \ {0}

**gehele getallen**
Z = {..., -3, -2, -1, 0, 1, 2, 3, ...}
Z$^-$ = {..., -3, -2, -1, 0}
Z$^+$ = {0, 1, 2, 3, ...}
Z$^-$\* = {..., -3, -2, -1}
Z$^+$\* = {1, 2, 3, ...}
---
N [a,b] = { a, a+1, a+2, ..., b-1, b} met a\<b
N[a,b] = Ø met a\>b

### De optelling en de vermenigvuldiging
In de verzameling van de gehele getallen gelden de volgende axioma's voor de bewerkingen van de optelling en de vermenigvuldiging.

De optelling en vermenigvuldiging zijn \-
* *inwendige bewerkingen:* a,b ∈ Z dan a+b ∈ Z en ab ∈ Z
* *commutatieve of abelse bewerkingen*: a + b = b + a en ab = ba
* *associatieve bewerkingen:* (a + b) + c = a + (b + c) en a(bc) = (ab)c
* het getal 0 is het *neutraal element* voor de optelling en 1 is het *neutraal element* voor de vermenigvuldiging
* *links- en rechtsdistributief* voor de vermenigvuldiging t.o.v. de optelling
* elk geheel getal a bezit een tegengesteld geheel getal -a zodat a + (-a) =0
* *de schrappingswet* als ab = ac en a ≠ 0 --> b = c

De meeste rekenregels kunnen uit deze axioma's worden afgeleid
bv: a - b := a + (-b)

### de ordening van de gehele getallen

Een relatie is een *partiële orderelatie* als ze reflexief, anti-symmetrisch en transitief is. [[H1 verzamelingen en relaties#equivalentierelaties]]
**poset = partially ordered set**

Een relatie is een *totale orderelatie* als dit een partiële orderelatie is voor alle elementen --> voor alle a,b geldt aRb of bRa

Strikte orderelaties zijn transitief en anti-reflexief

>2 axiomas die gelden voor =<
>- voor alle a, b, c geldt als a <= b dan ook a+c <= b+c
>- voor alle a, b, c geldt als a <= b en c>=0 dan ook ac<=bc

##### het axioma van de goede ordening
Noem X een willekeurige deelverzameling van Z, dan is er een benedengrens b waarvoor geldt
b<=x, ∀x ∈ X, als de benedengrens element is van X dan wordt b het kleinste element genoemd. Als X een kleinste element heeft,  is dit uniek.

>(axioma van de goede ordening)
>als X ≠ Ø een deelverzamelng is van Z en een benedengrens heeft, dan bezit X een kleinste element.

Het axioma van de goede ordening laat ons toe om recursieve definities op te stellen van bepaalde bewerkingen met de notaties 

![\displaystyle\sum a_i~\\*~\\*~\\*=~a_1+a_2+a_3+...](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle%5Csum+a_i%7E%5C%5C%2A%7E%5C%5C%2A%7E%5C%5C%2A%3D%7Ea_1%2Ba_2%2Ba_3%2B...&bg=ffffff&fg=000000&s=2&c=20201002)


![\displaystyle\prod_{n=0}^{3}(n+x)\\*~\\*~\\*=(0+x)(1+x)(2+x)(3+x)](https://s0.wp.com/latex.php?latex=%5Cdisplaystyle%5Cprod_%7Bn%3D0%7D%5E%7B3%7D%28n%2Bx%29%5C%5C%2A%7E%5C%5C%2A%7E%5C%5C%2A%3D%280%2Bx%29%281%2Bx%29%282%2Bx%29%283%2Bx%29&bg=ffffff&fg=000000&s=2&c=20201002)