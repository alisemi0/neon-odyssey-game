# 🌌 NEON ODYSSEY: OVERDRIVE + COMBAT

Synthwave ve Cyberpunk kültüründen ilham alan, sonsuz koşu (endless runner) ve uzay nişancı (space shooter) türlerini harmanlayan retro tarzı web tabanlı bir arcade oyunu. Tamamen tarayıcı üzerinde, harici bir oyun motoruna ihtiyaç duymadan çalışır.

## 📺 Önizleme

![Neon Odyssey Oynanış](https://blogger.googleusercontent.com/img/a/AVvXsEgwkyxjD8cAs50ruvoOGG7mcimcO1L9RlVnAxNKmgTayYYVtsL_G5OM1zF8a_MKg_xIQ1lBAqS9fCzL25qAdqtM-BAKXDvOcBV6cxLFUzbBNQVgXohsXrlx6nv5wNVtHJCmBMl66VDGHfBn2nYMWNaie9hWjtcOCyBXnJgyLilp10RDCxPYe3V6F5ydrfqO)

**[🚀 OYUNU CANLI OYNA (Live Demo) - Buraya Tıklayın](https://denemeaaaa.fwh.is/)**

## ✨ Özellikler

* **Retro Görsel Stil:** CRT monitör tarama çizgileri (scanlines), sahte 3D (pseudo-3D) perspektif ızgarası ve yoğun neon parlama efektleri.
* **Savaş ve Yok Etme Sistemi (Combat):** Sadece kaçmakla kalmayın; engelleri lazer mermilerinizle vurarak puan kazanın ve yolunuzu açın.
* **Overdrive (Hyper) Modu:** Yeterli enerjiyi topladığınızda geminiz altın rengine bürünür, yenilmez olur ve engelleri parçalayarak geçer.
* **Dahili Synthesizer Ses Motoru:** Harici hiçbir ses veya MP3 dosyası kullanılmamıştır. Tüm müzikler ve ses efektleri (ateş etme, patlama, kalkan) doğrudan tarayıcının *Web Audio API* modülü kullanılarak kodla sentezlenir.
* **Kapsamlı Ayarlar:** Düşük donanımlı cihazlar için parçacık efektlerini (GFX), sesleri (SFX) ve mobil cihazlardaki titreşimi (Vibration) kapatma/açma imkanı.
* **Yerel Kayıt (Save Sistemi):** Oyuncunun ulaştığı maksimum seviye ve skor tarayıcının *LocalStorage* belleğine kaydedilir.

## 🎮 Kontroller

* **Yönlendirme:** Gemi, fare (mouse) imlecinizi veya dokunmatik ekrandaki parmağınızı otomatik olarak, yumuşak bir eğimle (tilt) takip eder.
* **Ateş Etme:** Lazer ateşlemek için ekrana sol tıklayın veya dokunun (Tap).
* **Duraklatma:** Oyun içi arayüzdeki "II" butonunu kullanarak veya menülere dönerek oyunu güvenle duraklatabilirsiniz.

## 🛠 Kullanılan Teknolojiler

| Teknoloji | Kullanım Alanı |
| :--- | :--- |
| **HTML5 Canvas API** | Saniyede 60 kare (60FPS) çizim, oyun döngüsü (game loop) ve çarpışma tespit (collision) algoritmaları. |
| **Vanilla JavaScript** | Oyun mekanikleri, entity (nesne) yönetimi, skor takibi ve Web Audio API ile ses üretimi. |
| **CSS3** | Glassmorphism menü tasarımları, animasyonlar ve CRT ekran katmanı. |

## 🚀 Kurulum ve Çalıştırma

Bu oyun, çalışmak için bir sunucuya (backend) veya NodeJS gibi paket yöneticilerine ihtiyaç duymaz.

1. Bu depoyu (repository) bilgisayarınıza `.zip` olarak indirin veya klonlayın.
2. Klasör içindeki `.html` dosyasını çift tıklayarak herhangi bir modern tarayıcıda (Chrome, Edge, Safari, Firefox) açın.
3. Oynamaya başlayın!
