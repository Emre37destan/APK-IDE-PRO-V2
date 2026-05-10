# 🚀 APK-MASTER 2026 PRO (Global Edition)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.10+-green.svg)
![Platform](https://img.shields.io/badge/platform-Windows-orange.svg)

**[TR]** APK-MASTER, Android uygulama geliştiricileri ve mod geliştiricileri için tasarlanmış, hepsi bir arada (all-in-one) bir APK düzenleme ve optimizasyon merkezidir.

**[EN]** APK-MASTER is an all-in-one APK editing and optimization hub designed for Android application developers and modders.

---

## 🇹🇷 Türkçe Tanıtım

### ✨ Özellikler
* **Tam Otomatik Derleme:** APK parçalama (Decompile) ve yeniden derleme (Build).
* **Gelişmiş Düzenleyici:** Sözdizimi vurgulamalı QuickEditor ile hızlı kod müdahalesi.
* **Akıllı Çeviri:** Tüm projeyi tek tıkla hedef dile çevirme.
* **Güvenlik Analizi:** Şüpheli bağlantı, bot ve reklam birimi taraması.
* **ProjectFixer:** Derleme hatalarını otomatik tespit eder ve onarır.
* **Tek Tıkla EXE:** Nuitka_Kur.bat ile tüm kütüphaneler dahil, taşınabilir tek bir EXE dosyası oluşturulur.

### 📂 Dosya Yapısı
Uygulama, modüler bir çekirdek (core/) ve modern bir arayüz (gui/) mimarisine sahiptir. Diller languages/ klasöründen JSON formatında yönetilir.

---

## 🇺🇸 English Description

### ✨ Features
* **Fully Automated Build:** Decompile and Rebuild APKs seamlessly.
* **Advanced Editor:** Quick code intervention with syntax-highlighted QuickEditor.
* **Smart Translation:** Translate the entire project to the target language with one click.
* **Security Analysis:** Scans for suspicious links, bots, and ad units.
* **ProjectFixer:** Automatically detects and fixes compilation errors.
* **Single EXE:** Creates a portable, standalone EXE file including all libraries via Nuitka_Kur.bat.

---

## 🛠 Kurulum / Installation

### Gereksinimler / Requirements
* Python 3.10+
* Java JRE (Sistemde yüklü olmalıdır / Must be installed)

### Geliştirme Modu / Development Mode
```bash
pip install -r requirements.txt
python main.py

## 📦 Dağıtım / Distribution (EXE)
Nuitka_Kur.bat dosyasını çalıştırarak tüm projeyi **tek bir .exe** haline getirebilirsiniz.
> *Run Nuitka_Kur.bat to compile the entire project into a single standalone .exe.*

## 📐 Proje Mimarisi / Architecture
```text
├── assets/          # Görsel materyaller & İkonlar
├── core/            # İş mantığı & Motorlar (Translator, Fixer, vb.)
├── gui/             # Kullanıcı arayüzü bileşenleri (PyQt)
├── languages/       # Çoklu dil destek dosyaları (TR/EN)
├── resources/       # JKS ve imza dosyaları
├── themes/          # QSS Tema dosyaları
└── tools/           # Apktool, Signer ve Yardımcı araçlar

## 💡 Gemini'nin Notu (The AI Partner's Quote)
> "Kodlar sadece komutlardan ibaret değildir; onlar birer dijital sanat eseridir. Bu projenin her satırında bir mantık, her hatasında bir tecrübe gizli. Başarı, derleme (build) hatası almadığında değil, aldığın hatayı çözecek sabrı bulduğundadır."
>
> — **Your AI collaborator, Gemini. 🤖✨**

## 📄 Lisans / License
Bu proje **MIT Lisansı** ile korunmaktadır.
```
