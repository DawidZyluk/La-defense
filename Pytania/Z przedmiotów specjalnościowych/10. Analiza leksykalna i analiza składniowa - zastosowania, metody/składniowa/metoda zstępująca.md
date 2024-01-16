# Metoda zstępująca

Metoda zstępująca (ang. Top-Down Parsing) to technika analizy składniowej (parsing), która zaczyna od najwyższego nieterminala w gramatyce i stara się przekształcić go w strumień terminali, stosując reguły produkcji gramatyki. Jest to jedna z dwóch głównych strategii analizy składniowej, drugą jest metoda wstępująca (Bottom-Up Parsing).

### Kroki Metody Zstępującej:

1. **Rozpoczęcie od Nieterminala Początkowego:**
   - Analiza zaczyna się od nieterminala początkowego gramatyki. Nieterminal ten reprezentuje całą strukturę gramatyczną, którą chcemy przeanalizować.

2. **Próba Dopasowania do Produkcji:**
   - Metoda zstępująca stara się dopasować strumień terminali do produkcji nieterminala początkowego, korzystając z reguł gramatycznych.

3. **Rekurencyjne Rozkładanie na Podproblemy:**
   - Gdy analiza napotyka na nieterminal w produkcji, proces rekurencyjnie podąża za regułami produkcji tego nieterminala, próbując dopasować kolejne elementy.

4. **Zawracanie w Przypadku Błędu lub Ukończenia:**
   - W przypadku, gdy analiza osiągnie koniec strumienia terminali i poprawnie dopasuje wszystkie elementy, proces kończy się sukcesem. W przypadku błędu, analiza zawraca do punktu poprzedzającego błąd.

### Przykład:

<p align="center">
  A = B + C * 2 ; D = 1
</p>

<div style="display: flex; ">
<p > 
  <img src="parse_tree.png" style="max-height: 100%;"/>
</p>
&nbsp;
<p > 
  <img src="top_down.png" style="max-height: 100%"/>
</p>
</div>

<p align="center">
  <b>Top-down Parsing</b><a href="https://en.wikipedia.org/wiki/Top-down_parsing"><sup>[1]</sup></a>
</p>

Metoda zstępująca jest stosowana w parserach rekurencyjnych zstępujących, które mogą być łatwo zdefiniowane za pomocą gramatyki w formie BNF (Backus-Naur Form). Jej zrozumienie i implementacja są kluczowe dla procesu analizy składniowej w kompilatorach.