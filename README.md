# ❤️ Kalp Hastalığı Tahmini (Logistic Regression)

Bu proje, bireylerin kalp hastalığına sahip olup olmadığını tahmin etmek için makine öğrenmesi tekniklerinden **Lojistik Regresyon** kullanılarak geliştirilmiştir.

## 📊 Kullanılan Adımlar

1. Veri yükleme ve ön analiz
2. Keşifsel Veri Analizi (EDA)
3. Kategorik verilerin dönüşümü (OneHotEncoding)
4. Özellik ve hedef ayrımı (X, y)
5. Eğitim-test ayırımı (%80-%20)
6. Standardizasyon (StandardScaler)
7. Lojistik Regresyon modeli eğitimi
8. Başarı metrikleri ve confusion matrix
9. Özellik önemi analizi
10. Sonuçların değerlendirilmesi

## ✅ Model Performansı

- **Accuracy:** 0.83  
- **Precision:** 0.86  
- **Recall:** 0.81  
- **F1-Score:** 0.83  

## 📁 Proje Dosya Yapısı
heart-disease-logreg/
├── data/ # Veri dosyası (heart.csv)
├── notebooks/ # .ipynb dosyaları (EDA + Model)
├── results/ # confusion matrix, feature importance, metrikler
├── models/ # Eğitilmiş modeller (isteğe bağlı)
├── README.md # Proje özeti ve açıklamalar
└── requirements.txt # Kullanılan Python kütüphaneleri

