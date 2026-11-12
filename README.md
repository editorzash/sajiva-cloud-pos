# Sajiva Cloud POS

**Kasir ringkas, kendali bisnis menyeluruh.** Sajiva adalah demo aplikasi Point of Sale dan backoffice untuk bisnis kafe dan restoran.

## Fitur

- **Dashboard:** KPI penjualan, filter periode, grafik penjualan dan metode pembayaran, menu terlaris, ekspor transaksi, dan transaksi terbaru.
- **Kasir / POS:** katalog 12 menu, filter kategori dan pencarian, keranjang interaktif, tipe pesanan, pajak PB1 10%, simpan pesanan sementara, dan simulasi pembayaran.
- **Riwayat pesanan:** transaksi selesai maupun batal, filter tanggal, serta aksi cetak struk.
- **Pelanggan:** daftar member, poin, kunjungan, nilai belanja, dan tingkat loyalitas.
- **Manajemen produk:** daftar produk, harga modal/jual, SKU, stok, kategori, modifier, inventori, dan restock.
- **Laporan & analisis:** omset, HPP, laba kotor, dan rekonsiliasi kasir/shift.
- **Pajak & diskon:** tarif PB1 dan service charge serta voucher promo.
- **Pengaturan:** cabang, printer kasir/dapur, profil bisnis, preferensi, dan catatan struk.
- **Antarmuka responsif:** sidebar mobile, notifikasi toast, serta tata letak desktop dan ponsel.

Semua data bersifat dummy dan tersimpan di dalam aplikasi. Tidak diperlukan server maupun proses build. Chart.js, Font Awesome, dan Google Fonts dimuat melalui CDN; komponen utama tetap dapat dibuka langsung dari berkas `index.html`.

## Deploy ke GitHub Pages

1. Buat repository GitHub baru, lalu buka terminal di direktori proyek.
2. Jalankan perintah berikut dan ganti `USERNAME` serta `NAMA-REPO` sesuai akun dan repository:

   ```bash
   git init
   git add .
   git commit -m "feat: initial commit"
   git remote add origin https://github.com/USERNAME/NAMA-REPO.git
   git branch -M main
   git push -u origin main
   ```

3. Di repository GitHub, buka **Settings → Pages**.
4. Pilih **Source: Deploy from a branch**, branch **main**, folder **/(root)**, lalu klik **Save**.
5. Setelah deploy selesai, situs tersedia di `https://USERNAME.github.io/NAMA-REPO/`.

## Teknologi

- HTML5, CSS3, dan JavaScript Vanilla (ES6+)
- Chart.js melalui jsDelivr CDN
- Font Awesome 6 melalui cdnjs
- Plus Jakarta Sans melalui Google Fonts
- GitHub Pages untuk hosting statis
