# Günlük Plan

Temalarla kişiselleştirilebilen, Pomodoro tekniğini içeren günlük çalışma planı ve yapılacaklar listesi. Görevlerini hobiler, kişisel işler ve çalışma gibi kategorilere ayırıp günlük planını kendi tarzına göre düzenleyebilirsin.

**Canlı demo:** https://imer-coder.github.io/temal-to-do-list/

## Özellikler

- **Görev yönetimi:** Kategori (Günlük, Çalışma, Hobiler, Kişisel), öncelik ve enerji seviyesi (düşük / yüksek) ile görev ekleme, düzenleme ve silme
- **Filtreleme:** Duruma, kategoriye ve enerji seviyesine göre listeleme
- **Takvim:** Görevler eklendikleri güne kaydedilir; geçmiş günlere dönüp bakabilir, gelecek günler için plan yapabilirsin. Tamamlanmamış eski görevler tek tıkla bugüne kopyalanır
- **İlerleme çubuğu:** Tamamlanan görevlerin oranını gösterir
- **Pomodoro zamanlayıcı:** Odak, kısa mola ve uzun mola süreleri ayarlanabilir; oturumlar seçilen göreve işlenir
- **Renk teması seçici:** Klasik pembe-turkuaz ve 10 Pantone renk paleti (Living Coral, Greenery, Rose Quartz & Serenity, Emerald, Tangerine Tango, Honeysuckle, Turquoise, Mimosa, Sand Dollar, Blue Iris)
- **Sticker kutusu:** Çıkartmaları sürükleyip sayfaya yapıştırma
- **Washi bant:** Yüksek öncelikli görev kartlarında ekose, puantiyeli veya çiçekli bant
- **Ses efektleri ve ortam sesi:** Tamamlama sesleri, kuş sesleri ve lo-fi
- **Ekran efektleri:** Sakura yaprakları, ateşböcekleri, kalpler
- **Ruh hali seçici:** Seçime göre karşılama mesajı ve enerji filtresi değişir
- **Ek panolar:** Not kağıdı, günün sözü ve su takibi
- **Veri saklama:** Tüm veriler tarayıcıda saklanır, sayfa yenilendiğinde kaybolmaz

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
- **localStorage:** Görevlerin, tercihlerin ve sticker konumlarının saklanması
- **Web Audio API:** Tamamlama sesleri ve ortam seslerinin ses dosyası kullanmadan üretilmesi
- **Canvas API:** Düşen yaprak, ateşböceği ve kalp efektleri
- **Pointer Events:** Sticker'ların sürükle-bırak ile yerleştirilmesi
- **SVG:** Zambak, ikonlar ve sticker çizimleri

### Araçlar
- **[Claude](https://claude.ai/) (Anthropic):** Yapay zeka destekli kod geliştirme ve tasarım
- **GitHub:** Kod barındırma
- **GitHub Pages:** Canlı yayın

## Kurulum

Kurulum gerektirmez. Projenin tamamı tek bir `index.html` dosyasıdır. Dosyayı indirip tarayıcıda açman yeterli. İnternet bağlantısı yalnızca Tailwind, yazı tipleri ve konfeti kütüphanesi için gerekir.
