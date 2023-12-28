# Objaśnij znaczenie zapisu O(n) oraz scharakteryzuj wpływ doboru struktury danych na czas wykonania programu.

### O(n) - Złożoność Czasowa Algorytmu:

Zapis O(n) to forma zapisu złożoności czasowej algorytmu, gdzie "O" oznacza notację wielkiego O, a "n" reprezentuje rozmiar danych wejściowych. Złożoność czasowa O(n) oznacza, że czas wykonania algorytmu rośnie liniowo wraz z rozmiarem danych wejściowych. Innymi słowy, im większe "n", tym więcej czasu algorytm będzie potrzebować do wykonania.

Przykłady złożoności czasowej:

- O(1): Stała złożoność czasowa (czas stały, niezależny od rozmiaru danych).
- O(log n): Logarytmiczna złożoność czasowa.
- O(n log n): Złożoność czasowa dominowana przez iloczyn rozmiaru danych i logarytmu tego rozmiaru.
- O(n): Liniowa złożoność czasowa.
- O(n^2): Kwadratowa złożoność czasowa.
- O(2^n): Wykładnicza złożoność czasowa.

### Wpływ Doboru Struktury Danych na Czas Wykonania Programu:

Dobór odpowiedniej struktury danych ma kluczowe znaczenie dla efektywności algorytmu i czasu wykonania programu. Poniżej przedstawiamy kilka aspektów, które pokazują, jak struktury danych wpływają na wydajność:

1. **Operacje Wyszukiwania:**

   - **Lista Łańcuchowa vs. Tablica:** Jeśli często musisz wykonywać operacje wyszukiwania, tablice są bardziej efektywne niż listy łańcuchowe. Wyszukiwanie w tablicy o stałym czasie O(1), podczas gdy w liście łańcuchowej może wymagać O(n) czasu.

2. **Operacje Wstawiania i Usuwania:**

   - **Lista vs. Tablica:** W przypadku częstych operacji wstawiania i usuwania, lista może być bardziej efektywna, ponieważ operacje te wymagają O(1) czasu dla listy, podczas gdy dla tablicy mogą wymagać O(n) czasu ze względu na konieczność przesuwania elementów.

3. **Dostęp do Elementu w Losowym Miejscu:**

   - **Tablica vs. Lista:** W przypadku częstego dostępu do elementów w dowolnym miejscu, tablica jest bardziej efektywna, ponieważ umożliwia dostęp w czasie O(1), podczas gdy dla listy może to być O(n).

4. **Wielkość Pamięci:**

   - **Tablica vs. Lista:** Tablice zazwyczaj wymagają mniej pamięci, ponieważ przechowują elementy w jednym obszarze pamięci, podczas gdy listy potrzebują dodatkowej pamięci na przechowywanie wskaźników do kolejnych elementów.

5. **Kolejność Elementów:**
   - **Kopiec binarny vs. Lista Posortowana:** Jeśli często potrzebujesz znaleźć najmniejszy lub największy element, kopiec binarny jest bardziej efektywny niż sortowanie listy, ponieważ operacje dodawania i usuwania w kopcu binarnym mają złożoność czasową O(log n).

Ostatecznie, dobór odpowiedniej struktury danych zależy od konkretnej sytuacji i rodzaju operacji, które będą wykonywane w programie. Wielkość danych, częstość operacji oraz specyfika problemu mają kluczowe znaczenie przy wyborze struktury danych dla optymalnej wydajności.
