# Trasa 4:30

Gra przeglądarkowa o kierowcy ciężarówki: przejedź limit czasu jazdy 4:30 bez stłuczki, zdążaj z dostawami, tankuj i omijaj fotoradary.
Działa jako aplikacja PWA (ikona na ekranie głównym, pełny ekran, tryb offline).

## Sterowanie

- **Telefon:** dotknij lewej albo prawej połowy ekranu.
- **Komputer:** strzałki ← → albo A / D, Enter uruchamia jazdę.

## Publikacja na GitHub Pages

1. Utwórz nowe repozytorium na GitHubie (np. `trasa-430`) i wgraj **wszystkie pliki z tego folderu** (`index.html`, `manifest.webmanifest`, `sw.js`, folder `icons/`).
2. W repozytorium: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, gałąź `main`, folder `/ (root)` → **Save**.
3. Po minucie gra będzie pod adresem `https://<twoj-login>.github.io/trasa-430/`.

## Instalacja na iPhonie

1. Otwórz adres gry w **Safari**.
2. Przycisk **Udostępnij** → **Do ekranu początkowego** → **Dodaj**.
3. Uruchamiaj grę z ikony – otworzy się na pełnym ekranie i będzie działać także bez internetu.

## Aktualizacja gry

Po zmianie plików podbij numer wersji w `sw.js` (np. `trasa430-v1` → `trasa430-v2`), żeby telefon pobrał nową wersję.
Postęp (saldo, rekordy, punkty karne) jest zapisany w telefonie i nie zginie przy aktualizacji.

## Pliki

| Plik | Opis |
| --- | --- |
| `index.html` | cała gra |
| `manifest.webmanifest` | opis aplikacji PWA (nazwa, kolory, ikony) |
| `sw.js` | service worker – tryb offline |
| `icons/` | ikona w SVG oraz PNG (180 dla iPhone'a, 192 i 512 dla Androida, 32 dla karty przeglądarki) |
| `LICENSE` | informacja o prawach autorskich (Wszelkie prawa zastrzeżone) |

## Prawa autorskie

© 2026 Maciej Ratajczak. Wszelkie prawa zastrzeżone.  
Kopiowanie, modyfikowanie, rozpowszechnianie lub użycie komercyjne bez zgody autora jest zabronione.

