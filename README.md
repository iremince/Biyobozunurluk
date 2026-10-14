# Kimyasal Molekül Biyobozunurluk Tahmin Modeli (Biodegradability Classification)

Bu proje, kimyasal moleküllerin atomik özellikleri ve katsayıları kullanılarak doğada biyobozunurluk durumlarının (güvenli/riskli) makine öğrenmesi ile sınıflandırılmasını sağlayan uçtan uca bir veri bilimi çalışmasıdır.

## Proje Özeti
* **Model Başarısı:** %86.0 Doğruluk (Accuracy)
* **Kullanılan Algoritma:** Random Forest Classifier[cite: 1, 2, 3]
* **Özellik Uzayı:** Kimyasal moleküllere ait 41 atomik özellik ve katsayı[cite: 1, 2, 3]

## Kullanılan Teknolojiler ve Kütüphaneler
* **Python**
* **Scikit-Learn** (Model eğitimi ve değerlendirmesi)
* **Pandas & NumPy** (Veri manipülasyonu ve ön işleme)
* **Matplotlib & Seaborn** (Veri görselleştirme ve performans analizleri)

## Proje Yapısı
```text
├── data/                  # Ham ve işlenmiş veri setleri
├── notebooks/             # Keşifsel veri analizi (EDA) ve model denemeleri
├── src/                   # Python kaynak kodları (eğitim ve tahmin)
├── README.md              # Proje dokümantasyonu
└── requirements.txt       # Proje bağımlılıkları
