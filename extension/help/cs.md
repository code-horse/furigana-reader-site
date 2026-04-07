---
layout: bare
title: Furigana Reader — Uživatelská příručka
lang: cs
---

# Furigana Reader — Uživatelská příručka

> Verze: v1.4.0

## Úvod

Furigana Reader je rozšíření prohlížeče pro studenty japonštiny. Běží na morfologickém analyzátoru WASM (Lindera + IPAdic) s zálohou v JavaScriptu a přesně přidává furiganu (čtení nad znaky) ke kanji na webových stránkách i v PDF. Obsahuje také vestavěný japonský slovník, převod textu na řeč a překlad — usnadňuje učení japonské výslovnosti.

---

## Hlavní funkce

- **Režim furigany pro celou stránku** — Jedním kliknutím furigana ke všem kanji na stránce
- **Slovník při najetí** — Najetím na anotované znaky uvidíte definice z JMdict (180 000+ záznamů), čtení, odznaky úrovně JLPT (N5–N1) a tlačítka výslovnosti; volba režimu Slovník / Čtení / Vypnuto
- **Čtečka PDF** — Vestavěná čtečka PDF s furiganou, slovníkem, řečí a překladem; podpora přetažení souboru, načtení z URL a automatická detekce PDF s chytrým přesměrováním
- **Tři styly furigany** — Hiragana, katakana nebo rómadži
- **Rozdělení okurigany** — Přesně odděluje okurigana (送り仮名) od kmene kanji
- **Podpora jukujikun** — Správná čtení u víceznakových spojení se zvláštním čtením (熟字訓)
- **Převod textu na řeč** — Kliknutím na reproduktor uslyšíte výslovnost
- **Řeč výběru s karaoke efektem** — Vyberte libovolný japonský text; u výběru se zobrazí kompaktní panel s tlačítky mluvení a překladu; při čtení se slova nebo znaky v reálném čase zvýrazňují (karaoke) v souladu s audiem
- **Překlad výběru** — Vyberte text, v panelu klepněte na překlad; okamžitý překlad přes Bing nebo Google Translate v bublině pod panelem
- **Klávesové zkratky** — Rychlý přístup k hlavním funkcím přes nastavitelné zkratky
- **Vícejazyčné rozhraní** — 38 jazyků rozhraní

---

## Jak používat

### Krok 1: Instalace rozšíření

Nainstalujte **Furigana Reader** z [Chrome Web Store](https://chromewebstore.google.com/), nebo jej načtěte lokálně v režimu vývojáře.

### Krok 2: Otevřete libovolnou stránku

Navštivte stránku s japonským obsahem.

### Krok 3: Zapněte furiganu

Klikněte na ikonu rozšíření na panelu nástrojů. Zapněte „Povolit furiganu“, pak „Furigana pro celou stránku“, aby se anotovala všechna kanji. Můžete také použít plovoucí tlačítko vpravo dole.

### Krok 4: Prohlížení furigany

Najetím na znaky uvidíte nápovědy s čtením a definicemi ze slovníku. Kliknutím na reproduktor uslyšíte výslovnost.

### Krok 5: Mluvení a překlad výběru

Myší vyberte japonský text. U výběru se zobrazí kompaktní panel se dvěma tlačítky:
- **🔊 Mluvit** — Přečte vybraný text nahlas s karaoke zvýrazněním
- **🌐 Přeložit** — Zobrazí bublinu s překladem pod panelem

Můžete také kliknout pravým tlačítkem a zvolit „Furigana Reader > Přečíst výběr nahlas“ nebo „Furigana Reader > Přeložit výběr“.

> **Tip:** Kliknutím na ikonu rozšíření otevřete nastavení a upravíte styl furigany, režim najetí, rychlost řeči, překladový engine a další.

---

## Slovník při najetí

Rozšíření obsahuje vestavěný japonský slovník na bázi JMdict (více než 180 000 záznamů). V nastavení si můžete zvolit režim najetí:

| Režim | Chování |
|-------|---------|
| **Slovník** | Najetí zobrazí čtení + definici + úroveň JLPT + tlačítko výslovnosti |
| **Čtení** | Najetí zobrazí čtení + tlačítko výslovnosti (bez definic) |
| **Vypnuto** | Žádný efekt při najetí |

V režimu **Slovník** nápověda obsahuje:
- Slovo a jeho čtení (furigana)
- Tlačítko výslovnosti (kliknutím přehrát)
- Japonské definice z JMdict
- Odznak úrovně JLPT (N5–N1), pokud je k dispozici

> **Tip:** Data slovníku se načítají podle potřeby, když je zapnutý režim Slovník, a uvolní se při přepnutí na jiné režimy kvůli úspoře paměti.

---

## Čtečka PDF

Furigana Reader obsahuje vestavěnou čtečku PDF, kde můžete číst PDF s furiganou, slovníkem, řečí a překladem — stejné funkce jako na webu, nyní i pro PDF.

### Otevření PDF

**Způsob 1: Z vyskakovacího okna**  
Klikněte na ikonu rozšíření a pak na „Otevřít čtečku PDF“. Přetáhněte soubor PDF nebo klikněte na „Vybrat soubor“. Můžete také vložit URL PDF.

**Způsob 2: Kontextová nabídka**  
Klikněte pravým tlačítkem na odkaz `.pdf` na stránce a zvolte „Otevřít PDF ve Furigana Reader“.

**Způsob 3: Automatická detekce**  
Když je v nastavení zapnutá „Chytrá detekce PDF“, rozšíření automaticky přesměruje URL končící na `.pdf` do vestavěné čtečky. Pokud se PDF nepřesměruje (např. vestavěný prohlížeč Chrome), uvidíte upozornění a výzvu k otevření ve Furigana Reader.

### Funkce čtečky PDF

- **Furigana** — Všechny funkce furigany na textu PDF včetně režimu celé stránky a nápověd
- **Pět režimů furigany** — Hiragana, katakana, rómadži, pouze najetí a vypnuto
- **Slovník kliknutím** — Kliknutím na slovo zobrazíte definici z JMdict (v PDF se místo najetí používá kliknutí pro klidnější čtení)
- **Panel výběru** — Vybraný text: mluvení, překlad nebo kopírování
- **Postranní panel** — Obsah (outline) a náhledy stránek
- **Hledání** — Fulltextové hledání v PDF
- **Motivy** — Tmavý, světlý a sepia
- **Přiblížení** — Více úrovní zoomu včetně furigany přizpůsobené zoomu
- **Klávesové zkratky** — Šipky pro navigaci, +/- pro zoom, Ctrl/Cmd+F pro hledání

---

## Řeč výběru a karaoke

Funkce řeči výběru umožní vybrat libovolný japonský text a přečíst ho jedním kliknutím — vhodné pro výslovnost vět a čtení.

**Způsob 1: Panel výběru**  
Vyberte japonský text. U výběru se zobrazí panel s tlačítky 🔊 mluvení a 🌐 překladu. Kliknutím na mluvení se přehraje čtení; během čtení se slova nebo znaky v reálném čase zvýrazňují (karaoke).

**Způsob 2: Nabídka pravým tlačítkem**  
Po výběru japonského textu klikněte pravým tlačítkem a zvolte „Furigana Reader > Přečíst výběr nahlas“.

**Způsob 3: Klávesová zkratka**  
Vyberte text a stiskněte `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) pro mluvení.

> **Tip:** Karaoke zvýraznění funguje nejlépe, pokud prohlížeč podporuje události hranic slov u TTS. Jinak rozšíření použije časovanou náhradu pro plynulé zvýraznění.

---

## Překlad

Vyberte libovolný text na stránce a použijte překlad pro okamžitý výsledek.

**Způsob 1: Panel výběru**  
Vyberte text a klikněte v panelu na 🌐 překlad. Pod panelem se zobrazí bublina s výsledkem a tlačítkem kopírovat.

**Způsob 2: Nabídka pravým tlačítkem**  
Vyberte text, pravé tlačítko a „Furigana Reader > Přeložit výběr“.

**Způsob 3: Klávesová zkratka**  
Vyberte text a stiskněte `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) pro překlad.

**Překladové enginy:**
- **Bing Translate** (výchozí) — Microsoft Translator
- **Google Translate** — Google

Oba enginy podporují **108 cílových jazyků**.

Engine a cílový jazyk změníte v nastavení rozšíření. Cílový jazyk se automaticky odvodí z jazyka prohlížeče.

> **Tip:** Kliknutím mimo panel nebo bublinu je zavřete.

---

## Klávesové zkratky

| Zkratka | Mac | Akce |
|---------|-----|------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Zapnout/vypnout furiganu |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Přečíst vybraný text |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Přeložit vybraný text |

> **Tip:** Zkratky si upravíte v Chrome na `chrome://extensions/shortcuts`.

---

## Průvodce nastavením

| Nastavení | Popis |
|-----------|--------|
| **Povolit furiganu** | Hlavní přepínač funkce furigany |
| **Furigana pro celou stránku** | Furigana u všech kanji (může ovlivnit rozvržení stránky) |
| **Režim najetí** | Chování při najetí: Slovník (čtení + definice + JLPT + zvuk), Čtení (čtení + zvuk) nebo Vypnuto |
| **Styl furigany** | Hiragana, katakana nebo rómadži |
| **Rychlost řeči** | Rychlost čtení vět |
| **Překladový engine** | Bing Translate nebo Google Translate |
| **Cílový jazyk** | Jazyk překladu (automaticky z jazyka prohlížeče) |
| **Chytrá detekce PDF** | Automatické přesměrování URL PDF do vestavěné čtečky a upozornění při detekci PDF |

---

## Časté dotazy

**Ot.: Proč to na některých stránkách nefunguje?**  
Odp.: Z bezpečnostních důvodů nemohou rozšíření běžet na speciálních stránkách jako `chrome://`, nastavení prohlížeče nebo Chrome Web Store.

**Ot.: Co když je furigana nepřesná?**  
Odp.: U vzácných slov nebo zvláštních čtení (熟字訓) mohou být chyby. Stále vylepšujeme; napište konkrétní případy.

**Ot.: Žádný zvuk u TTS?**  
Odp.: Zkontrolujte hlasitost systému a nainstalované japonské hlasy. Podpora se liší podle prohlížeče a OS.

**Ot.: Režim celé stránky mění rozvržení?**  
Odp.: Furigana potřebuje místo a může změnit vzhled stránky. Pokud to vadí, vypněte celostránkový režim a používejte nápovědy při najetí.

**Ot.: Překlad nefunguje?**  
Odp.: Překlad vyžaduje internet. Pokud selže Bing, zkuste v nastavení Google Translate. Některé sítě mohou služby blokovat.

**Ot.: Jak otevřít PDF ve Furigana Reader?**  
Odp.: Vyskakovací okno → „Otevřít čtečku PDF“, pravé tlačítko na odkaz PDF → „Otevřít PDF ve Furigana Reader“, nebo zapněte „Chytrou detekci PDF“ pro automatické přesměrování.

**Ot.: Zapnutá chytrá detekce PDF, ale některá PDF se nepřesměrují?**  
Odp.: Automatické přesměrování platí pro URL končící na `.pdf`. U PDF bez přípony nebo ve vestavěném prohlížeči Chrome uvidíte oznámení a odznak s výzvou otevřít ve Furigana Reader.

**Ot.: Jde používat slovník offline?**  
Odp.: Ano. Data JMdict (180 000+ záznamů) jsou plně v rozšíření. Všechna vyhledávání probíhají lokálně bez sítě.

---

## Související odkazy

- [Zásady ochrany osobních údajů](../privacy-policy)
- [Podpora a zpětná vazba](../support)

---
