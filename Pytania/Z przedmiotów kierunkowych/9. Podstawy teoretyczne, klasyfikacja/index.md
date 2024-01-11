# Podstawy teoretyczne, klasyfikacja, metody analizy i syntezy układów cyfrowych. Typowe układy o różniej skali integracji. Przykłady zastosowań.

### Podstawy Teoretyczne:

**Układy cyfrowe**, także **układy logiczne** – układy operujące na wartościach dyskretnych. Układy cyfrowe budowane są w oparciu o bramki logiczne realizujące elementarne operacje logiczne: iloczyn logiczny (AND, NAND), sumę logiczną (OR, NOR), negację NOT, różnicę symetryczną (XOR). Tworzone są układy o logice sekwencyjnej i kombinacyjnej. Początkowo układy cyfrowe były realizowane jako układy mechaniczne, następnie elektromechaniczne, współcześnie tworzone są układy elektroniczne. Złożone układy cyfrowe wykonuje się w postaci układów scalonych.

**Zalety układów cyfrowych**:

- Możliwość bezstratnego kodowania i przesyłania informacji.
 
- Uproszczony zapis i przechowywanie informacji cyfrowej.
  
- Mniejsza wrażliwość na zakłócenia elektryczne.
  
- Możliwość tworzenia układów programowalnych, których działanie określa program komputerowy (patrz: mikroprocesor, koprocesor).
  
**Wady układów cyfrowych**:

- Skomplikowanie zarówno na poziomie elektrycznym, jak i logicznym; obecnie ich projektowanie wspomagają komputery (patrz: język opisu sprzętu).
  
- Mimo większej odporności na zakłócenia, wykrywanie przekłamań stanów logicznych, np. pojawienie się wartości 0 zamiast spodziewanej 1, wymaga dodatkowych zabezpieczeń (patrz: kod korekcyjny) choć nie zawsze jest możliwe wykrycie błędu; jeszcze większy problem stanowi ewentualne odtworzenie oryginalnej informacji.
  
---

### Klasyfikacja

Ze względu na sposób przetwarzania informacji:

1. **Układy kombinacyjne** – układy „bez pamięci”, w których sygnały wyjściowe są zawsze takie same dla określonych sygnałów wejściowych;
2. **Układy sekwencyjne** – układy „z pamięcią”, w których stan wyjść zależy nie tylko od aktualnego stanu wejść, ale również od stanów wcześniejszych.

Dodatkowe kategorie klasyfikacji:
   
Ze względu na technologie w jakiej wykonano bramki logiczne:

1. **Bipolarne**:
   - TTL (ang. Transistor-Transistor Logic)
   - ECL (Emitter Coupled Logic)
   - I2L (Integrated Injection Logic).
2. **Unipolarne**:
   - NMOS i PMOS
   - CMOS (Complementary MOS)
   
Ostatnimi laty bardzo popularne stały się programowalne układy cyfrowe. W odróżnieniu od programowalnych mikroprocesorów, w tym przypadku programowana jest fizyczna struktura układu oparta na:

1. **Matrycach**:
   - PLA
   - PAL
2. **Komórkach**:
   - SPLD
   - CPLD
   - FPGA
  
# Metody analizy i syntezy układów cyfrowych

**Analiza układów cyfrowych:**

1. **Symulacje komputerowe:** Wykorzystywane są narzędzia do symulacji układów cyfrowych, które pozwalają na modelowanie zachowania układu podczas różnych scenariuszy działania. Symulacje umożliwiają przewidywanie wyników działania układu i identyfikowanie ewentualnych problemów przed implementacją fizyczną.

2. **Analiza czasowo-przestrzenna:** Określa się, jakie są opóźnienia sygnałów i jak rozkładają się ścieżki sygnałowe w przestrzeni. Analiza czasowo-przestrzenna pozwala na optymalizację układu pod kątem czasu propagacji sygnałów i minimalizację zakłóceń.

3. **Analiza sygnałów i widm:** Pozwala na zrozumienie charakterystyk sygnałów w układzie, w tym analizę zakłóceń, szumów, czy potencjalnych sygnałów niepożądanych. Analiza widmowa pozwala na identyfikację składowych częstotliwościowych w sygnałach.

4. **Analiza zużycia energii:** Współczesne układy cyfrowe muszą być efektywne energetycznie. Analiza zużycia energii obejmuje określenie, ile energii zużywa układ podczas różnych operacji i w różnych trybach pracy.

**Synteza układów cyfrowych:**

1. **Logika programowalna:** Umożliwia konfigurację układów za pomocą programowalnych układów logicznych (PLD) lub układów FPGA (Field-Programmable Gate Array). Programowanie tych układów pozwala na dostosowywanie ich funkcjonalności do konkretnych wymagań.

2. **Języki opisu sprzętu (HDL):** Synteza HDL (Hardware Description Language) umożliwia opisanie funkcjonalności układu w formie programu, który może zostać przetworzony na fizyczny układ. Popularnymi językami HDL są VHDL i Verilog.

3. **Automatyczne narzędzia projektowe:** Narzędzia CAD (Computer-Aided Design) pozwalają na automatyczne generowanie struktury układów cyfrowych na podstawie opisu funkcjonalnego. Te narzędzia potrafią optymalizować rozkład bramek logicznych, ścieżki sygnałowe i inne parametry układu.

4. **Techniki optymalizacyjne:** W trakcie syntezy stosuje się różne techniki optymalizacyjne, takie jak minimalizacja liczby bramek logicznych, optymalizacja czasu propagacji sygnałów, czy minimalizacja zużycia energii.

5. **Generacja układów ASIC:** Układy specjalizowane (ASIC - Application-Specific Integrated Circuit) są projektowane na potrzeby konkretnego zastosowania. Proces projektowania ASIC obejmuje fazę syntezy, w której opis funkcjonalny jest przekształcany w fizyczną strukturę układu. 

# Typowe układy o różniej skali integracji i przykłady zastosowań

Skala integracji określa stopień skomplikowania i wielkość układów elektronicznych zawartych na jednym chipie (układzie scalonym). Istnieje kilka kategorii układów o różnej skali integracji:

1. **SSI (Small Scale Integration):**
   - Układy SSI zawierają zazwyczaj od kilku do kilkudziesięciu bramek logicznych.
   - Przykłady to bramki NAND, NOR, XOR, itp.
   - SSI jest wykorzystywane głównie w prostych układach cyfrowych.

2. **MSI (Medium Scale Integration):**
   - Układy MSI posiadają większą liczbę bramek logicznych niż SSI, zazwyczaj od kilkudziesięciu do kilkuset.
   - Przykłady to multipleksery, demultipleksery, rejestr przesuwny, itp.
   - MSI jest stosowane w bardziej złożonych układach cyfrowych.

3. **LSI (Large Scale Integration):**
   - Układy LSI charakteryzują się dużą liczbą bramek logicznych, liczoną w tysiącach.
   - Przykłady to mikroprocesory, mikrokontrolery, pamięci RAM, itp.
   - LSI umożliwiają projektowanie bardziej zaawansowanych systemów.

4. **VLSI (Very Large Scale Integration):**
   - Układy VLSI mają ogromną liczbę bramek logicznych, zazwyczaj w zakresie od kilku tysięcy do milionów.
   - Przykłady to zaawansowane mikroprocesory, układy FPGA (Field-Programmable Gate Array), czy układy ASIC (Application-Specific Integrated Circuit).
   - VLSI pozwala na implementację skomplikowanych funkcji na jednym chipie.

5. **ULSI (Ultra Large Scale Integration):**
   - Układy ULSI to jeszcze bardziej zaawansowana kategoria, gdzie liczba bramek logicznych sięga setek milionów lub nawet miliardów.
   - Przykłady to najnowsze mikroprocesory, GPU (Graphics Processing Unit), czy pamięci flash o wysokiej pojemności.

6. **GSI (Giga Scale Integration):**
   - Układy GSI to najnowsza kategoria, charakteryzująca się liczbą bramek logicznych przekraczającą miliard.
   - Przykłady to zaawansowane procesory używane w najnowszych technologiach.
