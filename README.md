Pembahasan Kondisi If

Dalam praktikum ini, mahasiswa mempelajari penggunaan struktur percabangan if pada Python. Struktur ini digunakan agar program dapat mengambil keputusan berdasarkan kondisi tertentu. Dengan adanya kondisi if, program bisa mengeksekusi perintah yang berbeda sesuai dengan input atau situasi yang terjadi, sehingga hasil yang ditampilkan menjadi lebih dinamis.

Pada latihan pertama (latihan1.py), program dibuat untuk menentukan jenis bilangan yang dimasukkan oleh pengguna. Ketika pengguna mengetikkan sebuah angka, program memeriksa apakah angka tersebut bernilai positif, negatif, atau nol menggunakan pernyataan if, elif, dan else. Jika angka lebih besar dari nol maka dikategorikan sebagai bilangan positif, jika lebih kecil dari nol maka negatif, dan jika nilainya sama dengan nol maka akan ditampilkan sebagai nol. Latihan ini menunjukkan dasar logika pemilihan kondisi sederhana dalam Python.

Sementara itu, latihan kedua (latihan2.py) menggunakan bentuk nested if (if di dalam if) untuk menentukan nilai huruf (grade) berdasarkan nilai angka yang dimasukkan pengguna. Pertama, program memeriksa apakah nilai berada dalam rentang yang valid, yaitu 0 hingga 100. Jika valid, maka program melanjutkan proses untuk menentukan nilai huruf: A untuk nilai 90 ke atas, B untuk 80–89, C untuk 70–79, D untuk 60–69, dan E untuk nilai di bawah 60. Jika nilai yang dimasukkan di luar batas tersebut, maka program akan menampilkan pesan kesalahan.

Melalui kedua latihan ini, mahasiswa memahami bahwa struktur if sangat penting dalam pembuatan program karena berfungsi sebagai dasar pengambilan keputusan. Dengan if, program dapat menyesuaikan hasil sesuai kondisi, yang merupakan pondasi utama dalam logika pemrograman dan pembuatan aplikasi berbasis interaksi pengguna.


Pembahasan Perulangan

Pada bagian ini, mahasiswa mempelajari konsep perulangan (loop) dalam Python, yaitu proses menjalankan perintah yang sama berulang kali secara otomatis. Konsep perulangan digunakan agar programmer tidak perlu menulis baris kode yang sama berkali-kali. Selain mempersingkat program, perulangan juga membuat kode menjadi lebih efisien, terutama untuk menangani data dalam jumlah banyak atau operasi yang berulang.

Dalam Python, terdapat dua jenis perulangan utama, yaitu for dan while. Perulangan for biasanya digunakan ketika jumlah pengulangan sudah diketahui sebelumnya, sedangkan while digunakan saat jumlah pengulangan bergantung pada kondisi tertentu yang bisa berubah selama program berjalan.

Pada latihan pertama (latihan1.py), program dibuat untuk menampilkan bilangan dari 1 sampai N menggunakan perulangan for. Pengguna akan memasukkan nilai batas akhir, kemudian program mencetak semua bilangan dari 1 hingga N dengan memanfaatkan fungsi range(). Melalui latihan ini, mahasiswa belajar bagaimana for dapat digunakan untuk mengontrol banyaknya iterasi dengan jumlah yang pasti.

Berbeda dengan itu, latihan kedua (latihan2.py) menggunakan perulangan while untuk menghitung jumlah bilangan dari 1 hingga N. Program meminta pengguna memasukkan batas akhir, kemudian menggunakan variabel penghitung i yang akan terus bertambah sampai mencapai batas tersebut. Selama kondisi i <= n terpenuhi, proses penjumlahan akan terus dijalankan. Setelah kondisi menjadi salah, perulangan berhenti dan hasil akhir ditampilkan.

Dari praktikum ini dapat dipahami bahwa perulangan merupakan salah satu konsep fundamental dalam pemrograman. for lebih cocok digunakan untuk proses yang jumlah iterasinya sudah jelas, sedangkan while digunakan ketika pengulangan bergantung pada kondisi logika. Pemahaman terhadap keduanya menjadi bekal penting untuk membuat program yang efisien dan responsif.

