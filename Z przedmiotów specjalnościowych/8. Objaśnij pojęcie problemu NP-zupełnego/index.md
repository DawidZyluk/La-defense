# Objaśnij pojęcie problemu NP-zupełnego oraz podaj przykłady problemów tego typu. 

### Problem NP-zupełny:

Problem NP-zupełny (ang. NP-complete) to problem decyzyjny, który spełnia dwie kluczowe cechy:

1. **Trudność Decyzji:** Jeśli mamy rozwiązanie, możemy w łatwy sposób sprawdzić, czy jest poprawne.
2. **Trudność Znalezienia Rozwiązania:** Brak efektywnego algorytmu do znalezienia rozwiązania dla dowolnej instancji problemu.

Jeśli uda się znaleźć efektywny algorytm do rozwiązania jednego problemu NP-zupełnego, to taki algorytm można by użyć do rozwiązania każdego innego problemu NP-zupełnego w czasie wielomianowym. Wyjaśnia to, dlaczego są one uważane za trudne i dla nich nie jest znany szybki algorytm rozwiązujący.

### Przykłady Problemów NP-zupełnych:

1. **Problem Komiwojażera (Travelling Salesman Problem, TSP):**
   - **Treść:** Czy istnieje cykl odwiedzający każde miasto dokładnie raz i minimalizujący łączną długość trasy?
   - **Znane Rozszerzenie:** Problem Komiwojażera jest NP-zupełny nawet w wersji, gdzie miary odległości spełniają nierówność trójkąta.

2. **Problem Plecakowy (Knapsack Problem):**
   - **Treść:** Mając plecak o ograniczonej pojemności i zestaw przedmiotów z danymi wagami i wartościami, jakie przedmioty wybrać, aby maksymalizować sumaryczną wartość, zachowując ograniczenie pojemności plecaka?
   - **Znane Rozszerzenie:** Wersja problemu plecakowego, w której przedmioty mogą być ułamkowe (Fractional Knapsack Problem), również jest NP-zupełna.

3. **Problem Kolorowania Grafu:**
   - **Treść:** Czy dla danego grafu można przyporządkować kolory w taki sposób, żeby żadne dwa sąsiednie wierzchołki nie miały tego samego koloru?
   - **Znane Rozszerzenie:** Problem Kolorowania Grafu jest NP-zupełny, nawet gdy ograniczymy liczbę dostępnych kolorów do dwóch (Problem 2-kolorowalności).

4. **Problem SAT (Boolean Satisfiability Problem):**
   - **Treść:** Czy dla danej formuły logicznej w postaci CNF (Conjunctive Normal Form) istnieje przypisanie wartości logicznych zmiennym, które sprawi, że cała formuła będzie prawdziwa?
   - **Znane Rozszerzenie:** Rozszerzenie 3-SAT, gdzie każda klauzula ma co najwyżej trzy zmienne, również jest NP-zupełne.

5. **Problem Pokrycia Wierzchołkowego (Vertex Cover Problem):**
   - **Treść:** Czy dla danego grafu można znaleźć pokrycie wierzchołkowe o rozmiarze co najwyżej k?
   - **Znane Rozszerzenie:** Problem Pokrycia Wierzchołkowego jest NP-zupełny, nawet gdy graf jest dwudzielny.

Problemy NP-zupełne są fundamentalne dla teorii obliczeń i mają znaczenie w praktyce, ponieważ dostarczają dowodów na trudność wielu problemów decyzyjnych. W związku z tym, znalezienie efektywnego algorytmu dla dowolnego z tych problemów oznaczałoby znalezienie algorytmu dla wszystkich problemów NP-zupełnych.