5\. BÖLÜM

<img src="media/image1.png" style="width:0.15in;height:0.13171in" />SIKILAŞTIRMA
TEDBİRLERİ

# <img src="media/image2.png" style="width:0.29in;height:0.12171in" />İşletim Sistemi Sıkılaştırma Tedbirleri

## Amaç

> Bu güvenlik tedbiri ana başlığının amacı, işletim sistemi güvenlik
> sıkılaştırmaları çerçevesinde ele alınan tedbir listeleri ve denetim
> sorularını belirlemektir. “İşletim Sistemi Sıkılaştırma Tedbirleri”
> ana başlığı kapsamında ele alınan güvenlik tedbirleri alt başlıkları
> aşağıda yer almaktadır.

- Genel Sıkılaştırma Tedbirleri

- Linux İşletim Sistemi Sıkılaştırma Tedbirleri

- Windows İşletim Sistemi Sıkılaştırma Tedbirleri

## Genel Sıkılaştırma Tedbirleri

> Tedbirler

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 48%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.1.1</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Kurulum Güvenliği</p>
</blockquote></td>
<td><blockquote>
<p>Kurulum esnasında kullanılan işletim sistemi dosyalarının özet
bilgisi orijinal dağıtıcı özet değerleriyle teyit edilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.2</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Servis Güvenliği</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuların normal işleyişi için gerekli olmayan tüm servisler
kapatılmalıdır. Sistemlerde çalışan servisler ihtiyaçları olan en az
yetki ile çalışmalıdır. Servis kullanıcılarının yetkileri ayrıca
kısıtlanmalıdır. Servislerin döndüğü başlık bilgileri (banner) bilgi
ifşasına yol açmayacak şekilde değiştirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.3</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Güncel İşletim Sistemi ve Uygulamaların Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Güncel ve güvenlik desteği devam eden işletim sistemleri
kullanılmalıdır. Uygulama sürümleri periyodik olarak kontrol
edilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.4</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Şifreli Haberleşen Servislerin Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Şifresiz kimlik doğrulama ve haberleşme kullanan servisler (Telnet,
FTP, rlogin, HTTP, SMTP vb.), eğer varsa şifreli haberleşme imkânı
sağlayan muadilleri (SSH, SFTP, HTTPS, SMTPS vb.) ile
değiştirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.5</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Parola Politikasının Belirlenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Tüm makinelerde kullanıcı parolaları için güçlü bir parola politikası
belirlenmelidir. Kullanıcılar ilk girişten sonra parolalarını
değiştirmeye zorlanmalı ve parolaların belirli bir süreden sonra
geçerliliğini yitirip yenilenmesi sağlanmalıdır. Ayrıca belirli bir
sayıda hatalı giriş denemesinden sonra kullanıcı hesapları
kilitlenmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.6</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Son Kullanıcı Bilgisayarlarında Ağ Erişiminin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Kullanıcı bilgisayarlarında, bilgisayara ağ üzerinden erişim yetkisi,
sadece yönetici hesapları ve uzak masaüstü kullanıcıları veya grupları
ile sınırlandırılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.7</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Hata ve Sorun Bilgilerinin Üretici ile Paylaşılmaması</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemi kurulumu ile gelen hata ve sorun bilgilerinin üretici
ile paylaşılması özelliği pasif hale getirilmelidir.</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 48%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.1.8</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Kablosuz Ağ Arayüzlerinin Kapatılması</p>
</blockquote></td>
<td><blockquote>
<p>Tüm sunucularda kullanılmayan kablosuz ağ arayüzleri pasif hale
getirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.9</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sistem Üzerinde Düzenli Olarak Zafiyet ve Zararlı Yazılım Taraması
Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Sistemde düzenli olarak zafiyet taraması yapılmalı ve bu zafiyetlerin
yönetimi gerçekleştirilmelidir. Sistem zararlı yazılımlara karşı düzenli
olarak taranmalıdır.</p>
<p>Bk. Tedbir No: 3.1.5.1</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.10</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Yerel Güvenlik Duvarı Ayarlarının Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Bk. Tedbir No: 3.1.6.11</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.11</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sunucularda Zaman Senkronizasyonunun Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Sunucularda ilgili NTP ayarlamaları yapılarak tüm sunucularda zaman
senkronizasyonu sağlanmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.12</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Güvenli Süreç (Process) İşleme Ayarlarının Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemlerinin DEP, ASLR, XD/NX gibi savunma özellikleri
istisnai durumlar haricinde aktif olmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.13</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Kullanılmayan Uygulamaların Kaldırılması</p>
</blockquote></td>
<td><blockquote>
<p>Sistemlerde kullanılmayan uygulamalar belirlenerek
kaldırılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.14</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Merkezi Güncelleme Sunucusu</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemi güncellemeleri için merkezi bir güncelleme sunucusu
oluşturulmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.15</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>IPv6 Pasif Hale Getirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Eğer kurum içerisinde IPv6 kullanılmıyorsa, IPv6 destekleyen tüm
sunucularda IPv6 desteği pasif hale getirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.16</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Sistem İz Kayıtlarının Aktif Edilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Tüm sunucu ve makinelerde iz kayıtları aktif edilmelidir. Sistem
zaman ve tarih ayarları, kullanıcı hesapları, ağ yapılandırması, erişim
kontrolleri üzerinde yapılan değişiklikler kayıt altına alınmalıdır.
Ayrıca giriş ve çıkış bilgileri, yetkisiz dosya okuma denemeleri, dosya
silme işlemleri ve sistem yöneticisi hareketleri de kayıt altına
alınmalıdır.</p>
<p>Bk. Tedbir No: 3.1.8.1</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.17</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Sistem İz Kayıtlarının Merkezi Bir Sunucuda Toplanması</p>
</blockquote></td>
<td><blockquote>
<p>Sistemlerden syslog vb. araçlarla toplanan sistem iz kayıtları
merkezi bir kayıt yönetim sistemine gönderilmelidir. Burada toplanan iz
kayıtları kurum kritiklik seviyesi ve dinamiklerine uygun olarak
işlenmelidir.</p>
<p>Bk. Tedbir No: 3.1.8.6</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.18</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Merkezi Kimlik Yönetimi Servisinin Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Tüm makinelerde kullanıcı kimlik doğrulama için merkezi kimlik
yönetimi servisi kullanılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.19</p>
</blockquote></td>
<td>3</td>
<td><blockquote>
<p>Sunucularda Çalışan Servislerin Takibi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuların normal işleyişi için gerekli olan servisler dışında başka
bir servisin sunucuda açılması halinde alarm üretilmeli ve ilgili servis
kapatılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.20</p>
</blockquote></td>
<td>3</td>
<td><blockquote>
<p>Bilgisayar Tabanlı Saldırı Tespit ve Engelleme Sistemlerinin
Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Makine özelinde saldırı tespit ve engelleme sistemi (HIDS/HIPS)
kullanılmalıdır.</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.1.21</p>
</blockquote></td>
<td>3</td>
<td><blockquote>
<p>Disk Kotalarının Belirlenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Tüm makinelerde kullanıcılar için her dosya sistemine özel disk kota
politikaları belirlenmeli ve etkinleştirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.22</p>
</blockquote></td>
<td>3</td>
<td><blockquote>
<p>Disk Seviyesinde Şifreleme Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Kritik bilgi içeren ve/veya işleyen makinelerde disk seviyesinde
şifreleme yapılmalıdır.</p>
</blockquote></td>
</tr>
</tbody>
</table>

> Denetim Maddeleri

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.1.1</p>
</blockquote></td>
<td><blockquote>
<p>Kurulum Güvenliği</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat</p>
</blockquote></td>
<td><blockquote>
<p>Kurulumda kullanılan işletim sistemlerinin bütünlüğü, kurulumdan önce
özetleri alınarak teyit edilmekte midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.2</p>
</blockquote></td>
<td><blockquote>
<p>Servis Güvenliği</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Sistemlerin döndüğü başlık bilgilerinde kısıtlamalar uygulanmakta
mıdır?</p>
<p>Bu kısıtlamalar nasıl belirlenmiştir?</p>
<p>Sunucularda kullanılan ve kullanılmayan servisler belirlenmiş
midir?</p>
<p>Kullanılmayan servisler kapatılmış mıdır?</p>
<p>Çalışan servislerin yetkileri nasıl belirlenmektedir? Yönetici
hakları ile çalıştırılan servisler var mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.3</p>
</blockquote></td>
<td><blockquote>
<p>Güncel İşletim Sistemi ve Uygulamaların Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemi sürümleri ne sıklıkla güncellenmektedir?</p>
<p>Kullanılan işletim sistemi sürümlerinin güncelliği sağlanmakta
mıdır?</p>
<p>İşletim sistemi üzerinde yer alan uygulamaların güncelliği kontrol
edilmekte midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.4</p>
</blockquote></td>
<td><blockquote>
<p>Şifreli Haberleşen Servislerin Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Şifresiz haberleşen servisler, şifreli işlem yapan muadilleri ile
değiştirilmiş midir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.5</p>
</blockquote></td>
<td><blockquote>
<p>Parola Politikasının Belirlenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Tüm makineler için kullanıcı parolaları hangi prosedürlere göre
belirlenmektedir? Parola değişimi ve yenileme hangi politikalara göre
yapılmaktadır?</p>
<p>Parola geçmişi tutulmakta ve hatalı giriş sayısına göre kullanıcı
hesapları kilitlenmekte midir?</p>
<p>Parolası olmayan hesaplar için nasıl bir prosedür
uygulanmaktadır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.6</p>
</blockquote></td>
<td><blockquote>
<p>Son Kullanıcı Bilgisayarlarında Ağ Erişiminin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Son kullanıcı bilgisayarlarında ağ erişimi kısıtlaması yapılmış
mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.7</p>
</blockquote></td>
<td><blockquote>
<p>Hata ve Sorun Bilgilerinin Üretici ile Paylaşılmaması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemi kurulumu ile gelen hata ve sorun bilgilerinin üretici
ile paylaşılması özelliği pasif hale getirilmiş midir?</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.1.8</p>
</blockquote></td>
<td><blockquote>
<p>Kablosuz Ağ Arayüzlerinin Kapatılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Tüm sunucularda kullanılmayan kablosuz ağ arayüzleri pasif hale
getirilmiş midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.9</p>
</blockquote></td>
<td><blockquote>
<p>Sistem Üzerinde Düzenli Olarak Zafiyet ve Zararlı Yazılım Taraması
Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sistemler için zafiyet yönetimi nasıl sağlanmaktadır? Bu işlem için
hangi araçlardan faydalanılmaktadır?</p>
<p>Sistemler üzerinde düzenli olarak zararlı yazılım taraması yapılmakta
mıdır?</p>
<p>Zararlı yazılım taramasında faydalanılan araçlar nelerdir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.10</p>
</blockquote></td>
<td><blockquote>
<p>Yerel Güvenlik Duvarı Ayarlarının Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Tüm sunucularda yerel güvenlik duvarı aktif olarak çalışmakta
mıdır?</p>
<p>Güvenlik duvarı yapılandırması yaparken neler dikkate
alınmaktadır?</p>
<p>Güvenlik duvarı kurallarında varsayılan reddetme (deny) kuralı yer
almakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.11</p>
</blockquote></td>
<td><blockquote>
<p>Sunucularda Zaman Senkronizasyonunun Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucularda zaman senkronizasyonu sağlanmış mıdır ve güncel
midir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.12</p>
</blockquote></td>
<td><blockquote>
<p>Güvenli Süreç (Process) İşleme Ayarlarının Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemlerinin DEP, ASLR vb. savunma mekanizmaları
etkinleştirilmiş midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.13</p>
</blockquote></td>
<td><blockquote>
<p>Kullanılmayan Uygulamaların Kaldırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sistemlerde kullanılmayan uygulamaların tespiti nasıl
gerçekleştirilmektedir?</p>
<p>Sistemde kullanılmayan uygulamalar sistemlerden kaldırılmış
mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.14</p>
</blockquote></td>
<td><blockquote>
<p>Merkezi Güncelleme Sunucusu</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sistemlerin güncellik durumları nasıl kontrol edilmektedir?</p>
<p>Güncelleştirme işlemleri için merkezi bir güncelleştirme sunucusu
kullanılmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.15</p>
</blockquote></td>
<td><blockquote>
<p>IPv6 Pasif Hale Getirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kurum içinde IPv6 kullanılmakta mıdır? Kullanılmıyorsa sunucularda
IPv6 desteği pasif hale getirilmiş midir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.16</p>
</blockquote></td>
<td><blockquote>
<p>Sistem İz Kayıtlarının Aktif Edilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Tüm sunucu ve makinelerde sistem iz kayıtları alınmakta mıdır?</p>
<p>Hangi bilgiler kayıt altına alınmaktadır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.17</p>
</blockquote></td>
<td><blockquote>
<p>Sistem İz Kayıtlarının Merkezi Bir Sunucuda Toplanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sistem iz kayıtları merkezi bir kayıt sistemine gönderilmekte
midir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.18</p>
</blockquote></td>
<td><blockquote>
<p>Merkezi Kimlik Yönetimi Servisinin Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Merkezi bir kullanıcı yönetim sistemi kullanılmakta mıdır?
Kullanılıyorsa, nasıl yönetilmektedir?</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.1.19</p>
</blockquote></td>
<td><blockquote>
<p>Sunucularda Çalışan Servislerin Takibi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucularda gerekli ve gereksiz servisler belirlenmiş midir? Gerekli
ve gereksiz servisler nasıl belirlenmiştir?</p>
<p>Listede olmayan bir servis başlatıldığında bunu engellemek/yönetmek
için hangi araçlardan faydalanılmaktadır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.20</p>
</blockquote></td>
<td><blockquote>
<p>Bilgisayar Tabanlı Saldırı Tespit ve Engelleme Sistemlerinin
Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sistem yerelinde saldırı tespit ve engelleme sistemi (HIDS/HIPS)
kullanılmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.1.21</p>
</blockquote></td>
<td><blockquote>
<p>Disk Kotalarının Belirlenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kullanıcılar için disk kotaları belirlenmiş midir? Disk kota
politikaları uygulanmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.1.22</p>
</blockquote></td>
<td><blockquote>
<p>Disk Seviyesinde Şifreleme Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kritik bilgi içeren ve/veya işleyen makineler için disk seviyesinde
şifreleme yapılmakta mıdır?</p>
</blockquote></td>
</tr>
</tbody>
</table>

## Linux İşletim Sistemi Sıkılaştırma Tedbirleri

> Tedbirler

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.2.1</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Kullanılmayan Dosya Sistemlerinin Pasif Hale Getirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Kullanılmayan dosya sistemleri (cramfs, freevxfs, hfs vb.) pasif hale
getirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.2.2</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Yetkili Kullanıcı Hesap Yönetimi</p>
</blockquote></td>
<td><ul>
<li><p>Sisteme erişecek her kişi için ayrı bir kullanıcı hesabı
oluşturulmalıdır.</p></li>
<li><p>Oluşturulan kullanıcılar için yetkiler belirlenmelidir.</p></li>
<li><p>Kullanılmayan hesaplar kaldırılmalıdır.</p></li>
<li><p>Sistem kullanıcılarının kabuğu /sbin/nologin olmalıdır.</p></li>
<li><p>Root login mümkünse engellenmelidir.</p></li>
<li><p>Tüm makinelerde UID değeri 0 olan tek kullanıcı root
olmalıdır.</p></li>
<li><p>Ayrıca aynı isme veya UID değerine sahip kullanıcı veya grup
bulunmamalıdır.</p></li>
<li><p>Servis ve sistem kullanıcıları hariç parolasız kullanıcılar
bulunmamalıdır.</p></li>
<li><p>Sudoers kullanıcıları değişikliklere karşı takip
edilmelidir.</p></li>
</ul></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.2.3</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Dosya Sistemi Güvenli Erişim Düzenlemeleri</p>
</blockquote></td>
<td><blockquote>
<p>İçeriği değiştiğinde, silindiğinde veya taşındığında sistemin
çalışmasını olumsuz yönde etkileyebilecek çalışma dosyalarının,
kütüphanelerin ve yapılandırma dosyalarının (SUID ve SGID dosyaları,
kayıt dosyaları, cron dosyaları, başlangıç betikleri, /etc/passwd,
/etc/shadow vb.) yetkilendirmeleri amacına uygun şekilde düzenlenmeli ve
kurum politikaları doğrultusunda denetlenmelidir. Varsayılan kullanıcı
umask değeri en az yetki prensibine göre ayarlanmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.2.4</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Güvenli Disk Bölümlendirme</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemi dosyaları ile kullanıcı dosyaları, /home,</p>
<p>/root, /boot, /tmp vb. birimler ayrı disk bölümlerinde
tutulmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.2.5</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Otomatik Başlatma (Mount) Özelliğinin Pasif Hale Getirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>CD/DVD ve USB gibi harici medyanın otomatik olarak mount edilmesini
önlemek adına otomatik mount özelliği pasif hale getirilmelidir. Ayrıca
/tmp dizini gibi mount noktalarında noexec, nodev, nosuid
parametreleriyle çalıştırılabilir dosyalar pasif hale
getirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.2.6</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Dosya Sistemi Bütünlük Kontrollerinin Düzenli Olarak Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Önemli görülen dosyaların bütünlüğü düzenli olarak kontrol
edilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.2.7</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Önyükleme (Boot) Ayarlarının Güvenli Şekilde Yapılandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Kullanılan makinelerde önyükleyici (bootloader) parolası belirlenmeli
ve zorunlu tutulmalıdır. Ayrıca tek kullanıcı modu için kimlik
doğrulaması yapılmalıdır. Boot edilebilir cihazlar listesi
kısıtlanmalıdır. Kullanılmıyorsa USB, Firewire, Thunderbolt, PCMCIA vb.
cihazlar iptal edilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.2.8</p>
</blockquote></td>
<td>3</td>
<td><blockquote>
<p>Zorunlu Erişim Kontrolünün (MAC) Aktif Edilmesi</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemi üzerinde erişim kontrolü, ilgili servisler (SELinux,
AppArmor vb.) kullanılarak zorunlu erişim kontrolü (MAC) modeline göre
yapılmalıdır.</p>
</blockquote></td>
</tr>
</tbody>
</table>

> Denetim Maddeleri

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.2.1</p>
</blockquote></td>
<td><blockquote>
<p>Kullanılmayan Dosya Sistemlerinin Pasif Hale Getirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kullanılmayan dosya sistemleri (cramfs, freevxfs, hfs vb.) etkisiz
hale getirilmiş midir?</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><strong>Denetim Soru Önerileri</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.2.2</p>
</blockquote></td>
<td><blockquote>
<p>Yetkili Kullanıcı Hesap Yönetimi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kullanıcılar ve yetkileri nasıl yönetilmektedir? Gereksiz
kullanıcılar bulunmakta mıdır?</p>
<p>Sistem ve servis kullanıcıları hariç diğer kullanıcıların parolaları
bulunmakta mıdır?</p>
<p>Root ile uzaktan erişim mümkün müdür?</p>
<p>UID değeri 0 olan kullanıcı bulunmakta mıdır?</p>
<p>Aynı isme ve UID değerine sahip kullanıcılar ve gruplar bulunmakta
mıdır?</p>
<p>Sistem kullanıcıların kabuğu /sbin/nologin midir?</p>
<p>Sudoers kullanıcıları değişikliklere karşı takip edilmekte midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.2.3</p>
</blockquote></td>
<td><blockquote>
<p>Dosya Sistemi Güvenli Erişim Düzenlemeleri</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sistemlerde yer alan kritik dosyalar belirlenmiş midir?</p>
<p>Dosya sistemlerine güvenli erişim kapsamında tanımlanmış bir politika
var mıdır?</p>
<p>Politika içeriğinde hangi hususlar ele alınmaktadır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.2.4</p>
</blockquote></td>
<td><blockquote>
<p>Güvenli Disk Bölümlendirme</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td>Disk bölümlendirme nasıl yapılmaktadır?</td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.2.5</p>
</blockquote></td>
<td><blockquote>
<p>Otomatik Başlatma (Mount) Özelliğinin Pasif Hale Getirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>CD/DVD ve USB gibi medya cihazları otomatik olarak başlatılmakta
mıdır?</p>
<p>Bunu engellemek için ne gibi bir yapılandırma ayarı yapılmıştır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.2.6</p>
</blockquote></td>
<td><blockquote>
<p>Dosya Sistemi Bütünlük Kontrollerinin Düzenli Olarak Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sistemlerde bütünlüğü kritik olan dosyalar belirlenmiş midir?</p>
<p>Belirlenen bu dosyaların kontrolünü yapmak için hangi
araçlardan/programlardan faydalanılmaktadır?</p>
<p>Dosyaların bütünlüğünün bozulduğu durumlar için ne gibi bir süreç
işletilmektedir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.2.7</p>
</blockquote></td>
<td><blockquote>
<p>Önyükleme (Boot) Ayarlarının Güvenli Şekilde Yapılandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Önyükleyici için güvenli bir yapılandırma var mıdır? Boot
cihazlarının yönetimi nasıl yapılmaktadır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.2.8</p>
</blockquote></td>
<td><blockquote>
<p>Zorunlu Erişim Kontrolünün (MAC) Aktif Edilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Zorunlu erişim kontrolü (MAC) için hangi servilerden
faydalanılmaktadır?</p>
<p>Bu servislerin yönetimi nasıl sağlanmaktadır?</p>
</blockquote></td>
</tr>
</tbody>
</table>

## Windows İşletim Sistemi Sıkılaştırma Tedbirleri

> Tedbirler

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.3.1</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Kullanıcı Haklarının Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Kullanıcı hakları en az yetki prensibi göz önünde bulundurularak
sadece ihtiyaç duyulan kullanıcı ve gruplara verilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.2</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Otomatik Güncellemenin Aktif Olması</p>
</blockquote></td>
<td><blockquote>
<p>Tüm kullanıcı makinelerinde otomatik güncelleme özelliği aktif hale
getirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.3</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>SMB Protokolü Güvenliği</p>
</blockquote></td>
<td><blockquote>
<p>Windows işletim sistemlerinde SMB versiyon 1 protokolü yerine daha
güvenli ve güncel SMB protokol versiyonları kullanılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.4</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Yerel Yönetici Hesapları Yönetimi</p>
</blockquote></td>
<td><blockquote>
<p>Gerekli kullanıcılar dışında tüm kullanıcıların yerel yönetici
hesapları devre dışı bırakılmalıdır. Gerekli kullanıcılar için
varsayılan olarak aynı tanımlanan yerel yönetici hesaplarının parolaları
değiştirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.5</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Ayrıcalıklı Hesap Sayılarının Sınırlandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Etki alanı yöneticisi (Domain Admin) ve diğer yetkili hesapların
(Enterprise Admin, Backup Admin ve Schema Admin) sayısı
sınırlandırılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.6</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Yetkili Hesapların Parola Özetlerinin Çalınmasının Engellenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Yetkili hesapların parola özetlerinin çalınmasının engellenmesi
için:</p>
</blockquote>
<ul>
<li><p>Etki alanı yöneticisi (domain admin) hesabıyla kullanıcı
bilgisayarlarında gerekli olmadıkça işlem yapılmamalı, işlem yapıldığı
durumlarda kullanıcı bilgisayarlarının yeniden başlatılması
sağlanmalıdır.</p></li>
<li><p>Yerel bilgisayarlarda parola özetleri tutulma sayısı 0
yapılmalıdır.</p></li>
<li><p>Ayrıcalıklı kullanıcı hesapları Korunan Kullanıcılar (Protected
Users) grubuna alınmalıdır.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.7</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Kullanılmayan Hesapların Devre Dışı Bırakılması</p>
</blockquote></td>
<td><blockquote>
<p>Aktif dizinde uzun süre kullanılmayan kullanıcı ve bilgisayar
hesaplarını tespit etmek için bir yordam tanımlanmalıdır.</p>
<p>Bk. Tedbir No: 3.1.12.10</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.8</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Varsayılan Yönetici ve Misafir Hesaplarının Yapılandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Sistemlerde yer alan varsayılan yönetici ve misafir hesapları pasif
hale getirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.9</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Standart Kullanıcıların Betik Çalıştırma Motorlarına Erişiminin
Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Standart kullanıcıların betik çalıştırma motorlarına (Windows Script
Host, Powershell, Command Prompt ve Microsoft HTML Application Host vb.)
erişimi engellenmeli veya kısıtlanmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.10</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Aktif Dizin Sorguları Güvenliği</p>
</blockquote></td>
<td><blockquote>
<p>Aktif dizin sorguları LDAP protokolü yerine güvenli LDAPs protokolü
ile yapılacak şekilde konfigüre edilmelidir.</p>
<p>Bk. Tedbir No: 3.2.9.1</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.3.11</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Yönetici Hesaplarının İzlenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Ayrıcalıklı etki alanı gruplarına kullanıcı ekleme ve çıkarma
işlemleri ve oturum açma kapama işlemleri izlenmelidir.</p>
<p>Bk. Tedbir No: 3.1.12.11</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.12</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Güvenli Yönetici İş İstasyonu Kullanımı</p>
</blockquote></td>
<td><blockquote>
<p>Yalnızca etki alanı yönetimini (Domain Controller) gerçekleştirmek
için güvenli bir yönetici iş istasyonu konumlandırılmalı, ek yazılım
veya rol yüklenmemeli, eposta, internet vb. erişimleri için
kullanılmamalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.13</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Devre Dışı Bırakılan Hesabın Mail Erişiminin Engellenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Aktif dizinde devre dışı bırakılan kullanıcı hesabı için activesync
mail erişimi hemen kesilmelidir.</p>
</blockquote></td>
</tr>
</tbody>
</table>

> Denetim Maddeleri

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 48%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.3.1</p>
</blockquote></td>
<td><blockquote>
<p>Kullanıcı Haklarının Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kullanıcı haklarının kısıtlanması son kullanıcı bilgisayarlarına
uygun olarak yapılandırılmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.2</p>
</blockquote></td>
<td><blockquote>
<p>Otomatik Güncellemenin Aktif Olması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sisteminin otomatik güncelleme ayarı açık mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.3</p>
</blockquote></td>
<td><blockquote>
<p>SMB Protokolü Güvenliği</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>SMB versiyon 1 protokolü sunucu ve istemcilerde kapatılmış mıdır, SMB
protokolü hangi versiyon u kullanılmaktadır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.4</p>
</blockquote></td>
<td><blockquote>
<p>Yerel Yönetici Hesapları Yönetimi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Gerekli kullanıcılar dışında tüm kullanıcıların yerel yönetici
hesapları devre dışı bırakılmış mıdır?</p>
<p>Yerel yönetici hesaplarının parolaları nasıl değiştirilmektedir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.5</p>
</blockquote></td>
<td><blockquote>
<p>Ayrıcalıklı Hesap Sayılarının Sınırlandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Ayrıcalıklı hesap sayıları sınırlandırılmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.6</p>
</blockquote></td>
<td><blockquote>
<p>Yetkili Hesapların Parola Özetlerinin Çalınmasının Engellenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Etki alanı yöneticisi (domain admin) hesabıyla kullanıcı
bilgisayarlarında ne sıklıkla ve ne gibi işlemler yapılmaktadır?</p>
<p>Yerel bilgisayarlarda tutulan hesaplara ait parola özetlerinin
tutulma sayısı 0 olarak ayarlanmış mıdır?</p>
<p>Ayrıcalıklı kullanıcı hesapları Korunan Kullanıcılar (Protected
Users) Grubuna alınmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.7</p>
</blockquote></td>
<td><blockquote>
<p>Kullanılmayan Hesapların Devre Dışı Bırakılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Aktif dizinde uzun süre kullanılmayan kullanıcı ve bilgisayar
hesaplarını tespit etmek için bir yordam tanımlanmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.8</p>
</blockquote></td>
<td><blockquote>
<p>Varsayılan Yönetici ve Misafir Hesaplarının Yapılandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Varsayılan yönetici ve misafir hesaplarının yapılandırılması en iyi
çözüm önerilerine uygun olarak yapılmış mıdır?</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 48%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.1.3.9</p>
</blockquote></td>
<td><blockquote>
<p>Standart Kullanıcıların Betik Çalıştırma Motorlarına Erişiminin
Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Cmd, powershell gibi betik çalıştırma motorlarına erişimler
kısıtlandırılmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.10</p>
</blockquote></td>
<td><blockquote>
<p>Aktif Dizin Sorguları Güvenliği</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Aktif dizin sorguları güvenli LDAPs protokolü ile yapılmakta
mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.11</p>
</blockquote></td>
<td><blockquote>
<p>Yönetici Hesaplarının İzlenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Ayrıcalıklı etki alanı gruplarına kullanıcı ekleme ve çıkarma
işlemleri ve oturum açma kapama işlemleri izlenmekte midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.1.3.12</p>
</blockquote></td>
<td><blockquote>
<p>Güvenli Yönetici İş İstasyonu Kullanımı</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Yalnızca etki alanı yönetimini (Domain Controller) gerçekleştirmek
için güvenli bir yönetici iş istasyonu kullanılmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.1.3.13</p>
</blockquote></td>
<td><blockquote>
<p>Devre Dışı Bırakılan Hesabın Mail Erişiminin Engellenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Aktif dizinde devre dışı bırakılan kullanıcı hesabı için activesync
mail erişimi hemen kesilmekte midir?</p>
</blockquote></td>
</tr>
</tbody>
</table>

# <img src="media/image3.png" style="width:0.29in;height:0.12333in" />Veri Tabanı Sıkılaştırma Tedbirleri

## Amaç

> Bu güvenlik tedbiri ana başlığının amacı, veri tabanı güvenlik
> sıkılaştırmaları çerçevesinde ele alınan tedbir listeleri ve denetim
> sorularını belirlemektir. “Veri Tabanı Sıkılaştırma Tedbirleri” ana
> başlığı kapsamında ele alınan güvenlik tedbirleri alt başlıkları
> aşağıda yer almaktadır.

- Genel Sıkılaştırma Tedbirleri

## Genel Sıkılaştırma Tedbirleri

> Tedbirler

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.2.1.1</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Güncelleme ve Yama Yönetimi</p>
</blockquote></td>
<td><blockquote>
<p>Üretici tarafından desteklenmeyen sistemler zafiyet
içerebileceğinden, veri tabanı bilinen en kararlı versiyon ile
kullanılmalıdır. Bu kapsamda, belirli periyotlar ile sistemlerin
güncelliği kontrol edilmeli ve gerekli güncelleştirmeler
gerçekleştirilmelidir.</p>
<p>Güvenlik yamaları, yayımlandıktan sonra mümkün olan en kısa zamanda
ilgili sistemlere yüklenmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.2</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Veri Tabanı Parametrelerinin Güvenli Yapılandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı için sunulan parametreler ulusal ve/veya uluslararası
otoriteler tarafından güvenli olarak kabul görmüş yöntemler ile
yapılandırılmalıdır. Ayrıca veri tabanı yönetim sistemi üreticisi
tarafından yayımlanan güvenli kullanım önerileri uygulanmalıdır.</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.2.1.3</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Varsayılan Hesap ve Parolaların Kullanılmaması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanlarında varsayılan kullanıcı hesapları ve parolalar
kullanılmamalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.4</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Veri Tabanı Kullanıcıları için Parola Politikalarının
Oluşturulması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı kullanıcıları için güçlü parola politikaları
oluşturulmalı ve uygulanmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.5</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Veri Tabanına Yapılan Uzak Bağlantıların Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı sunucularına olan uzak bağlantı, mümkün olduğunca
sınırlandırılarak yalnızca yetkili kullanıcıların ve/veya uygulamaların
uzaktan erişimine olanak sağlayacak şekilde yapılandırılmalıdır. Bu
kapsamda, ilgili sunucularda mevcut yapılandırmalar düzenlenmeli ve ağ
katmanında gerekli önlemler alınmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.6</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Kullanılmayan Hesapların Kapatılması</p>
</blockquote></td>
<td><blockquote>
<p>Düzenli olarak gerçekleştirecek denetimler ile belirli bir süre
boyunca kullanılmayan kullanıcılar tespit edilerek pasif hale
getirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.7</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Anonim Hesapların Bulunmaması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı kullanıcı hesapları, yapılan işlemlerin izlenebilirliğini
sağlayacak ve tekil olarak kişi veya sistemi işaret edecek şekilde
yapılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.8</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Veri Tabanı Rol ve Yetkilerinin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Tüm ayrıcalıklar, doğrudan kullanıcıya verilmek yerine kullanıcıların
atanmış oldukları rollere/profillere tanımlanmalıdır. Düzenli
aralıklarla veri tabanı rol ve yetkileri gözden geçirilmelidir.
Kullanılmayan roller kaldırılmalı/pasif hale getirilmelidir. Ayrıca,
kullanıcı hakları gözden geçirilerek gereksiz olarak tanımlanmış ve/veya
ihtiyaç duyulmayan yetkiler kaldırılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.9</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Veri Tabanı Yönetim Sisteminin İşletim Sistemi Üzerindeki
Ayrıcalıklarının Sınırlandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanının çalıştığı işletim sistemi üzerinde; komut çalıştırma,
yerel dosya okuma/yazma vb. işlemlere imkân sağlayabilecek
ayrıcalıkların sınırlandırılması için veri tabanı yönetim sistemi,
desteklediği ölçüde yapılandırılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.10</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Komut/Sorgu Geçmişi Kayıtlarının Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı tarafından, üzerinde çalıştırılmış komut/sorgu geçmişinin
kayıt altına alındığı durumda ilgili kayıtların/dosyaların güvenliği
sağlanmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.11</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Yedeklerin Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Yedek dosyalarına yetkisiz kullanıcıların erişmesini engellemek adına
dosya izinlerinin yapılandırılması, şifreleme vb. yöntemler ile güvenlik
sağlanmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.12</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Adanmış Sunucu Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Saldırı yüzeyini düşürmek amacıyla, veri tabanı yönetim sistemi
adanmış bir sunucu üzerinde çalışmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.13</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Kurulum Dosyalarının Güvenilir Kaynaklardan Temin Edilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Kurulum dosyaları ve/veya kurulum için kullanılan paketler, güvenilir
kaynaklardan elde edilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.14</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Örnek Verilerin Silinmesi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanından, kurulum ile gelen örnek veriler (örnek tablolar,
kayıtlar, kullanıcılar vb.) silinmelidir.</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.2.1.15</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Veri Tabanı Sistem Dosyalarının ve İz Kayıtlarının Aynı Disk Bölümü
Üzerinde Bulunmaması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı tarafından kullanılan sistem dosyaları ve üretilen iz
kayıtları farklı disk bölümlerinde tutulmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.16</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Veri Tabanında Tablo ve Nesne Düzeyinde Yetkilendirme Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Kritik veri içeren tablo ve nesneler için tablo ve/veya nesne bazında
yetkilendirme yapılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.17</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>İşletim Sistemi Üzerinde Veri Tabanı Servisi Çalıştıran
Kullanıcıların Yönetici Haklarına Sahip Olmaması</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemi üzerinde veri tabanı servis(ler)ini çalıştıran
kullanıcılar için en az yetki prensibi uygulanmalıdır. Bu kapsamda
ilgili kullanıcılar, ihtiyaç duyulmadığı takdirde yönetici haklarına
sahip olmamalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.18</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Kümeleme veya Replikasyon İçinde Bulunan Veri Tabanı Sunucuları Arası
İletişimin Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Kümeleme (cluster) ve/veya replikasyon içinde bulunan veri tabanı
sunucuları arasında gerçekleştirecekleri iletişim şifreli olarak
yapılmalıdır. Buna ek olarak, ilgili süreçlerde kullanılacak hesaplar
için en az yetki prensibi uygulanmalıdır. Bu kapsamda, replikasyon ve
kümeleme faaliyetlerinde kullanılan hesaplar ihtiyaç duyulmadığı
takdirde yönetici haklarına sahip olmamalıdır.</p>
<p>Bk. Tedbir No: 5.2.1.8 Bk. Tedbir No: 3.2.5.11</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.19</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Merkezi Kimlik Doğrulama Sisteminin Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı yönetim sisteminin desteklediği ölçüde, merkezi kimlik
doğrulama sistemi kullanılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.20</p>
</blockquote></td>
<td>3</td>
<td><blockquote>
<p>Kritik Bilgi İçeren Veri Tabanı Sunucularında Durağan Verinin
Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı sunucularında yer alan kritik verinin, depolama motoru
(storage engine) ve/veya disk seviyesinde şifreleme gibi yöntemler ile
güvenliği sağlanmalıdır.</p>
<p>Bk. Tedbir No: 5.1.1.22</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.21</p>
</blockquote></td>
<td>3</td>
<td><blockquote>
<p>Veri Tabanı Sunucusu ile İstemci Arasındaki İletişimin Şifreli
Olması</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı sunucusu ile istemci arasındaki iletişim şifreli trafik
üzerinden sağlanmalıdır.</p>
</blockquote></td>
</tr>
</tbody>
</table>

> Denetim Maddeleri

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.2.1.1</p>
</blockquote></td>
<td><blockquote>
<p>Güncelleme ve Yama Yönetimi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanının güncelliği ve güvenlik yamalarının mevcut olup
olmadığı belirli periyotlar ile kontrol ediliyor mu?</p>
<p>Yeni versiyonun veya güvenlik yamasının tespit edilmesi halinde
güncelleştirmeler kontrollü bir şekilde devreye alınıyor mu?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.2</p>
</blockquote></td>
<td><blockquote>
<p>Veri Tabanı Parametrelerinin Güvenli Yapılandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı için sunulan parametreler, ulusal ve/veya uluslararası
otoriteler tarafından güvenli olarak kabul görmüş yöntemler ile
yapılandırılıyor mu?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.3</p>
</blockquote></td>
<td><blockquote>
<p>Varsayılan Hesap ve Parolaların Kullanılmaması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanında varsayılan hesaplar bulunmakta mıdır?</p>
<p>Veri tabanı kullanıcıları arasında varsayılan parola kullanan hesap
bulunmakta mıdır?</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.2.1.4</p>
</blockquote></td>
<td><blockquote>
<p>Veri Tabanı Kullanıcıları için Parola Politikalarının
Oluşturulması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı kullanıcılarını güçlü parola kullanmaya zorlayacak
politikalar tanımlanmış mıdır?</p>
<p>Tanımlanan politikalar tüm kullanıcılar için zorunlu tutulmakta
mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.5</p>
</blockquote></td>
<td><blockquote>
<p>Veri Tabanına Yapılan Uzak Bağlantıların Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı sunucularına yalnızca gerekli/yetkili kullanıcılar
ve/veya uygulamalar tarafından uzaktan bağlantının sağlaması için hangi
önlemler alınmaktadır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.6</p>
</blockquote></td>
<td><blockquote>
<p>Kullanılmayan Hesapların Kapatılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Belirli bir süre boyunca kullanılmayan kullanıcılar tespit edilerek
pasif hale getiriliyor mu?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.7</p>
</blockquote></td>
<td><blockquote>
<p>Anonim Hesapların Bulunmaması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Aynı hesabın birden fazla kullanıcı tarafından kullanılmasını (ortak
hesap) önlemek adına tekil kullanıcılar tanımlanmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.8</p>
</blockquote></td>
<td><blockquote>
<p>Veri Tabanı Rol ve Yetkilerinin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı rol ve yetkileri düzenli aralıklarla gözden geçirilerek
kullanılmayan roller pasif hale getiriliyor/kaldırılıyor mu?</p>
<p>Kullanıcı hakları gözden geçirilerek gereksiz olarak tanımlanmış
ve/veya ihtiyaç duyulmayan yetkiler kaldırılıyor mu?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.9</p>
</blockquote></td>
<td><blockquote>
<p>Veri Tabanı Yönetim Sisteminin İşletim Sistemi Üzerindeki
Ayrıcalıklarının Sınırlandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanının çalıştığı işletim sistemi üzerinde; komut çalıştırma,
yerel dosya okuma/yazma vb. işlemlere imkân sağlayabilecek
ayrıcalıkların sınırlandırılması için veri tabanı yönetim sistemi,
desteklediği ölçüde yapılandırılmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.10</p>
</blockquote></td>
<td><blockquote>
<p>Komut/Sorgu Geçmişi Kayıtlarının Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı tarafından, üzerinde çalıştırılmış komut/sorgu geçmişi
kayıt altına alınıyor mu?</p>
<p>Böyle bir durumda ilgili kayıtların/dosyaların güvenliği nasıl
sağlanmaktadır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.11</p>
</blockquote></td>
<td><blockquote>
<p>Yedeklerin Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Yedek dosyaların güvenliği hangi yöntemler ile sağlanmaktadır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.12</p>
</blockquote></td>
<td><blockquote>
<p>Adanmış Sunucu Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>İlgili veri tabanı sunucusu adanmış sunucu mudur?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.13</p>
</blockquote></td>
<td><blockquote>
<p>Kurulum Dosyalarının Güvenilir Kaynaklardan Temin Edilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kurulum dosyalarının/kurulum için kullanılan paketlerin, güvenilir
kaynaklardan alınmış olduğu kontrol ediliyor mu?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.14</p>
</blockquote></td>
<td><blockquote>
<p>Örnek Verilerin Silinmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanında, kurulum ile gelen örnek veriler (örnek tablolar,
kayıtlar, kullanıcılar vb.) bulunuyor mu?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.15</p>
</blockquote></td>
<td><blockquote>
<p>Veri Tabanı Sistem Dosyalarının ve İz Kayıtlarının Aynı Disk Bölümü
Üzerinde Bulunmaması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı tarafından kullanılan sistem dosyaları hangi disk bölümü
üzerinde bulunmaktadır?</p>
<p>Veri tabanı tarafından üretilen iz kayıtları hangi disk bölümü
üzerinde bulunmaktadır?</p>
<p>Sistem bölümü, hangi disk bölümü üzerindedir?</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.2.1.16</p>
</blockquote></td>
<td><blockquote>
<p>Veri Tabanında Tablo ve Nesne Düzeyinde Yetkilendirme Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kritik veri içeren tablo ve nesneler için tablo ve/veya nesne bazında
yetkilendirme kullanılıyor mu?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.17</p>
</blockquote></td>
<td><blockquote>
<p>İşletim Sistemi Üzerinde Veri Tabanı Servisi Çalıştıran
Kullanıcıların Yönetici Haklarına Sahip Olmaması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemi üzerinde veri tabanı servis(ler)ini çalıştıran
kullanıcılar için en az yetki prensibi uygulanmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.18</p>
</blockquote></td>
<td><blockquote>
<p>Kümeleme veya Replikasyon İçinde Bulunan Veri Tabanı Sunucuları Arası
İletişimin Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kümeleme ve/veya replikasyon içinde veri tabanı sunucuları mevcut
mudur?</p>
<p>Bu sunucular arasında gerçekleşen iletişim şifreli olarak mı
yapılmaktadır?</p>
<p>İlgili süreçlerde kullanılacak hesaplarda en az yetki prensibi
uygulanmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.19</p>
</blockquote></td>
<td><blockquote>
<p>Merkezi Kimlik Doğrulama Sisteminin Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Merkezi kimlik doğrulama sistemi kullanılmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.2.1.20</p>
</blockquote></td>
<td><blockquote>
<p>Kritik Bilgi İçeren Veri Tabanı Sunucularında Durağan Verinin
Güvenliğinin Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Kritik veri içeren veri tabanı sunucularında bulunan hareketsiz
verinin (data at rest) güvenliği nasıl sağlanmaktadır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.2.1.21</p>
</blockquote></td>
<td><blockquote>
<p>Veri Tabanı Sunucusu ile İstemci Arasındaki İletişimin Şifreli
Olması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Veri tabanı sunucusu ile istemci arasındaki iletişim şifreli trafik
üzerinden mi sağlanmaktadır?</p>
</blockquote></td>
</tr>
</tbody>
</table>

# <img src="media/image4.png" style="width:0.29in;height:0.12333in" />Sunucu Sıkılaştırma Tedbirleri

## Amaç

> Bu güvenlik tedbiri ana başlığının amacı, sunucu güvenlik
> sıkılaştırmaları çerçevesinde ele alınan tedbir listeleri ve denetim
> sorularını belirlemektir. “Sunucu Sıkılaştırma Tedbirleri” ana başlığı
> kapsamında ele alınan güvenlik tedbirleri alt başlıkları aşağıda yer
> almaktadır.

- Web Sunucusu Sıkılaştırma Tedbirleri

- Sanallaştırma Sunucusu Sıkılaştırma Tedbirleri

## Web Sunucusu Sıkılaştırma Tedbirleri

> Tedbirler

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.3.1.1</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Güncel Web Sunucu Yazılımlarının Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımlarının güncel, zafiyet içermeyen ve üreticisi
tarafından desteği devam eden kararlı sürümleri kullanılmalıdır. Ayrıca,
sunucuda kullanımda olan tüm araçların/paket programların güvenlik
yamaları için düzenli aralıklarla kontrol yapılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.2</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>WebDAV Desteğinin Kaldırılması</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucusunun WebDAV (Web Distributed Authoring and Versioning)
desteği kaldırılmalıdır. WebDAV ile ilgili modüller pasif hale
getirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.3</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Web Sunucusu Kullanıcı Yönetimi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımı yönetici hesabıyla değil, bu amaç için özel
olarak oluşturulmuş bir hesap ile çalıştırılmalıdır. Web sunucusunda
bulunan varsayılan hesaplar/parolalar kullanım dışı bırakılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.4</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Web Sunucusunun Bilgi İfşalarını Önleyecek Şekilde
Yapılandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucusu bilgi ifşalarını önleyecek şekilde yapılandırılmalıdır.
Varsayılan hata ve kurulum sayfaları kaldırılmalıdır. Web sunucu
teknolojisi hakkında bilgi ifşasına neden olan HTTP başlıkları
kaldırılmalıdır. Hatalı HTTP isteklerine dönen cevaplarda bilgi ifşasına
izin verilmemelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.5</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Desteklenen HTTP Metotlarının Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>POST, GET, OPTIONS ve HEAD metotları dışında diğer HTTP metotları
desteklenmemelidir. PUT, DELETE, PROPFIND gibi metotlar web servisi için
kullanılıyorsa, kullanımlarının sadece web servis ihtiyaçları ile
sınırlı olup olmadığı kontrol edilmelidir. Bu metotların dosya yükleme
veya silme gibi farklı amaçlarla kullanımı engellenmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.6</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Dizin Listelemenin Pasif Hale Getirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Dizin listelemesi pasif hale getirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.7</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Debug Modunun Kapalı Olması</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımı debug (hata ayıklama) modunda
çalıştırılmamalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.8</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>İstek Limitlerinin Tanımlanması</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımının desteklediği ölçüde, istekler için limitler
belirlenmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.9</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>İz Kayıtlarının Alınması</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımına ilişkin iz kayıtları alınmalıdır. Bk. Tedbir
No: 3.1.8.1</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.10</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Yazma İzni Olan Dizinlerin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Yazma izni olan dizinler belirlenmeli, yazma yetkileri sadece dosya
yükleme ihtiyacı olan dizinlere verilmelidir. Uygulama üzerinden
yüklenen dosyalar için oluşturulmuş dizinlerde çalıştırma izni
kaldırılmalıdır.</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.3.1.11</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>SSL/TLS Kullanımı</p>
</blockquote></td>
<td><blockquote>
<p>Sunucu SSL/TLS kullanımına elverişli yapılandırılmalıdır. Bu
kapsamda, sunucuda sadece, bilinen zafiyet içermeyen güvenilir sürüme
sahip SSL/TLS versiyonları kullanılmalıdır.</p>
<p>Bk. Tedbir No: 3.2.9.1</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.12</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>İsteklerin HTTP’den HTTPS’e Yönlendirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucusundaki herhangi bir HTTP bağlantı noktası, şifreleme
kullanan bir sunucu bağlantı noktasına yönlendirmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.13</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Kullanılmayan Modüllerin Kaldırılması</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuda sadece kullanılan modüllerin aktif olmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.14</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Açık Portların Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucusu yalnızca yetkili bağlantı noktalarındaki ağ
bağlantılarını dinlemelidir. Kullanımda olmayan portlar
kapatılmalıdır.</p>
<p>Bk. Tedbir No: 5.1.1.2</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.15</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Kaynak Kullanım Optimizasyonu</p>
</blockquote></td>
<td><blockquote>
<p>Uygulama seviyesinde yapılabilecek servis dışı bırakma saldırılarına
karşı aşağıdaki sunucu üzerinde aşağıdaki sıkılaştırmalar
yapılmalıdır:</p>
</blockquote>
<ul>
<li><p>Sunucunun kabul edebileceği maksimum kullanıcı sayısı
artırılmalıdır.</p></li>
<li><p>Tek bir IP adresinden yapılabilecek bağlantı sayısı
sınırlandırılmalıdır.</p></li>
<li><p>Her bir bağlantının kullanabileceği maksimum ve minimum transfer
hızı belirlenmelidir.</p></li>
<li><p>Bağlantılar için zaman aşım değeri belirlenmeli, belirli bir süre
açık kalan bağlantılar sonlandırılmalıdır.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.16</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sunucunun Korumalı ve Ayrıştırılmış Şekilde Kurulumu</p>
</blockquote></td>
<td><blockquote>
<p>İnternete açık olarak çalışan web sunucu ayrı bir bölgede (DMZ vb.)
tutulmalıdır.</p>
<p>Bk. Tedbir No: 3.2.5.3 Bk. Tedbir No: 3.1.6.6</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.17</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sunucuda Koruyucu HTTP Başlıklarının Kullanımı</p>
</blockquote></td>
<td><blockquote>
<p>Sunucu tarafında koruyucu HTTP başlıkları (X-Frame- Options,
Strict-Transport-Security vb.) yapılandırılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.18</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sunucunun Özel Anahtarının (Private Key) Korunması</p>
</blockquote></td>
<td><blockquote>
<p>Sunucunun özel anahtarına (private key) yapılacak yetkisiz erişimlere
karşı önlemler alınmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.19</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>İz Kayıtlarının Merkezi Kayıt Sistemine Gönderilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucularından alınan iz kayıtları merkezi bir kayıt sistemine
gönderilmelidir.</p>
<p>Bk. Tedbir No: 3.1.8.6</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.3.1.20</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Sunucuya IP Adresi Üzerinden Erişimlerin Engellenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuya IP adresi üzerinden yapılan erişimler engellenmelidir.</p>
</blockquote></td>
</tr>
</tbody>
</table>

> Denetim Maddeleri

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 17%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.3.1.1</p>
</blockquote></td>
<td><blockquote>
<p>Güncel Web Sunucu Yazılımlarının Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımlarının güncel, zafiyet içermeyen ve üreticisi
tarafından desteği devam eden kararlı sürümleri mi kullanılmaktadır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.2</p>
</blockquote></td>
<td><blockquote>
<p>WebDAV Desteğinin Kaldırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucusunun WebDAV (Web Distributed Authoring and Versioning)
desteği bulunmakta mıdır?</p>
<p>WebDAV ile ilgili modullerden aktif durumda olan var mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.3</p>
</blockquote></td>
<td><blockquote>
<p>Web Sunucusu Kullanıcı Yönetimi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımı hangi kullanıcı hesabıyla çalıştırılmaktadır?</p>
<p>Web sunucusunda bulunan varsayılan hesaplar/parolalar kullanım dışı
bırakılmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.4</p>
</blockquote></td>
<td><blockquote>
<p>Web Sunucusunun Bilgi İfşalarını Önleyecek Şekilde
Yapılandırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucusu bilgi ifşalarını önleyecek şekilde yapılandırılmış
mıdır?</p>
<p>Web sunucu teknolojisi hakkında bilgi ifşasına neden olan HTTP
başlıkları kaldırılmış mıdır?</p>
<p>Olağan dışı (hatalı) HTTP isteklerine dönülen yanıtlarda bilgi ifşası
olmaması için kontrol sağlanmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.5</p>
</blockquote></td>
<td><blockquote>
<p>Desteklenen HTTP Metotlarının Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Uygulama gereksinimleri dışındaki tüm HTTP metotları kısıtlanmış
mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.6</p>
</blockquote></td>
<td><blockquote>
<p>Dizin Listelemenin Pasif Hale Getirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuda dizin listelemesi pasif hale getirilmiş midir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.7</p>
</blockquote></td>
<td><blockquote>
<p>Debug Modunun Kapalı Olması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımı debug modunda çalıştırılabilmekte midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.8</p>
</blockquote></td>
<td><blockquote>
<p>İstek Limitlerinin Tanımlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımının desteklediği ölçüde, istekler için limitler
belirlenmiş midir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.9</p>
</blockquote></td>
<td><blockquote>
<p>İz Kayıtlarının Alınması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucu yazılımına ilişkin iz kayıtları alınmakta mıdır?</p>
<p>Alınan iz kayıtları kurum politikaları ve ilgili mevzuatlarda
belirtilen süre boyunca saklanmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.10</p>
</blockquote></td>
<td><blockquote>
<p>Yazma İzni Olan Dizinlerin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuda yazma izni olan dizin bulunuyor mudur? Bu dizinlerde
düzenleme yapılmış mıdır?</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 17%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.3.1.11</p>
</blockquote></td>
<td><blockquote>
<p>SSL/TLS Kullanımı</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucu SSL/TLS kullanımına elverişli yapılandırılmış mıdır?</p>
<p>Sunucuda hangi SSL/TLS sürümü kullanılmaktadır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.12</p>
</blockquote></td>
<td><blockquote>
<p>İsteklerin HTTP’den HTTPS’e Yönlendirilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucusundaki tüm HTTP bağlantı noktaları şifreleme kullanan bir
sunucu bağlantı noktasına yönlendiriliyor mudur?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.13</p>
</blockquote></td>
<td><blockquote>
<p>Kullanılmayan Modüllerin Kaldırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuda kullanılmayan modüller kaldırılmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.14</p>
</blockquote></td>
<td><blockquote>
<p>Açık Portların Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucusunun yalnızca yetkili bağlantı noktalarındaki ağ
bağlantıları mı dinlenmektedir?</p>
<p>Kullanımda olmayan portlar kapatılmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.15</p>
</blockquote></td>
<td><blockquote>
<p>Kaynak Kullanım Optimizasyonu</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Tek bir IP adresi üzerinden yapılabilecek maksimum bağlantı sayısı
belirlenmiş midir?</p>
<p>Uzun süre açık kalan bağlantılar kapatılmakta mıdır?</p>
<p>Bağlantılar için maksimum ve minimum transfer hızı belirlenmiş
midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.16</p>
</blockquote></td>
<td><blockquote>
<p>Sunucunun Korumalı ve Ayrıştırılmış Şekilde Kurulumu</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>İnternete açık olarak çalışan web sunucu DMZ (DeMilitarized Zone)
gibi ayrı bir bölgede tutulmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.17</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuda Koruyucu HTTP Başlıklarının Kullanımı</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Olası saldırılara karşın önlem olarak sunucu tarafında koruyucu HTTP
başlıkları yapılandırılmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.18</p>
</blockquote></td>
<td><blockquote>
<p>Sunucunun Özel Anahtarının (Private Key) Korunması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucunun özel anahtarı (private key) yetkisiz erişime karşı
korunmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.1.19</p>
</blockquote></td>
<td><blockquote>
<p>İz Kayıtlarının Merkezi Kayıt Sistemine Gönderilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Web sunucularından alınan iz kayıtları merkezi bir kayıt sistemine
gönderiliyor mudur?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.1.20</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuya IP Adresi Üzerinden Erişimlerin Engellenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi, Sızma Testi</p>
</blockquote></td>
<td><blockquote>
<p>Sunucuya IP adresi üzerinden erişimler engellenmiş midir?</p>
</blockquote></td>
</tr>
</tbody>
</table>

## Sanallaştırma Sunucusu Sıkılaştırma Tedbirleri

> Tedbirler

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 48%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.3.2.1</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Güncel Sanallaştırma Yazılımının Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma sunucusunda kullanılan sanallaştırma yazılımı güncel
olmalı ve mevcut güvenlik yamaları yüklü olmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.2</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Konteynerların /Sanal Makinelerin Çalıştığı Ana Makine Üzerinde
Sıkılaştırmaların Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Konteynerların/sanal makinelerin çalıştığı ana makine üzerinde
sıkılaştırmalar yapılmalıdır.</p>
<p>Bk. Bölüm 5.1</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.3</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sanal Makineler Arasında Zaman Senkronizasyonunun Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Bk. Tedbir No: 5.1.1.11</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.4</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sanallaştırma Yazılımı Güvenlik Duvarının Aktif Olması</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma yazılımı ile beraber gelen güvenlik duvarı aktif olmalı
ve sadece ihtiyaç duyulan portlar üzerinden ihtiyaç duyulan IP
adreslerine erişime izin vermelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.5</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Mantıksal Birim Numarası (LUN) Maskelemesi Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Depolama alanı ağı (SAN) etkinliğini ayırmak için imar ve mantıksal
birim numarası (LUN) maskeleme kullanılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.6</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sanallaştırma Ünitesi Üzerinden Konsol Erişimlerinin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma ünitelerine erişim sağlayabilen kullanıcıların, sanal
makinelerin sahibi olan kullanıcıların ekranlarını yetkisiz olarak
görüntülemesi engellenmelidir. Ayrıca yetkisiz konsol erişimleri de
engellenmelidir. Her kullanıcı kimlik doğrulaması sonrasında erişim
sağlamalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.7</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sanallaştırma Ünitesinde Kullanıcı Yetkilendirme</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma ünitesinde kullanıcılar en az yetki prensibine uygun
şekilde ilgili kullanıcı rollerine atanmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.8</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Gereksiz Hizmetlerin ve Kullanılmayan Donanımların Kaldırılması</p>
</blockquote></td>
<td><blockquote>
<p>Ana bilgisayardan ve sanal makinelerden gerekli olmayan tüm
hizmetler/donanımlar kaldırılmalıdır. Örneğin, kullanılmayan sanal
donanımlar (sürücüler, ağ adaptörleri vb.) devre dışı bırakılmalıdır.
Ayrıca gereksiz hipervizör hizmetleri (pano paylaşımı, dosya paylaşımı
vb.) devre dışı bırakılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.9</p>
</blockquote></td>
<td>1</td>
<td><blockquote>
<p>Sanal Makineler Üzerindeki Diskler için Disk Küçültme
Konfigürasyonuna Erişimin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Sanal disk küçültme (disk shrinking) işleminin sürekli olarak
yapılması, sanal diskin kullanılamamasına ve veri kaybına sebebiyet
verebileceği için bu ayarı yönetebilecek kullanıcılar belirlenerek,
sadece bu kullanıcıların erişimine izin verilmelidir.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.10</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Sanallaştırma Yazılımının Merkezi Olarak Güncellenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma yazılımı çalıştığı tüm sunucularda merkezi olarak eş
zamanlı güncellenmelidir.</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 10%" />
<col style="width: 30%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Seviyesi</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Tanımı</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.3.2.11</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Sanal Makineler için İz Kayıtlarının Yönetilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma ortamında çalışan sanal makineler için alınan iz
kayıtları kalıcı bir şekilde saklanmalıdır. Ayrıca bu iz kayıtları
merkezi bir kayıt sistemine gönderilmelidir.</p>
<p>Bk. Tedbir No: 3.1.8.1 Bk. Tedbir No: 3.1.8.6</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.12</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Sanal Makinelerin Güvenli İmhası</p>
</blockquote></td>
<td><blockquote>
<p>Sanal makineler silinmeden önce, sanal makineye ait disk dosyalarına
sıfır yazılmalı ve daha sonrasında kalıcı silme işlemi yapılmalıdır.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.13</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Hipervizörler Tarafından Sunulan Bellek Paylaşımı Özelliklerinin
Kullanımı</p>
</blockquote></td>
<td><blockquote>
<p>Bellek paylaşımı (memory sharing) kullanılmıyor ise devre dışı
bırakılmalıdır. Eğer bellek paylaşımı özelliği kullanılacak ise sanal
makineler arasında gruplandırma gibi gerekli güvenlik önlemleri
alınmalıdır.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.14</p>
</blockquote></td>
<td>2</td>
<td><blockquote>
<p>Sunucu Yedeklerinin Alınması</p>
</blockquote></td>
<td><blockquote>
<p>Düzenli olarak sunucu sistem yedekleri alınmalıdır. Yedekler yetkisiz
erişime karşı güvenli ortamlarda muhafaza edilmelidir. Belirli
aralıklarla yedekten geri dönme testleri gerçekleştirilmelidir.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.15</p>
</blockquote></td>
<td>3</td>
<td><blockquote>
<p>Disk ve İmajların Şifreli Olarak Saklanması</p>
</blockquote></td>
<td><blockquote>
<p>Sanal makineye ait imajlar ve anlık görüntüler şifreli olarak
muhafaza edilmelidir. Ayrıca, sanal makinelerde disk seviyesinde
şifreleme yapılmalıdır.</p>
</blockquote></td>
</tr>
</tbody>
</table>

> Denetim Maddeleri

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.3.2.1</p>
</blockquote></td>
<td><blockquote>
<p>Güncel Sanallaştırma Yazılımının Kullanılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma sunucusu için kullanılan sanallaştırma yazılımı güncel
midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.2</p>
</blockquote></td>
<td><blockquote>
<p>Konteynerların /Sanal Makinelerin Çalıştığı Ana Makine Üzerinde
Sıkılaştırmaların Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>İşletim sistemi sıkılaştırmaları en iyi çözüm önerilerine uygun
mudur?</p>
<p>Bk. Bölüm 5.1</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.3</p>
</blockquote></td>
<td><blockquote>
<p>Sanal Makineler Arasında Zaman Senkronizasyonunun Sağlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sanal makineler arasında zaman senkronizasyonunun sağlanması için
gerekli yapılandırma sağlanmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.4</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma Yazılımı Güvenlik Duvarının Aktif Olması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma yazılımı güvenlik duvarı aktif midir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.5</p>
</blockquote></td>
<td><blockquote>
<p>Mantıksal Birim Numarası (LUN) Maskelemesi Yapılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>SAN etkinliğini ayırmak için LUN maskeleme yapılmış mıdır?</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 22%" />
<col style="width: 18%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Tedbir No.</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Tedbir Adı</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Yöntem Önerileri</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Denetim Soru Önerileri</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>5.3.2.6</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma Ünitesi Üzerinden Konsol Erişimlerinin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma ünitesi üzerinde konsol kısıtlaması için gerekli
yapılandırma var mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.7</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma Ünitesinde Kullanıcı Yetkilendirme</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sanal makinelere ait imajlar ve anlık görüntülere erişim yetkisi
kimlere verilmektedir?</p>
<p>Erişim yetkileri en az yetki prensibine uygun olarak mı
verilmektedir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.8</p>
</blockquote></td>
<td><blockquote>
<p>Gereksiz Hizmetlerin ve Kullanılmayan Donanımların Kaldırılması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Ana makine ile sanal makine arasında dosya paylaşımında gerekli
kısıtlamalar uygulanmış mıdır?</p>
<p>Sanal makine üzerinde kullanılan/çalışmakta olan gereksiz
donanım/hizmet mevcut mudur?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.9</p>
</blockquote></td>
<td><blockquote>
<p>Sanal Makineler Üzerindeki Diskler için Disk Küçültme
Konfigürasyonuna Erişimin Kısıtlanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Disk kapasite küçültme işlemi için kullanıcı bazlı izin tanımlaması
mevcut mudur?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.10</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma Yazılımının Merkezi Olarak Güncellenmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma yazılımı merkezi olarak güncellenmekte midir?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.11</p>
</blockquote></td>
<td><blockquote>
<p>Sanal Makineler için İz Kayıtlarının Yönetilmesi</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Sanal makineler için iz kayıtları tutulmakta mıdır?</p>
<p>Tutulan bu kayıtlar merkezi bir kayıt sistemine gönderilmekte
midir?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.12</p>
</blockquote></td>
<td><blockquote>
<p>Sanal Makinelerin Güvenli İmhası</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Sanal makinelerin güvenli imhası için belirli bir politika bulunmakta
mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.13</p>
</blockquote></td>
<td><blockquote>
<p>Hipervizörler Tarafından Sunulan Bellek Paylaşımı Özelliklerinin
Kullanımı</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Hipervizörler tarafından sunulan bellek paylaşımı özellikleri
kullanılmakta mıdır?</p>
<p>Sanal makineler arasında bellek paylaşımı ile ilgili bir gruplandırma
yapılmış mıdır?</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>5.3.2.14</p>
</blockquote></td>
<td><blockquote>
<p>Sunucu Yedeklerinin Alınması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme</p>
</blockquote></td>
<td><blockquote>
<p>Sanallaştırma sisteminin yedeklemesi yapılmakta mıdır?</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>5.3.2.15</p>
</blockquote></td>
<td><blockquote>
<p>Disk ve İmajların Şifreli Olarak Saklanması</p>
</blockquote></td>
<td><blockquote>
<p>Mülakat, Gözden Geçirme, Güvenlik Denetimi</p>
</blockquote></td>
<td><blockquote>
<p>Sanal makinelere ait diskler şifreli olarak korunmaktadır? Anlık
görüntüler şifreli olarak korunmakta mıdır?</p>
</blockquote></td>
</tr>
</tbody>
</table>
