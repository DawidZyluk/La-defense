# Języki oparte o wirtualne maszyny

**Wirtualna Maszyna (VM):** Jest to abstrakcyjna maszyna, która symuluje funkcje rzeczywistej maszyny komputerowej. Oferuje zestaw instrukcji i środowisko wykonawcze dla kodu pośredniego.

- są **kompilowane do kodu pośredniego** zamiast bezpośrednio do kodu maszynowego danego komputera. 
- Ten kod pośredni jest później **interpretowany lub kompilowany** przez wirtualną maszynę, 
- pozwala na **uruchamianie tego samego kodu na różnych platformach** sprzętowych. 


### 1. **Kompilacja JIT**
W niektórych przypadkach kod pośredni może być kompilowany Just-In-Time (JIT) na maszynie docelowej przed wykonaniem.

### 2. **Automatyczne zarządzanie pamięcią (Garbage collector)**
Wirtualna maszyna często oferuje mechanizmy automatycznego zarządzania pamięcią, ułatwiające programistom pracę.


### 3. **Wyższe zużycie zasobów**
 Wirtualna maszyna wprowadza pewien narzut związany z interpretacją lub kompilacją JIT, co może skutkować wyższym zużyciem zasobów.

**Przykłady języków:**
  - **Java:** Kompilacja do bajtowego kodu Java, uruchamianego na maszynie wirtualnej Java (JVM).
  - **C#:** Kompilacja do Common Intermediate Language (CIL), uruchamianego na platformie .NET.
  - **Python:** Często używa wirtualnej maszyny Python (CPython), gdzie kod źródłowy jest kompilowany do bajtowego kodu Pyc i interpretowany przez VM.


