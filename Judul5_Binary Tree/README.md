JUDUL >> ANTRIAN KOPI
DESKRIPSI >> Program tersebut merupakan implementasi struktur data Binary Search Tree (BST) untuk mengelola nomor antrian pesanan kopi. Program memungkinkan pengguna menambahkan nomor antrian, melihat seluruh antrian, melihat nomor antrian pertama, dan melihat nomor antrian terakhir.

SOURCE CODE >>
<img width="951" height="686" alt="Screenshot 2026-05-21 004455" src="https://github.com/user-attachments/assets/68db826f-c2e9-4d63-aa09-789cdeae91af" />
<img width="977" height="613" alt="Screenshot 2026-05-21 004512" src="https://github.com/user-attachments/assets/062dbe68-7a3a-4344-af46-703a2357abed" />
<img width="808" height="704" alt="Screenshot 2026-05-21 004526" src="https://github.com/user-attachments/assets/ce5dae48-8033-413e-923a-0406b6b36afd" />
<img width="855" height="742" alt="Screenshot 2026-05-21 004539" src="https://github.com/user-attachments/assets/3e3b4181-e901-4847-aa41-4f1476b3e1c3" />
<img width="776" height="694" alt="Screenshot 2026-05-21 004605" src="https://github.com/user-attachments/assets/7f157ace-d8f3-407b-b1c0-12c04afa0011" />

Fungsi __init__() pada class Node digunakan untuk membuat node baru pada Binary Search Tree (BST). Fungsi ini menyimpan data nomor antrian ke dalam atribut key serta menyiapkan pointer left dan right untuk menghubungkan node ke anak kiri dan anak kanan.

Fungsi __init__() pada class BSTAntrianKopi digunakan untuk membuat BST dalam keadaan kosong. Pada fungsi ini, root diatur menjadi None karena pohon belum memiliki data nomor antrian.

Fungsi insert_node() digunakan untuk menambahkan nomor antrian ke dalam BST secara rekursif. Fungsi ini bekerja dengan membandingkan nilai yang dimasukkan dengan nilai root. Jika nilai lebih kecil, data ditempatkan di subtree kiri, sedangkan jika lebih besar ditempatkan di subtree kanan. Dengan cara ini, struktur BST tetap terurut.

Fungsi insert() digunakan sebagai fungsi pemanggil untuk insert_node(). Fungsi ini mempermudah proses penambahan nomor antrian karena pengguna hanya perlu memasukkan nilai tanpa mengatur root secara langsung.

Fungsi level_order() digunakan untuk menampilkan seluruh nomor antrian pesanan kopi menggunakan metode traversal level-order. Data ditampilkan dari level paling atas ke bawah dan dari kiri ke kanan menggunakan bantuan queue. Fungsi ini berguna untuk melihat seluruh isi antrian dalam BST.

Fungsi find_min() digunakan untuk mencari nomor antrian paling kecil atau antrian pertama pada BST. Fungsi ini bekerja dengan menelusuri node paling kiri karena pada BST nilai terkecil selalu berada di sisi kiri pohon.

Fungsi find_max() digunakan untuk mencari nomor antrian paling besar atau antrian terakhir pada BST. Fungsi ini menelusuri node paling kanan karena pada BST nilai terbesar selalu berada di sisi kanan pohon.

Fungsi main() merupakan fungsi utama yang menjalankan seluruh program. Fungsi ini menampilkan menu pilihan kepada pengguna, menerima input, serta memanggil fungsi-fungsi lain seperti menambah antrian, melihat antrian, mencari nomor antrian pertama, dan mencari nomor antrian terakhir. Program akan terus berjalan sampai pengguna memilih menu keluar.

OUTPUT >>
<img width="784" height="755" alt="Screenshot 2026-05-21 011115" src="https://github.com/user-attachments/assets/0095fec2-219e-4848-8395-a4a9be7da8cb" />
<img width="742" height="733" alt="Screenshot 2026-05-21 011130" src="https://github.com/user-attachments/assets/af2d8c2d-b5c4-4fbb-ac85-6857d20a1311" />
<img width="639" height="459" alt="Screenshot 2026-05-21 011141" src="https://github.com/user-attachments/assets/d0565113-a200-4832-8b43-f5acc50d4455" />

Pada awal program, tampil menu utama:
1. Tambah nomor antrian
2. Lihat antrian
3. Lihat nomor antrian pertama
4. Lihat nomor antrian terakhir
5. Keluar
Menu ini digunakan untuk memilih operasi yang akan dilakukan pada antrian pesanan kopi.

Saat pengguna memilih menu 1, program meminta input nomor antrian. User akan menambahkan nomor antrian 20 lalu dimasukkan ke dalam Binary Search Tree dan menjadi root karena data pertama yang dimasukkan.
Kemudian pengguna kembali memilih menu 1 dan memasukkan nomor 19. Karena 19 lebih kecil dari 20, maka pada BST data 19 ditempatkan di sebelah kiri node 20.
Selanjutnya pengguna memasukkan nomor 22. Karena 22 lebih besar dari 20, maka data ditempatkan di sebelah kanan node 20.
Kemudian pengguna memasukkan nomor 26. Karena 26 lebih besar dari 20 dan juga lebih besar dari 22, maka data ditempatkan di sebelah kanan node 22.

Saat pengguna memilih menu 2 yaitu lihat antrian:
Nomor antrian pesanan kopi: 20 19 22 26

Saat pengguna memilih menu 3:
Nomor antrian pertama: 19
Program menjalankan fungsi find_min().
Pada BST, nilai terkecil selalu berada di node paling kiri. Karena node paling kiri adalah 19, maka itulah nomor antrian pertama.

Saat pengguna memilih menu 4:
Nomor antrian terakhir: 26
Program menjalankan fungsi find_max().
Pada BST, nilai terbesar selalu berada di node paling kanan. Karena node paling kanan adalah 26, maka itulah nomor antrian terakhir.

Saat pengguna memilih menu 5:
Program selesai. Program berhenti karena pengguna memilih keluar dari sistem.

Kesimpulannya, program berhasil menggunakan Binary Search Tree untuk menyimpan dan mengelola nomor antrian pesanan kopi. Data otomatis tersusun berdasarkan aturan BST sehingga pencarian nomor antrian pertama dan terakhir menjadi lebih mudah dan cepat.

https://youtu.be/dCPPbX5XKgE


