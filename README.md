# Dataset
https://www.kaggle.com/datasets/rohanharode07/webmd-drug-reviews-dataset

## TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) Yöntemi

TOPSIS yöntemi, 6 aşamalı bir süreçten oluşmaktadır. TOPSIS yönteminin adımları aşağıda açıklanmıştır.
1.Alternatiflerin ve kriter ağırlıklarının belirlenmesi
2.Normalize ve ağırlıklı karar matrisinin oluşturulması
3.Pozitif ideal noktası, Negatif ideal noktası çözümlerinin belirlenmesi
4.Ayırım ölçütlerinin belirlenmesi 
5.İdeal çözüme yakınlığın hesaplanması
6.Sıralama ve tercihin yapılması

Adım 1: Karar Matrisinin(A) Oluşturulması
Yöntemin ilk aşamasında her bir alternatifin performans değerinin her bir kriter tarafından belirtilerek matris şeklinde ifade edilmesidir. Karar matrisinin sütunlarında kriterlerden oluşurken, satırlarda ise sıralanmak istenen alternatiflerden meydana gelmektedir. Matrisinde m karar noktası sayısını, n değerlendirme faktörü (kriter) sayısını verir. Karar matrisi aşağıdaki gibi gösterilir. 

![image](https://user-images.githubusercontent.com/83714984/174070546-b4a60e1e-4785-4399-85dc-f77b5bc290c0.png)

Adım 2: Standart Karar Matrisinin (R) Oluşturulması 
Olarak ifade edilen normalize edilmiş karar matrisi   matrisinin elemanlarından yararlanarak ve aşağıdaki formül kullanılarak hesaplanır. 

![image](https://user-images.githubusercontent.com/83714984/174070515-3ae3a8fd-b82e-4dad-9d86-72af16c886db.png)

Matrisin gösterimi aşağıdaki gibidir. 

![image](https://user-images.githubusercontent.com/83714984/174070477-fab34162-3bfa-4c56-8998-9b3ee698c51a.png)

Adım 3: Normalize Edilmiş Karar Matrisinin Ağırlıklandırılması 
Öncelikle kriterlere ilişkin ağırlık değerleri ( ) belirlenir . Daha sonra  matrisinin her bir sütunundaki elemanlar ilgili  değeri ile çarpılarak ağırlıklı normalize matrisi olarak ifade edilen  oluşturulur.  

![image](https://user-images.githubusercontent.com/83714984/174070434-0af99328-9e33-4bd5-9dc7-4f32f22cd7c6.png)

Adım 4: İdeal ve Negatif İdeal Çözümlerin Belirlenmesi
Ağırlıklı normalize edilmiş değerlere göre pozitif-ideal çözüm ( ) ve negatif-ideal çözüm ( belirlenir. İdeal çözüm setinin bulunması aşağıdaki formülde gösterilmiştir. Her iki formülde de J fayda (maksimizasyon)   ise kayıp (minimizasyon) değerini göstermektedir. Hem pozitif ideal hem de negatif ideal noktaların çözümleri belirtilen kriterlerin durumlarını hesaplamaktadır. 

![image](https://user-images.githubusercontent.com/83714984/174069910-1db50235-3e7a-495e-9da9-e8af876d0fe7.png)

Adım 5: Ayırım Ölçülerinin Hesaplanması 
Alternatifler arasındaki mesafe, n boyutlu Öklid Uzaklık Yaklaşımından faydalanılarak bulunmaktadır. Her alternatifin pozitif-ideal çözümden olan mesafesi ( ) ve negatif-ideal çözümden olan mesafesi (   ) şu şekilde hesaplanmaktadır:

![image](https://user-images.githubusercontent.com/83714984/174070090-a87371da-1f84-49d7-8e7b-0c9692280221.png)

Adım 6: İdeal Çözüme Göreli Yakınlığın Hesaplanması
Her bir alternatifin ideal çözüme göreli yakınlığı (  ) pozitif-ideal ve negatif-ideal ayırım ölçüsüne göre; negatif-ideal ayırım ölçüsünün toplam ayırım ölçüsü içindeki payı şeklinde aşağıdaki gibi hesaplanır:

![image](https://user-images.githubusercontent.com/83714984/174069783-e90f8bbc-a6a5-49b0-83de-804a3b605764.png)

