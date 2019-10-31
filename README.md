Quality Assurance Checklist Problem Solving
============================
Berikut checklist problem solving mengenai Quality Assurance yang terjadi per kasus dengan tujuan sebagai referensi Quality Assurance agar meminimalisir pengulangan permasalahan yang terjadi.


| No | Tema  | Masalah  | Penyebab  | Solusi  |
| :--------:  | :--------| :-------- | :--------   | :-------- |
| 1 | Pengecekan skenario QA | Terjadi fail dalam melakukan pengujian aliran data antar role yang berbeda | <ul><li>Pengujian dilakukan masih lingkup perfungsi</li><li>Tidak dilakukan pengecekan pada lingkup role yang berbeda</li></ul> |Pengujian dilakukan mengikuti aliran data dan aliran skenario antar role  |
| 2 | Uji coba pada data yang memiliki relasi antar data| Data A memiliki relasi dengan data X, Ketika data A dihapus berpengaruh pada data X gagal diassign ke data B http://prntscr.com/o9ubuv |Uji coba dilakukan belum menyeluruh antar semua data yang memiliki relasi|Dilakukan pengecekan dan uji coba pada semua form yang memiliki relasi berhasil atau tidak ketika dilakukan assign di data lain |
| 3 | URL tidak SEO friendly | ID URL terlalu panjang pada URL produk dan kategori | Tidak diperhatikan dalam penulisan URL secara detail | <ul><li>Semua halaman list terutama list produk image harus dapat di click dan URL yang digunakan harus dengan ID yang pendek</li><li>URL harus SEO friendly dan human readable</li>|
| 4 | Penanganan image pada list produk|Pada halaman list produk image tidak clickable http://prntscr.com/oabnjo| Tidak ditambahkan fungsi clickable pada image | Semua halaman terutama list produk, image dan judul harus clickable |
| 5 | Batasan penulisan versi aplikasi pada UAT | Ada permintaan pengubahan versi OS saat aplikasi sudah di deploye | Tidak ada batasan versi environment aplikasi di dokumen UAT | <ul><li>Menuliskan batasan pengujian versi environment sebuah aplikasi</li><li>Menuliskan support minimum dan maksimal versi android</li><li>Menuliskan support minimum dan maksimal versi IOS</li><li>Menuliskan support minimum dan maksimal versi browser</li><li>Menuliskan support minimum dan maksimal versi browser</li><li>Ketika dilakukan deployment, mendapat laporan bug dari pihak CS atau Client maka lakukan pengecekan mengenai bug tersebut dan cek dokumen yang sudah dibuat</li><li>Apabila batasan versi environment aplikasi sudah didefine di Proses Bisnis dan UAT tetapi masih terjadi bug maka hotfix wajib dilakukan</li><li>Apabila batasan versi environment aplikasi belum didefine di Proses Bisnis dan UAT, maka cek kembali untuk mempertimbangkan prosentase impact yang akan terjadi pada user dan device (GA atau firebase), apabila impact yang akan terjadi tinggi maka diskusikan terlebih dahulu untuk pricing hotfix priority dan apabila yang terkena impact tindak tinggi maka masuk ke sprint berikutnya</li> |
| 6 | Mengatasi crash pada radio button jika diklik berulang-ulang | Aplikasi crash saat user klik radio button yang telah dipilih beberapa kali, berulang-ulang | <ul><li> User klik pada produk lalu klik tombol Beli pada halaman Cart, selanjutnya User memilih metode Pickup in Store dan pilih Cabang yang tersedia lalu klik tombol Bayar, pada pilihan Pay Now via Transfer dan Generate QR Code (disabled karena fitur belum tersedia) User klik beberapa kali dan berulang-ulang </li><li>pada pilihan Pay Now via Transfer (pilihan default) dan aplikasi crash </li> | Jika ada 2 radio button, yang satu aktif dan satunya tidak aktif, maka di-disable select untuk user
  
