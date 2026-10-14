# Taktuk Köy — Legal / Yasal Belgeler

Legal documents for **Taktuk Köy**, a village-building Android game for children by Mehmet Emin İnce.
Mehmet Emin İnce'nin çocuklar için köy kurma oyunu **Taktuk Köy**'ün yasal belgeleri.

- **Privacy Policy / Gizlilik Politikası:** https://kidolab-studio.github.io/linasfarm-legal/taktuk-koy/privacy-policy
- **Licenses / Lisanslar:** https://kidolab-studio.github.io/linasfarm-legal/taktuk-koy/licenses

The game collects no personal data: it does not connect to the internet, shows no ads and has no in-app purchases.
Oyun hiçbir kişisel veri toplamaz: internete bağlanmaz, reklam göstermez, uygulama içi satın alma yoktur.

Contact / İletişim: benbilirim2004@gmail.com

---

## Bakım notları

- Bu klasördeki dosyalar oyunun deposundaki `docs/legal/` klasöründen kopyalanır; orada düzenle, buraya kopyala.
- `licenses.html` elle yazılmaz: oyun deposunda `godot --headless --path . -s tools/lisans_html.gd -- lisans` ile
  üretilir (oyundaki lisans ekranıyla aynı veri). Godot sürümü ya da yazı tipi değişince yeniden üret.
- `privacy-policy.html` elle düzenlenir; Türkçe ve İngilizce bölümleri ve iki "Yürürlük tarihi" satırını birlikte güncelle.
- Gizlilik adresi Google Play Console'daki gizlilik politikası alanında ve oyunun lisans ekranında
  (`scripts/config.gd` → `GIZLILIK_URL`) kullanılır; klasör adı değişirse ikisini de güncelle.
