### priemgetallen
Een positief getal p wordt eeen priemgetal genoemd  als p precies 2 positieve delers bezit (1 en zichzelf). 1 is geen priemgetal. 
Elk getal kan dus geschreven worden als het product van 2 priemgetallen.

*bewijs*
We passen het principe van het [[H2 inductie en het kleinste tegenvoorbeeld#het kleinste tegenvoorbeeld|kleinste tegenvoorbeeld]] toe.
veronderstel dus dat m het kleinste getal is in N\{0,1} dat niet te schrijven is als het product van priemfactoren. 
Dan kan m vanzelfsprekend geen priemgetal zijn, en dus moet m samengesteld zijn: stel m = m$_1$m$_2$ met m$_1$, m$_2$ ∈ N \{2,m-1}. Aangezien echter m het kleinste tegenvoorbeeld was, bezitten zowel m$_1$ als m$_2$ elk een ontbinding in priemfactoren. Hieruit kunnen we afleiden dat m zelf ook een ontbinding van priemfactoren bevat en dat is tegen de veronderstelling dat m het kleinste tegenvoorbeeld was. Hiermee hebben we de stelling bewezen

###### stelling van euclides : 
*De verzameling van de priemgetallen is een oneindige verzameling.*

*bewijs*
veronderstel dat de verzameling van priemgetallen een eindige verzameling is {p$_1$,p$_2$,...,p$_n$}.
Stel m = het product van alle priemgetallen in deze verzameling, dan is m+1 dus geen priemgetal en dus bezit m+1 eigenllijke delers. 
noem q de kleinste positieve eigenlijke deler van m+1. Dan is q dus een deler van m. Bijgevolg is q een deler van (m+1)-m=1. Dit is een tegenstrijdigheid. Bijgevolg is de verzameling van de priemgetallen een oneindige verzameling.


###### de zeef van Eratosthenes
Een snelle manier om de priemgetallen te vinden tot aan een bepaald natuurlijk getal n is door alle even getallen te schrappen <=n buiten 2, dan de overgebleven oneven getallen verschillend van 1 te ranschikken van klein naar groot en voor elk getal dat niet geschrapt is de veelvouden van dit getal te schrappen >het getal zelf. 
Uiteindelijk komen we met de niet gescrapte getallen de priemgetallen tot en met n uit 