# Tablica

Tablica to jedna z podstawowych struktur danych, a jej złożoność czasowa zależy od rodzaju operacji, które są na niej wykonywane.

### Operacje na Tablicy:

1. **Dostęp do Elementu (Odczyt/Zapis):**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Dostęp do elementu w tablicy jest bardzo efektywny, ponieważ elementy są indeksowane, co umożliwia bezpośredni dostęp.

2. **Wstawianie na Koniec:**
   - **Złożoność:** $O(1)$ - jeśli mamy dostęp do ostatniego indeksu.
   - **Opis:** Dodawanie elementu na koniec tablicy jest efektywne, ponieważ wymaga jedynie zwiększenia licznika elementów.

3. **Wstawianie w Dowolne Miejsce:**
   - **Złożoność:** $O(n)$ - konieczność przesunięcia elementów po wstawieniu.
   - **Opis:** Wstawianie w dowolne miejsce wymaga przesunięcia wszystkich elementów o jeden lub więcej miejsc.

4. **Usuwanie Elementu:**
   - **Złożoność:** $O(n)$ - konieczność przesunięcia elementów po usunięciu.
   - **Opis:** Usuwanie elementu wymaga przesunięcia pozostałych elementów, aby zachować spójność tablicy.

5. **Szukanie Elementu (Brutalna Siła):**
   - **Złożoność:** $O(n)$ - konieczność przeszukania całej tablicy.
   - **Opis:** Wyszukiwanie elementu w tablicy metodą brutalnej siły wymaga przeszukania każdego elementu w tablicy.

### Zastosowania:

- **Przechowywanie Danych o Stałym Rozmiarze:**
  Tablice są idealne do przechowywania danych o stałym rozmiarze, gdzie konieczny jest szybki dostęp do elementów za pomocą indeksów.

- **Implementacja Algorytmów Sortowania:**
  Wiele algorytmów sortowania, takich jak Quicksort czy Mergesort, opiera się na manipulacjach elementami w tablicy.

- **Reprezentacja Macierzy:**
  Tablice są wykorzystywane do reprezentacji dwuwymiarowych macierzy, gdzie indeksy pozwalają na bezpośredni dostęp do poszczególnych elementów.

- **Bufory i Kolejki:**
  W implementacji buforów, kolejek czy stosów często korzysta się z tablic.

Tablice są efektywne w przypadku operacji odczytu i zapisu, ale ich złożoność czasowa związana z wstawianiem i usuwaniem elementów może być kosztowna w przypadku dużych zbiorów danych. W takich przypadkach inne struktury danych, takie jak listy, mogą być bardziej efektywne.