# 📁 Proje Yöneticisi Discord Botu

Discord üzerinden kişisel proje yönetimi yapmanızı sağlayan bir bottur.
Kullanıcılar projelerini ekleyebilir, güncelleyebilir, silebilir, beceri
atayabilir ve listeleyebilir.

## ✨ Özellikler

-   🆕 Yeni proje ekleme
-   📋 Projeleri listeleme
-   📝 Proje bilgilerini güncelleme
-   🗑️ Proje silme
-   🧠 Projeye beceri ekleme
-   📌 Hazır durum (status) listesi
-   🔍 Proje adını yazarak projekt bilgilerine direkt erişme

## 📦 Gereksinimler

    pip install discord.py

sqlite3 Python içinde hazır gelir.

## 📂 Proje Yapısı

    project-bot/
    ├── bot.py
    ├── logic.py
    ├── config.py
    ├── database.db
    └── README.md

## ⚙️ config.py Örneği

    DATABASE = "database.db"
    TOKEN = "DISCORD_BOT_TOKENINIZ"

## 🧠 Kullanılabilir Komutlar

### !start

Botu başlatır ve tanıtım mesajı gönderir.

### !info

Tüm kullanılabilir komutları gösterir.

### !new_project

Yeni proje oluşturur (ad, link ve durum bilgisi alınır).

### !projects

Kullanıcının projelerini listeler.

### !skills

Seçilen projeye beceri ekler.

### !delete

Bir projeyi siler.

### !update_projects

Proje adı, açıklaması, linki veya durumunu günceller.

## ▶️ Botu Çalıştırma

    python bot.py

## 🛠️ Geliştirici Notları

-   Her kullanıcı kendi projelerini yönetir.
-   Yanıtlar wait_for ile alınır.

## 📞 İletişim

Her türlü geliştirme isteği için iletişime geçebilirsiniz.
