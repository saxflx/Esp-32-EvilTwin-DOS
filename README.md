DİKKAT!  
Bu proje, https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal projesinin Türkçeye çevirilmiş halidir.  
Wifi adı : 1devlet2millet  
Şifre : 128milyar  
Ekstra Özellik :  
16x2 LCD ekran  
Pin Bağlantıları : SDA = G21 , SCL = G22  

---

[![Github Issues](https://img.shields.io/github/issues/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/issues)
[![Github Forks](https://img.shields.io/github/forks/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/network/members)
[![Github Stars](https://img.shields.io/github/stars/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/stargazers)
[![Top Language](https://img.shields.io/github/languages/top/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)

---

## 🧠 Etiketler

`ESP32` `IoT` `WiFi Hacking` `Deauthentication` `Captive Portal` `Mikrodenetleyici Güvenliği` `Arduino`

---

---

# 🚨 ESP32 Kötü İkiz WiFi Hacking | Deauthentication & Captive Portal 🚨

> **Uyarı:** Bu proje sadece **eğitim amaçlıdır**. Sorumlulukla ve yasal olarak kullanın. Ağlar üzerinde yetkisiz saldırılar, çoğu ülkede yasaktır. 🌐🔒

---

![Profil Görüntülenmeleri](https://komarev.com/ghpvc/?username=aadesh0706\&color=blue)
*Aktif: `Eylül 2024`*

**Hesap Açılışı:** `Eylül 2020`

---

### 🎥 **Demo Videosu**

Bu projenin aksiyon halindeki demosuna göz atın! 🎬
[![ESP32 Kötü İkiz WiFi Hacking](https://img.youtube.com/vi/AEb33trYEAY/0.jpg)](https://www.youtube.com/shorts/AEb33trYEAY)
Küçük resmi tıklayarak veya [bu bağlantıyı](https://www.youtube.com/shorts/AEb33trYEAY) takip ederek izleyebilirsiniz.

---

### 🎯 **Proje Genel Bakış**

Bu depo, **ESP32** modülünü kullanarak **Kötü İkiz WiFi Hacking** saldırısı nasıl yapılır, bunu gösteriyor. Saldırı, kullanıcıları orijinal ağlarından çıkararak, onları sahte bir erişim noktasına bağlar ve burada **captiv portal** ile WiFi şifrelerini toplar.

Proje, **HTML**, **CSS** ve **JavaScript** kullanarak captive portal için özel bir ön yüz oluşturur, böylece gerçek bir giriş sayfası gibi görünmesini sağlar.

---

## 🚀 **Özellikler**

* 🛑 **Deauthentication Saldırısı**: Cihazları mevcut WiFi ağlarından ayırır.
* 🌐 **Captive Portal**: Kullanıcıların istemeden WiFi şifrelerini girdiği sahte giriş sayfası.
* 🎨 **Özel Ön Yüz**: Kullanıcı etkileşimi için **HTML**, **CSS** ve **JavaScript** kullanılarak yapılmıştır.
* 📡 **ESP32 Entegrasyonu**: Güçlü ve uygun fiyatlı ESP32 modülüyle WiFi hacking.

---

## 🛠️ **Kurulum ve Yükleme**

### 1️⃣ **Depoyu Klonlayın**

```bash
git clone https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal.git
cd IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal
```

### 2️⃣ **Gerekli Kütüphaneleri Yükleyin**

ESP32'yi programlamak için gerekli olan kütüphanelerin ve araçların yüklü olduğundan emin olun:

* **ESP32 Arduino Çekirdek Kitaplığı**: [Kurulum Kılavuzu](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)

### 3️⃣ **Kodu ESP32'ye Yükleyin**

1. `esp32_deauth_attack.ino` dosyasını Arduino IDE'nizde açın.
2. ESP32'nizi USB aracılığıyla bilgisayarınıza bağlayın.
3. Araçlar > Kart menüsünden ESP32 kartını seçin.
4. **Yükle** butonuna tıklayın.

### 4️⃣ **Captive Portal'ı Özelleştirin**

* Captive portal dosyaları `html/` klasöründe yer almaktadır. 🎨
* Tasarımı, **HTML**, **CSS** ve **JavaScript** kullanarak istediğiniz gibi kolayca düzenleyebilirsiniz.

---

## ⚡ **Saldırıyı Çalıştırma**

1. **Deauthentication Saldırısını Başlatın**: 📶 Cihazları orijinal WiFi ağından ayırın.
2. **Sahte AP'yi Başlatın**: 🖧 Sahte bir erişim noktası yayınlayın.
3. **Captive Portal Kullanımı**: 🌐 Kullanıcılar yeniden bağlanmaya çalıştığında, onları sahte bir giriş sayfasına yönlendirin.
4. **WiFi Şifrelerini Yakalama**: 🔐 Kullanıcılar tarafından girilen şifreler ESP32'de kaydedilir.

---

## 📂 **Dahil Edilen Dosyalar**

* `esp32_deauth_attack.ino`: Deauthentication saldırısının ana kodu.
* `html/`: Captive portal için gerekli tüm dosyalar (HTML, CSS, JavaScript).
* `README.md`: Genel bakış, kurulum talimatları ve kullanım bilgileri.

---

## 🔗 **Nasıl Çalışır**

1. **Deauthentication Saldırısı**: ESP32, cihazları orijinal ağlarından ayırmak için deauth paketleri gönderir.
2. **Sahte Erişim Noktası**: Cihazlar bağlantıyı kaybettikten sonra, ESP32, gerçek ağla benzer bir SSID'ye sahip sahte bir AP yayınlar.
3. **Captive Portal**: Kullanıcılar sahte AP'ye bağlanmaya çalıştığında, onları şifre girmeleri için sahte bir giriş sayfasına yönlendirir.
4. **Şifreler Kaydedilir**: Kullanıcıların girdiği şifreler ESP32 üzerinde kaydedilir.

---

## 💻 **Kullanılan Teknolojiler**

* **ESP32**: Düşük maliyetli WiFi modülü.
* **HTML**: Captive portal için yapı.
* **CSS**: Kullanıcı dostu portal arayüzü için stil.
* **JavaScript**: Kullanıcı etkileşimlerini ve form gönderimlerini işler.

---

## 🚧 **Gelecek İyileştirmeler**

* 🔒 Şifrelerin güvenli bir şekilde iletilmesi için şifreleme eklemek.
* 📊 Yakalanan şifreleri depolamak için bir log dosyası oluşturmak.
* 🔧 Deauthentication saldırılarının doğruluğunu artırmak.

---

## 👨‍💻 **Katkıda Bulunma**

Bu projeyi geliştirmek ister misiniz? Depoyu çatallayarak, değişiklik yaparak ve bir pull request göndererek katkıda bulunabilirsiniz. Katkılar her zaman hoş karşılanır! 🛠️

---

## 📝 **Lisans**

Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakabilirsiniz. 📜

---

## ⚠️ **Uyarı**

Bu proje sadece **eğitim ve etik test amaçlıdır**. **Bu kodu** herhangi bir WiFi ağına hedef almak için **ağ sahibi tarafından açıkça izin verilmediği sürece** kullanmayın. Her zaman yerel yasa ve yönetmeliklere uyun.

---

### 📦 **Depo Etiketleri**

```
ESP32, Evil Twin, WiFi Hacking, Deauthentication, Captive Portal, HTML, CSS, JavaScript, Siber Güvenlik, Etik Hacking, ESP32 WiFi, IoT, WiFi Pentesting
```

---
