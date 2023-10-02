DBSCAN Algoritması ( Yoğunluk Tabanlı Kümeleme )

Kümelemeler ve gürültü kavramına dayalı olarak çalışan algoritmadır.
En azından minimum sayıda nokta içermesi gerekir.
İyi ayrılmış kümelerde çalışırken uygun bir algoritmadır.

Gerekli parametreler:

- eps : iki nokta arasındaki mesafe. Bir veri noktasının etrafındaki komşuluğu tanımlar.
İki nokta arasındaki mesafe eps ye eşit ya da daha küçükse bunlar komşu olarak kabul edilir.
k-distance grafikleri eps hesaplamalarında kullanılır.

- MinPts : Eps yarıçapı içerisindeki minimum komşu sayısını ifade eder. Veri kümesi ne kadar büyük olursa,
MinPts o kadar büyük seçilmelidir. MinPts en az 3 seçilmelidir.

 Bu algoritmada 3 tip veri nooktası vardır:

 - Çekirdek nokta
 - Sıfır noktası
 - Gürültü veya aykırı değerler

Silhouette score ve Adjusted Rand Score

- Silhouette score : Silhouette score, k-mean gibi
kümeleme algoritmaları tarafından oluşturulan kümelerin
kalitesini değerlendirmek için kullanılan bir ölçüm.
Siluet puanı, kümelerin uyumunu ve ayrılığını değerlendirir.
Daha yüksek bir siluet puanı, kümelerin iyi bir şekilde ayrıldığını ve aynı küme içindeki veri noktalarının benzer olduğunu gösterir.

- Adjusted Rand Score : Düzeltilmiş Rand Endeksi, kümeleme sonuçları ile temel gerçeklik etiketleri ( ground truth labels ) arasındaki benzerliği ölçmek için kullanılan bir ölçümdür. 
Veriler için doğru etiketlere erişiminiz olduğunda kümeleme algoritmanızın performansını değerlendirebilirsiniz. Yaygın olarak kullanılır.