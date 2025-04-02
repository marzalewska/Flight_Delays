## Opis projektu
Projekt zawiera analizę danych dotyczących opóźnień i anulowanych lotów w 2015 roku na terenie Stanów Zjednoczonych. Dane pochodzą z Kaggle ([2015 Flight Delays and Cancellations](https://www.kaggle.com/datasets/usdot/flight-delays)) i zostały udostępnione przez Departament Transportu USA. Celem analizy jest eksploracja oraz przekształcenie danych w przejrzystą strukturę bazodanową umożliwiającą efektywne zapytania i analizy.

## Zawartość
Plik zawiera:
1. **Wstępną eksplorację danych** - opis datasetu i kluczowych zmiennych.
2. **Strukturę danych** - podział danych na logiczne tabele zgodnie ze schematem bazy danych.
3. **Transformacje danych** - czyszczenie i normalizacja danych.
4. **Tworzenie tabel** - definicje tabel w SQL oraz ich uzupełnienie danymi.

## Struktura bazy danych
Dane zostały podzielone na następujące tabele:
- **Date** - zawiera informacje o dniach roku 2015.
- **Airlines** - linie lotnicze i ich kody IATA.
- **Airports** - lotniska, ich lokalizacja i kody IATA.
- **Journey** - połączenia lotnicze (lotniska początkowe, docelowe i dystans).
- **Schedule** - harmonogram lotów (planowane godziny wylotu i przylotu).
- **Delay** - przyczyny opóźnień lotów.
- **Flights** - główna tabela faktów z danymi o lotach.

Struktura została zaprojektowana według schematu **płatka śniegu**, aby zminimalizować redundancję danych i poprawić ich czytelność.

