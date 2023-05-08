## Nama      : Dwi Maria Ulfa
## Kelas     : TI - 3C
## No. Absen : 06
##

### Kode 1 
[ mylist, myschema ]
- mylist : variabel yang biasanya digunakan untuk menyimpan data dalam bentuk daftar atau array. 

- myschema : variabel yang biasa digunakan untuk menyimpan struktur atau skema dari suatu data
##

### Kode 2
[ spark.createDataFrame ]
- spark.createDataFrame() : metode yang digunakan dalam Apache Spark untuk membuat objek DataFrame baru dari data yang diberikan dalam format tertentu.
##

### Kode 3
[ parallelize, toDF ]
- parallelize : metode dalam Spark SQL yang digunakan untuk membuat RDD dari koleksi yang ada di memori (in-memory collection), seperti list atau array.
- toDF : metode dalam Spark SQL yang digunakan untuk mengubah RDD menjadi DataFrame.
##

### Kode 4
[ hadoop, fs, put ]
- hadoop : modul dalam Spark SQL yang digunakan untuk berinteraksi dengan Hadoop Distributed File System (HDFS) dan sistem file lainnya yang didukung oleh Hadoop.
- fs : modul dalam Spark SQL yang digunakan untuk berinteraksi dengan sistem file secara langsung tanpa melalui Hadoop.
- put : sebuah operasi untuk mengunggah file atau objek dari mesin lokal atau virtual ke sistem penyimpanan objek pada PySpark.
##

### Kode 5
[ pyspark.sql, SQLContext, createOrReplaceTempView, show ]
- pyspark.sql : modul dalam PySpark yang menyediakan antarmuka untuk bekerja dengan data terstruktur menggunakan DataFrame API atau SQL.
- SQLContext : kelas dalam modul pyspark.sql yang digunakan untuk membuat objek SparkSession. 
- createOrReplaceTempView : method dalam DataFrame API yang digunakan untuk membuat view sementara dari DataFrame yang ada. 
##

### Kode 6
[ textFile, map, lambda, strip, StructField, StringType ]
- textFile : method pada objek SparkContext yang digunakan untuk membaca file teks dalam format Hadoop dan mengembalikan RDD yang berisi baris-baris dalam file tersebut.
- map : method pada RDD yang digunakan untuk mengaplikasikan sebuah fungsi pada setiap elemen di dalam RDD, menghasilkan RDD baru.
- lambda : sebuah fungsi anonim dalam Python yang dapat didefinisikan dalam satu baris kode.
- strip : method pada string yang digunakan untuk menghapus karakter whitespace dari awal dan akhir string.
- StructField : kelas dalam modul pyspark.sql.types yang digunakan untuk mendefinisikan kolom dalam schema DataFrame.
- StringType : salah satu kelas dalam modul pyspark.sql.types yang digunakan untuk mendefinisikan tipe data string dalam schema DataFrame.
##

### Kode 7
[ spark.read.format, jdbc, options, load ]
- spark.read.format : method pada objek SparkSession yang digunakan untuk membaca data dari sumber eksternal dalam berbagai format, seperti CSV, Parquet, JSON, dan lain-lain.
- jdbc : salah satu format yang didukung oleh spark.read.format. Format ini digunakan untuk membaca data dari database relasional menggunakan JDBC.
- options : parameter opsional pada method jdbc yang digunakan untuk menentukan opsi-opsi koneksi dan pembacaan data dari database, seperti username, password, URL koneksi, dan lain-lain.
- load : method pada objek DataFrameReader yang digunakan untuk membaca data dari sumber eksternal dan mengembalikan DataFrame.
##

### Kode 8
[ show ]
-show : method pada objek DataFrame pada PySpark SQL yang digunakan untuk menampilkan isi DataFrame. Method ini sangat berguna saat kita ingin melihat data yang terdapat dalam DataFrame.
##

### Kode 9
[ collect, rdd, take ]
- collect : method pada objek DataFrame pada PySpark SQL yang digunakan untuk mengumpulkan semua data dalam DataFrame dan mengembalikannya sebagai bentuk list di driver program. 
- rdd : singkatan dari Resilient Distributed Datasets, yaitu representasi dasar data pada Spark. RDD adalah koleksi yang terdistribusi dan tahan terhadap kegagalan, yang dapat dipartisi dan didistribusikan di seluruh node pada cluster Spark.
- take : method pada objek RDD pada PySpark yang digunakan untuk mengambil sejumlah elemen pertama dari RDD dan mengembalikannya sebagai bentuk list.
##

### Kode 10
[ makeRDD, Seq, createDataset ]
- makeRDD : method pada objek SparkContext pada PySpark yang digunakan untuk membuat RDD dari kumpulan data yang ada di dalam memory driver program.
- Seq (Sequence) : struktur data pada bahasa pemrograman Scala yang digunakan untuk merepresentasikan kumpulan data berurutan dalam bentuk list. 
- createDataset : method pada objek SparkSession pada PySpark yang digunakan untuk membuat Dataset dari kumpulan data yang ada di dalam memory driver program.
##

### Kode 11
[ filter ]
- Sintaks filter pada PySpark digunakan untuk memfilter RDD atau DataFrame berdasarkan suatu kondisi atau predikat yang didefinisikan. Fungsi ini memungkinkan kita untuk mengambil subset dari data yang kita perlukan, berdasarkan kondisi tertentu.
##

### Kode 12
[ as, toDF, first ]
- as : method pada PySpark yang digunakan untuk memberi alias pada suatu kolom pada DataFrame atau RDD. Dengan memberikan alias pada kolom, kita dapat mengacu pada kolom tersebut dengan nama yang lebih mudah dibaca dan dimengerti
- toDF : method pada RDD pada PySpark yang digunakan untuk mengubah RDD menjadi DataFrame. Method ini sangat berguna ketika kita ingin menggunakan fitur-fitur DataFrame pada RDD yang kita miliki.
- first : method pada RDD atau DataFrame pada PySpark yang digunakan untuk mengembalikan nilai pertama pada RDD atau DataFrame. 
##

### Kode 13
[ listDatabases, listTables, listFunctions, isCached, select ]
- listDatabases() : method pada SparkSession yang digunakan untuk mengambil daftar nama database yang ada dalam cluster Spark.
- listTables(databaseName=None) : method pada SparkSession yang digunakan untuk mengambil daftar nama tabel yang ada dalam database tertentu atau semua database dalam cluster Spark.
- listFunctions : method pada SparkSession yang digunakan untuk mengambil daftar nama fungsi yang tersedia dalam database tertentu atau semua database dalam cluster Spark.
- isCached() : method pada RDD atau DataFrame pada PySpark yang digunakan untuk mengecek apakah RDD atau DataFrame tersebut sudah dicache di memori atau belum.
- select(*cols) : method pada DataFrame pada PySpark yang digunakan untuk memilih kolom tertentu dari DataFrame.
##

### Kode 14
[ Read, text ]
- Sintaks read dan text pada PySpark digunakan untuk membaca file teks dan mengonversi isi file menjadi RDD (Resilient Distributed Dataset) pada PySpark.
##

### Kode 15
[ load, json, format, printSchema ]
- load : method yang digunakan pada objek DataFrameReader untuk membaca data dari berbagai format file dan mengembalikan DataFrame. Method ini memungkinkan kita untuk menentukan format file yang ingin dibaca dan mengatur beberapa opsi saat membaca data.
- json : method yang digunakan pada objek DataFrameReader untuk membaca file JSON dan mengonversi isi file menjadi DataFrame.
- format : method yang digunakan pada objek DataFrameWriter untuk menentukan format file saat menyimpan DataFrame sebagai file. Format yang didukung oleh PySpark antara lain adalah JSON, CSV, Parquet, dan Avro.
- printSchema : method yang digunakan pada DataFrame untuk mencetak schema DataFrame ke konsol.
##

### Kode 16
[ write, save ]
- Sintaks write dan save pada PySpark digunakan untuk menyimpan DataFrame ke dalam format file yang berbeda-beda, seperti CSV, Parquet, dan JSON.
##

### Kode 17
[ parquet ]
- Sintaks parquet pada PySpark dapat digunakan untuk membaca, menulis, dan memproses data dalam format Parquet pada DataFrame.
##

### Kode 18
[ Options, inferSchema, csv, header, codec ] 

Sintaks Options, inferSchema, csv, header, dan codec pada PySpark digunakan untuk membaca file CSV dan mengonfigurasi opsi pembacaan.
- Options: Digunakan untuk mengkonfigurasi opsi pembacaan file CSV. Beberapa opsi yang tersedia adalah delimiter, quote, escape, nullValue, dan dateFormat.
- inferSchema: Digunakan untuk mengambil skema data dari file CSV secara otomatis.
- csv: Digunakan untuk mengidentifikasi format file yang dibaca sebagai file CSV.
- header: Digunakan untuk menentukan apakah baris pertama dalam file CSV berisi header kolom.
- codec: Digunakan untuk mengidentifikasi jenis codec yang digunakan untuk membaca file CSV. Beberapa codec yang didukung adalah UTF-8, ISO-8859-1, dan US-ASCII.

##