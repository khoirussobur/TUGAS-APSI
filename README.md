# TUGAS-APSI

## Nama

Khoirus Sobur

## NIM

20240803079

## Mata Kuliah

Analisis dan Perancangan Sistem Informasi

## Deskripsi

JUDUL: SISTEM INFORMASI PENJUALAN SAYUR "TOKO SEGAR HIJAU"

1. Ringkasan
   Toko Segar Hijau merupakan usaha kecil yang menjual sayur secara langsung dipasar tradisional dan melalui pesanan Whatsapp. Untuk saat ini proses pencatatan stok dan pesanan dilakukan secara manual dan menggunakan kertas, sehingga terjadi selisih stok, keterlambatan konfirmasi, dan kesulitan dalam merekapitulasi penjualan.

Proyek ini bertujuan membangun sistem informasi penjualan berbasis web yang memungkinkan pelanggan melihat stok secara real‑time, melakukan pemesanan, dan mengunggah bukti pembayaran. Admin dapat mengelola produk, memverifikasi pembayaran, dan memperbarui status pesanan. Pemilik memperoleh akses dashboard untuk memantau penjualan.

Dengan sistem ini, diharapkan efisiensi operasional meningkat, kesalahan pencatatan berkurang, dan kepuasan pelanggan bertambah.

2. Tujuan Proyek

- Mempercepat respons pemesanan – dari rata‑rata 15 menit (manual) menjadi maksimal 2 menit setelah pembayaran terverifikasi.
- Menghilangkan selisih stok – stok diperbarui secara otomatis saat pesanan dikemas. -Menyediakan katalog digital – pelanggan dapat melihat ketersediaan sayur sebelum memesan.
  -Memudahkan rekonsiliasi – seluruh transaksi tercatat digital dan dapat diakses oleh pemilik kapan saja.
  -Meningkatkan omzet – dengan kemudahan pemesanan, diharapkan frekuensi pembelian meningkat 20% dalam 6 bulan pertama.

3. Pernyataan Kebutuhan
   Berdasarkan wawancara dengan pemilik dan admin toko, permasalahan utama yang dihadapi adalah:

- Pencatatan stok tidak akurat karena perubahan stok hanya dilakukan di akhir hari atau saat ingat, sehingga sering terjadi pesanan tidak dapat dipenuhi.
- Proses pemesanan lambat – pelanggan harus menunggu admin mengecek stok fisik dan membalas manual melalui WhatsApp.
- Tidak ada riwayat transaksi digital – data pesanan tersimpan di binder, rawan hilang dan sulit dianalisis.
- Keterbatasan pemantauan – pemilik tidak dapat memantau penjualan secara langsung karena tidak berada di toko setiap saat.
- Kesulitan mengelola pembayaran – verifikasi transfer manual sering tertukar, terutama saat banyak pesanan bersamaan.

Oleh karena itu, dibutuhkan sebuah sistem yang mampu:
a. Menampilkan stok sayur yang selalu terkini.
b. Menerima pesanan secara mandiri oleh pelanggan melalui katalog online.
c. Mengelola status pesanan (Menunggu Pembayaran → Dikemas → Siap Diambil → Selesai).
d. Mencatat bukti pembayaran dan memudahkan verifikasi admin.
e. Menyediakan laporan penjualan ringkas untuk pemilik

4. Ruang Lingkup
   a. Lingkup In Scope

Modul Katalog & Stok

- Admin dapat menambah, mengubah, menghapus, atau menonaktifkan produk sayur.
- Sistem menampilkan stok secara real‑time kepada pelanggan.

Modul Pemesanan

- Keranjang belanja, checkout, pemilihan metode pembayaran (transfer bank/saldo digital).
- Upload bukti pembayaran oleh pelanggan.

Modul Verifikasi & Status

- Admin memverifikasi bukti bayar dan mengubah status pesanan.
- Pengurangan stok otomatis saat status “Dikemas”.
- Pembatalan otomatis pesanan yang tidak dibayar dalam 2 jam.

Modul Notifikasi

- Notifikasi WhatsApp/email kepada pelanggan setiap perubahan status.

Modul Dashboard Pemilik

- Ringkasan penjualan harian, stok kritis, dan daftar pesanan aktif.

Manajemen Pengguna

- Login untuk admin dan pemilik (dua faktor untuk pemilik).

b. Diluar Lingkup Out Of Scope

- Integrasi dengan rekening bank (verifikasi pembayaran tetap manual oleh admin).
- Manajemen pengadaan sayur dari petani.
- Modul pengiriman eksternal.
- Sistem akuntansi penuh.
- Aplikasi mobile native (hanya web responsif).

5. Pernyataan Fungsional
   F-01 Melihat Katalog
   F-02 Mengelola Keranjang
   F-03 Checkout
   F-04 Upload Bukti Bayar
   F-05 Verifikasi Pembayaran
   F-06 Manajemen Status Pesanan
   F-07 Pembatalan Otomatis
   F-08 Kelola Produk
   F-09 Dashboard Pemilik
   F-10 Notifikasi

6. Laporan Keuangan
   Kertas, buku, alat tulis: Rp 100.000
   Waktu admin: Rp 600.000/bulan
   Kehilangan penjualan: Rp 750.000/bulan

Total kerugian/inefisiensi per bulan ≈ Rp 1.450.000

Proyeksi omzet setelah sistem berjalan:
Omzet meningkat menjadi Rp 18.000.000/bulan.
Keuntungan tambahan kotor Rp 900.000/bulan.

7. Kebutuhan Personil
   Tim Proyek Pengembangan:

- Project Manager
- System Analyst / Business Analyst
- Web Developer (Full‑stack)
- UI/UX Designer
- Tester (QA)

Personil Operasional:

- Admin Toko (Sdri. Rina)
- Pemilik (Bpk. Ahmad)

8. Jadwal dan Batas Waktu
   Inisiasi & Analisis : Minggu 1–2
   Desain : Minggu 3–4
   Pengembangan : Minggu 5–8
   Pengujian : Minggu 9–10
   Pelatihan & Deployment : Minggu 11–12

Batas waktu kritis: Sistem harus sudah dapat digunakan sebelum Ramadhan 2027.

9. Asumsi

- Pelanggan memiliki ponsel pintar dan akses internet.
- Admin mampu mengoperasikan sistem setelah pelatihan.
- Koneksi internet stabil.
- Biaya pengembangan disetujui.
- Integrasi WhatsApp Business API dapat dilakukan.
- Pembayaran tetap dilakukan manual.

10. Biaya dan Manfaat
    Total Investasi Awal = Rp 35.900.000

Total Manfaat Bulanan = Rp 2.350.000

Analisis ROI:
Investasi total tahun pertama = Rp 35.900.000
Manfaat per tahun = Rp 28.200.000
Net Benefit tahun pertama = - Rp 7.700.000
Surplus tahun kedua dan seterusnya = Rp 18.300.000 per tahun
Payback Period ≈ 1,4 tahun

11. Kesimpulan
    Proyek layak secara finansial karena menghasilkan penghematan dan peningkatan pendapatan yang melebihi biaya operasional setelah tahun pertama.
