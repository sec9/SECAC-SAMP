# SA-MP için SECAC eklentisi

[![GitHub Release](https://img.shields.io/github/release/sec9/SECAC-SAMP.svg)](https://github.com/sec9/SECAC-SAMP/releases/latest) [![Download](https://img.shields.io/github/downloads/sec9/SECAC-SAMP/total.svg?r3)](https://github.com/sec9/SECAC-SAMP/releases/latest)

SECNINE SA-MP hizmetleri için SECAC eklentisi.

# Bilinen Açıklar / Hatalar
- SA-MP Addon entegreli bir oyunda /q kullanılırsa crash hatası alınıyor.
- CodsMP entegreli bir oyunda /time ve /weather komutları çalışmıyor.
- Winebottler entegreli bir oyunda SECAC çalışmıyor.

# Bilgilendirmeler
- SECAC'nin D3D hook kullanmaması için oyun klasörünüzde secac_nohook.set adında boş bir dosya oluşturabilirsiniz. (oyun performansını arttırabilir fakat /hitmarker komutunu kullanamazsınız)

# Komutlar
> /anticrasher
- Oyunun çökme sorunlarını düzeltir.
> /fpsunlock
- Oyundaki FPS limitini (90) kaldırır.
> /memoryfix
- Oyundaki RAM kaynaklı geç yüklenmeyi (objeler, oyuncular, araçlar vb.) düzeltmek için oyunun kullanabileceği RAM değerini bilgisayarınıza uygun şekilde arttırır.
> /mousefix
- Farenizin oyun içerisindeki X ve Y hassaslığını eşitleyerek, fare kontrolünde daha uygun hassaslığı sağlar.
> /motionblur [0-60]
- Araç ile hızlanınca ekran blur efekti seviyesini belirler.
> /hitsound
- Herhangi bir oyuncuya silah ile hasar verdiğinizde bildirim sesi çıkartır.
> /hitmarker
- Herhangi bir oyuncuya silah ile hasar verdiğinizde ekranda bildirim işareti çıkartır.
> /removezeros
- Sağ üstteki para göstergesindeki gereksiz 0'ları kaldırır. (dikkat! bu komutun açıkları aşağıda belirtilmiştir)
  - Eğer para değeriniz 0'dan aşağıya düşer ise oyununuz çöker, yeniden girmeniz gerekir.
> /moneyborder [0-2]
- Sağ üstteki para göstergesinin dışındaki siyahlığın kalınlığını belirler.
> /fov [30-100]
- Kamera FOV değerini belirler.
> /aimfov [30-100]
- Aim kamerasının FOV değerini belirler.
> /wheelfix
- Araçların uzaktayken sadece tekerleklerinin gözükmesi sorununu düzeltir.
> /time [0-24]
- Oyun içerisindeki saati değiştirir.
> /weather [0-255]
- Oyun içerisindeki hava durumunu değiştirir.
> /chatshoot
- Oyunun sohbet görüntüsünü transparan bir şekilde PNG olarak kaydeder.

# Güncel izinli dosya listesi

> CLEO
- Artık izinli cleo listesi yayınlanmıyor.
