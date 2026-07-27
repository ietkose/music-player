# Audio Player

[![Java](https://img.shields.io/badge/Java-15%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![CLI](https://img.shields.io/badge/CLI-Audio_Player-black.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)](https://en.wikipedia.org/wiki/Command-line_interface)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

**[Visit Project Repository / Proje Deposu](https://github.com/ietkose/music-player)**

⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝

## 🇬🇧 ENGLISH

A lightweight command-line audio player built using native Java Sound API (`javax.sound.sampled`). It enables real-time playback control for `.wav` audio files directly from the terminal interface.

---

### 🎸 Key Features
* **Interactive Playback Controls**:
  * `P` : **Play** audio stream
  * `S` : **Stop / Pause** playback
  * `R` : **Reset** audio to the beginning
  * `Q` : **Quit** the application
* **Modern Java Syntax**: Implements clean switch expressions (Java 15+) for streamlined event handling.
* **Robust Error Handling**: Gracefully handles missing files, unsupported audio formats, and line exceptions.

---

### 🎸 Tech Stack & Concepts
* **Language:** Java (v15 or higher)
* **API:** Java Sound API (`javax.sound.sampled`)
* **Concepts:** File I/O, Audio Streams, Clip Interface, Exception Handling, Scanner Input Processing

---

### 🎸 Installation & Usage

#### Prerequisites
* **Java Development Kit (JDK 15+)** installed and configured.

#### 1. Clone the Repository
```bash
git clone [https://github.com/ietkose/music-player.git](https://github.com/ietkose/music-player.git)
cd music-player
```

#### 2. Setup Audio File
Place your .wav file inside the assets/ directory (or update the audio path in App.java).

#### 3. Compile the Application
```bash
javac App.java -d bin
```

#### 4. Run the Player
```bash
java -cp bin App
```

### 🎸 License
This project is licensed under the MIT License.

⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝

## 🇹🇷 TÜRKÇE
Java Sound API (javax.sound.sampled) kullanılarak geliştirilmiş, terminal üzerinden çalışan hafif bir komut satırı ses çalar uygulaması. .wav uzantılı ses dosyalarını komut satırından anlık olarak kontrol etmenizi sağlar.

### 🎸 Öne Çıkan Özellikler
* **Etkileşimli Oynatma Kontrolleri:**
  * `P` : Sesi Oynat
  * `S` : Sesi Durdur / Duraklat
  * `R` : Sesi başa Sıfırla
  * `Q` : Uygulamadan Çık
* **Modern Java Sözdizimi:** Java 15+ ile gelen switch ifadeleri ile temiz ve okunabilir kod yapısı.
* **Hata Yakalama Mekanizması:** Eksik dosya, desteklenmeyen ses formatı ve akış hatalarına karşı güvenli hata yönetimi.

### 🎸 Kullanılan Teknolojiler ve Kavramlar
* **Dil:** Java (v15 veya üzeri)
* **Kütüphane / API:** Java Sound API (javax.sound.sampled)
* **Kavramlar:** Dosya G/Ç (File I/O), Ses Akışları (Audio Streams), İstisna Yönetimi (Exception Handling)

### 🎸 Kurulum ve Çalıştırma
**Gereksinimler**
* Sisteminizde JDK 15 veya üzeri sürümün yüklü olması gerekir.

#### 1. Depoyu Klonlayın
```bash
git clone [https://github.com/ietkose/music-player.git](https://github.com/ietkose/music-player.git)
cd music-player
```

#### 2. Ses Dosyası Ekleme
Kendi .wav uzantılı ses dosyanızı assets/ klasörüne ekleyin (veya App.java içerisindeki dosya yolunu güncelleyin).

#### 3. Kodu Derleyin
```bash
javac App.java -d bin
```

#### 4. Uygulamayı Başlatın
```bash
java -cp bin App
```

### 🎸 Lisans
Bu proje MIT lisansı altında lisanslanmıştır.

⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝⸝

Sample Video / Örnek Video
https://github.com/user-attachments/assets/3f91f79b-0da4-4676-9547-3d1b30af84fa
