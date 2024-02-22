# TMP006 Sıcaklık Sensörü Örneği

Bu örnek uygulama, Texas Instruments Tiva4c mikrodenetleyici kartı üzerinde bulunan TMP006 adlı sıcaklık sensöründen veri okuma işlemini gerçekleştirir.

## Kod Açıklaması

Bu kod bloğu aşağıdaki işlevleri gerçekleştirir:

- I2C (Inter-Integrated Circuit) arayüzünü kullanarak, TMP006 sensöründen sıcaklık verisi okur.
- I2C arayüzü üzerinden TMP006 ile iletişim kurar ve sıcaklık değerlerini okur.
- Okunan sıcaklık değerini konsola yazdırır.

## Kullanılan Donanım ve Kütüphaneler

- Texas Instruments Tiva4c mikrodenetleyici kartı
- TMP006 sıcaklık sensörü
- TI-RTOS (TI Gerçek Zamanlı İşletim Sistemi)
- TI-DRIVERS Kütüphanesi
- I2C ve GPIO kütüphaneleri
