# Omów urządzenia występujące w sieciach komputerowych zgodnie z modelem ISO/OSI

Model OSI (Open Systems Interconnection) jest modelem warstwowym, który pomaga zrozumieć i opisać, jak różne elementy sieci komunikują się ze sobą. Składa się z siedmiu warstw, z których każda odpowiada za konkretne zadania. Oto omówienie urządzeń występujących w sieciach komputerowych zgodnie z modelem OSI:

1. **Warstwa Fizyczna (Warstwa 1):**
   - **Charakterystyka:** Odpowiada za przesyłanie bitów między urządzeniami. Zajmuje się sprzętowymi aspektami transmisji danych, takimi jak kable, sygnały elektryczne i świetlne.
   - **Przykładowe Urządzenia:**
      - **Hub:** Proste urządzenie, które przekazuje dane do wszystkich podłączonych urządzeń w sieci fizycznej.
      - **Kable, Złącza, Wzmacniacze:** Elementy fizyczne niezbędne do przesyłania sygnałów.

2. **Warstwa Łącza Danych (Warstwa 2):**
   - **Charakterystyka:** Zapewnia niezawodny przesył danych między sąsiednimi węzłami w sieci. Odpowiada za adresację fizyczną i zarządzanie dostępem do medium transmisyjnego.
   - **Przykładowe Urządzenia:**
      - **Switch (Przełącznik):** Ustala połączenia między różnymi portami, filtrowanie ruchu na podstawie adresów MAC.
      - **Bridge (Most):** Połącza dwa segmenty sieci, działając na warstwie 2, podejmując decyzje na podstawie adresów MAC.

3. **Warstwa Sieci (Warstwa 3):**
   - **Charakterystyka:** Odpowiada za rutowanie i przekazywanie pakietów między różnymi sieciami. Zarządza adresacją logiczną i decyduje o najlepszej ścieżce dla pakietu.
   - **Przykładowe Urządzenia:**
      - **Router:** Przekazuje pakiety między różnymi sieciami, podejmuje decyzje na podstawie adresów IP.
      - **Layer 3 Switch:** Kombinuje funkcje routera i switcha, umożliwiając przekazywanie pakietów na podstawie adresów IP.

4. **Warstwa Transportowa (Warstwa 4):**
   - **Charakterystyka:** Zapewnia niezawodną komunikację między aplikacjami na różnych urządzeniach. Odpowiada za segmentację, kolejkowanie i przesyłanie pakietów.
   - **Przykładowe Urządzenia:**
      - **Brama (Gateway) na Poziomie Transportu:** Może pełnić funkcje konwersji między różnymi protokołami transportowymi, np. TCP a UDP.

5. **Warstwa Sesji (Warstwa 5):**
   - **Charakterystyka:** Zarządza sesjami komunikacyjnymi między aplikacjami na różnych urządzeniach. Kontroluje rozpoczynanie, utrzymywanie i zakończenie sesji.
   - **Przykładowe Urządzenia:**
      - **Serwery Sesji:** Mogą zarządzać i kontrolować sesje między aplikacjami.

6. **Warstwa Prezentacji (Warstwa 6):**
   - **Charakterystyka:** Odpowiada za konwersję, kodowanie i kompresję danych, aby aplikacje na różnych urządzeniach mogły współpracować.
   - **Przykładowe Urządzenia:**
      - **Brak dedykowanych urządzeń. Funkcje tej warstwy są zazwyczaj wbudowane w aplikacje i systemy operacyjne.**

7. **Warstwa Aplikacji (Warstwa 7):**
   - **Charakterystyka:** Zapewnia interfejs między aplikacjami a siecią. Odpowiada za komunikację między różnymi aplikacjami, obsługuje protokoły komunikacyjne.
   - **Przykładowe Urządzenia:**
      - **Serwery Aplikacji:** Zapewniają usługi i zasoby aplikacyjne dla użytkowników lub innych aplikacji.

Każda z tych warstw pełni określone funkcje, a urządzenia w sieci współpracują, aby umożliwić skomplikowane procesy komunikacyjne w modelu OSI.