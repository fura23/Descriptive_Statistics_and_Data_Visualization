# Statystyki opisowe i wizualizacja danych (Descriptive Statistics and Data Visualization Report)

Projekt akademicki dotyczący analizy statystycznej i wizualizacji danych na podstawie zbioru `carbig.csv`.

## Opis projektu
Raport przedstawia kompletną analizę danych z wykorzystaniem języka Python oraz metod statystyki opisowej.

Dokument obejmuje przygotowanie danych, obliczenie podstawowych miar statystycznych, analizę zależności między zmiennymi oraz wykonanie wykresów ułatwiających interpretację wyników.

## Zakres opracowania
W projekcie zrealizowano:
- wczytanie i przygotowanie danych do analizy,
- obsługę braków danych,
- dodanie losowego szumu do wybranych zmiennych,
- obliczenie miar położenia,
- obliczenie miar rozrzutu,
- analizę asymetrii i kurtozy,
- wykonanie histogramów,
- wykonanie wykresów pudełkowych,
- wykonanie wykresów probplot,
- analizę korelacji liniowej,
- wykonanie scatter matrix,
- wykonanie parallel coordinates po standaryzacji,
- analizę zużycia paliwa,
- porównanie średniego zużycia paliwa według liczby cylindrów.

## Zbiór danych
Analiza została oparta na zbiorze `carbig.csv`, który zawiera informacje o samochodach opisanych za pomocą zmiennych takich jak:
- `Acceleration`
- `Displacement`
- `Horsepower`
- `Weight`
- `MPG`
- `Cylinders`

## Wykorzystane narzędzia
Projekt został wykonany w Pythonie z użyciem bibliotek:
- `numpy`
- `pandas`
- `matplotlib`
- `scipy`

## Zawartość raportu
Plik zawiera:
- część teoretyczną,
- kod źródłowy,
- wyniki obliczeń,
- tabele,
- wykresy,
- komentarze interpretacyjne do każdego zadania,
- wnioski końcowe.

## Główne wnioski
Na podstawie przeprowadzonej analizy stwierdzono, że:
- większość zmiennych numerycznych wykazuje asymetrię prawostronną,
- pojemność silnika, moc i masa pojazdu są silnie ze sobą powiązane,
- zużycie paliwa rośnie wraz ze wzrostem masy, mocy, pojemności silnika i liczby cylindrów,
- standaryzacja danych ułatwia porównywanie zmiennych mierzonych w różnych skalach.

## Pliki w repozytorium
- `raport_sow.pdf` – główny raport,
- `carbig.csv` - dane wejściowe,
- `sow_task.ipynb` - kod projektu,
- `README.md` – opis projektu.

## Autor
Projekt wykonany w ramach zajęć z analizy danych i statystyki opisowej.

## License
This project is provided for viewing, downloading, running, and private modification only.
Redistribution, republication, commercial use, and claiming authorship or ownership are prohibited without prior written permission from the author.
