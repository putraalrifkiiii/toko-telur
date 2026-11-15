# Egg Store Manager

Aplikasi kasir toko telur untuk mengelola penjualan, produk, stok barang, dan laporan omzet.

## Teknologi

- React
- TypeScript
- TanStack Start
- Tailwind CSS
- Supabase (Database & Authentication)
- TanStack Query
- Bun

## Fitur

- Dashboard omzet penjualan
- Manajemen produk
- Manajemen stok barang
- Transaksi penjualan
- Riwayat transaksi
- Laporan penjualan
- Autentikasi pengguna

## Persyaratan

- [Bun](https://bun.sh/)
- Akun [Supabase](https://supabase.com/)

## Instalasi

Clone repository:

```bash
git clone https://github.com/putraalrifkiiii/egg-store-manager.git
cd egg-store-manager
```

Install dependencies:

```bash
bun install
```

## Konfigurasi Environment

Buat file `.env` di root project dan isi konfigurasi Supabase:

```env
SUPABASE_PROJECT_ID=
SUPABASE_URL=
SUPABASE_PUBLISHABLE_KEY=

VITE_SUPABASE_PROJECT_ID=
VITE_SUPABASE_URL=
VITE_SUPABASE_PUBLISHABLE_KEY=
```

Gunakan URL dan publishable key dari project Supabase milik sendiri.

Jangan mengunggah file `.env` atau secret key ke repository publik.

## Menjalankan Aplikasi

```bash
bun run dev
```

Aplikasi akan berjalan melalui server development Vite.

## Build

```bash
bun run build
```

## Repository

GitHub: https://github.com/putraalrifkiiii/egg-store-manager
