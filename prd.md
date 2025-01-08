
# Product Requirements Document (PRD): Namaz Vakitleri Mobil Uygulaması

## 1. Genel Bilgiler

### 1.1. Proje Adı
Namaz Vakitleri Uygulaması

### 1.2. Amaç
Namaz Vakitleri Uygulaması, kullanıcıların bulundukları lokasyona özel namaz vakitlerini öğrenebileceği, en yakın camilere ulaşabileceği ve kıble yönünü kolayca bulabileceği bir araç sunmayı amaçlamaktadır. Uygulama aynı zamanda dini günler, hadisler, dualar ve ayetler gibi bilgilendirici içeriklerle kullanıcıların günlük dini hayatlarını desteklemeyi hedefler.

### 1.3. Hedef Kitle
- Müslüman bireyler
- Namaz vakitlerini takip etmek isteyenler
- Kıble yönü bulma ve camilere kolayca ulaşma ihtiyacı olanlar

---

## 2. Ana Özellikler

### 2.1. Namaz Vakitleri
- **Lokasyon Bazlı Vakitler:** Kullanıcıların konumuna göre namaz vakitleri görüntülenir. 
- **Günlük/Haftalık/Aylık Görüntüleme:** Kullanıcılar namaz vakitlerini günlük, haftalık veya aylık olarak görüntüleyebilir.
- **API Entegrasyonu:** Namaz vakitleri, 3. parti bir API (örn. Diyanet İşleri Başkanlığı API'si) aracılığıyla sağlanacaktır.
- **Bildiriler:** Namaz vakti geldiğinde bildirim gönderilir. Bildirimler isteğe bağlı olarak sesli ya da sessiz olabilir.

### 2.2. Cami Bulma Özelliği
- Kullanıcının mevcut konumuna göre en yakın camiler harita üzerinde görüntülenir.
- Camilerin adı, adresi ve mesafesi belirtilir.
- Harita entegrasyonu (örn. Google Maps) ile kullanıcı yönlendirilir.

### 2.3. Kıble Pusulası
- Pusula animasyonu ile sürekli kıble yönü gösterilir.
- Telefonun sensörlerinden faydalanılarak doğru yön tespiti yapılır.

### 2.4. İmsakiye
- Yıl boyunca imsak vakitlerini ve dini günleri listeleyen bir bölüm.

### 2.5. Dini Günler ve Geceler
- Ramazan, Kadir Gecesi, Mevlid Kandili gibi önemli dini günler uygulama içinde ayrı bir sayfada listelenir.

### 2.6. Günün Hadisi, Duası ve Ayeti
- Veritabanında bulunan hadis, dua ve ayetlerden her gün rastgele birer içerik seçilerek kullanıcılara sunulur.
- Kullanıcılar bu içerikleri favorilere ekleyebilir ve sosyal medya üzerinden paylaşabilir.

### 2.7. Bildirim Özellikleri
- Namaz vakitleri geldiğinde kullanıcılara bildirim gönderilir.
- Bildirim sesleri: Kullanıcı, veritabanından sunulan ses dosyalarını seçebilir (örn. ezan, tekbir, sessiz mod vb.).

---

## 3. Teknik Gereksinimler

### 3.1. Platformlar
- **iOS:** iOS 12 ve üzeri cihazlar.
- **Android:** Android 7.0 ve üzeri cihazlar.

### 3.2. Geliştirme Ortamı
- **Teknoloji:** React Native
- **Backend:** Node.js ya da Django (tartışılabilir)
- **Veritabanı:** Firebase veya PostgreSQL
- **Harita API:** Google Maps veya alternatifleri
- **Namaz Vakti API:** Diyanet İşleri Başkanlığı API’si ya da benzeri üçüncü taraf API’ler

### 3.3. Entegrasyonlar
- Harita entegrasyonu (Google Maps veya Apple Maps)
- Konum servisi (GPS)
- Üçüncü taraf API entegrasyonu (Namaz vakitleri için)

---

## 4. Kullanıcı Arayüzü (UI/UX)

### 4.1. Ana Ekran
- Günün tarihine göre namaz vakitleri listesi.
- Günün hadisi, duası ve ayeti bölümü.

### 4.2. Kıble Pusulası
- Tam ekran kıble yönü gösteren pusula.
- Minimalist tasarım ve animasyon.

### 4.3. Cami Bulma
- Harita görünümü ve listeleme seçeneği.
- Her cami için mesafe bilgisi.

### 4.4. Ayarlar
- Bildirim tercihleri (sesli/sessiz mod).
- Bildirim sesi seçimi.
- Tema seçimi (aydınlık/karanlık mod).

---

## 5. Performans ve Güvenlik

### 5.1. Performans
- Minimum gecikme ile namaz vakitlerini ve harita verilerini sunacak optimizasyonlar.
- Kullanıcı arayüzünün hızlı ve akıcı çalışması.

### 5.2. Güvenlik
- Kullanıcı konum verileri güvenli şekilde işlenir ve üçüncü taraflarla paylaşılmaz.
- API anahtarları ve veritabanı erişimi güvenli şekilde saklanır.

---

## 6. Zaman Çizelgesi

### 6.1. Geliştirme Aşamaları
1. **Planlama ve Tasarım:** 2 hafta
2. **Backend Geliştirme:** 4 hafta
3. **Frontend Geliştirme:** 6 hafta
4. **Test Süreci:** 3 hafta
5. **Yayınlama:** 1 hafta

---

## 7. Başarı Kriterleri
- Kullanıcıların namaz vakitlerine kolay erişim sağlaması.
- Kıble yönünün doğru ve güvenilir şekilde gösterilmesi.
- En yakın cami bilgilerine hızlıca ulaşabilme.
- Kullanıcıların bildirimleri kişiselleştirebilmesi.
