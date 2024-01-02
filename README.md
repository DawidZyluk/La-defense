# Witamy w La Défense!
![Alt text](assets/image.png)

> "Obrona jest sztuką,\
> a sztuka nigdy nie jest łatwa."\
> ~ Sun Tzu

## Before you start

Polecane rozszerzenia do Visual Studio Code:

- **Markdown All in One**: Zestaw narzędzi do pisania w jezyku Markdown
- **LaTeX Workshop**: Rozszerzenie wspomagające pisanie wzorów matematycznych w języku LaTeX
- **Markdown PDF**: Opcjonalne rozszerzenie umożliwiające eksport plików Markdown do PDF

Markdown cheat sheet:  https://www.markdownguide.org/cheat-sheet/

## Struktura projektu

Struktura projektu wraz z omówieniem poszczególnych elementów:

```
├── assets/                                    # Katalog zawierający zasoby
├── Pytania/                                   # Katalog zawierający pytania
│  ├── Z przedmiotów kierunkowych/             # sic erat scriptum
│  │  ├── 1. Kompilacja, interpretacja.../     # Folder danego pytania
│  │  │  ├── index.md                          # plik zawierający odpowiedź
│  │  │  ├── kompilacja.md                     # plik wyjaśniający zagadnienie  
│  │  │  ├── interpretacja.md                  # plik wyjaśniający zagadnienie
│  ├── Z przedmiotów specjalnościowych/        # sic erat scriptum
│  │  ├── ...
```
 
- **assets**: Zdjęcia, schematy, rysunki poglądowe oraz wszystkie inne pliki umieszczane w odpowiedzach na pytania lub w wyjaśnieniu zagadnień powinny znajdować się w katalogu odpowiadającym danemu pytaniu. Jeżeli jednak dany plik występuję w wielu odpowiedziach lub nie jest bezpośrednio związany z danym pytaniem należy umieścić go w folderze assets

- **Pytania**: Katalog zawierający pytania z przedmiotów kierunkowych oraz specjalnościowych znajdujące się w odpowiednuch folderach. Każde pytanie posiada swój własny katalog zawierający wyczerpującą odpowiedź na dane pytanie (*plik index.md*) oraz możliwie przydatne wyjaśnienia zagadnień związanych z danym pytaniem.

## Jak dodawać i edytować materaiały

**Poradnik video**: https://www.youtube.com/watch?v=jRLGobWwA3Y

### Krok 1: Sklonuj Repozytorium

Rozpocznij od sklonowania repozytorium. Użyj komendy:

```bash
git clone https://github.com/DawidZyluk/La-defense.git
```

### Krok 2: Utwórz i Przełącz się na Nowy Branch


Utwórz nowy branch, aby wprowadzić swoje zmiany, i przełącz się na niego:

```bash
git checkout -b nazwa-nowego-brancha
```

### Krok 3: Wprowadź Zmiany

Dokonaj zmian w kodzie, dodaj nowe pliki lub wprowadź modyfikacje zgodnie z Twoimi zamierzeniami.

### Krok 4: Zatwierdź Zmiany

Dodaj zmienione pliki do indeksu i zatwierdź zmiany lokalnie:

```bash
git add .
git commit -m "Opis zmian"
```

### Krok 5: Pobierz Najnowszą Wersję z Głównego Brancha

Upewnij się, że masz najnowszą wersję kodu z głównego brancha:

```bash
git checkout main
git pull origin main
```

### Krok 6: Wprowadź Zmiany na Główny Branch

Przełącz się z powrotem na swój branch i scal zmiany z głównym branchem:

```bash
git checkout nazwa-nowego-brancha
git merge main
```

### Krok 7: Rozwiąż Konflikty (Jeśli Wystąpią)

W razie konfliktów, rozwiąż je lokalnie i kontynuuj proces scalania.

### Krok 8: Wypchnij Zmiany na GitHub

Wypchnij swoje zmiany na GitHub na swój branch:

```bash
git push origin nazwa-nowego-brancha
```

### Krok 9: Utwórz Pull Request

Przejdź do repozytorium na GitHubie i kliknij "Compare & pull request". Następnie opisz swoje zmiany i utwórz Pull Request.

### Krok 10: Dyskusja i Akceptacja

Oczekuj na recenzję i dyskusję dotyczącą Twoich zmian. Po zatwierdzeniu, Pull Request zostanie połączony z głównym branchem.
