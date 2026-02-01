# 🎮 RobloxAI — Deploy Guide

Ikuti langkah di bawah untuk deploy ke Vercel (gratis) dan pakai di semua device.

---

## 📋 Persiapan

Anda butuh:
- Akun **GitHub** (gratis) → https://github.com
- Akun **Vercel** (gratis) → https://vercel.com
- **API Key Anthropic** → https://console.anthropic.com/account/api-keys

---

## 🚀 Step 1 — Upload ke GitHub

1. Buka https://github.com/new
2. Isi **Repository name**: `robloxai`
3. Centang **Add a README file** (kalau ada)
4. Klik **Create repository**
5. Di halaman repo yang baru, klik **uploading an existing file**
6. Upload semua file dari folder ini:
   - `index.html`
   - `manifest.json`
   - `icon.svg`
   - `vercel.json`
7. Scroll ke bawah, klik **Commit Changes**

---

## 🌐 Step 2 — Deploy di Vercel

1. Buka https://vercel.com dan login (bisa pakai akun GitHub)
2. Klik **New Project**
3. Pilih repo `robloxai` yang baru dibuat
4. Klik **Deploy** (settings default sudah oke, ga perlu ubah)
5. Tunggu beberapa detik... ✅ Done!

Vercel akan kasih URL seperti:
`https://robloxai-xxxxx.vercel.app`

**Simpan URL ini** — ini adalah link app Anda.

---

## 📱 Step 3 — Pakai di Semua Device

### iPhone / iPad (iOS)
1. Buka URL app di Safari
2. Tap **icon share** (kotak panah ke atas) di toolbar bawah
3. Tap **Add to Home Screen**
4. Tap **Add** di pojok kanan atas
5. App sekarang ada di home screen Anda ✅

### Android
1. Buka URL app di Chrome
2. Tap **titik tiga** (menu) di pojok kanan atas
3. Tap **Install app** (atau "Add to home screen")
4. Tap **Install**
5. App sekarang ada di home screen Anda ✅

### PC / Laptop (Windows / Mac)
1. Buka URL di Chrome atau Edge
2. Bisa langsung pakai di browser
3. Atau: klik **titik tiga** → **Install app** untuk versi desktop ✅

### Orang lain
Cukup kirim URL-nya, mereka bisa langsung pakai tanpa install apapun.

---

## 🔑 Step 4 — Masukkan API Key

Saat pertama buka app, akan muncul layar untuk masukkan API Key:

1. Buka https://console.anthropic.com/account/api-keys
2. Klik **Create API Key**
3. Copy key yang dimulai dengan `sk-ant-...`
4. Paste di app, klik **Simpan & Mulai**

> ✅ Key disimpan di perangkat (localStorage), **tidak dikirim ke server lain**.
> Setiap device butuh input key masing-masing.

---

## ⚡ Fitur App

- 🎮 Roblox Mode — Lua/Luau specialist
- 🧠 Extended Thinking — Chain-of-thought reasoning
- ⚡ Streaming — Real-time response
- 🗺️ Memory System — Ingat konteks antar chat
- 🌙 Dark / Light mode
- 📤 Share & Export chat (.txt / .md)
- 🔊 Text-to-Speech
- 👑 Pilih model: Opus 4.5 / Sonnet 4 / Haiku 4.5

---

## 🔧 Troubleshooting

| Problem | Solusi |
|---|---|
| "Failed to fetch" | Coba refresh. Kalau masih, cek koneksi internet |
| "API Key tidak valid" | Pastikan key dimulai `sk-ant-` dan masih aktif |
| "Rate limit" | Tunggu 30 detik, coba lagi |
| App tidak muncul di home screen | Pastikan buka di Safari (iOS) atau Chrome (Android) |
