# K-MES_AS-STAN-_PRO[README.md](https://github.com/user-attachments/files/33538469/README.md)
# 🐔 Kümes Asistanı (Küm-As)

Kümes Asistanı, modern hayvancılık ve akıllı tarım teknolojilerine odaklanan, kümes içi kritik çevre koşullarını anlık olarak izleyen ve otomasyon süreçlerini yöneten akıllı bir yönetim sistemidir.

Bu proje; tavuk ve diğer kümes hayvanlarının sağlığını korumak, verimliliği artırmak ve kümes yönetimini dijitalleştirmek amacıyla geliştirilmiştir.

## 🚀 Öne Çıkan Özellikler

- **Anlık Çevre Takibi:** Sıcaklık ve nem değerlerinin gerçek zamanlı izlenmesi.
- **Kaynak Yönetimi:** Yemlik ve suluk seviyelerinin kritik sınır kontrolü.
- **Akıllı Otomasyon:** 
  - Yüksek sıcaklıkta otomatik **Fan Sistemi** aktivasyonu.
  - İdeal ışık döngüsü için **Aydınlatma Kontrolü**.
- **Erken Uyarı Sistemi:** Sınır değerler aşıldığında sistem tarafından otomatik üretilen Türkçe uyarı logları.

## 🛠️ Kurulum ve Çalıştırma

### Gereksinimler
Projenin çalışabilmesi için bilgisayarınızda **Python 3.x** sürümünün kurulu olması yeterlidir. Herhangi bir harici kütüphane bağımlılığı bulunmamaktadır.

### Çalıştırma Adımları

1. Depoyu bilgisayarınıza kopyalayın veya indirin:
   ```bash
   git clone https://github.com/KULLANICI_ADINIZ/DEPO_ADINIZ.git
   cd DEPO_ADINIZ
   ```

2. Uygulamayı çalıştırın:
   ```bash
   python kumes_asistani.py
   ```

## 📂 Proje Yapısı

- `kumes_asistani.py`: Kümes simülasyonunu, eşik değer kontrollerini ve otomasyon mantığını içeren ana kaynak kod dosyası.
- `README.md`: Proje hakkında genel bilgileri ve kurulum adımlarını içeren doküman.

## 🔮 Gelecek Planları (Roadmap)

- [ ] Verilerin geriye dönük saklanması için **SQLite** veritabanı entegrasyonu.
- [ ] Grafiksel arayüz (GUI) veya **Flask** ile web tabanlı yönetim paneli.
- [ ] Gerçek sensörler (DHT11/DHT22 vb.) ve **Raspberry Pi / Arduino** donanım entegrasyonu.

## 📄 Lisans
Bu proje [MIT Lisansı](https://opensource.org/licenses/MIT) altında lisanslanmıştır.
