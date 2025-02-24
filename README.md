Müşteri Segmentasyonu - KMeans Kümeleme

Proje Hakkında

Bu proje, müşteri verilerini analiz ederek KMeans kümeleme algoritmasıyla müşteri segmentlerini belirlemektedir. Veriler ön işlenmiş, ölçeklendirilmiş ve optimum küme sayısı Elbow Yöntemi ile belirlenmiştir. Sonrasında PCA ile boyut indirgeme yapılarak görselleştirme gerçekleştirilmiştir.

Kullanılan Teknolojiler

Python

Pandas, NumPy (Veri işleme)

Seaborn, Matplotlib (Veri görselleştirme)

Scikit-learn (Makine öğrenmesi ve kümeleme)

Proje Adımları

Tarih Kolonlarının Dönüştürülmesi: Tarih verileri datetime formatına çevrildi.

Müşteri Dağılımının Görselleştirilmesi: Bölgeler arasındaki müşteri dağılımı analiz edildi.

Veri Ön İşleme: Seçilen özellikler ölçeklendirildi.

Elbow Yöntemi: Optimum küme sayısı belirlendi.

KMeans Kümeleme: En uygun küme sayısı ile model eğitildi.

PCA ile Boyut İndirgeme: Kümeleme sonuçları 2D'ye indirgenerek görselleştirildi.

Bölgesel Küme Dağılımı: Kümeler ve bölgeler arasındaki ilişki analiz edildi.

Model Performans Değerlendirmesi: Silhouette skoru hesaplandı.
