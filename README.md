# BIST 100 Tahmin Modeli

Bu projede, 2010–2023 yılları arasındaki Türkiye’ye ait makroekonomik göstergeler kullanılarak BIST 100 endeksinin kapanış değeri tahmin edilmiştir.

## Kullanılan Değişkenler

- **TÜFE (%)** – Enflasyon oranı  
- **KUR (USD/TRY)** – Dolar kuru  
- **FAİZ (%)** – Politika faizi  
- **İŞSİZLİK (%)** – İşsizlik oranı  
- **BIST_KAPANIŞ** – Yıllık BIST 100 kapanış değeri (hedef değişken)

## Kullanılan Yöntemler

- Çoklu doğrusal regresyon (Linear Regression)
- Korelasyon analizi
- Performans ölçütleri:  
  - R² Skoru: 0.91  
  - MAE: 463.61

## Kullanılan Kütüphaneler

- pandas  
- matplotlib  
- seaborn  
- scikit-learn

## Görselleştirme

Gerçek ve tahmin edilen BIST 100 kapanış değerleri grafikle gösterilmiştir.

## Amaç

Makroekonomik göstergeler ile borsa endeksi arasındaki ilişkiyi anlamak ve tahminleme pratiği yapmaktır.

## 🧑‍💻 Katkıda Bulunan
**Esma Sultan Koyuncu**  
- Dokuz Eylül Üniversitesi, Ekonometri
- LinkedIn: [https://www.linkedin.com/in/esma-sultan-koyuncu-077975266/]
