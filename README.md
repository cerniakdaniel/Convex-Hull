# 🔷Convex Hull Visualizer — Graham Scan \& Andrew's Monotone Chain



### Interaktywna wizualizacja algorytmów otoczki wypukłej zbudowana w czystym HTML/CSS/JavaScript (Canvas API).



### 📖Opis projektu



Aplikacja pozwala krok po kroku obserwować działanie dwóch algorytmów geometrycznych:

\- **Graham Scan** — sortuje punkty według kąta biegunowego od pivota, buduje otoczkę przy użyciu stosu

\- **Andrew's Monotone Chain** — sortuje punkty leksykograficznie, buduje osobno dolną i górną otoczkę



### 🚀Uruchomienie



Projekt nie wymaga żadnych bibliotek ani serwera.



1\. Pobierz plik `Project.html`

2\. Otwórz go w przeglądarce (Chrome, Firefox, Edge)

3\. Gotowe✅



### 🎮Jak używać



&#x20;         Akcja           |              Opis               

\-------|-----

&#x20;    Klik na canvas       | Dodaje punkt w tym miejscu

&#x20;    Losowe punkty        | Generuje 20 losowych punktów

&#x20;  Punkty w skupiskach    | Generuje 40 punktów w 5 grupach

&#x20;   Uruchom algorytm      | Uruchamia wybrany algorytm

&#x20;        ← / →            | Poprzedni / następny krok

&#x20;       Auto-Play         | Automatyczne odtwarzanie kroków

&#x20;    Suwak prędkości      | Reguluje tempo animacji (50–1500ms)

&#x20;        Spacja           | Play / Pauza 

&#x20;    Strzałki ← →         | Nawigacja po krokach 



### 📂Struktura projektu



convex-hull/

└── Project.html

└── uwb.png



### 🛠Technologie



\- **HTML5 Canvas API** — rysowanie wizualizacji

\- **Vanilla JavaScript** — logika algorytmów i animacji

\- **CSS3** — interfejs użytkownika (dark theme)

\- **Google Fonts** — czcionki Space Mono i Syne



### 🎨Legenda kolorów



&#x20;     Kolor       |             Znaczenie 

\-------|------------

&#x20;⚪ Biały        | Punkt wejściowy 

&#x20;🟡 Żółty        | Pivot (punkt startowy Graham Scan) 

&#x20;🟢 Zielony      | Wierzchołek otoczki / górna otoczka 

&#x20;🟠 Pomarańczowy | Aktywna krawędź / dolna otoczka 

&#x20;🔵 Niebieski    | Testowany kandydat 

&#x20;🟣 Fioletowy    | Element na stosie 

##### 

