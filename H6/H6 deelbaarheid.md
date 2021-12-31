### deelbaarheid
elk geheel getal b ≠ 0 is uiteraard deelbaar door 1, -1, b, -b; Dit worden vaak de onechte delers genoemd.
veronderstel a|b en a|c dan geldt voor alle gehele getallen a|(bx+cy), in het bijzonder is a dan een deler van b+c en van b-c.

In plaats van te zeggen 2|b zeggen we b is even en 2 $\nmid$  b oneven.

voor elke 2 getallen a ∈ N* en b ∈ Z bestaan er unieke gehele getallen q(quotiënt) en r(rest) zodanig dat 
b=a*q+r waarbij r ∈N[0,a-1]

*bewijs*
(a) we tonen aan dat q en r bestaan. We passen het axioma van de goede ordening toe op de verzameling R ={ x ∈ N| b = a\*y+x voor een y ∈ Z}

we bewijzen eerst dat R niet ledig is. als b>= 0, dan volgt uit b =  a*o +b dat b ∈ R. als b<0, dan geldt b = a\*b+(1-a)b

aangezien (1-a)b >= 0 zal (1-a)\*b ∈ R. De verzameling R is dus niet ledig en bezit bijgevolg een kleinste element r. We hebben dan b=q\*a+r voor een zekere q∈Z. als r >=a, dan hebben we eveneens dat b = a \*(q+1)+(r-a) met r>r-a>=0, in tegenstrijd met de definitie van r. Bijgevolg geldt r ∈ N[0,a-1]

(b) We tonen de uniciteit aan van q en r. Onderstel dat b = a\*q$_1$+r$_1$ = a\*q$_2$+r$_2$ voor zekere q$_1$,q$_2$ ∈ Z en zekere r$_1$,r$_2$ ∈ N[0,a-1]. als q$_1$>q$_2$, dan geldt r$_2$=a(q$_1$-q$_2$)+r$_1$>=a+r$_1$>=a, een tegenstrijdigheid . bijgevolg geldt q$_2$>=q$_1$. we kunnen nu de rol van q$_1$ en q$_2$ omkeren, waaruit dan volgt dat q$_1$>=q$_2$, zodat we mogen besluiten dat q$_1$=q$_2$ en r$_1$=r$_2$ 