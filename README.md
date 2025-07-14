# tugas-algoritma-pertemuan14
program toko skincare garnier 
1.  1. Daftar Produk

Di awal, program punya data produk-produk Garnier.
Data ini disimpan dalam bentuk “dictionary” (mirip tabel berisi daftar produk dan harga).
Contohnya:
Kode 1 → Garnier Micellar Water, harganya Rp35.000
Kode 2 → Garnier Serum Vitamin C, harganya Rp75.000
Dan seterusnya.
Ini supaya program tahu produk mana saja yang tersedia dan harganya.

2. Keranjang Belanja

Saat kita memilih produk, program akan mencatatnya di “keranjang belanja”.
Keranjang ini juga disimpan sebagai data (list of dictionary).
Misalnya, kalau kita beli:
2 botol Micellar Water
1 tube Facial Foam
Program akan menyimpan data ini di keranjang untuk dihitung nanti.

3.  Fungsi-fungsi Program

Program punya beberapa bagian penting (disebut “fungsi”):

✅ Fungsi tampilkan_produk()

Menampilkan daftar semua produk Garnier beserta harganya. Agar kita tahu produk apa saja yang bisa dibeli dan berapa harganya.

Contoh output:

=== Daftar Produk Skincare Garnier ===
1. Garnier Micellar Water - Rp35,000
2. Garnier Serum Vitamin C - Rp75,000
...

✅ Fungsi tambah_ke_keranjang()

Bagian ini bertanya ke kita:

Mau beli produk yang mana? (masukkan kode produk)

Mau beli berapa banyak?


Program akan terus bertanya sampai kita ketik 0 untuk selesai.

Program juga memeriksa:

Apakah kode produk yang dimasukkan valid?

Apakah inputnya angka? (supaya tidak error)

✅ Fungsi tampilkan_keranjang()

Setelah selesai memilih produk, fungsi ini menampilkan:

Isi keranjang belanja (produk apa saja dan berapa jumlahnya)

Subtotal untuk tiap produk

Total keseluruhan belanja


Contoh output:

=== Keranjang Belanja ===
Garnier Serum Vitamin C x2 = Rp150,000
Total Belanja: Rp150,000


4.  Main Program (Bagian yang dijalankan)

Bagian terakhir dari program ini menjalankan ketiga fungsi tadi secara berurutan:
1. Menampilkan daftar produk
2. Meminta kita memilih produk
3. Menampilkan ringkasan belanja dan total

Lalu program ditutup dengan ucapan:

Terima kasih telah berbelanja di Toko Skincare Garnier kami!

✅ Singkatnya: Program ini adalah seperti kasir virtual sederhana.
Kita:

Lihat daftar produk

Pilih produk + jumlah

Dapatkan ringkasan dan total belanja

Programnya membantu kita menghitung otomatis, supaya belanja lebih praktis.



