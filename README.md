# clusteringML
Nasz [dataset](https://www.kaggle.com/datasets/hariharanpavan/bank-marketing-dataset-analysis-classification).

Pytania do projektu:
1. Mając część danych ciągłych i część kategorycznych, czy po zastosowaniu one-hot-encoding należy zrobić normalizację wszystkich zmiennych?
<br> Odp: Nie stosować one-hot encoding, zamiast tego woe w klasteryzacji.

3. Czy potrzebny jest tutaj train/test split?
<br> Nie potrzebny, nie zajmujemy sie klasyfikacja tylko grupowaniem.

4. Jak ocenić czy dane pogrupowanie ma sens ze wzgląd na wartość wynikową eksperymentu?
<br> Można zrobić pca i zwizualizować, albo dla sklasteryzowanych danych wizualizacje na wybranych kolumnach.

6. Czy tak samo jak w przypadku budowy modeli należy tutaj liczyć korelację pomiędzy kolumnami i usuwać te z wysoką korelacją?
<br> Nie

BŁĘDY PO 1 PREZENTACJI:
- ustalić business case
- nie używać kolumny celu do klasteryzacji, będziemy budować na tym modele klasyfikacyjne
- podział na train/test
- walidacja klastrów na podstawie porównania weźmie kredyt/nie weźmie?
- przy interpretacji klastrów zbudować model klasyfikacyjny i zobaczyć feature importacne i wybrać do 3 klolumn do wizualizacji

![instrukcja](https://github.com/wojo501/clusteringML/blob/main/images/instruction.png)


