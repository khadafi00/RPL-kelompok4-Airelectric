# Airelectric
Aplikasi pemantau tingkat polusi udara dan tingkat pemakaian bulanan listrik

## Anggota Kelompok 16
1. Reza Achmad Naufal **G64180078**
2.  **G64180000**.
3.  **G64800000**.

# Latar Belakang
Teknologi saat ini sudah sangat berkembang. Berbagai permasalahan dapat dibantu atau bahkan diselesaikan dengan cepat melalui bantuan teknologi. Beberapa petmasalahan hidup yang terjadi di masyarakat generasi sekarang dan juga akan berdampak besar kepada kehidupan di generasi nantinya adalah permasalahan pencemaran udara di suatu daerah dan pemakaian listrik yang berlebihan di tempat tinggal masing-masing. Pencemaran udara di suatu daerah dapat mengakibatkan masalah kesehatan, seperti terganggunya pernapasannya pada manusia dan menyebabkan juga kanker pada tubuh, selain itu dapat menyebabkan pemanasan global yang dapat meningkatkan suhu di bumi. Pemakaian listrik yang berlebihan dapat mengakibatkan semakin banyaknya emisi yang dihasilkan berupa karbon yang berdampak pada pemanasan global, karena sebagian besar listrik dihasilkan dari energi fosil. Oleh karena dampak yang sangat buruk tersebut dan untuk mempermudah manusia dalam mengingatkan agar dampak tersebut dapat diminimalisir, diperlukannya alat berupa teknologi untuk mengingatkan manusia akan hal-hal tersebut.

# Tujuan
1. Memudahkan masyarakat untuk mengetahui kondisi udara di daerahnya sendiri setiap saat;
2. Memudahkan masyarakat untuk mengetahui peningkatan atau penurunan kualitas udara di daerahnya sendiri melalui grafik;
3. Memudahkan masyarakat dalam mengetahui status cuaca setiap saat;
4. Memudahkan masyarakat untuk mengetahui peningkatan atau penurunan pemakaian rata-rata listrik perbulannya melalui grafik.

# Ruang Lingkup
1. Aplikasi ini harus terhubung dengan internet untuk melihat menggambil data dari database melalui API;
2. Masyarakat cenderung terlalu tidak peduli terhadap dampak dari berlebihan penggunaan listrik dan buruknya kualitas udara;
3. Data untuk pembayaran tagihan listrik harus terkini dan valid;
4. Masyarakat hanya bisa melihat grafik peningkatan atau penurunan penggunaan listrik apabila transaksinya melalui aplikai **Airelectric**;
5. Data cuaca dan kualitas udara bergantung pada situs **Airvisual**;
6. Grafik penggunaan listrik belum menampilkan rata-rata penggunaan perbulannya;
7. Data daerah untuk menampilkan cuaca dan kualitas udara terbatas.

# Deskripsi Aplikasi
Aplikasi **Airelectric** menyimpan data mengenai kondisi cuaca dan kondisi udara di setiap daerah, dan menyimpan data penggunaan listrik masing-masing penggguna aplikasi melalui transaksi pembayaran listrik yang dilakukan dari aplikasi ini. Aplikasi ini akan memberikan info mengenai kondisi cuaca dan udara di daerah terdekat dari tempat aplikasi ini di jalankan. Aplikasi ini juga akan memberikan info mengenai penaikan atau penurunan kualitas udara dan penggunaan listrik melalui grafik yang di tampilkan.

# User Profile
Target dari aplikasi ini adalah masyarakat, terutama orang yang sudah bekerja dan memiliki tempat tinggal sendiri, yang harus diingatkan akan penggunaan kendaraan bermotor yang emisi nya bisa menyebabkan kondisi udara buruk dan juga harus diingatkan tentang pemakaian listrik, terutama di tempat tinggalnya tersebut.

# User Story
- Sebagai seorang pekerja yang setiap hari harus keluar rumah, berarti saya harus mengetahui kondisi cuaca hari ini agar saya bisa mempersiapkan apabila kondisi cuaca saat ini sedang tidak mendukung aktivitas saya.
- Sebagai seorang pekerja yang setiap hari harus keluar rumah, saya harus tau bagaimana kondisi udara di daerah saya saat ini, apabila itu buruk untuk kesehatan saya maka saya harus menggunakan pelindung pernapasan (masker).
- Sebagai seseorang yang memiliki tempat tinggal, saya ingin mengetahui seberapa besar peningkatan pembayaran listrik saya setiap bulannya.

# Use Case Diagram
![UseCaseDiagram](https://user-images.githubusercontent.com/48080398/82188414-07f54200-9918-11ea-99f7-1cc3a9efe80c.png)

# Use Case Description
### Use Case Description : Proses Melihat Cuaca
![UseCaseDescription-ProsesMelihatCuaca](https://user-images.githubusercontent.com/48080398/82188545-3d019480-9918-11ea-9d05-caef877a2acb.png)
### Use Case Description : Proses Pembelian Token
![UseCaseDescription-ProsesPembelianToken](https://user-images.githubusercontent.com/48080398/82188585-48ed5680-9918-11ea-86bf-3ee77f6cf727.png)
### Use Case Description : Proses Pembayaran Tagihan
![UseCaseDescription-ProsesPembayaranTagihan](https://user-images.githubusercontent.com/48080398/82188658-66222500-9918-11ea-87f8-642193513b74.png)
### Use Case Description : Proses Pendaftaran Meteran
![UseCaseDescription-ProsesPendaftaranMeteran](https://user-images.githubusercontent.com/48080398/82188711-7d611280-9918-11ea-8902-fff95357710a.png)
### Use Case Description : Proses Melihat History Pembelian
![UseCaseDescription-ProsesMelihatHistoryPembelian](https://user-images.githubusercontent.com/48080398/82188774-94076980-9918-11ea-8dc6-a9865be0f417.png)


# Activity Diagram
### Activity Diagram : Login
![ActivityDiagram-Login](https://user-images.githubusercontent.com/48080398/82188834-abdeed80-9918-11ea-9432-539b7fee9097.png)
### Activity Diagram : Menampilkan Cuaca
![ActivityDiagram-MenampilkanCuaca](https://user-images.githubusercontent.com/48080398/82188883-c0bb8100-9918-11ea-9850-835f40448d29.png)
### Activity Diagram : Pembayaran Token
![ActivityDiagram-PembayaranToken](https://user-images.githubusercontent.com/48080398/82188937-d466e780-9918-11ea-939e-2d18d5e3db94.png)
### Activity Diagram : Pembayaran Tagihan
![ActivityDiagram-PembayaranTagihan](https://user-images.githubusercontent.com/48080398/82188968-e47ec700-9918-11ea-8c23-863b597ef335.png)

# Gantt Cart
![TeamGantt](https://user-images.githubusercontent.com/48080398/82191690-15f99180-991d-11ea-9fed-f47c7c783ede.png)

# Trello
![Trello](https://user-images.githubusercontent.com/48080398/82189835-44c23880-991a-11ea-9502-f2717d9041fb.PNG)


# Entity Relationship Diagram
![EntityRelationshipDiagram](https://user-images.githubusercontent.com/48080398/82189016-f6606a00-9918-11ea-96d2-e0692ecec471.png)

# Hasil Implementasi Perangkat Lunak
## Penjelasan Singkat
Kami telah membuat video berupa tampilan dari implementasi perangkat lunak yang telah kami buat. video ini menjadi bukti bahwa aplikasi kita sudah bisa dijalankan walau tidak maksimal. Kami berharap aplikasi kami bisa berguna kelak.
### Link Video
https://youtu.be/plRGSOh6ar4
