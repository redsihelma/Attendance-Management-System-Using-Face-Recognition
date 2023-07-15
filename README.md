## Attendance Management System Using Face Recognition 💻

Proyek ini melibatkan pembuatan sistem absensi yang memanfaatkan pengenalan wajah untuk menandai kehadiran, waktu masuk, dan waktu istirahat karyawan. Ini mencakup area seperti deteksi wajah, penyelarasan, dan pengenalan, bersamaan dengan pengembangan aplikasi web untuk memenuhi berbagai kasus penggunaan sistem seperti pendaftaran karyawan baru, penambahan foto ke dataset pelatihan, melihat laporan kehadiran, dll. Proyek ini dimaksudkan untuk berfungsi sebagai pengganti yang efisien untuk sistem kehadiran manual tradisional. Ini dapat digunakan di kantor perusahaan, sekolah, dan organisasi di mana keamanan sangat penting.

Proyek ini bertujuan untuk mengotomatisasi sistem absensi tradisional dimana kehadiran ditandai secara manual. Ini juga memungkinkan organisasi untuk mempertahankan catatannya seperti waktu masuk, waktu keluar, waktu istirahat dan kehadiran secara digital. Digitalisasi sistem juga akan membantu dalam visualisasi data yang lebih baik menggunakan grafik untuk menampilkan no. karyawan yang hadir hari ini, jumlah jam kerja masing-masing karyawan dan waktu istirahat mereka. Fitur tambahannya berfungsi sebagai pemutakhiran dan penggantian yang efisien atas sistem kehadiran tradisional.

## Lingkup proyek 🚀
Pengenalan wajah menjadi lebih menonjol di masyarakat kita. Ini telah membuat kemajuan besar di bidang keamanan. Ini adalah alat yang sangat efektif yang dapat membantu penegak rendah untuk mengenali penjahat dan perusahaan perangkat lunak memanfaatkan teknologi untuk membantu pengguna mengakses teknologi. Teknologi ini dapat dikembangkan lebih lanjut untuk digunakan di jalan lain seperti ATM, mengakses file rahasia, atau materi sensitif lainnya.
Server proyek ini sebagai dasar untuk proyek masa depan berdasarkan deteksi dan pengenalan wajah. Proyek ini juga mengonversi pengembangan web dan manajemen basis data dengan UI yang mudah digunakan. Dengan menggunakan sistem ini, setiap kantor perusahaan, sekolah dan organisasi dapat menggantikan cara tradisional mereka dalam menjaga kehadiran karyawan dan juga dapat menghasilkan laporan ketersediaan (kehadiran) mereka sepanjang bulan.

**Sistem ini terutama bekerja di sekitar 2 jenis pengguna**
1. Employee
2. Admin

**Fungsi berikut dapat dilakukan oleh admin: <br>**
• Login <br>
• Register new employees<br>
• Add employee photos ke training data set <br>
• Train model <br>
• Lihat laporan kehadiran semua karyawan di View attendance report. Kehadiran dapat disaring berdasarkan tanggal atau karyawan untuk lihatnya di By date dan By employee. <br>

**Fungsi-fungsi berikut dapat dilakukan oleh karyawan: <br>**
• Login <br>
• Tandai waktu masuk dan waktu habisnya dengan scanning wajah mereka <br>
• melihat laporan kehadiran mereka di View attendance report <br>

## Extraction of Facial Embeddings
face_recognition by Adam Geitgey

## Classification of Unknown Embedding 
using a Linear SVM (scikit-learn)

## cara menjalankan aplikasi ini:
 - di aplikasi ini menggunakan Django versi 3.1.8 bisa mengintall 
 atau menggunakan Python versi 3.6 atau yang lebih baru, dalam 
 aplikasi ini menggunakan Python versi 3.9.12 
 - buat environment untuk install modul modul yang di butuhkan setelah membuat env selanjutnya aktifkan environment tersebut, ketik ```pip install <nama-modul>```tanpa tanda petik atau ```pip install -r requirements.txt``` di dalam path penyimpanan aplikasi yaitu ```\<path penyimpanan aplikasi>\Attendance-System-Using-Face-Recognition``` untuk menginstall modul modul yang di butuhkan 
 - untuk run/menjalankan aplikasinya menggunakan CMD dengan mengubah
 pathnya di penyimpanan aplikasi yang tersimpan ```\<path penyimpanan aplikasi>\Attendance-System-Using-Face-Recognition``` dan mengaktifkan
 environment yang telah dibuat sebelumnya, selanjutnya ketik 
 ```python manage.py runserver``` jika berhasil akan menampilkan link localhost klik link tersebut dengan ```Ctrl + click``` untuk masuk ke halman utama/home, beda 
 lagi jika aplikasi sudah di hosting/di onlinekan

 ## perbedaan aplikasi ini dengan sebelumnya:
 - mengubah semua background dan semua logo dan menambahkan logo di home/tampilan utama
 - menambahkan back to andim di bagian View Attendance Reports dan di tulisan Attendance Dashboard tertanam link untuk kembali ke halaman utama View Attendance Reports jika ke halaman By Empliyee atau halaman By Date

## Thank You
- Author : [Nevil Parmar](https://nevilparmar.me)
- copier, modifier : [Reza Maulana Rizky](https://github.com/redsihelma)
