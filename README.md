[README.md](https://github.com/user-attachments/files/20527508/README.md)
# Sosyal Mühendislik İçerikli Mesajların Tespiti

Bu proje, sosyal mühendislik saldırılarına yönelik mesajları tespit etmek amacıyla makine öğrenmesi ve metin madenciliği yöntemleri kullanılarak geliştirilmiştir.

## 📌 Proje Özeti

E-posta mesajları gibi metin verileri üzerinde;
- Temizleme (ön işleme),
- TF-IDF vektörleştirme,
- Anahtar kelimeye dayalı etiketleme,
- Makine öğrenmesi ile sınıflandırma (Logistic Regression),
- K-Means ile kümeleme  
gibi işlemler uygulanarak sosyal mühendislik içeren mesajlar tespit edilmiştir.

## 🔧 Kullanılan Teknolojiler

- Python 3.x
- Pandas
- Scikit-learn
- Regex
- TF-IDF
- KMeans Clustering
- Logistic Regression

## 📁 Dosya Yapısı

```

├── social_engineering.py   # Python kodları (tek dosyada ise)
├── README.md               # Bu dosya
```

## ⚙️ Nasıl Çalıştırılır?

1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install pandas scikit-learn
   ```

2. Python dosyasını çalıştırın veya Jupyter Notebook ile adımları izleyin.

3. Kod, veriyi temizleyecek, TF-IDF ile vektörleştirecek ve modelleyecektir.

## 📊 Model Performansı

Model, anahtar kelime tabanlı etiketleme ile oluşturulan veri üzerinde Logistic Regression algoritması ile eğitilmiştir. Sonuçlar `classification_report`, `accuracy_score` ve `confusion_matrix` metrikleri ile değerlendirilmiştir.

## 🧠 Anahtar Kelimeler

Aşağıdaki anahtar kelimeler sosyal mühendislik saldırılarına işaret edebilir:
- `password`, `login`, `urgent`, `click`, `verify`, `account`, `bank`, `credit`, `update`, `security`, `alert`, `confirm`

## 📚 Kaynakça

- Jurafsky & Martin. *Speech and Language Processing*.
- Scikit-learn Documentation: https://scikit-learn.org
- [Hadnagy, C.](https://www.wiley.com/en-us/Social+Engineering%3A+The+Art+of+Human+Hacking-p-9780470639535) *Social Engineering: The Art of Human Hacking*

## 📝 Lisans

Bu proje eğitim amaçlıdır. Herhangi bir ticari kullanım için uygun değildir.
