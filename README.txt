MY LIFE FINANCE — PWA WEBSITE PACKAGE

Isi folder:
- index.html: aplikasi My Life Finance
- manifest.json: metadata untuk pemasangan sebagai aplikasi
- service-worker.js: cache dasar untuk membuka app saat offline setelah pernah dibuka online
- icons/: ikon aplikasi

CARA PUBLISH GRATIS DENGAN GITHUB PAGES
1. Login/daftar di https://github.com
2. Buat repository baru bernama my-life-finance
3. Pilih Public (GitHub Pages gratis biasanya memerlukan repo public untuk akun Free).
4. Upload SEMUA ISI folder ini ke root repository (index.html harus di root, bukan di subfolder).
5. Buka Settings > Pages.
6. Di Build and deployment, pilih Deploy from a branch; branch main dan folder /(root), lalu Save.
7. Tunggu proses publish selesai. URL biasanya https://USERNAME.github.io/my-life-finance/.
8. Buka URL tersebut melalui Chrome di Android, lalu menu titik tiga > Install app atau Add to Home screen.

CATATAN PRIVASI:
Aplikasi ini menyimpan catatan di localStorage browser pada perangkat yang digunakan. Data tidak otomatis tersinkron ke HP lain dan bisa hilang jika data situs/browser dihapus. Gunakan ekspor/backup dari aplikasi secara berkala. Jangan unggah ekspor JSON ke repository publik karena berisi data keuangan pribadi.

HTTPS:
GitHub Pages menyediakan HTTPS untuk alamat publiknya. Website belum dipublikasikan otomatis oleh paket ini; kamu perlu mengunggah file dan mengaktifkan Pages pada akun GitHub milikmu.
