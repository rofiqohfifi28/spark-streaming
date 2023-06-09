# spark-streaming

## Tugas Praktikum
<ol>
  <li>Jelaskan perbedaan Spark Streaming dengan metode stateless dan stateful stream processing?</li>
  <li>Jelaskan masing-masing maksud kode berikut sesuai nomor kodenya pada laporan praktikum Anda!</li>
  
 sys.argv: Ini adalah daftar dalam modul sys di Python yang memberikan akses ke argumen baris perintah yang dilewatkan ke sebuah skrip. Ini memungkinkan kita untuk mengakses argumen yang dilewatkan ke skrip Python saat dieksekusi dari baris perintah.

sys.stderr: Ini adalah objek mirip file dalam modul sys di Python yang mewakili aliran kesalahan standar. Digunakan untuk mencetak pesan kesalahan dan informasi traceback.

StreamingContext: Ini adalah kelas dalam modul Streaming Apache Spark yang digunakan untuk membuat DStream, yang merupakan Discretized Stream. DStream mewakili aliran data kontinu dalam Spark.

sc: Ini adalah objek dalam Apache Spark yang mewakili SparkContext. SparkContext adalah titik masuk untuk semua fungsionalitas Spark. Digunakan untuk membuat RDD (Resilient Distributed Datasets) dan melakukan operasi pada mereka.

socketTextStream: Ini adalah fungsi dalam Apache Spark Streaming yang membuat DStream dengan mendengarkan soket untuk data. Membaca data teks yang diterima melalui soket sebagai aliran baris masukan.

reduceByKey: Ini adalah operasi transformasi dalam Apache Spark yang digunakan pada pasangan RDD untuk menggabungkan nilai-nilai setiap kunci menggunakan fungsi reduce yang ditentukan. Mengelompokkan nilai-nilai setiap kunci dan menerapkan fungsi reduce pada nilai-nilai yang dikelompokkan.

lambda line: Ini adalah fungsi lambda dalam Python yang mengambil parameter bernama 'line' dan mewakili fungsi anonim. Dapat digunakan untuk mendefinisikan fungsi kecil satu baris tanpa nama.

awaitTermination: Ini adalah metode dalam StreamingContext Apache Spark yang memblokir thread saat ini sampai konteks streaming dihentikan secara eksplisit atau terjadi pengecualian.
nc: Ini merujuk pada perintah "nc" atau "netcat" di Linux. Ini adalah utilitas yang digunakan untuk membaca dari dan menulis ke koneksi jaringan. Dalam konteks data streaming, "nc" sering digunakan untuk mengatur soket jaringan yang berfungsi sebagai sumber data.

lk: Istilah "lk" tidak memiliki arti standar atau diakui secara luas dalam konteks pemrograman atau pemrosesan data. Tanpa konteks tambahan, sulit untuk menentukan arti spesifiknya.

spark-submit: Ini adalah alat baris perintah yang disediakan oleh Apache Spark yang digunakan untuk mengirimkan aplikasi Spark ke sebuah kluster. Ini mengambil file JAR atau file Python aplikasi sebagai input dan meluncurkan aplikasi di kluster.
 master: Ini adalah parameter yang digunakan dengan spark-submit untuk menentukan alamat manajer kluster. Ini menentukan di mana aplikasi Spark harus dijalankan.

local[*]: Ini adalah nilai khusus untuk parameter "master" dalam Apache Spark yang menunjukkan aplikasi harus dijalankan secara lokal pada semua core yang tersedia. Sering digunakan untuk pengembangan dan pengujian lokal.

ssc.checkpoint: Ini adalah metode dalam StreamingContext Apache Spark yang mengatur direktori di mana sistem streaming akan menulis file checkpoint. Checkpointing digunakan untuk toleransi kesalahan dan pemulihan dalam aplikasi streaming.
parallelize: Ini adalah metode dalam SparkContext Apache Spark yang digunakan untuk membuat RDD dari koleksi data dalam program pengemudi. Mendistribusikan data ke beberapa partisi untuk memungkinkan pemrosesan paralel.

updateStateByKey: Ini adalah operasi transformasi dalam Apache Spark Streaming yang memungkinkan kita untuk mempertahankan informasi status sembarang di beberapa batch data. Digunakan untuk memperbarui status suatu kunci berdasarkan data masukan baru dan fungsi pembaruan yang ditentukan oleh pengguna.

flatMap: Ini adalah operasi transformasi dalam Apache Spark yang digunakan untuk mengubah setiap elemen RDD menjadi nol atau lebih elemen keluaran. Mengambil fungsi sebagai argumen dan menerapkannya pada setiap elemen masukan untuk menghasilkan elemen keluaran.
rdd.take(5): Ini adalah metode dalam RDD Apache Spark yang mengembalikan lima elemen pertama dari RDD.
</ol>
