---
layout: bare
title: Furigana Reader — Kullanıcı Kılavuzu
lang: tr
---

# Furigana Reader — Kullanıcı Kılavuzu

> Sürüm: v1.4.0

## Giriş

Furigana Reader, Japonca öğrenenler için bir tarayıcı uzantısıdır. JavaScript yedeklemeli WASM morfolojik analizör (Lindera + IPAdic) ile çalışır; web sayfalarındaki ve PDF’lerdeki kanji karakterlerine okuma notları (furigana) doğru şekilde ekler. Yerleşik bir Japonca sözlük, metinden konuşma ve çeviri özellikleri de sunar — böylece Japonca telaffuzu daha kolay öğrenirsiniz.

---

## Temel özellikler

- **Tüm sayfa furigana modu** — Tek tıkla sayfadaki tüm kanjilere furigana ekleyin
- **Üzerine gelince sözlük** — İşaretlenmiş karakterin üzerine gelince JMdict tanımları (180 binden fazla madde), okunuşlar, JLPT seviye rozetleri (N5–N1) ve telaffuz düğmeleri; Sözlük, Okunuş veya Kapalı modlarından birini seçin
- **PDF okuyucu** — Furigana, sözlük, konuşma ve çeviri ile yerleşik PDF okuyucu; sürükle-bırak, URL ile açma ve akıllı yönlendirmeyle otomatik PDF algılama
- **Üç okuma biçimi** — Hiragana, katakana ve romaji gösterimi
- **Okurigana bölme** — Okurigana (送り仮名) ile kanji gövdelerini doğru ayırır
- **Jukujikun desteği** — Özel okunuşlu çoklu kanji birleşikleri (熟字訓) için doğru okunuşlar
- **Metin okuma (TTS)** — Hoparlör düğmesine tıklayarak Japonca telaffuzu dinleyin
- **Seçimle konuşma ve karaoke** — Herhangi bir Japonca metni seçin; kompakt bir araç çubuğu konuş ve çevir düğmeleriyle görünür; ses çalarken kelime veya karakter bazında gerçek zamanlı vurgulama (karaoke) sesle senkronize olur
- **Seçim çevirisi** — Herhangi bir metni seçin, araç çubuğundaki çevir düğmesine tıklayın; Bing Translate veya Google Translate ile anında çeviri, satır içi balon içinde gösterilir
- **Klavye kısayolları** — Özelleştirilebilir kısayollarla temel özelliklere hızlı erişim
- **Çok dilli arayüz** — 38 arayüz dili

---

## Nasıl kullanılır

### Adım 1: Uzantıyı yükleyin

**Furigana Reader**’ı [Chrome Web Mağazası](https://chromewebstore.google.com/)’ndan yükleyin veya geliştirici modunda yerel olarak yükleyin.

### Adım 2: Herhangi bir web sayfasını açın

Japonca içerik içeren bir sayfaya gidin.

### Adım 3: Furigana’yı etkinleştirin

Tarayıcı araç çubuğundaki uzantı simgesine tıklayın. «Furigana’yı etkinleştir»i açın, ardından sayfadaki tüm kanjilere not eklemek için «Tüm sayfa furigana»yı açın. Sağ alttaki yüzen düğmeyi de kullanabilirsiniz.

### Adım 4: Furigana’yı görüntüleyin

Karakterlerin üzerine gelince okunuş ve sözlük tanımları içeren furigana ipuçları görünür. Telaffuz için hoparlör simgesine tıklayın.

### Adım 5: Seçili metni okutun ve çevirin

Fareyle herhangi bir Japonca metni seçin. Seçimin yakınında kompakt bir araç çubuğu iki düğmeyle görünür:
- **🔊 Konuş** — Seçili metni karaoke tarzı vurgulama ile sesli okur
- **🌐 Çevir** — Araç çubuğunun altında satır içi çeviri balonu gösterir

Sağ tıklayıp «Furigana Reader > Seçimi sesli oku» veya «Furigana Reader > Seçimi çevir» de seçebilirsiniz.

> **İpucu:** Furigana biçimi, üzerine gelme modu, konuşma hızı, çeviri motoru ve daha fazlasını ayarlamak için tarayıcı araç çubuğundaki uzantı simgesine tıklayarak ayar panelini açın.

---

## Üzerine gelince sözlük

Uzantı, JMdict (180.000’den fazla madde) ile çalışan yerleşik bir Japonca sözlük içerir. Ayarlardan birden fazla üzerine gelme modu seçebilirsiniz:

| Mod | Davranış |
|-----|----------|
| **Sözlük** | Üzerine gelince okunuş + tanım + JLPT seviyesi + telaffuz düğmesi |
| **Okunuş** | Üzerine gelince okunuş + telaffuz düğmesi (tanım yok) |
| **Kapalı** | Üzerine gelme etkisi yok |

**Sözlük** modunda ipucu şunları gösterir:
- Kelime ve okunuşu (furigana)
- Telaffuz düğmesi (tıklayınca dinle)
- JMdict’ten Japonca tanımlar
- Varsa JLPT seviye rozeti (N5–N1)

> **İpucu:** Sözlük verisi Sözlük modu açıkken isteğe bağlı yüklenir; başka modlara geçildiğinde bellek tasarrufu için kaldırılır.

---

## PDF okuyucu

Furigana Reader, web sayfalarındaki özelliklerin aynısını PDF’lerde de sunan yerleşik bir PDF okuyucu içerir: furigana, sözlük, konuşma ve çeviri.

### PDF açma

**Yöntem 1: Açılır pencereden**  
Uzantı simgesine tıklayın, ardından «PDF okuyucuyu aç»a tıklayın. PDF dosyasını sürükleyip bırakın veya «Dosya seç» ile yerel PDF açın. PDF URL’si de yapıştırabilirsiniz.

**Yöntem 2: Bağlam menüsü**  
Sayfadaki herhangi bir `.pdf` bağlantısına sağ tıklayıp «Furigana Reader ile PDF aç»ı seçin.

**Yöntem 3: Otomatik algılama**  
Ayarlarda «PDF akıllı algılama» açıkken uzantı `.pdf` URL’lerini yerleşik okuyucuya yönlendirir. PDF algılanıp yönlendirilmediğinde (ör. Chrome’un yerleşik görüntüleyicisi) Furigana Reader’da açmanız için bildirim ve istemler görürsünüz.

### PDF okuyucu özellikleri

- **Furigana notları** — Tüm sayfa modu ve üzerine gelme ipuçları dahil tüm furigana özellikleri PDF metninde çalışır
- **Beş furigana modu** — Hiragana, katakana, romaji, yalnızca üzerine gelme ve Kapalı
- **Tıklamayla sözlük** — Herhangi bir kelimeye tıklayınca JMdict tanımı (PDF’de dikkat dağıtmamak için üzerine gelme yerine tıklama kullanılır)
- **Seçim araç çubuğu** — Metni seçerek okutma, çevirme veya kopyalama
- **Kenar çubuğu** — İçindekiler ve sayfa küçük resimleri
- **Arama** — PDF içinde tam metin arama
- **Temalar** — Koyu, açık ve sepia okuma temaları
- **Yakınlaştırma** — Furigana’ya uyumlu birden fazla yakınlaştırma düzeyi
- **Klavye kısayolları** — Gezinme için ok tuşları, yakınlaştırma için +/-, arama için Ctrl/Cmd+F

---

## Seçimle konuşma ve karaoke

Seçimle konuşma, herhangi bir Japonca metni seçip tek tıkla seslendirmenizi sağlar — cümle telaffuzu ve okuma pratiği için idealdir.

**Yöntem 1: Seçim araç çubuğu**  
Fareyle Japonca metin seçin. Seçimin yakınında 🔊 konuş ve 🌐 çevir düğmeli kompakt araç çubuğu görünür. Konuş düğmesine tıklayın. Metin okunurken her kelime veya karakter gerçek zamanlı vurgulanır (karaoke), böylece takip edebilirsiniz.

**Yöntem 2: Sağ tık menüsü**  
Japonca metni seçtikten sonra sağ tıklayıp «Furigana Reader > Seçimi sesli oku»yu seçin.

**Yöntem 3: Klavye kısayolu**  
Metni seçip `Alt+Shift+S` (Mac: `Ctrl+Shift+S`) tuşlarına basın.

> **İpucu:** Karaoke vurgusu, tarayıcınız TTS kelime sınırı olaylarını desteklediğinde en iyi çalışır. Desteklenmiyorsa uzantı akıcı vurgu için zamanlamaya dayalı bir yedek kullanır.

---

## Çeviri

Sayfadaki herhangi bir metni seçip çeviri özelliğiyle anında çeviri alın.

**Yöntem 1: Seçim araç çubuğu**  
Metni seçin, araç çubuğundaki 🌐 çevir düğmesine tıklayın. Sonucu kopyalama düğmesiyle birlikte gösteren bir çeviri balonu açılır.

**Yöntem 2: Sağ tık menüsü**  
Metni seçin, sağ tıklayıp «Furigana Reader > Seçimi çevir»i seçin.

**Yöntem 3: Klavye kısayolu**  
Metni seçip `Alt+Shift+T` (Mac: `Ctrl+Shift+T`) tuşlarına basın.

**Çeviri motorları:**
- **Bing Translate** (varsayılan) — Microsoft Translator
- **Google Translate** — Google

Her iki motor da **108 hedef dili** destekler.

Çeviri motorunu ve hedef dili uzantı ayarlarından değiştirebilirsiniz. Hedef dil tarayıcı dilinizden otomatik algılanır.

> **İpucu:** Araç çubuğunu veya balonu kapatmak için dışarı herhangi bir yere tıklayın.

---

## Klavye kısayolları

| Kısayol | Mac kısayolu | Eylem |
|---------|--------------|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Furigana notlarını aç/kapa |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Seçili metni seslendir |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Seçili metni çevir |

> **İpucu:** Bu kısayolları Chrome’da `chrome://extensions/shortcuts` adresinden özelleştirebilirsiniz.

---

## Ayarlar rehberi

| Ayar | Açıklama |
|------|----------|
| **Furigana’yı etkinleştir** | Furigana özelliğini açıp kapatma ana anahtarı |
| **Tüm sayfa furigana** | Açıkken tüm kanjilere furigana gösterir (sayfa düzenini etkileyebilir) |
| **Üzerine gelme modu** | Üzerine gelme davranışı: Sözlük (okunuş + tanımlar + JLPT + ses), Okunuş (okunuş + ses) veya Kapalı |
| **Furigana biçimi** | Hiragana, katakana veya romaji |
| **Konuşma hızı** | Cümle okuma hızını ayarlar |
| **Çeviri motoru** | Bing Translate veya Google Translate |
| **Hedef dil** | Çeviri hedef dili (tarayıcı dilinden otomatik algılanır) |
| **PDF akıllı algılama** | Açıkken PDF URL’lerini yerleşik okuyucuya yönlendirir ve PDF algılandığında bildirim gösterir |

---

## SSS

**S: Bazı sayfalarda neden çalışmıyor?**  
C: Güvenlik nedeniyle uzantılar `chrome://`, tarayıcı ayarları veya Chrome Web Mağazası gibi özel sayfalarda çalışamaz.

**S: Furigana yanlışsa ne yapmalıyım?**  
C: Nadir kelimeler veya özel okunuşlar (熟字訓) hata verebilir. Sürekli geliştiriyoruz. İyileştirmemize yardımcı olmak için örnek paylaşın.

**S: Metinden konuşmada ses yok?**  
C: Sistem sesini ve Japonca ses paketlerinin yüklü olduğunu kontrol edin. Konuşma desteği tarayıcı ve işletim sistemine göre değişir.

**S: Tüm sayfa modu düzeni bozuyor mu?**  
C: Furigana ekstra alan gerektirebilir. Okumayı zorlaştırıyorsa tüm sayfa modunu kapatıp üzerine gelme ipuçlarını kullanın.

**S: Çeviri çalışmıyor?**  
C: Çeviri internet bağlantısı gerektirir. Bing Translate başarısız olursa ayarlardan Google Translate’i deneyin. Bazı ağlar çeviri hizmetlerini engelleyebilir.

**S: PDF’yi Furigana Reader ile nasıl açarım?**  
C: Açılır pencerede «PDF okuyucuyu aç», PDF bağlantısına sağ tıklayıp «Furigana Reader ile PDF aç» veya ayarlarda «PDF akıllı algılama» ile otomatik yönlendirme kullanabilirsiniz.

**S: PDF akıllı algılama açık ama bazı PDF’ler yönlendirilmiyor?**  
C: Otomatik yönlendirme `.pdf` ile biten URL’ler için geçerlidir. Uzantısız sunulan PDF’ler veya Chrome görüntüleyicide açılanlar için bildirim ve rozetle Furigana Reader’da açmanız istenir.

**S: Sözlüğü çevrimdışı kullanabilir miyim?**  
C: Evet. JMdict sözlüğü (180.000’den fazla madde) uzantıya tamamen gömülüdür. Tüm aramalar yerel yapılır, ağ bağlantısı gerekmez.

---

## İlgili bağlantılar

- [Gizlilik politikası](../privacy-policy)
- [Destek ve geri bildirim](../support)

---
