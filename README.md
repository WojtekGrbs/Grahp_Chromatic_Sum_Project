# Wyznaczanie sumy chromatycznej grafu
Konstrukcja dwóch algorytmów w ramach realizacji projektu z przedmiotu Chromatyczna Teoria Grafów
# Problem sumy chromatycznej
Dla dowolnego grafu $G=(V,E)$ definiujemy jego sumę chromatyczną jako minimum sumy: $$\sum_{v\in V} c(v)$$ ze względu na wszystkie możliwe dobre kolorowania $c$ grafu $G$, przy czym zbiór kolorów jest podzbiorem $\mathbb{N}_{+}$. Sumę chromatyczną grafu $G$ oznaczać będziemy $\Sigma(G)$.
# Algorytm w oparciu o drzewo rozpinające
Znajduje się w pliku ```ST_Algorithm_ChTG.ipynb``` i reprezentuje grafy jako symetryczne macierze sąsiedztwa. Nie przechowuje żadnych danych na temat innych własności grafu. Na końcowy algorytm ```ST_Algorithm``` składa się szereg wcześniej zdefiniowanych funkcji.
### Parametry Wejściowe:
```matrix``` - macierz sąsiedztwa jako klasa ```np.Array``` lub ```np.Matrix```
### Parametry wyjściowe:
```coloring``` - słownik kolorów
```chromatic_sum``` - suma kolorów dla wyznaczonego kolorowania
