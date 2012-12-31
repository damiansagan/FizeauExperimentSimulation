## Eksperyment Fizeau - zespół Segmentation Fault

###Jakość projektu:

* ***Spełnienie wymogów formalnych 2pkt:***  
Wymogi spełnione 							**2pkt**  
* ***Ładny układ kodu 2-4pkt:***  
Wersja DRY, program napisany jest bardzo starannie 	**4pkt**  
* ***Estetyczny wygląd programu 0-3pkt:***  
Wszystko skaluje się dokładnie jak powinno 	**3pkt**  
* ***Program działa intuicyjnie 0-3pkt:***  
Uważamy że program działa najintuicyjniej jak się da w przypadku tego rodzaju projektu **3pkt**  
* ***Brak wymienionych błędów: 0pkt***  

*Razem za jakość projektu: 12pkt, ocena 5 i 2pkt zapasu*

****************************************************************************************************
###Funkcjonalność projektu:

* Zarówno obliczenia (jak i prezentacja wyników) są wykonywane w jednostkach fizycznych (np. prędkość jest wyznaczana w (m)/(s).  
* Model jest kompletny tj. możliwie dokładnie modeluje dane zjawisko, nie pomijając żadnych efektów fizycznych.  

* Za pomocą interfejsu programu można sterować wszystkimi istotnymi parametrami symulacji, oraz są przynajmniej cztery takie parametry: **2pkt**  
* Animacja jest bardziej zaawansowana, na przyklad: zawiera ładne tło, kilka obiektów **2pkt**  
* Program zawiera sensowne materiały pomocowe dla uczniów, które wyświetlają się po kliknięciu na jakiś element interfejsu **1-2 pkt**  
* Skorzystanie z technik/bibliotek nie omawianych na wykładzie: **1-3 pkt**  
***Zastosowano design pattern: Observer. Na wykładzie nie było nic mowy o design patternach. Stworzyliśmy listenery dla modelu obliczeniowego i  animacji. Bez nich program straciłby na fukncjonalności oraz jakości. Dzięki temu zmiany w modelu przeładowują pola w GUI, a prędkość światła wyświetlana jest dopiero gdy efekt mający fundamentalne znaczenie w eksperymencie - zajdzie.***  
* Wykorzystano również nowoczesne techniki wprowadzone w JDK 1.8 - funkcje lambda  
* Wyniki wyświetlane są kilku różnych wykresach, między którymi można przełączać **1-2pkt**  
* Wykresy są animowane (tj. zmieniają się w czasie obliczeń)	**1pkt**  
* Wyniki działania programu są możliwe do pobrania w postacji plków tekstowych z danymi, bądż obrazków **1-3pkt**  
* Program powstaje w przy użyciu systemu kontroli wersji Git, w publicznym repozytorium, i jest dostępny na licencji open source **2pkt**  
***Obie osoby używają repozytorium: https://github.com/damiansagan/fizeau***  
* Program jest wielojęzyczny (ma wersje językowe przynajmniej polską i angielską) **1pkt**  
* Wielojęzyczność zaimplementowano za pomocą mechanzmu internacjonalizacji wbudowanych w JDK **1pkt**  

*Razem za funkcjonalność projektu: max 18pkt, ocena 5 i 8pkt zapasu*

****************************************************************************************************
## Dodatkowe funkcjonalności opisane w danym projekcie: 
* Automatyczny wybór parametrów eksperymentu. *(do oceny prowadzącego)*  
* Programy predefiniowane wyboru parametrów eksperymentu.	*(do oceny prowadzącego)*	 
