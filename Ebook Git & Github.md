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

- **Efficiency**  
   Version control mendorong pengembangan dokumen yang efisien. Tim developer bekerja untuk menyederhanakan proses yang kompleks dan menciptakan ruang lingkup yang lebih besar untuk otomatisasi dan konsistensi. Proses yang kompleks ini diimplementasikan secara bertahap melalui versi yang diperbarui. Versi yang diperbarui memungkinkan pengembang untuk kembali ke versi sebelumnya ketika mereka mendeteksi kesalahan. Dengan begitu, pengujian menjadi lebih mudah karena masalah bisa terdeteksi lebih cepat .

- **Riwayat Dokumen**  
   Riwayat dokumen memberikan informasi yang sangat berharga tentang editor beserta tanggal pengeditannya. Dengan adanya riwayat dokumen, dapat mempermudah mendapatkan informasi mengenai tujuan dari perubahan yang dilakukan. Informasi dalam riwayat dokumen, akan mempengaruhi pengembang yang bekerja pada versi terbaru domana VCS menyediakan informasi yang dapat membantu memecahkan masalah yang dialami pada versi sebelumnya.

- **Branching dan Merge**  
   Version Control memungkinkan anggota tim untuk mengerjakan dokumen yang sama secara bersamaan secara independen sehingga tidak akan memengaruhi kontribusi sesama kolaborator. Setiap kontributor yang bekerja pada aliran perubahan independen biasanya disebut sebagai cabang.

- **Pengurangan Duplikasi dan Kesalahan**  
   Version Control dapat mengurangi duplikasi beberapa versi atau versi yang sudah ketinggalan zaman dari dokumen tertentu. Pada dasarnya, dengan adanya vcs, akan mengurangi kesalahan yang muncul akibat informasi yang saling bertentangan yang ditampilkan melalui beberapa dokumen.

- **Management Overview**  
   Version Control memungkinkan manajemen untuk memperoleh perspektif yang komprehensif tentang perkembangan proyek. Pihak manajemen dapat memantau penulis, tujuan perubahan, jadwal kemajuan, dan dampak perubahan terhadap tujuan jangka panjang dokumen.

- **Identitas**  
   Version Control memungkinkan tim untuk menganalisis penghapusan, pengeditan, dan pembuatan kumpulan data yang dibuat setelah dibuatnya salinan asli.


### Jenis-Jenis Version Control System

1.  **Local Version Control System**
    ![Gambar LVCs](img/local.png)
    Sistem kontrol versi lokal adalah sistem yang menyimpan riwayat perubahan perangkat lunak secara lokal di komputer pengguna. Ini berarti bahwa semua perubahan disimpan di dalam direktori proyek yang sama di mana pengembang bekerja. Sistem ini biasanya sederhana dan cocok untuk pengembangan perangkat lunak kecil atau proyek pribadi.

	Contoh paling sederhana dari sistem kontrol versi lokal adalah penggunaan salinan manual dari file proyek dengan penamaan berbeda-beda untuk setiap versi. Sebagai alternatif, alat seperti RCS (Revision Control System) dapat digunakan untuk mengotomatisasi proses ini dengan menyimpan setiap revisi dalam file terpisah di dalam direktori proyek.

	Meskipun sederhana, sistem kontrol versi lokal memiliki keterbatasan dalam hal kolaborasi dan keamanan data. Untuk proyek yang lebih besar atau tim yang lebih besar, sistem kontrol versi terdistribusi atau terpusat mungkin

2.  **Centralized Version Control System**
    ![Gambar CVCs](img/centralized.png)
    Centralized version control memiliki server tunggal yang berisi semua versi file. Hal ini memungkinkan beberapa klien untuk mengakses file di server secara bersamaan dengan mengambil file dari komputer lokal atau mengirimkannya ke server dari komputer lokal. Dengan cara ini, semua orang dapat mengetahui apa yang dilakukan oleh orang lain dalam proyek.

    Dalam struktur ini, administrator memiliki kendali atas siapa yang dapat melakukan apa. Hal ini memungkinkan kolaborasi yang mudah dengan pengembang lain atau tim.

    Masalah terbesar dari struktur ini adalah semuanya disimpan di server terpusat. Jika terjadi sesuatu pada server tersebut, tidak ada yang bisa menyimpan perubahan, menarik file, atau berkolaborasi sama sekali.

3.  **Decentralized Version Control System**
    ![Gambar DVCs](img/distributed.png)

    Dengan struktur VCS ini, klien tidak hanya bisa melihat cuplikan file terbaru dari server, tetapi juga meniru repositori secara penuh, termasuk riwayat lengkapnya. Dengan demikian, setiap orang yang berkolaborasi dalam sebuah proyek memiliki salinan lokal dari keseluruhan proyek, meiliputi basis data lokal mereka sendiri dengan riwayat lengkapnya.

    Dengan model ini, jika server tidak tersedia atau mati, repositori klien mana pun dapat mengirimkan salinan versi proyek ke klien lain atau kembali ke server saat server tersedia.
