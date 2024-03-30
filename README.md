# Assignment Test Python 5: OOP
Assigment  ini bertujuan untuk membersihkan dan mentransformasi data yang terdapat dalam file CSV menggunakan prinsip Object-Oriented Programming (OOP). Khususnya, tugas ini akan menggunakan konsep dasar OOP, pewarisan (inheritance), dan polimorfisme.

### Prinsip OOP yang akan digunakan:

1. Basic OOP
2. Inheritance
3. Polymorphism

### Task 1: Basic OOP

Buatlah class `MarketingDataETL` yang memiliki tiga metode:
- `extract()`: akan membaca data dari sebuah file CSV (Misalkan, `marketing_data.csv`)
- `transform()`: akan melakukan pembersihan dan transformasi sederhana pada data (seperti mengubah format tanggal atau membersihkan nilai yang kosong)
- `store()`: akan menyimpan data yang telah ditransformasi ke dalam struktur data DataFrame.

### Task 2: Inheritance & Polymorphism

1. Gunakan pewarisan untuk membuat class TargetedMarketingETL yang mewarisi dari MarketingDataETL.
2. Tambahkan metode segment_customers() ke dalam TargetedMarketingETL yang mengelompokkan pelanggan berdasarkan kriteria tertentu, misalnya pengeluaran total atau kategori produk yang dibeli.
3. Lakukan polimorfisme dengan meng-override metode transform() dalam TargetedMarketingETL untuk menambahkan logika segmentasi pelanggan ke dalam proses transformasi. `TargetedMarketingETL` untuk menambahkan logika segmentasi pelanggan ke dalam proses transformasi.
