# Gizlilik Politikası — Koordinatör: İşletme Takip

**Uygulama Adı:** Koordinatör: İşletme Takip  
**Paket Adı:** `com.muhammedyalcinkaya.mebkoordinator`  
**Geliştirici:** Muhammed Yalçınkaya  
**Son Güncelleme:** 19 Kasım 2026  

> **Bağımsız Uygulama Beyanı:** Bu uygulama Millî Eğitim Bakanlığı'nın (MEB) resmi bir uygulaması değildir ve herhangi bir devlet kurumunu temsil etmez. Mesleki eğitimde koordinatör öğretmenlerin saha ziyaretlerini, yoklama ve tutanak işlemlerini kolaylaştırmak amacıyla bağımsız olarak geliştirilmiştir.

## 1. Toplanan Veriler ve Yerel Depolama (%100 Çevrimdışı)
**Koordinatör: İşletme Takip** uygulaması, kullanıcı tarafından girilen işletme, stajyer öğrenci, yoklama, öğretmen/okul profil bilgileri ve ziyaret fotoğraflarını **yalnızca kullanıcının kendi Android cihazındaki yerel SQLite (Room) veritabanında ve uygulama içi depolama alanında** saklar. Geliştiriciye ait hiçbir harici sunucuya kişisel veri aktarılmaz.

## 2. İzinlerin Kullanım Amacı
- **Kamera (`CAMERA`):** İşletme ziyareti sırasında anlık saha fotoğrafı çekmek için kullanılır. Galeriden eski fotoğraf seçilmesine izin verilmez.
- **Konum (`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`):** Ziyaret tutanaklarına ve fotoğraf damgasına anlık GPS enlem-boylam koordinatını eklemek için kullanılır.
- **İnternet ve Reklam Kimliği (`INTERNET`, `ACCESS_NETWORK_STATE`, `AD_ID`):** Yalnızca Google AdMob reklam banner'larının gösterimi ve varsa cihazın adres çözümleme (Geocoder) işlemi için kullanılır. Temel saha işlevleri internet bağlantısı olmadan çevrimdışı çalışır.

## 3. Üçüncü Taraf Hizmetler (Google AdMob)
Uygulama, ücretsiz sunulabilmesi amacıyla Google AdMob reklam hizmetini içerebilir. Google AdMob, reklam sunumu ve ölçümleme amacıyla cihazın reklam kimliğini (`AD_ID`) Google'ın kendi gizlilik politikasına tabi olarak işleyebilir. Öğrenci, işletme, yoklama veya PDF/Excel belgelerindeki hiçbir veri AdMob ile paylaşılmaz.

## 4. Verilerin Silinmesi ve İletişim
Tüm veriler cihazınızda yerel olarak tutulduğu için uygulamayı sildiğinizde tüm veriler kalıcı olarak silinir. İletişim: `systemfailed20@gmail.com`
