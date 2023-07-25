# Aygaz_Data_Analysis_Bootcamp_Final_Project


[Proje Adı]
Airbnb Konaklama Öneri Sistemi

[Proje Özeti]
Bu rapor, New York'ta bulunan Airbnb konaklama listelerini analiz etmek ve kullanıcılara ilgi alanlarına uygun konaklama önerileri sunmak amacıyla geliştirilen "Airbnb Konaklama Öneri Sistemi" projesini detaylı olarak açıklamaktadır. Proje, içeriğe dayalı ve işbirliğine dayalı filtreleme algoritmalarını kullanarak kullanıcıların tercihlerine uygun konaklama listelerini önermektedir.

[Proje Girişi]
Airbnb, dünya genelinde birçok şehirde konaklama imkanı sunan popüler bir platformdur. Bu projede, New York'ta bulunan Airbnb konaklama listeleri kullanılarak, kullanıcılara ilgi alanlarına uygun konaklama önerileri sunmak hedeflenmektedir. Proje için gerekli veri kümesi "NYC Airbnbs-2019" adlı CSV dosyasından yüklenmiştir.

[Proje Amacı]
Bu projenin amacı, New York'ta seyahat etmeyi planlayan kullanıcılara, Airbnb konaklama listeleri arasından ilgi alanlarına uygun ve tercih edebilecekleri konaklama birimlerini önermektir. İçeriğe dayalı filtreleme algoritması, kullanıcıların ilgi alanlarına göre benzer konaklama birimlerini önerirken; işbirliğine dayalı filtreleme algoritması ise kullanıcıların verdiği puanlar aracılığıyla benzer kullanıcıları bulup onların tercihlerine göre önerilerde bulunmaktadır.

[Proje Yöntemi]
Proje, Python programlama dilinde geliştirilmiştir. Ana kütüphaneler arasında "pandas", "numpy", "matplotlib.pyplot", "sklearn.feature_extraction.text.TfidfVectorizer" ve "sklearn.metrics.pairwise.linear_kernel" yer almaktadır. Proje aşağıdaki adımlarla gerçekleştirilmiştir:

1. Veri Kümesinin Yüklenmesi ve Düzenlenmesi: Airbnb konaklama veri kümesi "NYC Airbnbs-2019" CSV dosyasından yüklenmiş ve gerekli sütunlar alınmıştır.

2. AirbnbListings ve User Sınıflarının Tanımlanması: Konaklama listelerini temsil etmek için "AirbnbListing" sınıfı ve kullanıcıları temsil etmek için "User" sınıfı tanımlanmıştır.

3. Airbnb Listelerinin ve Kullanıcıların Oluşturulması: Veri kümesindeki her bir satır için bir "AirbnbListing" örneği oluşturulmuş ve bir dizi kullanıcı oluşturulmuştur.

4. Ratings Oluşturulması: Her bir kullanıcı için, rastgele seçilen Airbnb listelerine rastgele puanlar verilerek "ratings" adlı bir veri yapılmıştır.

5. İlgili Listelerin Eşleştirilmesi: Kullanıcıların ilgi alanları, Airbnb listeleri ile karşılaştırılarak ilgi alanlarına uygun listeler belirlenmiştir.

6. İçeriğe Dayalı Konaklama Önerileri: Kullanıcıların ilgi alanlarından metin vektörleri oluşturulmuş, metin benzerliği hesaplamaları kullanılarak benzer listeler belirlenmiştir.

7. İşbirliğine Dayalı Filtreleme ile Konaklama Önerileri: Kullanıcının verdiği puanlar ve diğer kullanıcıların verileri kullanılarak benzer kullanıcılar belirlenmiş ve onların tercihlerine göre yeni öneriler yapılmıştır.

8. Sonuçların Görselleştirilmesi: Konaklama birimlerinin fiyat dağılımı histogramı çizilmiştir.

[Proje Çıktıları]
Proje sonucunda, kullanıcılar için içeriğe dayalı ve işbirliğine dayalı filtreleme algoritmaları kullanılarak konaklama önerileri sunulmuştur. Kullanıcılar, ilgi alanlarına uygun konaklama birimlerini kolayca bulabilir ve tercihlerine göre seçim yapabilirler. Ayrıca, konaklama birimlerinin fiyat dağılımı görselleştirilerek, kullanıcılar için genel bir fiyat aralığı sunulmuştur.

[Projede Kullanılan Algoritmalar]
1. İçeriğe Dayalı Filtreleme: Kullanıcının ilgi alanlarından metin vektörleri oluşturulmuş ve benzerlik matrisi hesaplanarak ilgi alanlarına uygun konaklama birimleri önerilmiştir.

2. İşbirliğine Dayalı Filtreleme: Kullanıcının verdiği puanlar ve diğer kullanıcıların puanları kullanılarak benzer kullanıcılar belirlenmiş ve onların tercihlerine göre yeni konaklama birimleri önerilmiştir.

[Proje Sonuçları ve Öneriler]
Proje, içeriğe dayalı ve işbirliğine dayalı filtreleme algoritmalarının kullanılmasıyla başarılı bir şekilde kullanıcılara konaklama önerileri sunmaktadır. Bu öneriler, kullanıcıların ilgi alanları ve tercihlerine göre şekillenmektedir. Proje, veri kümesine ve kullanıcıların puanlarına bağlı olarak daha da geliştirilebilir ve kişiselleştirilmiş öneriler sunacak şekilde güncellenebilir.

[Proje Sonu]
Bu proje, New York'ta seyahat etmeyi düşünen kullanıcılara uygun konaklama önerileri sunmak için geliştirilen bir öneri sistemi olarak başarılı bir şekilde tamamlanmıştır. İçeriğe dayalı ve işbirliğine dayalı filtreleme algoritmaları, kullanıcılara kişiselleştirilmiş öneriler sunmada etkili bir rol oynamaktadır. Proje, daha fazla veri ve geliştirme ile daha kapsamlı ve hassas bir öneri sistemi haline getirilebilir.

