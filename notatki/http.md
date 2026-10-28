date - pokazuje obecna date
dir - pokazuje pliki
users - wyswietla uzytkownikow

info.cern.ch - 
curl -v http://info.cern.ch
Zwrocony jest kod strony

github.com - 
curl -I http://github.com/
Zwrocony jest blad 301, strona zostala przeniesiona na adres https://github.com/

info.cern.ch/nie-ma-takiej -
curl -I http://info.cern.ch/nie-ma-takiej
Zwrocony jest blad 404 - strony nie znaleziono

spacejam.com/1996
18 żądań
przeslano 66,62 kB
119 elementow DOM
najciezszy element 