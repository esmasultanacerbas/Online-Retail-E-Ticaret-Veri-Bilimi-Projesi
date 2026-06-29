# Online-Retail-E-Ticaret-Veri-Bilimi-Projesi


Bu proje, uluslararası bir e-ticaret şirketinin işlem verilerini kullanarak müşteri davranışlarını analiz etmeyi ve veriye dayalı iş stratejileri geliştirmeyi amaçlayan bir veri bilimi çalışmasıdır. Proje kapsamında veri temizleme, özellik mühendisliği (feature engineering), keşifsel veri analizi (EDA), müşteri segmentasyonu (K-Means) ve sepet analizi (Market Basket Analysis) uygulanmıştır.

Esma Sultan Acerbaş

1306240105


## Araştırma Soruları

Proje aşağıdaki üç temel soruya odaklanarak iş kararlarını destekleyecek içgörüler üretmeyi hedeflemektedir:

S1 - Ülke ve Zaman Bazlı Satış Örüntüleri: Toplam gelir ülke bazında nasıl dağılıyor? Aylık satış trendlerinde bir mevsimsellik var mı?

S2 - Müşteri Segmentasyonu: Müşteriler RFM (Recency, Frequency, Monetary) boyutlarına göre nasıl dağılıyor ve K-Means algoritması ile anlamlı segmentlere ayrılabilir mi?

S3 - Birlikte Satın Alma Analizi: Aynı fatura içinde hangi ürünler en sık birlikte satın alınıyor? (Çapraz satış fırsatları)

## Veri Seti Bilgileri

### Veri Seti Adı: 
Online Retail Dataset

### Kaynak: 
UCI Machine Learning Repository (Kaggle üzerinden temin edilmiştir)

### Bağlantı: 
[Kaggle - Online Retail](https://www.kaggle.com/datasets/vijayuv/onlineretail)

### İçerik: 
Aralık 2010 ile Aralık 2011 arasında gerçekleşen yaklaşık 541.000 işlem kaydı.

### Kullanılan Teknolojiler ve Kütüphaneler

Proje Python programlama dili ile Jupyter Lab ortamında geliştirilmiştir. Gerekli kütüphaneler aşağıda listelenmiştir:

-pandas - Veri manipülasyonu ve analizi

-numpy - Matematiksel işlemler

-matplotlib & seaborn - Veri görselleştirme

-scikit-learn - Makine öğrenmesi (K-Means kümeleme ve veri ölçeklendirme)

-itertools - Kombinasyon hesaplamaları (Sepet analizi)

## Projeyi Çalıştırma Talimatları

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:

### Repository'yi Klonlayın:

git clone [https://github.com/]https://github.com/esmasultanacerbas/Online-Retail-E-Ticaret-Veri-Bilimi-Projesi-.git

cd [Online-Retail-E-Ticaret-Veri-Bilimi-Projesi]



### Gerekli Kütüphaneleri Kurun:
Terminal veya komut satırında aşağıdaki komutu çalıştırarak gerekli paketleri yükleyin:

pip install pandas numpy matplotlib seaborn scikit-learn



###  Veri Setini İndirin:

Kaggle'daki Online Retail sayfasından Online Retail.csv (veya OnlineRetail.csv) dosyasını indirin.

İndirdiğiniz CSV dosyasını, klonladığınız proje klasörünün ana dizinine (.ipynb dosyası ile aynı yere) yerleştirin.

### Jupyter Notebook'u Başlatın:
Proje dizininde Jupyter Lab veya Notebook'u çalıştırın:

jupyter lab
veya 
jupyter notebook



### Kodu Çalıştırın: 
Açılan tarayıcı penceresinde online_retail_project.ipynb dosyasını açın ve hücreleri sırasıyla çalıştırarak analizleri inceleyin.

## Proje Çıktıları ve Temel Bulgular

Satışların büyük çoğunluğu Birleşik Krallık (UK) kaynaklıdır. Yılın son çeyreğinde (özellikle Kasım) belirgin bir satış artışı (mevsimsellik) gözlemlenmiştir.

K-Means kümeleme algoritması ile müşteriler başarıyla 4 segmente (High-Value, Loyal, At-Risk, Dormant) ayrılmıştır.

En çok birlikte satılan ürün çiftleri belirlenerek "Bunu alanlar bunu da aldı" modülleri için temel kurallar oluşturulmuştur.

## Lisans

Bu proje, eğitim amaçlı oluşturulmuş olup MIT Lisansı altındadır. Veri seti UCI Machine Learning Repository'ye aittir ve açık kaynak olarak paylaşılmıştır.
