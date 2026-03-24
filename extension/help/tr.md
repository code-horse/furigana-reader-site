---
layout: bare
title: Furigana Reader — Kullanıcı Kılavuzu
lang: tr
---

# Furigana Reader — Kullanıcı Kılavuzu

> Sürüm: v2.0.0

## Giriş

Furigana Reader, Japonca öğrenenler için bir tarayıcı uzantısıdır. JavaScript yedeklemeli WASM morfolojik analizör (Lindera) ile çalışır; web sayfalarındaki kanji karakterlerine okuma notları (furigana) ekleyerek telaffuzu öğrenmenizi kolaylaştırır.

---

## Temel özellikler

- **Metin seçimiyle not** — Sayfadaki Japonca metni seçerek furigana ve konuşma düğmelerini otomatik gösterin
- **Tüm sayfa furigana modu** — Tek tıkla sayfadaki tüm kanjilere furigana ekleyin
- **Metin okuma (TTS)** — Hoparlör simgesine tıklayarak telaffuzu dinleyin
- **Seçim okuma** — Japonca metni seçin, yüzen düğmeyi kullanın veya sağ tıklayıp «Seçimi sesli oku» deyin
- **Üzerine gelince ipuçları** — İşaretlenmiş karakterin üzerine gelince furigana ve telaffuz düğmeleri
- **Çoklu furigana biçimi** — Hiragana, katakana veya romaji
- **Çok dilli arayüz** — 38 arayüz dili

---

## Nasıl kullanılır

### Adım 1: Uzantıyı yükleyin

**Furigana Reader**’ı [Chrome Web Mağazası](https://chromewebstore.google.com/)’ndan yükleyin veya geliştirici modunda yerel olarak ekleyin.

### Adım 2: Bir web sayfası açın

Japonca içerik içeren herhangi bir sayfayı ziyaret edin.

### Adım 3: Metin seçin veya yüzen düğmeyi kullanın

Not eklemek istediğiniz metni seçin veya sağ alttaki yüzen düğmeye tıklayarak tüm sayfa furigana modunu açın.

### Adım 4: Furiganayı görüntüleyin

Karakterlerin üzerine gelin; telaffuz için hoparlör simgesine tıklayın.

### Adım 5: Seçili metni okutun

Metni fareyle seçin, yüzen hoparlör düğmesine tıklayın veya sağ tıklayıp «Seçimi sesli oku»yu seçin.

> **İpucu:** Araç çubuğundaki uzantı simgesine tıklayarak furigana biçimi, konuşma hızı vb. ayarları açın.

---

## Ayarlar rehberi

| Ayar | Açıklama |
|------|----------|
| **Furiganayı etkinleştir** | Furigana özelliğini açıp kapatır |
| **Tüm sayfa furigana** | Açıkken tüm kanjiler için furigana gösterir (sayfa düzenini etkileyebilir) |
| **Furigana biçimi** | Hiragana, katakana veya romaji |
| **Konuşma hızı** | Okuma hızı |
| **Üzerine gelince ipuçları** | Fareyle üzerine gelince furigana ipucu |

---

## SSS

**S: Bazı sayfalarda neden çalışmıyor?**  
C: Güvenlik nedeniyle uzantılar `chrome://`, tarayıcı ayarları veya Chrome Web Mağazası gibi özel sayfalarda çalışmaz.

**S: Furigana yanlışsa ne yapmalıyım?**  
C: Nadir kelimeler veya özel okumalar (熟字訓, jukujikun) hatalı olabilir. Sürekli geliştiriyoruz; lütfen örnekleri paylaşın.

**S: Metin okumada ses yok?**  
C: Sistem sesini ve Japonca ses paketlerinin yüklü olduğunu kontrol edin. Destek tarayıcı ve işletim sistemine göre değişir.

**S: Tüm sayfa modu düzeni bozar mı?**  
C: Furigana ek alan gerektirir; orijinal düzeni etkileyebilir. Rahatsız ediyorsa modu kapatıp ipuçlarını kullanın.

---

## İlgili bağlantılar

- [Gizlilik politikası](../privacy-policy)
- [Destek ve geri bildirim](../support)

---
