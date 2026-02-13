# ⚽ La Liga 24/25 Season Analysis | Python & Pandas

## 📌 Project Overview
This project is an statistical analysis of last La Liga season. The main target was to check form, offensive efectivness and defensive stats. I've also tried to make some conclusions about advantage of home matches.

The project starts with **data preparation**, **Feature Engineering** and **Visualization**, also conclusions below the charts

## 🎯 Key insights
Based on the analysis, the following conclusions has been made:
1.  **FC Barcelona offensive dominance**
    * Barcelona scored the most goals in the whole league.
2.  **Shots and goals correlation**
    * naliza wykazała silną korelację dodatnią. Drużyny z Top 4 (Barcelona, Real Madryt) cechują się wyższą skutecznością konwersji strzałów (znajdują się "nad kreską" trendu).
3.  **Home Advantage (Przewaga własnego boiska):**
    * [TUTAJ WPISZ WNIOSEK Z NOTATNIKA, np.: Analiza wykazała, że dla drużyn ze środka tabeli gra u siebie nie gwarantuje znaczącej przewagi punktowej w tym sezonie.]
4.  **Analiza Formy (Rolling Average):**
    * Wykres średniej kroczącej pokazuje dynamikę zdobywania punktów przez czołowe zespoły w czasie.

## 🛠️ Użyte Technologie (Tech Stack)
Projekt został zrealizowany w języku **Python 3.x** z wykorzystaniem bibliotek:

* **Pandas & NumPy:** Manipulacja danymi, grupowanie (`groupby`), łączenie tabel (`merge`), operacje na datach.
* **Matplotlib & Seaborn:** Data visualization.
* **Jupyter Notebook:**

## 📊 Visuals

### 1. League Table
![League Table](images/table_overview.png)

### 2. Correlation Matrix
![Correlation Heatmap](images/correlation.png)
*Badanie zależności między rzutami rożnymi, strzałami a wynikiem końcowym.*

### 3. Teams' from over the season (Rolling Average)
![Team Form](images/team_form.png)
**


## 📂 Struktura Plików
* `laliga2425.ipynb` - Główny notatnik z kodem, analizą i opisami.
* `laliga2425.csv` - Zbiór danych (mecze, wyniki, statystyki).
* `README.md` - Dokumentacja projektu.

---
*Autor: [Twoje Imię i Nazwisko]*
