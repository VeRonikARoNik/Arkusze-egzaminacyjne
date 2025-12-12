# Arkusze-egzaminacyjne
Arkusze z 2025 roku

## Spis treści
* [1. Opis zadania](#opis-zadania)
* [2. Kod programu](#kod-proramu)
* [3. Wizualizacja](#Wizualizacja)
* [4. Źródła](#źródła)

### 1. Opis zadania
Wykonaj zapytania SQL działające na bazie piekarnia. Zapytania zapisz w pliku kwerendy.txt. Wykonaj
zrzuty ekranu przedstawiające wyniki działania kwerend. Zrzuty zapisz w formacie PNG i nadaj im nazwy
kw1, kw2, kw3, kw4. Zrzuty powinny obejmować cały ekran monitora z widocznym paskiem zadań
- Zapytanie 1: wybierające jedynie pola: Rodzaj, Nazwa, Gramatura i Cena dla wyrobów z rodzaju
„INNE”
- Zapytanie 2: wybierające jedynie posortowane malejąco rodzaje wyrobów. Rodzaje wyrobów nie mogą
się powtarzać
- Zapytanie 3: wybierające jedynie pola: ID oraz Nazwa dla wyrobów, których nazwa zawiera słowo
„Chałka”


### 2. Kod programu
```
Zapytanie 1: SELECT Rodzaj, Nazwa, Gramatura, Cena FROM wyroby WHERE Rodzaj = "INNE";
```

```
Zapytanie 2: SELECT DISTINCT Rodzaj FROM wyroby ORDER BY Rodzaj DESC;
```
```
Zapytanie 3: SELECT ID, Nazwa FROM wyroby WHERE Nazwa LIKE '%Chałka%';
```
```
Zapytanie 4: SELECT Rodzaj, ROUND(AVG(Cena), 2) AS "Średnia_cena" FROM wyroby GROUP BY Rodzaj;
```
### 3. Wizualizacja 

### 4. Źródła
#### Link do arkusza : https://ee-informatyk.pl/inf03-ee09/praktyka/
