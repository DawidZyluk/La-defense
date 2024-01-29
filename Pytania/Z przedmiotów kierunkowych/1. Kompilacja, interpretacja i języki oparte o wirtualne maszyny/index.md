# Kompilacja, interpretacja i języki oparte o wirtualne maszyny – omów podobieństwa i różnice

## Kompilacja:

**Definicja:** Kompilacja to proces przekształcania kodu źródłowego napisanego w języku programowania na kod maszynowy lub kod pośredni, który może być później wykonywany przez komputer.

**Pełny proces:**
1. **Analiza leksykalna**: Lekser dzieli kod źródłowy na tokeny oraz usuwa białe znaki
2. **Analiza składnionwa**: Parser tworzy drzewo składniowe w oparciu o tokeny oraz sprawdza, czy kod źródłowy jest poprawny gramatycznie
3. **Semantyczna analiza**: Sprawdzenie poprawności operacji, typów danych oraz zakresów zmiennych
4. **Optymalizacja**: poprawienie wydajności kodu poprzez eliminację niepotrzebnych lub redundanckich fragmentów.
5. **Generowanie kodu pośredniego**: Tworzony jest kod pośredni, który jest niezależny od konkretnej platformy sprzętowej.
6. **Optymalizacja kodu pośredniego**: poprawienie wydajności kodu poprzez eliminację niepotrzebnych lub redundanckich fragmentów.
7. **Generowanie kodu maszynowego**: dostosowanego do konkretnej architektury procesora. Każda instrukcja kodu pośredniego jest mapowana z odpowiadającą instrukcją danego procesora.
8. **Linkowanie**: Proces łączenia modułów programu w jedną całość. Przypisywanie adresów pamięci.
9. **Generowanie pliku wykonalnego**: Tworzenie pliku, który może być uruchomiony na docelowej platformie.


## Interpretacja:

Interpretacja jest alternatywnym podejściem do wykonania kodu programu, które polega na natychmiastowym wykonywaniu kodu źródłowego bez wcześniejszego etapu kompilacji. Oto dokładny opis procesu interpretacji:

1. **Analiza leksykalna**: Lekser dzieli kod źródłowy na tokeny oraz usuwa białe znaki
2. **Analiza składnionwa**: Parser tworzy drzewo składniowe w oparciu o tokeny oraz sprawdza, czy kod źródłowy jest poprawny gramatycznie
3. **Wykonywanie kodu**: Interpreter przetwarza i wykonuje instrukcje programu na bieżąco.
Interpreter zarządza danymi, zmiennymi i stanem programu w trakcie jego wykonywania.
4. **Obsługa błędów**: Interpreter monitoruje i obsługuje błędy w trakcie wykonywania kodu.
5. **Debugowanie**: Interpreter może dostarczać narzędzia do śledzenia wykonania programu, umożliwiając programistom zidentyfikowanie błędów.
6. **Dynamiczne typowanie**: Interpreter automatycznie przypisuje typy zmiennym w trakcie wykonywania programu.
7. **Efektywność**: Interpretacja jest często mniej efektywna niż kompilacja, ponieważ kod jest wykonywany bezpośrednio, co może prowadzić do pewnych opóźnień.

## Języki oparte o wirtualne maszyny:

**Wirtualna Maszyna (VM):** Jest to abstrakcyjna maszyna, która symuluje funkcje rzeczywistej maszyny komputerowej. Oferuje zestaw instrukcji i środowisko wykonawcze dla kodu pośredniego.

1. **Kompilowane do kodu pośredniego** zamiast bezpośrednio do kodu maszynowego danego komputera. 
2. Kod pośredni jest później **interpretowany lub kompilowany** przez wirtualną maszynę, 
3.  **Uruchamianie tego samego kodu na różnych platformach sprzętowych**. 


4. **Kompilacja JIT i AOT**: W niektórych przypadkach kod pośredni może być kompilowany Just-In-Time (JIT) lub Ahead-of-Time (AOT) na maszynie docelowej.

5. **Automatyczne zarządzanie pamięcią (Garbage collector)**: Wirtualna maszyna często oferuje mechanizmy automatycznego zarządzania pamięcią, ułatwiające programistom pracę.


6. **Wyższe zużycie zasobów**: Wirtualna maszyna wprowadza pewien narzut związany z interpretacją lub kompilacją JIT, co może skutkować wyższym zużyciem zasobów.

**Przykłady języków:**
  - **Java:** Kompilacja do bajtowego kodu Java, uruchamianego na maszynie wirtualnej Java (JVM).
  - **C#:** Kompilacja do Common Intermediate Language (CIL), uruchamianego na platformie .NET.
  - **Python:** Często używa wirtualnej maszyny Python (CPython), gdzie kod źródłowy jest kompilowany do bajtowego kodu Pyc i interpretowany przez VM.