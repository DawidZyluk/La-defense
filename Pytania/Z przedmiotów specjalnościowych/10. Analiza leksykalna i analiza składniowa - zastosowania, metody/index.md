# Analiza leksykalna i analiza składniowa - zastosowania, metody

**Analiza leksykalna (analiza składników leksykalnych):**

1. **Zastosowania:**

   - **Podział na Tokeny:** Analiza leksykalna dzieli źródłowy tekst na jednostki leksykalne zwane tokenami, takie jak identyfikatory, liczby, operatory, słowa kluczowe itp.
   - **Usuwanie Białych Znaków:** Pozwala na usuwanie nieistotnych dla analizy informacji, takich jak białe znaki, komentarze itp.
   - **Przygotowanie do Analizy Składniowej:** Przygotowuje strumień tokenów dla analizy składniowej, dostarczając bardziej zorganizowany i przetworzony strumień danych dla parsera.

2. **Metody:**
   
    **Automaty Skończone:**
    - **Opis:** Automat skończony to model matematyczny zdefiniowany jako graf skierowany z określonymi stanami, przejściami między stanami i zbiorami stanów akceptujących.
    - **Zastosowanie:** Automaty skończone są często używane do implementacji lekserów. Każdy stan reprezentuje określony stan analizatora, a przejścia odpowiadają poszczególnym znakom wejściowym.
    - **Przykład:** Diagram stanów automatu skończonego może reprezentować proces analizy leksykalnej, gdzie każdy stan odpowiada jednemu z możliwych stanów w analizatorze.

    **Wyrażenia Regularne:**

    - **Opis:** Wyrażenia regularne to sekwencje znaków definiujące wzorce tekstowe. Mogą być używane do opisania leksemów w językach programowania.
    - **Zastosowanie:** Wyrażenia regularne są powszechnie używane w lekserach do identyfikacji i dopasowania tokenów na podstawie zdefiniowanych wzorców.
    - **Przykład:** Wyrażenie regularne `\d+` może dopasować ciąg cyfr w tekście.

---

**Analiza składniowa (analiza gramatyczna):**

1. **Zastosowania:**

   - **Tworzenie Drzewa Składniowego:** Analiza składniowa przekształca strumień leksemów na strukturę drzewa składniowego, reprezentującego hierarchię składniową programu.
   - **Weryfikacja Poprawności Składniowej:** Sprawdza, czy struktura języka źródłowego jest zgodna z jego gramatyką.
   - **Generowanie Kodu Pośredniego:** W niektórych przypadkach analiza składniowa może generować kod pośredni w postaci AST (Abstract Syntax Tree).

2. **Metody:**
    
    **Metoda Zstępująca (Top-Down):**
   - **Opis:** Początkowo próbuje dopasować nieterminal początkowy, a następnie rozwija gramatykę od góry do dołu, używając reguł produkcji.
   - **Zastosowanie:** Metoda jest często stosowana w parserach rekurencyjnych zstępujących, które mogą być łatwo zdefiniowane za pomocą gramatyki w formie BNF (Backus-Naur Form).
   - **Przykład:** Parser rekurencyjny dla wyrażeń arytmetycznych, gdzie produkcje odpowiadają hierarchii operatorów.

    **Metoda Wstępująca (Bottom-Up):**
      - **Opis:** Początkowo rozpoczyna analizę od leksemów, a następnie próbuje budować drzewo składniowe, przesuwając się od dołu do góry.
      - **Zastosowanie:** Metoda jest wykorzystywana w parserach takich jak LR Parser, SLR Parser czy LALR Parser.
      - **Przykład:** LR Parser dla wyrażeń arytmetycznych, który rozpoczyna od identyfikacji terminali i buduje drzewo składniowe.

    **Analiza Operatorowa:**
      - **Opis:** Specjalna technika analizy składniowej wyrażeń, która uwzględnia priorytety i asocjacje operatorów.
      - **Zastosowanie:** Wykorzystywana w analizie składniowej wyrażeń arytmetycznych, logicznych itp.
      - **Przykład:** Rozważa priorytety operatorów matematycznych, takich jak mnożenie przed dodawaniem.

Analiza leksykalna i analiza składniowa są kluczowymi krokami w procesie kompilacji lub interpretacji programów komputerowych, przekształcając źródłowy kod źródłowy na struktury danych, które mogą być dalej przetwarzane.
