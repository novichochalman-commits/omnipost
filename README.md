# OmniPost Agent 🚀
> **AI-Powered Social Media Automation Platform** — Otomasi posting ke **Threads**, **X (Twitter)**, **LinkedIn**, dan **Facebook** secara aman, terjadwal, dan mandiri tanpa API resmi.

[![Release](https://img.shields.io/github/v/release/novichochalman-commits/omnipost?style=flat-square&color=blue)](https://github.com/novichochalman-commits/omnipost/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20VPS%20%7C%20macOS-brightgreen?style=flat-square)](#)
[![Python](https://img.shields.io/badge/python-3.10%20%7C%203.11%20%7C%203.12%20%7C%203.13%2B-blue?style=flat-square)](#)

---

## ⚡ Instalasi Cepat (1 Baris Perintah)

### 🐧 Untuk Linux VPS (Ubuntu / Debian / CentOS / macOS):
Buka terminal SSH VPS Anda lalu jalankan:
```bash
curl -fsSL https://github.com/novichochalman-commits/omnipost/releases/latest/download/install.sh | bash
```

### 🪟 Untuk Windows (PowerShell):
Buka PowerShell lalu jalankan:
```powershell
$s = irm "https://github.com/novichochalman-commits/omnipost/releases/download/v1.0.0/install.ps1?v=2"; iex $s.Substring($s.IndexOf('#'))
```
*(Atau perintah standar):*
```powershell
irm https://github.com/novichochalman-commits/omnipost/releases/latest/download/install.ps1 | iex
```

---

## ✨ Fitur Utama

- 🧵 **Threads (Meta):** Posting teks, multi-media gambar, video, dan tag topik (*topic tags*).
- 🐦 **X (Twitter):** Posting tweet, media, threads panjang, dengan pemotongan cerdas proteksi link affiliate (*smart URL truncation*).
- 💼 **LinkedIn:** Posting update, gambar, serta fitur link pembelian di **komentar pertama** (*first comment*).
- 📘 **Facebook:** Posting teks dan media foto.
- 🛒 **Affiliate Automation System:** Rotasi produk acak seimbang (*smart fair-shuffle*), AI storytelling otomatis, dan import produk dari file Excel.
- 🤖 **AI Copywriter Engine:** Integrasi fleksibel dengan LLM (Groq, OpenAI, Ollama, OpenRouter, Gemini).
- 🕒 **Human-like Scheduler:** Penjadwalan cerdas dengan variasi waktu acak (*natural jitter*) agar akun terbebas dari deteksi bot.
- 🌐 **Modern Dark-Mode Dashboard:** Tampilan web premium, responsif, dan ringan.
- 🔒 **AES-256 Encryption:** Kredensial akun dan sesi browser dienkripsi secara aman.

---

## 🎮 Pengendali Layanan CLI (*Hermes-Style*)

Setelah terinstall, Anda dapat mengontrol layanan OmniPost kapan saja melalui terminal:

```bash
omnipost status      # Menampilkan status lengkap (PID, Port HTTP, HWID, status lisensi)
omnipost start       # Menyalakan server di background daemon
omnipost start -f    # Menyalakan dengan log interaktif di layar terminal
omnipost stop        # Menghentikan server dan membebaskan port
omnipost restart     # Memulai ulang server
omnipost logs        # Melihat aktivitas realtime postingan
omnipost license     # Melihat Hardware ID perangkat untuk lisensi
```

---

## 🐳 Opsi Alternatif: Docker & Docker Compose

Jalankan langsung di server menggunakan Docker:

```bash
docker compose up -d
```
Akses dashboard di browser Anda pada: **`http://localhost:8080`** (atau `http://IP_VPS:8080`).

---

## 📖 Dokumentasi Lengkap
Panduan distribusi komersial, konfigurasi firewall, import cookies tanpa monitor, dan deployment VPS dapat dibaca di:  
👉 **[PANDUAN_GITHUB_DAN_VPS.md](PANDUAN_GITHUB_DAN_VPS.md)**
