Bu projede, bir e-ticaret/restoran zincirine ait sipariş verileri Python kullanılarak analiz edilmiş, müşteri davranışları ve ciro metrikleri çıkarılmıştır.

## 🛠️ Kullanılan Teknolojiler
- **Python 3**
- **Pandas** (Veri temizleme ve manipülasyon)
- **Matplotlib & Seaborn** (Veri görselleştirme)
- **Google Colab** (Geliştirme ortamı)

## 📌 Yapılan İşlemler ve Analiz Adımları
1. **Veri Temizleme:** Fiyat sütunundaki özel karakterler (`$`) temizlenerek veri tipleri `float` formatına dönüştürüldü.
2. **Öznitelik Mühendisliği:** Miktar (`quantity`) ve birim fiyat (`item_price`) kullanılarak toplam harcama (`total_price`) sütunu oluşturuldu.
3. **İş Metrikleri Hesaplama:** Toplam sipariş sayısı, toplam ciro ve sipariş başına ortalama harcama (AOV) hesaplandı.
4. **Görselleştirme:** En çok satılan ve en çok ciro getiren ilk 5 ürün sütun grafikleriyle görselleştirildi.
