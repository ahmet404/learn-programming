## Tentang Version Control
### Apa itu Version Control?
**Version Control System** disebut juga **revision control system** atau **source code management** adalah sebuah sistem yang mencatat setiap perubahan yang terjadi pada sebuah berkas atau kumpulan berkas, dokumen, program komputer, website dan kumpulan informasi lain sehingga pada suatu saat anda dapat kembali ke salah satu versi dari berkas tersebut.

### Kegunaan Version Control System
- Dapat menyimpan \'rekaman / snapshot' perubahan pada berkas.
- Memungkinkan bekerja berkolaborasi dengan lebih baik.
- Mengetahui siapa yang melakukan dan kapan sebuah perubahan terjadi.
- Memungkinkan kita untuk kembali ke keadaan sebelum perubahan (checkout). 

### Jenis-Jenis Version Control System
1. **Local Version Control System**
![Gambar LVCs](img/local.png)
Melansir Geeks For Geeks, _local version control systems_ merupakan jenis VCS paling sederhana dan memiliki _database_ yang menyimpan semua perubahan pada _file_.  LCS juga merupakan salah satu alat VCS yang paling umum. Sistem ini mampu membuat set patch, atau perbedaan antara file, dalam format khusus pada sebuah disk. Dengan menambahkan semua patch, LCS dapat menciptakan bentuk orisinal dari semua file ketika seorang engineer atau developer membutuhkannya.

2. **Centralized Version Control System**
![Gambar CVCs](img/centralized.png)
Jenis version control system berikutnya adalah CVCS. Sistem satu ini kerap menjadi jembatan kolaborasi di antara para engineer dan developer. CVCS dapat memberikan informasi tentang apa yang dilakukan para engineer dan developer pada sebuah proyek. Hal ini memungkinkan database administrator untuk mengontrol pekerjaan yang harus dilakukan seluruh pihak dalam proyek tanpa terjadinya benturan dan miskomunikasi.  Cth: CVS, Subversion, dan Perforce.
3. **Decentralized Version Control System**
![Gambar DVCs](img/distributed.png)
DVCS mengandung banyak repositori. Sistem ini mendukung cara kerja di mana tiap pengguna memiliki repositori dan _copy_ dari pekerjaan mereka sendiri. Ketika pengguna melakukan perubahan, DVCS tidak akan memberi orang lain akses ke pada perubahan yang telah dibuat tersebut. Hal ini karena DVCS akan mencerminkan perubahan tersebut dalam repositori masing-masing pengguna dan mereka perlu mendorongnya agar terlihat pada repositori pusat. Intinya, DVCS mendorong budaya tanggung jawab pada tiap perubahan yang dilakukan masing - masing engineer dan developer. Cth: Git, Mercurial, Bazaar, Darcs.

