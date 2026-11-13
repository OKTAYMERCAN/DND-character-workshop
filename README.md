# DND Character Workshop

**Karakter Atölyesi** · Tek dosyalık, tarayıcıda çalışan D&D karakter sheet oluşturucu.
A single-file, in-browser D&D character sheet builder.

![Açık tema / Light theme](docs/screenshot-light.png)

[Türkçe](#türkçe) · [English](#english)

---

## Türkçe

Bir D&D sürümü seçin; form, kurallar ve karakter sheet'i o sürüme göre değişir. Sunucu, derleme adımı ya da bağımlılık yoktur: `index.html` dosyasını tarayıcıda açmanız yeterli.

### Özellikler

- **6 sürüm:** B/X (1981), AD&D 2. Baskı, D&D 3.5, 4. Baskı, 5. Baskı (2014) ve 5.5 (2024).
- **Sürüme göre oluşturma ekranı:** ırk, sınıf, geçmiş, hizalanma ve yetenek bonusları her sürümün kendi kurallarına göre hesaplanır.
- **Rastgele karakter:** tek tuşla tüm karakter, ya da zar simgesiyle tek tek alanlar.
- **Yetenek puanı yöntemleri:** 3d6, 4d6 (en düşüğü at), standart dizi, puan satın alma, elle giriş.
- **3 sayfalık sheet** (resmî 5E sheet düzeninden esinlenilmiştir):
  1. Karakter: statlar, kurtarmalar, beceriler, AC, can, saldırılar, ekipman, kişilik.
  2. Hikâye ve görünüm: yaş, boy, kilo, göz/ten/saç, **resim ekleme**, hikâye, müttefikler, hazine.
  3. Büyüler (4e'de Güçler): büyü yuvaları ve seviye başına büyü listeleri.
- **Dışa ve içe aktarma:** karakter resmiyle birlikte JSON olarak.
- **Kayıtlı karakterler:** tarayıcıda (`localStorage`) saklanır.
- **Arayüz:** Türkçe / İngilizce, aydınlık ve tam siyah OLED tema, telefon uyumlu.

### Kullanım

1. Depoyu indirin ve `index.html` dosyasını tarayıcıda açın.
2. Ya da GitHub Pages'i açın: *Settings → Pages → Deploy from a branch → `main` / `(root)`*.

### Veri ve gizlilik

Her şey tarayıcınızda kalır. Karakterler yalnızca cihazınızdaki `localStorage` içinde saklanır; dışarı veri gönderilmez. Tek dış istek, yazı tipleri için Google Fonts'tur (çevrimdışıyken sistem fontlarına düşer).

### Bilinen sınırlar

- Seviye 1 sonrası sınıf özellikleri listelenmez; 3.5 feat ön koşulları denetlenmez.
- Büyü yuvaları 5e için tam hesaplanır. 3.5'te yalnızca Sihirbaz, Rahip, Druid ve Büyücü için hesaplanır; diğer durumlarda yuvalar elle girilir.
- B/X ve AD&D 2e karakterleri 1. seviyeden başlar.

---

## English

Pick a D&D edition and the form, rules and character sheet follow it. There is no server, build step or dependency: open `index.html` in a browser.

### Features

- **6 editions:** B/X (1981), AD&D 2nd Edition, D&D 3.5, 4th Edition, 5th Edition (2014) and 5.5 (2024).
- **Edition-aware creation:** race, class, background, alignment and ability bonuses follow each edition's own rules.
- **Random character:** one button for a full character, or the dice icons for single fields.
- **Ability score methods:** 3d6, 4d6 drop lowest, standard array, point buy, manual entry.
- **3-page sheet** (inspired by the official 5E sheet layout):
  1. Character: ability scores, saves, skills, AC, HP, attacks, equipment, personality.
  2. Story & looks: age, height, weight, eyes/skin/hair, **image upload**, backstory, allies, treasure.
  3. Spells (Powers in 4e): spell slots and per-level spell lists.
- **Export and import:** as JSON, including the character image.
- **Saved characters:** stored in the browser (`localStorage`).
- **Interface:** Turkish / English, light and true-black OLED themes, mobile friendly.

### Usage

1. Download the repository and open `index.html` in a browser.
2. Or enable GitHub Pages: *Settings → Pages → Deploy from a branch → `main` / `(root)`*.

### Data and privacy

Everything stays in your browser. Characters are stored only in your device's `localStorage` and nothing is sent anywhere. The only external request is Google Fonts for typefaces (it falls back to system fonts offline).

### Known limitations

- Class features beyond level 1 are not listed and 3.5 feat prerequisites are not checked.
- Spell slots are fully computed for 5e. In 3.5 they are computed only for Wizard, Cleric, Druid and Sorcerer; otherwise enter them by hand.
- B/X and AD&D 2e characters start at level 1.

---

![Koyu tema / Dark theme](docs/screenshot-dark.png)

## Yasal not / Legal

Resmî olmayan bir hayran aracıdır. Dungeons & Dragons, Wizards of the Coast'un tescilli markasıdır; bu proje onunla bağlantılı değildir. Resmî karakter sheet PDF'lerini ya da telifli kural metinlerini depoya eklemeyin.

Unofficial fan tool. Dungeons & Dragons is a trademark of Wizards of the Coast; this project is not affiliated with them. Do not commit official character sheet PDFs or copyrighted rules text to this repository.
