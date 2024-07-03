# Zadanie 1: Nazwy użytkowników

Napisz funkcję strzałkową getUserNames(users), która przyjmuje jeden parametr users — tablicę obiektów użytkowników. Funkcja powinna zwrócić tablicę nazw wszystkich użytkowników (właściwość name) z tablicy users.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Zadanie 2. Użytkownicy ze znajomym

Napisz funkcję strzałkową getUsersWithFriend(users, friendName), która przyjmuje dwa parametry:

* pierwszy parametr users — tablica obiektów użytkowników,
* drugi parametr friendName — nazwa znajomych do wyszukania.


Funkcja powinna zwrócić tablicę wszystkich użytkowników z tablicy users, którzy mają znajomego o nazwie friendName. Znajomi każdego użytkownika są przechowywani we właściwości friends. Jeśli nie ma użytkowników, którzy mają takiego znajomego, funkcja powinna zwrócić pustą tablicę.

Wskazówki:

* Metoda filter() może być użyta do utworzenia nowej tablicy z elementami spełniającymi określony warunek.
* Użyj metody includes(), aby sprawdzić czy tablica friends zawiera friendName.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Zadanie 3. Sortowanie według liczby znajomych

Napisz funkcję strzałkową sortByDescendingFriendCount(users), która przyjmuje jeden parametr users — tablicę obiektów użytkowników.


Funkcja powinna zwrócić tablicę wszystkich użytkowników posortowanych według liczby znajomych w porządku malejącym (właściwość friends).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Zadanie 4. Saldo

Napisz funkcję strzałkową getTotalBalanceByGender(users, gender), która przyjmuje dwa parametry:

* pierwszy parametr users — tablica obiektów użytkowników,
* drugi parametr gender — ciąg znaków przechowujący płeć.
  
Funkcja powinna używać łańcucha wywołań metod i zwracać saldo użytkowników (właściwość balance), których płeć (właściwość gender) odpowiada wartości parametru gender.
