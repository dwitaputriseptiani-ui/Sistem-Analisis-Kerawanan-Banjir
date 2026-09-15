# Black-Box Testing

Pengujian sistem dilakukan menggunakan metode Black-Box Testing untuk memastikan setiap fitur berjalan sesuai dengan kebutuhan dan hasil yang diharapkan.

## A. Pengujian Halaman User

| ID | Fitur | Skenario Pengujian | Hasil yang Diharapkan | Status |
|---|---|---|---|---|
| TC-01 | Beranda | Membuka halaman utama | Halaman beranda tampil | Berhasil |
| TC-02 | Peta Kerawanan | Membuka menu peta | Peta tampil | Berhasil |
| TC-03 | Klik Kecamatan | Klik salah satu kecamatan | Informasi kecamatan tampil | Berhasil |
| TC-04 | Status Kerawanan | Klik kecamatan | Kategori rendah/sedang/tinggi tampil | Berhasil |
| TC-05 | Mitigasi | Klik kecamatan | Mitigasi tampil | Berhasil |
| TC-06 | Informasi | Membuka menu informasi | Informasi banjir tampil | Berhasil |
| TC-07 | Tentang | Membuka menu tentang | Informasi penelitian tampil | Berhasil |

## B. Pengujian Halaman Admin

| ID | Fitur | Skenario Pengujian | Hasil yang Diharapkan | Status |
|---|---|---|---|---|
| TC-08 | Login | Login dengan data benar | Masuk dashboard | Berhasil |
| TC-09 | Login | Login dengan data salah | Login ditolak | Berhasil |
| TC-10 | Perhitungan AHP | Menginput nilai AHP | Bobot dan CR dihitung | Berhasil |
| TC-11 | Upload Peta | Upload GeoJSON | Data tersimpan | Berhasil |
| TC-12 | Edit Peta | Mengubah data peta | Data diperbarui | Berhasil |
| TC-13 | Hapus Peta | Menghapus peta | Data terhapus | Berhasil |
| TC-14 | Kelola Mitigasi | Tambah/Edit/Hapus | Perubahan tersimpan | Berhasil |
| TC-15 | Kelola Informasi | Tambah/Edit/Hapus | Perubahan tersimpan | Berhasil |
