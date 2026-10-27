# NPrD Generator Hub — GitHub Pages

Versi ini memuat perbaikan RM Cost Simulation: hanya bagian terakhir otomatis mengisi sisa menuju 100%.

## Cara upload
1. Ekstrak ZIP ini di komputer.
2. Buat atau buka repository GitHub.
3. Pilih Add file > Upload files, lalu unggah isi paket ke direktori utama repository. Jangan unggah ZIP-nya. Pastikan index.html berada langsung di direktori utama, bukan di subfolder.
4. Commit changes.
5. Buka Settings > Pages.
6. Pada Source, pilih Deploy from a branch.
7. Pilih branch main (atau branch tempat file diunggah), folder / (root), lalu Save.
8. Setelah deployment selesai, buka alamat situs yang ditampilkan pada Settings > Pages.

Contoh alamat: https://USERNAME.github.io/NAMA-REPOSITORY/

## Isi paket
- index.html: aplikasi lengkap, siap disajikan tanpa build atau instalasi dependency.
- .nojekyll: menyajikan file statis tanpa pemrosesan Jekyll.
- README.md: panduan ini.

## Data dan perpindahan dari file lokal
Data kerja disimpan di browser/perangkat, bukan di repository GitHub. Data tidak tersinkron otomatis antarperangkat. Untuk memindahkan data dari HTML lokal ke situs, buka aplikasi lama dan pilih Cadangkan semua, kemudian buka situs GitHub Pages pada browser dan pilih Pulihkan semua menggunakan file cadangan tersebut. Pemulihan mengganti data yang sudah ada di tujuan. Simpan file cadangan secara terpisah.

Sumber resmi: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site


## v174 — DLK Generator
Menu DLK berisi Report Trial, Realisasi Dinas, dan Rancob. Rancob memakai data divisi yang sama dengan versi sebelumnya dan dapat mengambil sumber RM Cost yang sudah ada.
