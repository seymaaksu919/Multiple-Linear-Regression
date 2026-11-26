# Çoklu Doğrusal Regresyon – Öğrenci Sınav Notu Tahmini

## Proje Hakkında

Bu projede, öğrencilerin günlük alışkanlıkları ve çalışma düzenleri kullanılarak sınav notları tahmin edilmektedir.

Çoklu Doğrusal Regresyon (Multiple Linear Regression) algoritması kullanılarak çalışma süresi, uyku süresi, derse devam oranı ve sosyal medya kullanımının sınav notlarıyla ilişkisi incelenmiştir.

## Veri Seti

Veri seti 50 öğrenciye ait kayıt ve 5 değişkenden oluşmaktadır.

**Bağımsız Değişkenler (X):**
- Çalışma Saati (Study Hours)
- Uyku Saati (Sleep Hours)
- Derse Devam Oranı (Attendance Rate)
- Sosyal Medya Kullanım Süresi (Social Media Hours)

**Bağımlı Değişken (Y):**
- Sınav Notu (Exam Score)

## Kullanılan Teknolojiler ve Kütüphaneler

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Proje Aşamaları

1. Veri setinin yüklenmesi ve incelenmesi
2. Keşifsel Veri Analizi (EDA)
3. Veri görselleştirme
4. Korelasyon analizi
5. Eğitim ve test verilerinin ayrılması
6. StandardScaler ile özellik ölçeklendirme
7. Çoklu Doğrusal Regresyon modelinin eğitilmesi
8. Tahmin işlemleri
9. Model performansının değerlendirilmesi
10. Artık (Residual) analizi
11. Yeni öğrenci verileriyle sınav notu tahmini

## Model Değerlendirme Metrikleri

Model performansını değerlendirmek için aşağıdaki metrikler kullanılmıştır:

- **MAE:** Ortalama Mutlak Hata
- **MSE:** Ortalama Kare Hata
- **RMSE:** Ortalama Kare Hatanın Karekökü
- **R²:** Belirlilik Katsayısı
- **Adjusted R²:** Düzeltilmiş Belirlilik Katsayısı

## Tahmin Örneği

Eğitilen model ile yeni bir öğrencinin sınav notu tahmin edilebilmektedir.

Örnek öğrenci bilgileri:

- 5 saat çalışma
- 7 saat uyku
- %90 derse devam oranı
- 2 saat sosyal medya kullanımı

Bu bilgiler modele verilerek tahmini sınav notu elde edilmiştir.

## Projenin Amacı

Çoklu Doğrusal Regresyon algoritmasının uygulanmasını öğrenmek, bağımsız değişkenler ile sınav notu arasındaki ilişkileri incelemek ve makine öğrenmesi kullanarak sayısal tahmin gerçekleştirmektir.

## Nasıl Çalıştırılır?

1. Projeyi bilgisayarınıza indirin.
2. Gerekli kütüphaneleri yükleyin:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
3. Jupyter Notebook'u açın.
4. Notebook içerisindeki hücreleri sırasıyla çalıştırın.


Not: Bu çalışma, Udemy'de Atıl Samancıoğlu'nun eğitim içeriği takip edilerek öğrenme ve uygulama amacıyla gerçekleştirilmiştir.


