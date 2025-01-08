
# Feature Dökümanı: Namaz Vakitleri Mobil Uygulaması

## 1. Lokasyon Bazlı Namaz Vakitleri

### Tanım
Uygulama, kullanıcının bulunduğu konuma göre günlük, haftalık ve aylık namaz vakitlerini gösterecektir.

### Ana Özellikler
- **Günlük Namaz Vakitleri:** Bugüne özel namaz vakitlerinin listelenmesi.
- **Haftalık ve Aylık Görünüm:** Kullanıcıların yaklaşan namaz vakitlerini detaylı şekilde görüntülemesi.
- **Lokasyon Tespiti:** GPS ve harita entegrasyonu ile kullanıcı konumunun belirlenmesi.
- **API Entegrasyonu:** Namaz vakitleri, üçüncü parti API’lerden çekilecektir.

---

## 2. Cami Bulma Özelliği

### Tanım
Kullanıcılar, bulundukları lokasyona en yakın camileri harita üzerinde görebilecek ve yönlendirme alabilecek.

### Ana Özellikler
- **Harita Entegrasyonu:** Google Maps veya Apple Maps kullanılarak camilerin haritada görüntülenmesi.
- **Mesafe Bilgisi:** Camilerin mesafelerinin kullanıcıya gösterilmesi.
- **Listeleme:** Harita görünümü yanı sıra camilerin listelenmesi.
- **Yönlendirme:** Seçilen camiye navigasyon desteği.

---

## 3. Kıble Pusulası

### Tanım
Cihazın sensörleri kullanılarak kıble yönü doğru şekilde gösterilecektir.

### Ana Özellikler
- **Gerçek Zamanlı Pusula:** Telefon hareket ettirildiğinde kıble yönü anlık olarak değişir.
- **Animasyonlu Gösterim:** Kullanıcı deneyimini artırmak için animasyonlu bir pusula.
- **Kalibrasyon Desteği:** Kullanıcıya cihaz sensörlerini doğru kalibre etmesi gerektiğinde bilgi verilmesi.

---

## 4. İmsakiye

### Tanım
Kullanıcılar, yıllık imsak vakitlerini ve önemli dini günleri görebilecektir.

### Ana Özellikler
- **Yıllık Takvim:** Tüm yılın imsak vakitlerini içeren detaylı takvim.
- **Dini Günler Listesi:** Ramazan, Mevlid Kandili gibi önemli günlerin tarihleri.
- **Bildirimler:** Yaklaşan dini günler için hatırlatıcı bildirimler.

---

## 5. Günün Hadisi, Duası ve Ayeti

### Tanım
Uygulama her gün rastgele bir hadis, dua ve ayet sunacaktır.

### Ana Özellikler
- **Günlük Gösterim:** Her gün yeni içerik otomatik olarak güncellenir.
- **Veritabanı Kullanımı:** Hadis, dua ve ayetler bir veritabanından çekilir.
- **Favorilere Ekleme:** Kullanıcılar beğendikleri içerikleri favorilere ekleyebilir.
- **Paylaşma:** İçerikler sosyal medya veya mesajlaşma uygulamalarında paylaşılabilir.

---

## 6. Namaz Bildirimleri

### Tanım
Namaz vakitleri geldiğinde kullanıcıya sesli veya sessiz bildirimler gönderilir.

### Ana Özellikler
- **Kişiselleştirilebilir Bildirimler:** Kullanıcı, bildirimlerin sesli veya sessiz olmasını seçebilir.
- **Ses Dosyası Seçimi:** Kullanıcı, ezan, tekbir veya farklı bir bildirim sesi seçebilir.
- **Öncelik:** Her namaz için ayrı bildirim ayarları yapılabilir (örn. sabah için sesli, diğer vakitler için sessiz).

---

## 7. Tema ve Kişiselleştirme

### Tanım
Kullanıcı arayüzü, kullanıcı tercihine göre kişiselleştirilebilir.

### Ana Özellikler
- **Karanlık ve Aydınlık Mod:** Uygulama teması tercihe göre değiştirilebilir.
- **Dil Desteği:** Türkçe, İngilizce gibi birden fazla dil desteği sağlanabilir.
- **Widget Desteği:** Ana ekran widget’ları ile namaz vakitleri kısa yoldan görüntülenebilir.

---

## 8. Güvenlik ve Performans

### Tanım
Kullanıcı verilerinin güvenliği ve uygulamanın hızlı çalışması sağlanacaktır.

### Ana Özellikler
- **Konum Gizliliği:** Kullanıcının konum verileri yalnızca namaz vakitleri ve cami bulma işlemleri için kullanılacaktır.
- **Performans Optimizasyonu:** Hızlı yüklenme süreleri ve düşük enerji tüketimi.
- **Veritabanı Güvenliği:** Tüm kullanıcı ve içerik verileri güvenli bir şekilde saklanır.

---

## Ek Özellikler
- **Push Bildirimleri:** Özel günler veya önemli vakitlerde kullanıcıya genel bildirimler gönderilebilir.
- **Offline Mod:** İnternet bağlantısı olmadan son yüklenen namaz vakitlerine erişim sağlanabilir.
- **Dua Listesi:** Kullanıcıların kendi dualarını kaydedip düzenleyebileceği bir alan.
