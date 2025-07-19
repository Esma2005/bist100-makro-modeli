# BIST 100 Tahmini: Makroekonomik Göstergelerle Modelleme

Bu projede 2010–2023 dönemine ait yıllık Türkiye verileri kullanılarak BIST 100 endeksi tahmin edilmeye çalışılmıştır. Tahmin modeli olarak çoklu doğrusal regresyon uygulanmıştır.

## 📊 Kullanılan Değişkenler:
- TÜFE (%)
- Döviz kuru (USD/TRY)
- Faiz oranı (%)
- İşsizlik oranı (%)

## 📁 Veri Seti
Veriler yıllık olarak toplanmış ve aşağıdaki kaynaklardan derlenmiştir:
- TÜİK
- TCMB
- Investing

## 🧠 Modelleme Süreci
1. Veriler sıralandı ve 2010–2020 arası eğitim, 2021–2023 arası test seti olarak ayrıldı.
2. Çoklu doğrusal regresyon modeli eğitildi.
3. Eğitim ve test seti performansları karşılaştırıldı.

## 📈 Performans
- Eğitim R² Skoru: **0.8042**
- Test R² Skoru: **0.7515**
- Test MAE: **977.61**

> Not: Başlangıçta tüm veri ile model eğitildiğinde R² ≈ 0.91 çıkmıştı. Ancak zaman serisi mantığıyla veri bölünerek test edildiğinde performansın gerçekte daha düşük olduğu görüldü. Bu durum ezberleme (overfitting) riskine dikkat edilmesi gerektiğini göstermektedir.


## Görselleştirme

Gerçek ve tahmin edilen BIST 100 kapanış değerleri grafikle gösterilmiştir.

## Amaç

Makroekonomik göstergeler ile borsa endeksi arasındaki ilişkiyi anlamak ve tahminleme pratiği yapmaktır.

## 🧑‍💻 Katkıda Bulunan
**Esma Sultan Koyuncu**  
- Dokuz Eylül Üniversitesi, Ekonometri
- LinkedIn: [https://www.linkedin.com/in/esma-sultan-koyuncu-077975266/]
