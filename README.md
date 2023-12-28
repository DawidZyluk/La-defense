# Witamy w La Défense

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
