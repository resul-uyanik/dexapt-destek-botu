# 🤖 DEXAPT | Görsel Destekli AI & Destek Botu Paneli

DEXAPT, modern web teknolojileriyle geliştirilmiş, yerel depolama tabanlı dinamik bir yapay zeka simülasyonu ve destek botu yönetim panelidir. Kullanıcıların sorularına anlık yanıtlar verirken, botun bilmediği kavramları canlı olarak öğrenebilmesi için gelişmiş bir yönetici arayüzü ve istatistik paneli sunar.

---

## 🚀 Öne Çıkan Özellikler

* **🧠 Dinamik Bilgi Bankası (Hafıza Yapısı):** Bot, sorulan soruları yerel hafızasından tarar ve kullanıcıya anında doğru yanıtı döndürür.
* **⚙️ Canlı Yönetici Müdahale Alanı (Admin Panel):** Botun yanıtını bulamadığı durumlarda otomatik olarak admin panel alanı devreye girer. Yönetici yeni bilgiyi anlık olarak ekleyebilir ve botun zekasını gerçek zamanlı olarak geliştirebilir.
* **💾 Kalıcı Yerel Depolama:** Öğretilen tüm yeni kavramlar ve bot hafızası `localStorage` (`dexapt_memory`) mimarisi üzerinde JSON formatında güvenle saklanır; sayfa yenilense bile veriler kaybolmaz.
* **📊 İstatistik Paneli:** Botun o an kaç adet kavram bildiğini gerçek zamanlı olarak takip eden dinamik `Zeka: X Kavram` sayacı.
* **📜 Yönetici Log Takibi:** Botun arka planda gerçekleştirdiği tüm bellek yazma, öğrenme ve müdahale süreçlerini terminal benzeri bir arayüzle izleme imkanı.
* **🛡️ Güvenli Bellek Sıfırlama:** Tek bir butonla yönetici onay mekanizmalı (`confirm`) tüm bot hafızasını temizleme fonksiyonu.
* **🎨 Fütüristik Gece Modu Tasarımı:** Google Fonts (`Montserrat`) entegrasyonlu, neon renk paletlerine ve akıcı kaydırma efektlerine sahip modern CSS arayüzü.

---

## 🛠 Kullanılan Teknolojiler

* **HTML5:** Panel hiyerarşisi, sohbet pencereleri ve log kayıt alanları.
* **CSS3 (Modern UI):** Neon ışık efektleri, asimetrik gölgelendirmeler, özel CSS değişkenleri (`:root`) ve responsive arayüz tasarımı.
* **Vanilla JavaScript (ES6+):** Gelişmiş string manipülasyonları (`toLowerCase`), `localStorage` yönetimi, DOM manipülasyonları ve asenkron bot durum yönetimleri.

---

## 📂 Dosya Yapısı

```text
├── dexapt destek botu.html   # Tüm HTML, CSS ve JavaScript mimarisini içeren ana dosya
└── resim/                    # Arka plan, bot ikonları ve logolar (Örn: ytb.png)
