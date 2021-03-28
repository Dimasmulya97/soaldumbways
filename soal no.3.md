![Gambar Git](https://3.bp.blogspot.com/-ZcUp-f8LtpE/WJhkSmZoDYI/AAAAAAAADzA/yCVxld7RX54uxKKBhY-0pI-TfOqmTaFugCPcB/s1600/git-petanikode.png)
-------

### Git adalah salah satu tool yang sering digunakan dalam proyek pengembangan software.
### Git bahkan menjadi tool yang wajib dipahami oleh programmer, karena banyak digunakan di mana-mana.
### Pada kesempatan ini kita akan belajar Git dari dasar.
### Artikel ini hanya akan membahas pengenalan Git saja. Untuk mempelajari Git lebih lanjut, saya sudah menyediakan link di bagian akhir.
-------

# **Mengenal Git**
### **Git** adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.
### Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
### Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

![Gambar sistem git](https://www.petanikode.com/img/git/sistem-git.png)

------

### Semua orang yang terlibat dalam pengkodean proyek akan menyimpan database Git, sehingga akan memudahkan dalam mengelola proyek baik online maupun offline.
### Dalam Git terdapat _merge_ untuk menyebut aktifitas penggabungan kode.
### Sedangkan pada **VCS (Version Control System)** yang terpusat… database disimpan dalam satu tempat dan setiap perubahan disimpan ke sana.

![Gambaran sistem VCS](https://www.petanikode.com/img/git/vcs-terpusat.png)
----

# __VCS terpusat memiliki beberapa kekurangan:__

* Semua tim harus terkoneksi ke jaringan untuk mengakses source-code;
* Tersimpan di satu tempat, nanti kalau server bermasalah bagaimana?
* Karena itu, Git hadir untuk menutupi kerkurangan yang dimiliki oleh VCS terpusat.

# __Apa yang dilakukan oleh Git?__
### Git sebenarnya akan memantau semua perubahan yang terjadi pada file proyek. Lalu menyimpannya ke dalam database.

### Sebelum menggunakan Git:

![Gambar revisi tanpa git](https://www.petanikode.com/img/git/revisi-tanpa-git.png)

### Setelah menggunakan Git:

![Gambaran revisi sesudah Git](https://www.petanikode.com/img/git/database-git.png)

------

### Apa perbedaannya?

#### Saat kita ingin menyimpan semua perubahan pada file, biasanya kita membuat file baru dengan “save as”. Lalu, file akan menumpuk dalam direktori proyek seperti pada ilustrasi di atas.

#### Tapi setelah menggunakan Git…

#### Hanya akan ada satu file dalam proyek dan perubahannya disimpan dalam database.

#### Git hanya akan menyimpan delta perubahannya saja, dia tidak akan menyimpan seluruh isi file yang akan memakan banyak memori.

#### Git memungkinkan kita kembali ke versi revisi yang kita inginkan.

# __Kenapa Git Penting Bagi Programmer?__

![gambaran git gabungan](https://www.petanikode.com/img/git/jutsu-kolaborasi.jpg)
------

#### Jadi selain untuk mengontrol versi, git juga digunakan untuk kolaborasi.

#### Saat ini Git menjadi salah satu tool terpopuler yang digunakan pada pengembangan software open souce maupun closed source.

#### Selain itu, berikut ini ada beberapa menfaat yang akan kamu rasakan setelah bisa menggunakan Git.

1. Bisa menyimpan seluruh versi source code;
2. Bisa paham cara kolaborasi dalam proyek;
3. Bisa ikut berkontribusi ke poryek open-source;
4. Lebih aman digunakan untuk kolaborasi, karena kita bisa tahu apa yang diubah dan siapa yang mengubahnya.
5. Bisa memahami cara deploy aplikasi modern;
6. Bisa membuat blog dengan SSG.
7. dan sebagainya…


