# Gizlilik ve KVKK Bilgilendirmesi

Son güncelleme: 23 Kasım 2026 · Dort 1.2.0

Bu metin, Dort'u indiren ve kullanan kişileri 6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) kapsamında
bilgilendirmek için hazırlanmıştır. Kısa özeti şudur: **Dort sizden kişisel veri toplamaz.** Program bilgisayarınızda
çalışır; belgeleriniz, ayarlarınız ve kullanım bilgileriniz geliştiriciye ya da başka birine gönderilmez.

## 1. Kim tarafından hazırlanmıştır

Dort'un geliştiricisi ve bu sayfanın sahibi: Enes İsa Göktaş.
İletişim: **enesisagoktas@gmail.com**

## 2. Dort hangi verileri toplar?

Hiçbirini. Dort'ta şunlar **yoktur**:

- Kullanıcı hesabı, kayıt ya da etkinleştirme
- Kullanım istatistiği (telemetri)
- Hata ya da çökme raporu gönderimi
- Güncelleme denetimi
- Reklam ve izleme

Program kendiliğinden internete bağlanmaz. Bu nedenle geliştirici, Dort'u kullanırken oluşturduğunuz ya da açtığınız
hiçbir bilgiye erişemez ve bu bilgiler bakımından kişisel veri işlememektedir.

## 3. Bilgisayarınızda saklananlar

Aşağıdaki bilgiler yalnız sizin bilgisayarınızda, sizin Windows kullanıcı hesabınızın altında durur. Hiçbir yere
gönderilmez; dilediğiniz zaman silebilirsiniz.

| Ne | Nerede | Not |
|---|---|---|
| Ayarlar ve son açılan dosyaların listesi | Windows kayıt defteri (`HKCU\Software\Dort`) | Dosyaların kendisi değil, yalnız yolları |
| Kurtarma kopyaları | `%LOCALAPPDATA%\Dort\recovery` | Çökme hâlinde belgenizi geri getirmek içindir; belge içeriğini taşır ve şifrelenmez |
| Günlükler | `%LOCALAPPDATA%\Dort\logs` | Hata ayıklama kayıtları; gönderilmez |
| Kişisel sözlük, kendi şablonlarınız, imza resimleri | `%APPDATA%\Dort` | |
| Yapay zekâ bağlantıları ve API anahtarları | `%APPDATA%\Dort` | Yalnız asistanı kullanırsanız oluşur. Anahtarlar Windows'un kullanıcıya özel şifrelemesiyle (DPAPI) saklanır |
| Web sayfası ve oyun kayıtları | `%APPDATA%\Dort\web-profile` | Açtığınız yerel HTML sayfalarının kendi kayıtları |

Dort'u kaldırdığınızda program dosyaları silinir; yukarıdaki kişisel dosyalarınız (ayarlar, sözlük, şablonlar) siz
silene kadar kalır.

## 4. İnternet ne zaman kullanılır?

Yalnız sizin açık isteğinizle, şu durumlarda:

1. **Yapay zekâ asistanı.** Asistan, siz bir bağlantı eklemedikçe kapalıdır. İnternetteki bir sağlayıcıyı kendi API
   anahtarınızla bağlayıp mesaj gönderdiğinizde; yazdığınız istek, açık belgenin ilgili içeriği ve (açıksa) ekran
   görüntüsü **sizin seçtiğiniz sağlayıcının sunucusuna** gönderilir. Bu aktarım sizinle o sağlayıcı arasındadır;
   verilerinizin orada nasıl işlendiği sağlayıcının kendi sözleşmesine ve gizlilik politikasına tabidir. Sağlayıcı
   yurt dışında olabilir. Geliştirici bu veriye erişmez. Bilgisayarınızda çalışan yerel bir yapay zekâ programı
   kullanırsanız veri bilgisayarınızdan çıkmaz.
2. **"İnternete izin ver".** Açtığınız bir web sayfası internetten içerik istiyorsa ve siz izin verirseniz, o sayfa
   ayrı bir pencerede internete bağlanır.
3. **Bağlantılara tıklamak.** Bir belgedeki bağlantıya, "GitHub Sayfası" ya da "Bağış Yap" komutlarına tıkladığınızda
   varsayılan tarayıcınız açılır.

## 5. Bu sayfadan indirme

Kurulum dosyası GitHub üzerinden sunulur. Sayfayı ziyaret ettiğinizde ve dosyayı indirdiğinizde IP adresi gibi teknik
veriler GitHub (GitHub, Inc., ABD) tarafından kendi gizlilik bildirimi kapsamında işlenir. Geliştirici indirenlerin
kim olduğunu göremez; yalnız toplam indirme sayısını görebilir.

## 6. Bana e-posta ya da geri bildirim gönderirseniz

Bana e-posta yazdığınızda ya da bu sayfada bir kayıt (Issue) açtığınızda paylaştığınız bilgiler (adınız, e-posta
adresiniz, kullanıcı adınız, mesajınızın içeriği) yalnız size yanıt vermek, bildirdiğiniz sorunu çözmek ve
telif, izin ya da iş birliği taleplerini değerlendirmek amacıyla kullanılır.

- **Hukuki sebep:** talebinizin yerine getirilmesi için işlemenin gerekli olması ve meşru menfaat (KVKK md. 5/2).
- **Aktarım:** bu bilgiler başkasıyla paylaşılmaz, satılmaz. E-posta hizmeti (Google) ve GitHub altyapısı kullanıldığı
  için veriler bu hizmet sağlayıcıların sunucularında bulunur.
- **Saklama:** yazışmalar, talep sonuçlandıktan sonra gerekli olduğu sürece saklanır; silinmesini her zaman
  isteyebilirsiniz.
- Lütfen mesajlarınızda gerekmedikçe kimlik numarası, sağlık bilgisi gibi özel nitelikli veriler paylaşmayın; sorun
  bildirirken belgenizin kişisel bilgi içermeyen bir örneğini gönderin.

## 7. Haklarınız

KVKK'nın 11. maddesi uyarınca; kişisel verinizin işlenip işlenmediğini öğrenme, işlenmişse bilgi isteme, amacına uygun
kullanılıp kullanılmadığını öğrenme, yurt içinde ya da yurt dışında aktarıldığı kişileri bilme, eksik ya da yanlış
işlenmişse düzeltilmesini, silinmesini ya da yok edilmesini isteme, bu işlemlerin aktarıldığı kişilere bildirilmesini
isteme, otomatik sistemlerle analiz sonucu aleyhinize bir sonuç çıkmasına itiraz etme ve zarara uğramanız hâlinde
giderilmesini isteme haklarına sahipsiniz.

Başvurularınızı **enesisagoktas@gmail.com** adresine iletebilirsiniz. Başvurular en geç otuz gün içinde yanıtlanır.

## 8. Çocuklar

Dort her yaştan kullanıcı tarafından kullanılabilir; veri toplamadığı için çocuklardan da veri toplamaz.

## 9. Değişiklikler

Bu metin, programın davranışı değiştiğinde güncellenir. Güncel sürüm her zaman bu sayfadadır.

---

Bu metin bilgilendirme amaçlıdır ve hukuki danışmanlık yerine geçmez.
