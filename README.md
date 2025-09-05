# HEIC → JPEG Dönüştürücü (Web)

📸 Basit, hızlı ve tamamen **tarayıcı içinde çalışan** bir HEIC → JPEG dönüştürücü.  
Dosyalarınız **sunucuya yüklenmez**, tüm işlem bilgisayarınızda gerçekleşir.

👉 [Canlı demo (GitHub Pages)](https://metinciris.github.io/HEIC/)

---

## ✨ Özellikler
- **Çoklu yükleme** desteği (birden fazla HEIC dosyasını aynı anda seçin veya sürükleyin).
- **Otomatik JPEG dönüşümü** – tek tıkla toplu işlem.
- **Önizleme**: Dönüştürülen her dosya için küçük JPEG önizlemesi.
- **Durum takibi**: Her dosya için *Beklemede → Dönüştürülüyor → Hazır* bilgisi.
- **İndirme seçenekleri**:
  - Tek tek indir (her dosya için ayrı).
  - Tümünü ZIP olarak indir.
- **Kalite ayarı** (%40 – %100 arasında seçilebilir).
- Hiçbir ek yazılım gerekmez — yalnızca modern bir tarayıcı yeterlidir.

---

## 🚀 Kullanım
1. [Demo sayfasını açın](https://metinciris.github.io/HEIC/).
2. HEIC dosyalarınızı sürükleyip bırakın veya “HEIC dosyaları seç” butonuyla yükleyin.
3. “Dönüştür” butonuna basın.
4. Sonuçları önizleyin, tek tek indirin veya topluca ZIP olarak alın.

---

## 🛠️ Teknolojiler
- [heic2any](https://github.com/alexcorvi/heic2any) (WASM tabanlı HEIC → JPEG dönüştürücü)
- [JSZip](https://stuk.github.io/jszip/) (ZIP arşivleme)
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) (tarayıcıda dosya indirme)

---

## 📦 Kurulum (Opsiyonel)
Projeyi yerel bilgisayarında çalıştırmak istersen:
```bash
git clone https://github.com/metinciris/HEIC.git
cd HEIC
# index.html dosyasını tarayıcıda aç
