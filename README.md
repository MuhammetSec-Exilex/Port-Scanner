```markdown
# 🔍 Port Scanner

Python CLI tabanlı çoklu iş parçacıklı (multithreaded) port tarayıcı. Güvenlik önerileriyle birlikte açık portları tespit eder. Kullanıcı dostu arayüz, ASCII logo ve animasyonlu giriş ekranıyla birlikte gelir.

## 🚀 Özellikler

- ⚡ Hızlı tarama (multi-threaded)
- 🎨 Renkli terminal çıktısı (colorama + termcolor)
- 🔠 ASCII logo ve type-effect animasyon
- 🛡️ Açık portlara özel güvenlik önerileri
- 🧪 CLI argüman desteği

---

## 🧰 Gereksinimler

Proje sanal bir ortamda çalıştırılmalı:

```bash
python3 -m venv venv
source venv/bin/activate  # Windows için: venv\Scripts\activate
pip install -r requirements.txt
```

---

## 📦 Kurulum

```bash
git clone https://github.com/MuhammetSec-Exilex/Port-Scanner.git
cd Port-Scanner
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

---

## 🧪 Kullanım

```bash
python3 PortScanner_1.0.py -t <hedef_ip_adresi> -sp <başlangıç_portu> -ep <bitiş_portu>
```

### Örnek:

```bash
python3 PortScanner_1.0.py -t scanme.nmap.org -sp 20 -ep 100
```

---

## 📸 Ekran Görüntüsü

![screenshot](https://github.com/MuhammetSec-Exilex/Port-Scanner/assets/image1.png)

---

## 🧠 Örnek Güvenlik Uyarısı

```
Port 21 (FTP): FTP transmits data in plaintext... 🔐 Öneri: FTPS/SFTP'ye geçin, anonim erişimi kapatın.
```

---

## 👨‍💻 Geliştirici

- Muhammet Alperen Şıvgın – [GitHub](https://github.com/MuhammetSec-Exilex)

---

## 📜 Lisans

MIT Lisansı. Detaylar için `LICENSE` dosyasını inceleyin.
```
