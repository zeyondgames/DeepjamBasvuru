# Deep Jam Başvuru Formu

GameDev.ist **Deep Jam** başvuru kılavuzundaki bölümleri aynı sırayla soran, tek sayfalık statik başvuru formu.

**Canlı sayfa:** https://zeyondgames.github.io/Deepjambasvuru/

## Bölümler

1. **1.0 Takım Bilgileri:** Girişim ve iletişim bilgileri
2. **2.0 Oyun Konsepti:** Oyunun adı, türü, özeti ve proje kapsamı
3. **3.0 Teknik & Portfolyo:** Proof of Concept
4. **4.0 İş Modeli ve Finans:** Gelir modeli ve pazara giriş stratejisi
5. **5.0 Taahhüt & Uygunluk:** Motivasyon mektubu, şartlar ve gizlilik

## Veriler nerede saklanır?

Sunucu yok. Yazılan hiçbir şey internete gönderilmez.

- **Otomatik taslak:** Cevaplar her değişiklikte o tarayıcının yerel deposuna kaydedilir. Aynı tarayıcıda sayfa tekrar açılınca geri gelir. Gizli sekmede çalışmaz, cihazlar arasında taşınmaz.
- **JSON olarak indir:** Tüm cevapları bir `.json` dosyasına kaydeder. Asıl yedek budur.
- **JSON'dan yükle:** Kaydedilmiş dosyayı forma geri doldurur. Başka cihazda devam etmek için de kullanılır.
- **Başvuruyu tamamla:** Zorunlu alanları kontrol eder, eksik yoksa JSON dosyasını indirir.

## Yerelde çalıştırma

Derleme adımı yok. `index.html` dosyasını tarayıcıda açmak yeterli.

## GitHub Pages

Depo ayarlarında **Settings → Pages → Build and deployment → Source: Deploy from a branch**, **Branch: `main` / `(root)`** seçilir. `.nojekyll` dosyası Jekyll işlemesini kapatır.
