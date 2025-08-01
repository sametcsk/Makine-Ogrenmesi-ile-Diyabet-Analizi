README.md dosyasını markdown formatında, yani kod blokları kullanmadan, sadece metin olarak yazmamı istediğinizi anlıyorum. İşte projenizi açıklayan metin:

Diyabet Tahmin Projesi (Diabetes Prediction Project)
Proje Hakkında
Bu proje, Atıl Samancıoğlu'nun "Veri Bilimi ve Makine Öğrenmesi 2025: 100 Günlük Kamp" ödevi kapsamında geliştirilmiştir. Projenin amacı, Pima Indian Diabetes veri setini kullanarak makine öğrenmesi modelleri ile diyabet hastalığının tahmini için en uygun sınıflandırma modelini belirlemektir.

Proje, temel veri analizi adımlarından başlayarak model optimizasyonuna kadar olan süreci kapsamaktadır.

Kullanılan Veri Seti
Bu projede Pima Indian Diabetes veri seti kullanılmıştır. Veri seti, bir dizi tıbbi teşhis ölçümüne dayanarak bir hastanın 5 yıl içinde diyabet geliştirip geliştirmeyeceğini tahmin etmeye odaklanmaktadır.

Uygulanan Metodoloji
Proje, aşağıdaki adımları içermektedir:

Veri Temizliği ve Ön İşleme:

Veri setindeki mantıksız "0" değerleri (örneğin, Glikoz, Kan Basıncı) medyan ile doldurulmuştur.

StandardScaler kullanılarak veriler standartlaştırılmıştır.

Model Geliştirme:

Lojistik Regresyon (Logistic Regression)

Naive Bayes

Karar Ağacı (Decision Tree)

Destek Vektör Makineleri (SVC)

K-En Yakın Komşu (K-Neighbors Classifier)

Hiperparametre Ayarlama:

GridSearchCV ile her bir model için en uygun parametreler (hiperparametreler) bulunarak modellerin performansı optimize edilmiştir.

Model Değerlendirme:

Hiperparametre ayarı yapılmadan önceki (varsayılan) modellerin performansı ile ayarlandıktan sonraki modellerin performansı karşılaştırılmıştır.

Modellerin hem eğitim (train) hem de test (test) verisi üzerindeki doğruluk (accuracy) skorları, karmaşıklık matrisi (confusion matrix) ve sınıflandırma raporu (classification report) ile detaylı analiz yapılmıştır.

Proje Sonuçları
Yapılan kapsamlı analizler sonucunda, test verisinde en yüksek doğruluğu elde eden modelin Karar Ağacı (Decision Tree) olduğu tespit edilmiştir. Karar Ağacı, eğitim ve test doğruluk skorları arasındaki tutarlılığı ile iyi bir genelleme yeteneği sergilemiştir.

Kullanılan Teknolojiler
Python

Pandas

NumPy

Scikit-learn

Matplotlib & Seaborn
