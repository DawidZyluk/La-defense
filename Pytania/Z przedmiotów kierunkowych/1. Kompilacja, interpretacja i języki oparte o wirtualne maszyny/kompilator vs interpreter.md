# kompilator vs interpreter

Interpretator i kompilator to dwa różne podejścia do przekształcania i wykonywania kodu źródłowego napisanego w języku programowania. Poniżej przedstawiam kluczowe różnice między interpretacją a kompilacją:

### 1. **Faza przetwarzania:**

- **Kompilacja:**
  - **Proces:** Kod źródłowy jest przekształcany w odrębny plik wykonywalny (lub kod pośredni) w czasie kompilacji.
  - **Wynik:** Kompilator generuje plik wynikowy, który może być uruchomiony wielokrotnie bez konieczności ponownej kompilacji.

- **Interpretacja:**
  - **Proces:** Kod źródłowy jest wykonywany linia po linii podczas działania interpretera, bez generowania oddzielnego pliku wynikowego.
  - **Wynik:** Wykonywanie kodu odbywa się natychmiast podczas działania interpretera.

### 2. **Wydajność:**

- **Kompilacja:**
  - **Zalety:** Kod jest zoptymalizowany podczas kompilacji, co może prowadzić do lepszej wydajności wykonania.
  - **Wady:** Proces kompilacji może być czasochłonny, a wynikowy plik wymaga osobnego kroku przed wykonaniem.

- **Interpretacja:**
  - **Zalety:** Brak konieczności generowania pliku wynikowego, co pozwala na szybszy rozwój i łatwiejsze debugowanie.
  - **Wady:** Wydajność wykonania może być niższa ze względu na konieczność analizy i wykonywania kodu w czasie rzeczywistym.

### 3. **Portowność:**

- **Kompilacja:**
  - **Zalety:** Kody źródłowe mogą być skompilowane dla różnych platform, ale może być konieczna ponowna kompilacja dla każdej platformy docelowej.
  - **Wady:** Większa zależność od architektury docelowej.

- **Interpretacja:**
  - **Zalety:** Interpreter może dostosowywać się do różnych środowisk wykonawczych bez konieczności ponownej kompilacji.
  - **Wady:** Wydajność może być zależna od interpretatora dostępnego na danej platformie.

### 4. **Debugowanie:**

- **Kompilacja:**
  - **Zalety:** Debugowanie może być bardziej skomplikowane, a informacje o błędach mogą być mniej zrozumiałe.
  - **Wady:** Potrzebne są specjalne narzędzia do debugowania skompilowanego kodu.

- **Interpretacja:**
  - **Zalety:** Łatwiejsze debugowanie, ponieważ błędy są raportowane w kontekście kodu źródłowego.
  - **Wady:** Mniejsza optymalizacja może sprawić, że niektóre błędy będą widoczne dopiero podczas wykonania.

### 5. **Przykłady języków:**

- **Kompilacja:**
  - Języki takie jak C, C++, Rust.

- **Interpretacja:**
  - Języki takie jak Python, JavaScript, Ruby.

### 6. **Typowanie:**

- **Kompilacja:**
  - Często związana z językami o statycznym typowaniu, gdzie typy są określane podczas kompilacji.

- **Interpretacja:**
  - Często związana z językami o dynamicznym typowaniu, gdzie typy są określane podczas wykonania.

### Wiki

Tekst mówi o tym, jak programy napisane w języku wysokopoziomowym są albo bezpośrednio wykonywane przez pewnego rodzaju interpreter, albo przekształcane w kod maszynowy przez kompilator (i assembler oraz linker), aby CPU mógł je wykonać.

Kompilatory (i assemblery) zazwyczaj produkują kod maszynowy, który jest bezpośrednio wykonywany przez sprzęt komputera. Mogą jednak (opcjonalnie) generować formę pośrednią zwanej kodem obiektowym. Jest to praktycznie ten sam kod specyficzny dla danej maszyny, ale uzupełniony o tablicę symboli z nazwami i etykietami, aby bloki wykonywalne (lub moduły) były identyfikowalne i przenośne. Skompilowane programy zazwyczaj używają bloków konstrukcyjnych (funkcji) przechowywanych w bibliotece takich modułów kodu obiektowego. Do połączenia (gotowych) plików bibliotecznych z plikami obiektowymi aplikacji używa się linkera, tworząc pojedynczy plik wykonywalny. Pliki obiektowe używane do wygenerowania pliku wykonywalnego są więc często produkowane w różnych momentach, a czasem nawet przez różne języki (zdolne do generowania tego samego formatu obiektowego).

Prosty interpreter napisany w języku niskopoziomowym (np. asemblerze) może mieć podobne bloki kodu maszynowego implementujące funkcje języka wysokopoziomowego, przechowywane i wykonywane, gdy wejście funkcji w tabeli poszukiwań wskazuje na ten kod. Jednak interpreter napisany w języku wysokopoziomowym zazwyczaj stosuje inne podejście, takie jak generowanie i następnie przechodzenie drzewa analizy składniowej lub generowanie i wykonywanie pośrednich instrukcji zdefiniowanych programowo, lub obie te metody.

Podsumowując, zarówno kompilatory, jak i interpretery ogólnie przekształcają kod źródłowy (pliki tekstowe) na tokeny, oba mogą (lub nie) generować drzewo analizy składniowej, a oba mogą generować natychmiastowe instrukcje (dla maszyny stosowej, kodu kwadruplanowego lub innymi środkami). Podstawowa różnica polega na tym, że system kompilatora, w tym (wbudowany lub oddzielny) linker, generuje samodzielny program kodu maszynowego, podczas gdy system interpretera wykonuje czynności opisane przez program wysokopoziomowy.

Kompilator może więc dokonać niemal wszystkich konwersji od semantyki kodu źródłowego do poziomu maszyny raz na zawsze (czyli do momentu, gdy program trzeba będzie zmienić), podczas gdy interpreter musi wykonać pewne prace konwersji za każdym razem, gdy jest wykonywane jakieś zdanie lub funkcja. Niemniej jednak, w wydajnym interpreterze duża część pracy translacyjnej (w tym analiza typów i podobne) jest wydzielana i wykonuje się tylko za pierwszym razem, gdy program, moduł, funkcja, a nawet zdanie są uruchamiane, co jest dość zbliżone do tego, jak działa kompilator. Niemniej jednak skompilowany program zazwyczaj działa znacznie szybciej, w większości przypadków, głównie dlatego, że kompilatory są projektowane do optymalizowania kodu i mogą mieć dużo czasu na to. Dotyczy to zwłaszcza prostszych języków wysokopoziomowych bez (wielu) dynamicznych struktur danych, sprawdzeń czy sprawdzania typów.