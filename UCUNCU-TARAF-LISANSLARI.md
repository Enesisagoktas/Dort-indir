# Üçüncü Taraf Bileşenler ve Lisansları

Dort 1.2.0'ın kurulum dosyası, aşağıdaki açık kaynak bileşenleri içerir. Her bileşen kendi lisansına tabidir; lisans
metinlerine ve kaynak kodlarına verilen bağlantılardan ulaşabilirsiniz. Dort'un kendi kodu bu lisansların kapsamında
değildir (bkz. [Kullanım koşulları](KULLANIM-KOSULLARI.md)).

| Bileşen | Sürüm | Lisans | Kaynak ve lisans metni |
|---|---|---|---|
| Qt 6 (Qt Core, Gui, Widgets, Svg, PrintSupport, Network, Pdf) | 6.12 | LGPL v3 | https://www.qt.io/download-open-source · https://www.gnu.org/licenses/lgpl-3.0.html |
| Qt for Python (PySide6, Shiboken6) | 6.12 | LGPL v3 | https://code.qt.io/cgit/pyside/pyside-setup.git/ |
| Qt WebEngine (Chromium 140 tabanlı) | 6.12 | LGPL v3; Chromium ve alt bileşenleri BSD, MIT, Apache 2.0 ve benzeri lisanslar | https://doc.qt.io/qt-6/qtwebengine-licensing.html · https://chromium.googlesource.com/chromium/src/+/main/LICENSE |
| Python çalışma zamanı | 3.13 | PSF License | https://docs.python.org/3/license.html |
| OpenSSL | 3.x | Apache 2.0 | https://www.openssl.org/source/license.html |
| PDFium | 159 | BSD 3 Maddeli / Apache 2.0 | https://pdfium.googlesource.com/pdfium/ |
| pypdfium2 | 5.15 | BSD 3 Maddeli / Apache 2.0 | https://github.com/pypdfium2-team/pypdfium2 |
| lxml (libxml2 ve libxslt ile) | 6.1 | BSD 3 Maddeli; libxml2 ve libxslt MIT | https://lxml.de/ |
| Pillow | 13.0 | MIT-CMU | https://github.com/python-pillow/Pillow/blob/main/LICENSE |
| olefile | 0.47 | BSD 2 Maddeli | https://github.com/decalage2/olefile |
| spylls (yazım denetimi) | 0.1.7 | MPL 2.0 | https://github.com/zverok/spylls |
| Türkçe sözlük (hunspell-tr, tdd-ai) | 1.1.1 | MPL 2.0 | https://github.com/tdd-ai/hunspell-tr |
| İngilizce sözlük (SCOWL, en_US) | 2020.12.07 | SCOWL lisansı (BSD benzeri) | http://wordlist.aspell.net/ |
| Fluent UI System Icons | | MIT (Microsoft) | https://github.com/microsoft/fluentui-system-icons |
| libffi, Expat, bzip2, XZ/liblzma, zlib, SQLite (Python ile gelen) | | MIT ve benzeri izin verici lisanslar | https://docs.python.org/3/license.html#licenses-and-acknowledgements-for-incorporated-software |
| Nuitka çalışma zamanı | 4.3 | Apache 2.0 | https://nuitka.net/ |
| Microsoft Visual C++ çalışma zamanı | | Microsoft yeniden dağıtım koşulları | https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist |

## LGPL bileşenleri hakkında

Qt ve Qt for Python kitaplıkları GNU Kısıtlı Genel Kamu Lisansı (LGPL) sürüm 3 ile dağıtılır.

- Bu kitaplıklar kurulum klasöründe **ayrı dosyalar** olarak durur (`qt6*.dll`, `PySide6` ve `shiboken6` klasörleri).
  Dort bunları değiştirmeden kullanır.
- LGPL'nin tanıdığı hak gereği, bu kitaplıkları kendi derlediğiniz uyumlu sürümleriyle değiştirebilirsiniz. Bu durumda
  Dort'un bütünlük denetimi dosyaların değiştiğini bildirir; program çalışmaya devam eder.
- Kitaplıkların kaynak kodu yukarıdaki bağlantılardan indirilebilir. Erişemezseniz, ilgili sürümün kaynak kodunu
  edinmenize yardımcı olmam için **enesisagoktas@gmail.com** adresine yazabilirsiniz.
- LGPL v3 metni: https://www.gnu.org/licenses/lgpl-3.0.html · GPL v3 metni: https://www.gnu.org/licenses/gpl-3.0.html

## MPL bileşenleri hakkında

spylls ve Türkçe sözlük Mozilla Kamu Lisansı (MPL) 2.0 ile dağıtılır; değiştirilmeden kullanılır. Lisans metni:
https://www.mozilla.org/MPL/2.0/


---

Bu listede bir eksik ya da yanlış görürseniz lütfen bildirin: **enesisagoktas@gmail.com**
