Wyspowy algorytm genetyczny dla problemu komiwojażera w zastosowaniach obliczeń superkomputerowych

Autorzy:
Jakub Kępiński 261319
Krzysztof Szczepaniak 258416

## Opis wstępny projektu

Algorytmy genetyczne, będące metodą inspirowaną biologiczną ewolucją, są szeroko stosowane do rozwiązywania problemów optymalizacyjnych, w tym znanego problemu komiwojażera (TSP). Problem ten polega na znalezieniu najkrótszej możliwej trasy, która odwiedza każde z miast dokładnie raz, a następnie wraca do miasta początkowego. Ze względu na jego złożoność obliczeniową (NP-trudność), efektywne rozwiązywanie dużych instancji TSP wymaga zaawansowanych technik optymalizacyjnych oraz odpowiedniej infrastruktury obliczeniowej, takiej jak superkomputery.

Celem tego projektu jest implementacja i analiza wyspowego algorytmu genetycznego (IGA) dla problemu komiwojażera, z naciskiem na zrównoleglenie obliczeń i badanie efektywności różnych wariantów wyspowego podejścia. Wyspowy algorytm genetyczny dzieli populację rozwiązań na kilka podpopulacji (wyspy), które ewoluują niezależnie, a co jakiś czas wymieniają informacje między sobą (np. poprzez migrację najlepszych osobników). Dzięki temu możliwe jest rozproszenie obliczeń na wiele węzłów superkomputerowych, co prowadzi do znaczącego przyspieszenia obliczeń.

## Zakres projektu

Projekt obejmuje:

1. Wybór gotowego problemu komiwojażera o dużej skali z dostępnych benchmarków.
2. Implementację wyspowego algorytmu genetycznego w środowisku przystosowanym do superkomputerów.
3. Eksperymenty z różnymi parametrami wyspowego podejścia, takimi jak:
   - Częstotliwość migracji,
   - Rozmiary populacji na wyspach,
   - Badanie wpływu różnych schematów migracyjnych na jakość i czas rozwiązywania problemu.
4. Analiza skalowalności algorytmu w kontekście obliczeń równoległych, w tym badanie wydajności przy różnych liczbach węzłów obliczeniowych.

## Oczekiwane rezultaty

Rezultaty tego projektu mogą dostarczyć nowych wniosków na temat efektywnego równoleglenia algorytmów ewolucyjnych oraz ich zastosowania do rozwiązywania dużych instancji problemu komiwojażera.
