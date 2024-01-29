# Architektury mikroprocesorów. Porównaj CISC i RISC

**Architektury mikroprocesorów** odnoszą się do struktury i organizacji komponentów wewnątrz mikroprocesora, które wykonują operacje na danych i instrukcjach programu. Istnieją dwie główne kategorie architektur mikroprocesorów: CISC (Complex Instruction Set Computing) i RISC (Reduced Instruction Set Computing). Oto porównanie obu tych architektur:

### CISC (Complex Instruction Set Computing):

1. **Rozbudowane instrukcje:** 
   - mogą manipulować danymi w pamięci, 
   - obsługiwać różnorodne tryby adresowania.
   - wykonywać operacje arytmetyczne, 
   - sterować przerwaniami 
2. **Instrukcje o różnym czasie wykonania:** Niektóre instrukcje zajmują więcej cykli zegarowych niż inne, co prowadzi do nierównomiernego obciążenia procesora.
3. **Instrukcje o różnej długości:** niektóre z nich zajmują więcej miejsca w pamięci co utrudnia dekodowanie i przetwarzanie
4. **Złożony dekoder instrukcji:** 
5. **Wsparcie dla trybów adresowania:** 
   - umożliwia skomplikowane operacje na danych. 
   - bezpośrednie, 
   - pośrednie, 
   - indeksowane,  
   - z użyciem wskaźników.
6. **Instrukcje mnemoniczne:**
7. **Wsparcie dla języków wysokiego poziomu:**
8. **Różnorodność trybów przetwarzania:** 
   - tryb użytkownika, 
   - tryb systemowy,
   - tryby chronione.
9. **Rozbudowane wbudowane funkcje:**

### RISC (Reduced Instruction Set Computing):

1. **Proste instrukcje:**
2. **Instrukcje o równym czasie wykonania:** 
3. **Instrukcje o równej długości:** mają zazwyczaj jednolity rozmiar, co ułatwia dekodowanie i przetwarzanie
4. **Szybki dekoder instrukcji:**
5. **Bogaty zestaw rejestrów:** przechowywanie tymczasowych danych bezpośrednio w rejestrach. Operacje na rejestrach są szybkie i efektywne.
6. **Architektura Load/Store:**
7. **Wysoka wydajność:**
8. **Wykorzystanie techniki pipelining:** równoczesne wykonanie kilku instrukcji w różnych etapach potoku
9. **Optymalizacja przez kompilatory:** programy są łatwe do optymalizacji przez kompilatory
