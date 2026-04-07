---
layout: bare
title: Furigana Reader — Przewodnik użytkownika
lang: pl
---

# Furigana Reader — Przewodnik użytkownika

> Wersja: v1.4.1

## Wprowadzenie

Furigana Reader to rozszerzenie przeglądarki dla osób uczących się japońskiego. Dzięki morfologicznemu analizatorowi WASM (Lindera + IPAdic) z zapasowym silnikiem w JavaScript dokładnie dodaje furiganę (adnotacje odczytu) do znaków kanji na stronach internetowych i w plikach PDF. Zawiera też wbudowany słownik japoński, syntezę mowy (TTS) i tłumaczenie — ułatwiając naukę wymowy japońskiego.

---

## Główne funkcje

- **Tryb furigany na całą stronę** — Jednym kliknięciem dodaj furiganę do wszystkich kanji na stronie
- **Słownik po najechaniu** — Najedź na oznaczony znak, aby zobaczyć definicje z JMdict (ponad 180 tys. haseł), odczyty, oznaczenia poziomu JLPT (N5–N1) i przyciski wymowy; wybierz tryb Słownik, Odczyt lub Wyłączone
- **Czytnik PDF** — Wbudowany czytnik PDF z furiganą, słownikiem, mową i tłumaczeniem; obsługa przeciągnij i upuść, wczytywania z adresu URL oraz automatycznego wykrywania PDF z inteligentnym przekierowaniem
- **Trzy style odczytu** — Hiragana, katakana i romaji
- **Rozdzielanie okurigany** — Dokładnie oddziela okuriganę (送り仮名) od rdzenia kanji
- **Obsługa jukujikun** — Poprawne odczyty dla wieloznakowych związków ze specjalnym odczytem (熟字訓)
- **Synteza mowy (TTS)** — Kliknij przycisk głośnika, aby usłyszeć wymowę po japońsku
- **Mowa zaznaczenia z efektem karaoke** — Zaznacz dowolny tekst japoński; pojawi się kompaktowy pasek z przyciskami mowy i tłumaczenia; odtwarzanie z podświetlaniem słów lub znaków w czasie rzeczywistym (karaoke) zsynchronizowanym z dźwiękiem
- **Tłumaczenie zaznaczenia** — Zaznacz tekst i kliknij tłumaczenie na pasku, aby uzyskać natychmiastowy wynik przez Bing lub Google Translate w dymku inline
- **Skróty klawiszowe** — Szybki dostęp do głównych funkcji dzięki konfigurowalnym skrótom
- **Wielojęzyczny interfejs** — 38 języków interfejsu

---

## Jak korzystać

### Krok 1: Zainstaluj rozszerzenie

Zainstaluj **Furigana Reader** ze [sklepu Chrome Web Store](https://chromewebstore.google.com/) lub wczytaj lokalnie w trybie deweloperskim.

### Krok 2: Otwórz dowolną stronę

Wejdź na stronę z treścią po japońsku.

### Krok 3: Włącz furiganę

Kliknij ikonę rozszerzenia na pasku narzędzi. Włącz „Włącz furiganę”, potem „Furigana na całą stronę”, aby oznaczyć wszystkie kanji. Możesz też użyć pływającego przycisku w prawym dolnym rogu.

### Krok 4: Przeglądaj furiganę

Najedź na znaki, aby zobaczyć podpowiedzi z odczytem i definicjami ze słownika. Kliknij ikonę głośnika, aby usłyszeć wymowę.

### Krok 5: Mów i tłumacz zaznaczenie

Zaznacz tekst japoński myszą. Obok zaznaczenia pojawi się kompaktowy pasek z dwoma przyciskami:
- **🔊 Mów** — Czyta zaznaczenie na głos z podświetlaniem w stylu karaoke
- **🌐 Tłumacz** — Pokazuje dymek tłumaczenia pod paskiem

Możesz też kliknąć prawym przyciskiem i wybrać „Furigana Reader > Read aloud selection” lub „Furigana Reader > Translate Selection”.

> **Wskazówka:** Kliknij ikonę rozszerzenia, aby otworzyć ustawienia i dostosować styl furigany, tryb najechania, tempo mowy, silnik tłumaczenia i inne opcje.

---

## Słownik po najechaniu

Rozszerzenie zawiera wbudowany słownik japoński oparty na JMdict (ponad 180 000 haseł). W ustawieniach możesz wybrać tryb najechania:

| Tryb | Zachowanie |
|------|------------|
| **Dictionary** | Najechanie: odczyt + definicja + poziom JLPT + przycisk wymowy |
| **Reading** | Najechanie: odczyt + przycisk wymowy (bez definicji) |
| **Off** | Brak efektu po najechaniu |

W trybie **Dictionary** podpowiedź pokazuje:
- Słowo i jego odczyt (furigana)
- Przycisk wymowy (kliknij, aby usłyszeć)
- Definicje japońskie z JMdict
- Oznaczenie poziomu JLPT (N5–N1), jeśli jest dostępne

> **Wskazówka:** Dane słownika wczytywane są na żądanie, gdy włączony jest tryb Dictionary, a zwalniane przy przełączeniu na inne tryby, aby oszczędzać pamięć.

---

## Czytnik PDF

Furigana Reader ma wbudowany czytnik PDF z furiganą, słownikiem, mową i tłumaczeniem — te same funkcje co na stronach WWW, teraz także dla PDF.

### Otwieranie PDF

**Metoda 1: Z wyskakującego okna**  
Kliknij ikonę rozszerzenia, potem „Open PDF Reader”. Przeciągnij i upuść plik PDF lub kliknij „Choose File”, aby otworzyć lokalny plik. Możesz też wkleić adres URL PDF.

**Metoda 2: Menu kontekstowe**  
Kliknij prawym przyciskiem dowolny link `.pdf` i wybierz „Open PDF with Furigana Reader”.

**Metoda 3: Automatyczne wykrywanie**  
Gdy w ustawieniach włączone jest „PDF Smart Detection”, rozszerzenie automatycznie przekierowuje adresy URL kończące się na `.pdf` do wbudowanego czytnika. Gdy PDF zostanie wykryty, ale nie przekierowany (np. wbudowany podgląd Chrome), zobaczysz powiadomienia zachęcające do otwarcia w Furigana Reader.

### Funkcje czytnika PDF

- **Adnotacje furigany** — Wszystkie funkcje furigany działają na tekście PDF, w tym tryb całej strony i podpowiedzi
- **Pięć trybów furigany** — Hiragana, katakana, romaji, tylko najechanie i wyłączone
- **Słownik kliknięciem** — Kliknij słowo, aby zobaczyć definicję z JMdict (w PDF zamiast najechania używany jest klik dla spokojniejszego czytania)
- **Pasek zaznaczenia** — Zaznacz tekst, aby mówić, tłumaczyć lub kopiować
- **Panel boczny** — Spis treści i miniatury stron
- **Wyszukiwanie** — Pełnotekstowe wyszukiwanie w PDF
- **Motywy** — Ciemny, jasny i sepia
- **Powiększenie** — Wiele poziomów zoomu, w tym furigana dopasowana do powiększenia
- **Skróty klawiszowe** — Strzałki do nawigacji, +/- do zoomu, Ctrl/Cmd+F do wyszukiwania

---

## Mowa zaznaczenia i karaoke

Funkcja mowy zaznaczenia pozwala zaznaczyć dowolny tekst japoński i odsłuchać go jednym kliknięciem — wygodne przy nauce wymowy całych zdań.

**Metoda 1: Pasek zaznaczenia**  
Zaznacz tekst japoński. Pojawi się pasek z przyciskami 🔊 mów i 🌐 tłumacz. Kliknij mów. Podczas odtwarzania słowa lub znaki są podświetlane na bieżąco (karaoke).

**Metoda 2: Menu kontekstowe**  
Po zaznaczeniu tekstu kliknij prawym przyciskiem i wybierz „Furigana Reader > Read aloud selection”.

**Metoda 3: Skrót klawiszowy**  
Zaznacz tekst i naciśnij `Alt+Shift+S` (Mac: `Ctrl+Shift+S`), aby odtworzyć mowę.

> **Wskazówka:** Efekt karaoke działa najlepiej, gdy przeglądarka obsługuje zdarzenia granic słów TTS. W przeciwnym razie rozszerzenie używa zapasowego mechanizmu czasowego dla płynnego podświetlania.

---

## Tłumaczenie

Zaznacz dowolny tekst na stronie i użyj tłumaczenia, aby uzyskać natychmiastowy wynik.

**Metoda 1: Pasek zaznaczenia**  
Zaznacz tekst, potem kliknij 🌐 tłumacz na pasku. Poniżej pojawi się dymek z wynikiem i przyciskiem kopiowania.

**Metoda 2: Menu kontekstowe**  
Zaznacz tekst, kliknij prawym przyciskiem i wybierz „Furigana Reader > Translate Selection”.

**Metoda 3: Skrót klawiszowy**  
Zaznacz tekst i naciśnij `Alt+Shift+T` (Mac: `Ctrl+Shift+T`), aby przetłumaczyć.

**Silniki tłumaczenia:**
- **Bing Translate** (domyślnie) — Microsoft Translator
- **Google Translate** — Google

Oba silniki obsługują **108 języków docelowych**.

Silnik tłumaczenia i język docelowy zmienisz w ustawieniach rozszerzenia. Język docelowy jest domyślnie wykrywany z języka przeglądarki.

> **Wskazówka:** Kliknij poza paskiem lub dymkiem, aby je zamknąć.

---

## Skróty klawiszowe

| Skrót | Skrót na Macu | Działanie |
|-------|----------------|-----------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Włącz/wyłącz adnotacje furigany |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Odczytaj zaznaczony tekst |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Przetłumacz zaznaczony tekst |

> **Wskazówka:** Skróty możesz zmienić w Chrome pod adresem `chrome://extensions/shortcuts`.

---

## Przewodnik po ustawieniach

| Ustawienie | Opis |
|------------|------|
| **Enable Furigana** | Główny przełącznik włączający lub wyłączający furiganę |
| **Whole Page Furigana** | Gdy włączone, furigana dla wszystkich kanji (może wpłynąć na układ strony) |
| **Hover Mode** | Zachowanie po najechaniu: Dictionary (odczyt + definicje + JLPT + audio), Reading (odczyt + audio) lub Off |
| **Furigana Style** | Hiragana, katakana lub romaji |
| **Speech Rate** | Szybkość czytania zdań |
| **Translation Engine** | Bing Translate lub Google Translate |
| **Target Language** | Język docelowy tłumaczenia (automatycznie z języka przeglądarki) |
| **PDF Smart Detection** | Gdy włączone, automatyczne przekierowanie adresów PDF do wbudowanego czytnika i powiadomienia przy wykryciu PDF |

---

## FAQ

**P: Dlaczego nie działa na niektórych stronach?**  
O: Ze względów bezpieczeństwa rozszerzenia nie działają na stronach specjalnych, np. `chrome://`, ustawieniach przeglądarki ani w Chrome Web Store.

**P: Co jeśli furigana jest niedokładna?**  
O: Rzadkie słowa lub specjalne odczyty (熟字訓) mogą być błędne. Ciągle to ulepszamy. Prosimy o zgłaszanie konkretnych przypadków.

**P: Brak dźwięku z TTS?**  
O: Sprawdź głośność systemu i zainstalowane pakiety głosów japońskich. Obsługa mowy zależy od przeglądarki i systemu.

**P: Tryb całej strony psuje układ?**  
O: Furigana potrzebuje dodatkowego miejsca i może zmienić układ. Jeśli przeszkadza, wyłącz tryb całej strony i używaj podpowiedzi po najechaniu.

**P: Tłumaczenie nie działa?**  
O: Tłumaczenie wymaga internetu. Jeśli Bing zawiedzie, spróbuj Google w ustawieniach. Niektóre sieci mogą blokować usługi tłumaczenia.

**P: Jak otworzyć PDF w Furigana Reader?**  
O: Kliknij „Open PDF Reader” w wyskakującym oknie, kliknij prawym link PDF i wybierz „Open PDF with Furigana Reader”, albo włącz „PDF Smart Detection”, aby automatycznie przekierowywać adresy PDF.

**P: PDF Smart Detection jest włączone, ale niektóre PDF się nie przekierowują?**  
O: Automatyczne przekierowanie działa dla URL kończących się na `.pdf`. Dla PDF bez rozszerzenia w adresie lub w wbudowanym podglądzie Chrome pojawi się powiadomienie i znacznik zachęcający do otwarcia w Furigana Reader.

**P: Czy słownik działa offline?**  
O: Tak. Słownik JMdict (ponad 180 000 haseł) jest w pełni wbudowany w rozszerzenie. Wszystkie wyszukiwania są lokalne, bez połączenia sieciowego.

---

## Powiązane linki

- [Polityka prywatności](../privacy-policy)
- [Wsparcie i opinie](../support)

---
