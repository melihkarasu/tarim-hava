# 🌾 Akıllı Tarım & Zirai Hava Paneli

Open-Meteo ve FAO-56 standartlarında tarımsal hava durumu, Türkiye genelinde 100+ tarım havzası ve canlı il/ilçe arama motoru ile toprak nemi, don uyarısı, ilaçlama uygunluk penceresi ve sulama tavsiyeleri.

## ✨ Özellikler
- **100+ Türkiye Tarım Havzası:** Konya Ovası, Çukurova, Söke Ovası, Gediz Havzası, Harran Ovası, Çarşamba/Bafra, Trakya, Malatya Ovası vb. önceden tanımlı veya canlı OpenStreetMap aramayla tüm Türkiye il/ilçeleri.
- **Toprak Sıcaklığı & Nem Katman Profili:** 
  - 0 cm Yüzey katmanı
  - 6 cm Tohum yatağı derinliği
  - 18 cm Ana kök bölgesi
- **Ekin Türüne Özel Zirai Öneriler:** Buğday/Arpa, Mısır, Pamuk, Domates/Biber, Ayçiçeği, Zeytin, Narenciye için özelleştirilmiş fenolojik risk ve sulama analizi.
- **Aksiyon Odaklı Zirai Uyarılar (Actionable Alerts):**
  - **Don Riski Durumu:** Önümüzdeki 48 saat için yüzey don tahmini ve alarm rozetleri.
  - **Sulama Tavsiyesi:** FAO-56 referans evapotranspirasyon (ET0) buharlaşma indeksi.
  - **İlaçlama Uygunluğu (Spray Window):** Rüzgar hızı ve bağıl neme göre pülverizatör ilaçlama uygunluk penceresi.
  - **Ekim / Çimlenme İndeksi:** Tohum yatağı sıcaklığına göre ekim uygunluğu.
- **İnteraktif 7 Günlük Trend Grafiği (Chart.js):** Toprak sıcaklığı (6 cm) ve buharlaşma (ET0) eğrisi.
- **GPS ile Tarlamın Konumunu Al:** Tarayıcı Geolocation API ile tarlanızın anlık koordinatlarını otomatik çeker.
- **Kayıtlı Tarlalarım / Parsellerim:** Sık takip ettiğiniz parselleri LocalStorage'a kaydedin.
- **%100 Sunucusuz & Ücretsiz:** Herhangi bir API anahtarı veya backend gerektirmez; tamamen açık ve ücretsiz Open-Meteo ve OpenStreetMap servisleri ile doğrudan tarayıcı üzerinden çalışır.

## 🚀 Hızlı Başlangıç
1. Bu repoyu klonlayın:
   ```bash
   git clone https://github.com/melihkarasu/tarim-hava.git
   cd tarim-hava
   ```
2. `index.html` dosyasını doğrudan herhangi bir web tarayıcısında açın veya [GitHub Pages](https://melihkarasu.github.io/tarim-hava/) üzerinden canlı kullanın.

## 🔑 API & Veri Kaynağı
Bu uygulama herhangi bir özel API anahtarı veya kimlik doğrulama **gerektirmez**:
- **Zirai Hava Modeli:** [Open-Meteo Agricultural API](https://open-meteo.com/en/docs/agricultural-weather-api) (FAO-56 evapotranspirasyon, toprak sıcaklığı ve nem katmanları).
- **Coğrafi Konum Arama:** [OpenStreetMap Nominatim](https://nominatim.openstreetmap.org/).
- **Erişim:** Kamuya açık, ücretsiz ve CORS destekli açık veri servisleri.

## 🛠️ Teknik Detaylar
- **Styling:** Tailwind CSS & Mistral AI Design System
- **Grafikler:** Chart.js
- **Storage:** Browser LocalStorage API
- **API Source:** Open-Meteo & OpenStreetMap Nominatim

## 🏆 Krediler & Açık Kaynak Teşekkürleri
- **[Open-Meteo](https://open-meteo.com/):** Açık kaynak ve ücretsiz zirai meteoroloji API'si için teşekkürler.
- **[OpenStreetMap](https://www.openstreetmap.org/):** Açık harita ve konum arama veri tabanı için teşekkürler.
- **[Chart.js](https://www.chartjs.org/):** İnteraktif veri görselleştirme kütüphanesi için teşekkürler.
- **[Public APIs](https://github.com/public-apis/public-apis):** Açık kaynak API ekosistemi için teşekkürler.
- **[OpenClaw](https://github.com/openclaw/openclaw):** Proje mimarisi ve otonom iş akışı.
- **[Google Gemini](https://github.com/google-gemini):** Kodlama ve istemci optimizasyonları.
- **[VoltAgent / awesome-design-md](https://github.com/VoltAgent/awesome-design-md):** Mistral AI Tasarım Sistemi.

## 📜 Lisans
MIT Lisansı altında açık kaynak olarak paylaşılmıştır.

---
Daha fazla açık kaynak mikro uygulama için [GitHub profilimi](https://github.com/melihkarasu) ziyaret edebilirsiniz.
