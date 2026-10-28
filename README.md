# Neon Alley — PC Arcade Edition (Gudang Neon)

Game arcade cyberpunk top-down shooter 2D retro **eksklusif untuk PC (Keyboard & Mouse)** dengan synthwave procedural audio, visual pixelated neon, dan mekanisme tempur serba cepat.

---

## 🖥️ Eksklusif PC (Keyboard & Mouse)

Game ini dirancang khusus untuk kenyamanan dan presisi bermain di **Desktop / Laptop (PC)**:
- Menggunakan kontrol crosshair mouse penuh dengan bidikan sudut 360 derajat.
- Layout dan kontrol sentuh/mobile telah dihapus sepenuhnya untuk memberikan performa murni arcade cabinet PC.
- Dilengkapi pendeteksi layar: jika dibuka pada perangkat sentuh atau layar ponsel kecil, game akan menampilkan peringatan untuk membukanya di komputer PC.

---

## 🚀 Fitur Gameplay

1. **Sistem Multi-Senjata (Arsenal Switcher):**
   - **Blaster (Tombol `1`):** Akurat, stabil, damage 1, kapasitas 12 peluru.
   - **Neon Shotgun (Tombol `2`):** Menyebarkan 5 proyektil sekaligus, daya hancur tinggi untuk jarak dekat, kapasitas 6 shell.
   - **Plasma SMG (Tombol `3`):** Tembakan otomatis (rapid laser) berkecepatan tinggi, kapasitas 30 peluru (cukup tahan klik kiri untuk menembak terus-menerus).
   - Penggantian senjata cepat dapat menggunakan tombol `1`, `2`, `3`, `Q`, atau *Mouse Scroll Wheel*.

2. **Mekanik Dodge Dash (I-Frames):**
   - Tekan **`SHIFT`** atau **Klik Kanan Mouse** untuk melakukan dash lincah (kecepatan 540 px/s).
   - Selama durasi dash, pemain mendapatkan *Invulnerability Frames (I-Frames)* untuk menembus tembakan dan menghindari serangan musuh tanpa terkena damage.
   - Dilengkapi efek visual *cyan afterimage ghost trails* dan indikator cooldown di HUD.

3. **Barel Peledak Berantai (Explosive Barrels):**
   - Setiap stage kini dilengkapi barel bahan bakar merah bergaris hazard kuning `[TNT]`.
   - Menembak atau menebas barel akan memicu ledakan beradius 95px dengan gelombang kejut (*shockwave ring*), guncangan layar (*screen shake*), dan efek api.
   - Ledakan dapat memicu reaksi berantai (*chain reaction*) jika ada barel lain di dekatnya dan melumat kerumunan musuh sekaligus!

4. **Boss Fight Overdrive & Health Bar:**
   - Pertarungan melawan **Cyber Overlord** di Stage 3 menampilkan *Boss Health Bar* di bagian atas layar.
   - Ketika HP Boss tersisa $\le 50\%$, Boss memasuki mode **OVERDRIVE**: aura merah membara, pergerakan lebih agresif, dan secara berkala melepaskan serangan *bullet-hell 10-way radial burst*!

5. **Sistem Combo Multiplier:**
   - Mengeliminasi musuh secara berurutan dalam rentang 2.4 detik mengaktifkan combo:
     - 2 musuh: **COMBO x1.5**
     - 3 musuh: **COMBO x2.0**
     - 4+ musuh: **COMBO x3.0 ULTRA!**
   - Skor bonus berlipat ganda sesuai tingkat combo yang dicapai.

6. **Dukungan Standalone Offline (LocalStorage):**
   - Rekor skor tertinggi (*best score*) dan waktu tercepat (*best time*) tersimpan otomatis di `localStorage` peramban.

---

## 🎮 Kontrol Permainan (Keyboard & Mouse)

| Aksi | Tombol Keyboard / Mouse |
|---|---|
| **Bergerak** | `W` `A` `S` `D` atau Tombol Panah |
| **Membidik (Aim)** | Arahkan Kursor Mouse |
| **Menembak** | **Klik Kiri** (Tahan untuk SMG) |
| **Dodge Dash** | **`SHIFT`** atau **Klik Kanan** |
| **Ganti Senjata** | **`1`**, **`2`**, **`3`**, **`Q`**, atau *Scroll Wheel* |
| **Tebasan Pedang (Melee)** | **`SPACE`** atau **`E`** |
| **Isi Ulang (Reload)** | **`R`** |
| **Jeda (Pause)** | **`P`** atau **`ESC`** |

---

## 📁 Struktur File

- [`index.html`](file:///C:/Users/user/.gemini/antigravity/scratch/neon-alley/index.html) — File utama game versi PC Arcade Edition.
- [`neon_alley_canva.html`](file:///C:/Users/user/.gemini/antigravity/scratch/neon-alley/neon_alley_canva.html) — Cadangan kode asli Canva.
- [`README.md`](file:///C:/Users/user/.gemini/antigravity/scratch/neon-alley/README.md) — Panduan fitur dan kontrol PC.

---

## 🕹️ Cara Menjalankan

Cukup klik dua kali berkas [`index.html`](file:///C:/Users/user/.gemini/antigravity/scratch/neon-alley/index.html) menggunakan browser desktop apa pun (Google Chrome, Microsoft Edge, Firefox, Brave, Opera, Safari).
