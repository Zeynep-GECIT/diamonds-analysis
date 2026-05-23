## 💎 Diamonds Fiyat Analizi
Bu proje, 50.000'den fazla elmas kaydı içeren Diamonds veri seti üzerinde kapsamlı bir veri analizi ve makine öğrenmesi çalışması sunmaktadır.
# 📊 Veri Seti
-Kaynak: ggplot2 Diamonds Dataset

-Boyut: ~53.000 satır, 10 sütun

-Hedef değişken: Elmas fiyatı (price)
# 🔍 Yapılanlar
# Keşifsel Veri Analizi (EDA)

-Eksik ve hatalı veri tespiti ve temizlenmesi

-Kategorik değişkenlerin (cut, color, clarity) fiyata etkisinin incelenmesi

-Carat'ın maskeleme etkisinin keşfedilmesi ve görselleştirilmesi

-Korelasyon analizi

# Veri Ön İşleme

-Sıfır boyutlu hatalı kayıtların silinmesi

-Duplicate verilerin temizlenmesi

-Kategorik değişkenlerin ordinal encoding ile sayısallaştırılması

-Hedef değişkene log dönüşümü uygulanması

-Multicollinearity nedeniyle x, y, z sütunlarının çıkarılması

# Makine Öğrenmesi Modelleri
| Model | R² | RMSE |
|---|---|---|
| Linear Regression | 0.87 | 0.35 |
| Deep Learning | 0.96 | 0.17 |
| Random Forest | 0.98 | 0.11 |
| XGBoost | 0.99 | 0.09 |
# 🛠️ Kullanılan Teknolojiler
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, TensorFlow
