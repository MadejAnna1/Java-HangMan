# HANGMAN

Nasz klient potrzebuje grę *Hangman* w języku Java.

Gra jest bardzo prosta:

* losuje słowo i wyświetla "kreskami" ile to słowo ma liter
* mogę zgadywać czy dana litera pojawiła się w słowie
* jeśli trafiłem, gra odkrywa gdzie ta litera pojawia się w słowie (wszystkie wystąpienia)
* jeśli  nie trafiłem, infografika przedstawiająca status gry przybliża mnie do przegranej
* jeśli zgadnę wszystkie litery w słowie przed wykorzystaniem wszystkich prób - wygrywam
* jeśli nie uda mi się - przegrywam

Zasoby na ten projekt są limitowane. Otrzymane finansowanie pozwala nam poświęcić na ten projekt
3 godziny pracy dwóch programistów. Zarząd liczy na Wasz sukces! **Opóźnienie nie wchodzi w grę.**

Żeby było łatwiej, otrzymujecie projekt animacji z [działu grafików](https://gist.github.com/chrishorton/8510732aa9a80a03c829b09f12e20d9c). 
Nasz [lingwista](http://generatorslow.pl/) opracował listę słów do użycia w grze, a nasz 
specjalista ds. wizjonerstwa dodatkowo narysował koncepcję oczekiwanego produktu. 
Prawie wszystko jest więc gotowe. Wystarczy dodać trochę kodu.

![Success](https://raw.githubusercontent.com/fracz/java-hangman/master/img/success.gif)

![Failure](https://raw.githubusercontent.com/fracz/java-hangman/master/img/fail.gif)

# Jak to zrobić?

To już chyba wiesz?

Ale na wszelki wypadek:

1. Jedna osoba z pary forkuje ten projekt.
2. W ustawieniach repozytorium dodaje drugiej prawa zapisu do projektu (*Settings -> Manage access -> Invite collaborator*).
3. Obydwie osoby klonują sforkowane repozytorium na komputer, importują do IDE i patrzą co jest w środku.
4. Razem projektujecie implementacje i ustalacie podział prac.
5. Pracujecie, wykorzystując wszystko co poznaliście w Javie do tej pory i system kontroli wersji.

**Przed ustalonym wyżej deadlinem specjalista ds. koordynacji projektów sprawdzi i oceni postęp prac i jakość implementacji.**

Do dzieła!

# Gotowe? Przed czasem?

Takie postawy będą chwalone! 

Ba! NAGRADZANE!

Oto dodatkowe funkcjonalności, z których klient na pewno będzie zadowolony:

* gra powinna pozwalać na wybór długości słowa
* gra powinna gromadzić statystyki (może da się sprawdzić które słowo jest najtrudniejsze do odgadnięcia?)
* gra powinna pozwolić na podanie słowa, które ma być zagadką w kolejnej grze 
  (dzięki temu można uruchomić grę dla kogoś z wymyślonym przez siebie słowem)
