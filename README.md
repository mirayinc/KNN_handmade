# KNN_handmade
KNN algoritması, python ile kütüphane kullanmadan yazılmıştır. 

## KNN Nedir?
K-En Yakın Komşu (KNN) algoritması, sınıflandırma veya regresyon problemleri için kullanılan basit ve sezgisel bir yöntemdir. 
Bu algoritmada, yeni bir veri örneğinin sınıfı, eğitim veri setindeki en yakın K komşusuna bakılarak belirlenir. Mesafe ölçütü (genellikle Öklid mesafesi) kullanılarak veriler arasındaki benzerlik değerlendirilir. Ben de yazdığım kodlarda öklid mesafesini baz aldım.
Kodlar optimize edilebilir.

Çoğu makine öğrenmesi algoritmasında “Eğitim (Training)” ve “Tahmin (Prediction)” olmak üzere iki farklı süreç bulunur.
Ancak, K-NN sınıflandırıcı, parametrik olmayan, örnek tabanlı ve tembel bir öğrenme algoritmasıdır.

Tembel algoritma, eğitim verilerinden bir ayrıştırıcı fonksiyon (discriminative function) öğrenmek yerine eğitim veri setini ezberlediği anlamına gelir. Modelin öğrenmesine veya eğitilmesine gerek yoktur ve tüm veri noktaları tahmin (prediction) sırasında kullanılır.

K değeri, komşu sayısını belirleyerek modelin genelleme yeteneğini etkiler.
Komşu sayısı, karar verme faktörüdür bu nedenle genellikle 𝐾, beraberliği önlemek için tek bir sayı olarak seçilir.
Hesaplama basit olsa da, KNN algoritması büyük veri setlerinde yavaş çalışabilir ve özellik ölçeklendirmesi gibi ön işlemleri gerektirebilir.
