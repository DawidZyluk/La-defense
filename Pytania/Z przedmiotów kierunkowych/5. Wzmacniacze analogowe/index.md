# Wzmacniacze analogowe; własności wzmacniaczy i podstawowe zastosowania

### Wzmacniacze Analogowe:

https://www.youtube.com/watch?v=fmRHDqcodS4

Wzmacniacze analogowe to urządzenia elektroniczne, które zwiększają amplitudę sygnału elektrycznego. Są one kluczowym elementem w elektronice, umożliwiając wzmacnianie sygnałów słabych do poziomów, które są bardziej przydatne do przetwarzania, sterowania lub dalszej transmisji. Istnieje wiele różnych rodzajów wzmacniaczy, a każdy z nich ma swoje unikalne właściwości i zastosowania.

Wzmacniacz elektroniczny to urządzenie, które może zwiększyć wielkość sygnału (napięcia lub prądu zmiennego w czasie). Jest to dwuportowy obwód elektroniczny, który wykorzystuje energię elektryczną z zasilacza do zwiększania amplitudy (wielkości napięcia lub prądu) sygnału podawanego na wejście, wytwarzając proporcjonalnie większy sygnał amplitudy na wyjściu. Wzmacniacz definiuje się jako obwód, którego wzmocnienie mocy jest większe niż jeden. Wzmacniacz może być oddzielnym urządzeniem lub obwodem elektrycznym zawartym w innym urządzeniu. Wzmocnienie ma fundamentalne znaczenie dla współczesnej elektroniki, a wzmacniacze są szeroko stosowane w prawie każdym sprzęcie elektronicznym. Wzmacniacze można klasyfikować na różne sposoby. Jednym z nich jest częstotliwość wzmacnianego sygnału elektronicznego:
- **wzmacniacze audio** wzmacniają sygnały w zakresie audio (dźwięku) mniejszym niż 20 kHz, 
- **wzmacniacze RF** wzmacniają częstotliwości w zakresie częstotliwości radiowych od 20 kHz do 300 GHz, 
- **serwowzmacniacze i wzmacniacze pomiarowe** mogą pracować z bardzo niskimi częstotliwościami takimi jak prąd stały. 
 
**Wzmocnienie mocy**

Wielkość wzmocnienia zapewnianego przez wzmacniacz mierzy się jego wzmocnieniem: stosunkiem napięcia wyjściowego, prądu lub mocy do wejścia. 

$$G\,[{\text{dB}}]=10\log \left({\frac {P_{wy}}{P_{we}}}\right)$$

gdzie:
- $P_{we}$ - moc wejściowa
- $P_{wy}$ - moc wyjściowa
  
**Wzmocnienie (natężenia) prądu**

Wzmocnienie prądu w decybelach wyraża się wzorem:

$$G\,[{\text{dB}}]=10\log \left({\frac {I_{wy}}{I_{we}}}\right)^{2}$$
lub równoważnym mu:

$$G\,[{\text{dB}}]=20\log \left({\frac {I_{wy}}{I_{we}}}\right),$$
gdzie:

$I_{wy}$ – natężenie prądu na wyjściu układu,

$I_{we}$ – natężenie prądu na wejściu układu.

Analogicznie jak uprzednio, moc można zapisać wzorem: 
$P=I^{2}R,$ wtedy wzór na wzmocnienie mocy przyjmuje postać:

$$G\,[{\text{dB}}]=10\log {\frac {({I_{wy}}^{2}R_{wy})}{({I_{we}}^{2}R_{we})}}$$


### Własności Wzmacniaczy Analogowych:

1. **Wzmocnienie (Gain)** - Odnosi się do stopnia, o który wzmacniacz zwiększa amplitudę sygnału. Jest to stosunek amplitudy sygnału wyjściowego do sygnału wejściowego, wyrażony w jednostkach dB (decybeli) lub jako liczba bez jednostki.

2. **Pasmo Przenoszenia** - Określa zakres częstotliwości, w którym wzmacniacz efektywnie wzmacnia sygnał. Jest to istotne w zastosowaniach, gdzie istnieje konieczność zachowania odpowiedzi na różne częstotliwości.

3. **Oporność Wejściowa i Wyjściowa** - Oporność wejściowa to oporność, jaką wzmacniacz oferuje sygnałowi wejściowemu, podczas gdy oporność wyjściowa to oporność, jaką widzi sygnał wyjściowy. Niskie wartości oporności wejściowej są ważne w celu minimalizacji obciążenia źródła sygnału.

4. **Stabilność** - Wzmacniacze powinny być stabilne, aby unikać drgań, oscylacji i innych niestabilności, które mogą wprowadzać zakłócenia do sygnału.

5. **Szumy i Zniekształcenia:** - Szumy to niepożądane zakłócenia dodawane przez wzmacniacz, a zniekształcenia to wszelkie odkształcenia sygnału wzmacnianego. Dobry wzmacniacz powinien minimalizować obie te efekty.

### Podstawowe Zastosowania:

1. **Audio** - Wzmacniacze są szeroko stosowane w systemach audio, takich jak wzmacniacze mocy w odtwarzaczach audio, wzmacniacze słuchawkowe, itp.

2. **Komunikacja Radiowa** - Wzmacniacze są kluczowe w odbiornikach radiowych i transmiterach, wzmacniając sygnały radiowe przed przetworzeniem lub transmisją.

3. **Elektronika Instrumentacyjna** - Wzmacniacze są używane w układach pomiarowych i instrumentacyjnych do wzmacniania sygnałów pomiarowych, takich jak napięcie lub prąd.

4. **Telekomunikacja** - Wzmacniacze są używane w sieciach telekomunikacyjnych do wzmacniania sygnałów w celu utrzymania ich jakości na dużych odległościach.

5. **Elektronika Medyczna** - Wzmacniacze są stosowane w urządzeniach medycznych do wzmacniania sygnałów biomedycznych, takich jak EKG czy EEG.

6. **Elektronika Samochodowa** - Wzmacniacze mocy są używane w systemach audio samochodowych do wzmocnienia sygnału dźwiękowego z odtwarzacza lub radia.

7. **Przemysł** - Wzmacniacze są używane w różnych zastosowaniach przemysłowych, takich jak automatyka, sterowanie procesem czy monitorowanie.

