### **1. Python**
#### **a. Telethon**
- **Format**:  
  - `.session` file (SQLite database).  
  - Contoh nama file: `my_account.session`.  
- **Dokumentasi**: [Telethon Docs](https://docs.telethon.dev/)
- **GitHub**: [Telethon GitHub](https://github.com/LonamiWebs/Telethon)

#### **b. Pyrogram**
- **Format**:  
  - `.session` file (SQLite database).  
  - Contoh nama file: `user.session`.  
- **Dokumentasi**: [Pyrogram Docs](https://docs.pyrogram.org/)
- **GitHub**: [Pyrogram GitHub](https://github.com/pyrogram/pyrogram)

---

### **2. JavaScript / Node.js**
#### **a. GramJS**
- **Format**:  
  - File JSON atau buffer.  
  - Contoh nama file: `session.json`.  
- **Dokumentasi**: [GramJS Docs](https://gram.js.org/)
- **GitHub**: [GramJS GitHub](https://github.com/gram-js/gramjs)

#### **b. Telegraf**
- **Format**:  
  - JSON atau penyimpanan database eksternal (Redis, MongoDB, dll).  
  - Contoh nama file: `state.json`.  
- **Dokumentasi**: [Telegraf Docs](https://telegraf.js.org/)
- **GitHub**: [Telegraf GitHub](https://github.com/telegraf/telegraf)

#### **c. TDLib Bindings (tdlib-client)**
- **Format**:  
  - Binary session file (`tdlib.session`).  
- **Dokumentasi**: [TDLib Client Docs](https://tdlibx.github.io/)
- **GitHub**: [tdlib-client GitHub](https://github.com/Bannerets/tdl)

---

### **3. PHP**
#### **a. MadelineProto**
- **Format**:  
  - `.session` file (serialized data).  
  - Contoh nama file: `my_bot.session`.  
- **Dokumentasi**: [MadelineProto Docs](https://docs.madelineproto.xyz/docs/Sessions.html)
- **GitHub**: [MadelineProto GitHub](https://github.com/danog/MadelineProto)

---

### **4. Java**
#### **a. TelegramBots**
- **Format**:  
  - Tidak menyimpan session API klien.  
  - Bot hanya memerlukan token API dan data tambahan yang disimpan di database (contoh: Redis atau file JSON).  
- **Dokumentasi**: [TelegramBots Wiki](https://github.com/rubenlagus/TelegramBots/wiki)
- **GitHub**: [TelegramBots GitHub](https://github.com/rubenlagus/TelegramBots)

#### **b. Java Telegram Bot API**
- **Format**:  
  - Tidak ada file session yang dikelola otomatis.  
  - Bergantung pada implementasi pengguna.  
- **Dokumentasi**: Tidak ada dokumentasi eksplisit.  
- **GitHub**: [Java Telegram Bot API GitHub](https://github.com/pengrad/java-telegram-bot-api)

---

### **5. C#**
#### **a. TLSharp**
- **Format**:  
  - `.dat` file (binary).  
  - Contoh nama file: `session.dat`.  
- **Dokumentasi**: [TLSharp Usage](https://github.com/sochix/TLSharp#usage)
- **GitHub**: [TLSharp GitHub](https://github.com/sochix/TLSharp)

#### **b. WTelegramClient**
- **Format**:  
  - `.bin` file atau format lainnya sesuai konfigurasi pengguna.  
  - Contoh nama file: `telegram.bin`.  
- **Dokumentasi**: [WTelegramClient Docs](https://wiz0u.github.io/WTelegramClient/#example-connecting-and-logging-in)
- **GitHub**: [WTelegramClient GitHub](https://github.com/wiz0u/WTelegramClient)

---

### **6. Go (Golang)**
#### **a. go-tdlib**
- **Format**:  
  - Binary session file (`tdlib.session`).  
- **Dokumentasi**: [go-tdlib Docs](https://pkg.go.dev/github.com/zelenin/go-tdlib)
- **GitHub**: [go-tdlib GitHub](https://github.com/zelenin/go-tdlib)

#### **b. tgo**
- **Format**:  
  - File JSON atau custom.  
  - Contoh nama file: `session.json`.  
- **Dokumentasi**: Tidak ada dokumentasi resmi.  
- **GitHub**: [tgo GitHub](https://github.com/lajiverson/tgo)

---

### **7. Rust**
#### **a. Telegram-rs**
- **Format**:  
  - Binary atau JSON file.  
  - Contoh nama file: `session.json`.  
- **Dokumentasi**: Tidak ada dokumentasi eksplisit.  
- **GitHub**: [Telegram-rs GitHub](https://github.com/telegram-rs/telegram-bot)

---

### **8. Kotlin**
#### **a. Kotlogram**
- **Format**:  
  - Binary serialized session (`kotlogram.session`).  
- **Dokumentasi**: Tidak ada dokumentasi eksplisit.  
- **GitHub**: [Kotlogram GitHub](https://github.com/badoualy/kotlogram)
