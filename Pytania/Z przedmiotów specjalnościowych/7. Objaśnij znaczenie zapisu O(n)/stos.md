# Stos

Stos to abstrakcyjna struktura danych, w której elementy są dodawane i usuwane tylko z jednego końca, zwyczajowo zwanego wierzchołkiem. Operacje dodawania elementu na wierzch stosu nazywane są "push", natomiast operacje usuwania elementu z wierzchołka to "pop". Złożoność czasowa operacji stosu jest zazwyczaj stała, co sprawia, że stos jest bardzo efektywną strukturą danych.

### Operacje na Stosie:

1. **Dodawanie Elementu (Push):**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Nowy element jest dodawany na wierzch stosu, co nie wymaga przeglądania innych elementów.

2. **Usuwanie Elementu (Pop):**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Element z wierzchołka stosu jest usuwany, co również nie wymaga przeglądania innych elementów.

3. **Odczytanie Elementu na Wierzchu (Top):**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Odczytanie elementu znajdującego się na wierzchu stosu jest szybkie, ponieważ wierzchołek jest zawsze dostępny.

4. **Sprawdzenie Pustego Stosu:**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Prosta operacja sprawdzenia, czy stos jest pusty.

### Zastosowania:

- **Algorytmy DFS (Depth-First Search):**
  Stos jest często używany do implementacji algorytmów przeszukiwania w głąb.

- **Wyrażenia Matematyczne:**
  Stos jest wykorzystywany do ewaluacji wyrażeń matematycznych w odwrotnej notacji polskiej (RPN).

- **Zarządzanie Kontekstem:**
  W przypadku wywołań funkcji czy rekurencji, stos jest używany do zarządzania kontekstem wywołań.

- **Obsługa Przerwań:**
  W systemach operacyjnych stos często jest używany do obsługi przerwań, gdzie kontekst przerwania jest zapisywany na stosie.

Stosy są efektywnym narzędziem w przypadku potrzeby przetwarzania danych w kolejności LIFO (Last In, First Out), a ich złożoność czasowa pozwala na szybkie dodawanie, usuwanie i odczytywanie elementów.