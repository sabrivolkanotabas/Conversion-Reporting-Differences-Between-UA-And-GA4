
Universal Analytics ve Google Analytics 4 Arasındaki 

Dönüşüm Değerleri Farklılıkları


   Universal Analytics, dönüşümleri hedefler üzerinden ölçümlemektedir. Google Analytics 4 ise ölçümlenmesinin katkıda bulunduğu belirlenen tüm eventleri dönüşüm olarak ölçümleyebilmektedir.

Universal Analytics’de bir dönüşüm, oturum başına yalnızca bir kez sayılmaktadır. Google Analytics 4'de ise bir dönüşüm, kullanıcının oturumu başına birden çok kez sayılabilir.

Örneğin;
                “formsuccess_kulakçık” bir dönüşüm olarak tanımlandığında,

Universal Analytics, bir kullanıcıyı aynı oturumda kaç kez form doldurursa doldursun yalnızca bir form doldurması dönüşümü olarak saymaktadır.

Google Analytics 4'de ise bir kullanıcı aynı oturumda bir formu iki kez doldurduğunda iki dönüşüm sayılacaktır.



   Dönüşüm Modellemeleri, kullanıcıları tanımlamadan (kullanıcı gizliliği, teknik sınırlamalar veya kullanıcılar cihazlar arasında hareket ettiğinden dolayı) doğru dönüşüm ilişkilendirmesi yapılmasına olanak tanır.

Kullanıcılarınızın ölçümleme için gizlilik onayı vermemesi durumunda Google Analytics algoritması, eksik verileri mümkün olduğu kadar tamamlamaya çalışmaktadır. 

Yalnızca verinin doğruluğundan yüksek oranda emin olduğunda dönüşüm olarak saymaktadır. Bu durum, Universal Analytics ve Google Analytics 4 verileri arasında farklılığa yol açabilmektedir.
