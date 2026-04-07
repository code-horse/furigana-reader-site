---
layout: bare
title: Furigana Reader -laajennus - Käyttöopas
lang: fi
---

# Furigana Reader - Käyttöopas

> Versio: v1.4.1

## Johdanto

Furigana Reader on selainlaajennus japanin opiskelijoille. WASM-morfologinen analysoija (Lindera + IPAdic) ja JavaScript-varmistus lisäävät tarkasti furigana-lukumerkintöjä kanji-merkkeihin verkkosivuilla ja PDF-tiedostoissa. Mukana on myös sisäänrakennettu japanin sanakirja, tekstistä puheeksi ja käännös — japanin ääntämisen oppiminen helpottuu.

---

## Tärkeimmät ominaisuudet

- **Koko sivun furigana** — Lisää furigana kaikkiin kanji-merkkeihin yhdellä napsautuksella
- **Sanakirja osoitettaessa** — Vie osoitin merkittyjen merkkien päälle nähdäksesi JMdict-määritelmät (180 000+ tietuetta), lukutavat, JLPT-tasomerkit (N5–N1) ja ääntämispainikkeet; valitse tila Sanakirja, Lukutapa tai Pois käytöstä
- **PDF-lukija** — Sisäänrakennettu PDF-lukija furiganalla, sanakirjalla, puheella ja käännöksellä; tukee raahaa ja pudota -toimintoa, URL-latausta ja automaattista PDF-tunnistusta älykkäällä uudelleenohjauksella
- **Kolme furigana-tyyliä** — Hiragana, Katakana ja Romaji
- **Okurigana-jako** — Jakaa okurigana (送り仮名) kanji-juurista tarkasti
- **Jukujikun-tuki** — Oikeat lukutavat monikanji-yhdistelmille, joilla on erityislukutapa (熟字訓)
- **Tekstistä puheeksi** — Napsauta kaiutinkuvaketta kuullaksesi japanin ääntämisen
- **Valinnan puhe ja karaoke** — Valitse japaninkielistä tekstiä; kompakti työkalupalkki näkyy puhe- ja käännöspainikkeilla; puhe toistuu sanan tai merkin kerrallaan korostettuna reaaliajassa (karaoke) äänen mukana
- **Valinnan käännös** — Valitse tekstiä, napsauta käännöspainiketta palkissa saadaksesi heti käännöksen Bingin tai Google Translaten kautta, näkyy inline-kuplassa
- **Pikanäppäimet** — Pääominaisuuksiin pääsee mukautettavilla pikanäppäimillä
- **Monikielinen käyttöliittymä** — 38 käyttöliittymän kieltä

---

## Käyttöohje

### Vaihe 1: Asenna laajennus

Asenna **Furigana Reader** [Chrome Web Storesta](https://chromewebstore.google.com/) tai lataa se paikallisesti kehittäjätilassa.

### Vaihe 2: Avaa verkkosivu

Siirry sivulle, jossa on japaninkielistä sisältöä.

### Vaihe 3: Ota furigana käyttöön

Napsauta laajennuskuvaketta työkalupalkissa. Ota «Ota furigana käyttöön» käyttöön, sitten «Koko sivun furigana» merkitäksesi kaikki kanji. Voit myös käyttää oikean alakulman kelluvaa painiketta.

### Vaihe 4: Katso furiganaa

Vie osoitin merkkien päälle nähdäksesi vihjeet lukutavoista ja sanakirjamääritelmistä. Napsauta kaiutinkuvaketta kuullaksesi ääntämisen.

### Vaihe 5: Lue valittu teksti ääneen ja käännä

Valitse japaninkielistä tekstiä hiirellä. Kompakti työkalupalkki näkyy valinnan lähellä kahdella painikkeella:
- **🔊 Puhu** — Lukee valitun tekstin ääneen karaoketyylisellä korostuksella
- **🌐 Käännä** — Näyttää inline-käännöskuplan työkalupalkin alla

Voit myös napsauttaa hiiren oikealla ja valita «Furigana Reader > Lue valinta ääneen» tai «Furigana Reader > Käännä valinta».

> **Vinkki:** Napsauta laajennuskuvaketta avataksesi asetukset ja säätääksesi furigana-tyyliä, osoitustilaa, puhenopeutta, käännösmoottoria ja muuta.

---

## Sanakirja osoitettaessa

Laajennuksessa on sisäänrakennettu japanin sanakirja JMdictin pohjalta (180 000+ tietuetta). Asetuksista voit valita osoitustilan:

| Tila | Toiminta |
|------|----------|
| **Sanakirja** | Osoitus näyttää lukutavan + määritelmän + JLPT-tason + ääntämispainikkeen |
| **Lukutapa** | Osoitus näyttää lukutavan + ääntämispainikkeen (ei määritelmiä) |
| **Pois käytöstä** | Ei osoitustehostetta |

**Sanakirja**-tilassa vihje näyttää:
- Sanan ja sen lukutavan (furigana)
- Ääntämispainikkeen (napsauta kuunnellaksesi)
- Japaninkieliset JMdict-määritelmät
- JLPT-tasomerkin (N5–N1), kun saatavilla

> **Vinkki:** Sanakirjatiedot ladataan tarvittaessa, kun Sanakirja-tila on päällä, ja vapautetaan muissa tiloissa muistin säästämiseksi.

---

## PDF-lukija

Furigana Readerissa on sisäänrakennettu PDF-lukija: voit lukea PDF-tiedostoja furiganalla, sanakirjalla, puheella ja käännöksellä — samat ominaisuudet kuin verkkosivuilla, nyt PDF:lle.

### PDF:n avaaminen

**Tapa 1: Ponnahdusikkunasta**  
Napsauta laajennuskuvaketta ja sitten «Avaa PDF-lukija». Vedä ja pudota PDF-tiedosto tai napsauta «Valitse tiedosto» avataksesi paikallisen PDF:n. Voit myös liittää PDF-URL-osoitteen.

**Tapa 2: Kontekstivalikko**  
Napsauta sivulla `.pdf`-linkkiä hiiren oikealla ja valitse «Avaa PDF Furigana Readerilla».

**Tapa 3: Automaattinen tunnistus**  
Kun asetuksissa on «PDF Smart Detection» käytössä, laajennus ohjaa `.pdf`-URL-osoitteet automaattisesti sisäänrakennettuun lukijaan. Jos PDF tunnistetaan mutta ei ohjata (esim. Chromen sisäänrakennettu katselu), näet ilmoituksia ja kehotuksia avata Furigana Readerissa.

### PDF-lukijan ominaisuudet

- **Furigana** — Kaikki furigana-ominaisuudet toimivat PDF-tekstissä, mukaan lukien koko sivu ja osoitusvihjeet
- **Viisi furigana-tilaa** — Hiragana, Katakana, Romaji, Vain osoitus ja Pois käytöstä
- **Napsautussanakirja** — Napsauta sanaa nähdäksesi JMdict-määritelmän (PDF:ssä käytetään napsautusta osoituksen sijaan häiriöttömään lukemiseen)
- **Valintatyökalupalkki** — Valitse tekstiä puhuaksesi, kääntääksesi tai kopioidaksesi
- **Sivupaneeli** — Sisällysluettelo ja sivuminiatyyrit
- **Haku** — Koko tekstin haku PDF:ssä
- **Teemat** — Tumma, vaalea ja sepia
- **Zoomaus** — Useita zoomaustasoja mukaan lukien zoomiin sovitettu furigana
- **Pikanäppäimet** — Nuolinäppäimet navigointiin, +/- zoomaukseen, Ctrl/Cmd+F hakuun

---

## Valinnan puhe ja karaoke

Valitse japaninkielistä tekstiä ja kuuntele se yhdellä napsautuksella — hyvä lauseiden ääntämiseen ja lukuharjoitteluun.

**Tapa 1: Valintatyökalupalkki**  
Valitse japaninkielistä tekstiä. Kompakti palkki näkyy 🔊 puhe- ja 🌐 käännöspainikkeilla. Napsauta puhepainiketta. Puheen aikana jokainen sana tai merkki korostuu reaaliajassa (karaoke).

**Tapa 2: Kontekstivalikko**  
Kun olet valinnut japaninkielistä tekstiä, napsauta hiiren oikealla ja valitse «Furigana Reader > Lue valinta ääneen».

**Tapa 3: Pikanäppäin**  
Valitse tekstiä ja paina `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) puhuaksesi.

> **Vinkki:** Karaoke-korostus toimii parhaiten, kun selain tukee TTS-sanarajatapahtumia. Muuten laajennus käyttää aikaan perustuvaa varavaihtoehtoa.

---

## Käännös

Valitse tekstiä sivulta ja käytä käännöstä heti tuloksiin.

**Tapa 1: Valintatyökalupalkki**  
Valitse tekstiä ja napsauta 🌐 käännä palkissa. Käännöskupla näkyy alla tuloksella ja kopiointipainikkeella.

**Tapa 2: Kontekstivalikko**  
Valitse tekstiä, napsauta hiiren oikealla ja valitse «Furigana Reader > Käännä valinta».

**Tapa 3: Pikanäppäin**  
Valitse tekstiä ja paina `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) kääntääksesi.

**Käännösmoottorit:**
- **Bing Translate** (oletus) — Microsoft Translator
- **Google Translate** — Google

Molemmat tukevat **108 kohdekieltä**.

Voit vaihtaa käännösmoottoria ja kohdekieltä laajennuksen asetuksissa. Kohdekieli tunnistetaan automaattisesti selaimen kielestä.

> **Vinkki:** Napsauta työkalupalkin tai kuplan ulkopuolelle sulkeaksesi ne.

---

## Pikanäppäimet

| Pikanäppäin | Mac-pikanäppäin | Toiminto |
|-------------|-----------------|----------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Furigana päälle/pois |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Lue valittu teksti ääneen |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Käännä valittu teksti |

> **Vinkki:** Mukauta pikanäppäimiä Chromessa osoitteessa `chrome://extensions/shortcuts`.

---

## Asetusopas

| Asetus | Kuvaus |
|--------|--------|
| **Ota furigana käyttöön** | Pääkytkin furigana-toiminnolle |
| **Koko sivun furigana** | Näyttää furiganan kaikille kanji-merkeille (voi vaikuttaa asetteluun) |
| **Osoitustila** | Sanakirja (lukutapa + määritelmät + JLPT + ääni), Lukutapa (lukutapa + ääni) tai Pois käytöstä |
| **Furigana-tyyli** | Hiragana, Katakana tai Romaji |
| **Puhenopeus** | Lauseiden lukunopeus |
| **Käännösmoottori** | Bing Translate tai Google Translate |
| **Kohdekieli** | Käännöksen kohdekieli (auto selaimen kielestä) |
| **PDF Smart Detection** | Ohjaa PDF-URL-osoitteet automaattisesti sisäänrakennettuun lukijaan ja näyttää ilmoituksia PDF-tunnistuksesta |

---

## UKK

**Q: Miksi se ei toimi joillakin sivuilla?**  
A: Turvallisuussyistä laajennukset eivät toimi sivuilla kuten `chrome://`, selaimen asetukset tai Chrome Web Store.

**Q: Entä jos furigana on väärin?**  
A: Harvinaisilla sanoilla tai erityislukutavoilla (熟字訓) voi olla virheitä. Parannamme jatkuvasti. Kerro konkreettiset tapaukset.

**Q: Ei ääntä tekstistä puheeksi?**  
A: Tarkista järjestelmän äänenvoimakkuus ja japaninkieliset äänet. Tuki vaihtelee selaimen ja käyttöjärjestelmän mukaan.

**Q: Koko sivu vaikuttaa asetteluun?**  
A: Furigana tarvitsee tilaa. Poista koko sivun tila käytöstä ja käytä osoitusvihjeitä, jos se häiritsee.

**Q: Käännös ei toimi?**  
A: Käännös vaatii internetin. Jos Bing epäonnistuu, kokeile Googlea asetuksissa. Jotkin verkot estävät palvelut.

**Q: Miten avaan PDF:n Furigana Readerissa?**  
A: Napsauta «Avaa PDF-lukija» ponnahdusikkunassa, avaa PDF-linkki hiiren oikealla «Avaa PDF Furigana Readerilla» tai ota «PDF Smart Detection» käyttöön automaattista uudelleenohjausta varten.

**Q: PDF Smart Detection on päällä, mutta jotkin PDF:t eivät ohjaudu?**  
A: Automaattinen ohjaus koskee URL-osoitteita, jotka päättyvät `.pdf`-päätteeseen. PDF:itä ilman `.pdf`-päätettä tai Chromen katseluohjelmassa näkyy ilmoitus ja merkki avata Furigana Readerissa.

**Q: Voinko käyttää sanakirjaa offline-tilassa?**  
A: Kyllä. JMdict (180 000+ tietuetta) on kokonaan laajennuksessa. Kaikki haut tehdään paikallisesti ilman verkkoa.

---

## Linkit

- [Tietosuojakäytäntö](../privacy-policy)
- [Tuki ja palaute](../support)

---
