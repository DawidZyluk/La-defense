# Struktury danych

Różne struktury danych różnią się pod względem złożoności czasowej w zależności od rodzaju operacji, jakie na nich wykonujemy. Poniżej przedstawiam krótkie charakterystyki kilku popularnych struktur danych pod kątem ich złożoności czasowej:

### 1. **Tablica (Array):**
   - **Dostęp do Elementu:** $O(1)$ - stała złożoność czasowa, ponieważ elementy tablicy są indeksowane.
   - **Wstawianie na Końcu:** $O(1)$ - jeśli mamy dostęp do ostatniego indeksu.
   - **Wstawianie w Dowolnym Miejscu:** $O(n)$ - konieczność przesunięcia elementów po wstawieniu.

### 2. **Lista Jednokierunkowa (Singly Linked List):**
   - **Dostęp do Elementu:** $O(n)$ - wymaga przeszukania listy od początku do żądanego indeksu.
   - **Wstawianie na Końcu:** $O(n)$ - wymaga przeszukania całej listy.
   - **Wstawianie w Dowolnym Miejscu:** $O(n)$ - wymaga znalezienia odpowiedniego miejsca i przesunięcia elementów.

### 3. **Lista Dwukierunkowa (Doubly Linked List):**
   - **Dostęp do Elementu:** $O(n)$ - wymaga przeszukania listy od początku lub końca do żądanego indeksu.
   - **Wstawianie na Końcu:** $O(1)$ - dzięki wskaźnikowi do ostatniego elementu.
   - **Wstawianie w Dowolnym Miejscu:** $O(n)$ - wymaga znalezienia odpowiedniego miejsca i przesunięcia elementów.

### 4. **Kopiec Binarny (Binary Heap):**
   - **Wstawianie Elementu:** $O(\log n)$ - czas potrzebny na przywrócenie własności kopca po wstawieniu.
   - **Usunięcie Elementu:** $O(\log n)$ - czas potrzebny na przywrócenie własności kopca po usunięciu korzenia.

### 5. **Drzewo Binarne Przeszukiwań (Binary Search Tree - BST):**
   - **Wstawianie Elementu:** $O(h)$, gdzie $h$ to wysokość drzewa.
   - **Wyszukiwanie Elementu:** $O(h)$.
   - **Usuwanie Elementu:** $O(h)$.

### 6. **Tablica Haszująca (Hash Table):**
   - **Wstawianie Elementu:** $O(1)$ - w przypadku braku konfliktów.
   - **Wyszukiwanie Elementu:** $O(1)$ - w przypadku braku konfliktów.
   - **Usuwanie Elementu:** $O(1)$ - w przypadku braku konfliktów.

### 7. **Graf (Graph):**
   - **Dostęp do Krawędzi/Łuku:** $O(1)$ - jeśli znamy identyfikatory wierzchołków.
   - **Wstawianie Krawędzi/Łuku:** $O(1)$ - w przypadku reprezentacji macierzowej.
   - **Przeszukiwanie Wszerz (BFS) i W Głąb (DFS):** $O(V + E)$, gdzie $V$ to liczba wierzchołków, a $E$ to liczba krawędzi.

Podczas projektowania algorytmów i struktur danych ważne jest zrozumienie złożoności czasowej, ponieważ to wpływa na wydajność operacji w zależności od konkretnego scenariusza użycia. Nie ma jednej struktury danych, która byłaby optymalna we wszystkich przypadkach, dlatego dobór zależy od konkretnych wymagań problemu.