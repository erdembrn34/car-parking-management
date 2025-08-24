# Parking Management System 🚗🏍️🚲

Bu proje, basit bir **Araç Otopark Yönetim Sistemi**'dir. Python
kullanılarak geliştirilmiştir ve araçların giriş/çıkış işlemlerini, park
edilen araçları, boş park yerlerini ve park ücretlerini yönetmeyi
sağlar.

------------------------------------------------------------------------

## 📌 Özellikler

-   **Araç Girişi**\
    Kullanıcıdan araç numarası, türü (bisiklet, motosiklet, araba), araç
    adı, sahibinin adı, tarih ve saat bilgisi alır.

-   **Araç Çıkışı (Silme)**\
    Parktan çıkış yapan araç bilgilerini kayıtlardan siler.

-   **Park Halindeki Araçları Görüntüleme**\
    Tüm kayıtlı araçları tablo formatında listeler.

-   **Boş Park Yerlerini Görüntüleme**\
    Bisiklet, motosiklet ve araba için kalan park kapasitesini gösterir.

-   **Ücret Tablosu**

    -   Bisiklet: 20 Rs / Saat\
    -   Motosiklet: 40 Rs / Saat\
    -   Araba: 60 Rs / Saat

-   **Fatura Oluşturma**\
    Araç park süresine göre ücret hesaplar. %18 ek vergi uygular.

-   **Programdan Çıkış**\
    Kullanıcı programı sonlandırabilir.

------------------------------------------------------------------------

## 🚀 Çalıştırma

1.  Python 3 yüklü olduğundan emin olun.
2.  Dosyayı `parking_system.py` adıyla kaydedin.
3.  Terminal veya Komut Satırında çalıştırın:

``` bash
python parking_system.py
```

------------------------------------------------------------------------

## 📖 Kullanım Menüsü

Program çalıştığında şu menü gelir:

    1. Vehicle Entry
    2. Remove Entry
    3. View Parked Vehicle
    4. View Left Parking Space
    5. Amount Details
    6. Bill
    7. Close Programme

------------------------------------------------------------------------

## 🔧 Teknik Detaylar

-   **Veriler** listeler üzerinde saklanır (`Vehicle_Number`,
    `Vehicle_Type`, `Owner_Name`, vb.).\
-   **Kapasite sınırları**:
    -   Bisiklet: 78
    -   Motosiklet: 100
    -   Araba: 250\
-   **Try/Except yapısı** ile hata durumlarında program tekrar çalışır.

------------------------------------------------------------------------

## 📌 Örnek Kullanım

    Select option: 1
    Enter vehicle number (XXXX-XX-XXXX) - AB12-CD-3456
    Enter vehicle type (Bicycle=A/Bike=B/Car=C): b
    Enter vehicle name - Intruder
    Enter owner name - Ali
    Enter Date (DD-MM-YYYY) - 24-08-2025
    Enter Time (HH:MM:SS) - 15:22:00

    Record detail saved ✅

------------------------------------------------------------------------

## 📜 Lisans

Bu proje eğitim amaçlı geliştirilmiştir. Serbestçe kullanılabilir.
