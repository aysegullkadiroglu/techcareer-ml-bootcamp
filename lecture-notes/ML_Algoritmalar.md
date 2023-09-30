Lineer Regresyon

Regresyon: Bağımsız girdi değişkenlerine bağlı olarak sürekli çıktı değişkenleri tahmin eder.
ör: Bir evin yaşı, ana yola uzaklığı, konumu, alanı, vb. parametrelere dayanarak evin fiyat tahmini.

Doğrusal Regresyon

Bir tahminde bulunmak için çok güçlü bir araçtır.
Doğru ve güvenilir tahminler elde etmek için bazı koşullar bulunur.
- Doğrusallık : Bağımlı değişkenler bağımsız değişkenleri doğrusal olarak takip ediyorsa buna doğrusallık denir.
- Bağımsızlık: Verilerin birbirinden bağımsız olması.
- Eş varyans: Bağımsız değişkenler tüm düzeylerde hataların varyansına sahiptir. Bağımsız değişken varyanslarının hataların üzerinde bir etkisi olmadığı anlamına gelir.
- Normallik: Modeldeki hatalar normal dağılım gösterir.
- Çoklu Bağlantı olmaması: Bağımsız değişkenler arasında yüksek korelasyon yoktur. Bağımsız değişkenler arasında korelasyonun ya çok az ya da hiç olmadığını gösterir.


Lojistik Regresyon

Belli bir amacın bir sınıfa ait olup olmadığını tahmin etmekte kullanılan sınıflandırma algoritması.
İstatistiksel bir algoritmadır.
ör: E posta Spam tespiti

Terminolojiler:

- Bağımlı Değişkenler: Bir lojistik regresyon modelinde tahmin etmeye çalıştığımız hedef değişken
- Bağımsız Değişkenler: Bağımlı değişkenin tahminlerine uygulanan girdi özellikleri
- Lojistik Fonksiyon: B'lı ve B'sız değişkenlerin birbiriyle ilişkisini tahmin etmek için kullanılan formül. (0-1) arasında değer döndürür.
- Olasılık: Var olan bir durumun olmayan duruma oranı.
- Katsayı: B'lı ve B'sız değişkenlerin birbiriyle olan ilişkisini gösterir.
- Maksimum Olasılık Tahmini: Veriler kullanarak gözlem olasılığını maksimuma çıkarabilecek bir yöntem.


Naive Bayes Algoritmaları

Tek bir algoritma değildir. Bir algoritma ailesinden oluşur.
Sınıflandırılan her özellik çiftinin birbirinden bağımsız olduğu temeline dayanır.
ör: Bir futbol maçının hava koşullarına bağlı olarak oynanıp oynanamayacığını Evet-Hayır seklinde sınıflandırılması. 


Görünüm   Sıcaklık   Nem      Rüzgar      Sonuç

Güneşli    Sıcak   Yüksek      Var        Evet
Bulutlu    Hafif   Normal      Yok        Hayır
Yağmurlu   Serin   Düşük

-Bağımsız
-Eşit 

İki ihtimali ortaya koyması beklenir:
- Her bir özellik diğerini etkilemediği varsayılır.
- Her bir özellik aynı önem seviyesinde değerlenirilir.

Bayes Teoremi

P(A|B) P(B) sıfıra(0) eşit değildir .

Temelde B olayı doğruysa A nın olasılığını bulmaya çalışırız. "B olayı delil adlandırılır."

----------------------------

SVM Algoritması

Bir SVM modeli örneklerin uzayda yerleştirilmiş noktaları ayırmak için bir doğru çizer. 
Bu doğrunun, iki sınıfının noktaları için de maksimum uzaklıkta olmasını amaçlar. 
Karmaşık ama küçük ve orta ölçekteki veri setleri için uygundur.


Karar Ağaçları Algoriması

Terminoloji: 
- Kök Düğüm: Tüm veri setini temsil eden düğümdür.
- Karar Düğüm: Girilen verinin özelliğine göre seçimi simgeleyen düğümdür.
- Yaprak Düğüm: Bir sınıf etiketini gösteren ve alt düğümü olmayan düğümdür.


Random Forest Algoritması

Çoklu karar ağaçlarının oluşturduğu hem regresyon hem sınıflandırma işlemlerinin yapılabildiği algoritma türüdür.
Her karar ağacı için örnek veri kümesi oluşturur. 
Random satır örneklemesi ve özellik örneklemesi yaparak karar verir. Bu örnekleme işlemine 'BOOTSTRAP' adı verilir.


