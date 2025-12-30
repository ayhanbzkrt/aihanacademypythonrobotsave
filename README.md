# 🤖 AI'HAN ACADEMY | Python ile Robot Kurtarma

Çocuklar (7–14) için **tek sayfalık, oyunlaştırılmış ve iki dilli (TR/EN)** bir Python öğrenme macerası.  
Görevleri tamamla, mini quiz’leri çöz, kodu tarayıcıda çalıştır ve kayıp robotları galaksilerine geri gönder! 🌌

---

## 🚀 Canlı Demo (GitHub Pages)
Repo ayarlarında Pages açtıysan demo linkin şuna benzer:

- `https://<kullanici-adi>.github.io/<repo-adi>/`

> Eğer proje adını “repository name” olarak yayınladıysan URL yukarıdaki gibi olur.

---

## ✨ Özellikler

- **TR/EN dil seçimi** (açılış ekranı + içerikler)
- **Sinematik intro overlay**
- **Görev kartları (Mission Grid)**: kilitli/açık/tamamlandı durumları
- **Pyodide ile tarayıcıda Python çalıştırma** (terminal + kod editörü)
- **Mini quiz sistemi** (çoktan seçmeli / boşluk doldurma / mini görev formatları)
- **XP, rozet ve robot ruh hâli (mood) sistemi**
- **Final ekranı + sertifika üretimi** (yazdırma desteği)
- Mobil uyumlu tasarım + neon/uzay teması

---

## 🧩 İçerik (Topics)

Proje; Python temellerinden başlayıp mini projeye kadar ilerleyen **18 konu** içerir:

- Python temelleri: değişkenler, veri tipleri, koşullar, döngüler, fonksiyonlar  
- Veri yapıları: listeler & sözlükler  
- Hata yönetimi: try/except  
- Dosya işlemleri (tarayıcı simülasyonu)  
- OOP (class / inheritance)  
- Modüller (random, math, datetime)  
- API ile çalışma (tarayıcı simülasyonu)  
- Mini proje: Robot iletişimi  
- İleri Python: list comprehensions, lambda, decorators, iterators & generators  
- AI temelleri + Python ile basit AI uygulaması (simülasyon odaklı)

---

## 🛠️ Kullanılan Teknolojiler

- **HTML / CSS / Vanilla JS**
- **Pyodide** (Python’u tarayıcıda çalıştırmak için)
- Google Fonts: Fredoka, Orbitron, Comic Neue
- Font Awesome ikonları

---

## 📦 Kurulum (Yerelde Çalıştırma)

Bu proje statik olduğu için iki yol var:

### 1) En Kolay: Dosyayı Aç
- `index.html` dosyasını çift tıkla, tarayıcıda aç.

> Not: Bazı tarayıcılarda Pyodide/CORS nedeniyle “file://” modunda kısıtlar olabilir.  
> Sorun yaşarsan aşağıdaki gibi basit bir local server kullan.

### 2) Local Server (Önerilen)
Python yüklüyse:

```bash
python -m http.server 8000
