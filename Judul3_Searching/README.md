JUDUL >> SISTEM PENCARIAN NOMOR KURSI KERETA

DESKRIPSI >> Program ini bertujuan untuk mencari nomor kursi pada kereta. Kode program ini menggunakan sistem pencarian binary search yang dimana data akan dibagi menjadi dua dicari dimulai dari data nilai tengah dan di cari sampai data ditemukan.

SOURCE CODE >>
<img width="758" height="682" alt="Screenshot 2026-05-07 180348" src="https://github.com/user-attachments/assets/ba0a3e74-bed9-42f6-94cf-9b787deeeb03" />

<img width="896" height="667" alt="Screenshot 2026-05-07 183246" src="https://github.com/user-attachments/assets/11655f33-f542-4617-bdc5-07ba13bb6914" />

<img width="931" height="501" alt="Screenshot 2026-05-07 183255" src="https://github.com/user-attachments/assets/3dbe55e9-c7d6-4d6f-8e56-b9e10200396b" />

1. membuat definisi fungsi binary searching
2. menentukan batas kiri yang dimulai dari indeks 0
3. menentukan batas kanan yaitu indeks terakhir
4. variabel untuk menyimpan data jika ditemukan,-1 berarti data belum ditemukan
5. -
6. perulangan akan berjalan selama batas kiri masih kurang atau sama dengan batas kanan
7. menghitung indeks tengah array
8. -
9. menampilkan nomor kursi yang sedang diperiksa
10. -
11. mengecek apakah nomor kursi tengah sama dengan nomor yang dicari
12. jika ditemukan maka posisi akan disimpan
13. menghentikan pencarian
14. -
15. jika nomor kursi tengah lebih kecil dari target, pencarian dilakukan ke kanan
16. menampilkan informasi pencarian berpindah ke kanan
17. menggeser batas kiri
18. -
19. jika nomor kursi tengah lebih besar dari target
20. menampilkan informasi pencarian ke kiri
21. menggeser batas kanan
22. -
23. mengembalikan posisi kursi yang ditemukan
24. -
25. fungsi utama pada program
26. menampilkan judul program
27. -
28. menjalankan program
29. meminta jumlah kursi
30. menangani jika terdapat salah input
31. menampilkan input harus angka
32. mengembalikan fungsi
33. -
34. membuat list kosong untuk menyimpan nomor kursi
35. -
36. meminta pengguna memasukkan nomor kursi secara terurut
37. perulangan untuk menginput data kursi
38. perulangan validasi input
39. menjalankan program
40. meminta nomor kursi
41. menambahkan nomor kursi ke list
42. keluar dari perulangan jika input valid
43. menangani jika terdapat salah input
44. menampilkan jika input salah
45. -
46. menampilkan seluruh nomor kursi
47. menampilkan nomor kursi
48. -
49. membuat perulangan
50. menjalankan program
51. meminta memasukkan nomor kursi yang dicari
52. program berhenti jika di temukan
53. menangani program jika salah
54. menampilkan pesan input harus angka
55. -
56. memanggil fungsi binary searching
57. -
58. mengecek apakah kursi ditemukan
59. menampilkan posisi kursi jika ditemukan
60. kondisi lain jika tidak ditemukan
61. menampilkan pesan tidak ditemukan
62. -
63-64. menjalankan fungsi main saat program dijalankan

OUTPUT >>
<img width="825" height="560" alt="Screenshot 2026-05-07 200759" src="https://github.com/user-attachments/assets/4fd0cc3f-d776-4d70-a426-5efa28faefc7" />
1. pada output user akan diminta memasukkan jumlah nomor kursi yang tersedia dan meminta user untuk menginputkan data secara terurut lalu sistem akan mencetak keseluruhan data secara terurut
2. user akan menginputkan data untuk di cari
3. pengecekan dimulai dari data yang di tengah
4. setelah di cek data lebih kecil daripada nilai data tengah jadi pengeceka bergeser ke kiri
5. data di temukan pada indeks ke-0
    
https://youtu.be/RhdDrRxY9JM
