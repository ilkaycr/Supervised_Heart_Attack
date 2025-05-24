# Supervised_Heart_Attack
# Kalp Krizi Tahminleme Projesi

Bu proje, Global AI Hub Bootcamp kapsamında bireylerin kalp sağlığı ile ilgili verilerini kullanarak kalp krizi geçirme olasılıklarını tahmin eden bir makine öğrenimi modeli geliştirmek amacıyla oluşturulmuştur.

## Giriş

Projemde [Kaggle - Heart Attack Prediction in United States](https://www.kaggle.com/datasets/ankushpanday2/heart-attack-prediction-in-united-states/data) veri setini kullandım. Veri setinde , bireylerin yaş, kolesterol, kan basıncı gibi çeşitli medikal özelliklerini içermektedir. Bu özellikler kullanılarak bireyin kalp krizi riski taşıyıp taşımadığı tahmin etmeye çalıştım.

Proje boyunca denetimli öğrenme (supervised learning) yöntemlerinden Logistic Regression ve Decision Tree algoritmaları uyguladım.

## Teknik Detaylar

Kullanılan Kütüphaneler:

- `pandas`, `numpy`: Veri manipülasyonu ve analizleri için
- `matplotlib`, `seaborn`: Görselleştirme için
- `sklearn`: Makine öğrenimi modelleri ve metrikler için

Uygulanan Adımlar:

1. Veri Yükleme ve Ön İnceleme
2. Eksik ve Uç Değer Analizi
3. Görselleştirme ile EDA
4. Veri Ön İşleme
5. Modelleme ve Değerlendirme

## Metrikler ve Sonuçlar

Projemde model performansı şu metrikleri kullanarak değerlendirdim:

- Doğruluk (Accuracy)
- F1 Skoru
- Karışıklık Matrisi (Confusion Matrix)
- Classification Report

Yapılan testler sonucunda Logistic Regression ve Decision Tree modelleri uygulayıp  başarı oranlarını karşılaştırdım. Elde edilen sonuçlar, veri setinin boyutu ve dengesine bağlı olarak yorumladım.

## Sonuç ve Gelecek Çalışmalar

Bu proje kapsamında kalp krizi tahmini için temel bir makine öğrenimi modeli oluşturulmuş ve analiz edilmiştir. Gelecekte Daha fazla algoritma ile model karşılaştırmaları yapılabilir (Random Forest, XGBoost, vb.).

Linkler

[Kaggle](https://www.kaggle.com/code/lkayacar/kalp-krizi)

---
