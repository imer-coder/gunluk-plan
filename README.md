# Günlük Plan

Temalarla kişiselleştirilebilen, Pomodoro tekniğini içeren günlük çalışma planı ve yapılacaklar listesi. Görevlerini hobiler, kişisel işler ve çalışma gibi kategorilere ayırıp günlük planını kendi tarzına göre düzenleyebilirsin.

**Canlı demo:** https://imer-coder.github.io/temal-to-do-list/

## Özellikler

- **Görev yönetimi:** Kategori (Günlük, Çalışma, Hobiler, Kişisel), öncelik ve enerji seviyesi (düşük / yüksek) ile görev ekleme, düzenleme ve silme
- **Filtreleme:** Duruma, kategoriye ve enerji seviyesine göre listeleme
- **Takvim:** Görevler eklendikleri güne kaydedilir; geçmiş günlere dönüp bakabilir, gelecek günler için plan yapabilirsin. Tamamlanmamış eski görevler tek tıkla bugüne kopyalanır
- **İlerleme çubuğu:** Seçili günün tamamlanma oranını gösterir
- **Pomodoro zamanlayıcı:** Odak, kısa mola ve uzun mola süreleri ayarlanabilir; tamamlanan oturumlar seçilen göreve işlenir
- **Toplam çalışma süresi:** Odak modunda geçen süre gün gün kaydedilir; bugünün, haftanın ve toplam çalışma süresi görünür, takvimde seçilen günün süresi başlıkta yazar
- **Renk teması seçici:** Klasik pembe-turkuaz ve 10 Pantone renk paleti (Living Coral, Greenery, Rose Quartz & Serenity, Emerald, Tangerine Tango, Honeysuckle, Turquoise, Mimosa, Sand Dollar, Blue Iris)
- **Sticker kutusu:** Ruh haline göre hazır sticker'lar, sayfa kenarlarına yerleştirme, boyut değiştirme ve kendi sticker'larını yükleme
- **Washi bant:** Yüksek öncelikli görev kartlarında ekose, puantiyeli veya çiçekli bant
- **Ses efektleri ve ortam sesi:** Görev tamamlama sesleri (su damlası, arp, pop, kağıt) ve ortam sesleri (kuş sesleri, lo-fi)
- **Ekran efektleri:** Sakura yaprakları, ateşböcekleri, kalpler
- **Ruh hali seçici:** Seçime göre karşılama mesajı, sticker'lar ve enerji filtresi değişir
- **Ek panolar:** Not kağıdı, günün sözü ve su takibi
- **Veri saklama:** Tüm veriler tarayıcıda saklanır; sayfa yenilendiğinde ya da sekme kapatılıp tekrar açıldığında kaybolmaz

## Kullanılan teknolojiler

### Diller
- **HTML5:** Sayfa yapısı
- **CSS3:** Cam efekti (glassmorphism), degradeler, animasyonlar
- **JavaScript (Vanilla JS):** Tüm uygulama mantığı, framework kullanılmadı

### Kütüphaneler ve servisler
- **[Tailwind CSS](https://tailwindcss.com/)** (CDN): Yerleşim ve yardımcı sınıflar
- **[canvas-confetti](https://github.com/catdad/canvas-confetti):** Görev tamamlama konfetisi
- **[Google Fonts](https://fonts.google.com/):** Cormorant Garamond ve Jost yazı tipleri

### Tarayıcı API'leri
- **localStorage:** Görevlerin, tercihlerin ve sticker'ların saklanması
- **Web Audio API:** Tamamlama sesleri ve ortam seslerinin ses dosyası kullanmadan üretilmesi
- **Canvas API:** Düşen yaprak, ateşböceği ve kalp efektleri
- **Pointer Events:** Sticker'ların sürükle-bırak ile yerleştirilmesi
- **SVG:** Zambak, ikonlar ve çizimler

### Araçlar
- **[Claude](https://claude.ai/) (Anthropic):** Yapay zeka destekli kod geliştirme ve tasarım
- **GitHub:** Kod barındırma
- **GitHub Pages:** Canlı yayın

## Kurulum

Kurulum gerektirmez. Projenin tamamı tek bir `index.html` dosyasıdır; ek dosya gerekmez. Dosyayı indirip tarayıcıda açman yeterli. İnternet bağlantısı yalnızca Tailwind, yazı tipleri ve konfeti kütüphanesi için gerekir.

## Gizlilik

Uygulama sunucuya veri göndermez. Görevler, ayarlar ve yüklenen sticker'lar yalnızca kullanıcının kendi tarayıcısında saklanır; tarayıcı verisi silinirse bu kayıtlar da silinir.

## Görseller hakkında

Hazır sticker görselleri kişisel kullanım amacıyla derlenmiştir ve hak sahiplerine aittir. Ticari amaçla kullanılmamalıdır.
