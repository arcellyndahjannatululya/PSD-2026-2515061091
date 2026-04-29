JUDUL PROGRAM >> PROGRAM LIST MENU MAKANAN

DESKRIPSI SINGKAT >> Program ini dibuat menggunakan list 2D yang dimana digunakan untuk membuat list menu makanan. Didalam kode ini terdapat 7 pilihan yaitu tambah makanan, hapus makanan, tampilkan menu, lihat makanan sekarang, menu selanjutnya, menu sebelumnya dan keluar. Jadi user dapat memilih salah satu dari piliha yang tersedia.

SOURCE CODE >>
<img width="583" height="631" alt="Screenshot 2026-04-29 201704" src="https://github.com/user-attachments/assets/5de31b98-c8bf-422b-8b37-0c62f8516b92" />
1. untuk mendefinisikan class bernama MenuMakanan sebagai node/simpul
2. method yang otomatis akan dipanggil saat objek dibuat
3. menyimpan nilai nama ke dalam objek
4. pointer ke node berikutnya
5. pointer ke node sebelumnya
7. mendefinisikan class untuk mengelola linked list menu makanan
8. untuk inisialisai awal
9. node pertama adalah head pada list yang awal nya kosong
10. current untuk menyimpan posisi menu yang sedang aktif/dipilih
12. untuk menambah menu baru
13. membuat objek baru node pada class MenuMakanan
14. mengecek apakah list masih kosong
15. jika kosong node baru menjadi head
16. current juga diarahkan menjadi node pertama
17. else jika list sudah ada isinya
18. variabel sementara untuk menelusuri list mulai dari head
19. perulangan untuk mencari node terakhir selama node masih ada
20. berpindah ke node berikutnya
21. menghubungkan node terakhir dengan node baru
22. node terakhir menunjuk kembali ke node sebelumnya

<img width="713" height="545" alt="Screenshot 2026-04-29 201721" src="https://github.com/user-attachments/assets/c64b53b2-89c2-4bc4-9373-2bb0eda3b2da" />
24. fungsi untuk menghapus data makanan
25. mulai dari node pertama
26. menelusuri semua node
27. mengecek data yang akan dicari
28. jika bukan node pertama
29. lewati node yang dihapus
30. jika node pertama
31. menggeser head
32. jika ada node setelahnya
33. menghubungkan ke node sebelumnya
34. jika yang di hapus adalah current
35. current pindah
36. pesan berhasil dihapus
37. hentikan fungsi
38. lanjutkan ke node selanjutnya
39. jika tidak ada data

<img width="704" height="634" alt="Screenshot 2026-04-29 201736" src="https://github.com/user-attachments/assets/833c48cf-dba3-4e7f-a97d-0cd4b7787c27" />
41. fungsi menampilkan semua data
42. mulai dari awal
43. mengecek list kosong
44. menampilkan pesan jika menu kosong
45. menghentikan fungsi
46. melakukan perulangan semua node
47. menampilkan data
48. pindah ke node berikutnya
49. penanda akhir list
51. menampilkan menu aktif
52. mengecek ada data
53. menampilkan menu saat ini
54. jika kosong
55. menampilkan pesan tidak ada menu
57. navigasi ke depan
58. mengecek apakah bisa maju
59. pindah ke selanjutnya
60. menampilkan menu
61. jika tidak ada
62. menampilkan pesan menu sudah di akhir

<img width="575" height="193" alt="Screenshot 2026-04-29 201751" src="https://github.com/user-attachments/assets/bf2f196d-c43e-4d26-809e-1ce1fc96ec9f" />
64. navigasi ke belakang
65. mengecek apakah bisa mundur
66. pindah ke sebelumnya
67. menampilkan menu
68. jika tidak bisa
69. menampilkan pesan sudah di menu pertama

<img width="745" height="704" alt="Screenshot 2026-04-29 201804" src="https://github.com/user-attachments/assets/33ff9c4c-8df1-4bdd-a88f-382f4a16b02d" />
72. membuat objek
74. perulangan program
75-82. menampilkan menu pilihan
84. user menginput
86. if pertama menambah makanan
87. mengambil data
88. menyimpan data
90. if kedua menghapus makanan
91. mengambil data
92. menghapus data
95. menampilkan menu

<img width="547" height="448" alt="Screenshot 2026-04-29 215235" src="https://github.com/user-attachments/assets/65d24eb2-690f-43d2-8e37-f39b0e0a1c82" />
<img width="633" height="560" alt="Screenshot 2026-04-29 215646" src="https://github.com/user-attachments/assets/08e3b4af-fda8-4673-9fdd-95ce0b1d2277" />
98. melihat makanan
101. menu selanjutnya
104. menu sebelumnya
107. keluar dari program
108. perulangan berhenti
110. jika input salah
111. menampilkan pesan pilihan tidak valid

OUTPUT >>
<img width="627" height="570" alt="Screenshot 2026-04-29 215627" src="https://github.com/user-attachments/assets/03764d03-2fbf-4fb9-9bdf-e0f4b98d9212" />
Jadi  pada output user memilih pilihan pertama yaitu menambah menu makanan yang selanjutnya akan disimpan oleh sistem lalu user kembali memilih menambah menu makanan yang akan kembali disimpan oleh sistem. User kembali memilih untuk menampilkan semua menu makanan yang dimana sistem akan menampilkan seluruh menu yang sudah di inputkan oleh user. Yang terakhir user memilih untuk keluar dah program akan otomatis berhenti.
