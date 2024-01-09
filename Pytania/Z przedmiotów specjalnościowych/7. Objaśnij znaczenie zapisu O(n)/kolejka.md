# Kolejka

Kolejka to abstrakcyjna struktura danych, w której elementy dodawane są na jednym końcu (tzw. tył) i usuwane są z drugiego końca (tzw. przód). W odniesieniu do złożoności czasowej operacji, związanych z kolejką, możemy podać następujące informacje:

### Operacje na Kolejce:

1. **Wstawianie Elementu (Enqueue):**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Dodawanie elementu na koniec kolejki polega na umieszczeniu go w miejscu, które jest aktualnie oznaczane jako koniec kolejki. Jest to bardzo efektywna operacja.

2. **Usuwanie Elementu (Dequeue):**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Usuwanie elementu z przodu kolejki polega na usunięciu elementu, który jest aktualnie oznaczany jako przód kolejki. Jest to również bardzo efektywna operacja.

3. **Odczytanie Elementu na Przodzie (Front):**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Odczytanie elementu znajdującego się na przodzie kolejki jest szybkie, ponieważ przód jest zawsze dostępny.

4. **Sprawdzenie Pustej Kolejki:**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Prosta operacja sprawdzenia, czy kolejka jest pusta.

### Zastosowania:

- **Algorytmy BFS (Breadth-First Search):**
  Kolejki są powszechnie używane do implementacji algorytmów przeszukiwania wszerz.

- **Zarządzanie Zadaniami:**
  Kolejki są często stosowane w zarządzaniu zadaniami lub procesami, gdzie nowe zadania są dodawane na koniec kolejki, a procesy są wykonywane w kolejności FIFO (First In, First Out).

- **Bufory:**
  Kolejki są wykorzystywane jako bufory w systemach komunikacyjnych, gdzie dane są kolejkowane przed przekazaniem.

- **Obsługa Zdarzeń:**
  Kolejki są stosowane do obsługi zdarzeń w systemach interaktywnych, takich jak obsługa zdarzeń myszy lub klawiatury.

Kolejki są skutecznym narzędziem w przypadku potrzeby operacji w kolejności, a ich złożoność czasowa pozwala na efektywne zarządzanie danymi w strukturze FIFO.