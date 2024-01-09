# Graf

Graf to abstrakcyjna struktura danych składająca się z wierzchołków (często nazywanych także węzłami) połączonych krawędziami. Grafy mogą mieć różne właściwości i struktury, co wpływa na złożoność czasową algorytmów operujących na nich.

### Operacje na Grafach:

1. **Dodawanie Wierzchołka:**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Dodanie nowego wierzchołka do grafu polega na stworzeniu nowego węzła i dodaniu go do listy wierzchołków.

2. **Dodawanie Krawędzi:**
   - **Złożoność:** W zależności od reprezentacji grafu może wynosić $O(1)$ (np. dla macierzy sąsiedztwa) lub $O(\log n)$ do $O(n)$ (np. dla listy sąsiedztwa).
   - **Opis:** Dodanie krawędzi polega na ustanowieniu połączenia między dwoma wierzchołkami.

3. **Usuwanie Wierzchołka:**
   - **Złożoność:** W zależności od reprezentacji grafu, ale może być $O(n^2)$ dla macierzy sąsiedztwa, $O(n)$ dla listy sąsiedztwa.
   - **Opis:** Usunięcie wierzchołka wymaga aktualizacji struktury grafu, w tym usuwania krawędzi prowadzących do tego wierzchołka.

4. **Usuwanie Krawędzi:**
   - **Złożoność:** W zależności od reprezentacji grafu, ale może być $O(1)$ (np. dla macierzy sąsiedztwa) lub $O(n)$ (np. dla listy sąsiedztwa).
   - **Opis:** Usunięcie krawędzi polega na przerwaniu połączenia między dwoma wierzchołkami.

5. **Przeszukiwanie Grafu (DFS, BFS):**
   - **Złożoność:** $O(V + E)$, gdzie $V$ to liczba wierzchołków, a $E$ to liczba krawędzi.
   - **Opis:** Przeszukiwanie grafu wymaga odwiedzenia każdego wierzchołka i krawędzi co najmniej raz.

### Rodzaje Grafów:

1. **Nieskierowany Graf Prosty:**
   - **Złożoność:** Operacje są zazwyczaj $O(1)$ do $O(\log n)$.

2. **Skierowany Graf Prosty:**
   - **Złożoność:** Operacje są zazwyczaj $O(1)$ do $O(\log n)$.

3. **Graf Skierowany Acykliczny (DAG):**
   - **Złożoność:** W zależności od operacji, ale często $O(V + E)$.

4. **Graf Kierowany Z Cyklem:**
   - **Złożoność:** W zależności od operacji, ale $O(V \cdot E)$ dla niektórych algorytmów.

### Zastosowania:

- **Analiza Relacji:**
  Grafy są używane do modelowania i analizy relacji między obiektami, na przykład w społecznościach internetowych.

- **Sieci Komputerowe:**
  Grafy reprezentują struktury sieci komputerowych, gdzie wierzchołki to urządzenia, a krawędzie to połączenia.

- **Planowanie Tras:**
  W trasowaniu i planowaniu tras, grafy są używane do modelowania połączeń między punktami.

- **Grafika Komputerowa:**
  W grafice komputerowej grafy reprezentują struktury sceny, gdzie wierzchołki to obiekty, a krawędzie to relacje między nimi.

Grafy są podstawową strukturą danych w informatyce, a złożoność czasowa operacji na grafach zależy od rodzaju operacji, reprezentacji grafu oraz jego struktury.