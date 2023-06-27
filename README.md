**# RivaldiSabala_F55121039_UAS_PAA2**

A. Analisis algoritma bubble sort dan insertion sort
   Fungsi Bubble Sort:
        Fungsi bubble_sort(arr) digunakan untuk mengurutkan array arr menggunakan algoritma Bubble Sort.
        Algoritma Bubble Sort bekerja dengan membandingkan setiap elemen secara berpasangan dan menukar posisi jika ditemukan elemen yang lebih besar.
        Fungsi ini mengembalikan waktu eksekusi pengurutan.
    
    Fungsi Insertion Sort:
        Fungsi insertion_sort(arr) digunakan untuk mengurutkan array arr menggunakan algoritma Insertion Sort.
        Algoritma Insertion Sort bekerja dengan membagi array menjadi dua bagian, yaitu bagian yang sudah diurutkan dan bagian yang belum diurutkan. Kemudian, elemen dari 
        bagian belum diurutkan dimasukkan ke posisi yang tepat dalam bagian yang sudah diurutkan. Fungsi ini mengembalikan waktu eksekusi pengurutan.

    Fungsi display_iterations(arr):
        Fungsi ini digunakan untuk menampilkan 5 iterasi pertama dan 5 iterasi terakhir dari array arr.
        Fungsi display_execution_time(execution_time):
        Fungsi ini digunakan untuk menampilkan waktu komputasi pengurutan yang diberikan dalam parameter execution_time.
        Fungsi display_before_after(arr, sorted_arr):
        Fungsi ini digunakan untuk menampilkan array sebelum dan setelah pengurutan.
        Array awal arr dan array yang sudah diurutkan sorted_arr ditampilkan.

    Fungsi analyze_algorithm():
        Fungsi ini digunakan untuk menampilkan analisis algoritma pengurutan yang diimplementasikan.
        Menjelaskan Worst Case, Best Case, dan Average Case complexity dari Bubble Sort dan Insertion Sort.
        Fungsi main():
        Fungsi ini merupakan fungsi utama yang akan dijalankan saat program dijalankan.
        Mendefinisikan array arr yang akan diurutkan.
        Menampilkan pilihan algoritma pengurutan kepada pengguna.
        Terdapat tiga pilihan: Bubble Sort, Insertion Sort, dan Analisis Algoritma.
        Jika pilihan adalah Bubble Sort atau Insertion Sort, maka array akan diurutkan menggunakan algoritma yang dipilih, dan hasilnya akan ditampilkan.
        Jika pilihan adalah Analisis Algoritma, maka akan ditampilkan penjelasan mengenai kompleksitas waktu algoritma pengurutan yang diimplementasikan.
        Jika pilihan tidak valid, akan ditampilkan pesan kesalahan.
        Selain itu, kode program juga mencakup baris kode yang menginisialisasi dan menjalankan fungsi main() jika file tersebut dieksekusi langsung.

Pada akhirnya, program ini memberikan pengguna pilihan untuk memilih algoritma pengurutan yang akan digunakan, menampilkan hasil pengurutan, waktu eksekusi, dan analisis kompleksitas waktu untuk algoritma pengurutan yang diimplementasikan.

B. Analisis algoritma TSP dan djikstra
   Algoritma TSP:
        Fungsi tsp_algorithm(graph, start_vertex) digunakan untuk mencari jalur terpendek dalam TSP menggunakan pendekatan rekursif dengan memoization.
        Fungsi ini mengambil graf sebagai input yang direpresentasikan dalam bentuk matriks adjacency.
        Algoritma TSP bekerja dengan mencoba semua kemungkinan permutasi dari vertex yang dikunjungi dan mencari jalur terpendek.
        Pada setiap pemanggilan rekursif, fungsi tsp_helper mencoba memilih vertex selanjutnya yang belum dikunjungi dan memanggil dirinya sendiri secara rekursif.
        Fungsi ini mengembalikan jalur terpendek (jarak terpendek) yang ditemukan.

   Algoritma Dijkstra:
        Fungsi dijkstra_algorithm(graph, start_vertex) digunakan untuk mencari jalur terpendek dalam graf menggunakan algoritma Dijkstra.
        Fungsi ini mengambil graf sebagai input yang direpresentasikan dalam bentuk matriks adjacency.
        Algoritma Dijkstra bekerja dengan memulai dari vertex awal dan secara iteratif memperbarui jarak terpendek ke setiap vertex yang belum dikunjungi.
        Pada setiap iterasi, vertex dengan jarak terpendek yang belum dikunjungi dipilih dan jarak terpendek untuk tetangga yang belum dikunjungi diperbarui.
        Fungsi ini mengembalikan array yang berisi jarak terpendek dari vertex awal ke setiap vertex dalam graf.

   Fungsi get_graph_from_user():
        Fungsi ini digunakan untuk meminta input pengguna untuk memasukkan informasi graf.
        Pengguna diminta untuk memasukkan jumlah vertex dan matriks adjacency graf.

   Fungsi main():
        Fungsi ini merupakan fungsi utama yang akan dijalankan saat program dijalankan.
        Menampilkan informasi pembuat program.
        Meminta pengguna untuk memilih algoritma yang ingin digunakan (TSP atau Dijkstra) atau keluar dari program.
        Jika pilihan adalah TSP, pengguna diminta untuk memasukkan informasi graf dan kemudian algoritma TSP dijalankan untuk mencari jalur terpendek. Hasilnya ditampilkan          bersama dengan waktu komputasi.
        Jika pilihan adalah Dijkstra, pengguna diminta untuk memasukkan informasi graf dan vertex awal. Algoritma Dijkstra dijalankan untuk mencari jarak terpendek dari             vertex awal ke setiap vertex dalam graf. Hasilnya ditampilkan bersama dengan waktu komputasi.
        Jika pilihan adalah keluar, program berakhir.
        Jika pilihan tidak valid, pesan kesalahan ditampilkan.
        Selain itu, program ini juga mencakup baris kode yang menginisialisasi dan menjalankan fungsi main() jika file tersebut dieksekusi langsung.

Pada akhirnya, program ini memberikan pengguna pilihan untuk mencari jalur terpendek dalam sebuah graf menggunakan algoritma TSP atau Dijkstra, meminta input graf dari pengguna, dan menampilkan hasil pencarian serta waktu komputasi.
