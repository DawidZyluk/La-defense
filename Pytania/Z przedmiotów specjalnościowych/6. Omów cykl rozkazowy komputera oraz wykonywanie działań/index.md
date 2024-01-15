# Omów cykl rozkazowy komputera oraz wykonywanie działań w kodzie uzupełnień do 2.

### Cykl Rozkazowy Komputera:

Cykl rozkazowy komputera to sekwencja kroków, które są wykonywane przez procesor w celu przetworzenia pojedynczego rozkazu. Podstawowe etapy cyklu rozkazowego to:

1. **Pobranie Rozkazu (Fetch):**
   - Procesor pobiera kolejny rozkaz z pamięci operacyjnej (RAM) lub pamięci podręcznej instrukcji (Cache) do rejestrów sterujących.

2. **Dekodowanie Rozkazu (Decode):**
   - Pobrany rozkaz jest dekodowany, co oznacza, że procesor interpretuje, jaka operacja powinna być wykonana.

3. **Wykonanie Operacji (Execute):**
   - Procesor wykonuje operację związana z zdekodowanym rozkazem. Może to obejmować operacje arytmetyczne, logiczne, przenoszenie danych, skoki, itp.

4. **Zapisanie Wyników (Write Back):**
   - Jeśli operacja generuje wyniki, są one zapisywane w odpowiednich rejestrach lub w pamięci.

---

### Wykonywanie Działań w Kodzie Uzupełnień do 2 (Two's Complement):

Kod uzupełnień do 2 jest sposobem reprezentacji liczb ze znakiem w komputerach. W tym systemie, liczby dodatnie są reprezentowane bezpośrednio, natomiast liczby ujemne są przedstawiane jako ich uzupełnienie do 2.

1. **Reprezentacja Liczb Dodatnich:**
   - Liczby dodatnie są reprezentowane bez zmian, czyli binarnie, np. `00101011` to liczba 43 w systemie dziesiętnym.

2. **Reprezentacja Liczb Ujemnych:**
   - Aby przedstawić liczbę ujemną, najpierw przedstawiamy ją w formie binarnej, a następnie wykonujemy operację uzupełnienia do 1 (negacja bitów). Na koniec dodajemy 1 do wyniku.
   - Przykład: `-43` w kodzie uzupełnień do 2:
     - Binarna reprezentacja `43`: `00101011`.
     - Negacja bitów: `11010100`.
     - Dodanie 1: `11010101`.

3. **Operacje Arytmetyczne:**
   - Operacje arytmetyczne (dodawanie, odejmowanie) w kodzie uzupełnień do 2 są przeprowadzane tak samo, jak w przypadku liczb bez znaku, z jednym dodatkowym krokiem - sprawdzaniem przeniesienia po najwyższym bicie.

4. **Przykład Dodawania:**
   - Dodajemy liczby `-43` i `25`:
     ```
       11010101   ; (-43)
     + 00011001   ; (25)
     ----------
       11101110   ; (-18)
     ```
   - Wynik `11101110` w kodzie uzupełnień do 2 reprezentuje liczbę `-18`.

Kod uzupełnień do 2 ułatwia operacje arytmetyczne na liczbach ze znakiem, eliminując potrzebę oddzielnych instrukcji dla dodatnich i ujemnych wartości oraz uprościwszy przekształcanie operacji arytmetycznych na operacje logiczne.