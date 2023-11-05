Gözetimli Öğrenme

1 Sınıflandırma
2 Regresyon( Tahmin )

Etiketli veriler ile çalışan öğrenme türüne denir.


Sınıflandırmada amaç bir karar sınıfı bulmaktır.
Regresyonda sonuçta önümüze iki farklı regresyon modeli çıkar.

Sınıflandırmada çıktılar kategoriktir.
Regresyonda çıktılar sayısal değerlerdir.

Kümelemeden farklı olarak sınıflandırmada sınıfların ne olduğu
önceden bellidir.

Çalıştığı parametreler ve değerlendirme metrikleri farklıdır.
Sınıflandırmada doğruluk, hassasiyet verileri algoritmayı test eder;
Regresyonda mutlak hatalar, ortalama kare hatası, Gradyan Mesafesi bulunur.



=== Linear Regression ===

Algoritmanın amacı bağımsız değişkenlere dayalı olarak bağımlı değişkenin değerini tahmin edebilecek en iyi doğrusal denklemi bulmaktır.

Güvenilir ve doğru bir çözüm elde etmek için bazı şartları sağlamak gerekir:

- Doğrusallık
- Bağımsızlık
- Normallik = hataların normal dağılıma sahip olması
- Çoklu bağlantı olmaması = Bağımsız değişkenler arasında yüksek korelasyon olmamalı.


MSE





=== Logistic Regression ===

Bu algoritmanın amacı bir veri kümesinin belirli bir gruba ait olma ihtimalini tahmin etmek.

Belirli bir bağımsız değişken kümesini kullanarak kategorik bağımlı değişkeni tahmin etmekte kullanılır.


Sonuçlar kategorik veya ayrık veriler olmalı.

S = 1 / 1+ e^-x

Gerçek sayı verilerini input alarak [0-1]  aralığında çıktılar elde etmeyi amaçlar.

Regresyon problemleri için Doğrusal Regresyon kullanılırken ; sınıflandırma problemlerini çözmek için Lojistik regresyon kullanılır.

Türleri : 

- Binom : iki olasılığa sahip olma durumu( 0 ve 1)
- Çok Terimli : Kedi, köpek, insan
- Sıralı LR = Düşük, orta, yüksek

(Toplam WiXi ) + b


