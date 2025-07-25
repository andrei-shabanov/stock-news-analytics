# Projekt „Börse Analytics“
### Berke Ari, Martin Matuschinski, Andrei Shabanov, Muhammed Mehmet Tanit

## Übersicht der Inhalte: 
- In der MEADME.md findet man die allgemeine Informationen zum Projekt.
- Der Code ist nach den Projektstufen gegliedert:
- - 1_data_load: Hochladen der Daten
- - 2_data_preparation: Datenvorbereitung; das Ergebnis ist in merged_df.csv gespeichert
- - 3_data_exploration: explorative Datenanalyse
- - alle 4_... Dateien: die entwickelten Modelle

## 1. Business Understanding
- Ziel: Entwicklung eines Börse-Analytics-Modells zur Vorhersage der NASDAQ-Kursentwicklung basierend auf englischsprachigen Finanznachrichten.
- Datengrundlage: [FinSen Dataset](https://github.com/EagleAdelaide/FinSen_Dataset)

## 2. Data Understanding
- Ein Web Scraper wird entwickelt, um tägliche NASDAQ-Kurswerte zu sammeln (für Modell-Evaluation).
- Daraus werden Kursänderungen abgeleitet.
- Erste explorative Analyse: Anzahl der Nachrichten, Textlängen, Schlagwörter, einfache Korrelationen (Berke).

## 3. Data Preparation (Muhammed)
- Reinigung der Nachrichtentexte.
- Teilweise Labelung: positive, negative oder schwankende Kursentwicklung.

## 4. Data Modelling (Martin / Andrei)
- Entwicklung eines Modells zur Label-Vorhersage.
- Optional: ergänzendes Optimierungsmodell.

## 5. Data Evaluation
- Bewertung der Modellgenauigkeit anhand roher und gelabelter Daten.

