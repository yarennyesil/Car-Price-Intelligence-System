Car Price Intelligence System (TensorFlow)
Bu proje, Python ve TensorFlow kullanarak ikinci el araç piyasasındaki fiyatları tahmin etmek amacıyla geliştirilmiştir. Veri biliminin temel aşamalarını (EDA, Temizlik, Modelleme) içeren uçtan uca bir çalışmadır.

Kullanılan Teknolojiler
Python (Pandas, NumPy)
Veri Görselleştirme: Matplotlib & Seaborn
Derin Öğrenme: TensorFlow & Keras
Ölçeklendirme: Scikit-learn (MinMaxScaler)

Proje Aşamaları
1. Veriyi Anlamak (EDA)
Veri setinin genel yapısı, eksik veriler ve istatistiksel özetler (head, info, describe) incelenerek verinin "sağlık durumu" kontrol edilmiştir.

2. Grafiksel Analizler
Araçların kilometresi, model yılı ve fiyatı arasındaki ilişkiler görselleştirilmiştir. Bu aşamada verideki uç değerler (outliers) tespit edilmiştir.

Not: Analiz grafiklerine images/ klasöründen ulaşabilirsiniz.

3. Veri Temizliği ve Hazırlık
Modelin genel başarısını düşüren en yüksek fiyatlı %1'lik kesim (outliers) ayıklanmıştır.

Veriler model eğitimine uygun hale getirmek için MinMaxScaler ile 0-1 arasına ölçeklendirilmiştir.

4. Model Oluşturma ve Eğitim
Yapay Sinir Ağı (ANN): TensorFlow kullanılarak 4 gizli katmandan oluşan bir regresyon modeli kurulmuştur.

Aktivasyon Fonksiyonu: 'ReLU'

Optimizer: 'Adam'

###  Proje Görselleri
![Araç Fiyat Analizi](images/car_analysis.png)

