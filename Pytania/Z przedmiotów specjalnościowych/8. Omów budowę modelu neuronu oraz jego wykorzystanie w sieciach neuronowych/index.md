# Omów budowę modelu neuronu oraz jego wykorzystanie w sieciach neuronowych 

### Budowa Modelu Neuronu:

Neuron w kontekście sztucznych sieci neuronowych jest modelem inspirowanym biologicznymi neuronami, ale uproszczonym i przystosowanym do celów obliczeniowych. Klasyczny model neuronu w sztucznych sieciach neuronowych składa się z kilku kluczowych elementów:

1. **Wejścia (Inputs):** Każde wejście neuronu reprezentuje pewną cechę lub wartość, które są przypisane wagom.

2. **Wagi (Weights):** Każde wejście jest przemnożone przez odpowiadającą mu wagę. Wagi określają, jak bardzo dane wejście jest istotne dla działania neuronu.

3. **Sumator (Summation):** Sumator agreguje ważone wejścia, generując ważoną sumę. Suma ta jest następnie przekazywana do funkcji aktywacji.

4. **Funkcja Aktywacji (Activation Function):** Funkcja aktywacji decyduje o tym, czy neuron ma zostać aktywowany (wygenerować wyjście) na podstawie sumy ważonych wejść. Funkcja ta wprowadza nieliniowość do modelu, co umożliwia sieci neuronowej modelowanie bardziej skomplikowanych zależności.

5. **Prog (Bias):** Prog (lub bias) jest dodawany do sumy ważonej przed przekazaniem jej do funkcji aktywacji. Prog pozwala na regulowanie, kiedy neuron powinien być aktywowany.

6. **Wyjście (Output):** Wynik działania funkcji aktywacji jest wyjściem neuronu, które może być przekazywane do innych neuronów jako wejścia.

### Wykorzystanie w Sieciach Neuronowych:

Sieć neuronowa składa się z wielu takich neuronów połączonych ze sobą w warstwach. Podstawowe typy warstw to:

1. **Warstwa Wejściowa (Input Layer):** Neurony tej warstwy odbierają dane wejściowe, np. cechy obrazu w przypadku problemów klasyfikacji obrazów.

2. **Warstwy Ukryte (Hidden Layers):** Neurony w warstwach ukrytych przetwarzają dane i uczą się reprezentacji cech danych wejściowych. Sieci z jedną lub więcej warstwami ukrytymi są nazywane głębokimi sieciami neuronowymi.

3. **Warstwa Wyjściowa (Output Layer):** Neurony tej warstwy generują wynik końcowy lub prognozę. W zależności od zadania, funkcja aktywacji i liczba neuronów w warstwie wyjściowej mogą się różnić.

### Proces Uczenia:

Proces uczenia sieci neuronowej polega na dostosowywaniu wag i progów w neuronach, aby minimalizować błąd prognozy w porównaniu z rzeczywistymi danymi wyjściowymi. Popularną techniką uczenia jest algorytm wstecznej propagacji błędu (backpropagation), który wykorzystuje różniczkowanie funkcji straty względem wag do aktualizacji parametrów sieci.

### Popularne Funkcje Aktywacji:

1. **Sigmoid:** $\sigma(x) = \frac{1}{1 + e^{-x}}$
2. **ReLU (Rectified Linear Unit):** $f(x) = \max(0, x)$
3. **Tanh:** $\tanh(x) = \frac{e^{2x} - 1}{e^{2x} + 1}$
4. **Softmax (dla warstwy wyjściowej):** $\text{softmax}(x)_i = \frac{e^{x_i}}{\sum_j e^{x_j}}$

Sieci neuronowe są wykorzystywane w różnych dziedzinach, takich jak rozpoznawanie obrazu, przetwarzanie języka naturalnego, rozpoznawanie mowy, gry komputerowe, predykcje finansowe itp. Dzięki zdolności do uczenia się hierarchii cech i abstrakcji, sieci neuronowe są efektywnym narzędziem w dziedzinie sztucznej inteligencji.