# EastJava Tourist Service (Demo)

Ini adalah versi demo dari web layanan wisatawan (Next.js) dengan dukungan PWA dasar.

Fitur yang ditambahkan pada sesi ini:
- Halaman `Pelayanan Wisatawan` di `/pelayanan`
- Endpoint API contoh `GET /api/services` dan `POST /api/services` (simulasi booking)
- PWA manifest (`/manifest.json`) dan service worker (`/sw.js`) untuk instalasi PWA
- Komponen `PwaRegister` yang mendaftarkan service worker pada load

Cara menjalankan lokal (Windows PowerShell):

```powershell
# install deps
pnpm install

# development
pnpm dev
```

Jika tidak menggunakan pnpm, gunakan `npm install` dan `npm run dev`.

Coba:
- Buka http://localhost:3000/pelayanan untuk melihat halaman layanan
- Panggil GET http://localhost:3000/api/services untuk daftar layanan
- POST ke http://localhost:3000/api/services dengan JSON untuk simulasi booking

Catatan: Ini demo minimal. Untuk produksi tambahkan validasi, autentikasi, dan penyimpanan DB.
