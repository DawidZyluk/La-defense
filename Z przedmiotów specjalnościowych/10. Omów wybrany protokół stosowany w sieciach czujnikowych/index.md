# Omów wybrany protokół stosowany w sieciach czujnikowych (Internet rzeczy) 

Jednym z popularnych protokołów stosowanych w sieciach czujnikowych, zwłaszcza w kontekście Internetu Rzeczy (IoT), jest MQTT (Message Queuing Telemetry Transport).

### Protokół MQTT:

**1. Charakterystyka:**
   - **Rodzaj Protokołu:** Oparty na protokole komunikacyjnym typu publish/subscribe.
   - **Przeznaczenie:** Optymalizowany dla komunikacji między urządzeniami o ograniczonych zasobach, często stosowany w sieciach czujnikowych i w IoT.
   - **Model Komunikacji:** Publish/Subscribe (Pub/Sub).
   - **Minimalizacja Overheadu:** Protokół został zaprojektowany z myślą o minimalizacji opóźnień i zużycia energii.

**2. Model Publikacji/Odbioru:**
   - **Publikacja (Publish):** Urządzenie może opublikować (wysłać) dane na konkretne tematy (topic). Temat identyfikuje rodzaj danych.
   - **Subskrypcja (Subscribe):** Inne urządzenia mogą subskrybować (odbierać) dane związane z określonym tematem.

**3. Lekkość i Elastyczność:**
   - **Minimalizacja Nagłówków:** Protokół jest lekki, co oznacza minimalne nagłówki komunikacyjne.
   - **Wysoka Elastyczność:** Dzięki elastycznej strukturze tematów (topics), urządzenia mogą przesyłać i odbierać dane w sposób bardzo elastyczny.

**4. QoS (Quality of Service):**
   - **Trzy Poziomy QoS:** Definiuje trzy poziomy jakości usług - od najmniejszej do największej gwarancji dostarczenia.
   - **Zaawansowane Mechanizmy QoS:** Protokół oferuje mechanizmy dla tego, aby decydować o tym, jakie informacje są ważniejsze i wymagają wyższego poziomu QoS.

**5. Bezstanowość (Statelessness):**
   - **Brak Stanu Sesji:** Każde żądanie jest niezależne od poprzednich, co sprawia, że protokół jest bezstanowy.

**6. Bezpieczeństwo:**
   - **Wspierane Mechanizmy Bezpieczeństwa:** MQTT może być używany z różnymi mechanizmami bezpieczeństwa, takimi jak TLS/SSL, co zapewnia bezpieczną komunikację.

**7. Przykłady Zastosowań:**
   - **Monitorowanie Czujników:** Stosowany w systemach monitorowania i zbierania danych z czujników.
   - **IoT i Automatyzacja Budynków:** Wykorzystywany w domowych systemach automatyki i w IoT do komunikacji między urządzeniami.

**8. Broker MQTT:**
   - **Centralny Punkt Komunikacji:** Protokół często wymaga istnienia centralnego punktu komunikacji, znanego jako broker MQTT, który zarządza przekazywaniem komunikatów między urządzeniami.

Protokół MQTT jest ceniony za swoją lekkość, prostotę oraz zdolność do obsługi urządzeń o ograniczonych zasobach, co sprawia, że jest popularnym wyborem w kontekście sieci czujnikowych i Internetu Rzeczy.