# Sürüm Notları

## Dort 1.2.0 (23 Kasım 2026)

İlk herkese açık sürüm.

> 1.2.0 en yeni sürümdür. Daha önce elden dağıtılmış 2.0.0 ve 2.1.0 numaralı deneme kurulumları eskidir;
> numaralandırma yeniden başlatılmıştır.

**Genel**
- Lisans anahtarı ve etkinleştirme yoktur; kuran herkes kullanır.
- Bütün pencereler küçük ekranlara uyar: bir pencere ekranın en çok yarısını kaplar, uzun içerik sayfalara bölünür.
- Türkçe ve İngilizce arayüz, açık ve koyu tema.

**Dosya türleri**
- Word, Excel, PowerPoint, PDF, LaTeX, Markdown, düz metin ve kod, web sayfaları, UYAP `.udf`, e-Fatura ve görseller
  tek programda açılır. Ayrıntılı tablo: [README](README.md#neler-yapabilir).
- LaTeX dosyaları Dort'un kendi dönüştürücüsüyle yanda sayfa görünümünde önizlenir.
- "Belgeleri Dort ile açın" penceresiyle bütün dosya türleri tek adımda Dort'a bağlanır.

**Yapay zekâ asistanı (isteğe bağlı)**
- Bağlantı ekleme üç adımdır: sağlayıcı, anahtar, o sağlayıcının kendi listesinden model.
- 34 internet sağlayıcısı ve bilgisayarda çalışan 9 yerel program desteklenir; hiçbiri öncelikli değildir.
- Bağlantı eklenmedikçe hiçbir veri gönderilmez.

**Güvenlik**
- Program dosyaları her açılışta imzalı bir özet listesiyle denetlenir; değiştirilmiş kopya uyarı verir.
- Kurulum dosyasının yanında SHA-256 özeti yayımlanır.
- Her sürüm Microsoft Defender ile taranır.

**Bilinen sınırlar**
- Kod imzalama sertifikası yoktur; Windows yayımcıyı "bilinmiyor" gösterebilir.
- Makrolar çalıştırılmaz. Hesap tablosunda grafik oluşturulamaz. PDF'te metin tanıma (OCR) ve e-imza yoktur.
- Diğer sınırlar: [README](README.md#bilmeniz-gereken-sınırlar).

Sorun ve önerileriniz için: enesisagoktas@gmail.com
