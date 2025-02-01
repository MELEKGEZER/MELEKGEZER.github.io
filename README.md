# Proje Adı
Kullanıcı ve Proje Yönetim Paneli (1.sınıf web programlama dersi için yapılan bir ödev)

## Açıklama
Bu proje, kullanıcıların adlarını, proje isimlerini ve tarihleri kaydedebildiği basit bir web uygulamasıdır. Kullanıcılar form üzerinden veri girişi yaparak, girilen bilgileri tabloya ekleyebilirler. Ayrıca, bilgiler bir API'ye gönderilir ve geri alınarak tabloda görüntülenir.

## Kullanılan Teknolojiler
- **HTML**: Sayfa yapısını oluşturmak için kullanıldı.
- **CSS (Bootstrap, Animate.css, FontAwesome)**: Sayfanın stilini ve duyarlılığını artırmak için kullanıldı.
- **JavaScript (Vanilla JS, jQuery)**: Dinamik içerik yönetimi ve API istekleri için kullanıldı.
- **jspdf**: Sayfa içeriğini PDF formatına dönüştürmek için kullanıldı.
- **reqres.in API**: Test verileri göndermek ve almak için kullanıldı.


## Kullanım
1. **Formu Doldurun:** Ad, Proje Adı ve Tarih bilgilerini girin.
2. **Kaydet Butonuna Basın:** Bilgiler tabloya eklenir ve API'ye gönderilir.
3. **Verileri Görüntüleyin:** API'den dönen yanıtla birlikte tablo güncellenir.

## API Kullanımı
- **POST İsteği:** Kullanıcı bilgileri `https://reqres.in/api/users` adresine gönderilir.
- **Yanıt:** API başarılı bir şekilde çalışırsa girilen veriler geri alınır ve tabloya eklenir.

## Geliştirme
- Daha güçlü bir backend API ile entegrasyon sağlanabilir.
- Veritabanı bağlantısı ile kalıcı veri saklama işlemleri eklenebilir.
- Daha iyi bir kullanıcı deneyimi için ek özellikler geliştirilebilir.



