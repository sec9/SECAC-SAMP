# SECAC-SAMP
SECNINE, SA-MP hizmetleri için geliştirilen antihile eklentisi.

[![GitHub Release](https://img.shields.io/github/release/sec9/SECAC-SAMP.svg)](https://github.com/sec9/SECAC-SAMP/releases/latest) [![Download](https://img.shields.io/badge/downloads-+50k-%20brightgreen)](https://github.com/sec9/SECAC-SAMP/releases/latest)

# Bilinen Açıklar / Hatalar
- SECAC oyunun anti aliasing seçeneğinin devre dışı kalmasına ve oyunun pikselleşmesine sebep olabiliyor.
> Çözüm: **Bilgilendirmeler** kısmından bilgi edinerek D3D hook kullanımını kapatmanız gerekiyor.
- SECAC oyunun gölgelerini ve birkaç sisteminin devre dışı kalmasına sebep olabiliyor.
> Çözüm: **Bilgilendirmeler** kısmından bilgi edinerek çözebilirsiniz.
- SA-MP Addon entegreli bir oyunda /q kullanılırsa crash hatası alınabiliyor.
- CodsMP entegreli bir oyunda /time ve /weather komutları çalışmayabiliyor.
- Winebottler ile SECAC çalışmıyor.

# Bilgilendirmeler
- SECAC'nin D3D hook kullanmaması için oyun klasörünüzde **secac_nohook** adında boş bir metin belgesi oluşturabilirsiniz. (oyun performansını arttırabilir fakat /hitmarker komutunu kullanamazsınız)
- SECAC'nin oyun hatalarını düzeltmesini, performansını ve açılışını optimize etmesini durdurmak için oyun klasörünüzde **secac_nofix** adında boş bir metin belgesi oluşturabilirsiniz. (oyunun gölgelerini ve birkaç özelliğini aktif eder fakat performans düşüşü yaşanabilir)

# Komutlar
**/chatshot, /css**
> Oyunun sohbet görüntüsünü transparan bir şekilde PNG olarak kaydeder.

**/anticrasher**
> Oyunun çökme sorunlarını düzeltir.

**/fpsunlock**
> Oyundaki FPS limitini (90) kaldırır.

**/memoryfix**
> Oyundaki RAM kaynaklı geç yüklenmeyi (objeler, oyuncular, araçlar vb.) düzeltmek için oyunun kullanabileceği RAM değerini bilgisayarınıza uygun şekilde arttırır.

**/mousefix**
> Farenizin oyun içerisindeki X ve Y hassaslığını eşitleyerek, fare kontrolünde daha uygun hassaslığı sağlar.

**/motionblur [0-60]**
> Araç ile hızlanınca ekran blur efekti seviyesini belirler.

**/hitsound**
> Herhangi bir oyuncuya silah ile hasar verdiğinizde bildirim sesi çıkartır.

**/hitmarker**
> Herhangi bir oyuncuya silah ile hasar verdiğinizde ekranda bildirim işareti çıkartır.

**/removezeros**
> Sağ üstteki para göstergesindeki gereksiz 0'ları kaldırır. (dikkat! bu komutun açıkları aşağıda belirtilmiştir)
> Eğer para değeriniz 0'dan aşağıya düşer ise oyununuz çöker, yeniden girmeniz gerekir.

**/moneyborder [0-2]**
> Sağ üstteki para göstergesinin dışındaki siyahlığın kalınlığını belirler.

**/fov [30-100]**
> Kamera FOV değerini belirler.

**/aimfov [30-100]**
> Aim kamerasının FOV değerini belirler.

**/wheelfix**
> Araçların uzaktayken sadece tekerleklerinin gözükmesi sorununu düzeltir.

**/time [0-24]**
> Oyun içerisindeki saati değiştirir.

**/weather [0-255]**
> Oyun içerisindeki hava durumunu değiştirir.

**/info**
> FPS, Ping ve bazı render verilerini ekranın sağ üstünde gösterir.

**/carsiren**
> Aracın siren durumunu değiştirir. (LSPD için)

**/wheelie**
> Araçların ön kaldırmasını aktifleştirir veya pasifleştirir.

**/weaponreload**
> R tuşu ile silah mermisi yenileme sistemini aktifleştirir veya pasifleştirir.

**/disableneon**
> Neon objelerinin gözükmesini aktifleştirir veya pasifleştirir.
