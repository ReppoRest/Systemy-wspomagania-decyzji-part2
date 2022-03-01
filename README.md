# Systemy-wspomagania-decyzji-part2
Jaki wpływ na jakość znalezienia drogi do frisbee ma wartość gamma? Czym większa wartość gamma tym mniejsza nagroda i tym mniejsza ilość iteracji. Oczekując najlepszej jakości drogi do znalezienia frisbee powinniśmy wybrać większą wartość gamma oby możliwość poruszania była w każdym kierunku.

Value i Policy Iteration znajdują swoje zastosowanie w sytuacjach, gdzie ilość kombinacji stanów jest mała, gdyż algorytmy, pomimo swojej dokładności, zajmują dużo pamięci i potrafią wykonywać się długo. Oba algorytmy zostały przez nas sprawdzone na grze Snake oraz Pacman.
Policy iteration : zaczyna się od losowej strategii, algorytm jest bardziej złożony, gwarantowana zbieżność, tańsze obliczenia, wymaga kilku iteracji do zbieżności, działa szybciej 


Value iteration : zaczyna się od funkcji wartości losowej, algorytm jest prostszy, gwarantowana zbieżność, droższe do obliczeń, wymaga większej liczby iteracji do zbieżności, działa wolniej

Dlaczego value_iteration znajduje lepszą drogę niż policy_iteration? Strategia value iteration polega na osiągnięciu największego zysku . Podczas działania strategii policy iteration są analizowane wszystkie możliwości przejścia drogi i na podstawie tych wyników jest wyciągana najlepsza droga.
