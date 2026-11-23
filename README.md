# Dort

**Tek uygulama. Bütün belgeler.**

Dort, Windows için **ücretsiz**, **internet olmadan çalışan**, yerli bir ofis programıdır. Yazı belgeleri, hesap
tabloları, sunular, PDF'ler, LaTeX ve daha fazlası tek pencerede açılır. Microsoft Office gerekmez. Lisans anahtarı,
hesap, abonelik ve reklam yoktur.

Geliştiren: **Enes İsa Göktaş** (bilgisayar mühendisliği öğrencisi).

---

## İndir

| | |
|---|---|
| **Kurulum dosyası** | [**Dort-Kurulum-1.2.0.exe**](https://github.com/Enesisagoktas/Dort-indir/releases/latest/download/Dort-Kurulum-1.2.0.exe) (yaklaşık 106 MB) |
| Sürüm | 1.2.0 (23 Kasım 2026) |
| Sistem | Windows 10 ya da 11, 64 bit. Yaklaşık 500 MB boş disk alanı |
| Ücret | Ücretsiz |

Bütün sürümler: [Sürümler (Releases)](https://github.com/Enesisagoktas/Dort-indir/releases)

> Dort'un resmî indirme adresi yalnız bu sayfadır. Başka bir yerden gelen kurulum dosyasını kullanmayın.

## Kurulum (adım adım)

1. Yukarıdaki bağlantıdan **Dort-Kurulum-1.2.0.exe** dosyasını indirin.
2. İndirilen dosyaya çift tıklayın.
3. Windows mavi bir pencereyle **"Windows kişisel bilgisayarınızı korudu"** diyebilir. Bu, dosyanın zararlı olduğu
   anlamına gelmez: Dort'un henüz ücretli bir kod imzalama sertifikası yoktur, bu yüzden Windows yayımcıyı tanımaz.
   **Ek bilgi**'ye, sonra **Yine de çalıştır**'a tıklayın. (İsterseniz önce aşağıdaki "İndirdiğiniz dosyayı doğrulama"
   adımını uygulayın.)
4. Kurulum dilini seçin (Türkçe ya da İngilizce) ve **İleri** deyin.
5. Hangi dosya türlerinin Dort ile açılacağını işaretleyin. İşaretlemedikleriniz değişmez; sonradan
   **Dosya > Seçenekler > Dosya türleri** sayfasından değiştirebilirsiniz.
6. **Kur**'a basın. Kurulum yönetici izni istemez ve yalnız sizin kullanıcı hesabınıza kurulur.
7. **Bitir**'e basın. "Dort'u başlat" kutusu işaretliyse Dort açılır.

**Güncelleme:** yeni sürümün kurulum dosyasını indirip aynı şekilde çalıştırın; eskisinin üzerine kurulur, ayarlarınız
korunur.

**Kaldırma:** Ayarlar > Uygulamalar > Yüklü uygulamalar > Dort > Kaldır. Dort'un değiştirdiği dosya türleri eski
hâline döner. Ayarlarınız ve kişisel sözlüğünüz silinmez.

> Sürüm numarası hakkında: 1.2.0 **en yeni** sürümdür. Daha önce elden dağıtılmış 2.0.0 ve 2.1.0 numaralı deneme
> kurulumları eskidir; numaralandırma yeniden başlatılmıştır.

### İndirdiğiniz dosyayı doğrulama (isteğe bağlı)

Her sürümün yanında bir `.sha256` dosyası bulunur. İndirdiğiniz dosyanın özgün olduğunu şöyle denetlersiniz:

1. Başlat menüsüne **PowerShell** yazıp açın.
2. Şu komutu, dosyayı indirdiğiniz klasörde çalıştırın:

   ```powershell
   Get-FileHash .\Dort-Kurulum-1.2.0.exe -Algorithm SHA256
   ```

3. Çıkan değer aşağıdakiyle aynı olmalıdır (büyük küçük harf fark etmez):

   ```
   8372efa782bd1dd9652100f7e1e711e292336be00f2722cc321287c0249aab1b
   ```

Değer farklıysa dosyayı çalıştırmayın ve yeniden bu sayfadan indirin.

---

## Neler yapabilir?

| Dosya | Ne yapabilirsiniz |
|---|---|
| Word belgeleri (`.docx`, `.doc`, `.rtf`, `.odt`) | Yazma, düzenleme, kaydetme; tablo, resim, üst ve alt bilgi, içindekiler; PDF'e aktarma |
| Excel tabloları (`.xlsx`, `.xlsm`, `.csv`) | Düzenleme ve kaydetme; 200'den fazla işlev (Türkçe adlarıyla), sıralama, süzme. `.xls` açılır, `.xlsx` olarak kaydedilir |
| PowerPoint sunuları (`.pptx`, `.ppsx`) | Açma, metinleri ve notları düzenleme, slayt ekleme ve sıralama; slayt gösterisi ve sunucu görünümü |
| PDF | Okuma, arama; açıklama ve vurgu, form doldurma; sayfaları birleştirme, bölme, döndürme; karartma, filigran, küçültme |
| LaTeX (`.tex`) | Yazarken yanda sayfa önizlemesi (Dort'un kendi dönüştürücüsü), hata listesi, PDF'e aktarma |
| Markdown, düz metin, kod dosyaları | Düzenleme; Markdown için canlı önizleme |
| Web sayfaları (`.html`) | Görüntüleme ve kaynak kodunu düzenleme; internet varsayılan olarak kapalıdır |
| UYAP belgeleri (`.udf`) | Açma; Word ya da PDF olarak kaydetme |
| e-Fatura, e-Arşiv, e-İrsaliye (UBL-TR `.xml`) | Okunur görünüm, toplam denetimi, PDF olarak kaydetme |
| Görseller (`.png`, `.jpg`, `.webp` ...) | Görüntüleme; kırpma, boyutlandırma, döndürme |

Ayrıca: Türkçe ve İngilizce arayüz, açık ve koyu tema, Türkçe yazım denetimi, resmî yazı ve dilekçe şablonları,
"tutarı yazıyla" ekleme, belge karşılaştırma, otomatik kurtarma.

### Bilmeniz gereken sınırlar

Dort dürüst olmayı tercih eder; şunlar **yoktur** ya da sınırlıdır:

- Makrolar çalıştırılmaz (dosyada saklanır).
- Hesap tablosunda grafik ve özet tablo oluşturulamaz; dosyadaki grafikler gösterilir ve korunur.
- Sunularda şekil çizme, animasyon, ses ve video yoktur.
- PDF'te metin tanıma (OCR) ve e-imza yoktur.
- LaTeX önizlemesi tam bir TeX motoru değildir; TikZ çizimleri gösterilmez.
- Eski PowerPoint (`.ppt`) ve OpenDocument tablo (`.ods`) dosyaları açılmaz.
- Belgede "değişiklikleri izle" kipi ve dipnot ekleme yoktur (var olan izlenen değişiklikler gösterilir, kabul ya da reddedilir).

---

## Çevrimdışı ve gizli

- Dort kendiliğinden internete bağlanmaz: güncelleme denetimi, kullanım istatistiği ve hata raporu gönderimi yoktur.
- Belgeleriniz bilgisayarınızda kalır. Hesap açmanız gerekmez.
- Ayrıntılar: [Gizlilik ve KVKK bilgilendirmesi](GIZLILIK-KVKK.md)

## Yapay zekâ asistanı (isteğe bağlı)

- Dort'un içinde belgenizi okuyup düzenleyebilen bir asistan paneli vardır. **Siz bir yapay zekâ bağlamadıkça kapalıdır
  ve hiçbir veri gönderilmez.**
- 34 internet sağlayıcısından birini kendi API anahtarınızla ya da bilgisayarınızda çalışan 9 yerel programdan birini
  (ör. Ollama, LM Studio) bağlayabilirsiniz. Hiçbir sağlayıcı öncelikli değildir; model listesi bağladığınız
  sağlayıcıdan gelir.
- Dort bir yapay zekâ hizmeti, anahtar ya da kota **sağlamaz**. İnternetteki bir sağlayıcıyı kullanırsanız
  yazdıklarınız ve belge içeriği o sağlayıcıya gider.

## Güvenlik

- Dort her açılışta kendi program dosyalarının yayımlanan özgün dosyalar olduğunu denetler; değiştirilmiş bir kopya
  uyarı verir.
- Her sürüm yayımlanmadan önce Microsoft Defender ile taranır.
- Program paketlenmiş ya da gizlenmiş değildir, yönetici yetkisi istemez, Windows ile birlikte başlamaz.
- Sınır: kod imzalama sertifikası olmadığı için Windows yayımcıyı "bilinmiyor" gösterir. Bu yüzden dosyayı yalnız bu
  sayfadan indirin ve isterseniz SHA-256 değerini karşılaştırın.

---

## Belgeler

- [Gizlilik ve KVKK bilgilendirmesi](GIZLILIK-KVKK.md)
- [Kullanım koşulları ve telif](KULLANIM-KOSULLARI.md)
- [Üçüncü taraf bileşenler ve lisansları](UCUNCU-TARAF-LISANSLARI.md)
- [Sürüm notları](SURUM-NOTLARI.md)

## İletişim

Telif hakkı, izin, iş birliği ve basın için: **enesisagoktas@gmail.com**

Hata bildirimi ve öneri için bu sayfadaki [Issues](https://github.com/Enesisagoktas/Dort-indir/issues) bölümünü ya da
aynı e-posta adresini kullanabilirsiniz.

---

© 2026 Enes İsa Göktaş. Tüm hakları saklıdır. Dort'un kaynak kodu yayımlanmamaktadır; bu sayfada yalnız kurulum dosyası
ve belgeler bulunur.
