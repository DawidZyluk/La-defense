# Drzewo

Drzewo to abstrakcyjna struktura danych składająca się z węzłów połączonych krawędziami. Węzeł może mieć zero lub więcej dzieci, ale tylko jednego rodzica (z wyjątkiem korzenia, który nie ma rodzica). W odniesieniu do złożoności czasowej algorytmów na drzewach, operacje zależą od rodzaju drzewa (binarne, wyszukiwania, AVL, czerwono-czarne itp.) oraz konkretnej operacji, której dotyczą.

### Operacje na Drzewach:

1. **Wstawianie Elementu:**
   - **Złożoność:** $O(\log n)$ do $O(n)$, w zależności od rodzaju drzewa.
   - **Opis:** Wstawianie elementu do drzewa polega na znalezieniu odpowiedniego miejsca i dodaniu nowego węzła jako liścia.

2. **Usuwanie Elementu:**
   - **Złożoność:** $O(\log n)$ do $O(n)$, w zależności od rodzaju drzewa.
   - **Opis:** Usuwanie elementu z drzewa może wymagać rekurencyjnego przeszukiwania i modyfikacji struktury drzewa.

3. **Wyszukiwanie Elementu:**
   - **Złożoność:** $O(\log n)$ do $O(n)$, w zależności od rodzaju drzewa.
   - **Opis:** Wyszukiwanie elementu w drzewie polega na porównywaniu poszukiwanego elementu z wartościami węzłów i kierowaniu się odpowiednio w lewo lub w prawo.

4. **Przechodzenie po Drzewie (In-order, Pre-order, Post-order):**
   - **Złożoność:** $O(n)$.
   - **Opis:** Operacje przechodzenia po drzewie mają złożoność czasową $O(n)$, gdzie $n$ to liczba węzłów w drzewie.

### Rodzaje Drzew:

1. **Drzewo Binarnych Poszukiwań (BST):**
   - **Złożoność:** Wstawianie, usuwanie, wyszukiwanie - $O(\log n)$ w przeciętnym przypadku, $O(n)$ w najgorszym przypadku.

2. **Drzewo AVL:**
   - **Złożoność:** Wstawianie, usuwanie, wyszukiwanie - $O(\log n)$, gdzie $n$ to liczba węzłów.

3. **Drzewo Czerwono-Czarne:**
   - **Złożoność:** Wstawianie, usuwanie, wyszukiwanie - $O(\log n)$, gdzie $n$ to liczba węzłów.

4. **Drzewo Kombinowane (B-tree):**
   - **Złożoność:** W zależności od stopnia drzewa, ale ogólnie $O(\log n)$.

### Zastosowania:

- **Struktury Danych:**
  Drzewa są podstawowym elementem struktur danych, takich jak drzewa binarne poszukiwań, stosowane w bazach danych, czy drzewa AVL i czerwono-czarne w implementacjach map i zbiorów.

- **Algorytmy Wyszukiwania:**
  Drzewa są używane w algorytmach wyszukiwania, takich jak drzewa Trie w strukturach danych obsługujących operacje na słowach.

- **Kompresja Danych:**
  Drzewa Huffman'a są stosowane w algorytmach kompresji danych.

- **Algorytmy Przetwarzania Grafów:**
  Drzewa są używane w wielu algorytmach przetwarzania grafów, takich jak drzewa ukorzenione w algorytmach BFS i DFS.

Podsumowując, drzewa są fundamentalnymi strukturami danych, które oferują różne złożoności czasowe w zależności od rodzaju drzewa i konkretnej operacji. Są szeroko stosowane w informatyce z uwagi na swoją efektywność w przechowywaniu i przeszukiwaniu danych.