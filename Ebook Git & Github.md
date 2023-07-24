## Tentang Version Control

### Pengertian Version Control System

**Version Control System** disebut juga **revision control system** atau **source code management** adalah sebuah sistem yang mencatat setiap perubahan yang terjadi pada sebuah berkas atau kumpulan berkas, dokumen, program komputer, website dan kumpulan informasi lain sehingga pada suatu saat anda dapat kembali ke salah satu versi dari berkas tersebut.

### Manfaat Version Control System

- Dapat menyimpan \'rekaman / snapshot' perubahan pada berkas.
- Memungkinkan bekerja berkolaborasi dengan lebih baik.
- Mengetahui siapa yang melakukan dan kapan sebuah perubahan terjadi.
- Memungkinkan kita untuk kembali ke keadaan sebelum perubahan (checkout).

### Fungsi Version Control System

Berikut beberapa fungsi dari Version Control System:

- **Tracebility**  
   Tracebility adalah mekanisme yang menyediakan bukti semua revisi dan perubahan yang dilakukan dalam satu periode waktu. Hal ini memungkinkan pengguna mengidentifikasi pengembangan file melalui berbagai tahapannya. VCS memungkinkan pengguna untuk melacak kontribusi yang dibuat oleh beberapa pengembang dari salinan asli ke berbagai versi yang telah diperbaiki dan, akhirnya, ke versi final.

  Selain itu, anggota tim juga bisa mengidentifikasi urutan perubahan yang dilakukan. Hal ini memungkinkan mereka untuk membuat katalog berbagai perubahan yang dapat membantu memudahkan mereka dalam mengidentifikasi perubahan.

  Ketika seorang developer mengerjakan draft terbaru, tim dapat dengan mudah memahami tujuan dataset jika memiliki riwayat dokuman yang mudah diakses. Hal ini memungkinkan pengembang untuk membuat perubahan dengan lancar yang sesuai dengan tujuan jangka panjang proyek.

- **Efficiency**  
   Version control mendorong pengembangan dokumen yang efisien. Tim developer bekerja untuk menyederhanakan proses yang kompleks dan menciptakan ruang lingkup yang lebih besar untuk otomatisasi dan konsistensi. Proses yang kompleks ini diimplementasikan secara bertahap melalui versi yang diperbarui. Versi yang diperbarui memungkinkan pengembang untuk kembali ke versi sebelumnya ketika mereka mendeteksi kesalahan. Dengan begitu, pengujian menjadi lebih mudah karena masalah bisa terdeteksi lebih cepat .

- **Riwayat Dokumen**  
   Riwayat dokumen memberikan informasi yang sangat berharga tentang editor beserta tanggal pengeditannya. Dengan adanya riwayat dokumen, dapat mempermudah mendapatkan informasi mengenai tujuan dari perubahan yang dilakukan. Informasi dalam riwayat dokumen, akan mempengaruhi pengembang yang bekerja pada versi terbaru domana VCS menyediakan informasi yang dapat membantu memecahkan masalah yang dialami pada versi sebelumnya.

  Kemampuan untuk mengidentifikasi penulis dokumen memungkinkan tim developer yang sedang mengembangkan proyek untuk menautkan dokumen ke kontributor tertentu. Informasi yang diperoleh memungkinkan tim untuk menemukan pola-pola yang dapat membantu memperbaiki bug. Hal ini akan membantu meningkatkan fungsionalitas perangkat lunak secara keseluruhan.

- **Branching dan Merge**  
   Version Control memungkinkan anggota tim untuk mengerjakan dokumen yang sama secara bersamaan secara independen sehingga tidak akan memengaruhi kontribusi sesama kolaborator. Setiap kontributor yang bekerja pada aliran perubahan independen biasanya disebut sebagai cabang.

  Cabang memungkinkan setiap anggota tim untuk bekerja pada proyek yang sama menggunakan beberapa stream (cabang). Cabang-cabang ini bersifat otonom satu sama lain.

  Hal ini memungkinkan pemberdayaan tim untuk menggabungkan pekerjaan independen mereka. Percabangan biasanya diadopsi di segmen-segmen dalam tim yang memiliki alur kerja yang berbeda.

- **Pengurangan Duplikasi dan Kesalahan**  
   Version Control dapat mengurangi duplikasi beberapa versi atau versi yang sudah ketinggalan zaman dari dokumen tertentu. Pada dasarnya, dengan adanya vcs, akan mengurangi kesalahan yang muncul akibat informasi yang saling bertentangan yang ditampilkan melalui beberapa dokumen.

- **Management Overview**  
   Version Control memungkinkan manajemen untuk memperoleh perspektif yang komprehensif tentang perkembangan proyek. Pihak manajemen dapat memantau penulis, tujuan perubahan, jadwal kemajuan, dan dampak perubahan terhadap tujuan jangka panjang dokumen.

  Hal ini membantu manajemen untuk mengidentifikasi masalah berulang yang mungkin berasal dari anggota tim tertentu.

- **Identitas**  
   Version Control memungkinkan tim untuk menganalisis penghapusan, pengeditan, dan pembuatan kumpulan data yang dibuat setelah dibuatnya salinan asli.

  Hal ini memberikan kejelasan pada tim pengembangan perangkat lunak bahwa versi dokumen yang berbeda dapat dibedakan satu sama lain. Jadi, mudah untuk mengidentifikasi versi terbaru.

### Jenis-Jenis Version Control System

1.  **Local Version Control System**
    ![Gambar LVCs](img/local.png)
    Local version control system adalah basis data lokal yang terletak di local computer, yang merupakan tempat setiap perubahan file disimpan sebagai patch. Setiap kumpulan patch hanya berisi perubahan yang dibuat pada file dari versi terakhirnya.

    Untuk melihat tampilan file pada saat tertentu, perlu menambahkan semua patch yang relevan ke file secara beururtan hingga saat itu.

    Masalah utama dari jenis VCS ini adalah semua datanya disimpan secara lokal, jadi jika terjadi sesuatu pada basis data lokal, semuat patch yang disimpan akan hilang dan semua perubahan yang dibuat setelah versi tersebut akan hilang. Selain itu, kolaborasi antar pengembang atau tim sangat sulit atau hampir tidak mungkin dilakukan.

2.  **Centralized Version Control System**
    ![Gambar CVCs](img/centralized.png)
    Centralized version control memiliki server tunggal yang berisi semua versi file. Hal ini memungkinkan beberapa klien untuk mengakses file di server secara bersamaan dengan mengambil file dari komputer lokal atau mengirimkannya ke server dari komputer lokal. Dengan cara ini, semua orang dapat mengetahui apa yang dilakukan oleh orang lain dalam proyek.

    Dalam struktur ini, administrator memiliki kendali atas siapa yang dapat melakukan apa. Hal ini memungkinkan kolaborasi yang mudah dengan pengembang lain atau tim.

    Masalah terbesar dari struktur ini adalah semuanya disimpan di server terpusat. Jika terjadi sesuatu pada server tersebut, tidak ada yang bisa menyimpan perubahan, menarik file, atau berkolaborasi sama sekali.

3.  **Decentralized Version Control System**
    ![Gambar DVCs](img/distributed.png)

    Dengan struktur VCS ini, klien tidak hanya bisa melihat cuplikan file terbaru dari server, tetapi juga meniru repositori secara penuh, termasuk riwayat lengkapnya. Dengan demikian, setiap orang yang berkolaborasi dalam sebuah proyek memiliki salinan lokal dari keseluruhan proyek, meiliputi basis data lokal mereka sendiri dengan riwayat lengkapnya.

    Dengan model ini, jika server tidak tersedia atau mati, repositori klien mana pun dapat mengirimkan salinan versi proyek ke klien lain atau kembali ke server saat server tersedia.
