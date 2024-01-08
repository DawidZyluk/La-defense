# Wyrażenia regularne 

Wyrażenia regularne (ang. regular expressions lub regex) to sekwencje znaków definiujące wzorce tekstowe. Służą do przeszukiwania, manipulowania i analizowania tekstu, a także do dopasowywania wzorców w ciągach znaków. Wyrażenia regularne są potężnym narzędziem, używanym w różnych dziedzinach informatyki, takich jak przetwarzanie tekstów, analiza leksykalna, czy filtrowanie danych.

Oto podstawowe elementy i składnie wyrażeń regularnych:

1. **Znak Literału:**
   - **Przykład:** `a`, `b`, `1`, `@`
   - **Opis:** Znak literału dopasowuje sam siebie. Na przykład, wyrażenie `a` dopasuje pojedynczą literę `a` w tekście.

2. **Klasy Znaków:**
   - **Przykład:** `[aeiou]`, `[0-9]`, `[^a-z]`
   - **Opis:** Klasy znaków pozwalają na dopasowanie jednego spośród zestawu znaków. `[aeiou]` dopasuje dowolną samogłoskę, a `[^a-z]` dopasuje dowolny znak, który nie jest małą literą.

3. **Kwantyfikatory:**
   - **Przykład:** `*`, `+`, `?`, `{n}`, `{n,}`, `{n,m}`
   - **Opis:** Określają liczbę powtórzeń poprzedzającego elementu. Na przykład, `a*` dopasuje ciąg zer lub więcej liter `a`.

4. **Metaznaki:**
   - **Przykład:** `.`, `^`, `$`, `\`
   - **Opis:** Metaznaki mają specjalne znaczenie. Na przykład, `.` dopasuje dowolny pojedynczy znak, `^` oznacza początek linii, a `$` koniec linii.

5. **Grupowanie i Znaki Alternatywy:**
   - **Przykład:** `(abc)`, `a|b`
   - **Opis:** Grupowanie umożliwia łączenie elementów w jeden blok. `(abc)` dopasuje dokładnie sekwencję `abc`. Znaki alternatywy `a|b` dopasują `a` lub `b`.

6. **Anchors:**
   - **Przykład:** `\b`, `\B`
   - **Opis:** `\b` oznacza granicę słowa, a `\B` granicę nie-słowa. Na przykład, `\bword\b` dopasuje słowo "word", ale nie "password".

7. **Inne Skróty:**
   - **Przykład:** `\d`, `\w`, `\s`
   - **Opis:** Skróty do dopasowywania cyfr (`\d`), znaków słowa (`\w`), oraz białych znaków (`\s`).

8. **Modyfikatory:**
   - **Przykład:** `i`, `g`, `m`
   - **Opis:** Modyfikatory zmieniają sposób dopasowywania, na przykład `i` sprawia, że dopasowanie jest nieczułe na wielkość liter.

### Przykłady:

1. Wyrażenie regularne dla dopasowania adresu email:
   ```regex
   ^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$
   ```

2. Wyrażenie regularne dla dopasowania liczby całkowitej:
   ```regex
   ^[0-9]+$
   ```

Wyrażenia regularne są potężnym narzędziem, ale ich składnia może być skomplikowana. Korzystając z różnych składników, można tworzyć bardzo precyzyjne wzorce dopasowywania dla różnych potrzeb analizy tekstu.