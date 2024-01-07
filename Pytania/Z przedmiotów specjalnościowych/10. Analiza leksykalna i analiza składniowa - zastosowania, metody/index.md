# Analiza leksykalna i analiza składniowa - zastosowania, metody

**Analiza leksykalna (analiza składników leksykalnych):**

1. **Zastosowania:**
   - **Podział na Tokeny:** Analiza leksykalna dzieli źródłowy tekst na jednostki leksykalne zwane tokenami, takie jak identyfikatory, liczby, operatory, słowa kluczowe itp.
   - **Usuwanie Białych Znaków:** Pozwala na usuwanie nieistotnych dla analizy informacji, takich jak białe znaki, komentarze itp.
   - **Przygotowanie do Analizy Składniowej:** Przygotowuje strumień tokenów dla analizy składniowej, dostarczając bardziej zorganizowany i przetworzony strumień danych dla parsera.

2. **Metody:**
   - **Automaty Skończone:** Wykorzystuje automaty skończone do przetwarzania i rozpoznawania leksemów na podstawie zdefiniowanych reguł.
   - **Wyrażenia Regularne:** Definiuje reguły leksykalne za pomocą wyrażeń regularnych, które opisują wzorce dla różnych tokenów.
   - **Tablice Przejść:** Tworzy tablice przejść, które określają, jakie akcje należy podjąć w odpowiedzi na konkretne sekwencje znaków.

---

**Analiza składniowa (analiza gramatyczna):**

1. **Zastosowania:**
   - **Tworzenie Drzewa Składniowego:** Analiza składniowa przekształca strumień leksemów na strukturę drzewa składniowego, reprezentującego hierarchię składniową programu.
   - **Weryfikacja Poprawności Składniowej:** Sprawdza, czy struktura języka źródłowego jest zgodna z jego gramatyką.
   - **Generowanie Kodu Pośredniego:** W niektórych przypadkach analiza składniowa może generować kod pośredni w postaci AST (Abstract Syntax Tree).

2. **Metody:**
   - **Metoda Zstępująca (Top-Down):** Zaczyna od nieterminala początkowego i próbuje dopasować go do strumienia leksemów, rozwijając gramatykę od najbardziej ogólnych do bardziej szczegółowych.
   - **Metoda Wstępująca (Bottom-Up):** Zaczyna od leksemów i próbuje dopasować je do nieterminala początkowego, budując drzewo składniowe od dołu do góry.
   - **Analiza Operatorowa:** Specjalna technika stosowana w analizie składniowej wyrażeń, uwzględniająca priorytety i asocjacje operatorów.
   - **LR Parser, LL Parser:** Klasy parserów, które są popularne w analizie składniowej. LR Parser bazuje na analizie z lewej strony, natomiast LL Parser na analizie z prawej strony.

Analiza leksykalna i analiza składniowa są kluczowymi krokami w procesie kompilacji lub interpretacji programów komputerowych, przekształcając źródłowy kod źródłowy na struktury danych, które mogą być dalej przetwarzane.