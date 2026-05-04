JUDUL >> Pengurutan Jumlah Waktu Jam Tidur

DESKRIPSI >> Program ini dibuat untuk mengurutkan jumlah waktu jam tidur berdasarkan jumlah waktu tidur tercepat hingga yang paling lama menggunakan Insertion Sort. Yang dimana sistem akan mengecek data mulai dari elemen kedua, dan elemen akan dipindahkan terlebih dahulu ke sebelah kanan supaya nilai sementara dapat dipindahkan se posisi yang benar. Jika elemen kedua lebih kecil dibandingkan dengan elemen pertama maka sistem akan menyisipkan ke posisi paling kiri, sedangkan jika elemen kedua tersebut lebih besar maka akan di tempatkan pada posisi di sebelah kanan. Proses ini akan terus berulang hingga semua elemen berada posisi yang sudah di terurut.

SOURCE CODE >>
<img width="678" height="260" alt="Screenshot 2026-05-02 220816" src="https://github.com/user-attachments/assets/fadfd723-a724-4e4a-823d-ce6923756ab9" />
1. mendefinisikan fungsi yang bernama insertion sort yang berbentuk array
2. melakukan perulangan dari indeks ke-1 sampai ke-(n-1) karena indeks ke-0 sudah dianggap terurut
3. menyimpan nilai elemen ke-i ke variabel sementara yang dimana nilai ini akan disisipkan ke posisi yang benar
4. menentukan indeks sebelumnya (yang berada pada sisi sebelah kiri) dan digunakan untuk membandingkan dan menggeser elemen
5. melakukan perulangan selama j masih pada batas array (tidak negatif) dan nilai j lebih besar di bandingkan nilai sementara
6. menggeser elemen yang lebih besar ke kanan satu langkah supaya nilai sementara memiliki tempat
7. pindah ke indeks sebelumnya (ke kiri) dan melanjutkan pengecekan
8. menempatkan nilai sementara ke posisi yang benar setelah pergeseran selesai

<img width="910" height="726" alt="Screenshot 2026-05-02 222026" src="https://github.com/user-attachments/assets/bc805d0c-7ca8-40b4-ae60-d505c76e2cac" />
10. mendefinisikan fungsi utama program
11. digunakan untuk menangani error jika input bukan angka
12. meminta user memasukkan jumlah data dan mengubah input menjadi bilangan bulat
13-15. jika user memasukan input selain angka maka sistem akan menampilkan pesan input tidak valid
16. membuat list kosong bernama array untuk menyimpan data
17. menampilkan instruksi untuk mengisi data
18. perulangan sebanyak n kali sesuai jumlah elemen
19. perulangan tak terbatas sampai input valid
20-21. meminta user menginputkan angka dan mengubah nya menjadi integer
22. menambahkan nilai ke dalam list arr
23. keluar dari while jika input valid
24-25. jika input bukan angka maka akan menampilkan pesan eror dan mengulangi input karena masih di dalam while
26. menampilkan isi array sebelum sorting
27. memanggil fungsi insertion sort untuk mengurutkan data
28. menampilkan teks tanpa pindah baris
29-30. menampilkan setiap elemen array yang sudah diurutkan
31. pindah ke baris baru
33-34. mengecek apakah file bisa dijalankan langsung jika iya maka fungsi main() akan dijalankan


OUTPUT >>
<img width="682" height="269" alt="Screenshot 2026-05-02 224037" src="https://github.com/user-attachments/assets/04e70066-bd0b-479e-a4f1-fab79878c177" />
Pada output ini program akan berjalan mengecek satu per satu elemen. Seperti pada elemen pertama adalah 8 dan elemen kedua adalah 6 jadi sistem akan melihat manakah elemen yang lebih kecil dan akan di tempatkan di sebelah kiri. Didapatkan elemen kedua lebih kecil dibandingkan dengan elemen pertama jadi, elemen kedua akan di tempatkan ke sebelah kiri dan elemen pertama di sebelah kanan. Sistem akan terus mengecek dan mengurutkan elemen sampai elem-elemen tersebut berada pada posisi yang benar.

https://youtu.be/sNTkEKsrRKI
