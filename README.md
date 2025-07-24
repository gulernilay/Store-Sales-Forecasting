# Store Sales Forecasting & Optimization

Bu proje, mağaza satışlarını analiz etmek ve tahmin etmek için kapsamlı bir veri bilimi ve makine öğrenimi süreci sunar. Proje, veri temizleme, keşifsel veri analizi, istatistiksel testler ve çeşitli regresyon modelleri ile satış tahmini yapmayı amaçlamaktadır.

## İçindekiler

- [Proje Hakkında](#proje-hakkında)
- [Kullanılan Veri Seti](#kullanılan-veri-seti)
- [Kurulum](#kurulum)
- [Kullanılan Kütüphaneler](#kullanılan-kütüphaneler)
- [Notebook Akışı](#notebook-akışı)
  - Veri Temizleme ve Ön İşleme
  - Keşifsel Veri Analizi (EDA)
  - Korelasyon ve Aykırı Değer Analizi
  - Kategorik Analizler
  - İstatistiksel Testler
  - Modelleme
  - Özellik Önemlilikleri
- [Sonuçlar](#sonuçlar)
- [Katkı Sağlamak](#katkı-sağlamak)
- [Lisans](#lisans)

---

## Proje Hakkında

Bu projede, mağaza satış verileri üzerinde veri analizi ve tahminleme çalışmaları yapılmıştır. Farklı regresyon modelleri ile satış tahmini gerçekleştirilmiş, en iyi performans gösteren modeller ve satışları etkileyen en önemli özellikler belirlenmiştir.

## Kullanılan Veri Seti

- **stores_sales_forecasting.csv**  
  Mağaza satışlarına ait sipariş, müşteri, ürün, bölge, tarih ve finansal bilgiler içeren veri seti.

## Kurulum

1. Gerekli kütüphaneleri yükleyin:
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```
2. Proje dosyalarını aynı klasöre yerleştirin:
   - `sales-forecasting-optimization-final.ipynb`
   - `stores_sales_forecasting.csv`
3. Notebook'u Jupyter veya VS Code ile açın ve hücreleri sırasıyla çalıştırın.

## Kullanılan Kütüphaneler

- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- xgboost

## Notebook Akışı

### 1. Veri Temizleme ve Ön İşleme

- Eksik ve tekrarlı verilerin analizi ve temizlenmesi
- Sabit ve gereksiz sütunların kaldırılması
- Kategorik değişkenlerin dummy değişkenlere dönüştürülmesi

### 2. Keşifsel Veri Analizi (EDA)

- Sayısal değişkenlerin dağılımı ve kutu grafikleri
- Kategorik değişkenlerin bar ve pasta grafikleri
- En çok satan ürünler ve alt kategoriler

### 3. Korelasyon ve Aykırı Değer Analizi

- Korelasyon matrisi ve ısı haritası
- Aykırı değerlerin IQR ve Winsorize ile analizi ve düzeltilmesi

### 4. Kategorik Analizler

- Bölge, segment, şehir, eyalet ve gönderim türüne göre satışların incelenmesi

### 5. İstatistiksel Testler

- ANOVA ve t-testi ile farklı gruplar arasında satış farklarının istatistiksel olarak incelenmesi

### 6. Modelleme

- **Linear Regression**
- **Random Forest Regressor**
- **Decision Tree Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**
- **Ridge Regression**
- **Voting Regressor (Ensemble)**
- Model performanslarının karşılaştırılması (R², MAE, MSE, RMSE)
- Model karmaşıklığı ve hata analizi

### 7. Özellik Önemlilikleri

- Gradient Boosting, Random Forest ve XGBoost modelleri için en önemli 10 özelliğin görselleştirilmesi

## Sonuçlar

- Farklı regresyon modellerinin performansları karşılaştırıldı.
- Satışları etkileyen en önemli değişkenler belirlendi.
- Segment, bölge, şehir ve eyalet bazında satış farklılıkları istatistiksel olarak analiz edildi.
- Model karmaşıklığı ve hata analizi ile en uygun model seçimi yapıldı.

## Katkı Sağlamak

Katkı sağlamak için lütfen bir pull request gönderin veya issue açın.

## Lisans

Bu proje eğitim ve araştırma amaçlıdır.

---

**Not:** Veri dosyasının yolunu kendi bilgisayarınıza göre güncellemeniz gerekebilir.
