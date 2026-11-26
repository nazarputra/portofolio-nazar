# Portofolio & CV ATS — Nazar Putra Hawali, S.Kom.

Website portofolio responsif dengan dukungan **Mode Dark & Light** (tema utama Hitam, Font Kuning, List Biru) serta **CV ATS PDF** siap unduh.

## Struktur Proyek
- `index.html` — Halaman utama portofolio
- `cv-ats.html` — Halaman pratinjau & cetak CV ATS
- `css/style.css` — Styling responsif desktop, tablet, dan mobile
- `js/script.js` — Interaksi tema, filter karya, modal, dan salin kontak
- `assets/images/` — Foto profil dan wisuda
- `assets/docs/CV-ATS-Nazar-Putra-Hawali.pdf` — Dokumen CV ATS 1 halaman A4
- `vercel.json` — Konfigurasi deployment statis Vercel

## Cara Deploy ke GitHub & Vercel (`*.vercel.app`)

### 1. Upload ke GitHub
Jika Git sudah terpasang di komputer Anda, jalankan perintah berikut di folder `portofolio`:
```bash
git init
git add .
git commit -m "Initial commit: Portofolio & CV ATS Nazar Putra Hawali"
git branch -M main
git remote add origin https://github.com/USERNAME_ANDA/portofolio-nazar.git
git push -u origin main
```
*(Alternatif tanpa Git CLI: buat repository baru di GitHub, lalu klik **uploading an existing file** dan seret seluruh isi folder `portofolio` beserta folder `assets`, `css`, dan `js`.)*

### 2. Deploy Otomatis ke Vercel
1. Buka [vercel.com](https://vercel.com) dan login menggunakan akun **GitHub** Anda.
2. Klik **Add New... > Project**.
3. Pilih repository `portofolio-nazar` lalu klik **Import**.
4. Pastikan pengaturan build:
   - **Framework Preset**: `Other`
   - **Root Directory**: `./`
   - **Build Command**: *(kosongkan)*
   - **Output Directory**: `.`
5. Klik **Deploy**. Dalam beberapa detik, portofolio Anda akan aktif di URL `https://<nama-proyek>.vercel.app`.
