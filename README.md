# smart-payment-error-feedback
AI-powered feedback tool for common payment card errors (inspired by Frink app).
# Smart Payment Error Feedback / Akıllı Ödeme Hatası Geri Bildirimi

---

## 🇹🇷 Proje Açıklaması

Bu proje, dijital ödeme sistemlerinde sıkça karşılaşılan "kart ekleme başarısız" hatalarını veri odaklı analiz ederek, kullanıcıya açıklayıcı ve yol gösterici geri bildirimler sunmayı amaçlar.

Mobil ödeme uygulamalarında kullanıcıların karşılaştığı genel hata mesajları, sorunun ne olduğunu net ifade etmediği için kullanıcı deneyimini olumsuz etkiler.  
Bu proje, Frink uygulamasında karşılaşılan bu sorundan ilham alınarak geliştirilmiştir.

---

## 🇬🇧 Project Description

This project aims to analyze common "card addition failed" errors in digital payment systems and provide users with clear, actionable feedback based on data.

General error messages in mobile payment apps often lack precise explanations, negatively affecting user experience.  
This project is inspired by a real issue encountered in the Frink app.

---

## 🇹🇷 Kullanılan Teknolojiler

- Python  
- Streamlit (Kullanıcı Arayüzü)  
- Kural tabanlı sınıflandırma (basit fonksiyonlar)

---

## 🇬🇧 Technologies Used

- Python  
- Streamlit (User Interface)  
- Rule-based classification (simple functions)

---

## 🇹🇷 Nasıl Çalışır?

1. Kullanıcı hata kodunu girer (örnek: E001, E002).  
2. Sistem, hata koduna karşılık gelen öneriyi verir.  
3. Kullanıcı öneri doğrultusunda problemi çözmeye çalışır.

---

## 🇬🇧 How It Works

1. User inputs an error code (e.g. E001, E002).  
2. The system provides a suggestion corresponding to the error code.  
3. User tries to resolve the issue based on the suggestion.

---

## 🇹🇷 Hata Kodları ve Anlamları

| Hata Kodu | Açıklama                                    |
|-----------|---------------------------------------------|
| E001      | Kartınız internet alışverişine kapalı olabilir.          |
| E002      | Kartınız 3D Secure sistemine kayıtlı olmayabilir.       |
| E003      | Uygulamanız güncel olmayabilir.                         |
| E004      | Kart limitiniz yetersiz olabilir.                        |
| Diğer     | Bilinmeyen hata, müşteri desteğine başvurun.            |

---

## 🇬🇧 Error Codes and Meanings

| Error Code | Description                                  |
|------------|----------------------------------------------|
| E001       | Your card might be blocked for online purchases.  |
| E002       | Your card might not be registered for 3D Secure.  |
| E003       | Your app might be outdated.                         |
| E004       | Your card limit might be insufficient.              |
| Other      | Unknown error, please contact customer support.     |

---

## 🇹🇷 Nasıl Çalıştırılır?

1. Projeyi klonlayın veya ZIP dosyasını indirin.  
2. Sanal ortam oluşturun ve aktif edin (opsiyonel):  
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows

Gerekli paketleri yükleyin:

pip install -r requirements.txt


Uygulamayı çalıştırın:

streamlit run app.py


🇬🇧 How to Run

Clone the project or download the ZIP file.
Create and activate a virtual environment (optional):
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

Install required packages:
pip install -r requirements.txt

Run the app:
streamlit run app.py


🇹🇷 Notlar

Proje Frink uygulamasından esinlenmiş olup resmi bir bağı yoktur.
Eğitim ve portfolyo amaçlı hazırlanmıştır.


🇬🇧 Notes

The project is inspired by the Frink app and has no official affiliation.
Developed for educational and portfolio purposes.

🇹🇷 İletişim

Tuğba Bayar
e.tugbabayar@gmail.com


🇬🇧 Contact

Tuğba Bayar
e.tugbabayar@gmail.com


