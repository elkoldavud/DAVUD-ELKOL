
# Statik Kart Bağlantı Sayfası (index.html)
**Hata nedeni büyük ihtimalle `links.html` dosya adıydı.** Birçok host kök dizinde **`index.html`** arar.
Bu pakette kökte `index.html` var; Netlify Drop, GitHub Pages ve çoğu hosting ile direkt çalışır.

## Yayınlama
### Seçenek 1 — Netlify Drop (en hızlı)
1. https://app.netlify.com/drop aç.
2. `index.html`, `200.html`, `favicon.ico` dosyalarını **birlikte** sürükleyip bırak.
3. Netlify anında bir URL verir (ör. `https://senin-site.netlify.app`).

### Seçenek 2 — GitHub Pages
1. Yeni repo oluştur.
2. Bu klasördeki dosyaları yükle (özellikle `index.html`).
3. Settings → Pages → Deploy from branch → `main` / `/ (root)` → Save.

## Düzenleme
- Metinleri `index.html` içinde değiştir (Ad, Ünvan, site linkleri, e‑posta, telefon).
- vCard için `contact.vcf` düzenle.
- Dosyaları aynı yere tekrar yüklediğinde URL **değişmez**; QR’ı yeniden basmana gerek kalmaz.

## İpucu
- Eğer alt yola yükleyeceksen (ör. `/liens`), Netlify’da klasör olarak deploy et; QR’ın hedefi yeni URL olsun.
