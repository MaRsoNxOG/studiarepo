# Źródła Dokumentacji Technicznej Sphinx

## Cel

Repozytorium zawiera pliki źródłowe reStructuredText (RST) oraz konfigurację do wygenerowania dokumentacji technicznej przy użyciu narzędzia **Sphinx** (w ramach zadania laboratoryjnego na Politechnice Wrocławskiej).

## Zawartość Dokumentu

Wygenerowany dokument spełnia następujące wymagania:
* **Minimalna struktura:** Zawiera co najmniej trzy rozdziały (Rozdział 1, Rozdział 2, Rozdział 3).
* **Elementy:** Zostały w nim zaimplementowane:
    * Co najmniej jedna **ilustracja** (`chmura.jpg`).
    * Co najmniej jedna **tabela**.
    * Co najmniej jedna **lista**.
* **Objętość:** Tekst ma objętość kilku stron w wynikowym pliku PDF.

## Struktura Repozytorium

* **`source/`**: Główny katalog zawierający pliki źródłowe `.rst` (w tym `index.rst`, `rozdzial1.rst`, `rozdzial2.rst`, `rozdzial3.rst`) oraz zasoby graficzne.
* **`.gitignore`**: Plik wykluczający pliki wynikowe (`_build`, PDF, tar.gz) z systemu kontroli wersji.

## Jak skompilować dokumentację (na serwerze Linux):

1.  Pobierz repozytorium.
2.  Przejdź do katalogu głównego (zawierającego `Makefile`).
3.  Użyj komend budowania:
    * `make html` (do generowania statycznej strony WWW)
    * `make latexpdf` (do generowania pliku PDF)
