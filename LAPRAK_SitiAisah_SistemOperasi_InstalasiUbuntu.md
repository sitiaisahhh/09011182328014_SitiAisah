<h1> LAPORAN PRAKTIKUM SISTEM OPERASI </h1>
<h2> PENDAHULUAN </h2>
<h3> LATAR BELAKANG </h3>
<p> Sistem operasi adalah komponen yang menghubungkan perangkat keras dengan perangkat lunak, mengelola sumber daya perangkat keras dan menyediakan platform untuk aplikasi berjalan. Di antara berbagai sistem operasi, Linux dikenal karena sifatnya yang open-source, fleksibel, dan aman. Ubuntu, salah satu distribusi Linux yang paling populer dan banyak digunakan, dikembangkan oleh Canonical Ltd. dan pertama kali dirilis pada tahun 2004. Ubuntu bertujuan untuk menyediakan sistem operasi yang mudah digunakan, stabil, dan gratis, dengan dukungan perangkat keras yang luas serta antarmuka yang ramah pengguna. Sebagai distribusi berbasis Debian, Ubuntu menawarkan fitur inovatif, termasuk pembaruan reguler dan dukungan jangka panjang (LTS) selama lima tahun, menjadikannya pilihan ideal untuk berbagai pengguna, dari pemula hingga profesional. Praktikum ini bertujuan untuk memberikan pemahaman tentang instalasi dan konfigurasi Ubuntu serta cara sistem operasi ini dapat meningkatkan efisiensi dan performa perangkat keras.</p>
<h3> TUJUAN </h3>
1.	Mengetahui prosedur instalasi pada sistem operasi Linux. <br/>
2.	Mampu menjalankan instalasi melalui Graphic User Interface (GUI) maupun Command Line Linux. <br/>
3.	Mampu menganalisis proses instalasi sistem operasi Linux. <br/>
<h3> ALAT DAN BAHAN </h3>
1. Laptop <br/>
2. Ubuntu 24.04 LTS <br/>
3. Virtual box <br/>
<h3> DASAR TEORI </h3>
<p> Sistem Operasi (Operating System) Sistem operasi adalah perangkat lunak yang mengelola perangkat keras komputer dan menyediakan layanan bagi aplikasi perangkat lunak. Sistem operasi bertindak sebagai perantara antara pengguna dan perangkat keras, memastikan operasi perangkat keras yang efisien dan manajemen sumber daya yang optimal.</p>
<p> Linux Linux adalah keluarga sistem operasi berbasis Unix yang dikembangkan dengan model open-source, yang berarti kode sumbernya tersedia untuk umum dan dapat dimodifikasi. Linux dikenal karena stabilitas, keamanan, dan fleksibilitasnya. Distribusi Linux berbeda-beda dalam hal antarmuka pengguna, manajemen paket, dan tujuan penggunaan.</p>
<p> Ubuntu Ubuntu adalah salah satu distribusi Linux yang paling populer, dikembangkan oleh Canonical Ltd. Ubuntu dikenal karena kemudahan penggunaannya, antarmuka grafis yang ramah pengguna, dan dukungan komunitas yang kuat. Versi terbaru Ubuntu seringkali mencakup pembaruan fitur, perbaikan keamanan, dan peningkatan performa.</p>
<h2> PEMBAHASAN </h2>
<h3> Proses Instalasi Ubuntu </h3>

1. Unduh Ubuntu 24.04 LTS dari Google dan unduh juga Rufus** (karena kita akan menggunakan flash disk, Rufus diperlukan untuk mentransfer Ubuntu ke flash disk). Selanjutnya, alokasikan 50 GB dari ruang penyimpanan yang ingin dipartisi di Disk Management untuk ruang penyimpanan Ubuntu.
2. Sesuaikan pengaturan BIOS untuk booting dan pastikan untuk menonaktifkan secure boot.
3. Setelah proses booting selesai, akan muncul opsi seperti pada gambar di bawah. Pilih "Try or Install Ubuntu" untuk memulai proses instalasi Ubuntu.<br/>
<img src="https://github.com/user-attachments/assets/c3150daa-f008-4cf2-ac23-3a00fea13e55" width=500/><br/>
4. pilih bahasa English untuk pilihan bahasanya lalu kemudian next. <br/>
<img src="https://github.com/user-attachments/assets/ea423a03-65b3-4df3-a6a2-5023742fe4b7" width=500/><br/>
5. Selanjutnya bagian ini langsung di next saja. <br/>
<img src="https://github.com/user-attachments/assets/0826ef62-13ad-4230-8eee-bd74898e0fab" width=500/><br/>
6. Untuk pilihan keyboard layout pilih English(US). <br/>
<img src="https://github.com/user-attachments/assets/2ef5ff62-7baa-4c96-a959-78d5872bec81" width=500/><br/>
7. Connect to internet boleh pilih seperti pada gambar jika ingin langsung terhubung ke internet. <br/>
<img src="https://github.com/user-attachments/assets/010ccb8e-b2bb-46bf-8fe8-7c17d08597c8" width=500/><br/>
8. Kemudian pilih Install Ubuntu. <br/>
<img src="https://github.com/user-attachments/assets/7031ad9b-565e-49d0-b079-1c1c32c63e33" width=500/><br/>
<img src="https://github.com/user-attachments/assets/9baec9e1-0606-4e5a-9907-327d5a08737d" width=500/><br/>
9. Lalu pilih interactive Ubuntu kemudian next. <br/>
<img src="https://github.com/user-attachments/assets/7d0fd9ec-b67f-448e-92fd-c560583503c8" width=500/><br/>
10.	Kemudian Pilih Default Selection.<br/>
<img src="https://github.com/user-attachments/assets/9a9bbdfe-f6d4-47b8-83aa-fd95bd96b460" width=500/><br/>
11.	Selanjutnya centang kedua pilihan.<br/>
<img src="https://github.com/user-attachments/assets/62fcc777-567a-46b9-ac07-c13db327671a" width=500/><br/>
12.	Pilih Erase disk and Install Ubuntu dan kita buat akun dan pasword kita.<br/>
<img src="https://github.com/user-attachments/assets/ee05f325-2ae6-432a-912b-0a2080da13d3" width=500/><br/>
13. Selanjutnya	kita pilih timezone jakarta kemudian next. <br/>
<img src="https://github.com/user-attachments/assets/b385c058-de16-4809-83ff-20fb7490f587" width=500/><br/>
14. Berikut ini masuk pada bagian intallasi klik install dan tunggu beberapa saat.  <br/>
<img src="https://github.com/user-attachments/assets/f42e20a7-b198-498f-bcbc-61eb9537fe59" width=500/><br/>
15. Setelah selesai proses installasi kita restart dan masuk dengan menggunakan kata sandi yang telah dibuat sebelumnya. <br/>
<img src="https://github.com/user-attachments/assets/b851d398-4119-4442-b00d-a9bec0a0e33e" width=500/><br/>
15. Dan berikut ini tampilan dari menu desktop Linux yang telah diinstal. <br/>
<img src="https://github.com/user-attachments/assets/ce544181-4aef-4180-9a8b-b2e92424a79b" width=500/><br/>

<h3> Analisis “/” Pada Opsi MountPoint </h3>
<p> Selama proses instalasi Linux Ubuntu, penting untuk memilih “/” (root) sebagai mount point karena direktori root adalah titik awal dari seluruh struktur sistem file di Linux. Direktori root adalah direktori tertinggi dalam hierarki sistem Linux, tempat semua file dan direktori lainnya berada di bawahnya. Semua komponen sistem operasi, termasuk kernel, file binary, pustaka, dan aplikasi, akan diinstal di bawah direktori root. Jika “/” tidak dipilih sebagai mount point, sistem operasi tidak akan mengetahui lokasi penyimpanan file-file penting tersebut. Memilih “/” sebagai mount point juga memungkinkan partisi utama untuk diakses oleh seluruh sistem, sehingga direktori penting seperti /home, /etc, dan /bin dapat diakses dengan benar. Ini sangat penting untuk memastikan sistem berjalan dengan baik setelah instalasi. </p>
<h3>	Penjelasan Tentang Ext4, Ext3, Swap, Ntfs, Fat32, Btrfs </h3>
Ext4 (Fourth Extended Filesystem): Ini adalah sistem file default di banyak distribusi Linux. Ext4 mendukung file dan partisi yang besar serta menawarkan berbagai fitur yang meningkatkan kecepatan dan stabilitas. Dibandingkan dengan Ext3, Ext4 lebih cepat dalam membaca dan menulis data, serta mendukung file hingga 16 Terabyte (TB) dan partisi hingga 1 Exabyte (EB). Ext4 juga memiliki fitur journaling yang membantu melindungi data dari kerusakan, meskipun fitur ini mungkin tidak diperlukan untuk penggunaan yang lebih sederhana. <br/> 
Ext3 (Third Extended Filesystem): Sistem file ini dikenal stabil dan memiliki fitur journaling untuk melacak perubahan data, yang membuatnya lebih aman jika terjadi crash. Namun, Ext3 tidak secepat dan seefisien Ext4 dalam hal kecepatan dan pengelolaan ruang. <br/>  Swap:
Penggunaan: Berfungsi sebagai area penyimpanan tambahan untuk RAM di sistem Linux.<br/>  
Kelebihan: Membantu sistem untuk menjalankan aplikasi lebih besar dari kapasitas RAM yang tersedia dengan menyimpan data sementara di disk.<br/>  
Kekurangan: Akses ke swap lebih lambat dibandingkan RAM, sehingga kinerja sistem bisa terpengaruh jika terlalu bergantung pada swap.
 <br/> 
NTFS (New Technology File System):
Penggunaan: Sistem file utama untuk Windows NT dan sistem operasi yang lebih baru (seperti Windows 10/11).<br/> 
Kelebihan: Mendukung fitur seperti enkripsi, kompresi, dan hak akses file yang lebih canggih dibandingkan FAT32. Memungkinkan volume dan file yang sangat besar.<br/> 
Kekurangan: Kurang kompatibel dengan sistem operasi non-Windows, meskipun dukungan untuk baca/tulis NTFS ada di beberapa sistem Linux. <br/> 
FAT32 (File Allocation Table 32):
Penggunaan: Sistem file yang lebih tua yang digunakan di berbagai sistem operasi, termasuk Windows, macOS, dan Linux.<br/> 
Kelebihan: Kompatibel dengan hampir semua sistem operasi, ideal untuk perangkat penyimpanan portabel seperti USB flash drive.<br/> 
Kekurangan: Tidak mendukung file yang lebih besar dari 4 GB dan volume lebih besar dari 8 TB. Tidak memiliki fitur seperti journaling.<br/> 
Btrfs (B-tree File System): <br/>
Penggunaan: Sistem file yang relatif baru untuk Linux, dirancang untuk menggantikan ext4. <br/>
Kelebihan: Menawarkan fitur canggih seperti snapshot, pengendalian kesalahan, dan kompresi data. Fleksibel dan mendukung pengelolaan volume yang lebih kompleks. <br/>
Kekurangan: Masih dianggap kurang stabil dibandingkan ext4 dan mungkin tidak selalu cocok untuk semua jenis penggunaan.<br/>

<h2> PENUTUP </h2>
<h3> KESIMPULAN </h3>
<p>Sistem operasi memainkan peran krusial sebagai penghubung antara perangkat lunak dan perangkat keras. Tanpa adanya sistem operasi, perangkat keras tidak dapat berfungsi secara maksimal karena tidak ada pengelolaan interaksi antar komponen komputer. Dengan sistem operasi, berbagai aplikasi dapat berjalan dengan efisien dan mengurangi potensi gangguan. Dalam praktikum ini, fokus kita adalah pada sistem operasi Linux, khususnya distribusi Ubuntu. Melalui praktikum ini, kita telah mempelajari proses instalasi Linux Ubuntu dan menganalisis berbagai tahapan yang terlibat dalam proses instalasi tersebut.</p>
