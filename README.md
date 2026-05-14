# Öğrenci Performans Analizi ve Tahminleme

Bu proje, öğrencilerin akademik performanslarını etkileyen çeşitli faktörleri analiz etmek ve bu faktörlere dayalı olarak bir performans indeksi tahmin modeli oluşturmak amacıyla geliştirilmiştir. Veri bilimi teknikleri kullanılarak hazırlanan bu çalışma, Python programlama dili ve popüler veri analizi kütüphanelerini içermektedir.

## 🚀 Proje Amacı
Öğrencilerin günlük çalışma saatleri, uyku düzenleri, ders dışı etkinlikleri ve önceki sınav puanları gibi değişkenlerin akademik başarı (Performance Index) üzerindeki etkisini incelemek ve makine öğrenmesi algoritmalarıyla yüksek doğrulukta tahminler yapmaktır.

## 📊 Veri Seti Hakkında
Projede kullanılan veri seti 10.000 öğrenci kaydını içermekte olup aşağıdaki sütunlardan oluşmaktadır:

- **Hours Studied:** Günlük ortalama çalışma saati.
- **Previous Scores:** Önceki sınavlardan alınan puanlar.
- **Extracurricular Activities:** Ders dışı etkinliklere katılım durumu (Evet/Hayır).
- **Sleep Hours:** Günlük ortalama uyku süresi.
- **Sample Question Papers Practiced:** Çözülen örnek soru sayısı.
- **Performance Index:** Hedef değişken (0-100 arası başarı puanı).

## 🛠 Kullanılan Teknolojiler
- **Python 3.x**
- **Pandas:** Veri manipülasyonu ve analizi.
- **NumPy:** Sayısal hesaplamalar.
- **Matplotlib & Seaborn:** Veri görselleştirme (Histogram, Boxplot, Isı Haritası vb.).
- **Scipy:** İstatistiksel testler (T-testi).
- **Scikit-learn:** Makine öğrenmesi (Lineer Regresyon, Veri bölme, Metrik hesaplama).

## 📈 Öne Çıkan Analizler ve Sonuçlar
- **Korelasyon Analizi:** Çalışma saatleri ve önceki puanların performans indeksi ile çok güçlü bir pozitif ilişkiye sahip olduğu gözlemlenmiştir.
- **İstatistiksel Testler:** Ders dışı etkinliklere katılan ve katılmayan öğrenciler arasında akademik başarı açısından anlamlı bir fark olup olmadığı T-testi ile incelenmiştir.
- **Makine Öğrenmesi Modeli:** Lineer Regresyon modeli eğitilmiş ve aşağıdaki başarı metrikleri elde edilmiştir:
  - **R2 Skoru:** ~0.989 (Modelin açıklanabilirlik oranı oldukça yüksektir).
  - **MSE (Mean Squared Error):** ~4.08.

## 📂 Proje Yapısı
- `StudentPerformance.csv`: Ham veri seti.
- `ogrperf (1).ipynb`: Veri analizi, görselleştirme ve modelleme adımlarını içeren ana çalışma dosyası.
- `main.py`: Projenin giriş ve kütüphane yapılandırma dosyası.
- `LICENSE`: Proje lisans bilgileri.

## ✍️ Hazırlayan
**Salih Karakuş**  

