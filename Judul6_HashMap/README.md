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
30. 
