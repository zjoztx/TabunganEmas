<p align="center">
  <img src="icon-192.png" width="96" alt="Ikon Tabungan Emas Antam">
</p>

<h1 align="center">Tabungan Emas Antam</h1>

<p align="center">
  Catat tabungan emas Logam Mulia Antam, ketahui harga rata-rata beli per gram,<br>
  dan hitung di harga buyback berapa emas sebaiknya dijual.
</p>

<p align="center">
  <a href="https://zjoztx.github.io/TabunganEmas/"><b>Buka aplikasi</b></a>
</p>

---

## Fitur

- **Catat transaksi beli dan jual** per pecahan, dari 0,5 g sampai 1.000 g, lengkap dengan tanggal dan catatan.
- **Rata-rata harga beli per gram**, dihitung dari total yang benar-benar dibayar (termasuk pajak dan biaya).
- **Untung/rugi hari ini** jika semua emas dijual di harga buyback terkini, sudah dipotong PPh 22.
- **Tabel "Jual di harga berapa?"**: harga buyback per gram yang dibutuhkan untuk balik modal, untung 5%, 10%, 15%, 20%, 30%, 50%, atau target sendiri.
- **Simulasi jual sebagian**: lihat laba dan sisa emas sebelum benar-benar menjual.
- **Rincian per pecahan**: jumlah keping dan rata-rata harga tiap ukuran.
- **Pengaturan pajak** yang bisa diubah: PPh 22 buyback 1,5% (dengan NPWP) atau 3% (tanpa NPWP) untuk penjualan di atas Rp10 juta.
- **Tampilan terang dan gelap** mengikuti pengaturan perangkat.
- **Bisa dipasang di layar utama HP** seperti aplikasi biasa.

## Cara pakai

1. Buka aplikasi dan tekan **Hapus contoh & mulai** untuk membuang data contoh.
2. Isi **harga buyback per gram** dan **harga beli per gram** hari ini. Harga resmi bisa dicek di [logammulia.com](https://www.logammulia.com/id/sell/gold).
3. Catat setiap pembelian: tanggal, pecahan, jumlah keping, dan **total yang dibayar**.
4. Lihat ringkasan posisi, tabel target jual, dan simulasi jual.

### Pasang di layar utama HP

- **Android (Chrome):** buka aplikasi, ketuk menu ⋮, lalu pilih **Tambahkan ke layar utama** atau **Instal aplikasi**.
- **iPhone (Safari):** buka aplikasi, ketuk tombol **Bagikan**, lalu pilih **Tambah ke Layar Utama**.

## Data dan privasi

Semua data tersimpan **hanya di browser perangkat Anda** (localStorage). Tidak ada data yang dikirim ke server mana pun, termasuk ke repository ini.

Karena itu:

- Data di HP dan di laptop terpisah.
- Data bisa hilang jika riwayat browser atau data situs dihapus.
- Gunakan **Salin kode cadangan** secara berkala dan simpan kodenya di tempat aman. Untuk memindahkan data ke perangkat lain, tempel kode itu lalu tekan **Pulihkan dari kode**.

## Cara hitung

| Istilah | Rumus |
|---|---|
| Rata-rata beli / gram | Total modal ÷ total gram |
| Nilai buyback kotor | Total gram × harga buyback / gram |
| Diterima bersih | Nilai kotor − PPh 22 (jika nilai kotor di atas batas) |
| Harga balik modal / gram | Total modal ÷ (total gram × (1 − tarif PPh 22)) |
| Harga target / gram | Total modal × (1 + target%) ÷ (total gram × (1 − tarif PPh 22)) |

Saat ada penjualan, modal yang keluar dihitung memakai harga rata-rata saat itu (metode rata-rata bergerak).

> **Catatan:** Aplikasi ini alat bantu pencatatan dan perhitungan, bukan saran investasi. Tarif dan ketentuan pajak bisa berubah, jadi sesuaikan pengaturannya dengan aturan yang berlaku.

## Isi repository

| File | Fungsi |
|---|---|
| `index.html` | Seluruh aplikasi (tampilan, perhitungan, penyimpanan) |
| `manifest.webmanifest` | Pengaturan agar bisa dipasang di layar utama |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | Ikon aplikasi Android |
| `apple-touch-icon.png` | Ikon aplikasi iPhone |
| `favicon.png` | Ikon tab browser |

## Menjalankan sendiri

Tidak perlu instalasi atau server khusus. Unggah semua file ke GitHub Pages (atau hosting statis lain), atau cukup buka `index.html` di browser.
