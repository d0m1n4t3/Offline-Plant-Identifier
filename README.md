# EN:
# 🌿 Offline Plant Identifier

Offline Plant Identifier is a mobile application that works entirely offline to identify plants using a built-in machine learning model. It analyzes photos taken from the camera or selected from the gallery and predicts the plant species using a TensorFlow Lite model.

---

## 🚀 Features

- 📷 Load images from camera or gallery  
- 🤖 On-device classification using TensorFlow Lite (TFLite)  
- 📡 Works fully **offline**  
- 🧠 Simple and user-friendly interface

An Android app that identifies plants offline using a TensorFlow Lite model.

## 🔧 Installation
# 📦 Requirements
Android Studio (Electric Eel or later recommended)

Android SDK (API 30+)

A physical device or emulator running Android 10+

## ⚙️ Steps
Clone the Repository
Either download the ZIP or use Git:
`git clone https://github.com/d0m1n4t3/offline-plant-identifier.git`

Open in Android Studio

Open Android Studio

Go to File > Open

Select the OfflinePlantIdentifier project folder

Allow Permissions
Make sure the app has Camera and Storage permissions declared in AndroidManifest.xml.

Build the Project
Android Studio will automatically download dependencies and build the project.

Run the App

Click on the green Run ▶️ button

Choose your device or emulator

The app will launch and be ready to use

## 🚀 Usage
Launch the App
When the app starts, you’ll see a simple interface to either take a photo or select one from the gallery.

Choose an Image

Click “Take Photo” to open the camera

Or click “Choose from Gallery” to select an existing image

View Result
The app will process the image offline using a TensorFlow Lite model and display the predicted plant name (if supported by the model).

Model Info

The default model can recognize a limited number of plant types.

For better accuracy, you can replace the plant_model.tflite file with a custom-trained model.

# TR:
# 🌿 Çevrimdışı Bitki Tanımlayıcı

Bu uygulama, TensorFlow Lite modeli kullanarak çevrimdışı bitki tanımlama yapar. Aşağıda kurulum ve kullanım talimatları yer almaktadır.

## 📦 Gereksinimler
- **Android Studio**: Electric Eel veya sonrası önerilir
- **Android SDK**: API 30+
- **Cihaz/Emülatör**: Android 10 veya üstü

## 🔧 Kurulum
1. **Depoyu Klonlayın**
   ```bash
   git clone https://github.com/d0m1n4t3/offline-plant-identifier.git
   ```
   Alternatif olarak, ZIP dosyasını indirip çıkarabilirsiniz.

2. **Android Studio’da Açın**
   - Android Studio’yu başlatın.
   - **Dosya > Aç**’ı seçin.
   - `OfflinePlantIdentifier` proje klasörünü seçin.

3. **İzinleri Kontrol Edin**
   - `AndroidManifest.xml` dosyasında **Kamera** ve **Depolama** izinlerinin tanımlı olduğundan emin olun.

4. **Projeyi Derleyin**
   - Android Studio, bağımlılıkları otomatik olarak indirir ve projeyi derler.

5. **Uygulamayı Çalıştırın**
   - Yeşil **Çalıştır ▶️** düğmesine tıklayın.
   - Cihazınızı veya emülatörü seçin.
   - Uygulama başlatılır ve kullanıma hazır olur.

## 🚀 Kullanım
1. **Uygulamayı Başlatın**
   - Uygulama açıldığında, fotoğraf çekme veya galeri seçimi için basit bir arayüz göreceksiniz.

2. **Görüntü Seçin**
   - **Kamera ile Çek**: Kamerayı açar.
   - **Galeriden Seç**: Mevcut bir görüntüyü seçmenizi sağlar.

3. **Sonuçları Görüntüleyin**
   - Uygulama, görüntüyü çevrimdışı TensorFlow Lite modeli ile işler ve bitki adını (modelin desteklediği türlerde) gösterir.

## ℹ️ Model Bilgisi
- Varsayılan model, sınırlı sayıda bitki türünü tanır.
- Daha yüksek doğruluk için `plant_model.tflite` dosyasını özel bir eğitilmiş modelle değiştirebilirsiniz.

## 📝 Notlar
- Sorun yaşarsanız, cihazınızın veya emülatörünüzün gereksinimleri karşıladığından emin olun.
- Daha fazla bilgi için [TensorFlow Lite dokümantasyonunu](https://www.tensorflow.org/lite) inceleyin.
