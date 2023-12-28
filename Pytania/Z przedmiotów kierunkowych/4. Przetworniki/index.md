# Przetworniki analogowo-cyfrowe i cyfrowo-analogowe; rodzaje przetworników, własności i zastosowania

### Przetworniki Analogowo-Cyfrowe (ADC):

Przetworniki analogowo-cyfrowe to urządzenia elektroniczne, które konwertują sygnał analogowy na sygnał cyfrowy, umożliwiając komputerom i mikrokontrolerom przetwarzanie i analizę danych. Istnieje kilka rodzajów przetworników analogowo-cyfrowych:

1. **Przetworniki sukcesywne aproksymacje (SAR):**
   - Polegają na iteracyjnym porównywaniu wartości analogowej z wartością cyfrową, zaczynając od najbardziej znaczącego bitu (MSB) do najmniej znaczącego bitu (LSB).

2. **Przetworniki delta-sigma:**
   - Wykorzystują modulację delta-sigma do uzyskania wysokiej rozdzielczości i niskiego poziomu szumów, często stosowane w aplikacjach audio.

3. **Przetworniki potokowe (Pipeline):**
   - Działa na zasadzie podziału procesu konwersji na kilka etapów, z każdym etapem przetwarzając kolejne bity sygnału wejściowego.

4. **Przetworniki Flash:**
   - Opierają się na równoczesnym porównywaniu sygnału wejściowego z zestawem napięć referencyjnych, co pozwala na natychmiastową konwersję.

### Własności Przetworników Analogowo-Cyfrowych:

1. **Rozdzielczość:**
   - Określa liczbę bitów w wynikowym sygnale cyfrowym, co wpływa na dokładność konwersji.

2. **Częstotliwość próbkowania:**
   - Określa, jak często przetwornik pobiera próbki sygnału analogowego. Wpływa na zdolność do reprezentowania szybkozmiennych sygnałów.

3. **Szum:**
   - Odnosi się do dodatkowych zakłóceń w wyniku konwersji, wpływających na jakość sygnału cyfrowego.

4. **Zakres dynamiczny:**
   - Różnica między najniższym a najwyższym poziomem sygnału, które mogą być skutecznie reprezentowane przez przetwornik.

### Zastosowania Przetworników Analogowo-Cyfrowych:

1. **Systemy Pomiarowe:**
   - Wprowadzanie sygnałów analogowych, takich jak temperatura, ciśnienie, czy natężenie prądu, do systemów komputerowych.

2. **Komunikacja Radiowa i Telewizyjna:**
   - Konwersja sygnałów radiowych i telewizyjnych na formę cyfrową dla lepszego przetwarzania i transmisji.

3. **Aparatura Audio:**
   - Konwersja dźwięku analogowego na cyfrowy w urządzeniach audio, takich jak mikrofony, karty dźwiękowe, itp.

4. **Systemy Sterowania:**
   - Zastosowanie w systemach sterowania, gdzie sygnały analogowe są przekształcane na dane cyfrowe dla skomputeryzowanej analizy i regulacji.

---

### Przetworniki Cyfrowo-Analogowe (DAC):

Przetworniki cyfrowo-analogowe wykonują odwrotną funkcję, konwertując sygnał cyfrowy na sygnał analogowy. Są one niezbędne w sytuacjach, gdy sterowanie lub reprezentacja sygnału wymaga formy analogowej.

### Rodzaje Przetworników Cyfrowo-Analogowych:

1. **Przetworniki PWM (Pulse Width Modulation):**
   - Sterują sygnałem o stałej częstotliwości poprzez zmianę proporcji impulsów w czasie, co efektywnie generuje sygnał analogowy.

2. **Przetworniki typu R-2R:**
   - Wykorzystują rezystory o wartościach R i 2R do generowania sygnału wyjściowego o wartościach proporcjonalnych do danych wejściowych cyfrowych.

3. **Przetworniki schodkowe (Ladder):**
   - Korzystają z konfiguracji rezystorów i przełączników, aby uzyskać napięcie wyjściowe proporcjonalne do wartości cyfrowej.

### Własności Przetworników Cyfrowo-Analogowych:

1. **Rozdzielczość:**
   - Określa ilość poziomów napięcia, które mogą być reprezentowane na wyjściu, co wpływa na precyzję konwersji.

2. **Szybkość Konwersji:**
   - Określa, jak szybko przetwornik może generować sygnał analogowy na podstawie danych wejściowych cyfrowych.

3. **Precyzja:**
   - Określa dokładność generowanego sygnału analogowego w porównaniu do wartości cyfrowej.

### Zastosowania Przetworników Cyfrowo-Analogowych:

1. **Dźwięk Cyfrowy:**
   - Konwersja sygnałów dźwiękowych z postaci cyfrowej na analogową w odtwarzaczach audio, smartfonach, itp.

2. **Sterowanie Silnikami:**
   - W systemach automatyki, gdzie sygnały sterujące muszą przyjmować formę sygnału analogowego.

3. **Transmisja Danych:**
   - Konwersja danych cyfrowych na analogowe sygnały modulacyjne do przesyłania danych, na przykład w transmisji radiowej.

4. **Generacja Napięć Referencyjnych:**
   - Stosowane do generowania stabilnych napięć referencyjnych w różnych układach elektronicznych.

Przetworniki cyfrowo-analogowe