# Stroke-prediction-hypotheses
Testing hypotheses on health and lifestyle factors influencing stroke risk in R. (Badanie hipotez dotyczących czynników zdrowotnych i stylu życia wpływających na ryzyko udaru w R.)


# Stroke-prediction-hypotheses

## Opis projektu
Celem badania było porównanie danych osób, które przeszły udar mózgu oraz tych, które go nie doświadczyły, 
aby spróbować przewidywać możliwość wystąpienia udaru u pacjentów o podobnych wynikach i cechach zdrowotnych.  

Projekt został zrealizowany w języku **R** na podstawie zbioru danych [Stroke Prediction (Kaggle)](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset).  

---

## Hipotezy badawcze
1. Osoby z niepoprawnym BMI lub palące papierosy częściej przechodzą udar mózgu.  
2. Nieodpowiednie wyniki BMI i zły poziom glukozy we krwi zwiększają prawdopodobieństwo wystąpienia udaru mózgu.  
3. Osoby mieszkające w mieście i będące w związku małżeńskim mają wyższe BMI.  

Celem badania było sprawdzenie, czy niekorzystne wskaźniki zdrowotne lub warunki życia mogą ostrzegać przed zwiększonym ryzykiem groźnych chorób.  

---

## Etapy analizy
1. **Wstępne czyszczenie danych**  
   - zmiana typów zmiennych,  
   - zamiana nazw z angielskich na polskie,  
   - uzupełnianie braków (np. status palenia u dzieci).  

2. **Podstawowe statystyki opisowe**  
   - rozkłady wieku, BMI, poziomu glukozy,  
   - charakterystyka grup (płeć, miejsce zamieszkania, status cywilny, palenie papierosów).  

3. **Analiza hipotez badawczych**  
   - dla każdej hipotezy przygotowano wykresy (histogramy, wykresy punktowe, wykresy korelacji),  
   - oceniono zależności między zmiennymi.  

4. **Budowa modeli regresji liniowej**  
   - **Model 1**: wpływ BMI i palenia na ryzyko udaru,  
   - **Model 2**: wpływ BMI i poziomu glukozy na ryzyko udaru,  
   - **Model 3**: wpływ miejsca zamieszkania i statusu cywilnego na BMI.  

5. **Wnioski**  
   - BMI i palenie papierosów mają istotny wpływ na wystąpienie udaru,  
   - poziom glukozy jest silniejszym czynnikiem ryzyka niż BMI,  
   - status małżeński wpływa na BMI, ale miejsce zamieszkania nie ma istotnego znaczenia.  
