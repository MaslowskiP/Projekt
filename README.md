# ATOM - aplikacja do zarządzania magazynem slekpów interentowych

Aplikacja pomagająca w zarządzaniu magazynem w małych i średnich sklepach internetowych. Program wyświetla listę produktów, które należy skompletować. Użytkownik wyświetlić zdjęcia produktów. Po znalezieniu produktu można go w odpowiedni sposób oznaczyć tak aby zniknął z listy. Aplikacja działa na najnowszych wersjach systemu Android. Projekt został stworzony w ramach zaliczenia przedmiotu Bogate Aplikacje.

## Uruchomienie aplikacji

Aby uruchomić aplikację należy skompilować program np. używając do tego narzędzi dostarczonych przez Adobe, znajdujących się na stronie:
```
https://build.phonegap.com
```

## Opis dziłania programu

Po swoim uruchumieniu aplikacja sprawdza czy są zapisane jakiś produkty w bazie danych ze statusem 0. Status ten oznacza że produkty nie zostały jeszcze znalezione. Jeżeli znajdzie takie produkty, wyświetla je użytkownikowi w formie listy za pomocą funkcji dodaj(). Użytkownik może też wcisnąć przycisk "Pobierz listę" dzięki któremu cała baza danych zostanie skasowana a następnie zasilona danymi z nowej listy. Użytkownik może nacisnąc przycisk "Zdjęcie" aby wyświetlić zdjęcie produktu. Przyciski "Brak", "Ostatni", "Uszkodzony" oraz "Znaleziono" służą do odpowiedniego oznaczenia każdego produktu. Po ich naciśnieciu pozycja ta znika z listy i dostaje inny status w bazie danych. Możliwe jest cofnięcie jednego oznaczenia przez użycie przycisku "Cofnij". Przywraca on produkt na listę jak również wcześniejszy stan w bazie danych. Po skończeniu wybierania produktów możliwe jest stworzenie raportu. Raport jest generowany automatycznie. Po przeczytaniu raportu użytkownik może go zedytować oraz wysłać mailem.

![](http://wizard.uek.krakow.pl/~s181008/1.png)
![](http://wizard.uek.krakow.pl/~s181008/3.png)
![](http://wizard.uek.krakow.pl/~s181008/2.png)

## Użyte pluginy Phonegapa

Przy projekcie użyto następujących wtyczek:
```
https://github.com/apache/cordova-plugin-whitelist.git - pozwala na dodanie stron interentowych na "białą liste"
https://github.com/katzer/cordova-plugin-email-composer.git - obsługa emaila
https://github.com/apache/cordova-plugin-splashscreen.git - pozwala na dodanie splashscreena
```

## Autorzy projektu

Piotr Masłowski<br>
Adrian Myszor
