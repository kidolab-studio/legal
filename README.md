# kidolab — Legal / Yasal Belgeler

Legal documents (privacy policies and license notices) for the games published by kidolab-studio.
kidolab-studio'nun yayımladığı oyunların yasal belgeleri (gizlilik politikaları ve lisans bildirimleri).

| Game / Oyun | Documents / Belgeler | Contact / İletişim |
| --- | --- | --- |
| **Lina's Farm** (*Lina'nın Çiftliği*) | [Privacy Policy / Gizlilik Politikası](https://kidolab-studio.github.io/legal/linasfarm/privacy-policy) | emirsalihgumruk@gmail.com |
| **Taktuk Köy** | [Privacy Policy / Gizlilik Politikası](https://kidolab-studio.github.io/legal/taktuk-koy/privacy-policy) · [Licenses / Lisanslar](https://kidolab-studio.github.io/legal/taktuk-koy/licenses) | benbilirim2004@gmail.com |

---

## Bakım notları

### Yapı

- Her oyunun kendi klasörü var (`linasfarm/`, `taktuk-koy/`). İçinde `privacy-policy.html`, varsa
  `licenses.html` ve o oyunun bakım notlarını tutan bir `README.md` bulunur.
- Sayfaların adresi `https://kidolab-studio.github.io/legal/<klasör>/<dosya>` biçimindedir; `.html` uzantısı
  yazılmadan da açılır.
- Kökte `index.html` yok; GitHub Pages bu README'yi sitenin ana sayfası olarak yayınlar.

### Yeni oyun eklemek

1. Oyun için kısa bir klasör aç: küçük harf, Türkçe karakter ve boşluk yok, gerekirse tire (`taktuk-koy`).
2. İçine `privacy-policy.html` (Türkçe ve İngilizce aynı sayfada) ve oyunun `README.md`'sini koy; lisans
   sayfası varsa `licenses.html`.
3. Yukarıdaki tabloya oyunu ekle.
4. `main` dalına gönder; GitHub Pages birkaç dakika içinde yayınlar.

### Adresler değişirse

Bir klasörün ya da reponun adı değişirse o oyunun adresleri de değişir ve GitHub Pages eski adresi yeni adrese
yönlendirmez. Google Play Console'daki gizlilik politikası alanını ve oyunun içindeki adresi birlikte güncelle
(hangi dosyada olduğu oyunun klasöründeki README'de yazar).
