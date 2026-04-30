# Gra Semestralna - VIEW

![Game Preview](https://img.shields.io/badge/Status-Complete-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

**VIEW** to minimalistyczna gra logiczna inspirowana serią "That Level Again", stworzona jako projekt semestralny. Każdy poziom wygląda podobnie, ale wymaga innego, często zaskakującego rozwiązania.

## 🎮 Opis Gry

Gra składa się z 10 poziomów, z których każdy prezentuje te same podstawowe elementy (drzwi, przycisk), ale wymaga odmiennego podejścia do rozwiązania zagadki. Gracz musi myśleć kreatywnie i testować różne interakcje, aby przejść dalej.

## ✨ Funkcje

- **10 unikalnych poziomów** - każdy z inną mechaniką rozwiązania
- **Minimalistyczny design** - retro-inspirowana estetyka z nowoczesnym wykończeniem
- **Płynne animacje** - przyjemne dla oka przejścia i efekty
- **System progressu** - śledzenie czasu i ukończonych poziomów
- **Intuicyjny interfejs** - czysty i responsywny UI
- **Wskazówki** - subtelne podpowiedzi dla każdego poziomu

## 🎯 Poziomy i Rozwiązania

Każdy poziom zawiera inną zagadkę:

1. **Poziom 1** - Proste kliknięcie przycisku
2. **Poziom 2** - Wielokrotne pukanie w drzwi (5x)
3. **Poziom 3** - Znalezienie ukrytego przycisku
4. **Poziom 4** - Sekwencja kolorów (czerwony → zielony → niebieski)
5. **Poziom 5** - Wprowadzenie hasła tekstowego
6. **Poziom 6** - Cierpliwość - odliczanie czasu
7. **Poziom 7** - Ruch myszką (symulacja potrząsania)
8. **Poziom 8** - Odwrotna psychologia (nie klikaj przycisku!)
9. **Poziom 9** - Szybkie klikanie (10 razy w 3 sekundy)
10. **Poziom 10** - Kombinacja kilku mechanik

## 🚀 Jak Uruchomić

### Metoda 1: Bezpośrednio w przeglądarce
1. Pobierz plik `view.html`
2. Otwórz go w dowolnej nowoczesnej przeglądarce
3. Graj!

### Metoda 2: Lokalny serwer
```bash
# Jeśli masz zainstalowany Python
python -m http.server 8000
# Lub
python3 -m http.server 8000

# Następnie otwórz przeglądarkę pod adresem:
# http://localhost:8000/view.html
```

### Metoda 3: GitHub Pages
1. Stwórz repozytorium na GitHubie
2. Prześlij plik `view.html`
3. Włącz GitHub Pages w ustawieniach repozytorium
4. Twoja gra będzie dostępna pod adresem: `https://[username].github.io/[repo-name]/view.html`

## 🛠️ Technologie

- **HTML5** - struktura strony
- **CSS3** - stylizacja, animacje i efekty
- **JavaScript (Vanilla)** - logika gry i interakcje
- **Google Fonts** - czcionki (Space Mono, Courier Prime)

## 📋 Wymagania

- Dowolna nowoczesna przeglądarka (Chrome, Firefox, Safari, Edge)
- JavaScript musi być włączony
- Zalecana rozdzielczość: minimum 400px szerokości

## 🎨 Design

Gra wykorzystuje:
- **Paleta kolorów**: Kremowe tło (#f4f1e8) z akcentami w odcieniach zieleni (#2d5a4a)
- **Typografia**: Space Mono (UI) + Courier Prime (tytuł)
- **Styl**: Minimalistyczny, retro-inspirowany z nowoczesnym wykończeniem
- **Animacje**: Płynne przejścia, efekty hover i feedback wizualny

## 📱 Responsywność

Gra jest w pełni responsywna i dostosowuje się do różnych rozmiarów ekranu:
- Desktop (500px+ szerokości)
- Tablet (400-500px)
- Mobile (do 400px)

## 🎓 Informacje o Projekcie

**Typ projektu**: Gra Semestralna  
**Nazwa**: VIEW  
**Gatunek**: Logiczna/Puzzle  
**Inspiracja**: That Level Again (TLA)  
**Język**: Polski (UI) + Angielski (kod)

## 📝 Struktura Kodu

```
view.html
├── HTML - Struktura gry
├── CSS - Style i animacje
│   ├── Zmienne CSS (kolory, cienie)
│   ├── Animacje (@keyframes)
│   └── Responsywność
└── JavaScript - Logika gry
    ├── System poziomów (levels array)
    ├── Zarządzanie stanem gry
    ├── Event listeners
    └── Funkcje pomocnicze
```

## 🔧 Możliwe Rozszerzenia

- Dodanie większej liczby poziomów
- System zapisywania postępów (localStorage)
- Ranking najlepszych czasów
- Tryb trudności (łatwy/trudny)
- Dźwięki i muzyka
- Wielojęzyczność
- Mobilne gesty (przesuwanie, pinch, etc.)
- Własny edytor poziomów

## 🐛 Znane Problemy

Obecnie brak znanych problemów. Jeśli znajdziesz bug, zgłoś go w sekcji Issues.

## 📄 Licencja

Ten projekt został stworzony do celów edukacyjnych jako projekt semestralny. Możesz go dowolnie modyfikować i używać do nauki.

## 👤 Autor

Projekt semestralny - VIEW

## 🙏 Podziękowania

- Inspiracja: That Level Again (IamTagir)
- Czcionki: Google Fonts
- Design: Custom minimalist aesthetic

---

**Miłej zabawy i powodzenia w rozwiązywaniu zagadek! 🎮**

### Quick Start
```bash
# Sklonuj repo
git clone [your-repo-url]

# Otwórz plik
open view.html  # macOS
start view.html # Windows
xdg-open view.html # Linux
```
