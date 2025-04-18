# Offline Plant Identifier / Çevrimdışı Bitki Tanımlayıcı

## 🇬🇧 English

### 🌿 Overview
Offline Plant Identifier is an Android app that identifies plants using a TensorFlow Lite model, working entirely offline. Capture or select photos to predict plant species with a simple, user-friendly interface.

### 🚀 Features
- 📷 Use camera or gallery to load images
- 🤖 On-device plant classification with TensorFlow Lite
- 📡 Fully offline operation
- 🧠 Intuitive and clean interface

### 📋 Requirements
- **Android Studio**: Electric Eel or later
- **Android SDK**: API 30+
- **Device/Emulator**: Android 10 or higher

### 🔧 Installation
1. **Clone the Repository**
   ```bash
   git clone https://github.com/d0m1n4t3/offline-plant-identifier.git
   ```
   Or download and extract the ZIP file.

2. **Open in Android Studio**
   - Launch Android Studio.
   - Select **File > Open**.
   - Choose the `OfflinePlantIdentifier` folder.

3. **Verify Permissions**
   - Confirm **Camera** and **Storage** permissions are set in `AndroidManifest.xml`.

4. **Build the Project**
   - Android Studio will download dependencies and build the project automatically.

5. **Run the App**
   - Click the **Run ▶️** button.
   - Select a device or emulator.
   - The app will launch and be ready.

### 📸 Usage
1. **Open the App**
   - Start the app to see a simple interface for image selection.

2. **Choose an Image**
   - **Take Photo**: Capture a new image with the camera.
   - **Select from Gallery**: Pick an existing image.

3. **View Results**
   - The app processes the image offline and displays the predicted plant name (if supported by the model).

### 🧠 Model Details
- The default model recognizes a limited set of plants.
- Replace `plant_model.tflite` with a custom model for better accuracy.

### ℹ️ Notes
- Ensure your device/emulator meets the requirements.
- Check the [TensorFlow Lite documentation](https://www.tensorflow.org/lite) for more details.

---

## 🇹🇷 Türkçe

### 🌿 Genel Bakış
Çevrimdışı Bitki Tanımlayıcı, TensorFlow Lite modeli kullanarak tamamen çevrimdışı bitki tanımlayan bir Android uygulamasıdır. Fotoğraf çekin veya galeri seçimi yapın, bitki türlerini basit bir arayüzle tahmin edin.

### 🚀 Özellikler
- 📷 Kamera veya galeri ile görüntü yükleme
- 🤖 TensorFlow Lite ile cihaz üzerinde sınıflandırma
- 📡 Tamamen çevrimdışı çalışma
- 🧠 Kullanıcı dostu ve sade arayüz

### 📋 Gereksinimler
- **Android Studio**: Electric Eel veya sonrası
- **Android SDK**: API 30+
- **Cihaz/Emülatör**: Android 10 veya üstü

### 🔧 Kurulum
1. **Depoyu Klonlayın**
   ```bash
   git clone https://github.com/d0m1n4t3/offline-plant-identifier.git
   ```
   Veya ZIP dosyasını indirip çıkarın.

2. **Android Studio’da Açın**
   - Android Studio’yu başlatın.
   - **Dosya > Aç**’ı seçin.
   - `OfflinePlantIdentifier` klasörünü seçin.

3. **İzinleri Kontrol Edin**
   - `AndroidManifest.xml` içinde **Kamera** ve **Depolama** izinlerinin tanımlı olduğundan emin olun.

4. **Projeyi Derleyin**
   - Android Studio, bağımlılıkları indirir ve projeyi otomatik olarak derler.

5. **Uygulamayı Çalıştırın**
   - **Çalıştır ▶️** düğmesine tıklayın.
   - Bir cihaz veya emülatör seçin.
   - Uygulama başlatılır ve kullanıma hazır olur.

### 📸 Kullanım
1. **Uygulamayı Açın**
   - Uygulamayı başlatın, görüntü seçimi için sade bir arayüz görün.

2. **Görüntü Seçin**
   - **Fotoğraf Çek**: Kamerayla yeni bir görüntü yakalayın.
   - **Galeriden Seç**: Mevcut bir görüntüyü seçin.

3. **Sonuçları Görüntüleyin**
   - Uygulama, görüntüyü çevrimdışı işler ve destekleniyorsa bitki adını gösterir.

### 🧠 Model Bilgileri
- Varsayılan model, sınırlı bitki türlerini tanır.
- Daha iyi doğruluk için `plant_model.tflite` dosyasını özel bir modelle değiştirin.

### ℹ️ Notlar
- Cihaz/emülatörünüzün gereksinimleri karşıladığından emin olun.
- Daha fazla bilgi için [TensorFlow Lite dokümantasyonuna](https://www.tensorflow.org/lite) bakın.
