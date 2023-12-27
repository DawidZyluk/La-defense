# Architektura systemu Android od strony programistycznej

Architektura systemu Android jest oparta na modelu komponentowym, co oznacza, że aplikacje są budowane z wielu oddzielnych komponentów, które można ponownie używać i wymieniać. Poniżej opisuję główne komponenty i struktury w architekturze systemu Android od strony programistycznej:

### 1. **Aplikacje:**
   - Podstawowym komponentem są aplikacje Android. Każda aplikacja składa się z co najmniej jednego elementu, tzw. "Android Application Package" (APK). APK zawiera kod źródłowy, zasoby, manifest aplikacji i inne pliki.

### 2. **Komponenty Aplikacji:**
   - Android definiuje kilka rodzajów komponentów aplikacji, które można łączyć, aby tworzyć kompleksowe aplikacje. Główne komponenty to:
     - **Activity:** Reprezentuje interfejs użytkownika, okno aplikacji.
     - **Service:** Wykonywanie długotrwałych operacji w tle, nawet po zamknięciu interfejsu użytkownika.
     - **Broadcast Receiver:** Odbieranie i reagowanie na powiadomienia systemowe lub z innych aplikacji.
     - **Content Provider:** Zarządzanie danymi aplikacji, dostarcza interfejs do współdzielenia danych między aplikacjami.

### 3. **Intents:**
   - Komponenty aplikacji komunikują się między sobą za pomocą Intents. Intent to abstrakcja opisująca operację do wykonania (np. otwarcie nowej aktywności) lub zdarzenie (np. otrzymanie wiadomości).

### 4. **Manifest Aplikacji:**
   - Każda aplikacja Android ma plik manifestu (AndroidManifest.xml), który zawiera informacje o aplikacji, takie jak nazwa pakietu, wersja, uprawnienia, deklaracje komponentów i inne.

### 5. **Android System Libraries:**
   - Android dostarcza zestaw bibliotek systemowych, takich jak Android Runtime (ART), które zapewniają środowisko uruchomieniowe dla aplikacji Java, oraz Android Framework, który oferuje zestaw gotowych komponentów i narzędzi programistycznych.

### 6. **Android Runtime (ART):**
   - W Android 5.0 i nowszych wersjach, ART zastąpiło Dalvik jako maszynę wirtualną Java. ART wykonuje kod aplikacji na urządzeniu i optymalizuje go dla konkretnej platformy sprzętowej.

### 7. **Android Framework:**
   - To zestaw bibliotek Java, które dostarczają interfejsy programistyczne aplikacji (API) dla deweloperów. Framework zapewnia gotowe komponenty, takie jak obsługa interfejsu użytkownika, zarządzanie danymi, obsługa zdarzeń, itp.

### 8. **Android System Services:**
   - System Android oferuje różne usługi systemowe, takie jak zarządzanie energią, zarządzanie pamięcią, obsługa sieci, obsługa plików, lokalizacja, powiadomienia, itp.

### 9. **Linux Kernel:**
   - Wszystkie urządzenia działające pod kontrolą systemu Android są oparte na jądrze Linux, które dostarcza podstawowe funkcje systemowe, zarządzanie procesami, sterowniki urządzeń, itp.

### 10. **Hardware Abstraction Layer (HAL):**
   - Warstwa abstrakcji sprzętu, która umożliwia komunikację między systemem Android a sprzętem urządzenia, niezależnie od konkretnego modelu urządzenia.

Architektura systemu Android jest elastyczna i umożliwia dostosowywanie aplikacji do różnych urządzeń i wersji systemu. Programiści korzystają z narzędzi dostarczonych przez Android SDK (Software Development Kit) do tworzenia aplikacji, które są zoptymalizowane dla różnych ekranów, rozdzielczości i wersji systemu operacyjnego.