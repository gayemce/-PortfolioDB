# Portfolio Database Design

Bu README dosyası, **PortfolioDB** adlı veritabanı tasarımını açıklamak ve içerdiği tablolar arasındaki ilişkiyi anlatmak için hazırlanmıştır.

## Proje Tanımı

Bu proje, kişisel bir portfolyo websitesi için gerekli veritabanı yapısını içermektedir. Proje, kullanıcıların yeteneklerini, blog yazılarını, iletişim bilgilerini, deneyimlerini ve daha fazlasını saklamak ve yönetmek için tasarlanmıştır.

## Portfolyo Veritabanı Diyagramı

![Portfolio Database Diagram](PortfolioDB.png)

## Tablolar ve İlişkiler

Veritabanı, aşağıdaki tabloları içermektedir:

### Users
Kullanıcıların temel bilgilerini içerir. Kullanıcı adı, e-posta, telefon numarası gibi bilgiler bu tabloda tutulur.

- **Id**: Kullanıcı kimlik numarası.
- **Name**: Kullanıcının adı.
- **Email**: Kullanıcının e-posta adresi.
- **PhoneNumber**: Kullanıcının telefon numarası.
- **AboutMe**: Kullanıcının kendisi hakkında açıklama.
- **ShortAboutMe**: Kullanıcının kendisi hakkında kısa bir açıklaması.
- **Password**: Kullanıcının şifresi.

### Abilities
Kullanıcıların sahip olduğu yetenekleri temsil eder. Yetenek adı, yüzde değeri ve simgesi gibi bilgiler bu tabloda saklanır.

- **Id**: Yetenek kimlik numarası.
- **Name**: Yeteneğin adı.
- **IsActive**: Yeteneğin aktif olup olmadığı.
- **Percent**: Yetenek yüzde değeri.
- **ImageUrl**: Yeteneği gösteren bir resim URL'i.

- 
### Blogs
Kullanıcıların yazdığı blog yazılarını içerir. Başlık, kapak resmi URL'si, içerik ve tarih gibi önemli detaylar bu tabloda bulunur.

- **Id**: Blog kimlik numarası.
- **Title**: Blog yazısının başlığı.
- **CoverImgUrl**: Blog yazısının kapak resmi URL'i.
- **Content**: Blog yazısının içeriği.
- **Date**: Blog yazısının tarihi.

### Contacts
İletişim formundan gelen iletişim taleplerini saklar. Ad, e-posta, konu, içerik, tarih ve tamamlanma durumu gibi bilgiler bu tabloda yer alır.

- **Id**: İletişim talep kimlik numarası.
- **Name**: Gönderenin adı.
- **Email**: Gönderenin e-posta adresi.
- **Subject**: İletişim talebinin konusu.
- **Content**: İletişim talebinin içeriği.
- **Date**: İletişim talebinin tarihi.
- **IsCompleted**: İletişim talebinin tamamlanma durumu.
