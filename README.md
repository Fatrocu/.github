# Fatrocu'ya Hoş Geldiniz!

**Yapay Zeka Destekli, Açık Kaynaklı Yeni Nesil Muhasebe ve Fatura Otomasyonu**

Mali müşavirler ve muhasebe departmanları için manuel veri girişini tarihe karıştırıyoruz. Fatrocu; e-arşiv faturalarını, yazar kasa fişlerini ve makbuzları **yerelde (lokalde) çalışan hafif yapay zeka modelleriyle** saniyeler içinde analiz eder, Excel formatına çevirir ve Defter Beyan gibi sistemlere otomatik işler.

## Fatrocu Ekosistemi

Fatrocu tek bir uygulama değil, birbirine entegre çalışan, açık kaynaklı bir araçlar bütünüdür:

*   **[Fatrocu](https://github.com/Fatrocu/Fatrocu):** Ana masaüstü uygulamamız. Fatura okuma ve dönüştürme işlemlerinin yapıldığı, son kullanıcı dostu grafik arayüzlü (GUI) çekirdek projemiz.
*   **[Fatrocu-DB](https://github.com/Fatrocu/Fatrocu-DB):** Defter Beyan Portal otomasyon aracımız. İşlenen ve kategorize edilen faturaları tek tıkla resmi sisteme aktarır.
*   **[fatrocu-cli](https://github.com/Fatrocu/fatrocu-cli):** Geliştiriciler ve sistem yöneticileri için terminal üzerinden tam otomasyon (zero-click) sağlayan komut satırı aracımız. Cron job'lar ve scriptler ile entegrasyon için idealdir.

## Vizyon ve Yol Haritası: Fatrocu Web

Fatrocu çekirdeğini her zaman açık kaynak tutmaya kararlıyız. Ancak kurulum ve donanım yönetimiyle uğraşmak istemeyen kullanıcılar için **Fatrocu Web** yolda! 

Kurulum gerektirmeyen bu SaaS (Hizmet olarak Yazılım) sürümü ile faturalarınızı tarayıcı üzerinden sisteme yükleyebileceksiniz. **Edge AI** felsefemiz sayesinde veri işleme süreçleri devasa bulut masrafları yaratmadan, hızla ve uygun maliyetlerle çözülecek.

## Teknolojilerimiz

Fatrocu ekosistemi, performans ve modernliği bir araya getiren güçlü bir teknoloji yığını üzerinde yükselir:
*   **Çekirdek Sistemler:** Rust ve Python
*   **Yapay Zeka (AI):** Düşük donanımlarda bile yüksek doğruluk veren, optimize edilmiş hafif görüntü işleme (Vision) modelleri.
