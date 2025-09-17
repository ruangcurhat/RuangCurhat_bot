# Curhat Bot Telegram (Simple, anonim, 1 konselor)

Fitur:
- Curhat anonim (user tidak terlihat ke konselor).
- Satu konselor (grup/akun), jam kerja 12:00–17:00.
- Jika dalam jam kerja: pesan (teks/foto) diteruskan ke konselor.
- Jika di luar jam kerja: bot membalas otomatis bahwa konselor sedang tutup.
- Konselor bisa membalas dengan `/reply <client_id> <pesan>`.
- Konselor bisa kirim foto ke klien dengan:
  - Reply ke foto di grup + `/sendphoto <client_id>` OR
  - `/sendphoto <client_id> <image_url>`

## Cara Jalankan (Lokal)

1. Pastikan Python 3.9+ terpasang.

2. Buat folder proyek, lalu simpan `bot_app.py`, `requirements.txt`, `README.md`.

3. (Opsional tapi direkomendasikan) Buat virtual environment:
   - Linux / macOS:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   - Windows PowerShell:
     ```powershell
     python -m venv venv
     .\venv\Scripts\Activate.ps1
     ```

4. Install dependency:
   ```bash
   pip install -r requirements.txt
