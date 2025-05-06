# Restoran Sipariş ve Yönetim Sistemi

# Programın amacı nedir?

Programın amacı müşterilerin menüden seçtiği yiyecek ve içecekleri teslim etme sürecini yönetmektir. 

# Sipariş Al Sayfası

Bu sayfadan daha önceden eklediğimiz menü ürünlerini, daha önceden eklemiş olduğumuz müşterilere satışını yapıyoruz. 

Eğer bir üründen birden daha fazla kez sipariş vermek istiyorsak ürünü seçip sepete eklemeden Adet kısmından adet miktarını değiştirmemiz gerekiyor.

Müşterinin sepetini hazırladıktan sonra Siparişi ver butonuna tıklayarak siparişi verebiliyoruz. Siparişi verdikkten sonraki işlemleri aktif siparişler kısmından yapmalıyız.

![image](https://github.com/user-attachments/assets/1754db6c-fe3d-4516-b2b2-dc221035c322)

# Aktif Siparişler Sayfası

Bu sayfayı "Sipariş Al" sayfasından verilen siparişleri yönetmek için kullanıyoruz. Aktif siparişler bu sayfada gözüküyor.

Aktif siparişin durumunu "Alındı, Hazırlanıyor, Yolda, Teslim Edildi, İptal Edildi" olarak güncelleyebiliyoruz. 

Eğer bir siparişi seçersek siparişin detayı "Seçili Sipariş Detayı" kısmında gözükmektedir.

![image](https://github.com/user-attachments/assets/7d3225d0-0ae8-4f4a-acfe-ad71a1c6db0d)


# Menü Yönetimi Sayfası

Müşterilere satışını yapacağımız menü ürünlerini bu sayfadan ekliyoruz.

Ekleyeceğimiz ürünün adını, adet fiyatını ve başlangıç stoğunu girip "Yeni Ürün Ekle" butonuna basarak ürünü ekleyebiliyoruz.

Eğer mevcut ürünlerden bir ürünün stoğunu güncellemek istersek seçtikten sonra yeni stok adedi kısmına ürünü kaç stok yapmak istiyorsak onu yazıyoruz.

![image](https://github.com/user-attachments/assets/e1b952a8-daf1-4cb6-89b2-260ae562383c)


# Müşteri Yönetimi Sayfası

Bu kısımdan sipariş verecek müşterileri ekliyoruz. 

Müşterinin adı soyadını, adresini ve telefon numarasını yazdıktan sonra "Yeni Müşteri Ekle" butonuna basarak ekliyoruz.

Daha sonrasında eklediğimiz müşteriyi silmek istersek kayıtlı müşteriler kısmından müşteriyi seçerek "Sil" butonuna basıyor ve siliyoruz. Düzenlemek istersekde seçtikten sonra "Düzenle" butonuna basarak düzenliyoruz.

![image](https://github.com/user-attachments/assets/3f1e5030-a6f4-4815-8a0b-6678176d765d)

# Geçmiş Siparişler Sayfası

Bu sayfayı kullanarak geçmiş siparişleri görüntüleyebiliyoruz.

![image](https://github.com/user-attachments/assets/451f2d31-533f-4f26-a30b-bfc30f5e146b)


# Veri Kaydedilmesi

Uygulamada bir işlem yapıldığında veriler otomatik olarak kodun çalıştığı klasöre "data" isimde bir klasör oluşturularak bu klasör içerisine her işlem katagorisi için ayrı bir dosya açılarak kaydediliyor. (aktif_siparisler.json, gecmis_siparisler.json, musteriler.json, urunler.json)

# Uygulama Kurulumu

Uygulamayı kurmak için ilk olarak Visual Studio Code uygulamasını kurup eklentiler kısmından Python'u kuruyoruz. Sonrasında projeyi indirip rardan çıkartıyoruz. restoran.py adındaki dosyayı visual studio code ile açıp çalıştırıyoruz.



