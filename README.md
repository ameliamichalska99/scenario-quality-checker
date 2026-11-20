# Scenario Quality Checker

Projekt realizowany na przedmiot Inżynieria Oprogramowania.

Scenario Quality Checker to aplikacja służąca do sprawdzania scenariuszy. W pierwszym Sprincie zajmujemy się tworzeniem podstawowych funkcji, takich jak liczenie kroków i sprawdzanie ich poprawności.

## Zespół i jego capacity (tygodniowe)

- Amelia Michalska [164042] - 3h
- Martyna Wyrobek [164128] - 3h
- Olga Kycia [164091] - 3h
- Izabela Jasiukiewicz [164071] - 3h

Łącznie: 12h tygodniowo.

## Role

- Product Owner - dr inż. Wojciech Complak
- Scrum Master - Amelia Michalska
- Proxy Product Owner - [...]

## Zakres Sprintu

Do Sprintu #1 wybrano:

- PB1 - REST API
- PB2 - Zliczanie wszystkich kroków scenariusza
- PB3 - Zliczanie kroków ze słowami kluczowymi
- PB4 - Wykrywanie kroków nierozpoczynających się od aktora

Łączna wartość Business Value: 4.

## Notacja scenariuszy

- Scenariusz zawiera nagłówek określający jego tytuł i aktorów (zewnętrznych oraz system)
- Scenariusz składa się z kroków (każdy krok zawiera tekst)
- Kroki mogą zawierać pod-scenariusze (dowolny poziom zagłębień)
- Kroki mogą się zaczynać od słów kluczowych: IF, ELSE, FOR EACH

### Przykład

**Tytuł:** Dodanie książki  
**Aktorzy:** Bibliotekarz  
**Aktor systemowy:** System

- Bibliotekarz wybiera opcje dodania nowej pozycji książkowej
- Wyświetla się formularz.
- Bibliotekarz podaje dane książki.
- IF: Bibliotekarz pragnie dodać egzemplarze książki
  - Bibliotekarz wybiera opcję definiowania egzemplarzy
  - System prezentuje zdefiniowane egzemplarze
  - FOR EACH egzemplarz:
    - Bibliotekarz wybiera opcję dodania egzemplarza
    - System prosi o podanie danych egzemplarza
    - Bibliotekarz podaje dane egzemplarza i zatwierdza.
    - System informuje o poprawnym dodaniu egzemplarza i prezentuje zaktualizowaną listę egzemplarzy.
- Bibliotekarz zatwierdza dodanie książki.
- System informuje o poprawnym dodaniu książki.

## Daily Scrum

Spotkania Daily Scrum odbywają się zdalnie w środy i niedziele o godzinie 20:00.
