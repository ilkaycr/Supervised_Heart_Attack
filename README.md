# Supervised_Heart_Attack

# Kalp Krizi Tahminleme Projesi

Bu proje, Global AI Hub Bootcamp kapsamında bireylerin kalp sağlığı ile ilgili verilerini kullanarak kalp krizi geçirme olasılıklarını tahmin eden bir makine öğrenimi modeli geliştirmek amacıyla oluşturulmuştur.

## Giriş

Projemizde [Kaggle - Heart Attack Prediction in United States](https://www.kaggle.com/datasets/ankushpanday2/heart-attack-prediction-in-united-states/data) veri seti kullanılmıştır. Veri seti, bireylerin yaş, kolesterol, kan basıncı, göğüs ağrısı tipi gibi çeşitli medikal özelliklerini içermektedir. Bu özellikler kullanılarak bireyin kalp krizi riski taşıyıp taşımadığı tahmin edilmeye çalışılmıştır.

Proje boyunca denetimli öğrenme (supervised learning) yöntemlerinden Logistic Regression ve Decision Tree algoritmaları uygulanmıştır.

## Teknik Detaylar

Projenin teknik süreci `kalp-krizi.ipynb` adlı Jupyter Notebook dosyasında yer almaktadır. Markdown hücreler aracılığıyla veri analizi, veri ön işleme ve model oluşturma adımları detaylı bir şekilde açıklanmıştır.

### Kullanılan Kütüphaneler:

- `pandas`, `numpy`: Veri manipülasyonu ve analizleri için
- `matplotlib`, `seaborn`: Görselleştirme için
- `sklearn`: Makine öğrenimi modelleri ve metrikler için

### Uygulanan Adımlar:

1. **Veri Yükleme ve Ön İnceleme**
2. **Eksik ve Uç Değer Analizi**
3. **Görselleştirme ile EDA**
4. **Veri Ön İşleme**
5. **Modelleme ve Değerlendirme**

## Metrikler ve Sonuçlar

Projede model performansı şu metrikler kullanılarak değerlendirilmiştir:

- **Doğruluk (Accuracy)**
- **F1 Skoru**
- **Karışıklık Matrisi (Confusion Matrix)**
- **Classification Report**

Yapılan testler sonucunda Logistic Regression ve Decision Tree modelleri uygulanmış, başarı oranları karşılaştırılmıştır. Elde edilen sonuçlar, veri setinin boyutu ve dengesine bağlı olarak yorumlanmıştır.

## Ekler

Eğer proje kapsamında arayüz (ör. Streamlit) geliştirirseniz, UI klasörü altında yer almalıdır. Bu projede henüz bir deploy işlemi yapılmamıştır, ancak ileride geliştirilmeye uygundur.

## Sonuç ve Gelecek Çalışmalar

Bu proje kapsamında kalp krizi tahmini için temel bir makine öğrenimi modeli oluşturulmuş ve analiz edilmiştir. Gelecekte:

- Daha fazla algoritma ile model karşılaştırmaları yapılabilir (Random Forest, XGBoost, vb.).

Linkler

[Kaggle](https://www.kaggle.com/code/lkayacar/kalp-krizi)

---
