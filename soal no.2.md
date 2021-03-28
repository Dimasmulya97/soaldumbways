![Gambaran sebuah perbedaan AWS & Open stack](https://www.gangboard.com/wp-content/uploads/2019/05/aws-vs-open-stack.jpg)

# *Perbedaan antara AWS & OpenStack*
___
## Artikel ini mencakup semua informasi yang diperlukan untuk membantu anda membuat keputusan yang lebih baik. ini menjelaskn fitur-fitur yang disediakan oleh kedua penyedia layanan,perbandingan tabel mereka untuk pemahaman yang lebih baik dan perbandingan mendalam yang pada akhirnya akan memungkinkan anda untuk membuat pilihan yang tepat. Tabel perbandingan untuk OpenStack & AWS berdasarkan layanan yang ditawarkan oleh kedua perangkat lunak diberikan dibawah ini. Lihat sekilas layanan ini dan lihat apakah ada fitur yang menarik bagi anda.

| Offered Services | AWS | OpenStack |
| ---------------- | --- | --------- |
| Virtual Servers | EC2 | Nova Instance |
| Dockers | ECS | Magnum |
| Scalability | AWS Scaling | Heat with Scaling |
| Load Balancing | Elastic Load Balancing | LBaas |
| API | EC2 API | OpenStack API |
| GUI | Console | Horizon |
| Storage Object | S3 | Swift |
| Block Storage | EBS | Cinder |
| Networking | Networking | NEutron |
| Compute | VM | Instance |
| Security/Identity | I AM | Keystone |
| Orchestration | CloudFormation | Heat |
| Archiving | Glacier | Swift |
| Image Templetes | Amazon Machine Image | Glance |
| DNS Managemenet | Route 53 | Designate |
| Relational Database | RDS | Trove |
------

# **Komputasi**
### Untuk menghitung berarti menjalankan aplikasi apa pun di server virtual. Anda harus menyediakan CPU dan perangkat keras lain yang diperlukan bersama dengan aplikasi sistem Operasi yang sudah diinstal sebelumnya (atau tidak). Di keduanya, pengguna OpenStack dan AWS dapat mengunggah gambar mereka sendiri.
### AWS memiliki EC2, yang merupakan jaringan virtual yang dapat diskalakan dengan analitik data besar berbasis Xen dan EMR Hadoop. Sebaliknya, OpenStack menawarkan infrastruktur Iaas. Ini menskalakan secara horizontal dan dirancang untuk menskalakan pada perangkat keras tanpa persyaratan khusus.

---------

# **Jaringan**
### Penting untuk menghubungkan server Anda ke server internal maupun eksternal lainnya. Ini pada dasarnya berarti menghubungkan pengguna ke server virtual. Ketika fasilitas semacam itu ditawarkan kepada admin, dia harus memiliki hak untuk mengetahui siapa yang memiliki akses ke jaringan.
### AWS memiliki DNS scalable route 53, Amazon ELB (Elastic Load Balancing), dan, Amazon VPC (Virtual Private Cloud) yang memperluas kemampuannya untuk terhubung ke server perusahaan. AWS akan mengalokasikan alamat IP pribadi ke instans yang berjalan pada DHCP dan ELB hanya membantu dalam mendistribusikan lalu lintas masuk ke instans Amazon EC2.
### Openstacks LBaas dan jaringan datar VLAN memungkinkan pengelolaan alamat dan jaringan Ip secara otomatis maupun manual. Anda memiliki kekuatan untuk membuat fungsi jaringan dan jaringan.
-------


# **Pemantauan**
### Ketika datang ke layanan komputasi awan, Anda mungkin ingin tahu bagaimana sumber daya Anda digunakan. Pemantauan memungkinkan Anda melakukannya untuk pengguna individu dan menagih mereka sesuai dengan penggunaannya. OpenStack memiliki ceilometer dan AWS memiliki cloudwatch sebagai penyedia layanan pemantauan mereka.
### Baik itu OpenStack atau AWS, keduanya bekerja sama kecuali Anda akan memiliki kontrol yang lebih baik atas logistik dengan ceilometer. AWS cloudwatch dirancang khusus untuk memenuhi kebutuhan AWS. Layanan ini dapat digunakan untuk mencatat metrik dan mengumpulkan file log, Anda bahkan dapat mengatur tindakan untuk dieksekusi ketika kriteria yang ditentukan sebelumnya terpenuhi. Ini juga merupakan aspek penting untuk dipertimbangkan saat membandingkan AWS Vs OpenStack.

--------

# **Keamanan**
### Istilah ini pada dasarnya berarti kontrol akses atas server dan mesin Virtual. Setiap kali sebuah instance diluncurkan, grup keamanan terpisah harus tersedia untuk dilampirkan. Keamanan OpenStack tertinggal dari AWS dalam hal kondisi ini dan mungkin tidak memberikan rangkaian layanan yang diinginkan saat diperlukan. AWS menanamkan pendekatan yang lebih pribadi untuk mendapatkan akses ke instans yang dikunci oleh pengguna menjadikannya pemenang yang jelas antara AWS Vs OpenStack.

-----

# **Penyimpanan**
### Anda memerlukan dua jenis unit penyimpanan saat menggunakan komputasi awan - Block Storage dan Object Storage. Penyimpanan blok digunakan untuk menetapkan nilai ke server virtual untuk meningkatkan kapasitas mereka saat mencapai ambang batas serta mencadangkan server virtual. Penyimpanan objek berisi file media, gambar, dan sebagainya.
### AWS memiliki S3 dan OpenStack memiliki Swift sebagai layanan penyimpanan blok mereka sementara Cinder dan EBS adalah mitra penyimpanan objek mereka.

------

# **Identitas**
### Keystone untuk OpenStack dan IAM untuk AWS memutuskan fungsi identitas. Server identitas memungkinkan Anda untuk memiliki kendali atas siapa yang akan mengakses cloud Anda dengan menerapkan otentikasi multi-faktor. Ini juga dapat diintegrasikan dengan beberapa penyedia eksternal seperti AD atau LAPD.
### Ini adalah layanan utama yang harus disediakan oleh OpenStack dan AWS. Semua layanan lain berjalan sesuai dengan layanan dan aplikasi ini dan merupakan bagian dari fungsi utama.