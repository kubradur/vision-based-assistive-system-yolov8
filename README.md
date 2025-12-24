## 👁️ VisionNode: Görme Engelliler İçin Yapay Zeka Rehberi

> *Teknoloji, engelleri kaldırdığında gerçekten değer kazanır.*

**VisionNode**, görme engelli bireylerin günlük hayatta çevrelerini daha güvenli şekilde algılayabilmeleri için geliştirilen, **yapay zekâ destekli bir yol asistanı prototipidir**. Sistem, kameradan aldığı görüntülere göre kullanıcıya **Türkçe sesli uyarılar** verir.

---

# 🌟 Neden Bu Proje?

Bu proje yalnızca nesne tanımayı hedeflemez. Çünkü gerçek hayatta en büyük engeller bazen bir **duvar**, **kapalı bir kapı** ya da **tanımlanamayan bir yüzey** olabilir.

VisionNode, bu nedenle iki yaklaşımı birleştirir:

* Yapay zekâ ile **tanıdık nesneleri** algılama
* Nesne olmasa bile **fiziksel engelleri** fark edebilme

Amaç, kullanıcıyı yormadan, yalnızca gerekli anlarda bilgi veren sakin bir dijital rehber oluşturmaktır.

---

## 🧠 Nasıl Çalışır?

* Kamera sürekli görüntü alır
* YOLOv8 modeli kişi, araba, sandalye gibi nesneleri algılar
* Nesne algılanmazsa, görüntüdeki kenar yoğunluğu analiz edilerek engel kontrolü yapılır
* Algılanan duruma göre uygun Türkçe sesli uyarı verilir
* Sesler üst üste binmez ve belirli aralıklarla çalınır

---

## 🛠️ Kullanılan Teknolojiler

* Python
* OpenCV
* NumPy
* YOLOv8 (Ultralytics)
* gTTS (Text-to-Speech)
* Pygame

---

## 🚀 Çalıştırma

Gerekli kütüphaneleri yükleyin:

pip install opencv-python ultralytics numpy gtts pygame

Ses dosyalarını oluşturun:

python ses_olustur.py

Sistemi başlatın:

python main.py

> Not: Ses dosyaları proje ile aynı dizinde bulunmalıdır.

---

## 🎯 Öne Çıkan Özellikler

* Gerçek zamanlı nesne algılama
* Nesne yokken engel tespiti
* Türkçe sesli geri bildirim
* Ses karmaşası olmadan sade uyarı sistemi

---

## 📝 Geliştiriciden Not

Bu proje, erişilebilirlik odaklı bir **prototip çalışmasıdır**. Kod yapısı sade tutulmuş ve geliştirilmeye açık olacak şekilde tasarlanmıştır.

Geri bildirimler ve katkılar memnuniyetle karşılanır.
