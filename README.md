# Portfolio Database Design

Bu README dosyası, **PortfolioDB** adlı veritabanı tasarımını açıklamak ve içerdiği tablolar arasındaki ilişkiyi anlatmak için hazırlanmıştır.

## Proje Tanımı

Bu proje, kişisel bir portfolyo websitesi için gerekli veritabanı yapısını içermektedir. Proje, kullanıcıların yeteneklerini, blog yazılarını, iletişim bilgilerini, deneyimlerini ve daha fazlasını saklamak ve yönetmek için tasarlanmıştır.

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
- **ImageUrl**: Yeteneği gösteren bir resim URL'si.
