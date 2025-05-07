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
