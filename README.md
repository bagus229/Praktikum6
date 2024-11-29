# Praktikum 6
## Daftar nilai mahasiswa

### Langkah 1
Memulai program dengan membuat variabel data_mahasiswa, sebuah list kosong yang akan digunakan untuk menyimpan data mahasiswa dalam bentuk dictionary. Setiap dictionary berisi dua elemen yaitu nama dan nilai:
![Gambar 1](screenshot/woy1.png)

### Langkah 2
tambah(), program meminta input data mahasiswa jika pengguna memilih menu tambah(). setelah itu, data diprint ditampilkan "data telah berhasil ditambahkan" dan disimpan dalam dictiionary:
![Gambar 1](screenshot/woy2.png)

### Langkah 3
tampilkan(), program akan menampilkan data mahasiswa. jika tidak ada/else data maka akan ditampilkan "belum ada data mahasiswa". jika ada/if maka akan menampilkan no urut, nama, dan nilai. penggunaan enumerate sebagai pemberi nomor otomatis. lalu print=*34 (sebagai pembatas):
![Gambar 1](screenshot/woy3.png)

### Langkah 4
hapus(nama), pengguna meminta program untuk menghapus data mahasiswa berdasarkan nama. program meminta input data mahasiswa yang akan dihapus. elemen global (comprehension) digunakan untuk menyaring data. lalu print=*65:
![Gambar 1](screenshot/woy4.png)

### Langkah 5
ubah(nama), pemgguna meminta program untuk mengubah data yang disimpan. program meminta pengguna untuk menginput data mahasiswa yang akan diubah berdasarkan nama. float sebagai mengubah nilai lama ke nilai baru. akan ditampilkan 'data berhasil diubah". retrun print=*55 menampilkan "mahasiswa dengan nama (nama) tidak berhasi di temukan":
![Gambar 1](screenshot/woy5.png)

### Langkah 6
While true untuk perulangan untuk menu(Tambah Data, Tampilkan Data, Hapus Data, Ubah Data, Keluar) yang ditampilkan sampai pengguna memilih keluar. lalu print=*20, pilih menu:
[Gambar 1](screenshot/woy6.png)

### Langkah 7
if, elif, else. kode ini untuk menangani berbagai aksi berdasarkan input pengguna (pilihan) yang diambil dari menu utama. setelah itu Input dibandingkan dengan nilai "1(tambah())", "2(tampilkan())", "3(hapus(nama))", "4(ubah(nama))", dan "5(break)". Jika tidak ada yang cocok, akan masuk ke blok else. jika pengguna memilih "5" akan ditampilkan "program selesai. terima kasih!". kemudian kembali ke menu. lalu print:
[Gambar 1](screenshot/woy7.png)

