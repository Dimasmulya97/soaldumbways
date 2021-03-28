# **Apa perbedaan puppet, ansible, chef dan terraform?**
----
## Ansible adalah open-source software otomatisasi untuk manajemen konfigurasi sistem, software provisioning dan orchestrate deployment.

## Arsitektur Ansible adalah Agentless, artinya bisa berjalan tanpa agent (client-only), software otomatisasi lain seperti: Chef, Puppet, SaltStack itu memerlukan agent (client-server).

## Untuk pekerjaan Config Management saya lebih memilih Ansible dibanding yang lain karena ansible agentless. Software ini dapat digunakan di Linux, BSD maupun Mac “Unix-like system”.
-------

# **SEJARAH**

## Software Ansible didevelop oleh Michael DeHaan dengan bahasa Python, PowerShell, Ruby dan dirilis pada 20 Februari 2012 yang kemudian pada Oktober 2015 diakuisisi oleh Red Hat. License Proprietary / GNU-GPL.

# **Arsitektur Ansible**
## Berikut adalah overview dasar arsitektur ansible, gambar dibawah lebih mengarah bagaimana proses seorang system operation melakukan automation baik configuration maupun provisioning ke server dan cloud.

![Gambaran Arsitektur Ansible](https://www.lukmanlab.com/wp-content/uploads/2019/05/Ansible-Architechture-LukmanLAB.png)

# __Perbedaan Ansible, Chef, Puppet, SaltStach, CloudFormation dan Terraform__

## Tools dibuat mempunyai kelebihan dan kekurangan maupun tujuan masing-masing yang spesifik, bukan berarti yang banyak digunakan oleh kita itu merupakan tools yang terbaik untuk otomatisasi.
## Contoh kasusnya disini misal: _Ansible lebih condong ke Config Management dan Terraform lebih kepada Orchestration atau provisioning Cloud. Jadi beda tujuan antara keduanya_ .
## Meskipun ansilbe mempunya modul yang sudah dikembangkan dan dapat melakukan Orchestration terhadap Cloud seperti AWS, VMware dsb.

![Gambaran Perbedaan Ansible, Chef, Puppet, SaltStach, CloudFormation dan Terraform](https://www.lukmanlab.com/wp-content/uploads/2019/05/Ansilbe-Chef-Puppet-SaltStack-CloudFormation-Terraform-1024x388.png)
