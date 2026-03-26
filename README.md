# LinqConsoleLab - System Analizy Danych Uczelni
Projekt został zrealizowany jako rozwiązanie ćwiczenia z zakresu wykorzystania technologii LINQ w środowisku .NET. Celem aplikacji jest wsparcie Biura Organizacji Studiów w szybkim generowaniu raportów dotyczących studentów, przedmiotów i kadr naukowych.

## Zakres Implementacji
W ramach projektu zaimplementowano 16 zadań podstawowych oraz 4 zaawansowane wyzwania raportowe, wykorzystując m.in.:

__Filtrowanie i Projekcję__: Where, Select.

__Sortowanie i Paginację__: OrderBy, ThenBy, Skip, Take.

__Złączenia i Grupowanie__: Join, GroupJoin, GroupBy.

__Agregację Danych__: Count, Average, Max.

## Kluczowe Wyzwania Biznesowe
Aplikacja rozwiązuje złożone problemy analityczne, takie jak:

- Identyfikacja studentów z nadmiarową liczbą aktywnych zapisów.

- Monitorowanie braków w ocenach końcowych dla przedmiotów startujących w określonych terminach.

- Obliczanie średniej efektywności nauczania dla poszczególnych prowadzących.

- Analiza geograficzna aktywności studentów.

## Uwaga dot. Danych Testowych (Wyzwanie 02)
W aktualnym zestawie danych testowych w klasie DaneUczelni, Wyzwanie 02 ("Przedmioty startujące w kwietniu bez ocen końcowych") nie zwraca wyników. Jest to zachowanie poprawne - wszystkie przedmioty spełniające kryterium daty (kwiecień 2026) posiadają już w systemie przypisane oceny dla przynajmniej jednego studenta.