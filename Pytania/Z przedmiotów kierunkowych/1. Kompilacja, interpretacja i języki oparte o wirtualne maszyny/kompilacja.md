# Kompilacja

Proces kompilacji jest złożonym etapem, który przekształca kod źródłowy napisany w języku programowania na kod maszynowy lub kod pośredni. Oto bardzo dokładny opis poszczególnych etapów procesu kompilacji:

### 1. Analiza leksykalna:

- **Definicja:** Pierwszym krokiem jest analiza leksykalna, gdzie kod źródłowy jest dzielony na tokeny, czyli najmniejsze jednostki znaczeniowe (np. słowa kluczowe, identyfikatory, operatory).

- **Proces:**
  - **Skanowanie:** Skaner (także nazywany lekserem) przegląda kod źródłowy i identyfikuje tokeny na podstawie zdefiniowanych reguł gramatycznych.
  - **Usuwanie białych znaków:** Białe znaki, takie jak spacje i tabulatory, są często pomijane.

### 2. Analiza składniowa:

- **Definicja:** W tym etapie analizujemy strukturę gramatyczną kodu źródłowego. Wynikiem jest drzewo składniowe.

- **Proces:**
  - **Parser:** Parser analizuje tokeny z poprzedniego etapu i tworzy drzewo składniowe.
  - **Sprawdzanie poprawności:** Parser sprawdza, czy kod źródłowy odpowiada gramatyce języka programowania.

### 3. Semantyczna analiza:

- **Definicja:** W tym etapie sprawdzane są znaczenia poszczególnych konstrukcji językowych.

- **Proces:**
  - **Sprawdzanie typów:** Weryfikacja poprawności typów danych i operacji.
  - **Rozpoznawanie zasięgu:** Określanie, gdzie i jak zmienne są dostępne.

### 4. Optymalizacja:

- **Definicja:** Optymalizacja ma na celu poprawienie wydajności kodu poprzez eliminację niepotrzebnych lub redundanckich fragmentów.

- **Proces:**
  - **Optymalizacje lokalne:** Zoptymalizowanie pojedynczych bloków kodu.
  - **Optymalizacje globalne:** Zoptymalizowanie całego programu.

### 5. Generowanie kodu pośredniego:

- **Definicja:** Tworzony jest kod pośredni, który jest niezależny od konkretnej platformy sprzętowej.

- **Proces:**
  - **Generowanie instrukcji pośrednich:** Kompilator tworzy kod pośredni, który jest abstrakcyjnym reprezentantem operacji programu.

### 6. Optymalizacja kodu pośredniego:

- **Definicja:** Dodatkowy etap optymalizacji, tym razem dla kodu pośredniego.

- **Proces:**
  - **Optymalizacje specyficzne dla kodu pośredniego:** Zoptymalizowanie struktury kodu pośredniego.

### 7. Generowanie kodu maszynowego:

- **Definicja:** Kompilator przekształca kod pośredni na kod maszynowy dostosowany do konkretnej architektury procesora.

- **Proces:**
  - **Mapowanie na instrukcje procesora:** Każda instrukcja kodu pośredniego jest mapowana na równoważną instrukcję dla danego procesora.
  - **Optymalizacje specyficzne dla architektury:** Dalsze optymalizacje uwzględniające cechy konkretnej platformy sprzętowej.

### 8. Linkowanie:

- **Definicja:** Proces łączenia różnych modułów programu w jedną całość.

- **Proces:**
  - **Łączenie modułów:** Kompilator łączy kod maszynowy zewnętrznych bibliotek z wygenerowanym kodem programu.
  - **Rozwiązanie odwołań do symboli:** Przypisywanie rzeczywistych adresów pamięci do odwołań do symboli.

### 9. Generowanie pliku wykonywalnego:

- **Definicja:** Tworzenie pliku, który może być uruchomiony na docelowej platformie.

- **Proces:**
  - **Tworzenie pliku wykonywalnego:** Kompilator generuje plik wykonywalny, który może być uruchomiony na komputerze docelowym.

Ostateczny plik wykonywalny zawiera już kod maszynowy, gotowy do uruchomienia na odpowiedniej platformie sprzętowej. Proces kompilacji jest kluczowym etapem w tworzeniu programów, umożliwiając programistom pisanie kodu w wysokopoziomowym języku programowania i uruchamianie go na różnych systemach komputerowych.