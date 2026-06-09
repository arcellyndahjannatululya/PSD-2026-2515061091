JUDUL >> Daftar Kopi

DESKRIPSI >> Program ini berfungsi untuk menyimpan, mencari, menampilkan, dan menghapus data daftar kopi berdasarkan sebuah key berupa bilangan integer. Program ini menyediakan operasi dasar seperti menambah data (insert), mencari data (search), menghapus data (remove_key), dan menampilkan isi hash table (display). Metode Separate Chaining digunakan untuk menangani collision dengan menyimpan data yang memiliki indeks sama dalam bentuk linked list, sehingga proses pengelolaan data menjadi lebih efisien.

SOURCE KODE >>
<img width="843" height="749" alt="Screenshot 2026-06-09 181534" src="https://github.com/user-attachments/assets/15a2e7e0-cc5c-46d5-bba0-5431f78a830e" />
<img width="865" height="685" alt="Screenshot 2026-06-09 181548" src="https://github.com/user-attachments/assets/513bdfad-0531-4848-b3a0-714be2145d20" />
<img width="1090" height="713" alt="Screenshot 2026-06-09 181606" src="https://github.com/user-attachments/assets/758dd712-cb8b-4723-a58d-a2b0843e6593" />
<img width="939" height="204" alt="Screenshot 2026-06-09 181617" src="https://github.com/user-attachments/assets/e00f0b8a-2452-4537-a003-2053e0a0f74c" />

1. mendefinisikan kelas node
2. constructor yang dijalankan saat objek Node dibuat
3. menyimpan key (kunci) data
4. menyimpan value (nilain) data
5. pointer menuju node selanjutnya, awalnya none karna belum terhubung dengan yang lain
6. -
7. membuat kelas HashMap yang menggunakan metode Separate Chaining untuk menangani collision
8. constructor dengan ukuran default hash table sebanyak 10
9. menyimpan ukuran Hash table
10. membuat list berisi 10 elemen dengan nilai awal None
11. -
12. membuat fungsi hash
13. menghasilkan indeks dari key menggunakan operasi modulo
14. -
15. fungsi untuk menambahkan data ke HashMap
16. menentukan posisi indeks menggunakan fungsi hash
17. mengambil node pertama pada indeks tersebut
18. melakukan penelusuran linked list selama masih ada node
19. memeriksa apakah key sudah ada
20. jika ada, value lama diperbarui
21. menghentikan fungsi
22. berpindah ke node berikutnya
23. membuat node baru
24. node baru diarahkan ke node pertama pada indeks tersebut
25. node baru menjadi node pertama (head) linked list
26. -
27. digunakan untuk mencari data berdasarkan key
28. menentukan indeks key
29. mengambil node pertama pada indeks tersebut
30. menelusuri linked list
31. jika key ditemukan
32. mengembalikan node yang ditemukan
33. berpindah ke node berikutnya
34. jika data tidak ditemukan maka mengembalikan None
35. -
36. fungsi untuk menghapus data berdasarkan key
37. menentukan indeks key
38. mengambil node pertama
39. variabel untuk menyimpan node sebelumnya
40. menelusuri linked list
41. jika key ditemukan
42-43. jika node yang dihapus berada diawal head berpindah ke node berikutnya
44-45. jika node berada di tengah atau akhir node sebelumnya langsung menunjuk ke node sesudahnya
46. penghapusan berhasil
47. menyimpan node sekarang sebagai node sebelumnya
48. berpindah ke node berikutnya
49. jika key tidak ditemukan
50. -
51. menampilkan isi hash table
52. mencetak judul
53. melakukan perulangan dari indeks 0 sampai 9
54. menampilkan nomor indeks
55. mengambil node pertama pada indeks tersebut
56. menelusuri linked list
57. menampilkan pasangan key dan value
58. berpindah ke node berikutnya
59. menandakan akhir linked list
60. -
61. program utama
62. membuat objek hash map
63. menambahkan data kopi dengan menyimpan key 7 value Torabika
64. menambahkan data kopi dengan menyimpan key 5 value Kopi Kapal Api
65. menambahkan data kopi dengan menyimpan key 1 value Capucinno
66. menambahkan data kopi dengan menyimpan key 3 value Latte
67. menambahkan data kopi dengan menyimpan key 9 value BUtterscout
68. menampilkan seluruh isi hash table
69. -
70. meminta pengguna memasukkan key kopi yang ingin dicari
71. jika data ditemukan
72. menampilkan nama kopi
73-74. jika key tidak ada
75. -
76. menghapus data dengan key 5 (Kopi Kapal Api)
77. menampilkan pesan
78. menampilkan isi hash table setelah penghapusan
79. -
80. memastikan program dijalankan langsung, bukan diimpor dari file lain
81. memanggil fungsi main() sehingga seluruh program dieksekusi

OUTPUT >>
<img width="750" height="763" alt="image" src="https://github.com/user-attachments/assets/a894e9cd-ec06-449d-be64-b5cddc5fbf09" />

Pada output tersebut menunjukkan bahwa program berhasil menyimpan data kopi ke dalam Hash Table, kemudian melakukan proses pencarian dan penghapusan data. Saat pengguna memasukkan key 9, program berhasil menemukan data dengan nilai "Butterscout". Selanjutnya, program menghapus data dengan key 5 (Kopi Kapal Api), sehingga pada tampilan hash table setelah penghapusan, indeks 5 menjadi NONE, yang menandakan bahwa data tersebut sudah tidak ada lagi di dalam Hash Map.

