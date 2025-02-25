# Spam-Detector-Application

Spam Detection Uygulaması / Spam Detection Application

📌 Açıklama / Description

Bu proje, SMS mesajları üzerinde spam tespiti yapan bir makine öğrenimi uygulamasıdır. UCI ML 'SMS Spam Collection' veri seti kullanılarak, metin verileri temizlenip TF-IDF vektörizasyonu uygulanmış ve Naive Bayes algoritması ile model eğitilmiştir.

This project is a machine learning application for spam detection in SMS messages. Using the UCI ML 'SMS Spam Collection' dataset, the text data is cleaned, vectorized with TF-IDF, and trained with a Naive Bayes algorithm.

🛠️ Kullanılan Kütüphaneler / Libraries Used

NumPy

Pandas

Matplotlib

Scikit-learn (train_test_split, TfidfVectorizer, MultinomialNB, accuracy_score, classification_report)

Regular Expressions (re)

String

🗃️ Veri Seti / Dataset

Kaggle: SMS Spam Collection Dataset

İçerik: SMS mesajları, "spam" veya "ham" (spam olmayan) olarak etiketlenmiştir.

The dataset contains SMS messages labeled as "spam" or "ham" (not spam).

🧪 Test / Testing

example = ["Congratulations! You won 100 dollar gift card!"]
example_tfidf = vectorizer.transform(example)
print("Spam (1) or not (0):", model.predict(example_tfidf)[0])

Bu örnek kod, rastgele bir mesajın spam olup olmadığını tahmin eder.
This example code predicts whether a given message is spam or not.

📂 Çalıştırma / Running the Project

python spam_detection.py

Bu komut veri setini indirir, modeli eğitir ve sonuçları ekrana yazdırır.
This command downloads the dataset, trains the model, and prints the results.
