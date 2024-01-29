# Kompilacja

Proces kompilacji jest złożonym etapem, który przekształca kod źródłowy napisany w języku programowania na kod maszynowy lub kod pośredni. Oto bardzo dokładny opis poszczególnych etapów procesu kompilacji:

### 1. Analiza leksykalna:

Kod źródłowy jest dzielony na **tokeny**, czyli najmniejsze jednostki znaczeniowe (np. słowa kluczowe, identyfikatory, operatory). Skaner (także nazywany **lekserem**) przegląda kod źródłowy i identyfikuje tokeny na podstawie zdefiniowanych reguł gramatycznych. **Białe znaki**, takie jak spacje i tabulatory, są często pomijane.

### 2. Analiza składniowa:
**Parser** analizuje tokeny z poprzedniego etapu i tworzy **drzewo składniowe**. Parser sprawdza, czy kod źródłowy odpowiada **gramatyce** języka programowania.

### 3. Semantyczna analiza:
Weryfikacja poprawności **typów danych**, **operacji** i **zakresu zmiennych**

### 4. Optymalizacja:
Optymalizacja ma na celu poprawienie wydajności kodu poprzez eliminację niepotrzebnych lub redundanckich fragmentów.

### 5. Generowanie kodu pośredniego:
Tworzony jest kod pośredni, który jest **niezależny od konkretnej platformy sprzętowej**.


### 6. Optymalizacja kodu pośredniego:
Dodatkowy etap optymalizacji, tym razem dla kodu pośredniego.
Zoptymalizowanie struktury kodu pośredniego.

### 7. Generowanie kodu maszynowego:
Kompilator przekształca kod pośredni na kod maszynowy **dostosowany do konkretnej architektury procesora**.
Każda instrukcja kodu pośredniego jest **mapowana** z odpowiadającą instrukcję dla danego procesora.

### 8. Linkowanie:
Proces **łączenia modułów programu** w jedną całość.
Kompilator łączy **kod maszynowy zewnętrznych bibliotek** z wygenerowanym kodem programu. Przypisywanie rzeczywistych **adresów pamięci**.

### 9. Generowanie pliku wykonywalnego:
Tworzenie pliku, który może być uruchomiony na **docelowej platformie**.



