---
layout: bare
title: Furigana Reader bővítmény - Felhasználói útmutató
lang: hu
---

# Furigana Reader - Felhasználói útmutató

> Verzió: v1.4.0

## Bevezetés

A Furigana Reader böngészőbővítmény japánt tanulóknak. WASM morfológiai elemzővel (Lindera + IPAdic) és JavaScript tartalékkal pontosan furigana (olvasási jelöléseket) ad a kanji karakterekhez weboldalakon és PDF-fájlokban. Beépített japán szótár, szövegfelolvasás (TTS) és fordítás is tartozik hozzá — a kiejtés könnyebb elsajátításához.

---

## Fő funkciók

- **Teljes oldalas furigana** — Egy kattintással furigana minden kanjihoz az oldalon
- **Lebegő szótár** — Vigye az egeret az annotált karakterekre: JMdict definíciók (180 000+ cím), olvasások, JLPT szintjelvények (N5–N1) és kiejtésgombok; válasszon Dictionary, Reading vagy Off módot
- **PDF-olvasó** — Beépített PDF-néző furiganával, szótárral, beszéddel és fordítással; húzd és ejtsd, URL-ből megnyitás, intelligens átirányítással kiegészített automatikus PDF-felismerés
- **Három olvasási stílus** — Hiragana, Katakana és Romaji
- **Okurigana szétválasztás** — Pontosan szétválasztja az okuriganát (送り仮名) a kanji tőtől
- **Jukujikun támogatás** — Helyes olvasások speciális olvasású többkanjis összetételeknél (熟字訓)
- **Szövegfelolvasás (TTS)** — Kattintson a hangszóró ikonra a japán kiejtéshez
- **Kijelölés felolvasása karaoke effekttel** — Jelöljön ki japán szöveget; megjelenik egy kompakt eszköztár beszéd- és fordítógombokkal; lejátszás közben szavak vagy karakterek valós időben kiemelődnek (karaoke), szinkronban a hanggal
- **Kijelölés fordítása** — Jelöljön ki szöveget, kattintson a fordításra az eszköztáron: azonnali Bing vagy Google Translate eredmény beágyazott buborékban
- **Billentyűparancsok** — Gyors hozzáférés a fő funkciókhoz testreszabható parancsokkal
- **Többnyelvű felület** — 38 felületi nyelv

---

## Használat

### 1. lépés: Telepítse a bővítményt

Telepítse a **Furigana Reader**-t a [Chrome Web Store](https://chromewebstore.google.com/)-ból, vagy töltse be helyben fejlesztői módban.

### 2. lépés: Nyisson meg bármilyen oldalt

Látogasson el egy japán tartalmú oldalra.

### 3. lépés: Kapcsolja be a furiganát

Kattintson a bővítmény ikonjára az eszköztáron. Kapcsolja be az „Enable Furigana”-t, majd a „Whole Page Furigana”-t az összes kanji annotálásához. Használhatja a jobb alsó lebegő gombot is.

### 4. lépés: Nézze a furiganát

Vigye az egeret a karakterekre az olvasások és szótári definíciók megjelenítéséhez. Kattintson a hangszóró ikonra a kiejtéshez.

### 5. lépés: Olvassa fel és fordítsa a kijelölést

Jelöljön ki japán szöveget. Megjelenik egy kompakt eszköztár két gombbal:
- **🔊 Speak** — Felolvassa a kijelölést karaoke-szerű kiemeléssel
- **🌐 Translate** — Beágyazott fordítási buborékot mutat az eszköztár alatt

Jobb klikkel is választhatja a „Furigana Reader > Read aloud selection” vagy „Furigana Reader > Translate Selection” menüt.

> **Tipp:** Kattintson a bővítmény ikonjára a beállításokhoz: furigana stílus, lebegő mód, beszédsebesség, fordítómotor stb.

---

## Lebegő szótár

A bővítmény beépített japán szótárat tartalmaz JMdict alapon (180 000+ cím). A beállításokban választhat lebegő módot:

| Mód | Viselkedés |
|-----|------------|
| **Dictionary** | Lebegés: olvasás + definíció + JLPT + kiejtésgomb |
| **Reading** | Lebegés: olvasás + kiejtésgomb (definíció nélkül) |
| **Off** | Nincs lebegő effekt |

**Dictionary** módban a buborék mutatja:
- A szót és olvasását (furigana)
- Kiejtésgombot (kattintásra hang)
- Japán definíciókat a JMdict-ből
- JLPT szintjelvényt (N5–N1), ha elérhető

> **Tipp:** A szótár adatai igény szerint töltődnek Dictionary módban, más módokra váltáskor felszabadulnak a memória takarékosságáért.

---

## PDF-olvasó

A Furigana Reader beépített PDF-olvasóval rendelkezik furiganával, szótárral, beszéddel és fordítással — ugyanazok a funkciók, mint weboldalakon, most PDF-re is.

### PDF megnyitása

**1. módszer: A felugró ablakból**  
Kattintson a bővítmény ikonjára, majd az „Open PDF Reader”-re. Húzza ide a PDF-et vagy kattintson a „Choose File”-ra helyi fájlhoz. Beilleszthet PDF URL-t is.

**2. módszer: Helyi menü**  
Jobb klikk egy `.pdf` linkre, majd „Open PDF with Furigana Reader”.

**3. módszer: Automatikus felismerés**  
Ha a beállításokban be van kapcsolva a „PDF Smart Detection”, a bővítmény automatikusan átirányítja a `.pdf`-re végződő URL-eket a beépített olvasóba. Ha a PDF felismerésre kerül, de nincs átirányítás (pl. Chrome beépített nézője), értesítések jelennek meg a Furigana Readerben való megnyitáshoz.

### PDF-olvasó funkciói

- **Furigana annotációk** — Minden furigana funkció PDF szövegen, beleértve a teljes oldal módot és a lebegő buborékokat
- **Öt furigana mód** — Hiragana, Katakana, Romaji, csak lebegés és ki
- **Kattintásos szótár** — Kattintson egy szóra a JMdict definícióért (PDF-ben a lebegés helyett kattintás a zavarmentes olvasáshoz)
- **Kijelölés eszköztár** — Jelöljön ki szöveget felolvasáshoz, fordításhoz vagy másoláshoz
- **Oldalsáv** — Tartalomjegyzék és oldal miniatűrök
- **Keresés** — Teljes szöveges keresés a PDF-ben
- **Témák** — Sötét, világos és szépia
- **Nagyítás** — Több nagyítási szint, beleértve a nagyításhoz igazodó furiganát is
- **Billentyűparancsok** — Nyilak navigációhoz, +/- nagyításhoz, Ctrl/Cmd+F kereséshez

---

## Kijelölés felolvasása és karaoke

A kijelölés felolvasása lehetővé teszi bármely japán szöveg kijelölését és egy kattintással történő lejátszását — mondatkiejtés és olvasásgyakorlás számára ideális.

**1. módszer: Kijelölés eszköztár**  
Jelöljön ki japán szöveget. Megjelenik az eszköztár 🔊 speak és 🌐 translate gombokkal. Kattintson a speak-re. Lejátszás közben szavak vagy karakterek valós időben kiemelődnek (karaoke).

**2. módszer: Helyi menü**  
Kijelölés után jobb klikk: „Furigana Reader > Read aloud selection”.

**3. módszer: Billentyűparancs**  
Jelöljön ki szöveget, majd nyomja meg az `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) billentyűket.

> **Tipp:** A karaoke legjobban akkor működik, ha a böngésző támogatja a TTS szóhatár eseményeket. Egyébként időzítés alapú tartalék kiemelés fut.

---

## Fordítás

Jelöljön ki bármilyen szöveget az oldalon, és használja a fordítást azonnali eredményhez.

**1. módszer: Kijelölés eszköztár**  
Jelöljön ki szöveget, majd kattintson a 🌐 translate gombra. Alatta megjelenik a fordítási buborék másológombbal.

**2. módszer: Helyi menü**  
Jelöljön ki szöveget, jobb klikk: „Furigana Reader > Translate Selection”.

**3. módszer: Billentyűparancs**  
Jelöljön ki szöveget, majd `Alt+Shift+T` (Mac: `Ctrl+Shift+T`).

**Fordítómotorok:**
- **Bing Translate** (alapértelmezett) — Microsoft Translator
- **Google Translate** — Google

Mindkettő **108 célnyelvet** támogat.

A motort és a célnyelvet a bővítmény beállításaiban változtathatja. A célnyelv általában a böngésző nyelvéből kerül felismerésre.

> **Tipp:** Kattintson az eszköztár vagy buborék mellé a bezáráshoz.

---

## Billentyűparancsok

| Parancs | Mac | Művelet |
|---------|-----|---------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Furigana annotációk ki/be |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Kijelölt szöveg felolvasása |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Kijelölt szöveg fordítása |

> **Tipp:** A parancsokat a Chrome-ban a `chrome://extensions/shortcuts` címen szabhatja testre.

---

## Beállítások útmutató

| Beállítás | Leírás |
|-----------|--------|
| **Enable Furigana** | Főkapcsoló a furigana funkcióhoz |
| **Whole Page Furigana** | Bekapcsolva minden kanjihoz furigana (befolyásolhatja az elrendezést) |
| **Hover Mode** | Lebegés viselkedése: Dictionary (olvasás + definíciók + JLPT + hang), Reading (olvasás + hang) vagy Off |
| **Furigana Style** | Hiragana, Katakana vagy Romaji |
| **Speech Rate** | Mondatfelolvasás sebessége |
| **Translation Engine** | Bing Translate vagy Google Translate |
| **Target Language** | Fordítás célnyelve (automatikus a böngésző nyelvéből) |
| **PDF Smart Detection** | Bekapcsolva automatikusan átirányítja a PDF URL-eket a beépített olvasóba, és értesít PDF felismeréskor |

---

## GYIK

**K: Miért nem működik egyes oldalakon?**  
V: Biztonsági okokból a bővítmények nem futnak speciális oldalakon (`chrome://`, böngészőbeállítások, Chrome Web Store).

**K: Mi van, ha a furigana pontatlan?**  
V: Ritka szavak vagy speciális olvasások (熟字訓) tévesek lehetnek. Folyamatosan javítunk. Konkrét eseteket szívesen fogadunk.

**K: Nincs hang a TTS-ből?**  
V: Ellenőrizze a rendszer hangerejét és a japán hangcsomagokat. A támogatás böngészőtől és OS-től függ.

**K: A teljes oldal mód rontja az elrendezést?**  
V: A furiganának extra hely kell. Ha zavar, kapcsolja ki a teljes oldal módot, és használjon lebegő buborékokat.

**K: A fordítás nem működik?**  
V: Internet szükséges. Ha a Bing nem megy, próbálja a Google-t a beállításokban. Egyes hálózatok blokkolhatják a fordítószolgáltatásokat.

**K: Hogyan nyitok PDF-et a Furigana Readerben?**  
V: „Open PDF Reader” a felugróban, jobb klikk PDF linkre — „Open PDF with Furigana Reader”, vagy kapcsolja be a „PDF Smart Detection”-t az automatikus átirányításhoz.

**K: A PDF Smart Detection be van kapcsolva, de néhány PDF nem irányít át?**  
V: Az automatikus átirányítás `.pdf`-re végződő URL-ekre működik. Kiterjesztés nélküli URL vagy a Chrome beépített nézője esetén értesítés és jelvény javasolja a Furigana Reader megnyitását.

**K: Használhatom a szótárt offline?**  
V: Igen. A JMdict (180 000+ cím) teljes egészében a bővítményben van. Minden keresés helyben történik, hálózat nélkül.

---

## Kapcsolódó linkek

- [Adatvédelmi irányelvek](../privacy-policy)
- [Támogatás és visszajelzés](../support)

---
