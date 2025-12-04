# Iris-Dataset-Naive-Bayes-Logistic-Regression-and-SVC
Iris Dataset – Naive Bayes, Logistic Regression ve SVC Karşılaştırması

Bu projede klasik Iris veri seti kullanılarak üç farklı makine öğrenimi sınıflandırma algoritması uygulanmış ve performansları karşılaştırılmıştır:

Gaussian Naive Bayes

Logistic Regression

Support Vector Classifier (SVC)

Projenin amacı; veri ön işleme adımlarını uygulamak, modelleri eğitmek ve sınıflandırma sonuçlarını karşılaştırarak analiz etmektir.

📂 Proje İçeriği

Proje aşağıdaki adımlardan oluşmaktadır:

✔ 1. Veri Keşfi (EDA)

Veri setinin yapısının incelenmesi (head(), info(), describe())

Pairplot, scatterplot ile görselleştirme

Korelasyon kontrolü

Gereksiz kolonun (Id) kaldırılması

✔ 2. Veri Ön İşleme

Label Encoding ile sınıf etiketlerinin dönüştürülmesi

Train-Test Split (%25 test)

StandardScaler ile ölçeklendirme

✔ 3. Modellerin Eğitilmesi

Aşağıdaki algoritmalar aynı eğitim/test verileri üzerinde eğitilmiştir:

GaussianNB

LogisticRegression

SVC

✔ 4. Performans Değerlendirme

Her model için:

Precision

Recall

F1-score

Confusion Matrix

Accuracy

hesaplanmıştır.

📊 Sonuçlar

Iris veri seti oldukça iyi ayrışan bir veri olduğu için, üç model de test verisi üzerinde %100 doğruluk (accuracy) elde etmiştir.

Model	Accuracy	Açıklama
Gaussian Naive Bayes	1.00	Iris veri setinde başarılı, hızlı bir model
Logistic Regression	1.00	Lineer ilişkiyi iyi modellediği için mükemmel sonuç
SVC	1.00	Kernel destekli, güçlü bir sınıflandırıcı

Iris veri setinin özelliklerinden dolayı bazı sınıflar neredeyse tamamen lineer ayrılabilir; bu nedenle bu üç modelin de yüksek başarı elde etmesi beklenen bir sonuçtur.
