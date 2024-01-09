# Lista liniowa

Lista liniowa to struktura danych, w której elementy są uporządkowane w liniowy sposób, a każdy element zawiera referencję do następnego elementu. W zależności od rodzaju listy (jednokierunkowa, dwukierunkowa), operacje na listach mogą różnić się złożonością czasową.

### Jednokierunkowa Lista Liniowa:

1. **Wstawianie Elementu na Początek:**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Wstawianie na początek listy jednokierunkowej polega na stworzeniu nowego elementu i ustawieniu jego wskaźnika na obecny pierwszy element listy.

2. **Wstawianie Elementu na Koniec:**
   - **Złożoność:** $O(n)$ - konieczność przeszukania listy, aby dotrzeć do ostatniego elementu.
   - **Opis:** Aby wstawić element na koniec listy, należy przeszukać listę, aż dotrzeć do ostatniego elementu, a następnie ustawić wskaźnik ostatniego elementu na nowy element.

3. **Usuwanie Elementu:**
   - **Złożoność:** $O(n)$ - konieczność przeszukania listy, aby odnaleźć i usunąć element.
   - **Opis:** Usuwanie elementu polega na znalezieniu elementu do usunięcia, a następnie zmianie wskaźników w poprzednim elemencie, aby ominąć usuwany element.

4. **Szukanie Elementu:**
   - **Złożoność:** $O(n)$ - konieczność przeszukania listy.
   - **Opis:** Szukanie elementu wymaga przeszukania listy od początku do końca w poszukiwaniu odpowiedniego elementu.

### Dwukierunkowa Lista Liniowa:

W przypadku dwukierunkowej listy liniowej, dodatkowo umożliwia ona operacje wsteczne, co wpływa na pewne operacje.

1. **Wstawianie Elementu na Początek:**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Operacja jest podobna do jednokierunkowej listy, jednak wymaga aktualizacji wskaźnika poprzedniego pierwszego elementu na nowy element.

2. **Wstawianie Elementu na Koniec:**
   - **Złożoność:** $O(1)$ - stała złożoność czasowa.
   - **Opis:** Wstawianie na koniec dwukierunkowej listy jest efektywne, ponieważ możemy łatwo uzyskać dostęp do ostatniego elementu i dostosować wskaźniki.

3. **Usuwanie Elementu:**
   - **Złożoność:** $O(n)$ - konieczność przeszukania listy.
   - **Opis:** Usuwanie elementu wymaga przeszukania listy, aby znaleźć odpowiedni element do usunięcia, a następnie aktualizacji wskaźników poprzedniego i następnego elementu.

4. **Szukanie Elementu:**
   - **Złożoność:** $O(n)$ - konieczność przeszukania listy.
   - **Opis:** Tak jak w przypadku jednokierunkowej listy, szukanie elementu wymaga przeszukania listy od początku do końca.

### Zastosowania:

- **Implementacja Kolejek i Stosów:**
  Listy liniowe są często używane do implementacji kolejek i stosów.

- **Dynamiczne Zarządzanie Pamięcią:**
  Listy liniowe są używane w dynamicznym zarządzaniu pamięcią, gdzie można dynamicznie alokować i zwalniać pamięć dla nowych elementów.

- **Operacje na Listach w Strukturach Danych:**
  Listy liniowe są często używane w implementacji innych zaawansowanych struktur danych, takich jak listy, mapy czy kolejki priorytetowe.

Podsumowując, lista liniowa ma różne zastosowania i złożoności czasowe zależne od operacji oraz rodzaju listy. Jednak w wielu przypadkach umożliwia dynamiczne zarządzanie danymi w sposób efektywny.