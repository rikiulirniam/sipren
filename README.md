# SiPren

SiPren adalah aplikasi sistem presensi siswa yang terintegrasi dengan teknologi RFID.

## Struktur proyek

- `sipren-api` - Backend Express dengan PostgreSQL.
- `sipren-client` - Frontend React dengan Vite.

## Menjalankan proyek

### Backend

```bash
cd sipren-api
npm install
npm start
```

Backend berjalan di `http://localhost:8000` secara default. Konfigurasi database dan langkah seeder tersedia di [sipren-api/README.md](sipren-api/README.md).

### Frontend

Buka terminal baru, lalu jalankan:

```bash
cd sipren-client
npm install
npm run dev
```

Vite akan menampilkan alamat lokal frontend di terminal.

## Perintah frontend

```bash
npm run dev      # Menjalankan development server
npm run build    # Membuat build production
npm run lint     # Menjalankan ESLint
npm run preview  # Meninjau build production
```

## Teknologi

- React dan Vite
- Node.js dan Express
- PostgreSQL dan Sequelize/pg
- Tailwind CSS
