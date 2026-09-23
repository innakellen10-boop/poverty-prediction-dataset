# Dataset Kemiskinan Kabupaten/Kota Indonesia 2024

Dataset pendukung artikel:

> A. M. B. Kellen, B. Surarso, dan Sutikno, "Seleksi Fitur dan Optimasi Parameter Premis
> ANFIS Berbasis RHGWO untuk Prediksi Persentase Penduduk Miskin Kabupaten/Kota di
> Indonesia," \\\*IJADIS\\\* (dalam proses revisi).

Repositori ini hanya berisi data, tanpa kode.

## Berkas

|Berkas|Isi|
|-|-|
|`dataset\\\_kemiskinan\\\_kabkota\\\_2024.csv`|Dataset (UTF-8, pemisah koma, titik desimal)|
|`dataset\\\_kemiskinan\\\_kabkota\\\_2024.xlsx`|Dataset yang sama dalam format Excel|

## Cakupan

* 508 kabupaten/kota di 37 provinsi (satu baris per kabupaten/kota).
* Provinsi DKI Jakarta tidak disertakan. Anggaran kota/kabupaten administrasinya
dikonsolidasikan ke keuangan pemerintah provinsi (UU No. 2 Tahun 2024), sehingga
tidak sebanding dengan daerah otonom lain.
* Target: **Persentase Penduduk Miskin (%)** tahun 2024.
* 27 fitur kandidat (kolom 3–29).
* Sumber: publikasi Badan Pusat Statistik (BPS) tingkat nasional dan provinsi, termasuk
tabel keuangan pemerintah kabupaten/kota (DJPK-Kemenkeu diolah BPS).

## Variabel

|No|Kolom|Kelompok|
|-|-|-|
|1|Provinsi|identitas|
|2|Kabupaten/Kota|identitas|
|3|Luas Wilayah (km2)|wilayah dan demografi|
|4|Jumlah Penduduk (ribu jiwa)|wilayah dan demografi|
|5|Indeks Pembangunan Literasi Masyarakat|pendidikan|
|6|Persentase Rumah Tangga yang Memiliki Akses Terhadap Sanitasi Layak|kesejahteraan|
|7|Persentase Rumah Tangga yang Memiliki Akses Terhadap Sumber Air Minum Layak|kesejahteraan|
|8|Realisasi Jumlah Kepala Keluarga Penerima Manfaat Bantuan Sosial|kesejahteraan|
|9|Jumlah Anggaran Bantuan Keluarga (rupiah)|kesejahteraan|
|10|Rata-rata Pengeluaran per Kapita Sebulan Makanan dan Bukan Makanan di Daerah Perkotaan dan Perdesaan (rupiah)|kesejahteraan|
|11|Tingkat Penyerapan Pendapatan (%)|keuangan daerah|
|12|Tingkat Penyerapan Belanja (%)|keuangan daerah|
|13|Rasio Efektivitas Pendapatan Asli Daerah (PAD) (%)|keuangan daerah|
|14|Rasio Efektivitas Penerimaan Pajak (%)|keuangan daerah|
|15|Rasio Belanja Terhadap Pendapatan (%)|keuangan daerah|
|16|Rasio Belanja Pendidikan (%)|keuangan daerah|
|17|Rasio Belanja Kesehatan (%)|keuangan daerah|
|18|Rasio Belanja Ekonomi (%)|keuangan daerah|
|19|Rasio Belanja Perumahan (%)|keuangan daerah|
|20|Umur Harapan Hidup (tahun)|kesehatan|
|21|Rata-rata Lama Sekolah (tahun)|pendidikan|
|22|Indeks Pembangunan Manusia (%)|kesejahteraan|
|23|Indeks Pembangunan Gender (%)|kesejahteraan|
|24|Tingkat Pengangguran Terbuka (%)|ketenagakerjaan|
|25|Jumlah Guru SMA/SMK|pendidikan|
|26|Jumlah Siswa SMA/SMK|pendidikan|
|27|Produk Domestik Regional Bruto (PDRB) Atas Dasar Harga Berlaku|ekonomi|
|28|Jumlah Desa yang memiliki Sarana Kesehatan|kesehatan|
|29|Jumlah Tenaga Kesehatan|kesehatan|
|30|Persentase Penduduk Miskin (%)|**target**|

Nama kolom mengikuti nama indikator pada publikasi BPS.



## Sel kosong

Ada 11 sel kosong di 3 baris karena nilainya tidak tersedia.

|Kabupaten/Kota|Kolom kosong|
|-|-|
|Grobogan (Jawa Tengah)|Rasio Belanja Perumahan|
|Barito Utara (Kalimantan Tengah)|9 rasio keuangan (kolom 11–19; BPS mencantumkan "–" atau 0,00)|
|Puncak (Papua Tengah)|Sanitasi Layak|

Pada artikel, sel kosong diisi dengan median data latih.

## 

## Lisensi dan sitasi

Data berasal dari publikasi resmi BPS. Bila menggunakan dataset ini, mohon cantumkan
BPS sebagai sumber data dan sitasi artikel di atas.

