# 0xZenith Bot 🔥
#JANGAN HAPUS WMNYA WOK, HARGAIN YG BUAT Y ANJG

WhatsApp bot simple tapi ngegas. Dibuat pake otak owner 
bukan 'tolong buatkan bot dengan... lalu.. 🗿😹😹"

Versi: **BOT-V5.0.0.0**  
Prefix: `.`  
Owner: `egx`

---

## Fitur Singkat

- AI chat (GPT, Gemini, DeepSeek, Alya, Jokowi, dll)
- Download TikTok, YT, IG, Spotify, Pinterest
- Bikin stiker (biasa + premium)
- Maker: brat, bratvid, meme drake, dll
- TTS Indonesia
- Group tools: kick, add, close/open, mute
- Stalk IG & TikTok
- Random asupan / cecan
- Image to real, anime gen, dll

Tinggal ketik `.menu` biar liat list lengkapnya wok. jangan manja

---

## Cara Install (Termux / VPS)

1. Extract zip-nya dulu
```bash
cd 0xZenith-newbot
unzip 0xZenith.zip
cd "v5. 0.0"
```

2. Install dependency
```bash
pkg update && pkg install nodejs ffmpeg -y   # kalo Termux
# atau di VPS: apt install nodejs ffmpeg -y

npm install
```

3. Jalankan bot
```bash
node bot_new.js
```

4. explanation!!
*ganti no owner or bot
   -buka file bot_new.js
   -cari kata kunci OWNER (untuk ganti no owner)
   - cari kata kunci PAIRING(untuk ganti no yang mau di jadikan bot)
   - kata kunci CODE (untuk ganti kode pairing custom)
 *rules
   -JANGAN GUNAKAN NO WA UTAMA UNTUK DI JADIKAN BOT!!
   -jika bot eror tunggu saja, karna bisa jadi bot lagi maintenance (tahap pengembangan)
   -jika bot selalu eror. cek apakah ada update versi bot!
   - gunakan dengan bijak. selebihnya ada di anda😹
5. Scan QR or pakai pairing code  
Bot pake multi-device. Tinggal ikutin instruksi di terminal.

Session bakal kesimpen di folder `auth_info`. Jangan dihapus kalo mau tetap login.

---

## Notes

- Butuh ffmpeg buat convert stiker & video
- API key udah ke-hardcode, jadi tinggal jalanin aja
- Kalo mau ganti owner / prefix, edit di `bot_new.js` bagian `const C = {...}`
- Folder `img/` buat taro media menu (udah ada menu.mp4)

---

That’s it. Tinggal jalanin, gas.  
Kalau error, cek node & ffmpeg udah terinstall belum.

**0xZenith** — simple, clean, siap tempur.
