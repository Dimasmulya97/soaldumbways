# **Pengertian tentang apa itu devops sebuah perusahaan?**
----

![Gambaran devops](https://www.dicoding.com/blog/wp-content/uploads/2020/06/apa-itu-devops-1024x527.png)

### DevOps merupakan singkatan dari dua kata yaitu Development dan Operation. Di mana kedua kata tersebut bermakna “operasional pengembang”. Seperti yang disebutkan sebelumnya, DevOps adalah sebuah prinsip developer untuk mengkoordinasikan antar tim yaitu tim development dengan tim operations dengan efektif dan efisien.

### DevOps merupakan singkatan dari dua kata yaitu Development dan Operation. Di mana kedua kata tersebut bermakna menggabungkan proses development/pengembangan dari sebuah sistem/aplikasi dengan operation/operasional. Seperti yang disebutkan sebelumnya, DevOps adalah sebuah prinsip developer untuk mengkoordinasikan antar tim yaitu tim development dengan tim operations dengan efektif dan efisien.
### Pola pikir yang dibentuk oleh DevOps adalah koordinasi antar tim yang dapat dilakukan dengan cara singkat sehingga tidak membutuhkan banyak pertanyaan. Tim operation atau development cukup mengonfigurasi beberapa komponen yang dibutuhkan melalui prosedur yang dibuat.

### Tentunya koordinasi yang diterapkan pada DevOps membutuhkan sebuah tools. Banyak tools yang bisa kamu gunakan, salah satunya adalah Source Code Management (SCM) yang biasa digunakan secara umum oleh tim development. Produk SCM yang paling terkenal adalah Git, ditemani oleh Source Code Repository (SCR) seperti GitHu, GitLab, Bitbucket, atau yang lainnya. Namun SCM saja tak cukup untuk mengomunikasikan antara tim development dengan tim operational.

### Agar tim operational dapat mengetahui permasalahn yang terjadi, biasanya akan dihubungkan ke Product Management Software, seperti Jira. Melalui Product Management Software, tim operation dapat mengetahui berbagai permasalahan yang terjadi pada sistem/aplikasi. Sehingga antara pihak development dengan operational akan saling terhubung satu sama lain.
-----

# __Tujuan DevOps__

![tujuan devops](https://www.dicoding.com/blog/wp-content/uploads/2020/06/tujuan-devops-1024x506.png)

-----

## DevOps bertujuan untuk meningkatkan kolaborasi antara tim development dan tim operation dari mulai perencanaan hingga aplikasi/fitur ter-deliver ke pengguna. Semua itu harus dilakukan secara otomatis agar:

1. Meningkatkan deployment frequency.
2. Meningkatkan waktu pemasaran.
3. Menurunkan tingkat kegagalan pada rilisan terbaru.
4. Mempersingkat waktu perbaikan.
5. Meningkatkan waktu pemulihan.

## Menurut laporan State of DevOps pada tahun 2015, organisasi IT yang menerapkan DevOps menghasilkan kinerja 30x lebih tinggi dengan 200x efisiensi waktu, kegagalan 60x lebih sedikit, dan proses pemulihan 168x lebih cepat.
-----

# **Tools yang Digunakan DevOps**

![Tools DevOps](https://www.dicoding.com/blog/wp-content/uploads/2020/06/tools-devops-1024x576.png)

## Melalui berbagai referensi, ternyata ada banyak alat bantu untuk menerapkan DevOps yang harus kamu tahu.

## #1 Source Code Management
### Melalui sumber repository, antar developer dapat memeriksa dan mengubah kode tanpa perlu saling menulis satu sama lainnya. Source control ini mungkin telah ada sejak 40 tahun yang lalu, tetapi ini merupakan komponen utama dari Continuous Integration atau CI.

## Adapun contoh produk yang berfungsi sebagai SCM yaitu Git, Subversion, Cloudforce, Bitbucket, dan TFS.

## #2 Build Server
### Build server adalah alat otomatisasi yang mengkompilasi kode dalam SCR (Source Code Repository) ke dalam basis kode yang dapat dieksekusi. Alat ini bisa kamu temukan seperti Jenkins, SonarQube, dan Artifactory.

## #3 Configuration Management
### Manajemen konfigurasi berguna untuk menetapkan konfigurasi pada server atau lingkungannya. Alat yang populer biasa kamu temukan seperti Puppet dan Chef.

## #4 Virtual Infrastructure
### Amazon Web Services dan Microsoft Azure adalah contoh infrastruktur virtual. Virtual Infrastructure ini disediakan oleh vendor cloud yang menjual insrastruktur atau Platform as a Service (PaaS). Infrastruktur ini memiliki API yang memungkinkan kamu membuat mesin baru yang terprogram dengan alat manajemen konfigurasi.

### Ada juga private cloud di mana private infrastructure virtual memungkinkan kamu menjalankan cloud di hardware sebagai data terpusat.

### Alat ini dikombinasikan dengan alat otomatisasi untuk memberdayakan organisasi yang melatih DevOps dengan kemampuan konfigurasi server tanpa jari di atas keyboard. Jika ingin menguji kode baru, cukup mengirimkan kode ke infrastruktur cloud untuk membangun lingkungan. Kemudian tes dijalankan tanpa adanya campur tangan manusia.

## #5 Test Automation
### Test automation sebenarnya sudah ada sejak lama. Pengujian yang diadopsi oleh DevOps berfokus pada pengujian otomatis melalui pipeline build untuk memastikan bahwa build deployable sudah dilakukan. Tools populer untuk tahapan ini adalah Selenium dan Air.

## **KEGIATAN DEVOPS** 

![Kegiatan devops](https://www.dicoding.com/blog/wp-content/uploads/2020/06/DevOps-1024x580.png)

# #1 Continuous Integration
### Continuous Integration merupakan layanan yang diberikan DevOps untuk melakukan build dan automation testing. Kegiatan ini dikerjakan dengan menggunakan tools berupa Source Code Repository (SCR) untuk menemukan error code dan fixed code.

# #2 Continuous Delivery
### Continuous Delivery selalu bekerja di dalam software development untuk merubah kode. Proses ini dilakukan setelah Continuous Integration untuk menambah update lebih banyak untuk aplikasi yang sedang berjalan.

# #3 Continuous Deployment
### Setelah proses Continuous Integration-Delivery sudah dinyatakan dengan baik, tim development dapat melihat perubahan yang terjadi pada environment test / environment development / environment production.

# #4 Configuration Management
### Proses ini berkaitan dengan system engineering yang bertujuan untuk maintain konfigurasi sebuah produk. Configuration Management memungkinkan otomatisasi dan standardisasi konfigurasi produk.

# #5 Infrastructure as a Code (IAAC)
### IAAC adalah pekerjaan yang mana infrastruktur suatu produk didefinisikan melalui kode yang dapat diprogram, distandarisasi, dan mudah dalam duplikasi. Melalui IAAC, tim development dapat menambah mesin melalui satu baris kode.

# #6 Monitoring
### Produk IT menjadi sangat baik karena adanya proses monitoring saat produk tersebut digunakan oleh pengguna. Tujuannya adalah untuk mengetahui bagaimana perubahan yang ada pada kode cukup berdampak pada produk dan penggunanya.

# #7 Logging
### Centralized logging menjadi hal yang tidak dapat dipisahkan dari kegiatan DevOps. Dengan menerapkan log aplikasi, kita developer bisa mengetahui produk yang dibuat berjalan dengan baik atau tidak.

# Kesimpulan
### DevOps adalah instrumen lingkungan kerja pada perusahaan IT yang sedang berkembang saat ini. Prinsip ini dibuat dan digunakan untuk mengatasi berbagai permasalahan yang ada perusahaan IT untuk mengatur alur source code dalam hal pengembangan dan operasional.

| “Kepemimpinan yang efektif adalah mengutamakan hal terpenting. Manajemen yang efektif adalah disiplin dan just do it.” (Stephen Covey) |

### Saat ini, DevOps Engineer menjadi salah satu profesi yang sedang berkembang dan prospek di masa mendatang. Kamu hanya cukup memenuhi persyaratan dan skill yang dibutuhkan perusahaan melalui rekrutmen kerja