### 4. Założenie konta github
Github jest zasadniczo usługą darmową, umożliwia na założenie darmowego konta i posiadanie maksymalnie dwóch repozytoriów prywatnych i jakąś ilość repozytoriów publicznych. W trakcie szkoleń będziemy korzystać z githuba do przesyłania plików, więc prośba o założenie kont pod linkiem: https://github.com/

### 5. Instalacja gita
Gita instalujemy z linku: https://git-scm.com/download/win wybieramy wersję naszego systemu pobieramy i instalujemy gita.

![obraz](https://user-images.githubusercontent.com/109360131/200548247-f0fe66c5-2c8e-4cef-943d-ac2acb60e6f6.png)

Generalnie nie będę wchodził tutaj bardzo w szczegóły, tak naprawdę instalujemy gita na ustawieniach domyślnych i to jest zasadniczo to czego będziemy potrzebować. Opcjonalnie w trakcie instalacji możecie zaznaczyć, aby nazwą głównej gałęzi było "main" zamiast "master", ale zrobimy to także później z Basha. Po instalacji możemy sprawdzić, czy git został zainstalowany poprawnie wchodząc w wiersz poleceń i wpisując instrukcję git –version:

![obraz](https://user-images.githubusercontent.com/109360131/200548313-874ab747-d752-481e-a3bb-caed166a9aa7.png)


Powinniśmy dostać wynik przypominający obraz wyżej, tzn. odpowiedź gita z aktualną zainstalowaną wersją. Git zainstalował też swoje wiersze poleceń – ja będę korzystał z aplikacji Git Bash, który korzysta z komend linuxowych, więc było mi trochę łatwiej się go uczyć bez nauki komend windowsowych. 


## Zadanie 1
Zapoznaj się z instrukcjami przechodzenia między folderami - zobacz jak działają instrukcje `cd`, `cd --`, `cd ..` oraz `cd ~/`.

Po tym dodaj nowy folder w folderze dokumenty, w którym będziesz przechowywał zadania/projekty z tego szkolenia, w nim stwórz folder z zadaniami z tej części (oczywiście wszystko w Bashu). Zainicjalizuj tam lokalne repozytorium.

## Zadanie 2
Do gita dodaj od razu zdalne repozytorium, które będzie wskazywać na to repozytorium w którym znajdują się zadania. Dodaj nową gałąź do repozytorium lokalnego o nazwie S1Z2_xx - gdzie xx to Twoje iniciały. Od teraz będziesz pracować na swojej gałęzi do spotkania i konkretnego zadania. Do repozytorium dodaj nowy plik tekstowy - nim teraz będziemy się bawić. Dodaj do niego jakąś teoretyczną funkcjonalność np:
feature{
  ta funkcja jeszcze nie działa
 }
 zapisz plik dodaj pierwszego commita, który opisze tą funkcjonalność. Dodaj tu tag - będziemy z niego korzystać. Zpushuj wszystko do repozytorium zdalnego.
 
 ## Zadanie 3
 Wejdź na githuba, do repozytorium z aktualnym spotkaniem (zasadniczo powineneś już tu być skoro to czytasz ;)), przejdź do swojej gałęzi, sprawdź czy wszystko się zgadza z lokalnym repozytorium. Stwórz pull request i w jego komentarzu daj mi znać, że skończyłeś zadanie. Wrócę z ewentualnymi uwagami.
 
 ## Zadanie 4
 Teraz dodamy kolejną funkcjonalność do naszego pliku. Stwórz nową gałąź, dodaj w niej nową funkcjonalność - np. feature2. Rozwiń ją o trzy commity, zasymuluj trochę pracy, np. napisz, że funkcja najpierw nie działa, później działa trochę, a na koniec działa już w 100%. 
 
 Wróć do głównej (głównej tzn. S1Z2_xx) gałęzi, tam zasymuluj poprawkę feature, wyetyduj plik (przy okazji zobacz jak się zmienia plik, gdy zmieniasz gałęzie commity, etc) i wgraj jako commit do głównej gałęzi. Teraz zmerguj te dwie gałęzie, bez udostępniania histori gałęzi z feature2, jeżeli pojawią się konfikty - usuń je tak aby mieć dwie funkcjonalności (feature, feature2). Zrób push i pull request na githubie.
 
 ## Zadanie 5
 Wróć teraz do tagu dodanego w zadaniu 2. Rozwiń kolejną funkcjonalność np. feature3 podobnie jak w zadaniu powyżej, zrób też min. 3 commity. Teraz zmerguj główną gałąź, oraz tą gałąź z feature 3, ale udostępnij historię edycji. Zrób push i pull request.
 
 ## Zadanie 6
 Usuń wszystko z pliku. Zapisz, zrób commit. O NIE! usunąłęś swój cały projekt. Wróć do wcześniejszej wersji, jednak chcesz ten projekt ;)
 
 ## Zadanie 7
 Zrób jakieś zmiany - może głupie, może nie. Ale jednak ich nie chcesz, wróć do wcześniejszej wersji, ale tak aby utrzymać historię zmian.
 
 ## Zadanie 8
 Zrób sobie zadanka tutaj - jest ładne graficzne
 https://learngitbranching.js.org/?locale=pl
