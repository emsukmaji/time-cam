# TimeCam

Web app kamera dengan watermark jam, tanggal, lokasi, dan catatan (mirip Timemark). Bisa dipasang di iPhone lewat "Add to Home Screen".

## Deploy ke GitHub Pages

1. Buat repo baru di GitHub, misalnya `timecam` (Public).
2. Upload semua isi folder ini (`index.html`, `manifest.json`, `sw.js`, folder `icons/`) ke root repo.
3. Buka **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
4. Tunggu 1–2 menit. Alamatnya: `https://<username>.github.io/timecam/`

## Pasang di iPhone

1. Buka link di **Safari** (bukan Chrome).
2. Tap tombol Share → **Add to Home Screen** → Add.
3. Buka dari ikon di home screen, izinkan **Kamera** dan **Lokasi**.

## Fitur

- Live watermark: jam besar, garis emas, tanggal + hari, alamat dari GPS, catatan
- Alamat otomatis (OpenStreetMap), bisa diganti manual lewat tombol edit
- Ganti kamera depan/belakang, zoom digital 1x / 1.5x / 2x
- Mode Foto & Video, watermark ikut berputar saat HP landscape
- Galeri dalam app: semua hasil tersimpan sampai dihapus, bisa simpan banyak sekaligus ke Photos lewat share sheet → **Save Images**
- Catatan foto bisa diedit setelah foto diambil

## Batasan di iPhone (web app)

- Flash/torch tidak didukung Safari untuk web app.
- Zoom 0.5 (ultra-wide) tidak bisa dipilih dari web, jadi diganti 1.5x digital.
- iOS kadang menanyakan izin kamera lagi setiap app dibuka ulang.
- Resolusi foto lebih rendah dari kamera bawaan (biasanya maks 1080p–4K tergantung iPhone).
