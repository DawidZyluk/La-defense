# Wyrażenie lambda na przykładzie języka Java lub Python

**Wyrażenie lambda w języku Java:**

Wyrażenia lambda w Javie wprowadzono w Java 8 i stanowią skróconą i bardziej zwięzłą formę interfejsów funkcyjnych. Oto przykład wyrażenia lambda w Javie:

```java
import java.util.ArrayList;

public class Main {
  public static void main(String[] args) {
    ArrayList<Integer> numbers = new ArrayList<Integer>();
    numbers.add(5);
    numbers.add(9);
    numbers.add(8);
    numbers.add(1);
    numbers.forEach( (n) -> { System.out.println(n); } );
  }
}
```

W powyższym przykładzie, `(a, b) -> a + b` to wyrażenie lambda, które implementuje metodę z interfejsu funkcyjnego `Dodawanie`. Wyrażenia lambda w Javie pozwalają zastąpić długie formy klas anonimowych przy implementacji interfejsów funkcyjnych.

**Wyrażenie lambda w języku Python:**

Python również obsługuje wyrażenia lambda, które są używane do tworzenia małych anonimowych funkcji. Oto przykład:

```python
# Przykładowe wyrażenie lambda
dodaj = lambda a, b: a + b

# Wywołanie funkcji przy użyciu wyrażenia lambda
wynik = dodaj(3, 5)
print("Wynik dodawania:", wynik)
```

W tym przypadku `lambda a, b: a + b` definiuje anonimową funkcję, która przyjmuje dwa argumenty (`a` i `b`) i zwraca ich sumę. Wyrażenia lambda w Pythonie są przydatne do szybkiego definiowania krótkich funkcji bez konieczności nadawania im nazwy.