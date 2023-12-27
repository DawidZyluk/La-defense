# Filtry cyfrowe; rodzaje filtrów, specyfikacja własności filtrów, metody projektowania

Filtry cyfrowe to systemy przetwarzania sygnałów, które operują na danych cyfrowych, eliminując lub wzmacniając pewne składowe sygnału. Filtry cyfrowe są szeroko stosowane w dziedzinie przetwarzania sygnałów, telekomunikacji, systemach audio i wielu innych dziedzinach. Istnieje wiele rodzajów filtrów cyfrowych, różniących się strukturą, właściwościami i zastosowaniami. Poniżej omówię podstawowe rodzaje, specyfikację właściwości oraz metody projektowania filtrów cyfrowych.

### Rodzaje filtrów cyfrowych:

1. **Filtr dolnoprzepustowy (LPF - Low Pass Filter):**
   - Przepuszcza składowe sygnału o niższych częstotliwościach, odcinając te o wyższych.

2. **Filtr górnoprzepustowy (HPF - High Pass Filter):**
   - Przepuszcza składowe sygnału o wyższych częstotliwościach, odcinając te o niższych.

3. **Filtr pasmowoprzepustowy (BPF - Band Pass Filter):**
   - Przepuszcza składowe sygnału zawarte w określonym paśmie częstotliwości.

4. **Filtr pasmowozaporowy (BRF - Band Reject Filter):**
   - Odcina składowe sygnału zawarte w określonym paśmie częstotliwości.

### Specyfikacja właściwości filtrów cyfrowych:

1. **Charakterystyka Amplitudowa:**
   - Opisuje, jak filtr wpływa na amplitudę różnych częstotliwości sygnału.

2. **Charakterystyka Fazowa:**
   - Opisuje przesunięcia fazowe wprowadzane przez filtr w zależności od częstotliwości sygnału.

3. **Strefa Przejściowa:**
   - Obszar, w którym sygnał zmienia się od przepuszczania do odcinania, charakteryzujący się stopniowym zmniejszaniem amplitudy.

4. **Wskaźnik odrzutu (Rejection Ratio):**
   - Określa stopień, w jakim filtr redukuje amplitudę składowych sygnału poza pasmem przepuszczania.

5. **Szerokość Pasma (Bandwidth):**
   - Zakres częstotliwości, w którym filtr działa efektywnie.

### Metody projektowania filtrów cyfrowych:

1. **Projektowanie w Domenie Czasu:**
   - Filtry impulsowe, takie jak filtr średniej ruchomej, są projektowane bezpośrednio w dziedzinie czasu.

2. **Projektowanie w Domenie Częstotliwości:**
   - Filtry są projektowane w dziedzinie częstotliwości, a następnie przekształcane do dziedziny czasu.

3. **Projektowanie Zaawansowane:**
   - Metody takie jak projektowanie z wykorzystaniem okien, projektowanie przy użyciu funkcji aproksymacyjnych (na przykład metoda aproksymacji częstościowej), czy projektowanie za pomocą transformacji.

4. **Projektowanie Filtrów FIR (Finite Impulse Response) i IIR (Infinite Impulse Response):**
   - Filtry FIR posiadają skończoną odpowiedź impulsową, a filtry IIR posiadają nieskończoną odpowiedź impulsową.

5. **Projektowanie Filtrów adaptacyjnych:**
   - Filtry, które automatycznie dostosowują swoje parametry w zależności od warunków środowiskowych lub wymagań sygnału.

Filtry cyfrowe są szeroko stosowane do poprawy jakości sygnałów, usuwania zakłóceń, czy nawet w dziedzinie syntezy sygnałów. Wybór odpowiedniej metody projektowania zależy od konkretnych wymagań aplikacji i charakterystyki sygnału.