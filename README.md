# TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) Yöntemi
Endikasyon ölçütüne göre antidepresan ilaçlarının verilen kriterlere göre topsis yöntemiyle sıralanması

TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) Yöntemi

Adım 1: Karar Matrisinin(A) Oluşturulması
Yöntemin ilk aşamasında her bir alternatifin performans değerinin her bir kriter tarafından belirtilerek matris şeklinde ifade edilmesidir. Karar matrisinin sütunlarında kriterlerden oluşurken, satırlarda ise sıralanmak istenen alternatiflerden meydana gelmektedir.   Matrisinde m karar noktası sayısını, n değerlendirme faktörü (kriter) sayısını verir. Karar matrisi aşağıdaki gibi gösterilir. ![image](https://user-images.githubusercontent.com/83714984/174067404-65b0fff9-3234-456d-8cc0-5fb1e91c9730.png)

Adım 2: Standart Karar Matrisinin (R) Oluşturulması
Olarak ifade edilen normalize edilmiş karar matrisi   matrisinin elemanlarından yararlanarak ve aşağıdaki formül kullanılarak hesaplanır. ![image](https://user-images.githubusercontent.com/83714984/174067436-8fcb1c0e-fe61-4a4e-8715-dff6dec4494a.png)

Matrisin gösterimi aşağıdaki gibidir. ![image](https://user-images.githubusercontent.com/83714984/174067454-d7e7b822-1903-4e63-8036-e8a75a4e6156.png)

 
Adım 3: Normalize Edilmiş Karar Matrisinin Ağırlıklandırılması
Öncelikle kriterlere ilişkin ağırlık değerleri ( ) belirlenir . Daha sonra  matrisinin her bir sütunundaki elemanlar ilgili  değeri ile çarpılarak ağırlıklı normalize matrisi olarak ifade edilen  oluşturulur. ![image](https://user-images.githubusercontent.com/83714984/174067473-1eb1788f-5b92-4d95-aaa9-5dc2ee7a4024.png)
 
Adım 4: İdeal ve Negatif İdeal Çözümlerin Belirlenmesi
Ağırlıklı normalize edilmiş değerlere göre pozitif-ideal çözüm ( ) ve negatif-ideal çözüm ( belirlenir. İdeal çözüm setinin bulunması aşağıdaki formülde gösterilmiştir.
![image](https://user-images.githubusercontent.com/83714984/174067504-ec968c55-56a5-4856-a116-171368ccde1d.png)

Her iki formülde de J fayda (maksimizasyon)   ise kayıp (minimizasyon) değerini göstermektedir. Hem pozitif ideal hem de negatif ideal noktaların çözümleri belirtilen kriterlerin durumlarını hesaplamaktadır. 
Adım 5: Ayırım Ölçülerinin Hesaplanması: 
Alternatifler arasındaki mesafe, n boyutlu Öklid Uzaklık Yaklaşımından faydalanılarak bulunmaktadır. Her alternatifin pozitif-ideal çözümden olan mesafesi ( ) ve negatif-ideal çözümden olan mesafesi (   ) şu şekilde hesaplanmaktadır: 
![image](https://user-images.githubusercontent.com/83714984/174067544-5f5c02dc-e180-4f38-be76-890a1166bcc3.png)

Adım 6: İdeal Çözüme Göreli Yakınlığın Hesaplanması
Her bir alternatifin ideal çözüme göreli yakınlığı (  ) pozitif-ideal ve negatif-ideal ayırım ölçüsüne göre; negatif-ideal ayırım ölçüsünün toplam ayırım ölçüsü içindeki payı şeklinde aşağıdaki gibi hesaplanır: 
![image](https://user-images.githubusercontent.com/83714984/174067559-6bc76843-18ca-4f18-8e26-3430bf3b5cfa.png)

