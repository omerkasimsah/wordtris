# 🧩 WordTris — Kelime & Blok Bulmaca Oyunu
### Hybrid Mobile Word & Falling Block Puzzle Game

> **JavaScript**, **HTML5 Canvas** ve **Capacitor (Android)** ile geliştirilmiş; Tetris mekaniklerini kelime türetme ve anagram çözme ile birleştiren hibrit mobil bulmaca oyunu.  
> *A hybrid mobile puzzle game that merges classic falling-block mechanics with vocabulary matching and anagram solving, built with JavaScript, HTML5 Canvas, and Capacitor.*

---

## 🇹🇷 Türkçe Açıklama

### 🎮 Oyun Konsepti
**WordTris**, yukarıdan düşen harf bloklarını doğru sıralayarak geçerli kelimeler oluşturma ve tahtayı temizleme mantığına dayanan tempolu bir zeka oyunudur. Klasik blok yerleştirme heyecanını zengin bir sözlük hazinesi ve kelime kombinasyonlarıyla bir araya getirir.

### ✨ Temel Özellikler
- **🧱 Düşen Harf Mekaniği:** Bloklar aşağı indikçe yatay, dikey veya çapraz kelime kombinasyonları oluşturma.
- **⚡ Kombo ve Puan Çarpanları:** Uzun kelimelerde ve art arda yapılan patlamalarda ekstra kombo puanları.
- **📱 Mobil Dokunmatik Kontroller:** Mobil ekranlara uyarlanmış hassas kaydırma (swipe) ve dokunmatik buton kontrolleri.
- **🎵 Ses & Görsel Efektler:** Oyun içi ses efektleri, arka plan müzikleri ve parçacık animasyonları.
- **📱 Android Hibrit Entegrasyonu:** Web teknolojileriyle (HTML5/JS) geliştirilip **Capacitor** ile yerel bir Android uygulamasına dönüştürülmüştür.
- **📡 Çevrimdışı (Offline) Desteği:** İnternet bağlantısı olmadan her an oynanabilir.

### 🛠️ Teknolojiler
- **Oyun Motoru / Çekirdek:** Vanilla JavaScript, HTML5 Canvas API
- **Mobil Köprü:** `@capacitor/core`, `@capacitor/android` v8
- **Gelir Modeli (Opsiyonel):** `@capacitor-community/admob`

---

## 🇬🇧 English Overview

### 🎮 Gameplay Concept
**WordTris** combines the fast-paced spatial puzzle elements of falling-block games with vocabulary strategy. Players must strategically position descending letter tiles to form valid words, trigger chain reactions, and prevent the grid from topping out.

### ✨ Features
- **🧱 Dynamic Falling Letter Tiles:** Arrange letters in real-time across rows and columns to clear lines.
- **⚡ Word Combos & Scoring:** Multipliers for longer words, rare letters, and rapid consecutive clears.
- **📱 Touch-Optimized Mobile Controls:** Intuitive touch gestures and on-screen pads designed for quick reflexes.
- **🎵 Soundscapes & Visuals:** Retro-modern UI styling, reactive particles, and satisfying sound effects.
- **📱 Hybrid Native Packaging:** Developed in web standards and wrapped as a high-performance native Android application via **Capacitor**.
- **📡 100% Offline-Friendly:** Zero server latency; runs completely on-device.

---

## 🚀 Kurulum ve Çalıştırma / Getting Started

### 1. Depoyu Klonlayın / Clone Repository
```bash
git clone https://github.com/omerkasimsah/wordtris.git
cd wordtris
```

### 2. Bağımlılıkları Yükleyin / Install Dependencies
```bash
npm install
```

### 3. Web Sürümünü Tarayıcıda Açın / Run in Browser
`www/index.html` dosyasını doğrudan bir tarayıcıda veya yerel bir sunucuyla açabilirsiniz:
```bash
npx serve www
```

### 4. Android Projesini Derleyin / Build Android
```bash
npx cap sync
npx cap open android
```
*(Android Studio üzerinden emülatöre veya fiziksel cihaza yükleyebilirsiniz.)*

---

## 📄 Lisans / License
Bu proje [MIT Lisansı](LICENSE) kapsamında açık kaynak olarak paylaşılmıştır.
