# __Apa Itu DevOps?__

![Gambaran Devops](https://www.jagoanhosting.com/blog/wp-content/uploads/2020/05/gambar-11.png)
----

### Dalam software development, DevOps adalah salah satu pendekatan development yang melakukan pengembangan, testing, integrasi, monitoring secara terus menerus atau on-the-fly. Contohnya, jika kamu sering main game, tidak jarang kita mendengar istilah “alpha” atau “beta”. Jika sebuah software masih berlabel alpha atau beta, bisa dipastikan development software tersebut belum sepenuhnya selesai. 
### Manfaat dari Implementasi CI/CD Pipeline
#### Jika kamu adalah seorang software developer, pastinya kamu ingin software yang dibuat menjadi lebih mudah menjangkau customer, bukan? Justru karena itu, CI/CD Pipeline berfungsi sebagai pendorong proses pengembangan software sekaligus mengurangi resiko dalam setiap tahap pengembangan dan lebih mudah mencapai tujuan akhir – mencapai customer.

### Berikut beberapa manfaat implementasi CI/CD Pipeline:

1. __Mendapatkan Feedback Lebih Cepat Menggunakan CI Tools__
### Untuk setiap code yang ditulis, setiap tes akan berjalan secara bersamaan untuk menjaga kestabilan pengembangan. Feedback yang lebih cepat membantu untuk memeriksa kualitas dan kegunaan dari setiap code.

* __Visibilitas yang Lebih Baik__
### Menggunakan CI/CD Pipeline, keseluruhan dari pengembangan, hasil tes, dan masalah dapat lebih mudah dianalisis. Sifat CI/CD Pipeline yang transparan ini memungkinkan developer untuk mengatur perubahan dan menghindari kerusakan pada software.

* __Deteksi Bug Lebih Awal__
### CI/CD memiliki fungsi tes otomatis, melalui tes otomatis ini akan lebih mudah mendeteksi bug pada tahap pengembangan awal, jadi kamu tidak perlu khawatir dikejutkan dengan error pada detik-detik terakhir.

__Tahap-Tahap dalam Implementasi CI/CD Pipeline__

![gambar](https://scontent-sin6-1.xx.fbcdn.net/v/t1.0-9/165477843_1329573970755756_6947484412504030955_n.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFsa29QM-2lRZ6Zvfzj7g3lsyy2ZNVkWg6zLLZk1WRaDhoDKDEz5zLbFWq3-f9P8qAvH14eac-Bb98PVZLY4qdj&_nc_ohc=mKgNfcOp7e0AX-D68pE&_nc_ht=scontent-sin6-1.xx&oh=b95083f35c3e05225797b8e9082cfd83&oe=6083498C)
[Pencet ini iya! untuk liat fotonya](https://scontent-sin6-1.xx.fbcdn.net/v/t1.0-9/165477843_1329573970755756_6947484412504030955_n.jpg?_nc_cat=100&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFsa29QM-2lRZ6Zvfzj7g3lsyy2ZNVkWg6zLLZk1WRaDhoDKDEz5zLbFWq3-f9P8qAvH14eac-Bb98PVZLY4qdj&_nc_ohc=mKgNfcOp7e0AX-D68pE&_nc_ht=scontent-sin6-1.xx&oh=b95083f35c3e05225797b8e9082cfd83&oe=6083498C)
----

### Gambar di atas adalah gambaran tentang arus dari pengembangan software menggunakan CI/CD Pipeline, dan bagaimana software akan bergerak dari tahap ke tahap hingga bisa diterbitkan atau digunakan customer. Berikut adalah penjelasan dari setiap proses CI/CD Pipeline.

1. Developer akan menulis code yang akan dieksekusi melalui __Version Control system__ (contohnya git, svn, dsb.)
2. Setelah itu, software tersebut akan memasuki tahap __Build__. Pada tahap ini, developer akan melanjutkan codenya, code tersebut akan dikembalikan ke __Version Control__ untuk pembaruan. Code baru dan yang mula ditulis akan digabungkan, dan akan di-compile menggunakan Compiler.
3. Setelah tahap __Build__ selesai, kamu akan memasuki tahap __Testing__. Pada tahap ini akan dilakukan berbagai jenis tes untuk menguji kelayakan dari software.
4. Setelah tahap __Testing__ selesai, akan dimulai tahap __Deploy__. Pada tahap __Deploy__, kamu akan menjalankan software ke staging server atau test server. Staging server atau test server berlaku sebagai simulasi dan kamu bisa melihat code atau software melalui simulator tersebut.
5. Jika tahap __Deploy__ berhasil, kamu akan berlanjut ke tahap __Auto Test__. Jika keseluruhan software yang dikembangkan sudah dapat berjalan baik, maka software kamu sudah dapat dijalankan ke produksi __(Deploy to Production)__.
6. Dalam setiap tahap, jika ada error dan semacamnya, kamu bisa menghubungi tim developer untuk membenarkan software tersebut, ini disebut sebagai __Production Feedback__. Developer akan memperbarui versi melalui __Version Control__, dan setiap tahap di atas akan berulang kembali. Siklus tersebut akan berulang sebanyak mungkin hingga diperoleh code yang dapat dijalankan ke server produksi, di mana kita dapat mengukur dan memvalidasi code. __(Measure + Validate)__.


# __Tools untuk proses CI/CD__
### Dalam implementasi CI/CD Pipeline, menggunakan tools dapat melakukan automasi CI/CD dan memastikan software yang dikembangkan dapat diproduksi dengan baik.

1. __Open-Source Tools__
### Pada beberapa konteks bisnis atau permintaan customer, kamu bisa menyesuaikan budget dengan menggunakan open-source tools untuk melakukan automasi pada proses CI/CD. Contohnya Jenkins.

* __Cloud atau layanan Self-Hosting__
### Untuk melakukan self-host pada aplikasi CI/CD kamu, tools seperti Jenkins atau Cruise Control bisa membantu kamu untuk setup, mengatur, dan memonitor aplikasi lebih efektif.

* __Build Status__
### Sangat penting buat kamu untuk memilih tools yang memudahkan kamu memonitor keseluruhan proses (transparan). Contohnya, melalui notifikasi, email, atau bentuk komunikasi lainnya.

## __Tantangan dalam CI/CD__
### Meski CI/CD digambarkan sebagai metode development yang sangat efektif dan efisien, tetapi juga harus kamu perhatikan tantangan-tantangan yang mungkin saja ada ketika kamu melakukan implementasi CI/CD Pipeline. Contohnya, strategi disiplin antara developer untuk mengidentifikasi masalah, jika tidak dapat berjalan baik, sistem feedback dari CI/CD tidak akan berfungsi baik pula.

### Dengan adanya versi-versi baru yang dikembangkan pada setiap tahap, terutama jika sering ditemukan error atau kesalahan, sangat besar kemungkinannya untuk membuat proses development jauh lebih lambat dari yang ditargetkan. Tantangan yang sering sekali ditemukan adalah sumber daya dan tim developer yang cenderung tidak bisa beradaptasi pada tools-tools lain.