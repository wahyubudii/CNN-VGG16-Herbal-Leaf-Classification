# Klasifikasi Daun Herbal Berdasarkan Citra Daun Menggunakan Metode Convolutional Neural Networks Arsitektur Model VGG16

## Abstrak

Daun herbal merupakan jenis daun yang sering dimanfaatkan masyarakat dalam bidang kesehatan. Permasalahan yang ditemui adalah kurangnya pengetahuan mengenai jenis daun herbal dan sulitnya membedakan jenis daun herbal bagi orang awam yang tidak paham dengan tanaman. Jika sembarang jenis tanaman digunakan  akan berdampak buruk bagi kesehatan. Oleh karenanya, penelitian ini bertujuan untuk mengklasifikasi citra daun herbal. Proposed method yang diusulkan menggunakan metode transfer learning dengan pretrained model VGG16 dan menggunakan dataset daun herbal dengan jumlah 10 kelas yaitu kelas: Belimbing Wuluh, Jambu Biji, Jeruk, Kemangi, Lidah Buaya, Nangka, Pandan, Pepaya, Seledri dan Sirih. Performa hasil klasifikasi proposed method terhadap dataset testing menunjukkan nilai accuracy sebesar 100% menggunakan classification report. Penggunaan ImageDataGenerator yang dimanfaatkan untuk proses augmentasi berfungsi dalam menambah citra daun herbal, menurunkan overfitting, dan meningkatkan akurasi.

## Manfaat

Tanaman herbal mempunyai banyak manfaat bagi kehidupan manusia dalam berbagai aspek, seperti bahan makanan, penyedia oksigen, dan lainnya [1]. Untuk mengetahui jenis tanaman herbal ada beberapa yang dapat diperhatikan, seperti mengenali pola dari tanaman herbal, bentuk tanaman, tekstur tanaman, dan karakteristik struktur tanamannya [2]. Salah satu bagian tanaman yang sering dimanfaatkan dalam bidang kesehatan adalah bagian daun dari tanaman itu sendiri [3]. Kondisi orang awam yang tidak terlalu paham dengan tanaman pastinya akan merasa bingung untuk membedakan jenis daun herbal, dikarenakan banyak jenis daun herbal yang dapat ditemukan saat ini. Bahkan,  banyak masyarakat yang kurang paham apakah daun tersebut tergolong jenis tanaman herbal atau tanaman biasa dan jika disalahgunakan akan berdampak buruk bagi kesehatan. Untuk dapat membedakan jenis daun herbal, diperlukan informasi yang akurat dan khusus mengenai daun herbal dan pengetahuan dalam memanfaatkan daun herbal [4]. Salah satu cara yang dapat digunakan untuk memberikan informasi kepada masyarakat terkait jenis daun herbal adalah dengan memanfaatkan teknologi berkembang. Tanpa adanya pemanfaatan teknologi berkembang, maka yang dilakukan untuk mengetahui jenis daun herbal adalah dengan proses identifikasi secara manual [5]. Proses ini tergolong memakan waktu, biaya dan tidak semua orang dapat melakukannya karena membutuhkan bantuan ahli.

## Metode

Penelitian ini menerapkan metode transfer learning dalam pembuatan proposed method. Architecture model yang digunakan yakni VGG16 yang selanjutnya akan ditambah dengan arsitektur layer baru pada bagian Fully Connected Layer yaitu output layer untuk menyesuaikan dengan jumlah kelas dataset yang diklasifikasikan.

## Dataset
Database yang kami gunakan dalam penelitian ini adalah berikut: 
<a href=https://data.mendeley.com/datasets/s82j8dh4rr/1>Indonesian Herb Leaf Dataset 3500</a>
