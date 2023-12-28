# Interpretacja

Interpretacja jest alternatywnym podejściem do wykonania kodu programu, które polega na natychmiastowym wykonywaniu kodu źródłowego bez wcześniejszego etapu kompilacji. Oto dokładny opis procesu interpretacji:

### 1. Analiza leksykalna:

- **Definicja:** Proces identyfikacji i analizy tokenów w kodzie źródłowym.

- **Proces:**
  - **Skanowanie:** Kod źródłowy jest skanowany w celu identyfikacji tokenów, takich jak słowa kluczowe, identyfikatory, operatory itp.
  - **Usuwanie białych znaków:** Białe znaki są często pomijane, podobnie jak w przypadku kompilacji.

### 2. Analiza składniowa:

- **Definicja:** Proces analizy struktury gramatycznej kodu źródłowego.

- **Proces:**
  - **Parser:** Parser analizuje tokeny, tworząc drzewo składniowe.
  - **Sprawdzanie poprawności:** Parser sprawdza, czy struktura kodu jest zgodna z gramatyką języka programowania.

### 3. Wykonywanie kodu:

- **Definicja:** Kod źródłowy jest natychmiastowo wykonywany linia po linii, bez konieczności generowania oddzielnego pliku wynikowego.

- **Proces:**
  - **Wykonywanie instrukcji:** Interpreter przetwarza i wykonuje instrukcje programu na bieżąco.
  - **Obsługa danych:** Interpreter zarządza danymi, zmiennymi i stanem programu w trakcie jego wykonywania.

### Obsługa błędów:

- **Definicja:** Interpreter monitoruje i obsługuje błędy w trakcie wykonywania kodu.

- **Proces:**
  - **Raportowanie błędów:** Interpreter zgłasza błędy, takie jak błędne typy danych czy odwołania do nieistniejących zmiennych.
  - **Zatrzymywanie wykonania:** W przypadku poważnych błędów interpreter może zatrzymać wykonanie programu.

### Debugowanie:

- **Definicja:** Proces identyfikacji, analizy i usuwania błędów w kodzie źródłowym.

- **Proces:**
  - **Wsparcie dla debugowania:** Interpreter może dostarczać narzędzia do śledzenia wykonania programu, umożliwiając programistom zidentyfikowanie błędów.
  - **Przerywanie wykonania:** Interpreter może umożliwiać zatrzymywanie wykonania programu w celu dokładniejszej analizy.

### Dynamiczne typowanie:

- **Definicja:** W przypadku języków z dynamicznym typowaniem, typy zmiennych są określane podczas wykonania, a nie podczas kompilacji.

- **Proces:**
  - **Dynamiczne przypisywanie typów:** Interpreter automatycznie przypisuje typy zmiennym w trakcie wykonywania programu.

### Efektywność:

- **Definicja:** Interpretacja jest często mniej efektywna niż kompilacja, ponieważ kod jest wykonywany bezpośrednio, co może prowadzić do pewnych opóźnień.

### Koniec wykonania:

- **Definicja:** Program kończy swoje wykonanie po przejściu przez cały kod źródłowy.

- **Proces:**
  - **Zwolnienie zasobów:** Interpreter zwalnia zasoby używane przez program po zakończeniu jego działania.

Interpretacja oferuje zalety takie jak szybki cykl programistyczny i łatwość debugowania, ale może być mniej wydajna niż kompilacja, szczególnie w przypadku dużych projektów. Wybór między interpretacją a kompilacją zależy od wielu czynników, takich jak wydajność, przenośność, i specyfika projektu.