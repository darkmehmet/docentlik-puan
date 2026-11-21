# Doçentlik Puan Hesabı

ÜAK Tablo 10 (Sağlık Bilimleri temel alanı, Mart 2025) kriterlerine göre doçentlik başvuru puanını hesaplayan tek sayfalık web uygulaması.

- Yazar payı kuralları (0,8 / 0,5 / yarı-yarı, diğer yayınlarda eşit bölüşüm)
- Madde tavanları ve alt sınırlar (3g–h, 4c–d en çok 5)
- Aynı kitaptan tek bölüm, aynı toplantıdan tek bildiri
- 8 zorunlu şartın (100 puan, uzmanlık sonrası 90, 1., 2., 3., 5., 8. ve 9. madde şartları) kontrolü

Veriler yalnız kullanıcının kendi tarayıcısında (localStorage) saklanır, hiçbir sunucuya gönderilmez.

## GitHub Pages'te yayınlama

1. GitHub'da yeni bir depo oluşturun (örn. `docentlik-puan`). Herkese açık (Public) olmalı; ücretsiz hesapta Pages yalnız açık depolarda çalışır.
2. **Add file → Upload files** ile `index.html` ve `README.md` dosyalarını yükleyip **Commit changes** deyin.
3. **Settings → Pages** bölümünde *Source* olarak **Deploy from a branch**, dal olarak **main** ve klasör olarak **/ (root)** seçip kaydedin.
4. Bir iki dakika sonra sayfa `https://KULLANICI-ADINIZ.github.io/docentlik-puan/` adresinde açılır.

## Veriler hakkında

- Kayıtlar, sayfayı açtığınız tarayıcıya ve adrese bağlıdır. Başka bilgisayarda ya da başka tarayıcıda görünmez.
- Chrome'da "Tarama verilerini temizle → Çerezler ve diğer site verileri" yaparsanız kayıtlar silinir. Gizli pencerede kayıt tutulmaz.
- Düzenli olarak **Yedeği dosyaya indir** ile `.json` yedek alın; başka bir cihazda **Yedekten yükle** ile geri getirebilirsiniz.

Bu hesap bir ön değerlendirmedir; resmi puanlama ÜAK ve jüri tarafından yapılır.
