Teorijski deo
---

Dati sto konciznije odgvore u formi prosto prosirenih recenica na svako od sledecih pitanja.

01. Sta je to JSON?
To je tekstualni jednostavan format za razmenu podataka, zasnovan na principima C jezika.
02. Sta je to XML?
Extensible markup language. To je textualni format za razmenu podataka na World wide web-u, intranetu itd.
03. Sta je to URL?
Uniformni resursni lokator. Slozen niz karaktera koji se korsiti za lociranje nekog resursa na internetu.
04. Sta je to HTTP?
Hypertext transfer protocol. Metod prenosa informacija na web-u.
05. Sta je to RESTful API?
To je aplikacija koja obradjuje zahteve dobijene preko http protokola za obradu podataka.
06. Koje HTTP metode imamo?
GET, HEAD, POST, PUT , DELETE, TRACE, OPTIONS, CONNECT, PATCH
07. Sta je to DNS?
Domain name system. Sistem koji pretvara imena racunara u IP adrese.
08. Sta je to private IP?
Privatna adresa koja nema direktan pristup internetu.
09. Sta je to AJAX?
Asinhroni javascript i XML. To je web interaktivna aplikacija koja se koristi za brzu i momentalnu obradu podataka koju salje korisnik. 
10. Sta je to TCP/IP?
Protokol ili skup protokola koji omogucava umrezenim racunarima da razmenjuju resurse putem mreze.
11. Sta je to kes memorija?
Mala memorija koja sluzi za cuvanje podataka koji se cesto koriste.
12. Koja je razlika izmedju klase i objekta?
Klasa je obrazac (templejt) po kome nastaja objekat, a objekat je instanca klase. Objekat je fizicka kategorija, a klasa logicka. Postoji mnogo nacina da se definise objekat,. ali samo jedan da se definise klasa.

Backend
---

1. U `models.py` fajlu implementirati `Comment` model (klasu) u Python-u koja sadrzi atribute:
- `text`: sam komentar, i
- `date`: datum komentara u formatu `YYYY-MM-DD`
"Override"-ovati `__repr__` metod.

2. U `models.py` fajlu definisati `COMMENTS` varijablu koja sadrzi niz od 3 elementa koji su tipa `Comment`. 

3. U `app.py` fajlu napraviti Flask applikaciju koja ima `index` "view" funkciju koja handle-uje `/` route. Funkcija bi trebalo da vraca HTML string koji u `body`-ju sadrzi heading "Welcome!".

4. U `app.py` dodati `comments` "view" funkciju koja handle-uje `/comments` route. Funkcija bi trebalo da vraca HTML koji u `body`-ju sadrzi tabelu komentara. Koristiti Flask template.

5.  U `app.py` dodati `api_comments` "view" funkciju koja handle-uje `/api/v1.0/comments` route. Funkcija bi trebalo da vraca JSON reprezentaciju `COMMENTS` niza.

Frontend
---

U `home.html` fajlu imlementirati jednostavnu klijent aplikaciju kojom moze da testira prethodno implementirani API end point. Koristiti `form` i `iframe`.

Algoritmi
---

Napisati i JavaScript i Python funkciju koja predstavlja resenje sledeceg zadataka:

Write a program that prints the numbers from 1 to 100. But for multiples of three print `Fizz` instead of the number and for the multiples of five print `Buzz`. For numbers which are multiples of both three and five print `FizzBuzz`.

Uputstvo
---

Resenja i odgovore predati u okviru GitHub repozitorijuma.
