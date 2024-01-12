# Opisz relacje między prądami i napięciami na szeregowo połączonych elementach RLC. Przedstaw stany pracy

### Równania dla Szeregowo Połączonych Elementów RLC:

 Zapiszmy równania opisujące relacje między prądami ($I$) i napięciami ($V$) na tych elementach. Załóżmy, że źródło prądu przemiennego dostarcza sinusoidalny sygnał o częstotliwości $\omega$.

### 1. Rezystor (R):

Zakładając, że prąd płynie od lewej do prawej strony rezystora, stosujemy prawo Ohma. Dla prądu stałego proporcjonoalność napięcia $V$ i natężenia $I$ wyraża się wzorem:

$$V_R = I \cdot R$$

gdzie:
- $R$ rezystancja

### 2. Kondensator (C):

Prąd płynący przez kondensator zależy od szybkości zmiany napięcia na nim. Wyraża się to równaniem:

$$I_C = C \cdot \frac{dV_C}{dt}$$

gdzie:

- $I_C$ to prąd płynący przez kondensator,
- $C$ to pojemność kondensatora,
- $\frac{dV_C}{dt}$ to szybkość zmiany napięcia na kondensatorze względem czasu.

Napięcie na kondensatorze jest związane z ładunkiem ($Q$) i pojemnością ($C$) przez równanie 
$$ 
V_C = \frac{Q}{C} 
$$

### 3. Cewka (L):

Napięcie na cewce zależy od szybkości zmiany prądu przez nią:

$$
\ V_L = L \cdot \frac{dI_L}{dt}\
$$

gdzie:

- $V_L$ to napięcie na cewce,
- $L$ to indukcyjność cewki,
- $\frac{dI_L}{dt}$ to szybkość zmiany prądu przez cewkę względem czasu.


Prąd płynący przez cewkę jest związany z napięciem przez równanie 
$$
I_L = \frac{1}{L} \int V_L \, dt
$$

### Równanie Kirchhoffa:

Zastosujmy pierwsze prawo Kirchhoffa dla napięć w szeregowym układzie RLC:

$$
\ V(t) = V_R + V_C + V_L\
$$

Podstawiając odpowiednie równania dla każdego elementu, otrzymujemy:

$$
\ V(t) = I \cdot R + \frac{1}{C} \int I_C \, dt + L \cdot \frac{dI_L}{dt}\
$$

### Prawo Drugie Kirchhoffa dla Prądów:

Prawo drugie Kirchhoffa dla prądów mówi nam, że prąd w obwodzie jest stały. Dlatego prąd przez rezystor, kondensator i cewkę jest taki sam:

$$
\ I(t) = I_R = I_C = I_L\
$$

### Szeregowy obwód rezonansowy RLC

Impedancja szeregowo połączonych elementów rezystora ,R, kondensatora C i indukcyjności L jest sumą impedancji elementów obwodu:
$$Z_{sr}=R-j{\frac {1}{\omega C}}+j\omega L=R+j\left(\omega L-{\frac {1}{\omega C}}\right),$$
moduł impedancji:
$$|Z_{sr}|={\sqrt {R^{2}+\left(\omega L-{\frac {1}{\omega C}}\right)^{2}}}.$$

Impedancja osiąga minimum o wartości R przy częstości równej:
$$\omega _{r}={\frac {1}{\sqrt {LC}}}.$$

Przy tej częstości prąd płynący przez obwód przy danym przyłożonym napięciu osiągnie maksimum (zjawisko rezonansu).

### Stany Pracy:

1. **Steady State (Stan Ustalony):**

   - W stanie ustalonym wszystkie prądy i napięcia w obwodzie osiągają stałe wartości.

2. **Transient State (Stan Przejściowy):**

   - Stan, w którym prądy i napięcia zmieniają się dynamicznie po zmianie sygnału wejściowego lub w momencie włączania obwodu.

3. **Resonance (Rezonans):**

   - Występuje, gdy częstotliwość źródła jest równa częstotliwości rezonansowej układu. Może prowadzić do znacznego wzrostu amplitudy.

4. **Damped Oscillations (Tłumione Oscylacje):**
   - Jeśli obwód zawiera rezystor, to oscylacje mogą być tłumione, a amplituda maleje w czasie.

Wartość rezystancji, indukcyjności, pojemności, częstotliwość źródła oraz warunki początkowe wpływają na charakterystykę szeregowego obwodu RLC. Analiza tego układu wymaga często użycia równań różniczkowych i uwzględnienia warunków początkowych.
