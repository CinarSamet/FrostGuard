# ❄️ FrostGuard

> **Bir gecede yok olan emeği korumak için.**

Akıllı don önleme sistemi: **erken tespit + otonom aksiyon + enerji verimliliği**

🌐 https://frostguard.com.tr

---

## 🎯 Problem

Don olayları:

- 🌙 Gece gerçekleşir → müdahale zor  
- ❄️ Mikro-iklim bazlıdır → genel tahminler yetersiz  
- 💸 Bir gecede %80’e varan ürün kaybı oluşturabilir  

Mevcut çözümler:

- Sadece **uyarı verir**  
- **Manuel müdahale** gerektirir  
- **Enerji ve su israfına** neden olur  

---

## 💡 Çözüm

FrostGuard, don riskini sadece tespit etmez:

> ⚡ **Doğru zamanda otomatik aksiyon alır**

- Sensör verisini analiz eder  
- Sahaya özel karar üretir  
- Aktüatörleri otomatik kontrol eder  

---

## 🧠 Nasıl Çalışır?

~~~text
[ Sensörler ]  →  [ FrostGuard Hub ]  →  [ Aktüatörler ]
     ↓                    ↓                    ↓
  Sıcaklık           Edge Decision        Fan / Isıtıcı
  Nem                (Offline AI)         Sulama / Sisleme
~~~

---

## 🏗️ Sistem Mimarisi

- 📡 **IoT Sensör Node'ları**  
- ⚙️ **Edge Controller (Offline çalışabilir)**  
- 🔥 **Aktüatör Kontrol Sistemi**  
- ☁️ **Cloud Dashboard (opsiyonel)**  

---

## ⚙️ Teknolojik Altyapı

- **Embedded:** ESP32 tabanlı sistemler  
- **Communication:** LoRa / WiFi  
- **Backend:** Go (yüksek performanslı API) + Python (AI işleme)  
- **AI:** Don riski analizi & karar mekanizması  
- **Frontend:** Modern web arayüzü  

---

## 🚀 Öne Çıkan Özellikler

- ⚡ Gerçek zamanlı don riski analizi  
- 🤖 Otonom aksiyon (insan müdahalesi olmadan çalışma)  
- 🌐 Offline çalışma (internet bağımsız)  
- 🔋 Enerji & su optimizasyonu  
- 🧩 Modüler sistem tasarımı  

---

## 🧪 MVP Planı

- 📍 10 dönüm kayısı bahçesi  
- ⏱️ 1 don sezonu test süreci  

📊 Ölçülecek metrikler:

- Müdahale süresi  
- Yanlış tetikleme oranı  
- Ürün kaybı azaltımı  
- Enerji tüketimi  

---

## 📸 Demo

> 🚧 Yakında eklenecek:  
> - Sistem diyagramı  
> - Sahadan görüntüler  
> - Demo video / GIF  

---

## 📌 Roadmap

- [ ] İlk saha kurulumu  
- [ ] Edge AI optimizasyonu  
- [ ] Mobil uygulama  
- [ ] Mikro-iklim tahmin modeli  
- [ ] Farklı ürünlere adaptasyon  

---

## 🧑‍💻 Kurulum (Website)

~~~bash
git clone https://github.com/CinarSamet/FrostGuard.git
cd FrostGuard
~~~

Statik site olduğu için:

- `index.html` dosyasını doğrudan açabilirsin  
veya  
- Live Server ile çalıştırabilirsin  

---

## 🤝 Katkı

1. Fork al  
2. Branch oluştur → `feature/...`  
3. Commit at  
4. Pull Request gönder  


## ⚠️ Durum

Bu proje aktif geliştirme aşamasındadır.  
Mimari ve özellikler sürekli geliştirilmektedir.  

---

## 🤝 Vizyon

FrostGuard’ın hedefi:

> Tarımda **reaktif sistemlerden → otonom karar sistemlerine geçişi** sağlamak.
