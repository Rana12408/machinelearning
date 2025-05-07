# trendyol_projesi 
# 🛍️ Trendyol Ürün Verisi Analizi

Bu proje, Trendyol üzerinde yer alan ürünlerin web scraping yöntemiyle elde edilen verileri üzerinden analiz yapılmasını amaçlamaktadır. Amaç, belirli bir fiyat aralığında kalan markaların tespit edilmesi ve bu ürünlerin temel özelliklerinin analiz edilmesidir.

## 📦 Veri İçeriği

Toplanan veri aşağıdaki alanları içermektedir:

- **Marka**: Ürünün ait olduğu marka
- **Açıklama**: Ürün başlığı/açıklaması
- **Fiyat**: Ürünün satış fiyatı (₺)
- **Favori Sayısı**: Ürünün kaç kişi tarafından favorilendiği

## 🎯 Proje Amacı

Belirlenen fiyat aralığına göre ürünler filtrelenmiş ve bu aralıkta yer alan **markalar listelenmiştir**. Bu sayede hem tüketici eğilimleri hem de uygun fiyatlı popüler markalar hakkında öngörü elde edilmiştir.

## 🔧 Kullanılan Teknolojiler

- Python 3.x
- `requests` / `selenium` (veri çekimi için)
- `pandas`
- `beautifulsoup4` (HTML parsing için)
- `matplotlib` veya `seaborn` (görselleştirme için)

## ⚙️ Çalışma Adımları

1. Trendyol web sayfasından ürün verilerinin çekilmesi
2. Marka, açıklama, fiyat ve favori sayısı bilgilerinin ayrıştırılması
3. Kullanıcının belirlediği fiyat aralığına göre ürünlerin filtrelenmesi
4. Bu aralıkta kalan markaların listelenmesi:
   **************************************************************************************************************************************************************************************************************
   # 🚢 Titanic - Hayatta Kalma Tahmini (Survival Prediction)

Bu proje, Titanic gemisindeki yolcuların verilerini kullanarak bir yolcunun hayatta kalıp kalamayacağını tahmin etmeyi amaçlayan bir makine öğrenmesi uygulamasıdır. Bu klasik sınıflandırma problemi, veri ön işleme, keşifsel veri analizi (EDA), modelleme ve performans değerlendirmesi adımlarını içermektedir.

## 📊 Veri Seti

Titanic veri seti aşağıdaki temel bilgileri içermektedir:

- `PassengerId`: Yolcu numarası
- `Pclass`: Yolcunun bilet sınıfı (1, 2, 3)
- `Name`, `Sex`, `Age`: Demografik bilgiler
- `SibSp`, `Parch`: Aile üyeleriyle birlikte seyahat durumu
- `Fare`: Ödenen ücret
- `Embarked`: Biniş limanı
- `Survived`: **(Hedef değişken)** 0 = Hayır, 1 = Evet

## 🎯 Proje Amacı

Makine öğrenmesi algoritmaları kullanarak yolcunun hayatta kalma durumunu (`Survived`) tahmin etmeye çalışmak.

## 🔍 Proje Adımları

1. **Veri Ön İşleme**
   - Eksik verilerin doldurulması
   - Kategorik verilerin sayısallaştırılması (Encoding)
   - Özellik mühendisliği

2. **Keşifsel Veri Analizi (EDA)**
   - Hayatta kalma oranlarının cinsiyet, yaş ve sınıfa göre dağılımları
   - Korelasyon analizi

3. **Modelleme**
   - `Logistic Regression`
   - `Random Forest`
   - `XGBoost` gibi sınıflandırma algoritmaları kullanıldı

4. **Değerlendirme**
   - Accuracy, Precision, Recall, F1-Score gibi metriklerle performans ölçümü
   - Confusion matrix ve ROC eğrileri ile analiz

## 🛠️ Kullanılan Kütüphaneler

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `xgboost` (isteğe bağlı)

